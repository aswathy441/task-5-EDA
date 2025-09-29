Project Title
Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

Objective
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset (or a similar dataset) to extract meaningful insights using visual and statistical exploration.
The goal is to understand the data structure, detect patterns, relationships, and key factors influencing survival.

Dataset
- Name: Titanic Dataset
- Source: https://www.kaggle.com/c/titanic/data
- Description: Contains passenger details such as age, sex, ticket class, fare, and survival status.

Tools & Libraries
- Programming Language: Python
- Libraries Used:
  - pandas – Data manipulation & cleaning
  - matplotlib – Data visualization
  - seaborn – Advanced visualizations & statistical plots

Steps Performed
1. Data Loading & Inspection
   - Used .head(), .info(), .describe(), and .value_counts() to explore data types, missing values, and basic statistics.
2. Data Cleaning
   - Handled missing values (e.g., Age, Cabin).
   - Checked for duplicates and outliers.
3. Univariate Analysis
   - Plotted histograms and boxplots for numerical features (Age, Fare).
   - Analyzed categorical features (Sex, Pclass) using bar plots.
4. Bivariate Analysis
   - Used pairplot to identify relationships between features.
   - Applied heatmap to visualize correlations.
   - Created scatterplots to study Age vs. Fare with respect to Survival.
5. Key Observations
   - Women had higher survival rates than men.
   - Passengers in 1st class were more likely to survive compared to 2nd and 3rd class.
   - Younger passengers had slightly better chances of survival.
   - Higher fares were associated with higher survival rates.
6. Summary of Findings
   - Survival strongly depended on gender, class, and fare.
   - Age had a mild influence on survival.
   - Correlation analysis revealed strong relationships between Fare and Pclass.

Deliverables
- Jupyter Notebook: Titanic_EDA.ipynb (Python code with visualizations and explanations)
- PDF Report: Titanic_EDA_Report.pdf (Summary of insights and visuals)
- README File: README.txt (This document)

How to Run
1. Download the dataset (train.csv) and place it in the project directory.
2. Install required libraries (if not already installed):
   pip install pandas matplotlib seaborn
3. Open the Jupyter Notebook and run all cells:
   jupyter notebook Titanic_EDA.ipynb

Author
ASWATHY SADANAPPAN
29-09-2025
