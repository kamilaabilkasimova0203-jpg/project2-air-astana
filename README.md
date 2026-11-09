# Air Astana Group: Engine Availability and Operational Efficiency

**Status:** Research submission candidate; fully synthetic data.

## Evidence
- S1 Air Astana Group Integrated Annual Report 2025 (primary company disclosure).
- S2 Simple Flying (17 Sep 2026), global GTF engine shortage context.
- S3 The Engine Cowl (13 Mar 2026), reporting on Air Astana 2025 results; substantially derived from S1.

Full text of S2 and S3 was provided by the user. The original URLs were not independently opened in this environment. See `source_register.csv`.

## Files
- `data_raw.csv`: intentionally imperfect, fully synthetic data
- `data_clean.csv`: cleaned, fully synthetic data
- `analysis.ipynb`: cleaning and Welch t-tests
- `data_note.pdf`: source, schema, cleaning, limitations
- `memo.pdf`: one-page management memo
- `source_register.csv`: evidence register

## Run
`pip install -r requirements.txt` then open `analysis.ipynb` in Jupyter and run all cells.

## Important
The published figures are real company/industry disclosures; the 1,500 scenario rows are not actual aircraft, flights, removals, or maintenance events. Do not infer company-specific effect sizes from synthetic hypothesis tests.


## November 9 evidence update
Four publications (three publishers) are listed in source_register.csv; S4 adds reported mitigation strategies. All analyses use synthetic scenarios and cannot be generalized to Air Astana. See SOURCE_4_VERIFICATION.md.
