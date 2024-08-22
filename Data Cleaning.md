# DATA CLEANING

Before using this data for analysis we need to clean it so that it does not provide any irrelevant results. It ensures accuracy and reliability in your analyses. 

1. Check and remove missing or null values

Select the range of column to check for null values. Go to the 'Data' tab and click on 'Filter' option. Click on the filter arrow in the column header and uncheck all options except Blanks.
Excel will filter and display only the cells with null or missing values.

2. Removed unwanted symbols like underscore(_) between two words
   
Create a new column with same heading of the old column who's rows contains unwanted symbols. Use substitute function to remove the symbols(=SUBSTITUTE(text, "_", " ")).
The corrected words appear on the first row. Drag the fill handle (a small square at the bottom-right corner of the cell) down to copy the formula for the entire range. Then delete the old column.

3. Check and remove duplicates

Select the range of cells or the entire table where you want to remove duplicates. Go to the Data tab on the Excel ribbon. Click on Remove Duplicates. In the dialog box, select the columns where you want to check for duplicates. You can check or uncheck columns depending on your needs. Click OK. Excel will remove the duplicate rows and give you a summary of how many duplicates were found and removed.

4. Change the formatting of necessary columns

Select the data range. Right-click and choose 'Format Cells'. Adjust the format settings as needed.

5. Spell Check

Select a cell or column. Go to Review > Spelling. Excel would suggest the correct spelling or similar words if there are wrong spellings. You can choose the value you want and it will get replaced everywhere in the column. If all spellings are correct, it will show a checkmark.

6. Trim the unwanted spaces

Write the TRIM function(=TRIM(A2)). Drag the fill handle (a small square at the bottom-right corner of the cell) down to copy the formula for the entire range.  
