# 🏀 NBA Stats Viewer App

An interactive dashboard to explore NBA player statistics — visualize, filter, and gain insights on historical player performance.

Built with:
- Python 🐍
- Pandas 🧾
- Streamlit 🎈
- Plotly 📊 (for visualizations)

## 🚀 Features
- Select specific seasons to analyze player data
- Filter by teams, player positions, and performance metrics
- Dynamic data visualizations (bar charts, heatmaps)
- Downloadable data preview

## 📘 Dataset
Uses player statistics scraped from [Basketball-Reference.com](https://www.basketball-reference.com/) using `BeautifulSoup`.

## 🧠 Learning Goal
Inspired by the [Data Professor Streamlit Series](https://youtu.be/JwSS70SZdyM), this project taught me:
- Web scraping basics
- How to build visual, data-driven dashboards with Streamlit

## 🔗 Live Demo
[View on Streamlit Cloud](https://your-nba-stats-app.streamlit.app/) *(if hosted)*

## 🛠️ How to Run Locally
```bash
git clone https://github.com/DarkPhoenixFn56/NBA_player_stats.git
cd NBA_player_stats
pip install -r requirements.txt
streamlit run app.py
