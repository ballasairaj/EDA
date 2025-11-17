📊 Electric Vehicle Population Data Analysis

A comprehensive Exploratory Data Analysis (EDA) on the Electric Vehicle Population Dataset, covering data cleaning, preprocessing, statistical summaries, and visual insights using Python.

📁 Project Overview

This project analyzes a large dataset containing details about electric vehicles, including their make, model, electric range, model year, EV type, MSRP, and more.
The purpose of the analysis is to understand trends in EV adoption, performance metrics, and manufacturer patterns using various visualization techniques.

🧰 Technologies Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

📥 Dataset Information

- Loaded from a CSV file: Electric_Vehicle_Population_Data.csv

- Contains 250,659 rows and 17 columns

Includes data columns such as:

- Make

- Model

- Electric Vehicle Type

- Model Year

- Electric Range

- Base MSRP

- County, City

And more…

🔍 Key Analysis Steps
✔️ Importing Necessary Libraries

Libraries like pandas, numpy, matplotlib, seaborn, and warnings were imported.

✔️ Loading & Exploring Data

* ds.head() — view top 5 rows

* ds.shape — check dataset dimensions

* ds.info() — check datatypes

* ds.describe() — statistical summary

✔️ Data Cleaning

* Handling missing values

* Converting datatypes

* Filtering irrelevant rows

* Standardizing categorical text

✔️ Data Visualization

Multiple visualizations were created to understand trends and distributions:

📌 1. Heatmap

Correlation between numerical features.

📌 2. Stacked Bar Chart

Distribution of Top 10 EV Makes by EV Type.

📌 3. Line Plot

Average Electric Range trend across Model Years, grouped by EV Type.

📌 4. Grouped Bar Plot

Comparison of top vehicle manufacturers based on EV type.

📌 5. Strip Plot

Distribution of Base MSRP across different EV Types.

📈 Insights Derived

- Certain manufacturers dominate specific EV categories.

- Electric range has shown a clear improvement over the years.

- Pricing distribution varies significantly between EV types.

- Top EV makes show strong correlation with model popularity and geographic distribution.

🎯 Conclusion

This project delivers a structured and visual exploration of the EV landscape using Python.
It highlights how data analysis can help understand consumer behavior, industry trends, and evolving EV technology.
