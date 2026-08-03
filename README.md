# FinanceHub V2 📊

An advanced, offline-first personal finance dashboard built to manage budgets, project retirement wealth, track net worth, and generate visual financial health insights. 

Designed entirely as a single-file application, FinanceHub V2 runs entirely in the browser and can be compiled into a native Android APK via Capacitor.

## ✨ Key Features
*   **Smart Budgeting:** Track monthly inflow vs. fixed bills with rollover functionality and automatic deficit/surplus health tagging.
*   **Retirement Engine:** Combined EPF and PPF compound interest projection calculators with inflation adjustments.
*   **Net Worth & Goals:** Track assets against liabilities over time, and assign surplus funds to visual goal buckets.
*   **Expense DNA:** Visual breakdown of salary allocation using dynamic charts.
*   **Universal Offline Mode:** Service worker integration ensures 100% offline functionality.
*   **Native PDF Export:** Generates financial summary reports directly to Android's native print spooler or desktop browser print dialog.

## 📱 Installation (Android)
1. Download the latest `app-release.apk` from the Actions / Artifacts tab.
2. Install directly on your Android device. No internet required after the initial load.

## 🛠️ Tech Stack
*   **Frontend:** HTML5, CSS3, JavaScript
*   **UI Framework:** Bootstrap 5
*   **Charts:** Chart.js
*   **Mobile Wrapper:** Capacitor 6 (with native Print Plugin)

## 🔒 Privacy First
All financial data is stored locally in your browser's `localStorage`. No data is ever sent to an external server. Includes a "Privacy Toggle" to blur sensitive figures while viewing in public.
