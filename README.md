# Smartphones Data Analysis - End to End

## Overview
This project showcases an end-to-end data analysis pipeline on a diverse dataset of smartphone listings. The workflow includes web scraping, data cleaning, exploratory data analysis (EDA), and insights extraction, conducted primarily using Python and popular data science libraries.

The challenge was to gather raw smartphone pricing and specification data from online sources, clean and preprocess it to a usable form, and then perform in-depth analysis to understand market trends, pricing factors, and product characteristics.

---

## Data Collection

- Data was sourced by scraping smartphone listing pages using the Python `smartprix_scrapping.py` script, leveraging Selenium and BeautifulSoup.
- The scraped raw dataset (`smartphones.csv`) contains detailed product attributes and pricing information collected directly from the web.

---

## Data Cleaning

- Multiple versions of cleaned datasets were created (`smartphone_cleaned_v2.csv`, `smartphone_cleaned_v5.csv`) as part of iterative refinement to correct inconsistencies, handle missing data, and convert formats for analysis readiness.
- Extensive data cleaning was assisted by exploratory analysis runs within the Jupyter notebooks.

---

## Exploratory Data Analysis

- The notebooks `EDA.ipynb` and `eda_assisted_data_cleaning.ipynb` document the full exploration and cleaning cycles.
- Key analyses include price distribution, brand-wise segmentation, feature correlations, missing value patterns, and market segmentation insights.
- Visualizations like histograms, boxplots, and correlation matrices are used extensively to uncover trends and anomalies.

---

## Skills and Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Web Scraping (Selenium, BeautifulSoup)
- Data Cleaning and Preprocessing
- Jupyter Notebook for analysis and visualization

---

## Outcomes

- Prepared a clean, analysis-ready dataset with over a thousand smartphone listings.
- Extracted actionable insights on price ranges and features across brands.
- Laid the foundation for further predictive modeling or dashboarding projects.

---

## How to Use

1. Run `smartprix_scrapping.py` to collect fresh data from the source website.
2. Review and run the cleaning notebooks to preprocess and clean the data.
3. Open `EDA.ipynb` to replicate or extend the exploratory analysis performed.
4. Use the cleaned CSV files for any subsequent projects like machine learning models or dashboards.

---

> **Note on Data Availability**
>
> Please be aware that if you run the web scraping script now, you may not retrieve the same data as presented in this project. The source website may have implemented stricter anti-scraping measures or updated its layout, which can prevent or limit automated data extraction. Consequently, the results and datasets obtained during the original scraping process might differ from any current attempts.
>
> However, the concepts, logic, and code used in this project are accurate and sound. The methodology demonstrated here remains valid for similar data extraction and analysis tasks
---
