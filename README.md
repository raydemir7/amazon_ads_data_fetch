# Amazon Ads Reporting via API

This project automates the process of fetching advertising data from Amazon Ads API, processing it, and writing the results to Google Sheets for reporting purposes. The script is designed to handle data efficiently and includes error handling for API requests and Google Sheets integration.

## Features
- Fetches advertising data (e.g., daily total sales) from the Amazon Ads API.
- Handles token-based authentication and manages API rate limits with retries.
- Automatically processes and aggregates the data.
- Writes the formatted data into a specified Google Sheet, creating a new sheet if necessary.
- Provides detailed logs for troubleshooting and insights.

## Technologies Used
- **Python**: Scripting and data processing.
- **Amazon Ads API**: For fetching advertising campaign data.
- **Google Sheets API (gspread)**: For updating reports in Google Sheets.
- **Google Cloud Functions**: To automate the script execution via Pub/Sub.

## Requirements
- **Python 3.9+**: Ensure you have Python installed.
- **Amazon Ads API Credentials**:
  - Client ID, Client Secret, Refresh Token, and Profile ID.
- **Google Sheets API Credentials**:
  - A `service_account.json` file for authentication.
- **Google Cloud Functions Setup**:
  - Deploy the script and trigger it via Pub/Sub.


