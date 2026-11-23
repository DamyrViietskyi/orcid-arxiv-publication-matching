# ORCID × arXiv Publication Matching

**Stack:** Python · pandas · Jupyter

How can researcher records be connected to preprints?

## Analysis

Normalize nested researcher records, construct people, works and employment tables, compare CSV and Parquet exports, and link works to preprints.

## Run locally

1. Install dependencies with `python -m pip install -r requirements.txt`.
2. Place your authorized input files at the paths referenced in the notebook. Expected inputs: `data/orcid_records.json.gz`, `data/arxiv_econ_se.csv.gz`.
3. Open `analysis.ipynb` in Jupyter and run the cells from the repository root.

The input datasets and generated tables are excluded. The analysis requires inputs matching the original column schema.

Developed from STAT163 coursework at Kyiv School of Economics.
