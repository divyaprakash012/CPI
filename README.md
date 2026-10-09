#  India CPI Inflation Analysis (2013–April 2023)


<p align="left">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Microsoft Excel"/> <img src="https://img.shields.io/badge/Data_Cleaning-4472C4?style=for-the-badge" alt="Data Cleaning"/> <img src="https://img.shields.io/badge/Data_Analysis-7030A0?style=for-the-badge" alt="Data Analysis"/>  <img src="https://img.shields.io/badge/Power_Query-0F6CBD?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white" alt="Power Query"/> <img src="https://img.shields.io/badge/Pivot_Tables-217346?style=for-the-badge" alt="Pivot Tables"/> <img src="https://img.shields.io/badge/Excel_Formulas-107C41?style=for-the-badge" alt="Excel Formulas"/> <img src="https://img.shields.io/badge/Data_Visualization-E97132?style=for-the-badge" alt="Data Visualization"/> <img src="https://img.shields.io/badge/Trend_Analysis-008C95?style=for-the-badge" alt="Trend Analysis"/> <img src="https://img.shields.io/badge/Correlation_Analysis-6A5ACD?style=for-the-badge" alt="Correlation Analysis"/> <img src="https://img.shields.io/badge/Insight_Generation-C65911?style=for-the-badge" alt="Insight Generation"/>
</p>

> **A data analytics project exploring Consumer Price Index (CPI) trends across India’s rural, urban, and combined sectors — with a focus on food inflation, COVID-19, and fuel-related patterns.**

##  Project Overview

Inflation affects household budgets and the cost of everyday essentials. In this project, I analyzed India’s Consumer Price Index (CPI) data to understand how price-index trends changed over time, which categories showed notable movement, and how the COVID-19 period compares with earlier years.

The workbook includes the original CPI dataset, a reshaped/unpivoted table for category-level analysis, and supporting summaries for sector-wise, monthly food-category, pre-/post-COVID, and fuel-versus-category comparisons.

##  Objectives

- Explore CPI trends across **Rural, Urban, and Rural + Urban** sectors.
- Compare year-wise and month-wise patterns in the general index and major CPI categories.
- Examine food inflation, including vegetables, fruits, pulses, cereals, milk, and other food groups.
- Compare selected categories before and after the onset of COVID-19 (using **March 2020** as the reference point).
- Explore how the Fuel and Light index moves alongside transport, education, food and beverages, household goods and services, non-alcoholic beverages, and cereals.
- Organize the data into analysis-friendly tables and derive insights from summaries and comparisons.
## Build an interactive Excel with slicers for year, month, sector, and category. 

<img width="327" height="122" alt="image" src="https://github.com/user-attachments/assets/61630f5c-83b1-4b73-af0e-e2499fc2b442" /> 

## Add clearly defined year-over-year inflation calculations. 

<img width="902" height="612" alt="image" src="https://github.com/user-attachments/assets/b8d54e48-7902-4d84-8998-2630babedccf" /> 

**Inflation peaked at approximately 7% in 2022**
**food and fuel price pressures, before declining to around 3% in 2023.**

## Broader Category Wise Inflation Rate
<img width="710" height="89" alt="image" src="https://github.com/user-attachments/assets/e33a32e1-e4ba-4daf-b8d9-e4f293a7d6f6" /> 


**Food contributes the highest share (44.44%)**
**Luxury (14.81%) and Clothing (11.11%)**
## Workbook Contents

| Worksheet | Purpose |
|---|---|
| `Raw Data` | Source CPI data in its original wide format |
| `CPI Inflation` | Working copy of the CPI data |
| `CPI Unpivot` | Reshaped data with category attributes and values for flexible analysis |
| `Broader Cat. Wise Inflation` | Summary by broader category |
| `YOY Sector Wise Inflation Rate` | Year-wise general-index comparison across sectors |
| `Month Wise food Cat.Inflation` | Monthly and yearly comparison of selected food categories |
| `Food Cat. Wise Inflation` | Food-category comparison by sector and year |
| `Inflation Before & After Covid` | Long-term comparison of selected categories around the COVID-19 period |
| `Fuel Vs Transport`, `Fuel vs Education`, `Fuel vs Food&Beverage`, `Fuel Vs Household`, `Fuel Vs Non Alc`, `Fuel Vs Cereal & Product` | Pairwise comparisons of Fuel and Light with other CPI categories |
| `Sheet1`, `Sheet2` | Supporting summaries/comparison tables |


##  Key Questions Explored

1. How did the general CPI index change over the years across rural and urban sectors?
2. Which broader CPI categories and food groups are worth examining for notable price-index changes?
3. How did selected categories compare before and after March 2020?
4. How did monthly food-category index values vary over time?
5. How did the Fuel and Light index move in relation to selected categories?
6. What patterns appear in the category comparisons and correlation summaries?

##  Tools & Techniques

- **Microsoft Excel** — data review, formulas, summaries, and comparisons
- **Power Query** — data preparation and unpivoting data into a long/tabular structure
- **PivotTables / Pivot summaries** — year-wise, month-wise, sector-wise, and category-wise analysis
- **Exploratory Data Analysis (EDA)** — trend comparison and insight generation
- **Correlation analysis** — exploring the direction and strength of association between selected index series

##  Data Preparation

The workbook contains CPI records organized by sector, year, month, and multiple expenditure categories. The `CPI Unpivot` worksheet restructures the category columns into an attribute/value layout, making it easier to filter and compare categories.

Typical preparation steps for this kind of analysis include:
- Checking column names, data types, and missing values.
- Keeping sector, year, and month fields available for grouping.
- Reshaping category columns into attribute/value rows.
- Grouping data by time period, sector, and category for comparison.
- Reviewing summaries before drawing conclusions.

##  What This Project Helps Demonstrate

- Turning a wide dataset into a structure suitable for analysis.
- Comparing CPI index patterns across time, sectors, and categories.
- Investigating the period around the COVID-19 onset without assuming that timing alone proves causation.
- Using correlation as a descriptive measure of co-movement, not proof that one category causes another.
- Communicating findings through concise, question-led insights.

##  Important Notes

- **CPI index values are not the same as inflation rates.** An index measures price levels relative to a base period; an inflation rate generally measures percentage change in an index over a specified period, such as year over year. Interpret each worksheet according to the measure it contains.
- The COVID-19 comparison is observational. Changes before and after March 2020 should not automatically be interpreted as caused only by the pandemic.
- Correlation indicates association, not causation. Results can also depend on the period, frequency, and method used to calculate the series.
- Please verify the source, base year, and methodology of the original CPI data before using the analysis for formal research or policy conclusions.
 
 <img width="882" height="480" alt="image" src="https://github.com/user-attachments/assets/12997261-9d06-4d16-b61f-a7f53d687755" />

**vegetable prices dropping by approximately 13% in December 2022**
**fruit prices rising by around 7% in February 2023.**

## Inflation Before & After Covid-19 

<img width="1020" height="593" alt="image" src="https://github.com/user-attachments/assets/50231338-55e6-4230-8e9f-db61c4a1db15" /> 

**Food inflation increased from 4% in 2019 to 8% in 2020, while health inflation declined from 7% to 4%. In 2021**

##  How to Explore

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Start with `Raw Data` to review the source structure.
4. Explore `CPI Unpivot` for category-level analysis.
5. Review the summary worksheets for sector-wise, food-category, COVID-period, and fuel comparisons.
6. Validate any conclusion against the underlying data and calculation method.

##  Potential Improvements

- Add charts/screenshots and a concise findings section after validating the final insights.
- Reproduce the transformation and analysis steps in a documented, repeatable workflow.

##  Author

**Divya Prakash Maurya**

*Data Analytics Project — Consumer Price Index (CPI) Inflation Analysis*

Linkedin- www.linkedin.com/in/divya-prakash-maurya-9183313a7
Email ID - divyaprakashoffice@gmail.com

If you find this project useful, feel free to  the repository.
