# task1-data-analyst
# Task 1 - Data Cleaning and Preprocessing (Excel)

## 📌 Objective
Clean and prepare the raw Netflix dataset in Excel by handling missing values, duplicates, and inconsistent formats.

## 🛠 Tools Used
- Microsoft Excel

## ⚡ Steps Performed
1. **Renamed Columns** → changed headers to clean names (lowercase, no spaces).
2. **Handled Missing Values**:
   - Used **Find & Replace** to fill blanks:
     - `Unknown` for `director`, `cast`, `country`, `duration`
     - `Not Rated` for `rating`
   - Kept missing `date_added` as blank.
3. **Converted Dates** → formatted `date_added` column to proper Date type.
4. **Trimmed Text** → applied `=TRIM(A2)` where needed to remove extra spaces.
5. **Removed Duplicates** → used **Data → Remove Duplicates**.
6. **Checked Data Types**:
   - `release_year` as Number
   - `date_added` as Date
   - Text columns cleaned for consistency.

## ✅ Deliverables
- Cleaned dataset saved as `netflix_titles_cleaned.xlsx`
- This README summary
