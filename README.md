
# Markdown to Google Docs Converter

## Description
This project provides a Google Colab notebook to convert Markdown-formatted text into a Google Doc using the Google Docs API. The notebook supports formatting features such as headers, bullet points, checkboxes, mentions with bold text, and footers.

---

## Setup Instructions

### Enable Google Docs API
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project (or use an existing one).
3. Enable the Google Docs API and the Google Drive API for the project.
4. Download the `credentials.json` file from the API credentials page.

### Upload to Colab
5. Upload the provided `.ipynb` file to your Google Colab environment.
6. Upload the `credentials.json` file to Colab when prompted.

---

## Required Dependencies
The following Python libraries will be installed directly in the Colab notebook:
- `google-auth`
- `google-auth-oauthlib`
- `google-api-python-client`

No additional setup is required as dependencies are managed within the notebook.

---

## How to Run in Colab
1. Open the Colab notebook in your browser.
2. Follow the below steps in order:
   - Authenticate the Google Docs API by uploading the `credentials.json` file when prompted.
   - Run the final code cell under "Ansible Health Assessment - Submission 2" to create the Google Doc with required formatting.
3. Once the final cell is executed, check your Google Drive for the newly created Google Doc.

---
