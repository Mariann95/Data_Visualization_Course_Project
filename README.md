# Automobile Sales Interactive Statistics Dashboard

By Mariann Ács-Kovács

#### [LinkedIn profile](https://www.linkedin.com/in/mariann-%C3%A1cs-kov%C3%A1cs-10032b299/)

## Overview
This project is the final assignment for the "IBM Visualizing Data with Python" course. It demonstrates the use of Plotly
and Dash to create an interactive dashboard that visualizes automobile sales statistics. The dashboard provides insights into yearly sales data and sales trends during recession periods.

## Features
- Interactive dropdown menus to select the type of statistics and specific years for detailed analysis.
- Multiple types of visualizations including line charts, bar charts, and pie charts.
- Dynamic updates based on user input.

## Installation
To run this project, you need to have Python and the necessary libraries installed. 

### Required Libraries
- dash
- pandas
- plotly

You can install the required libraries using pip:
```bash
pip install dash pandas plotly
```
### Running the Dashboard
1. Clone the repository or download the `Plotly_dashboard_automobile_sales.py` file.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the `Plotly_dashboard_automobile_sales.py` file.
4. Run the script using the following command:

```bash
python Plotly_dashboard_automobile_sales.py
```
5. Open your web browser and go to http://127.0.0.1:8050/ to view the dashboard.

## Data

The dataset used in this project is loaded directly from a CSV file available online:

[Historical Automobile Sales Data](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv)

## Dashboard Layout and Functionality

The dashboard consists of the following components:
### Layout
- **Title**: "Automobile Sales Statistics Dashboard"
- **Dropdown Menu**: For selecting the type of statistics (Yearly Statistics or Recession Period Statistics).
- **Year Selection**: Dropdown menu for selecting a specific year (enabled only for Yearly Statistics).

### Visualizations
#### Recession Period Statistics
1. **Average Automobile Sales Fluctuation over Recession Period**: Line chart showing average sales per year during
recession periods.
2. **Average Automobile Sales by Vehicle Type**: Bar chart showing average sales by vehicle type during recession periods.
3. **Total Expenditure Share by Vehicle Type**: Pie chart showing total advertising expenditure by vehicle type during
recession periods.
4. **Effect of Unemployment Rate on Vehicle Type and Sales**: Bar chart showing the effect of unemployment rate on sales
by vehicle type.

#### Yearly Statistics
1. **Yearly Average Automobile Sales**: Line chart showing average annual sales.
2. **Total Monthly Automobile Sales**: Line chart showing total sales per month for the selected year.
3. **Average Vehicles Sold by Vehicle Type**: Bar chart showing average sales by vehicle type for the selected year.
4. **Total Expenditure Share by Vehicle Type**: Pie chart showing total advertising expenditure by vehicle type for the
selected year.

### Callbacks
#### update_input_container
Disables or enables the year selection dropdown based on the selected statistics type.

#### update_output_container
Updates the visualizations based on the selected statistics type and year.

## Usage
- Select "Yearly Statistics" from the first dropdown menu to view detailed yearly data.
- Choose a specific year from the second dropdown menu to filter the data for that year.
- Select "Recession Period Statistics" from the first dropdown menu to view trends during recession periods.

## Conclusion
This dashboard provides a comprehensive view of automobile sales statistics, allowing users to explore data trends and
insights interactively. It leverages the powerful visualization capabilities of Plotly and the interactivity features of Dash to create a user-friendly data exploration tool.
