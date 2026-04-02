# Mulima Finance

## Project Overview
Mulima Finance is a financial management application designed to help users track their income and expenses, set budgets, and achieve savings goals. The application provides users with intuitive dashboards and detailed reports to analyze their financial health.

## Features
- **User Authentication**: Secure sign-up and login features.
- **Dashboard**: Visual representation of financial status, including graphs and charts.
- **Budgeting**: Set budgets for various spending categories.
- **Income Tracking**: Record and categorize income sources.
- **Expense Tracking**: Detailed logging of expenses with category support.
- **Reports**: Generate monthly and yearly financial reports.
- **CSV Import/Export**: Easily import or export financial data in CSV format.

## Setup Instructions
1. **Clone the Repository**:  
   `git clone https://github.com/CodeEdge-ai/mulima-finance.git`
2. **Navigate to the Project Directory**:  
   `cd mulima-finance`
3. **Install Dependencies**:  
   `npm install`
4. **Configure Environment**:  
   Create a `.env` file based on the provided `.env.example` and set your configuration variables.
5. **Run the Application**:  
   `npm start`

## CSV Format Specifications
When importing or exporting financial data, the CSV file must adhere to the following format:
- **Header Row**: The first row should contain the headers: `Date, Description, Amount, Category`
- **Date**: Format should be `YYYY-MM-DD`
- **Description**: A brief description of the transaction.
- **Amount**: Numeric value representing the transaction amount. Use negative values for expenses.
- **Category**: The category under which the transaction falls (e.g., Food, Transportation, Entertainment).

### Example CSV Content
```csv
Date,Description,Amount,Category
2026-04-01,Income from Freelance Work,2000.00,Income
2026-04-02,Grocery Shopping,-150.00,Food
```

## Troubleshooting Guide
- **Failed to Start Application**: Ensure all dependencies are installed and environment variables are set correctly.
- **CSV Import Issues**: Check that the CSV file has the correct format and headers. Ensure there are no extra commas or missing values.
- **Data Not Appearing**: Verify that your database is correctly set up and that migrations have been run.
- **Authentication Errors**: If you encounter login issues, ensure your credentials are correct. Consider resetting your password if necessary.

For further assistance, please refer to the [issues section](https://github.com/CodeEdge-ai/mulima-finance/issues). If you encounter a problem not listed here, feel free to open a new issue with a detailed description.