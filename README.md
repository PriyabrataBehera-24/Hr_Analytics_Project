# Power BI Project | HR Analytics Dashboard

Welcome to the "HR Analytics Dashboard" project repository! This project aims to provide practical experience in creating an HR analytics dashboard using Power BI and Microsoft Excel. The project simulates a real-world corporate environment, emphasizing the entire process from problem definition to dashboard creation.

## Project Overview
This project involves analyzing HR data for a company to provide actionable insights into employee demographics, turnover rates, and average tenure. The goal is to create a comprehensive dashboard to facilitate data-driven decisions in the HR department.

## Problem Statement
The company is experiencing challenges in tracking and understanding employee data due to inconsistent and fragmented reporting. Insights are currently gathered through verbal reports and numerous Excel files from various departments. This fragmented approach leads to incomplete and sometimes inaccurate insights, making it difficult to identify key areas for improvement and to make informed decisions.

## Getting Started
Follow these instructions to set up the project locally on your machine.

### Prerequisites
1. Power BI Desktop
2. Microsoft Excel
3. Basic knowledge of data analysis and visualization

### Instructions to Setup the Project
1. Install Power BI Desktop on your local computer.
2. Download the provided Excel data file to your local computer.
3. Open Power BI Desktop and import the Excel data file using the "Get Data" option.

## Data Analysis Using Power BI
1. **Import Data**: Import the Excel data file into Power BI using the "Get Data" option and select the relevant sheets.
2. **Data Cleaning**: Clean and preprocess the data as needed to ensure accuracy and consistency.
3. **Create Measures**: Use DAX functions to create measures for various HR metrics such as employee count, turnover rate, and average tenure.
    - Example: Create an employee count measure using the `DISTINCTCOUNT` function.
    ```dax
    Employee Count = DISTINCTCOUNT(Employees[EmployeeID])
    ```
    - Example: Create a measure for average tenure using the `AVERAGE` function.
    ```dax
    Average Tenure = AVERAGE(Employees[Tenure])
    ```
4. **Visualizations**: Create visualizations such as pie charts, column charts, and waterfall charts to represent the data effectively.
5. **Dashboard Design**: Customize the dashboard with appropriate themes, colors, and layouts to enhance visual appeal and usability.

## Usage
1. Open the Power BI file (.pbix) in Power BI Desktop.
2. Explore the different reports and visualizations to gain insights into the HR data.

## Acknowledgements
1. Special thanks to The Developer for their expertise and contributions to the project.
2. Inspired by real-world HR analytics projects to provide a practical learning experience.

