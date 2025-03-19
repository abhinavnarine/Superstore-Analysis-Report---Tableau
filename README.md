# Tableau
# Superstore Sales and Profit Analysis

## Overview
This project focuses on analyzing sales and profit for a Superstore in the United States. The store has rich data on products, regions, categories, and customer segments. The leadership team aims to understand which areas of the business are performing well and identify opportunities for improvement using data visualization techniques in Tableau.

## Key Objectives
- Analyze sales and profit by sub-category
- Create visualizations such as Waterfall Chart, Donut Chart, and Gantt Chart
- Utilize calculated fields and parameters for dynamic analysis
- Understand data joining and blending in Tableau for combining data from multiple sources

## Features
### **1. Data Visualization in Tableau**
- **Waterfall Chart**: To show cumulative impact of sequentially introduced values (profit or loss) over time.
- **Donut Chart**: For a visual representation of categorical data distribution.
- **Gantt Chart**: To analyze project timelines and order fulfillment durations.

### **2. Calculated Fields and Parameters**
- **Calculated Fields**: Used for feature engineering, allowing the creation of new columns based on existing data.
- **Parameters**: Dynamic values replacing constants in calculations, filters, and reference lines.
  1. Create a new parameter.
  2. Display the parameter in Tableau.
  3. Use the parameter in a calculated field.
  4. Apply the calculated field in a Tableau sheet.

### **3. Data Joining and Blending**
#### **Data Joining (For data from the same source)**
- **Inner Join**: Returns matching records from both tables.
- **Left Join**: Returns all records from the left table and matching ones from the right.
- **Right Join**: Returns all records from the right table and matching ones from the left.
- **Full Outer Join**: Returns all records when there is a match in either table.

#### **Data Blending (For data from multiple sources)**
- Keeps the primary and secondary data sources separate.
- Displays aggregated data from the secondary source along with the primary source.

## Tech Stack
- **Tableau**: Data visualization and analysis
- **SQL**: For data extraction and transformation
- **Excel**: Data source for additional insights
- **NoSQL Databases**: If applicable for certain datasets

## Installation & Setup
1. Download and install [Tableau Public](https://public.tableau.com/) or Tableau Desktop.
2. Load the dataset into Tableau.
3. Apply necessary data joins or blending techniques.
4. Create visualizations using calculated fields and parameters.

## Repository Structure
```
📂 Superstore-Analysis
 ├── 📁 Data               # Contains sample datasets (CSV, Excel, etc.)
 ├── 📁 Visualizations     # Tableau workbooks and dashboards
 ├── 📄 README.md          # Project documentation
 ├── 📄 superstore_analysis.twbx # Packaged Tableau Workbook
 └── 📄 insights_report.pdf  # Summary of findings
```

## Contribution
Feel free to contribute by:
- Enhancing existing visualizations
- Adding more calculated fields for better insights
- Improving parameter-based filtering and analysis

## License
This project is open-source and available under the MIT License.

## Contact
For queries or collaboration, reach out via GitHub Issues or email.

---
Happy Analyzing! 🚀
