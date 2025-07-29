# 🧅 Pyaz Samachar

Pyaz Samachar is an open-source platform for real-time onion price tracking, analysis, and forecasting across Indian wholesale markets (mandis), using official government data.

## ✨ Features

- 🤖 Automated scraping and collection of onion prices from official sources (AGMARKNET and more)
- 📈 Historical and real-time price analysis
- 📊 Forecasting and trend visualization
- 🗺️ Geo-mapped price dashboards
- 🚨 Alerts for significant price fluctuations

## 🛠️ Technologies

- Python (Scrapy, pandas, Prophet, etc.)
- PostgreSQL or MongoDB
- Apache Superset or Metabase for dashboards
- Airflow or Prefect for automation

## 📁 Project Structure

- `etl/` - Data scraping and cleaning scripts
- `forecasting/` - Price forecasting models
- `dashboards/` - Visualization and dashboard code/configs
- `alerts/` - Notification scripts
- `data/` - Raw and processed data
- `docs/` - Documentation

## 📝 Data Sources

- AGMARKNET (Government of India)
- India Data Portal
- Data.gov.in
- Official mandi portals

---

## 🚀 Getting Started

### 1️⃣ Clone This Repository

```bash
git clone https://github.com/YourUsername/PyazSamachar.git
cd PyazSamachar
```

### 2️⃣ Set Up a Python Virtual Environment

It is recommended to use a separate Python Virtual Environment for this project to manage dependencies cleanly.

#### ➡️ Create a Virtual Environment
```bash
python -m venv PyaazSamachaarEnv
```

#### ➡️ Activate the Virtual Environment

- **On Linux/MacOS:**
```bash
source PyaazSamachaarEnv/bin/activate
```
- **On Windows:**
```bash
PyaazSamachaarEnv\Scripts\activate
```

You should see `(PyaazSamachaarEnv)` before your terminal prompt when activated.

#### ➡️ Deactivate the Virtual Environment

When you’re done working:
```bash
deactivate
```

### 3️⃣ Install Required Packages

With the virtual environment activated, install dependencies:

```bash
pip install -r requirements.txt
```

---

## ⏩ Next Steps

1. Configure your data source credentials and scraping targets.
2. Run the ETL pipeline to collect and process real market data.
3. Train forecasting models or run dashboards as needed.

---

*Crafted for transparency & empowerment in India's agricultural markets 🇮🇳🧅*
