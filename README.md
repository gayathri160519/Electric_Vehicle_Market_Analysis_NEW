ELECTRIC VEHICLE MARKET ANALYSIS

An end-to-end data analytics project that explores Electric Vehicle adoption trends, manufacturer performance, electric range distribution, and geographic patterns using Python and Power BI.

## 📑 Table of Contents
 
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools & Technologies Used](#tools--technologies-used)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Dashboard Development](#dashboard-development)
- [Dashboard Preview](#dashboard-preview)
- [Dashboard 1 Screenshot](#dashboard-1-screenshot)
- [Dashboard 2 Screenshot](#dashboard-2-screenshot)
- [DAX Calculations](#dax-calculations)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)
- [Conclusion](#conclusion)
  
## 📊 Project Overview
This project analyzes Electric Vehicle (EV) registration data to identify EV adoption trends, manufacturer performance, EV type distribution, electric range analysis, and geographic distribution across counties. The dataset was cleaned and analyzed using Python, and interactive Power BI dashboards were developed to uncover insights and support data-driven decision-making.

## 🗂️ Data Source
Dataset: Electric Vehicle Population Data
Source: Government Open Data Portals
Dataset Size:
Records: 5000
Features: 17 Columns
Key Variables:
- VIN
- County
- City
- State
- Postal Code
- Model Year
- Make
- Model
- EV_Type
- CAFV Eligibility
- Range_Miles
- Legislative District
- DOL Vehicle ID
- Vehicle Location
- Electric Utility
- 2020 GEOID
- Electric Range Log

## 🛠️ Tools & Technologies

- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Visualization & Dashboarding: Power BI
- Documentation: Markdown (README.md)
- Version Control: GitHub
- Dataset Format: CSV

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

- Identified unique records using nunique().
- Handled missing/null values.
- Renamed columns for improved readability.
- Corrected data types.
- Treated outliers using the IQR method.
- Created the Electric Range Log feature.
- Performed data validation and consistency checks.
  
## 🔍 Exploratory Data Analysis (EDA)

Main Questions Explored
- How has EV adoption changed across model years?
- Which manufacturers have the highest EV registrations?
- What is the distribution of BEVs and PHEVs?
- Which counties have the highest EV adoption?
- How does electric range vary across manufacturers?
- What proportion of vehicles are CAFV eligible?

## 📈 Dashboard Development

Developed two interactive Power BI dashboards featuring 12 visualizations to analyze:

- EV adoption trends across model years.
- Top EV manufacturers and counties by registrations.
- BEV and PHEV vehicle distribution.
- Average and maximum electric range performance.
- Electric range distribution patterns.
- CAFV eligibility analysis and percentage distribution.
- Geographic distribution of EV registrations through maps.
- County-wise EV adoption using treemap visualization.
- Detailed vehicle-level information through tabular reporting.
- Interactive filtering with slicers for Model Year, EV Type, Make, County, City, Utility Provider, and CAFV Eligibility.

📊 Dashboard Preview

Dashboard 1: EV Adoption & Market Overview

<img width="1186" height="680" alt="13" src="https://github.com/user-attachments/assets/c3826994-82b1-4a3e-9497-a43a867411e4" />

Dashboard 2: Geographic & Performance Insights

<img width="1175" height="667" alt="14" src="https://github.com/user-attachments/assets/1c9849f6-311f-47af-b11d-ee28f520e5ac" />



📐 DAX Calculations

Created DAX measures using functions such as COUNT, DISTINCTCOUNT, AVERAGE, MAX, CALCULATE, SUMMARIZE, TOPN, MAXX, and VAR to generate KPI metrics and business insights, including:

- Total EVs
- Total Manufacturers
- Total Models
- Average Electric Range
- Maximum Electric Range
- Total Counties
- Total Cities
- CAFV Eligible Vehicles
- BEV Count
- PHEV Count
- Top Manufacturer
- Top EV County

## 💡 Key Insights

- Tesla is the leading EV manufacturer by registrations.
- BEVs significantly outnumber PHEVs.
- EV adoption has grown steadily in recent model years.
- A few counties account for the majority of EV registrations.
- Newer EV models generally offer higher electric ranges.
- CAFV-eligible vehicles represent a large share of the EV population.

## 🚀 Recommendations

- Expand charging infrastructure in high-growth counties.
- Promote EV adoption in low-registration regions through incentives.
- Encourage manufacturers to increase vehicle range.
- Support CAFV-eligible vehicle programs to accelerate clean-energy adoption.
- Monitor county-level adoption trends for targeted policymaking.

## 📁 Project Structure

├── data/
│   ├── Raw_EV_Data.csv
│   └── Cleaned_EV_Data.csv
├── notebooks/
│   └── EV_EDA.ipynb
├── dashboard/
│   └── EV_Dashboard.pbix
├── images/
│   └── Dashboard_Screenshots.png
└── README.md

## ⚙️ How to Use

- Download the project files.
- Review the Python notebook for EDA and data preprocessing.
- Access the cleaned EV dataset used for analysis.
- Open the Power BI report (.pbix file).
- Explore the interactive dashboards using slicers and filters.
- Analyze EV adoption, manufacturer performance, electric range, and geographic distribution insights.
  
## ✅ Conclusion

The analysis reveals a growing preference for Battery Electric Vehicles, with Tesla leading market adoption. EV registrations have increased significantly over time, particularly in major counties. The findings demonstrate how data analytics and visualization tools can support understanding of EV market trends and sustainable transportation initiatives.
