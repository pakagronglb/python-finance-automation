# Python Finance Automation

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.32.0-FF4B4B.svg)](https://streamlit.io)
[![Pandas](https://img.shields.io/badge/Pandas-2.2.0-150458.svg)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-5.18.0-3F4F75.svg)](https://plotly.com)

A personal finance automation tool that helps you analyse bank statements, categorise transactions, and visualise spending patterns.

## 📋 Features

- **CSV Import**: Upload your bank statement in CSV format
- **Automatic Categorization**: Transactions are automatically categorized based on keywords
- **Custom Categories**: Create and manage your own transaction categories
- **Visual Analytics**: View spending by category with interactive charts
- **Expense Tracking**: Separate analysis for debits (expenses) and credits (income)

## 🚀 Installation

1. Clone this repository
   ```bash
   git clone https://github.com/pakagronglb/python-finance-automation.git
   cd python-finance-automation
   ```

2. Create a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

## 💻 Usage

1. Run the application
   ```bash
   streamlit run main.py
   ```

2. Upload your bank statement CSV file
   - Sample format is provided in `sample_bank_statement.csv`

3. Manage transaction categories
   - Add new categories
   - Assign transactions to categories
   - The app will learn and remember categorizations for future use

## 📊 Data Visualization

The dashboard provides:
- Pie charts of expenses by category
- Summary of total expenses by category
- Overview of incoming payments

## 🔒 Privacy

All data processing happens locally on your machine. No financial data is uploaded to external servers.

## 🙏 Credits

This project was created by following [Tech With Tim's tutorial](https://www.youtube.com/watch?v=wqBlmAWqa6A&ab_channel=TechWithTim) on Python Finance Automation.

## 📄 License

This project is open source and available under the MIT License. 