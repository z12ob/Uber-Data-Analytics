# Ride-Hailing Data Analysis

**Junior Data Analyst Portfolio Project**  
Focus on data cleaning, exploration, statistical checks, basic modeling, and clear communication.

This project works on 148,770 ride bookings from a public NCR dataset. I process the data, run structured analysis, build simple models, and extract grounded insights. The goal is to demonstrate technical discipline, not business theatrics.

## Skills Demonstrated

- Data cleaning
- Feature creation
- Exploratory analysis
- Statistical tests
- Logistic regression and random forest
- Basic automation functions
- Matplotlib, Seaborn, Plotly for charts
- Structured analysis in Python

## Dataset

- 148,770 bookings
- Columns for timestamps, routes, fares, ratings, vehicle types, and outcomes
- Year-long span
- Used unchanged except cleaning and feature creation

## Project Structure

```
├── ncr_ride_bookings.csv
├── uber.ipynb
├── requirements.txt
├── README.md
└── Dashboard.png
```

## What the Notebook Does

**Data Cleaning**  
I drop duplicates, fix column types, handle missing values, and add time features.

**Exploration**  
I check distributions. I measure booking outcomes across hours, weekdays, vehicle types, and locations. I visualize patterns that guide the rest of the work.

**Statistical Checks**  
I use chi-square, t-tests, and ANOVA for group differences. I assign confidence levels to each finding.

**Modeling**  
I train logistic regression and random forest classifiers to estimate cancellation probability. I report accuracy, precision, recall, and AUC. I inspect feature importance and keep interpretations grounded.

**Automation**  
I add a small KPI helper that computes ride volume, average fare, and completion metrics. It runs inside the notebook.

**Visualization**  
I include Plotly views for interactive charts and Matplotlib for static ones.

## Key Findings

- Ride volume peaks in morning and evening
- Completion rate varies across hours and locations
- Certain vehicle types show consistent patterns in ride outcomes
- Model performance stays stable across multiple runs
- Time-based features influence cancellation probability

These findings stay inside the boundaries of the dataset. No revenue math. No operational claims.

## How to Run

```bash
git clone https://github.com/z12ob/Uber-Data-Analytics.git
cd Uber Data Analytics
pip install -r requirements.txt
jupyter notebook uber.ipynb
```
