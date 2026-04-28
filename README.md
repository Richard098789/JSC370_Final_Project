# JSC370 Final Project

**Canadian data job postings and salary analysis**

---

## Website

**[View the project website](https://richard098789.github.io/JSC370_Final_Project/)**

---

## Overview

This project studies Canadian **data-related job postings** and **advertised salaries** using the **Adzuna Job Search API**. The pipeline includes cleaning, role and geography feature engineering, exploratory analysis, and machine learning to relate salary to role, location, contract type, and posting date.

**Full write-up (PDF):** [JSC370Final.pdf](https://github.com/Richard098789/JSC370_Final_Project/blob/main/final_project/JSC370Final.pdf)

---

## Data sources

| Source | Description |
|--------|-------------|
| [Adzuna API](https://developer.adzuna.com/) | Job listings for Canada: title, company, location, salary range, contract type, posting time. Credentials are required for live API pulls. |
| Analytic extract | Saved postings used in the report: [`final_project/data/data.csv`](final_project/data/data.csv) |
| Statistique Canada | Values are defined in the CPI table inside [`final_project/data/cost_of_living.csv`](final_project/data/cost_of_living.csv)  |

---

## Repository layout

| Path | Purpose |
|------|---------|
| [`final_project/final.qmd`](final_project/final.qmd) | Full analysis and modeling |
| [`final_project/website/`](final_project/website/) | Quarto site source (`index.qmd`, `vis.qmd`) |
| [`docs/`](docs/) | Built static site for GitHub Pages (run `quarto render` from `final_project/website`) |
