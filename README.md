# Google Sheets Metabase Plugin

This README provides instructions to set up a Google Sheets plugin that connects to a Metabase instance and fetches data directly into your spreadsheet.

## Prerequisites

1. **Metabase Access**: Ensure you have access to a Metabase instance and the necessary API credentials (username and password).
2. **Google Account**: A Google account to use Google Sheets.

## Setup Instructions

Follow these steps to set up the Google Sheets plugin:

1. **Open Google Sheets**: Create a new or open an existing Google Sheet.
2. **Access Apps Script**: 
   - Go to `Extensions` > `Apps Script`.
   
3. **Add the Script**: Copy and paste the provided JavaScript code into the Apps Script editor.

4. **Configure API Credentials**:
   - Replace the placeholder values in the script with the URL of your Metabase instance and your Metabase username and password.

5. **Save the Script**: Click the floppy disk icon or go to `File` > `Save`.
6. **Close the Apps Script Editor**: Return to your Google Sheet.

## Usage

1. **Refresh the Google Sheet**: After saving the script, refresh the Google Sheet.
2. **Access the Plugin**: Click on the new `Metabase` menu in the toolbar.
3. **Import Data**: Select `Import Data`, enter a valid Metabase Query ID, and click OK. The data will populate in your sheet.

## Additional Information

- **Error Handling**: It is recommended to add proper error handling for production use.
- **Security Considerations**: Be cautious with how you handle credentials and session management.
- **Permissions**: Ensure the script has permissions to access the internet.
