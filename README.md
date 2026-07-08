# 🏏 T20I Batting Analysis

An end-to-end data analysis project that scrapes T20 International batting statistics from ESPNcricinfo and performs Exploratory Data Analysis (EDA) to uncover trends and insights among top batters.

## 📌 Project Overview

This project covers the complete data pipeline — from web scraping raw stats off multiple paginated pages, cleaning the data, to visualizing key batting performance metrics using Python.

## 🛠️ Tools & Technologies

- **Python**
- **BeautifulSoup / Requests** – Web scraping
- **Pandas** – Data cleaning & manipulation
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis environment

## 📂 Files in this Repository

| File | Description |
|------|-------------|
| `T20I_Batting_Webscraping_EDA.ipynb` | Main notebook with scraping code and full EDA |
| `t20i_batting_stat.csv` | Scraped dataset (~500 player records) |
| `README.md` | Project documentation |

## 🔍 Key Steps

1. **Web Scraping** – Extracted player batting statistics (matches, innings, runs, balls faced, strike rate, etc.) across multiple pages of ESPNcricinfo.
2. **Data Cleaning** – Removed unnamed/index columns, handled missing values, standardized column names.
3. **Exploratory Data Analysis**:
   - Identified top 5 run-scorers in T20Is
   - Analyzed strike rate distribution across players
   - Examined relationship between Balls Faced and Runs Scored
   - Visualized top performers using bar charts

## 📊 Key Insights

- Found a **strong positive correlation (0.97)** between Balls Faced and Runs Scored, confirming that facing more deliveries strongly predicts higher run totals.
- Visualized the **Top 5 run-scorers** in T20I cricket history using comparative bar charts.
- Dataset includes **~500 player records** scraped directly from ESPNcricinfo.

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/nandakumar95/T20-Batting-Analysis.git
```
2. Install dependencies:
```bash
pip install pandas matplotlib beautifulsoup4 requests
```
3. Open `T20I_Batting_Webscraping_EDA.ipynb` in Jupyter Notebook or VS Code and run all cells.

## 📈 Future Improvements

- Add bowling statistics for a complete player performance profile
- Build an interactive dashboard using Streamlit or Power BI
- Automate periodic data refresh via scheduled scraping

## 👤 Author

**Nanda Kumar**
Data Analyst | [LinkedIn](https://www.linkedin.com/in/nanda-kumar-banda/) | [GitHub](https://github.com/nandakumar95)
