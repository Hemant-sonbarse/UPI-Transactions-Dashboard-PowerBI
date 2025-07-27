# 📊 UPI Transactions Analysis Dashboard using Power BI

A complete end-to-end Power BI project that analyzes UPI transactions across India using various dimensions like state, payment mode, banks, and year. The project includes data transformation, modeling, DAX measures, and interactive dashboards.

---

## 🚀 Project Overview

This Power BI dashboard provides key insights into UPI (Unified Payments Interface) transaction trends across India. It uses Excel-based data and delivers a professional, interactive reporting experience.

The report helps in:

- Identifying transaction trends by year and state  
- Analyzing top performing banks and payment modes  
- Comparing volume and value across time periods  
- Visual storytelling using bookmarks and slicers

---

## 🧰 Tools & Technologies

| Tool                 | Purpose                                   |
|----------------------|-------------------------------------------|
| **Power BI Desktop** | Data modeling, report building            |
| **Power Query**      | Data transformation and cleaning          |
| **DAX**              | Creating custom measures and KPIs         |
| **Power BI Service** | Publishing and interacting with reports   |

---

## 📁 Folder Structure

| Folder/File        | Description                                                          |
|--------------------|----------------------------------------------------------------------|
| `Data/`            | Contains the source Excel files used in the report                   |
| `PBIX_Files/`      | Power BI report file used for development and visualization          |
| `Screenshots/`     | Visual snapshots of report pages and key insights                    |
| `README.md`        | Detailed explanation of the project, approach, and features          |
| `.gitignore`       | Git ignore rules for unnecessary local files                         |

---

## 📌 Key Features

- 📅 Year-wise trend analysis of UPI transactions  
- 🏦 Bank-wise performance comparison  
- 📉 Dynamic slicers and interactive bookmarks for seamless navigation  
- 📈 Customized DAX measures for volume, value, and growth metrics

---

## 🧠 Learnings

- Data cleaning and formatting using Power Query  
- DAX formulas to handle dynamic filters and time intelligence  
- Proper alignment and positioning of visuals using exact dimensions  
- Publishing reports to Power BI Service and using bookmarks without Ctrl-click

---

## 🖼️ Report Features

- **Date Slicers**: Two slicers for comparing between two different time ranges.
- **Dynamic KPIs**: Total amount, transaction count, period-over-period comparisons.
- **Visual Types**: Line chart, column chart, summary cards, matrix tables.

---

## 🔖 Bookmarks & Navigation

Used **Bookmarks** to create smooth navigation between multiple visual views:

### ➕ Why Bookmarks?

- Toggle between visuals (line chart ↔ column chart)
- Navigate to summary/balance view
- Reset visuals/filters
- Add interactivity without multiple pages

### 🛠️ Setup Process:

1. Enabled **Bookmarks Pane** and **Selection Pane** from the View tab.
2. Created multiple bookmarks:
   - `Line Chart View`
   - `Column Chart View`
   - `Summary Balance View`
3. Set visibility of visuals accordingly per bookmark.
4. Linked bookmarks to **buttons** for easy navigation.

### 📌 Usage:

- In **Power BI Desktop**: Ctrl + Click on bookmark button.
- In **Power BI Service**: Single Click (Ctrl not required).

---

# 📸 UPI Transactions Dashboard - Screenshots

This folder contains visual snapshots of key pages and features from the Power BI report.

| Screenshot Name                        | Description                                                |
|----------------------------------------|------------------------------------------------------------|
| `monthly-transactions-line-2024.png`   | Line chart showing monthly UPI transactions for 2024.      |
| `monthly-transactions-column-2024.png` | Column chart version of monthly transactions for 2024.     |
| `monthly-balance-line-hdfc.png`        | Balance trend line for HDFC Bank.                          |
| `city-currency-transaction-table.png`  | Matrix view showing city-wise UPI transaction summary.     |

> These screenshots highlight different views created using bookmarks and slicers in the report.

