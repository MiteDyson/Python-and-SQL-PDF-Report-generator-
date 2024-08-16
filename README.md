
# Python and SQL PDF Report Generator

This project is a Python-based PDF report generator that extracts data from an SQLite database (`sales.db`) and produces a comprehensive sales report. The project utilizes SQL for data extraction and Python for data processing, visualization, and report generation within a Jupyter Notebook environment.

## Repository Overview

- **Notebook**: `Sales_Analysis.ipynb`
- **Database**: `sales.db`
- **Output**: PDF reports generated from the data in `sales.db`

## Features

- **Data Extraction**: SQL queries are used to retrieve sales data from the `sales.db` SQLite database.
- **Data Visualization**: Sales data is visualized using Python libraries, with charts embedded directly into the report.
- **PDF Report Generation**: The notebook generates a professional PDF report summarizing sales performance.

## Prerequisites

Before running the notebook, ensure you have the following software installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries:
  - `sqlite3`
  - `pandas`
  - `matplotlib`
  - `fpdf` or `reportlab`

You can install the necessary libraries using pip:

```bash
pip install pandas matplotlib fpdf reportlab
```

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MiteDyson/Python-and-SQL-PDF-Report-generator.git
   cd Python-and-SQL-PDF-Report-generator
   ```

2. **Database Setup**:
   - Ensure the `sales.db` file is in the root directory of the repository.
   - If you need to recreate the database, you can use the provided SQL script or populate it with your own sales data.

3. **Running the Jupyter Notebook**:
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Load the `Sales_Analysis.ipynb` notebook.

## Usage

1. **Customize SQL Queries**:
   - Modify the SQL queries in the notebook to extract specific data from the `sales.db` database.
   - Example: Retrieve total sales per region, product, or salesperson.

2. **Generate the Report**:
   - Run all cells in the Jupyter Notebook.
   - The notebook will execute SQL queries, process the data, create visualizations, and generate a PDF report.
   - The report will be saved in the `output/` directory with a timestamped filename.

3. **View the Generated Report**:
   - Navigate to the `output/` directory to find and open the generated PDF report.

## Example Workflow

1. **Data Extraction**:
   - SQL queries are executed to gather necessary data, such as total sales, sales by product, or sales trends over time.

2. **Data Visualization**:
   - The extracted data is visualized using bar charts, line graphs, or pie charts.
   - These visualizations are embedded into the PDF report.

3. **PDF Generation**:
   - A well-structured PDF report is generated, summarizing the sales data and including relevant charts.

## Screenshots

Here are a couple of screenshots from the Jupyter Notebook:

![Data Extraction](https://github.com/user-attachments/assets/cf265d4c-6dfd-43b5-b9e1-5a45025f7100)
*Figure 1: SQL data extraction process in the notebook.*

![PDF Generation](https://github.com/user-attachments/assets/41bc5a38-1b43-4575-8af9-17df4bb67f59)
*Figure 2: PDF report generation in progress.*


## Acknowledgments

I would like to express my gratitude to the following:

- **[Coding Is Fun]**: For guidance and providing a great tutorial for the project. You can checkout the youtube channel for Coding Is Fun [here](https://www.youtube.com/@CodingIsFun)
  

