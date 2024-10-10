# Google Calendar Automation with UiPath

## Overview

This UiPath automation logs into Google Calendar, extracts calendar events for the current month, exports them to an Excel file, generates a summary report, and implements error handling and logging.

## Features
1. **Google Calendar Login:**
   - Secure login using windows Credential Manager.
   - Navigates to Google Calendar and authenticates the user.
  
2. **Export Calendar Events:**
   - Extracts event details (title, date, start time) for the current month.
   - Exports the data to an Excel file with proper formatting.
  
3. **Generate Summary Report:**
   - Calculates total number of events.
   - Identifies the busiest day of the month.
   - Shows event distribution by day of the week.

4. **Error Handling and Logging:**
   - Comprehensive error handling using Try-Catch blocks.
   - Logs each step and any errors to a log file.

## Prerequisites
- UiPath Studio
- Web browser (Chrome or Edge)
- Google Calendar account
- windows Credential Manager (for handling login credentials)

## Steps to Run the Automation

1. Open UiPath Studio and load the project.
2. Ensure that your Google Calendar login credentials are stored securely in windows credential manager.
3. Run the automation and follow the logs in the output panel.
4. The Excel file `CalendarEvents.xlsx` will be generated with the extracted event data and summary report.
## Error Handling
- The automation is equipped with Try-Catch blocks to handle potential issues like network errors or authentication failures.
## Output
- **Excel File:** Contains two sheets—`Events` (calendar events data) and `Summary` (total events, busiest day, distribution by day of the week).

