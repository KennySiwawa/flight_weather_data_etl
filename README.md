# Flight Weather Data ETL

A Python-based ETL (Extract, Transform, Load) pipeline that scrapes German cities (Berlin, Hamburg, Munich) and collects weather forecasts, airport information, and flight data from various APIs, then loads everything into a MySQL data warehouse.

## 📋 Project Overview

This project demonstrates a complete ETL pipeline that:

1. **Scrapes Wikipedia** for German city population data
2. **Fetches weather forecasts** from OpenWeatherMap API (5-day forecasts)
3. **Retrieves airport information** from AeroDataBox API (ICAO codes)
4. **Collects live flight arrivals** for Berlin Brandenburg Airport (EDDB)
5. **Stores all data** in a MySQL database (`sql_workshop_cloud`)

## 🛠️ Technologies Used

- **Python 3.9+**
- **pandas** - Data manipulation and analysis
- **MySQL** - SQL toolkit
- **requests** - HTTP library for API calls
- **BeautifulSoup4** - Web scraping
- **python-dotenv** - Environment variable management
- **Jupyter** - Interactive notebooks

### Prerequisites

- Python 3.9 or higher
- MySQL database server
- API keys (see Configuration section)

### Step 1: