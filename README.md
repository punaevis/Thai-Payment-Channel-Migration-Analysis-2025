# Thai-Payment-Channel-Migration-Analysis-2025
Visualizing the structural shift from ATM/Cash to Mobile Banking in Thailand using Bank of Thailand Open Data and Python.

# 🇹🇭 Thailand Payment Channel Migration Analysis (2019-2024)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project analyzes the structural shift in Thailand's payment infrastructure, tracking the migration from **Physical Channels (ATM, Branch Counter)** to **Digital Banking (Mobile, Internet)**.

Using official data from the **Bank of Thailand (BOT)**, the analysis visualizes the "Cashless Society" trend through a dual-axis correlation chart, confirming the impact of digital transformation policies (PromptPay) on consumer behavior.

## 📊 Key Findings
After processing 6 years of transaction data, the analysis reveals:
- **🚀 Digital Explosion:** Mobile & Internet banking transactions grew by **+549.65%** (approx. 5.5x growth).
- **🔻 Physical Decline:** Traditional channels (ATM & Counter) usage dropped by **-65.72%**.
- **❌ The Crossover:** The trends display a clear inverse correlation ("X-Shape"), marking the definitive transition era of the Thai financial landscape.

## 📷 Visualization
*The dual-axis chart below highlights the divergence between digital adoption and traditional infrastructure usage.*

![Payment Trend Chart](payment_migration_dual_axis_final.png)
*(Note: If the image doesn't load, please check the `payment_migration_dual_axis_final.png` file in the repository)*

## 🛠️ Technologies Used
- **Language:** Python 3
- **Libraries:**
  - `pandas` (Data cleaning, aggregation, and statistical calculation)
  - `matplotlib` & `seaborn` (Advanced dual-axis visualization)
- **Data Source:** Bank of Thailand (BOT) - PS_PT_002 Volume of Payment Transactions processed through Payment Systems and Channels

## 📂 Repository Structure
```bash
├── analysis.py         # Main Python script for data processing & plotting
├── payment_data.csv    # Raw dataset (cleaned format)
├── payment_migration_dual_axis_final.png  # Output visualization image
└── README.md           # Project documentation
