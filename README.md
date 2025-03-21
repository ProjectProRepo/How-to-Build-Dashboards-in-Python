# How to Build Dashboards in Python

This repository provides a Python-based solution for building interactive dashboards using Dash and Plotly. It demonstrates how to visualize sales data effectively, extract key performance indicators (KPIs), and generate insights through data-driven visualizations. The project loads sales and product data from Excel files and processes them using Pandas before creating interactive dashboards. For a detailed explanation of the code in this repository, visit the page: [How to Build Python Dashboards by ProjectPro](https://www.projectpro.io/article/build-python-dashboards/1102)

## Project Structure

- **Python_Dashboards.ipynb**: The main Jupyter Notebook containing code to load data, process it, and create visualizations.
- **sources/**: Contains raw data files used in the project.
  - **Product Details.xls**: Provides details of the products sold.
  - **Sales Orders.xls**: Contains order details, including sales figures, quantities, and customer information.

## Requirements

To run this project, ensure you have the following Python libraries installed:

```sh
pip install pandas numpy dash plotly dash-bootstrap-components openpyxl
```

## How to Run the Notebook

1. Clone this repository:

   ```sh
   git clone https://github.com/ProjectProRepo/How-to-Build-Dashboards-in-Python.git
   ```

2. Navigate to the project directory:

   ```sh
   cd How-to-Build-Dashboards-in-Python
   ```

3. Open the Jupyter Notebook:

   ```sh
   jupyter notebook Python_Dashboards.ipynb
   ```

4. Execute the notebook cells to load and analyze the data, and generate the dashboard.

## Features

- **Data Loading & Processing**: Reads sales and product data from Excel files.
- **Key Performance Indicators (KPIs)**: Calculates revenue, expenses, profit, sales margin, and discounts.
- **Interactive Visualizations**: Generates scatter plots and geographic sales distribution using Dash and Plotly.
- **Dashboard Development**: Implements a Dash web app for interactive data exploration.

## Expected Output

The project will generate:

- A summary of key metrics like revenue, profit, and expenses.
- A scatter plot showing sales vs. profit by product category.
- A map visualization displaying sales data by city.
- An interactive web-based dashboard for real-time data exploration.

## Special Thanks

Special thanks to [Chakrit Thong-ek](https://github.com/thongekchakrit/dashboard_dash_mock_sales) for inspiring the code.
