# NGINX Log Anomaly Detection Dashboard

A web-based dashboard developed during the UCC Hackathon to analyse
NGINX access logs and identify unusual traffic patterns.

## Features

- Analyse NGINX access logs
- Filter logs by IP address, HTTP method and status code
- View request statistics
- Analyse traffic patterns over time
- Identify unusually large requests
- Identify potential bot/web-scraper traffic
- Generate an anomaly summary report

## Technologies

- Python
- Flask
- SQLite
- SQL
- Pandas
- HTML/CSS

## How It Works

NGINX access logs are stored in a SQLite database. Python and Pandas
are used to analyse the log data, while Flask provides the web
interface for viewing and filtering the results.

The project uses statistical analysis to identify unusually large
requests. Requests exceeding the mean number of bytes sent by more
than three standard deviations are flagged for further investigation.

## Project Outcome

Developed as part of the UCC Hackathon.

The project placed in the top 30% of teams.

## What I Learned

- Working with large datasets
- SQL database querying
- Flask web development
- Statistical analysis
- Data visualisation
- Identifying potential anomalies in web traffic
