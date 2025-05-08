# BizExpense Tracker 🚀

[![Offline Ready](https://img.shields.io/badge/Offline-Ready-brightgreen)](https://shields.io/)
[![Data Storage](https://img.shields.io/badge/Storage-IndexedDB-blue)](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
[![Charts](https://img.shields.io/badge/Charts-Chart.js-orange)](https://www.chartjs.org/)
[![Tech](https://img.shields.io/badge/Tech-HTML | CSS | JS-yellow)](https://shields.io/)

**Author: Yasin Ullah (Pakistani)**

BizExpense Tracker is a comprehensive, client-side expense and income logger designed for small businesses and freelancers. It's a single HTML file application that runs entirely in your browser, ensuring your financial data stays private and accessible even offline.

## ✨ Core Functionality

*   **Log Transactions:** Easily record expenses and income with details like:
    *   Date
    *   Customizable Category
    *   Amount (Supports "Rs." currency display)
    *   Vendor (for expenses) / Client/Source (for income)
    *   Description
    *   Customizable Payment Method
*   **Receipt Management:** Upload receipt images (stored locally as base64/blob in IndexedDB). View previews and full images.

## 🌟 Advanced Features

*   **Powerful Reporting:**
    *   Generate reports by category or period.
    *   View total summaries.
    *   Visualize data with interactive charts (powered by Chart.js).
*   **Expense Attributes:** Mark expenses as "Reimbursable" or "Billed to Client".
*   **Recurring Transactions:** Set up and manage recurring expenses and income templates (e.g., monthly subscriptions, regular client payments).
*   **Advanced Search & Filtering:** Quickly find transactions using keywords, date ranges, categories, and types.
*   **Data Management:**
    *   **Full Database Backup:** Export your entire database (all transactions, categories, settings, and receipts) to a JSON file.
    *   **Database Restore:** Import a previously backed-up JSON file to restore your data.
    *   **Data Export:** Export transaction data to CSV or JSON formats.
*   **Offline First:** Fully operational without an internet connection. All data is stored securely in your browser's IndexedDB.
*   **Modern UI/UX:**
    *   Clean, fast, and organized interface for quick data entry and analysis.
    *   Clear report visualizations.
    *   Responsive design for seamless use on desktop and mobile devices.
    *   Light and Dark themes.
    *   Accessible forms and navigation.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Data Storage:** IndexedDB (for all application data and receipt images)
*   **Charting:** Chart.js
*   **No Server-Side Code:** Purely client-side application.

## 🚀 How to Use

1.  Download the `BizExpenseTracker.html` (or your app's HTML file name) file.
2.  Open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3.  That's it! Start tracking your business finances. No installation or internet connection required after loading.

## 🔒 Data Privacy

Your financial data is your own. BizExpense Tracker stores all information, including receipt images, directly in your browser's IndexedDB. **No data is ever sent to any external server.** You have full control, including the ability to backup and restore your entire database.

## 💡 Future Enhancements (Ideas)

*   Multi-currency support with automatic conversion.
*   Budgeting features.
*   Integration with cloud storage for optional, user-initiated backups.
*   More advanced reporting and analytics.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
---
Made with ❤️ by Yasin Ullah.
