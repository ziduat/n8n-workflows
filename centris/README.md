# Centris Property Listings Automation 🚀

An automated n8n workflow designed to fetch property listings from Centris.ca, store them in Google Sheets, and notify a Telegram channel.

## 📋 Overview
- **Trigger Type:** Schedule Trigger (runs every 2 minutes)
- **Key Functionality:** 
    - Queries Centris.ca property listings by sequencing specific API requests.
    - Appends the fetched data into a Google Sheet for tracking.
    - Sends automated notifications to a specified Telegram channel.

## 🧩 Nodes Used
- **Schedule Trigger:** Executes the workflow automatically on a 2-minute interval.
- **HTTP Request Nodes:** Communicates with Centris.ca API endpoints.
- **Google Sheets Node:** Appends property data to a spreadsheet.
- **Telegram Node:** Sends notifications or property details to the Telegram channel.
- **Set / Code Nodes:** Processes and structures the data for storage and messaging.

## ⚙️ How to Import & Use
1. Download the `workflow.json` file from this folder.
2. Open your **n8n** dashboard.
3. Click on the main menu (...) in the workflow view and select **Import from File**.
4. **Configure Credentials:** Ensure you have configured your credentials for:
    - **Google Sheets** (API access).
    - **Telegram** (Bot Token).
5. Save and activate your workflow!

---
*Part of my automated workflows collection.*
