# Final Project Test – Kato Joseph Bwanika  
**Name:** Kato Joseph Bwanika  
**REG:** 2023-B291-11709  

---

## Dataset Description

The dataset for this project is provided as a ZIP archive and includes the following files:

- **Train.csv** – 23,524 rows, 13 features (including the target: `bankaccount`)  
- **Test.csv** – 10,086 rows, 12 features for prediction  
- **SampleSubmission.csv** – Format for model output (33,610 rows)  

---

## Methodology

The analysis is implemented using Python with libraries such as **pandas**, **matplotlib**, and **seaborn**. The steps followed are:

1. **Data Ingestion**  
   - Automatic extraction and loading of all CSV files from the ZIP archive.

2. **Descriptive Analysis**  
   - Preview of dataset samples and summary statistics.  
   - Checked for missing values (none found).  
   - Analyzed class distribution: approximately 81% of samples do **not** have a bank account.

3. **Data Cleaning**  
   - Numeric features: missing values imputed using the **mean**.  
   - Categorical features: missing values imputed using the **mode**.

4. **Visualization**  
   - Histograms and count plots to explore feature distributions and relationships with the target.

---

**Author:** Kato Joseph Bwanika  
**REG:** 2023-B291-11709
