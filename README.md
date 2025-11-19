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
*The exponential increase in digital cmparing to traditional.*
![Payment Trend Chart](<img width="920" height="449" alt="Screenshot 2568-11-19 at 7 44 58 PM" src="https://github.com/user-attachments/assets/e3bc08bf-d821-4b7e-ab9b-fa55b81ccc3e" />
)

*The dual-axis chart below highlights the divergence between digital adoption and traditional infrastructure usage.*

![Payment Trend Chart](<img width="909" height="444" alt="Screenshot 2568-11-19 at 7 45 29 PM" src="https://github.com/user-attachments/assets/07ff5aaf-1eaf-4b19-a00a-a350819ee0e6" />
)

## 🛠️ Technologies Used
- **Language:** Python 3
- **Libraries:**
  - `pandas` (Data cleaning, aggregation, and statistical calculation)
  - `matplotlib` & `seaborn` (Advanced dual-axis visualization)
- **Data Source:** Bank of Thailand (BOT) - PS_PT_002 Volume of Payment Transactions processed through Payment Systems and Channels

## 📂 Repository Structure
```bash
├── README.md           # Project documentation
├── payment_data.csv    # Raw dataset (cleaned format)
└── analysis.py         # Main Python script for data processing & plotting

