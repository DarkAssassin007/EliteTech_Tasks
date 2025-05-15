Project: ETL Pipeline for Data Preprocessing, Transformation, and Loading

Description:

This project demonstrates a basic ETL (Extract, Transform, Load) pipeline using Python, pandas, and scikit-learn. It is designed to automate data preprocessing tasks typically needed before analysis or modeling.

Key Steps:

Extract: Loads raw data from a CSV file (raw_data.csv).

Preprocess:

Handles missing numeric values using the mean.
Handles missing categorical values using the most frequent value.

Transform:

Encodes categorical columns using label encoding.
Scales numeric columns using standardization (z-score).
Load: Saves the cleaned and transformed data to a new CSV file (cleaned_data.csv).

Tools Used:

-pandas for data handling
-scikit-learn for preprocessing (imputation, scaling, encoding)

How to Use:
Run the script using Python. Make sure your raw CSV file is named raw_data.csv and is in the same directory as the script.

bash
Copy
Edit
python etl_pipeline.py
The cleaned output will be saved as cleaned_data.csv.