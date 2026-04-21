# 🚕 NYC Yellow Taxi — Exploratory Data Analysis (January 2026)

## Project Overview
End-to-end exploratory data analysis of 3.7 million NYC Yellow Taxi trips 
from January 2026, sourced from the NYC Taxi & Limousine Commission (TLC).

## Key Findings
- 🚕 **3.7M trips** recorded in January 2026, 2.5M retained after cleaning
- ✈️ **JFK Airport** was the #1 pickup zone with 140,768 trips
- 🕔 **5–6pm** is peak demand — evening rush hour dominates
- 🎉 **Friday & Saturday** are the busiest days — nightlife & weekend travel
- 💳 **Credit cards dominate** payments — 78.8% of riders tipped
- ⚠️ **Tip data is biased** — only credit card tips are recorded, cash tips appear as $0
- 📈 **Strong correlation (r = 0.92)** between trip distance and fare amount
- 🏙️ **Upper East Side** is the busiest Manhattan neighborhood for both pickups & dropoffs
- 🚦 **32.8% of rows removed** during cleaning — mostly one vendor missing key fields

## Dataset
- **Source:** [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Period:** January 2026
- **Raw rows:** 3,724,889
- **Clean rows:** 2,503,027
- **Format:** Parquet

## Tech Stack
- Python 3.11
- pandas, numpy
- matplotlib, seaborn
- scipy (Pearson correlation)

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Download the dataset from NYC TLC and place in `data/`
4. Open `notebooks/01_eda.ipynb` and run all cells

## Author
Ewulo Oluwarotimi — [GitHub](https://github.com/Ewulo) | [LinkedIn](https://www.linkedin.com/in/oluwarotimi-ewulo/)
