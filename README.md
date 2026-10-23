# KidneyHealth-Predictive-Analytics
A complete data science pipeline focused on cleaning, exploratory data analysis (EDA), and preprocessing for the Chronic Kidney Disease dataset using Python.
🚀 Project Overview
This project processes raw medical data related to chronic kidney disease to make it ready for machine learning model training. It handles missing values, corrects formatting inconsistencies, performs statistical analysis, and visualizes feature correlations.

🛠️ Key Steps & Pipeline
Dataset Loading & Renaming: Loaded the initial 400x26 dataset, dropped redundant ID columns, and renamed features for better readability.

Data Cleaning & Correction: Fixed corrupted and inconsistent categorical entries (e.g., handling trailing tabs like \tno, ckd\t).

Type Conversion: Converted text-based numerical columns (like packed cell volume, white/red blood cell counts) into proper numeric types.

Missing Value Imputation:

Used Mean and Mode imputation.

Implemented KNNImputer for advanced missing value handling.

Target Encoding: Encoded the target variable (class) where ckd = 0 and not ckd = 1.

Exploratory Data Analysis (EDA):

Calculated statistical metrics such as Skewness, Kurtosis, and Variance.

Generated a Correlation Heatmap using Seaborn to understand feature relationships.

🧰 Technologies Used
Python

Pandas & NumPy (Data manipulation and handling)

Scikit-Learn (Data preprocessing & Imputation)

Seaborn & Matplotlib (Data visualization)
