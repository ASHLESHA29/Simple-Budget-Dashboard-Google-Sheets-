# 💰 Simple Budget Dashboard (Google Sheets)

A clean and interactive **Personal Budget Dashboard** built in **Google Sheets** for tracking monthly income, expenses, savings, debt, and spending categories.

This project is designed as a **1-person, 1-month budget tracker** with a visually structured dashboard inspired by modern spreadsheet finance templates.

---

## 📌 Project Overview

This dashboard helps track and compare:

- **Income**
- **Needs**
- **Wants**
- **Future Savings**
- **Debt Payments**
- **Left to Spend**
- **Planned vs Actual Spending**
- **Category Breakdown**

It uses a **dataset sheet** for raw transaction entries and a **dashboard sheet** for summaries, charts, and category-based spending tables.

---

## ✨ Features

- 📅 **Monthly budget tracking**
- 💵 **Start balance and income overview**
- 📊 **Planned vs Actual comparison chart**
- 🍩 **Left to Spend donut chart**
- 🥧 **Spending breakdown pie chart**
- 📂 **Category-wise expense sections**
  - Needs
  - Wants
  - Future
  - Debt
- 🧾 **Cashflow summary table**
- 📝 **Expense tracker table**
- ☑️ **Checkbox support for paid/completed items**
- 🔄 **Auto-calculated formulas**
- 🎨 **Custom dashboard layout with styled sections**

---

## 🗂️ Sheets Included

### 1. `data`
Contains the raw transaction dataset with the following columns:

- `Date`
- `Type`
- `Main_Category`
- `Sub_Category`
- `Description`
- `Budget`
- `Actual`
- `Due_Day`
- `Notes`

### 2. `Dashboard`
Main dashboard sheet containing:

- Overview section
- Cashflow summary
- Left to Spend chart
- Planned vs Actual chart
- Breakdown chart
- Needs table
- Wants table
- Future table
- Debt table
- Expense tracker
- Spending breakdown

### 3. `Helper` *(optional)*
Used for chart-friendly helper tables (especially for multi-color planned vs actual charts).

---

## 📈 Dashboard Sections

### 🔹 Overview
Displays:
- Start Date
- End Date
- Currency
- Start Balance

### 🔹 Cashflow Summary
Auto-calculates:
- Start Balance
- Income
- Bills / Needs
- Expense / Wants
- Debt
- Savings / Future
- Left to Spend

### 🔹 Left to Spend
A donut chart showing:
- Remaining balance after expenses

### 🔹 Planned vs Actual
A bar chart comparing:
- Planned vs Actual values for:
  - Income
  - Needs
  - Wants
  - Future
  - Debt

### 🔹 Breakdown
A pie chart showing:
- Expense distribution across categories

---

## 🧮 Formula Logic Used

This project uses Google Sheets formulas such as:

- `SUMIF`
- `SUMIFS`
- `FILTER`
- `INDEX`
- `SORT`
- `QUERY`
- `TRANSPOSE`
- `IF`
- `COUNTIF`

Examples:
- Summing category totals
- Pulling due days dynamically
- Auto-filling expense tracker values based on selected date
- Building spending breakdown tables
- Creating helper data for multi-color charts

---

## 📊 Sample Dataset Structure

Example transaction categories used:

- **Income** → Salary, Freelance
- **Needs** → Rent, Electricity, Internet, Groceries, Transport
- **Wants** → Netflix, Spotify, Coffee, Shopping, Beauty
- **Future** → Emergency Fund, SIP, Vacation Fund, Education Fund
- **Debt** → Credit Card Payment, Loan EMI

---

## 🎯 Purpose of This Project

This project was created to practice and demonstrate:

- Spreadsheet dashboard design
- Budget analysis
- Data organization in Google Sheets
- Formula-based automation
- Data visualization using charts
- Real-world finance tracking use case

It is suitable for:

- Portfolio projects
- Data Analyst / Business Analyst practice
- Excel / Google Sheets showcase projects
- College submissions
- Personal finance tracking

---

## 🛠️ Tools Used

- **Google Sheets**
- Spreadsheet formulas
- Charts (Donut, Pie, Bar)
- Manual dashboard design & formatting

---

## 📸 Preview

You can add screenshots of your dashboard here after uploading images.

Example:

```md
![Dashboard Preview](images/dashboard-preview.png)
