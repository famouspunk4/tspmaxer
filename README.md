# 🎖️ TSP MAXER: 2026 Military Retirement Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web-blue.svg)](https://[your-username].github.io/tsp-calculator/)

**Maximize your TSP without losing your Marine Corps match.**

[🚀 Open the Live App](https://[your-username].github.io/tsp-calculator/)

## 📖 Overview

The **TSP MAXER** is a specialized financial tool built for service members to navigate the 2026 elective deferral limits. While many calculators simply tell you how much to contribute, this tool specifically tracks your year-to-date (YTD) progress and calculates the exact percentage needed in myPay to reach the **$24,500** limit by December.

### Why I Built This
I created this tool because many Marines inadvertently "max out" their TSP in November or early December. Under the **Blended Retirement System (BRS)**, if you don't contribute at least 5% in a given pay period, you lose your government match. This tool ensures you hit the ceiling on your final paycheck of the year, maximizing both your savings and your free matching funds.

## ✨ Features

- **Dynamic Contribution Tracker:** Input your monthly LES data to see real-time updates on your remaining "space" under the IRS cap.
- **myPay Percentage Calculator:** Automatically rounds up to the nearest whole number to ensure you hit your goal.
- **10-Year Growth Projection:** Powered by `Chart.js`, see how your current contributions—including the 5% match—will grow with compound interest over a decade.
- **Privacy-First (Auto-Save):** Your data is saved locally in your browser. No personal pay information is ever sent to a server or stored in a database.
- **Mobile-Responsive:** Designed to be used on the go while checking your LES on a phone or tablet.

## 🛠️ How to Use

1. **Enter Your Basic Pay:** Use the amount found on your current LES.
2. **Input YTD Totals:** Add up your contributions from January to the current month.
3. **Set Your Target ROI:** Adjust the estimated annual return (e.g., 10% for C-Fund historical averages).
4. **Update myPay:** Adjust your TSP election in myPay to the "Recommended Percentage" shown in the tool.

## 📈 The Math Behind the Tool

- **IRS Limit (2026):** $24,500 (Elective Deferrals)
- **Annual Additions Limit:** $72,000 (Total contributions including match)
- **Logic:** The tool identifies the number of months remaining in the calendar year and spreads the remaining balance of the $24,500 limit across them to ensure a steady contribution through December.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features (like BRS vs. Legacy comparisons or a specific "Bonus" calculator), feel free to fork the repo and submit a pull request.

## ⚖️ Disclaimer

*This tool is for educational purposes only. I am an active-duty Marine, not a certified financial advisor. Always verify your pay data on your LES and consult with a financial professional or a base PFM (Personal Financial Manager) for official investment advice.*

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
