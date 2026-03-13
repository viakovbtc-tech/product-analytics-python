# Product Analytics with Python

## Overview

This project demonstrates an exploratory product and marketing analytics workflow using Python.

The objective of the analysis is to understand how users interact with a product platform, 
evaluate traffic acquisition channels and identify behavioral patterns that influence user engagement.

The project replicates a typical workflow of a Product / Marketing Data Analyst, including data aggregation, 
behavioral analysis, and visualization of key metrics.

---

## Business Objectives

The analysis focuses on answering key product analytics questions:

- Which traffic channels generate the highest number of sessions?
- How do users move through key product interaction events?
- What behavioral patterns can be observed in user activity?
- How does traffic change over time?
- Which acquisition channels drive the most engagement?

These insights help product teams evaluate marketing effectiveness and improve user acquisition strategies.

---

## Dataset

The dataset contains aggregated user interaction and marketing data with the following fields:

| Column | Description |
|------|-------------|
| date | Event date |
| country | User country |
| continent | Geographic region |
| device | Device type (desktop / mobile) |
| channel | Traffic acquisition channel |
| event_name | User interaction event |
| value | Number of event occurrences |

### Key Events Analyzed

- session  
- begin_checkout  
- add_shipping_info  
- add_payment_info  
- new_accounts  

These events represent important steps in the **user interaction funnel**.

---

## Tools & Technologies

The analysis was conducted using the following tools:

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

---

## Analytical Workflow

### 1. Data Preparation

- Data loading
- Dataset inspection
- Handling missing values
- Data aggregation

### 2. Exploratory Data Analysis

- Event frequency analysis
- Session distribution analysis
- Behavioral metric exploration

### 3. Traffic Channel Analysis

- Sessions by acquisition channel
- Channel performance comparison
- Identification of dominant traffic sources

### 4. Time Series Analysis

- Daily sessions aggregation
- Traffic trend visualization
- Behavioral changes over time

### 5. Visualization

- Histograms of session distributions
- Channel comparison charts
- Time series visualizations

---

## Key Insights

The analysis revealed several important behavioral patterns:

- Traffic is unevenly distributed across acquisition channels.
- Certain user interaction events dominate user activity.
- Engagement patterns differ depending on acquisition source.
- Time-based analysis reveals fluctuations in platform activity.

These insights can support **product optimization and marketing strategy decisions**.

---

## Project Structure

project/
├── images  
│   ├── Tableu.png  
│   └── Tableu 2.png  
├── notebooks  
│   └── marketing_analytics_analysis.ipynb  
└── README.md

### Folder Description

**notebooks/**  
Contains the full Python analysis including data preparation, aggregation, and visualizations.

**images/**  
Contains dashboard screenshots and visualization outputs used in the analysis.

---

## Skills Demonstrated

This project demonstrates practical skills relevant for a **Junior / Product Data Analyst role**:

- Exploratory Data Analysis (EDA)
- Behavioral data analysis
- Marketing channel performance analysis
- Data aggregation using Pandas
- Data visualization with Matplotlib
- Analytical storytelling

---

## How to Run the Project

1. Clone the repository

git clone https://github.com/viakovbtc-tech/product-analytics-python.git

2. Open the notebook

notebooks/marketing_analytics_analysis.ipynb

3. Run the analysis in Jupyter Notebook or Google Colab

## Author

Viacheslav Kovalchuk  
Aspiring Data Analyst



