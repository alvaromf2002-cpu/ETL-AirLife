# AirLife ETL Pipeline

## What This Does
This pipeline extracts airport data from a CSV file and live flight data from an API, 
cleans the data, and loads it into a PostgreSQL database.

## How to Run It
1. Install dependencies: `pip install -r requirements.txt`
2. Set up PostgreSQL database
3. Update database connection in `src/load_data.py`
4. Run: `python main.py`

## What We Built
- **Extract:** Gets airport data from CSV and flight data from OpenSky Network API
- **Transform:** Cleans invalid coordinates and converts units
- **Load:** Puts clean data into PostgreSQL tables

## Team Members
- [Angel García Urbán, Álvaro Martínez Felipe, Ismael El-Khattabi Vilchez, Alexandre Jesus de Oliveira ]
