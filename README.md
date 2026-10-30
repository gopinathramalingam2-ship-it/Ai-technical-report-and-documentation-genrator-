# AI Technical Report and Documentation Generator

**Capstone:** CAPSTONE 10  
**ECE demonstration project:** Automatic Street Light Using an LDR

## What this package contains
- `report/`: editable DOCX and PDF technical report.
- `automation/`: Python script that converts supplied lab notes (JSON) into a Markdown report outline.
- `data/`: editable lab-notes JSON, observation CSV and time/quality comparison workbook.
- `prompts/`: reusable prompts for abstract, introduction, methodology, results, conclusion, README and verification.
- `presentation/`: 7-slide PowerPoint.
- `verification/`: checklist, error log template and responsible-AI notes.
- `diagrams/`: simple block diagram.

## Important evidence note
No real prototype measurements were provided. The package does **not** claim that a physical circuit was built or tested. Replace all `NOT PROVIDED` fields with your own measured data and add your actual circuit diagram/photos before submitting.

## Run the automation
Requires Python 3.8 or newer. No third-party packages are required.

```bash
python automation/generate_report.py --input data/lab_notes.json --output generated_report.md
```

The script only formats the information supplied in the JSON file. It does not invent readings.

## Suggested workflow
1. Build or select your existing ECE project and collect actual notes/data.
2. Fill `data/lab_notes.json` and `data/observations.csv`.
3. Run the Python automation.
4. Use prompts in `prompts/prompt_library.md` to draft sections.
5. Verify every technical value against your actual circuit, datasheet, simulation or lab notebook.
6. Fill the comparison workbook with actual time and quality scores.
7. Update the report and slides with your details.
8. Follow your college’s AI-use and citation rules.

## Submission checklist
- [ ] Student/institution details completed.
- [ ] Actual circuit diagram and prototype/simulation evidence inserted.
- [ ] Actual component values and supply ratings checked.
- [ ] Observation table filled using real readings.
- [ ] Time/quality comparison measured, not guessed.
- [ ] AI tools actually used are listed with date/version.
- [ ] References checked and cited.
- [ ] Final report reviewed and understood by all team members.
