
# Retail Sales Dataset Cleaning

## 📁 Files Included
- `Cleaned_Retail_Sales_Analysis.csv` – The cleaned dataset
- `data_cleaning_script.py` – Python script used for cleaning
- `README.md` – This file (summary of changes)

## 🧼 Data Cleaning Summary

This dataset was cleaned and pre-processed to make it suitable for analysis. The following steps were taken:

1. ✅ Renamed the column `quantiy` to `quantity` to fix a typo.
2. 🕓 Converted `sale_date` from string to datetime format.
3. ⏰ Converted `sale_time` from string to time format.
4. 🧹 Removed any duplicate rows.
5. 🧩 Handled missing values using **forward fill** for:
   - `age`
   - `quantity`
   - `price_per_unit`
   - `cogs`
   - `total_sale`
6. 📤 Exported the cleaned dataset as `Cleaned_Retail_Sales_Analysis.csv`.

This cleaning ensures consistent data types, no nulls, and no duplicate entries for smooth analysis.

---

**Prepared by:** Arya Jadhav  
**Internship Task:** Data Cleaning and Preprocessing

