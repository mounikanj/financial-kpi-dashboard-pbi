
---

### 🟦 Project 3 – Financial KPI Dashboard

**Repo:** `financial-kpi-dashboard-pbi`

```markdown
# Financial KPI Dashboard – Power BI

## 📌 Overview
Executive-level dashboard to monitor revenue, expenses, profit, and key financial KPIs.

## 🎯 Objectives
- Track monthly and yearly profitability
- Compare planned vs actual performance
- Provide quick management view of financial health

## 🧰 Tech Stack
- Power BI
- Power Query
- DAX

## 🧮 Key DAX

```DAX
Total Revenue = SUM(Finance[Revenue])
Total Expenses = SUM(Finance[Expenses])
Net Profit = [Total Revenue] - [Total Expenses]

Net Profit % =
DIVIDE([Net Profit], [Total Revenue])
