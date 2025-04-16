# Excel Data Analysis Showcase: Retail Sales Dataset

## Project Overview

This repository demonstrates data analysis capabilities using Microsoft Excel, focusing on a retail sales dataset. The analysis covers data cleaning, manipulation, calculation, summarisation, and visualisation techniques commonly used in data analysis workflows.

The original Excel workbook (`retail_sales_dataset_Master - Justin Craciun.xlsx`) contains multiple sheets, each showcasing different skills:

---

### 1. `retail_sales_dataset` Sheet

* **Content:** The primary dataset containing detailed transaction records.
* **Columns Include:** Transaction ID, Date components (Day, Month, Year, Full Date), Customer ID, Gender, Age, Generation, Product Category, Quantity, Price per Unit, Total Sales.
* **Skills Demonstrated:**
    * Data Organisation: Structuring raw data effectively.
    * Calculated Fields: Evidence of commission calculations (`Commision 2023`, `Commision 2024`) directly within the table, likely using Excel formulas.
    * Date Handling: Separate and combined date fields suggest potential date manipulation or formatting.

---

### 2. `Transactions` Sheet

* **Content:** A focused table likely used to demonstrate specific lookup functionalities. Contains Transaction ID, Total Sales, Product Category, and a concatenated field.
* **Skills Demonstrated:**
    * **Lookup Functions:** Explicit examples using `VLOOKUP` (including referencing columns dynamically with `COLUMN()`) and the more modern `XLOOKUP` to retrieve data based on Transaction ID.
    * **Text Functions:** Use of `CONCATENATE` (or potentially `&` operator or `TEXTJOIN`) to combine data from different cells.

---

### 3. `PivotTable` Sheet

* **Content:** A summary report generated from the main dataset.
* **Analysis:** Aggregates `Sum of Total Sales`, broken down by `Product Category` and customer `Generation`, potentially filtered or grouped by `Gender`.
* **Skills Demonstrated:**
    * **Pivot Tables:** Creating dynamic summary reports from raw data.
    * Data Aggregation: Summarising key metrics (Total Sales) across different dimensions.
    * Data Grouping & Filtering: Organising pivot table rows/columns and potentially applying filters for focused analysis.

---

### 4. `Task 2` Sheet

* **Content:** Appears to be a separate exercise, possibly involving student scores, used to demonstrate specific Excel features and formulas.
* **Skills Demonstrated (based on descriptions in the sheet):**
    * **Filtering & Sorting:** Applying basic data manipulation techniques.
    * **Statistical Functions:** Calculating averages (`AVERAGE`) and finding maximum values (`MAX`).
    * **Advanced Formulas:** Using dynamic array functions like `FILTER` combined with `TEXTJOIN` for complex summaries (e.g., finding the top student per subject dynamically).
    * **Conditional Formatting:** Applying visual rules to highlight data (e.g., highest/lowest scores).

---

## Conclusion

This workbook serves as a practical example of using Excel for data analysis, covering data preparation, calculation using various formulas (including lookups and text functions), data summarisation with Pivot Tables, and applying specific data manipulation techniques like filtering, sorting, and conditional formatting.
