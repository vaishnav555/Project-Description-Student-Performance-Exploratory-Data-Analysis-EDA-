# Project-Description-Student-Performance-Exploratory-Data-Analysis-EDA-
This task focuses on performing Exploratory Data Analysis (EDA) on a student performance dataset using Python to understand data quality, distributions, relationships, and anomalies. The objective is to prepare a clean, reliable dataset suitable for further analysis, visualization, or machine learning.

Task Overview:

The project begins by loading a student performance dataset and performing initial inspections using .shape(), .info(), and .head() to understand the dataset structure, data types, and sample records. Descriptive statistics are generated using .describe() to summarize key numerical attributes and identify potential data quality issues.
Missing values are analyzed by computing the percentage of null values per column. Appropriate handling strategies are applied using median imputation to preserve data integrity without introducing bias.
To understand data distribution and detect anomalies, histograms and boxplots are used for key numerical variables such as study hours, attendance, and subject scores. Outliers are detected using the Interquartile Range (IQR) method, and an outlier-handling strategy is applied by capping extreme values rather than removing records. This approach maintains dataset size while reducing the impact of extreme observations.
A correlation matrix is created to analyze relationships between study habits, attendance, and academic performance. The analysis highlights positive correlations between study hours, attendance percentage, and exam scores, indicating their influence on student outcomes.
Finally, the cleaned dataset is exported as a CSV file, and key insights from the EDA process are documented in a findings report. The output includes a Jupyter Notebook containing the full analysis, a cleaned dataset ready for downstream use, and a summarized insights file for documentation.

Deliverables:

task10_eda.ipynb – Complete EDA workflow in Python
cleaned_dataset.csv – Processed and analysis-ready dataset
eda_findings.txt – Summary of insights and data quality observations

Skills Demonstrated:

Python (Pandas, NumPy, Matplotlib, Seaborn)
Exploratory Data Analysis
Missing Value Treatment
Outlier Detection (IQR Method)
Data Cleaning & Preprocessing
Correlation Analysis
Data Documentation
