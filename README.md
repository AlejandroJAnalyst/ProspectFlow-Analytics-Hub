# Marketing Data Correlation & Campaign Analytics Dashboard

## Project Overview

* Marketing analytics project focused on correlating prospect data with campaign performance.
* Simulates a real-world scenario involving multi-campaign engagement tracking and decision support.
* Goal: unify disparate data sources into a single analytical model to drive marketing actions.
* Built and published as part of a professional **Data Analyst / BI portfolio**.

## Business Context

* Campaign types and objectives:

  * **New Clients**: generate new opportunities.
  * **Impact Player**: deepen engagement with high-potential prospects.
  * **Newsletter**: maintain industry awareness (prospects and candidates).
* Prospects can transition between campaign types based on engagement behavior (opens, clicks).
* Accurate data correlation is required to track the prospect lifecycle and campaign effectiveness.

## Project Scope

* End-to-end analytics workflow, from raw data to dashboard insights.
* Focus on data correlation, segmentation, and performance evaluation.
* Deliverables included in this repository:

  * Raw (fictitious) datasets
  * Python-based ETL pipeline
  * Final analytical dataset
  * Interactive dashboard

> All data used in this project is fictional and intended solely for demonstration purposes.

## Data Sources

* Prospect master data (unique identifiers, industry, attributes).
* Campaign participation records.
* Campaign performance metrics:

  * Opens
  * Clicks
  * Responses

## Data Processing & ETL

* Implemented in **Python** using analytical libraries.
* Key ETL steps:

  * Data ingestion from raw files.
  * Data quality checks (duplicates, missing IDs, inconsistent naming).
  * Field standardization (emails, campaign names, stages).
  * Correlation of prospects across campaigns using unique identifiers.
  * Creation of derived fields:

    * Engagement indicators
    * Global Stage per prospect
* Output: clean, structured dataset optimized for BI consumption.

## Dashboard Overview

* Single, unified dashboard designed for interactive exploration.
* Eliminates the need to navigate multiple spreadsheets.
* Enables dynamic segmentation and drill-down analysis.

### Key Metrics & Views

* Total prospects and distribution by industry.
* Global Stage of each prospect.
* Campaign status per prospect.
* Campaign performance metrics:

  * Open rates
  * Click rates
  * Responses
* Supports decisions such as promoting prospects from **New Clients** to **Impact Player** campaigns.

## Tools & Technologies

* **Python** (ETL and data preparation)
* **Pandas / NumPy** (data manipulation)
* **BI Tool** (dashboard creation)
* **GitHub** (version control and portfolio presentation)

## Repository Structure

```
├── data/
│   ├── raw/               # Original fictitious datasets
│   └── processed/         # Final dataset after ETL
├── etl/
│   └── data_pipeline.ipynb   # Python ETL script
├── dashboard/
│   └── dashboard_file     # BI dashboard file or link
├── README.md
```

## Key Takeaways

* Demonstrates end-to-end marketing analytics and BI skills.
* Emphasis on data correlation, not just visualization.
* Reflects real-world challenges in campaign analytics and prospect lifecycle management.

## Disclaimer

* All data in this repository is fictional.
* This project is for portfolio and technical demonstration purposes only.
