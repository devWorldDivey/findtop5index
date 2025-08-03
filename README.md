# NSE Daily Snapshot Analyzer

A simple, client-side tool to instantly analyze and visualize the "Daily Snapshot" report from the National Stock Exchange (NSE) of India. No installation, no server, no data uploads—everything happens securely in your web browser.

![Screenshot of the NSE Analyzer tool in action](https://i.imgur.com/rS2jL8T.png)

## What It Does

This tool takes the daily market closing report (`ind_close_all_ddmmyyyy.csv`) from the NSE website and transforms it into an easy-to-understand dashboard. It's perfect for traders, investors, and enthusiasts who want a quick summary of the day's market performance without complex software.

### Key Features

*   **Zero Installation:** Just a single HTML file that runs in any modern web browser.
*   **Visual Pie Chart:** Instantly see the top 10 positive market movers and their percentage contribution to the day's total gains.
*   **Sorted Data Tables:** View the complete market data sorted by both absolute "Points Change" and "Percentage Change".
*   **Export to CSV:** Download the sorted data tables with a single click for your own records or further analysis.
*   **100% Private & Secure:** Your data is never uploaded anywhere. All file processing and analysis are done locally on your computer using JavaScript.

## How to Use

1.  **Download the Tool:**
    *   Go to the [Releases](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY/releases) page of this repository.
    *   Download the `NSE_Analyzer.html` file from the latest release.

2.  **Download the NSE Report:**
    *   Visit the official NSE India website: [**All Reports Page**](https://www.nseindia.com/all-reports).
    *   Download the **"Daily Snapshot"** report. The file is usually named `ind_close_all_ddmmyyyy.csv`.

3.  **Analyze:**
    *   Open the `NSE_Analyzer.html` file in your web browser (like Chrome, Firefox, or Edge).
    *   Click the **"Choose File"** button.
    *   Select the `ind_close_all...csv` file you just downloaded from the NSE website.

That's it! The pie chart and data tables will be generated instantly on the page.

## Technology Stack

This tool is intentionally built with a minimal and accessible technology stack to ensure it runs anywhere without dependencies.

*   **HTML5:** For the main structure of the page.
*   **CSS3:** For styling and layout.
*   **JavaScript (Vanilla):** For all the logic, data processing, and DOM manipulation.
*   **[Chart.js](https://www.chartjs.org/):** A powerful library used to create the interactive pie chart.
*   **[PapaParse.js](https://www.papaparse.com/):** A robust in-browser CSV parsing library to handle the NSE report file.

## Contributing

Contributions are welcome! If you have ideas for improvements, new features, or find a bug, please feel free to:
*   Open an issue to discuss your ideas.
*   Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
