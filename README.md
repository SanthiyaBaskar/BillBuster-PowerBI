# BillBuster 💸 – Monthly Expense Tracker

**BillBuster** is a financial analytics dashboard built in Power BI. It helps users or FinTech teams track monthly spending, spot overspending areas, and plan budgets effectively.

---

## 📊 Objective

To provide clear insights into how users spend money across various categories, track trends over time, and optimize financial decision-making.

---

## 🧾 Dataset

Excel File: `MonthlyExpenses.xlsx`

| Column       | Description                               |
|--------------|-------------------------------------------|
| Date         | Date of transaction                       |
| Category     | Expense type (Food, Rent, Utilities, etc) |
| Amount       | Expense amount in INR                     |
| Payment Mode | UPI, Cash, Credit Card, etc.              |
| Month        | Month of transaction                      |

---

## 📈 Visuals Used

- **Donut Chart** – Category-wise Spending
- **Bar Chart** – Payment Method Breakdown
- **Line Chart** – Daily Expense Trend
- **Card** – Total Expenses
- **Card (DAX)** – Avg Daily Spend
- **Table** – Expense Log
- **Slicer** – Category or Payment Mode

---

## 🧠 DAX Measure

```DAX
Avg Daily Spend = 
AVERAGEX(VALUES(MonthlyExpenses[Date]), CALCULATE(SUM(MonthlyExpenses[Amount])))

---

📸 Dashboard Preview

[Dashboard Screenshot](billbuster-preview.png)

---

📁 Files Included

MonthlyExpenses.xlsx – Source data

Diya 5.pbix – Power BI dashboard

billbuster-preview.png – Screenshot

README.md – Project info

---

🛠️ Tools Used

Microsoft Power BI Desktop

Excel

---

Built by Santhiya Diya to showcase financial analytics skills using Power BI 🚀