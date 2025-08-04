
# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset
**Source:** Customer Personality Analysis (marketing_campaign.csv)

## ✅ Steps Performed

1. **Handled Missing Values**
   - Numeric columns: Filled missing values with median.
   - Categorical columns: Filled missing values with 'unknown'.

2. **Removed Duplicates**
   - Dropped all duplicate rows from the dataset.

3. **Standardized Text Columns**
   - Converted all categorical/text data to lowercase and removed extra spaces.

4. **Converted Date Formats**
   - Converted 'Dt_Customer' column to `dd-mm-yyyy` format.

5. **Renamed Columns**
   - Changed all column names to lowercase and replaced spaces with underscores.

6. **Corrected Data Types**
   - Ensured numeric columns like 'year_birth' and 'income' are in correct format.
   - Date column properly converted.

7. **Outlier Detection (Optional)**
   - Flagged rows in 'income' column as outliers using IQR method.

## 📁 Files Included
- `marketing_campaign_cleaned_complete.xlsx` – Final cleaned dataset.

## 💡 Tools Used
- Excel
- Python (Pandas for processing)

## 🔗 Submission
Task completed as part of Data Analyst Internship. Ready for upload to GitHub and submission via [form link](https://forms.gle/o2uMAByM719GzebC7).

---

*Created by Bushra Begum*
