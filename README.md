# Mutual Fund Investments Tracker

## Description  
The Mutual Fund Investments Tracker is an Excel-based solution designed to help users manage and analyze their Mutual Fund investments effectively. This tracker includes Interactive Dashboards containing pivot tables, charts, and graphs to provide quick insights into investment performance. The workbook also has some utility macros to automate workflows. This tool is ideal for anyone looking to organize and visualize their Mutual Fund data with minimal effort.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Har-Var/Mutual-Fund-Investments-Tracker.git
   cd Mutual-Fund-Investments-Tracker
   ```
2. Ensure you have Microsoft Excel installed (version supporting macros)
3. Enable macros in Excel:
   - Go to `File > Options > Trust Center > Trust Center Settings`.
   - Enable "Trust access to VBA project object model."

## Usage
1. Open the `Mutual-Fund-Investments-Tracker.xlsm` file in Excel. 
2. Input your Mutual Fund data into the "Tracker" sheet.
3. Explore insights using "Dashboard" sheets.

## Features
- **Data Management**: Organize Mutual Fund investment records in a structured format.
- **Interactive Analysis**: Pivot tables and slicers provide dynamic filtering and summarization.
- **Visualization**: Charts for tracking unrealized profits/losses, investment timelines, and more.
- **Automation with Macros**: Automatically generates sheets/delete sheets for individual members based on their unique IDs.

## Project Structure
The Excel Workbook is organized into the following sheets:

  1. **Dashboard:** Dashboard showing overall Information. Some Questions answered:-

    1) What's the Best Performing Scheme?
    2) How has Investment varied over time?
    3) What's the most popular Nominee Relation?
    4) Who are the Star Investors, i.e. the ones with the most Invested Value?
    5) Which Members have the Best Performance? Which have the worst?
  2. **Dashboard-MemberOverview:** Dashboard showing Information for only Selected Investor. Some Metrics Tracked:-

    1) Invested Amount
    2) Schemes Invested in
    3) Investment Folio Numbers
    4) Member's Performance (Unrealized Profit/Loss)
  3. **Utils:** Buttons linked to 2 Utility Macro functions

    1) Create Member Sheets = Splits main table data into separate Member sheets
    2) Delete Member Sheets = Deletes all such split member sheets created using "Create Member Sheets"
  4. **Tracker:** Main table containing data, new entries/updates are made here
  5. **Members:** MemberID - MemberName table
  6. **DataSource:** Output of connection query fetching and cleaning data obtained from [AMFI Website](https://www.amfiindia.com/spages/NAVAll.txt)
  7. **Some Hidden Sheets:** Contains Pivots used to create Dashboard charts

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open a pull request.

## License
This project is licensed under the MIT License.

## Authors
- [Har-Var](https://github.com/Har-Var)

## Acknowledgments
Special thanks to my Father who provided Inspiration for this Project.




