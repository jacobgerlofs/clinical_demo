# clinical_demo

Demonstrative repository using publicly available health data (Framingham Heart Study teaching dataset) for analytic skill building and refreshing.

## Analyses covered

1. SQL ingestion with DuckDB
2. Data wrangling & exploratory data analysis (tidyverse)
3. Logistic regression + ROC curve
4. Risk score development and validation
5. Survival analysis (Kaplan-Meier & Cox proportional hazards)
6. Mixed-effects regression
7. Stakeholder communication artifact
8. Shiny dashboard

## Workflow conventions

Each phase of analysis is developed on its own Git branch (e.g. `phase-1-duckdb-ingestion`) and merged to `main` via a pull request.

## Repository structure

```
data/raw/          # raw source data (gitignored — do not commit datasets)
data/processed/    # cleaned/transformed data (gitignored)
R/                 # reusable R functions and helpers
analysis/          # phase-by-phase analysis scripts
outputs/           # rendered outputs (figures, tables, reports)
sql/               # SQL scripts for DuckDB ingestion
```
