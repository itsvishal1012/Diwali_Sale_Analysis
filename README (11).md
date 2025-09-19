# 🪔 Diwali Sales Analysis

## 📌 Project Overview

This project analyzes Diwali sales data to uncover customer behavior,
purchasing patterns, and key insights that can help improve business
strategies during festive seasons.\
The analysis was performed using **Python, Pandas, Matplotlib, and
Seaborn**.

------------------------------------------------------------------------

## 📂 Dataset

-   **File:** `Diwali Sales Data.xls`
-   The dataset contains information such as:
    -   Customer ID & Names
    -   Gender & Age Group
    -   State & Zone
    -   Product Category & Sub-category
    -   Amount Spent
    -   Marital Status
    -   Occupation
    -   Orders & Quantity
-   Some unnecessary columns (e.g., `Status`, `unnamed1`) were dropped
    for cleaning.

------------------------------------------------------------------------

## ⚙️ Requirements

Install the following Python libraries before running the notebook:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

------------------------------------------------------------------------

## 🧾 Steps Performed

1.  **Data Loading**
    -   Used Pandas to read the dataset (`read_csv` / `read_excel`)\
    -   Handled encoding issues with `unicode_escape`
2.  **Data Cleaning**
    -   Removed irrelevant columns: `Status`, `unnamed1`\
    -   Checked for null values and handled missing data\
    -   Converted data types where required
3.  **Exploratory Data Analysis (EDA)**
    -   Analyzed sales by **gender, age group, occupation, marital
        status, and state**\
    -   Studied **top-selling product categories & sub-categories**\
    -   Visualized spending patterns using **bar charts, histograms, and
        count plots**
4.  **Insights**
    -   Most buyers were **married women** aged **26--35 years**,
        working in the **IT sector**\
    -   Top contributing states: **Uttar Pradesh, Maharashtra, and
        Karnataka**\
    -   Most sold product categories: **Food, Clothing & Electronics**

------------------------------------------------------------------------

## 📊 Visualizations

The notebook contains various plots: - Sales by **Gender** - Sales by
**Age Group** - Sales by **State** - Top **Product Categories** -
Customer **Occupation Analysis**

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone this repository:

    ``` bash
    git clone https://github.com/yourusername/diwali-sales-analysis.git
    ```

2.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook Diwali.ipynb
    ```

3.  Run all cells to reproduce the analysis.

------------------------------------------------------------------------

## 🙌 Acknowledgments

-   Dataset: Provided for educational purposes\
-   Inspired by Data Analytics projects on festive sales\
-   Tools used: **Python, Pandas, Matplotlib, Seaborn, Jupyter
    Notebook**

------------------------------------------------------------------------
