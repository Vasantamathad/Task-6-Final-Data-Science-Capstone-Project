# Online Retail Sales Analysis and Customer Insights

## What is included
- `data/online_retail_2000_records.csv` — exactly 2,000 records
- `src/analyze_retail.py` — reusable analysis script
- `notebooks.ipynb` — Jupyter notebook walkthrough
- `outputs/charts/` — generated charts
- `outputs/*.csv` and `outputs/analysis_summary.json` — analysis tables and summary
- `report/project_report.docx` and `report/project_report.txt` — project report
- `requirements.txt` — Python dependencies

## Important: dataset authenticity
The CSV included here is **simulated practice data**, not a direct extract of actual company transactions. It was made so the project runs immediately and has exactly 2,000 records. Do not claim its results are real company findings.

Authentic public dataset:
UCI Machine Learning Repository — Online Retail
https://archive.ics.uci.edu/dataset/352/online+retail
Citation: Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33
License: CC BY 4.0 (provide attribution).

## To run on Windows
1. Extract the ZIP.
2. Install Python 3.10+.
3. Open Command Prompt in the extracted project folder.
4. Run:
   `python -m venv .venv`
   `.venv\Scripts\activate`
   `pip install -r requirements.txt`
   `python src/analyze_retail.py`
5. New results and charts are saved in `outputs/`.

## To open the notebook
Install dependencies, then run `jupyter notebook` and open `notebooks.ipynb`.

## To switch to authentic data
Download `Online Retail.xlsx` from the UCI dataset page, select exactly 2,000 authentic rows and save them as `data/online_retail_2000_records.csv` with matching column names. Preserve the original values and document the sampling method. Then run the analysis script again.

## How it maps to the internship objectives
1. Define the business problem: sales and customer insights.
2. Collect and prepare data: CSV, type conversion, duplicate/missing-value checks.
3. Apply data science techniques: groupby aggregations and descriptive statistics.
4. Build and evaluate solution: reproducible analysis script and KPI checks.
5. Analyze results: summaries and limitations.
6. Generate insights: charts and recommendations in the report.
7. Document and present: report, notebook, charts, and repository-ready structure.
