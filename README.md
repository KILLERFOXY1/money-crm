# Money CRM - Mobile Train Commute App

This app is designed specifically for fast single-handed data entry and client follow-ups on your phone during train commutes.

## Quick Setup Guide:

### Step 1: Set up Google Apps Script API
1. Open your Google Sheet containing the `MONEY` tab.
2. Click **Extensions** -> **Apps Script**.
3. Copy the code from `Code.gs` in this repository and paste it into Google Apps Script.
4. Click **Deploy** -> **New deployment**.
5. Select type: **Web App**.
6. Set **Execute as**: `Me` and **Who has access**: `Anyone`.
7. Click **Deploy** and copy the **Web App URL**.

### Step 2: Connect Web App to your HTML
1. Edit `index.html` on GitHub.
2. Replace `"YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL"` with the URL you copied in Step 1.
3. Save & commit changes.

### Step 3: Enable GitHub Pages (To open on phone)
1. In your GitHub Repo (`KILLERFOXY1/money-crm`), go to **Settings** -> **Pages**.
2. Under **Source**, select `main` branch and `/ (root)` folder.
3. Click **Save**.
4. Open the generated GitHub Pages link on your mobile phone, and tap **"Add to Home Screen"**!
