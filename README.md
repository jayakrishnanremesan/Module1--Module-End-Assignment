**Module-End-1, Module End  Assignment-“Data Cleaning, Analysis & Visualization with Excel”**
Steps followed in this assignment; 
1. Imported the data files. Imported raw datasets into Power Query Editor and loaded the processed outputs.
2. Data Cleaning & Preparation
• Duplicate & Error Handling: Used Power Query’s Remove Duplicates and Replace Values/Fill features to eliminate redundant records and resolve missing or inconsistent entries.
• Data Type & Format Standardization: Corrected formatting inconsistencies by enforcing strict column data types (Date, Currency, Whole Number, Text) and applying text transformations (Trim, Clean, Capitalize Each Word).
• Column Removal: Remove irrelevant "sub_Category" column directly within the Power Query transformation steps to keep the data model lean and focused.
• Data Validation: Applied Excel Data Validation rules on final workbook tables.
• Duplicate Removal: Using Excel’s Remove Duplicates tool checked for duplicate values in the data to ensure data .
• Handling Missing & Inconsistent Data: Located blank cells and standardized inconsistent text entries (e.g., casing, extra spaces) using functions like TRIM(), PROPER(), and targeted imputation/replacement.
3. Logical & Text Operations: Applied conditional logic (IF) function- =IF(Sales_Fact[@[Total_Amount]]>500, "High Value", "Standard").
4. Table Merging: Combined relational tables using VLOOKUP. 
5. Advanced Summarization & Statistical Analysis
• Descriptive Statistics: Generated comprehensive statistical profiles—Mean, Median, Mode, Standard Deviation, Variance, Minimum, and Maximum—using Excel statistical functions and the Analysis ToolPak.
• Pivot Tables: Created Pivot Tables to group and summarise data.
6. Data Visualization & Interactive Dashboard. created summarised data using pivot tables into a new worksheet. Selected the pivot tablle baased on which i needed to create chart types.
created pivot table directly from the dales datasheet. NB: sheetS categories and stock, payment chart are pivot tables directly created from the sales data sheet. Then created different chart types
7. Interactive Dashboard: Created a dashborad on another worksheet. Pivot Charts, and visual summaries onto a unified dashboard connected with Slicers. created dashboard with PivotCharts, and visual summaries of category and sum of stocks, payment type and count of customers, year wise sum of quantity and category wis sum oof cost.
