# SDG 3 Maternal Health Analysis using SQL Server and Power BI

## Project Overview
This project analyzes global maternal and reproductive health indicators related to **Sustainable Development Goal 3 (SDG 3) – Good Health and Well-Being**. The study focuses on understanding maternal health outcomes across countries using data analytics and visualization techniques.

The analysis is based on three important SDG health indicators:

- Maternal Mortality Ratio (SDG 3.1.1)
- Skilled Birth Attendance (SDG 3.1.2)
- Family Planning Coverage (SDG 3.7.1)

The project uses **Microsoft SQL Server** for data storage, cleaning, and transformation, while **Power BI** is used for data modeling, analysis, and interactive dashboard visualization.

This project was completed as part of the **Advanced SQL and Cloud Databases assignment** in the **BSc in Applied Data Science Communication program at General Sir John Kotelawala Defence University (KDU).**

---

## Objectives

- Analyze global maternal health indicators related to SDG 3
- Clean and transform large datasets using SQL Server
- Build a structured relational database
- Create analytical measures using Power BI
- Visualize global health trends through interactive dashboards
- Identify relationships between maternal mortality, skilled birth attendance, and family planning

---

## Dataset

The datasets used in this project were obtained from the **World Health Organization (WHO) Global Health Observatory**.

The analysis includes three major datasets:

- Maternal Mortality Ratio (SDG 3.1.1)
- Skilled Birth Attendance (SDG 3.1.2)
- Family Planning Coverage (SDG 3.7.1)

These datasets contain information such as:

- Country Name
- ISO Country Code
- Reporting Year
- Indicator Value
- SDG Goal Identifier
- Indicator Name

The datasets include information from **over 190 countries across multiple years**, allowing global comparison of maternal health outcomes.

---

## Technologies Used

### Database and Data Processing
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- T-SQL for data cleaning and transformation

### Data Visualization
- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)

---

## Project Workflow

### 1. Data Collection
Global maternal health datasets were obtained from the WHO Global Health Observatory database.

### 2. Data Preprocessing
The raw datasets were imported into SQL Server where several cleaning operations were performed, including:

- Removing rows with missing country names
- Converting text values to numeric format
- Standardizing column names
- Checking and removing duplicate records
- Structuring data for analytical use

### 3. Database Design
A structured relational database was designed with separate tables for each health indicator. A **Countries dimension table** was also created to support efficient data relationships.

The final database follows a **star schema structure**, which improves performance for analytical queries and dashboard visualizations.

### 4. Data Modeling in Power BI
The cleaned SQL datasets were connected to Power BI. Data modeling was performed by creating relationships between tables and developing calculated measures using DAX.

A **Calendar table** was created to support time-based analysis across all indicators.

### 5. Dashboard Development
Several interactive dashboards were created to visualize global maternal health indicators and compare trends between countries.

---

## Dashboard Visualizations

The Power BI dashboard includes multiple visualizations such as:

- Indicator contribution comparison (Pie Chart)
- Country comparison of health indicators (Clustered Column Chart)
- Health indicator radar chart
- KPI summary cards
- Maternal mortality trend analysis (Line Chart)
- Relationship between indicators (Scatter Plots)
- Global health coverage maps
- Country level data tables

These visualizations allow users to explore the data interactively using filters and slicers.

---

## Key Insights

- Global maternal mortality has generally decreased since 2000.
- Skilled birth attendance rates have improved in many regions.
- Countries with higher skilled birth attendance and family planning coverage tend to have lower maternal mortality.
- Significant geographical inequalities still exist between countries.
- Some regions continue to experience high maternal mortality due to limited healthcare access.

---

## Project Demonstration Video

A full walkthrough of the project, including SQL data preparation, Power BI modeling, and dashboard explanation can be viewed here:

**Project Video:**  
https://drive.google.com/drive/folders/1EhGrSC-hKsiJ7UoKJz_oSyNqrQTGPDpR?usp=sharing

---

## Authors

**Group: Avengers Plus**

- WMD Subhashwaree  
- GGI Gamanayaka  
- JANI Jayawardhana  

BSc in Applied Data Science Communication  
General Sir John Kotelawala Defence University (KDU)

---

## License

This project was developed for **academic purposes only**.
