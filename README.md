# Real-Time Country Time Tracker

This Python project scrapes real-time time data for a user-specified country from timeanddate.com and compares it with the local system time. The data is continuously updated and stored in an Excel file using openpyxl, with custom headers, styling, and calculated time differences.

## Features
- Web scraping with `requests` and `BeautifulSoup` 
- Real-time comparison of country time and local time
- Automated Excel data storage with formatting
- Workflow automation with continuous updates
- Demonstrates Python scripting, data handling, and automation skills

## Skills Demonstrated
- Python programming
- Web scraping
- Excel automation (`openpyxl`)
- Data parsing and datetime manipulation
- Workflow automation

## How to Run
1. Install dependencies: `pip install requests beautifulsoup4 openpyxl`
2. Run the script: `python country_time_tracker.py`
3. Enter the country name when prompted
4. The Excel file will update with time data every second

## Notes
- The script currently runs in a continuous loop; you can stop it with Ctrl+C
- Designed for beginner-to-intermediate Python learners focusing on automation and data workflows
