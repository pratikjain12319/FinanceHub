# 💰 FinanceHub V1

> A personal finance command centre built for Indians — budget tracking, portfolio management, EPF & PPF retirement projections, all in a single offline HTML file.

---

## ✨ Features

### 📊 Budget Tab
- Enter your **net monthly salary** (in-hand after tax)
- Track all fixed monthly expenses — Rent, Electricity, Internet, Gas/Fuel, Credit Card, Gold EMI, and Miscellaneous
- Real-time **Net Surplus** calculation with a **financial health indicator**:
  - 🟢 Healthy — saving 20%+ of income
  - 🟡 Caution — saving less than 20%
  - 🔴 Critical — overspending or saving less than 5%
- **₹ Lakh / ₹ Crore** display toggle
- **Commit Snapshot → Ledger** to timestamp and save the current budget state

### 📈 Invest Tab
- Track portfolio across **5 asset classes**: EPFO, Stocks, PPF, APY, and Others
- Enter current balance and monthly SIP per asset
- Uses **real weighted return rates** per asset class (EPFO 8.25%, Stocks 12%, PPF 7.1%, APY 8.5%, Others 10%)
- Shows **Total Assets**, **Monthly SIPs**, and a **1-year growth projection**
- Displays **Total Portfolio / Net Worth** with a forward estimate

### 🏦 Retire Tab
**EPFO Planner**
- Input Basic Salary + DA, monthly EPFO contribution, current EPF balance, interest rate, annual salary hike, and retirement age
- Projects **total EPF corpus at retirement** with full year-by-year breakdown
- Toggle between **chart view** and **detailed table view**

**PPF Planner**
- Input current PPF balance, monthly investment, interest rate, and maturity date
- Projects **PPF maturity value** with interest earned and total invested summary
- Year-by-year projection chart and table

- **Download EPFO + PPF Report as PDF** — clean printable report with full projection tables

### 📜 Financial Ledger
- Every committed snapshot is stored with a full timestamp
- View, edit, or delete any past entry
- Load any past entry back into the Budget tab for editing
- **Export to CSV** for spreadsheet analysis

### 🎤 Guided Voice Tour
- Tap the 🎤 mic icon for a full spoken walkthrough of every section
- Highlights the relevant card, switches tabs, and scrolls automatically
- Progress dots at the bottom show tour position — tap the dots to stop anytime

---

## 🎨 Themes

| Theme | Toggle |
|---|---|
| Light (default) | — |
| Dark Mode | 🌙 |
| Terminal Mode | ⌨️ (green-on-black, JetBrains Mono) |

---

## 🔒 Privacy Mode

- Launches with **Privacy ON** by default — all sensitive financial values are blurred
- Tap **🙈** in the toolbar to reveal / hide values
- Sensitive fields also auto-blur on focus-out when privacy is on
- Privacy preference is saved across sessions

---

## 📧 Email Report

Found in the **Dev tab** — generates a pre-formatted plain-text financial summary and opens it in your default mail client with subject and body pre-filled. Covers budget, investments, and retirement projection in one email.

---

## 🛠️ Tech Stack

- **Vanilla HTML, CSS, JavaScript** — zero build steps, zero dependencies to install
- **Bootstrap 5.3** — layout and components
- **Chart.js 4.4** — projection charts
- **Web Speech API** — voice tour narration (browser-native, no API key needed)
- **localStorage** — all data stored locally in the browser, nothing sent to any server
- Google Fonts: Plus Jakarta Sans, JetBrains Mono

---

## 🚀 Getting Started

No installation required. Just open the file.

```bash
git clone https://github.com/your-username/financehub.git
cd financehub
open index.html
```

Or simply download `index.html` and open it in any modern browser.

**Recommended browsers:** Chrome, Edge, or Safari (Firefox has limited Web Speech API support for the voice tour).

---

## 📁 Project Structure

```
financehub/
└── index.html      # The entire app — single self-contained file
└── README.md
```

---

## 🗺️ Roadmap

- [ ] Expense breakdown pie chart on Budget tab
- [ ] Month-over-month surplus comparison
- [ ] SIP target tracker (% of surplus being invested)
- [ ] Full JSON export/import for complete data backup and restore
- [ ] Swipe gestures between tabs on mobile

---

## 👤 Author

**Pratik Rajesh Jain**  
Support Analyst · 7+ years experience · IT Engineering  

---

## 📄 License

MIT — free to use, modify, and distribute.

---

> ⚠️ **Disclaimer:** FinanceHub is a personal finance calculator for informational purposes only. It is not financial advice. All projections are estimates based on the inputs and assumed rates provided.
