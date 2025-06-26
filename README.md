### 📊 Excel Data Cleaning Project

This project demonstrates a structured approach to **data cleaning in Microsoft Excel**. It includes:
- A **raw dataset** with quality issues.
- A **cleaned dataset** with all cleaning steps documented in **separate worksheets** for clarity and reproducibility.

## 🔧 Cleaning Steps Performed

1. **Auto Fit Columns**  
   Adjusted column widths to ensure all data is fully visible.

2. **Remove Duplicates**  
   Identified and removed duplicate rows to maintain data integrity.

3. **Trim Extra Spaces**  
   Applied the `TRIM()` function to eliminate unwanted leading/trailing spaces.

4. **Handle Blank Cells**  
   Replaced empty cells with appropriate alternate values for consistency.

5. **Spell Check**  
   Conducted spell check to fix textual errors manually.

6. **Data Validation (Drop-down Lists)**  
   Added drop-downs in selected columns to restrict data entry and prevent invalid inputs.

7. **Error Handling using IFERROR**  
   Used formulas like:  
   `=IFERROR([@Quantity]*[@[Price Per Unit]], 0)`  
   This helps prevent formula errors and ensures numeric columns return `0` instead of error messages.

8. **Formatting Numbers & Dates**  
   - Converted currency to plain number format for simplicity.  
   - Changed date fields from DateTime to **Short Date** format (no time component).

9. **Find & Replace**  
   Replaced `"inf"` values in the *Price Per Unit* column with empty cells to maintain numeric consistency.

10. **Gridlines Removed**  
    Disabled gridlines for a cleaner, more professional visual appearance.

## 📁 Files Included

- `RawData.xlsx` – Original uncleaned dataset.
- `CleanedData.xlsx` – Final cleaned version with individual worksheets showing each cleaning step.

## ✅ Purpose

It emphasizes:
- Clarity in documentation  
- Real-world formatting and validation practices  
- Easy-to-follow structure for learning and reuse
