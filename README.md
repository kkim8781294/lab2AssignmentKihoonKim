## What/ Why?
* This repo processes a small e-commerce dataset
* Main Step: Loads raw CSV → standardizes schema → cleans → transforms → mini-aggregation → serializes to CSV/JSON.
* Goal: One notebook that runs top-to-bottom and produces clean + enriched data, a brief insight, and a merged data dictionary.
* Why: practice the full ingest→wrangle→clean→feature-engineer flow with provided steps


## Project Structure
* data folder: raw inputs (primary CSV, secondary metadata)
* output folder: cleaned and finalized CSV & JSON
* notebook: main excute notebook


## Data Source:
* 1000 Sales Records : https://excelbianalytics.com/wp/downloads-18-sample-csv-files-data-sets-for-testing-sales/
- Coupon reference: https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company?select=Discount_Coupon.csv
- City reference: https://www.kaggle.com/datasets/dataanalyst001/all-capital-cities-in-the-world
