# Elevate_Lab_Internship_Task1
🧹 Internship Task 1 — Data Cleaning and Preprocessing on the Netflix Movies and TV Shows dataset using Python and Pandas. This project focuses on handling missing values, removing duplicates, standardizing formats, and preparing data for further analysis and visualization.


# Task 1 – Data Cleaning and Preprocessing (Netflix Dataset)

## Dataset
**Source**: Netflix Movies and TV Shows dataset (`netflix_titles.csv`)

## Tools Used
- Python
- Pandas

## Cleaning Steps Performed

1. **Removed Duplicates**  
   - Used `.drop_duplicates()` to remove repeated records.

2. **Handled Missing Values**  
   - Dropped rows with missing `title`.
   - Filled missing `director`, `cast` with "Not Available".
   - Filled missing `country` with "Unknown".
   - Filled missing `rating` and `duration` with "Unknown".
   - Parsed `date_added` to proper datetime format using `pd.to_datetime()`.

3. **Standardized Text**  
   - Trimmed leading/trailing spaces in string columns.
   - Standardized column headers to lowercase and replaced spaces with underscores.

4. **Fixed Data Types**  
   - Ensured date format consistency.
   - Other fields converted to string type for uniformity.

## Output
- ✅ Cleaned file: `netflix_titles_cleaned.csv`
- ✅ Ready for analysis or visualization

## Sample Interview Questions Covered
- How do you handle missing values?
- How do you treat duplicates?
- How do you standardize inconsistent text?
- How do you fix inconsistent date formats?
