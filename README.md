# Lottery Results Analysis (1724 - Present)

This project provides a comprehensive analysis of lottery results from 1724 to present, leveraging **SQL Server Integration Services (SSIS)** and **SQL Server Reporting Services (SSRS)** for streamlined data integration and insightful reporting.

## Objectives

- **Data Integration:** Use SSIS to extract, transform, and load (ETL) historical lottery data from various sources into a centralized SQL Server database.

- **Data Analysis and Reporting:** Implement SSRS to create dynamic reports and dashboards that provide valuable insights, statistical trends, and detailed analysis of historical lottery data.

## Technologies used
-**Visual Studio 2022: ** Data Processing
- **SSIS (SQL Server Integration Services):** To build and automate ETL workflows.
- **SSRS (SQL Server Reporting Services):** To create reports and dashboards to visualize trends and patterns.
- **SQL Server Database(SSMS 2022):** Is the primary data storage solution for processing and analyzing the extensive lottery dataset.

## Project Workflow

### 1. Data Collection and Preparation
- **Data Sources:** Collect lottery results data from reliable historical sources.

- **Data Cleaning and Transformation:** Normalize, clean, and prepare data in a format compatible with SQL Server data collection.

### 2. ETL Pipeline Design (SSIS)
- **Extract:** Build SSIS packages to import raw data into SQL Server.
- **Transform:** Implement transformation processes to clean and format data.
- **Load:** Load transformed data into a centralized database, ready for analysis.

### 3. Data Analysis and Aggregation
- **Statistical Analysis:** Use SQL queries to uncover historical patterns and trends in lottery results.

- **Aggregate:** Develop summary tables and aggregate data for high-level insights and deep analysis capabilities.

### 4. Report and Dashboard Development (SSRS)
- **Build Reports:** Design reports in SSRS to present historical trends and statistical summaries.
- **Create Dashboards:** Create interactive dashboards to allow users to explore data through visualizations and gain deeper insights.

## Folder Structure

```
├── ETL/
│ └── SSIS_Packages/
├── Reports/
│ ├── SummaryReports/
│ └── TrendDashboards/
├── SQL_Scripts/
│ └── AnalysisQueries/
└── Data/
└── HistoricalRecords/
```

- **ETL/SSIS_Packages**: Contains SSIS packages used to extract, transform, and load data.
- **Reports**: Stores SSRS reports and dashboards.

- **SummaryReports**: Contains summary reports of trends and general statistics.

- **TrendDashboards**: Contains interactive dashboards for in-depth visual analysis.

- **SQL_Scripts**: Contains SQL scripts used in data analysis and aggregation steps.

- **Data**: Stores raw and pre-processed historical lottery data.

## How to use

1. **Running SSIS Packages**:
- Open the `ETL/SSIS_Packages` folder and execute the SSIS packages to process and load the data into the SQL Server database.

2. **Executing SQL Scripts**:
- Run the SQL scripts in the `SQL_Scripts/AnalysisQueries` folder to perform data analysis and prepare the data for reporting.

3. **Create Reports**:
- Open `Reports/SummaryReports` and `Reports/TrendDashboards` in SSRS to view and interact with the data visualizations.
