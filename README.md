# 🚲 Indego_Analysis
Growth Solutions for Bike Sharing business 

## Overview 📋

This project analyzes Philadelphia's Indego Bike Share program using Q3 2025 trip data. The analysis was originally prepared as a Perpay exercise presentation, exploring ridership patterns, passholder behavior, and growth trends to inform strategic business decisions.

---

## Dataset 📊

> Download the Q3 2025 trip data directly from the official Indego website:
> 👉 https://www.rideindego.com/about/data/

| Feature | Description |
|---|---|
| `trip_id` | Locally unique integer that identifies the trip |
| `duration` | Length of trip in minutes |
| `start_time` | Date/time when the trip began (ISO 8601 format) |
| `end_time` | Date/time when the trip ended (ISO 8601 format) |
| `start_station` | Station ID where the trip originated |
| `start_lat` | Latitude of the origin station |
| `start_lon` | Longitude of the origin station |
| `end_station` | Station ID where the trip terminated |
| `end_lat` | Latitude of the destination station |
| `end_lon` | Longitude of the destination station |
| `bike_id` | Locally unique integer that identifies the bike |
| `plan_duration` | Number of days the passholder's plan covers (0 = single-ride) |
| `trip_route_category` | "Round Trip" or "One Way" |
| `passholder_type` | Name of the passholder's plan |
| `bike_type` | Standard pedal-powered bike or electric assist bike |

---

## Tools & Libraries 🛠️

- Python
- pandas
- numpy
- statsmodels
- seaborn
- matplotlib

---

## Data Cleaning 🧹

- Filled missing value
