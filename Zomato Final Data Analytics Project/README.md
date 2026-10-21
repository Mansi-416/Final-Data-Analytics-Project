# Zomato Restaurant Data Analytics Project

## Project Overview

This project presents an end-to-end data analytics case study using a Zomato restaurant dataset. It covers data cleaning and preparation, exploratory data analysis (EDA), interactive dashboard development, and business insights.

The objective is to identify patterns in restaurant ratings, popular cuisines, city-wise restaurant distribution, pricing, online delivery, and table booking.

## Project Objectives

* Clean and prepare the restaurant dataset.
* Identify missing values, duplicate records, incorrect data types, and inconsistent values.
* Explore restaurant data to discover meaningful patterns.
* Build visualizations to communicate analytical findings.
* Develop an interactive dashboard using Power BI.
* Present business insights and recommendations based on the analysis.

## Project Workflow

### Task 1: Data Cleaning and Preparation

The dataset was inspected and cleaned using Python and Pandas.

Key activities:

* Inspected the dataset structure and data types.
* Checked for missing values and duplicate records.
* Standardized text values and categorical columns.
* Handled missing values.
* Created a `Rating Status` column to distinguish rated and unrated restaurant records.
* Exported the cleaned dataset for further analysis.

**Notebook:** `Notebooks/task.ipynb`

### Task 2: Exploratory Data Analysis (EDA)

Exploratory data analysis was performed on the cleaned dataset to identify trends and relationships.

Key analyses:

* Restaurant rating distribution.
* Top 10 cuisines.
* Top cities by restaurant count.
* Cost versus rating.
* Average ratings by price range.
* Online delivery distribution.
* Table booking distribution.
* Cost outlier analysis.

**Notebook:** `Notebooks/eda.ipynb`

**Visualizations:** `Visualizations/`

### Task 3: Interactive Dashboard

An interactive Power BI dashboard was developed to present key restaurant analytics metrics and findings.

The dashboard provides an overview of restaurant distribution, ratings, pricing, and service availability.

**Dashboard file:** `Dashboard/Zomato_Restaurant_Dashboard.pbix`

To open the dashboard, download the `.pbix` file and open it using Microsoft Power BI Desktop.

### Task 4: Final Business Insights and Recommendations

The findings from data cleaning, EDA, and dashboard development were consolidated into a business insights report.

**Report:** `Reports/Business_Insights.md`

The report summarizes the main findings and suggests opportunities for improving customer experience, evaluating delivery services, understanding city-level competition, and reviewing restaurant price-range performance.

## Key Findings

The analysis of 9,551 restaurant records revealed the following:

* **Average restaurant rating:** 2.67 out of 5.
* **Total customer votes:** 1,498,645.
* **Restaurants offering online delivery:** 2,451.
* **Restaurants offering table booking:** 1,158.
* **Largest city by restaurant count:** New Delhi, with 5,473 records.
* **Most common cuisine category:** North Indian, appearing in 3,960 records.
* **Rating status:** 7,403 records are rated, while 2,148 are classified as not rated.

Average ratings also varied by price range, increasing from 2.00 in price range 1 to 3.82 in price range 4.

These findings describe the dataset analyzed and should not automatically be interpreted as current market conditions or proof of cause and effect.

## Technologies Used

* **Python** — data processing and analysis.
* **Pandas** — data cleaning and manipulation.
* **Jupyter Notebook** — documenting the analysis workflow.
* **Matplotlib** — data visualization.
* **Power BI** — interactive dashboard development.
* **CSV** — storing the original, cleaned, and analytical data.
* **Git and GitHub** — version control and project sharing.

## Repository Structure

```text
Zomato-Final-Data-Analytics-Project/
│
├── Data/
│   ├── Zomato Restaurant Dataset.csv
│   └── Zomato_Restaurant_Dataset_Cleaned.csv
│
├── Notebooks/
│   ├── task.ipynb
│   └── eda.ipynb
│
├── Dashboard/
│   └── Zomato_Restaurant_Dashboard.pbix
│
├── Visualizations/
│   ├── restaurant_rating_distribution.png
│   ├── top_10_cuisines.png
│   ├── cost_vs_rating.png
│   ├── online_delivery_distribution.png
│   ├── table_booking_distribution.png
│   ├── ratings_by_price_range.png
│   └── cost_outliers.png
│
└── Reports/
    ├── Business_Insights.md
    ├── rating_distribution.csv
    ├── ratings_by_price_range.csv
    ├── top_cities.csv
    └── top_cuisines.csv
```

*Note: The structure above is illustrative. Keep the actual filenames in your repository and include all files you have created.*

## How to Run the Project

1. Download or clone the repository.

2. Install Python if it is not already installed.

3. Install the required libraries:

   ```bash
   pip install pandas matplotlib jupyter
   ```

4. Open the project in VS Code.

5. Open the notebooks in the `Notebooks` folder.

6. Run the notebook cells in order, ensuring the dataset paths match the folder structure.

7. Open the Power BI dashboard using Microsoft Power BI Desktop.

8. Read `Reports/Business_Insights.md` for the conclusions and recommendations.

## Conclusion

This project demonstrates an end-to-end data analytics workflow, from data preparation and exploratory analysis to interactive dashboard development and business reporting.

It provides practical experience in data cleaning, visualization, analytical thinking, and communicating findings through data-driven recommendations.

## Author

**Mansi Jain**

B.Tech Computer Science Engineering Student

GitHub: [Mansi-416](https://github.com/Mansi-416)
