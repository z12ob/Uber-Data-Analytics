# Project Setup and Execution Guide

## For Bolt Junior Data Analyst Application

**Purpose**: This guide shows how to run the project, what tools I used, and what outputs a reviewer will see. Nothing inflated. Only the work I completed.

---

## Prerequisites

- Python 3.8 or newer
- Jupyter Notebook or VS Code with the Jupyter extension
- Git

---

## Installation

```bash
cd Uber Data Analytics
pip install -r requirements.txt
```

**Dependencies:**
- pandas - Data manipulation
- numpy - Numerical computing
- matplotlib - Static visualizations
- seaborn - Statistical plots
- scipy - Statistical hypothesis testing
- scikit-learn - Machine learning models
- plotly (optional) - Interactive visualizations

**Files Required:**
- ncr_ride_bookings.csv (148,770 records)
- uber.ipynb (Main notebook)

---

## How to Run

Open the notebook. Run all cells. Runtime is short.

---

## What the Notebook Covers

**Section 1: Data Loading and Cleaning**
- Load the dataset
- Remove duplicates and handle missing entries
- Create time-based features (hour, day of week, month)

**Section 2: Exploration**
- Plot ride volume across hours and weekdays
- Review booking outcomes
- Examine patterns across vehicle types and payment methods
- Highlight basic correlations

**Section 3: Statistical Checks**
- Run chi-square tests, t-tests, and simple ANOVA
- Use these tests to check group differences inside the dataset
- No claims about business revenue

**Section 4: Predictive Models**
- Train a logistic regression model and a random forest
- Report accuracy, precision, recall, and ROC AUC
- List feature importance without tying it to real operations

**Section 5: Basic Automation**
- Include a small function that computes simple KPIs like total rides and average booking value
- The function works inside the notebook
- No claims about production use

**Section 6: Visual Dashboards (Optional)**
- Show Plotly versions of some charts
- These run in the browser during notebook use
- No deployment claims

---

## Outputs a Reviewer Sees

- Cleaned dataset in memory
- Time series plots
- Distribution plots
- Correlation checks
- Hypothesis test results
- Two trained models with metrics
- Simple KPI function
- Plotly visuals (optional)

---

## Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- Hypothesis testing
- Basic modeling
- Python proficiency
- Communication through plots and clear outputs

---

## Troubleshooting

**Issue: Variable 'uber' is not defined**  
Solution: Rerun the data loading section

**Issue: Plotly module not found**  
Solution: Install it or skip the interactive charts

**Issue: Training fails due to RAM**  
Solution: Lower model parameters

---

## Project Structure

```
Uber Data Analytics/
├── uber.ipynb
├── ncr_ride_bookings.csv
├── requirements.txt
├── README.md
└── PROJECT_SETUP_GUIDE.md
```
