# Global-Happiness-Report-Analysis

📌 Project Overview

This project analyzes the World Happiness Report dataset, focusing on factors that influence happiness scores across different countries and years.
Using Power Query for data preparation and Power BI for visualization, the analysis provides insights into global well-being, regional differences, and the key drivers of happiness.

🎯 Aim of the Project

The aim of this project is to analyze and visualize data from the Global Happiness Report to understand the key factors that influence happiness across different countries and years. By exploring indicators such as GDP per capita, social support, life expectancy, freedom, generosity, and corruption perception, the project seeks to provide insights into global well-being trends and highlight patterns that shape the quality of life worldwide.

🗂️ Files in this Repository

->Global Happiness Report Analysis.pbix → Power BI Dashboard file with all visuals and insights.
->appended years.xlsx → Cleaned dataset prepared in Power Query, containing multiple years of happiness data.

⬇ Download Link
-> https://www.kaggle.com/datasets/unsdsn/world-happiness

📊 Key Features of the Dashboard

Country-wise Happiness Score & Ranking 📈
Comparison of factors such as:

-Economic Production (GDP per Capita) 💰
-Social Support (Family & Community) 🤝
-Life Expectancy (Health) 🏥
-Freedom of Choice 🕊️
-Generosity 💡
-Trust/Perception of Corruption ⚖️
-Regional analysis of happiness trends 🌍
-Year-over-year comparison of global scores 📅

Data Cleaning & Preparation Steps
Load Data: Ingested the Excel file and opened it in the Power Query Editor (PQE) for transformation.
Structural Review: Established relationships between the raw data sheets.

Column Standardization:
Renamed similar columns across all sheets to a common, matching name.
Removed unnecessary columns to streamline the dataset.

Data Quality Assurance:

Validated and Corrected Data Types to ensure consistency with the reference sheet structure.
Checked for and Addressed Null Values in key columns.
Region Data Remediation (Harmonization for Merging):
Created a Region Reference: Appended the 2015 and 2016 sheets, removing duplicates, to create a stable reference table (Append15&16) for the Region column.

Merged Region Data: Performed a Left Join (Merge) from the main sheets to the reference table (Append15&16) to populate the missing Region values.

Handled Mismatches: Corrected remaining nulls by identifying and renaming inconsistent country names across sheets and re-merging for a complete match.

Updated Missing Data: Manually updated the Region value for the Gambia country in the 2019 sheet using external data, as no internal reference was available.

Final Master Table Creation:

Added a Year column to each processed sheet, entering the corresponding reporting year.
Appended all individual year tables into a single, comprehensive table named Master.

🚀 How to Use

-Clone or download this repository.
-Open Mini Project Data.pbix in Power BI Desktop.
-Explore the interactive dashboard:
-Drill down into happiness score contributors.
-Use appended years.xlsx if you want to inspect or transform the raw dataset.

🛠️ Tools & Technologies

-Power Query (ETL) – Data transformation & cleaning
-Excel – Storing and preparing datasets
-Power BI Desktop – Dashboard creation & analysis

📸 Dashboard Preview

<img width="1379" height="769" alt="Image" src="https://github.com/user-attachments/assets/e898235a-a100-4656-bc1b-deb3ba4f181e" />

<img width="1374" height="777" alt="Image" src="https://github.com/user-attachments/assets/dc29a0f0-5905-4a8f-a45b-7a9e9e87eb42" />

We have made another dashboard: https://github.com/assualduaa/Global-Happiness-Report.git

![Image](https://github.com/user-attachments/assets/60829ca0-b906-46f9-a472-bf649ef69820)

![Image](https://github.com/user-attachments/assets/d75218bd-6582-4447-b3ed-1d2df8e74d78)

Conclusion

The Global Happiness Report analysis highlights the significant role of economic, social, and governance factors in shaping the well-being of nations. By comparing countries and regions over time, the project demonstrates that happiness is not determined by a single metric, but by a balanced combination of GDP per capita, social support, life expectancy, freedom, generosity, and trust in institutions.

The interactive dashboards provide a clear and engaging way to explore these patterns, enabling policymakers, researchers, and the public to better understand the drivers of happiness. Ultimately, the project emphasizes that sustainable progress requires improving both economic prosperity and social well-being.











