# T20 Performance Analyzer

The **T20 Performance Analyzer** is a data-driven tool designed to analyze the performance of batsmen and bowlers in the T20 World Cup. By extracting data from ESPN, cleaning and transforming it into a usable format, and leveraging Power BI, the project provides interactive dashboards for player performance analysis and team selection.

## Features

- **Data Extraction & Cleaning**: Extracts raw data from ESPN, cleans it using Jupyter Notebook, and transforms it into CSV format.
- **Player Performance Analysis**: Dynamic Power BI dashboards allow for filtering and detailed performance analysis of batsmen and bowlers.
- **Team Selection Tool**: Offers a feature in Power BI that enables the selection of the best 11 players based on performance metrics and custom criteria.

## Tools & Technologies

- **Jupyter Notebook**: Used for data cleaning and transformation of the extracted data into a CSV file format.
- **Power BI**: Employed to transform the cleaned data and create interactive dashboards for performance analysis and team selection.
- **Python**: Utilized within Jupyter Notebook for data manipulation and cleaning.
- **ESPN**: Data source for T20 World Cup player statistics.

## Project Workflow

1. **Data Collection**: Data is sourced from ESPN, containing statistics of players participating in the T20 World Cup.
2. **Data Cleaning & Transformation**: 
    - Jupyter Notebook is used to clean the raw data by handling missing values, removing inconsistencies, and formatting it for analysis.
    - The cleaned data is converted into CSV format.
3. **Data Visualization**: 
    - Power BI is utilized to load the CSV data and transform it for visualization.
    - Dynamic dashboards are created to allow users to filter player performances based on specific parameters like runs scored, wickets taken, strike rate, and economy rate.
4. **Best 11 Selection**: 
    - Power BI dashboards offer functionality to select the best 11 players based on user-defined criteria for team formation.

## Installation & Usage

### Prerequisites
- Python (with Jupyter Notebook)
- Power BI
- Necessary Python libraries (Pandas, Numpy, etc.)

### Steps

1. **Data Extraction**:
   - Extract data from ESPN’s T20 World Cup statistics.
   
2. **Data Cleaning**:
   - Open the Jupyter Notebook file.
   - Run the cleaning and transformation script to convert the data into CSV format.

3. **Load CSV in Power BI**:
   - Import the cleaned CSV data into Power BI.
   - Create and customize the dashboards for player analysis.

4. **Analyze & Select**:
   - Use the Power BI dashboard to analyze batsmen and bowlers based on the problem-specific filters.
   - Select the best 11 players using the dashboard.



