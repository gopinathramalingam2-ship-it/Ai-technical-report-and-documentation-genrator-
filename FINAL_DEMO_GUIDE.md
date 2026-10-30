# Final Demo Guide (5–7 minutes)

1. Introduce CAPSTONE 10 and the problem of manual technical documentation.
2. Show the selected ECE example: Automatic Street Light Using an LDR.
3. Open `data/lab_notes.json` and explain that it holds student-supplied facts.
4. Run the automation command from the README.
5. Open the generated Markdown outline and point out that missing values remain `NOT PROVIDED`.
6. Show the prompt library and verification checklist.
7. Show `observations.csv` and `time_quality_comparison.xlsx`; explain that actual measurements and timings must be entered.
8. Present the 7-slide PowerPoint.
9. Close with academic integrity: AI drafts; the student verifies.

**Demo command**
`python automation/generate_report.py --input data/lab_notes.json --output generated_report.md`
