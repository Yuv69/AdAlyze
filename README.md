# Adalyze: Marketing A/B Testing Dashboard

## Project Overview
Adalyze is a data analyst project that combines statistical analysis and interactive visualization to evaluate digital marketing campaigns.  
The dashboard compares Facebook Ads vs. Google Ads (AdWords) across conversion rate (CVR), click-through rate (CTR), and ROI, providing business-ready insights for optimization and budget allocation.

This project demonstrates the full data analytics workflow:
1. Data ingestion & wrangling  
2. Exploratory Data Analysis (EDA)  
3. Hypothesis testing & statistical validation  
4. Visualization (EDA + Dashboard)  
5. Business insights & recommendations  

## Features
- A/B Test Results: Measure lift in conversion rates and ROI between campaigns
- Statistical Rigor: P-values, confidence intervals, Cohen’s h, and power analysis
- Early Stopping Alerts: Detect significance thresholds to optimize ad spend
- Interactive Dashboard: Animated charts, KPI cards, and campaign alerts powered by Chart.js
- Segmentation Analysis: Breakdown by weekday, monthly trends, and time series
- Business Insights: Actionable recommendations for campaign optimization

## Tech Stack
*Data Analysis & Statistics*  
- Python: pandas, numpy  
- SciPy: hypothesis testing  
- Statsmodels: confidence intervals, z-test, power analysis  

*Visualization*  
- Matplotlib, Seaborn for EDA plots  
- Chart.js (JavaScript) for interactive dashboard visualizations  

*Frontend & Data*  
- HTML5, CSS3 (responsive dark-themed UI)  
- JSON datasets for results, segments, timeseries, and alerts  

## Key Insights
- Facebook Ads CVR = 27.1% vs. AdWords CVR = 9.87% → 174% Lift  
- Statistical significance confirmed (p-value = 0.0, CI robust)  
- Cohen’s h = 0.46 indicates medium-to-large effect size  
- Early stopping triggered (p < 0.017), suggesting budget could be reallocated sooner  
- ROI analysis revealed Facebook performed better, but both campaigns had negative ROI  



The dashboard displays:  
- KPI Cards: Conversion rates, ROI, CTR  
- Alerts: Statistical significance & early stopping signals  
- Time Series: Conversion trends over time  
- Segmentation: Weekday & monthly breakdowns  
- Comparative Charts: Facebook vs. AdWords performance  

## Skills Demonstrated
- Data Wrangling & Cleaning (pandas, numpy)  
- Exploratory Data Analysis (EDA) with Seaborn & Matplotlib  
- Hypothesis Testing & Confidence Intervals (SciPy, Statsmodels)  
- Statistical Power & Effect Size Analysis  
- Interactive Data Visualization (Chart.js, HTML, CSS)  
- Business Insights & Data Storytelling
