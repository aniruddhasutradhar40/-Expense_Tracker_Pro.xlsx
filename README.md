# 💰 Expense Tracker Pro

A fully-featured, formula-driven **Excel expense tracker and budgeting dashboard** — no add-ins, no macros, just a clean single workbook that turns raw transactions into real-time financial insights.

![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Features

- **📊 Live Dashboard** — Total income, total expenses, net savings, and savings rate update automatically as you log transactions.
- **🎯 Budget Utilization Tracking** — See budget vs. actual spend per category, with status flags (`✓ ON TRACK`, `⚡ NEAR LIMIT`, `⚠ OVER`).
- **📈 Monthly Trend Analysis** — 10-month rolling view of income, expenses, savings, cumulative savings, and net worth.
- **🧮 50/30/20 Rule Compliance** — Automatically checks your spending plan against the Needs/Wants/Savings benchmark.
- **📝 Transaction Ledger** — Simple date-in, category-out logging with payment method and notes.
- **📌 Key Insights & Recommendations** — Auto-generated financial health summary and action items based on your data.
- **📉 Built-in Charts** — Category breakdown and trend charts embedded directly in the Dashboard sheet.
- **🔗 Zero External Dependencies** — Pure Excel formulas; works offline, no plugins required.

---

## 📁 Workbook Structure

| Sheet | Purpose |
|---|---|
| **Dashboard** | Command center — key metrics, spending by category, monthly trend, insights |
| **Transactions** | Master ledger of all income/expense entries |
| **Categories** | Category-wise budget vs. actual analysis with status tracking |
| **Budget** | Annual budget planning + 50/30/20 rule allocation |
| **Monthly** | Rolling monthly performance and net worth tracking |

---

## 🚀 Getting Started

1. Download `Expense_Tracker_Pro.xlsx`.
2. Open in Excel (or LibreOffice Calc / Google Sheets — formulas are compatible).
3. Go to the **Transactions** sheet and start logging entries:

   | Date | Description | Category | Type | Amount | Payment Method | Notes |
   |---|---|---|---|---|---|---|
   | 2026-07-01 | Monthly Salary | Salary | Income | 5500 | Direct Deposit | Primary employment |

4. Switch to the **Dashboard** — all totals, charts, and insights refresh automatically.
5. Adjust monthly budgets on the **Budget** sheet to fit your goals.

---

## 🧩 How It Works

- Every category in **Transactions** must match a category listed in **Categories** — this keeps budget-vs-actual formulas accurate.
- **Categories** and **Budget** sheets auto-sync: update your monthly budget once, and it flows through to status flags and the 50/30/20 breakdown.
- **Monthly** sheet accumulates historical performance so you can track net worth growth over time.

---

## 🛠️ Customization

- Add new categories: insert a row in **Categories** and **Budget**, keeping the `TOTAL` row formulas updated.
- Change the 50/30/20 targets in the **Budget** sheet's compliance table to match your own plan (e.g., 60/20/20).
- Extend the **Monthly** sheet each month to keep the rolling trend view current.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

*Built for anyone who wants clear financial visibility without subscribing to another budgeting app.*
