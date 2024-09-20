# Instagram Post Downloader

This Python script automates the process of downloading the latest 50 posts (images and videos) from specified Instagram usernames and logs the details into a Google Sheet. The script also handles rate limiting and random sleep intervals between each download to mimic human behavior.

## Features

- Downloads the last 50 posts from Instagram for each username listed in a CSV file.
- Saves media (images and videos) in separate directories.
- Logs details (username, post shortcode, file path, timestamp) to a Google Sheet.
- Randomized sleep intervals between each scrape for human-like behavior.
- Handles rate limiting and graceful shutdown on user interruption.
  
## Requirements

Before you begin, ensure you have the following installed:

- Python 3.x
- Google Service Account JSON file for authentication with Google Sheets

### Python Libraries

To install the required Python libraries, run:

```bash
pip install -r requirements.txt

