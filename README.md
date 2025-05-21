# COVID-19-DATA Project

## Task:
Design a COVID-19 Global Dashboard that visually presents key pandemic data, including case numbers, vaccination progress, and fatalities across different countries.
## Goal:
Provide an interactive and data-driven platform that enables users to track global COVID-19 trends, understand vaccination efforts, and analyze the impact of the pandemic over time, supporting informed decisions and awareness.

## The process of Exploratory Data Analysis (EDA) in Power Query within Power BI,

### Importing Data into Power Query
- Opened Power BI and went to Power Query Editor (Transform Data).
- Imported datasets (Excel, CSV) as my data was in csv file
- Made sure columns were correctly mapped for consistency and the headers were clear.

### Data Cleaning
- Removed unnecessary columns that don’t contribute to the analysis.
- Renamed columns for clarity and uniformity.
- Dealt with missing values: 
  - Used Replace Values to fill gaps with null, mean, median, or mode.
  - Apply Removed Rows that were excessive missing data exists.
- Fixed inconsistent data formats and types, ensuring correct Date, Number, Text types. 

### Creating a Data Model
- Opened the Model View in Power BI.
- Defined relationships between tables:
- One-to-Many or Many-to-Many relationships for different datasets.
- Use Dated tables for time-based analysis

### Removing Duplicates
- Identified columns where duplicates existed (Home -> Remove Duplicates). Removed 8 data entries that were duplicates
- Validated the dataset after duplicate removal by checking unique values.

### Transforming Data
- Created Calculated Columns: Add custom metrics, (vaccination rate = total vaccinated / population). Performed DAX
- Pivot/Unpivot Data: Reshaped tables for better analytics.

### Joining Tables Using Relationships
- Used Merge Queries (Home -> Merge Queries).
- Selected the primary key i.e. (Country, Date) for merging.

### Loaded and Visualize in Power BI
- Clicked Close & Apply to load cleaned data into Power BI.
- Used Power BI visuals to analyze trends:
- Line charts for case progression.
- Bar charts for country-wise comparisons.

## Findings from the COVID-19 Dashboard:
1.	Global Case Trends:
- 765 million total reported new cases worldwide.
- Yearly breakdown: 
  - 61M (7.97%) in 2020
  - 80M (10.47%) in 2021
  - 200M (26.13%) in 2022
  - 423M (55.21%) in 2023-2024
2.	Vaccination Progress:
- 13 billion people received at least one dose.
- 2 billion booster doses administered globally.
- Total vaccinations: 5 billion doses given worldwide.
### 3.	Death Toll Analysis:
- 7 million total COVID-related deaths.
- Yearly breakdown: 
    - 0.3M (4.52%) in 2020
    - 1M (17.69%) in 2021
    - 2M (26.88%) in 2022
    - 4M (50.29%) in 2023-2024
### 4.	Country-Specific Insights:
- Highest new cases reported in United States, China, India, France, and Germany.
- Highest new deaths recorded in United States, Brazil, India, Russia, and Mexico.
## Recommendations:
- Strengthen Global Coordination: Ensure equitable vaccine distribution, especially in underserved regions.
- Expand Booster Campaigns: Increase awareness and access to booster doses to enhance long-term immunity.
- Improve Data Transparency: Countries should consistently report real-time figures to aid better policy-making.
- Targeted Interventions: High-risk regions should adopt stricter measures during infection surges.
- Public Health Investments: Strengthen healthcare infrastructure to improve response capabilities for future pandemics.
- Continuous Monitoring: Regular assessment of COVID-19 trends to anticipate potential outbreaks.
## Data Source
Kaggle

