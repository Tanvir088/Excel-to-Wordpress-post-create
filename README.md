# WordPress Auto Post Script

This project is a Python-based automation tool that allows users to publish WordPress posts directly from Excel files using the WordPress REST API. It is designed for bloggers, content managers, and small businesses who want to save time by avoiding repetitive manual posting. By reading titles and content from spreadsheets, the script automatically creates and publishes posts with just a few inputs, making bulk content management simple and efficient.

## Features
- Reads titles and content from Excel files (columns A and B).
- Publishes posts automatically via WordPress REST API.
- Handles authentication using WordPress Application Passwords.
- Skips rows with missing data to ensure clean posting.
- Provides clear success and error messages for each post.

## Requirements
- Python 3.x
- pandas
- requests

Install dependencies:
```bash
pip install -r requirements.txt
