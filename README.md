# SmartBudget Manager

An Excel workbook to track your monthly income and expenses, see your balance and get a warning when you go over budget. No formulas to write and no macros.

## What it does

- Records income and expenses in a simple table
- Sorts expenses into categories: Food, Transport, Rent, Health, Education
- Calculates total income, total expenses and the monthly balance automatically
- Shows a pie chart of expenses by category
- Shows **WITHIN BUDGET** (green) or **OVER BUDGET** (red) against your monthly budget

## What you need

- Microsoft Excel 2016, 2019, 2021 or Microsoft 365 (or a compatible application)
- The file `SmartBudget_Manager.xlsx`
- No internet connection

## Get started in 4 steps

1. Open `SmartBudget_Manager.xlsx`. If Excel shows **Protected View**, click **Enable Editing**.
2. Go to the **Categories** tab and set your monthly budget for each category.
3. Go to the **Transactions** tab. In the first empty row, enter the date, a description, the type (**Income** or **Expense**), the category (expenses only) and the amount in the **Income** or **Expense** column.
4. Go to the **Dashboard** tab to read your totals, balance, budget status and chart.

## The three worksheets

| Worksheet | Purpose |
|---|---|
| Dashboard | Shows total income, total expenses, balance, budget status and the chart (read only) |
| Transactions | Where you enter income and expenses (rows 4 to 50) |
| Categories | Expense categories and the monthly budget of each |

## Good to know

- Never type in the **Month** column or on the Dashboard: they contain formulas.
- Put an income only in **Income** and an expense only in **Expense**.
- Choose the category from the drop-down list.
- The sheets are not locked by default. Save a backup copy regularly.

## Limitations

- **One month per file:** the Dashboard adds all transactions and does not filter by month.
- **47 transactions maximum:** only rows 4 to 50 are counted.
- **Five categories only:** Food, Transport, Rent, Health and Education.
- **Overall warning:** OVER BUDGET is based on the total budget, not on each category.
- **One currency, one user** at a time; no internet or sharing features.
- **Formulas are not locked**, so they can be overwritten by mistake.

## Documentation

- `SmartBudget_User_Guide_Sara_Benachour_CPI2.docx` – step-by-step guide with screenshots
- `Software_Requirements_SmartBudget_Sara_Benachour_CPI2.docx` – requirements

## Support

support@smartbudget.example (example address for this course project)
