
# Python SIEM Dashboard

A simple SIEM-like dashboard using Python, Flask, SQLite, and Chart.js.

## Features

- Log ingestion from JSON
- Store logs in SQLite database
- Web dashboard showing log levels and timestamps
- Basic filtering and visualization

## Installation

```bash
git clone https://github.com/<your-username>/python-siem-dashboard.git
cd python-siem-dashboard
pip install -r requirements.txt
python parser.py   # Load sample logs
python app.py      # Start dashboard
