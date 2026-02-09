# Diwali Sales Data Analysis

## Project Overview
This project analyzes a dataset of Diwali sales to identify customer purchasing behaviors and trends. The goal is to provide insights that can help improve customer experience and increase revenue by understanding which demographics (age, gender, location, occupation) are most profitable.

## Technologies Used
* **Python**
* **Pandas** (Data manipulation and cleaning)
* **NumPy** (Numerical operations)
* **Matplotlib** (Data visualization)
* **Seaborn** (Advanced data visualization)

## Dataset
The analysis is performed on the `Diwali Sales Data.csv` file.
* **Input features include:** User ID, Customer Name, Product ID, Gender, Age Group, Marital Status, State, Zone, Occupation, Product Category, Orders, and Amount.

## Workflow & Analysis Steps

### 1. Data Cleaning
* **Loading Data:** Imported data using Pandas with `unicode_escape` encoding to handle special characters.
* **Cleaning:** * Removed unrelated/blank columns (`Status`, `unnamed1`).
    * Dropped rows with missing values (`NaN`).
    * Changed the data type of the `Amount` column to integer.
* **Renaming:** Renamed the `Marital_Status` column to `Shaadi` for better readability.

### 2. Exploratory Data Analysis (EDA)
The project visualizes data to answer the following questions:
* **Gender:** Who buys more? (Females vs. Males)
* **Age:** Which age group contributes the most to sales?
* **State:** Which states have the highest number of orders and total sales amount?
* **Marital Status:** How does marital status affect purchasing habits?
* **Occupation:** Which purchasing power is higher based on job sector?
* **Product Category:** Which product categories are bestsellers?

## Key Insights / Conclusion
Based on the analysis, the target customer profile for high sales volume is:
* **Demographic:** Married women in the age group of **26-35 years**.
* **Location:** Residents of **Uttar Pradesh, Maharashtra, and Karnataka**.
* **Occupation:** Professionals working in **IT, Healthcare, and Aviation**.
* **Interests:** They primarily purchase products from the **Food, Clothing, and Electronics** categories.

## How to Run
1.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
2.  Place `Diwali Sales Data.csv` in the same directory as the notebook.
3.  Run the `Diwali_Sales_Analysis.ipynb` file in Jupyter Notebook or VS Code.
