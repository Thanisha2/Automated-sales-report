# Automated Sales Report Generator

A Python automation script that reads sales data from MySQL,
analyzes it using Pandas, and generates a PDF report automatically.

## Tech Stack
- Python, MySQL, Pandas, FPDF2, Schedule

## Features
- Connects to MySQL database
- Analyzes sales by product and region
- Generates formatted PDF report
- Scheduled to run daily at 9 AM

## How to Run
pip install mysql-connector-python pandas fpdf2 schedule
python report_generator.py
