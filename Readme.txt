# Kato Joseph Bwanika – Data Analysis Notebook

This notebook performs exploratory data analysis (EDA) and preprocessing for a supervised binary classification task predicting **bank account ownership** among households in East Africa (Kenya, Rwanda, Tanzania, Uganda).

---

## Dataset Description
The dataset (from a ZIP archive) includes:

- **Train.csv** – 23,524 rows, 13 features (incl. target: `bankaccount`)
- **Test.csv** – 10,086 rows, 12 features for prediction
- **SampleSubmission.csv** – Format for model output (33,610 rows)
- **VariableDefinitions.csv** – Descriptions for 12 demographic and socioeconomic variables (e.g., `country`, `year`, `locationtype`, `cellphoneaccess`, `educationlevel`, `jobtype`, etc.)

---

## Methodology
The notebook uses **pandas, matplotlib, seaborn** and follows:

- **Data Ingestion:** Automatic extraction and loading of all CSV files.  
- **Descriptive Analysis:** Dataset previews, summary statistics, missing-value checks (none found), and class distribution (≈81% “No” bankaccount).  
- **Data Cleaning:** Mean imputation for numeric features and mode imputation for categorical features.  
- **Visualization:** Histograms and count plots to explore distributions and relationships.

---

## 🔍 Key Findings
- Significant **rural vs. urban differences** in cellphone access.  
- **Education levels** show strong patterns with employment types.  
- Notable **temporal variation** across survey years (2016–2018).  

These insights set the stage for feature engineering and model building.


## Kato Joseph Bwanika
