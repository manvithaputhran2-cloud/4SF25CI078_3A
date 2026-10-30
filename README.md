# Swiggy Data Analysis – Milestone 1 (CIE)

## Project Overview
This repository contains the exploratory data analysis and data preprocessing performed on the **Swiggy Food Delivery dataset**. The goal of this analysis is to evaluate restaurant pricing structures, rating distributions, cuisine categories, and delivery metrics to extract actionable insights for food delivery optimization.

---

## Repository Details
* **Student USN / Section:** 4SF25CI078_3A
* **Project Milestone:** Milestone 1 – Continuous Internal Evaluation (CIE)
* **Dataset File:** `swiggy.csv`

---

## Key Features & Workflow

### 1. Data Preprocessing & Cleaning
* **Missing Value & Duplicate Management:** Checked for null values across key features (e.g., `Avg ratings`, `Address`) and performed necessary data cleaning and deduplication.
* **Feature Categorization:** Standardized numerical and text fields into structured segments, including engineered pricing buckets (`Price category`).
* **Data Formatting:** Cleaned numerical metrics such as `Price`, `Avg ratings`, and `Total ratings` to ensure numerical consistency across visual analyses.

### 2. Visualization & Insights
* **Price & Rating Distributions:** Created bar plots, histograms, and pie charts illustrating the breakdown of restaurant pricing levels and rating score spreads.
* **Geographic & Cuisine Patterns:** Analyzed city and area-wise restaurant clusters along with popular `Food type` distributions.
* **Metric Correlations:** Explored relationships between delivery times, average ratings, and price tiers using correlation heatmaps and scatter plots.

---

## File Structure
```text
4SF25CI078_3A/
├── cie.ipynb          # Jupyter Notebook with full EDA, data preprocessing, and visualizations
├── swiggy.csv         # Raw dataset containing Swiggy restaurant listings and metadata
└── README.md          # Project documentation and summary
