
# Markdown to Google Docs Converter

## Description
This project provides a Python script to convert Markdown-formatted text into a Google Doc using the Google Docs API. It supports formatting headers, bullet points, interactive checkboxes, mentions with bold text, and footer styling. The script can be run locally or in Google Colab for ease of use.

---

## Setup Instructions

### Clone the Repository
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

### Install Dependencies
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Set Up Google Docs API Credentials
3. Enable the Google Docs API:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project (or use an existing one).
   - Enable the Google Docs API and the Google Drive API for the project.
   - Download the `credentials.json` file from the API credentials page.

4. Upload the `credentials.json` file:
   - If running locally, place the `credentials.json` file in the same directory as the script.
   - If running in Colab, upload the file using the file upload feature.

### Authentication
5. Authenticate the API client:
   - The script will automatically use `credentials.json` to authenticate with the Google Docs API.
   - In Colab, follow the prompts to authenticate when running the notebook.

---

## Required Dependencies
The following Python libraries are required:
- `google-auth`
- `google-auth-oauthlib`
- `google-api-python-client`
- `re`

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

## How to Run in Colab
1. Open the Colab notebook:
   [Google Colab Notebook](<add-your-notebook-link-here>)
2. Upload your `credentials.json` file in the notebook.
3. Run the cells in order:
   - Authenticate the Google Docs API.
   - Convert the provided Markdown text into a formatted Google Doc.
   - Check the created document in your Google Drive.

---

## Example Markdown Input
Below is an example of the Markdown input supported by the script:
```markdown
# Team Meeting - Weekly Sync

## Attendees
- John Doe
- Jane Smith
- @teamlead

## Agenda
- [ ] Review last week's tasks
- [ ] Discuss new feature development
- [x] Address critical issues

## Notes
* Next meeting scheduled for next Monday.
* Follow up with the marketing team.
```

This Markdown will be converted into a fully formatted Google Doc.

---

## Output
After running the script, you will find a new Google Doc in your Google Drive with the converted content and formatting.

---

For any questions or issues, feel free to open an issue in the repository. Happy coding! 🚀
