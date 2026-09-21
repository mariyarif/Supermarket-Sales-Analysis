# Supermarket Sales Analysis

## Project Overview
This project analyzes supermarket sales data to identify useful business insights about products, branches, categories, customers, payment methods, and customer ratings.

## Dataset
Dataset source: Google Sheets
https://docs.google.com/spreadsheets/d/1QIX__4VObHFMEXnRM2xJyXmB5JAB2peHrJcQ41_U9TE/edit?usp=sharing

The dataset contains 500 sales transactions and 13 columns: Invoice ID, Date, Branch, City, Customer Type, Gender, Product, Category, Quantity, Unit Price, Payment, Rating, and Sales.

## Objectives
- Inspect and clean the dataset.
- Check missing and duplicate values.
- Verify Sales = Quantity × Unit Price.
- Analyze sales by product, branch, city, and category.
- Analyze payment methods, customer types, and ratings.
- Create charts and summarize business insights.

## Technologies Used
- Python
- Pandas
- Matplotlib
- OpenPyXL
- Google Colab / Jupyter Notebook

## Setup and Run
1. Place `SUPER MARKET DATA.xlsx` in the `data` folder.
2. Open `Mariya_Supermarket_Sales_Analysis.ipynb` in Google Colab or Jupyter Notebook.
3. Update the dataset path if necessary.
4. Run the notebook cells from top to bottom.

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Key Results
- Total sales: ₹244,411.08
- Total quantity sold: 2,768 units
- Total transactions: 500
- Highest-selling product: Cheese — ₹27,906.30
- Highest-performing branch: Branch C — ₹72,469.45
- Highest-selling category: Beverages — ₹56,108.24
- Most-used payment method: UPI — 127 transactions
- Average customer rating: 3.99/5
- Average transaction value: Normal ₹497.07; Member ₹483.14

## Business Recommendations
- Maintain sufficient stock of high-selling products such as Cheese.
- Study the performance of Branch C in Mumbai.
- Ensure good availability of high-selling categories such as Beverages.
- Continue supporting UPI payments.
- Use customer spending patterns for membership offers.
- Improve customer service and shopping experience to increase ratings.

## Project Structure
```text
supermarket_sales_analysis/
├── data/
│   └── SUPER MARKET DATA.xlsx
├── notebooks/
│   └── Mariya_Supermarket_Sales_Analysis.ipynb
├── reports/
│   └── Mariya_Supermarket_Sales_Analysis_ProjectReport.docx
├── src/
├── requirements.txt
└── README.md
```
