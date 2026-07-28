# Netflix Data Analysis 📊

Exploratory data analysis and visualization of the Netflix Movies & TV Shows dataset using Python.

## 🎯 Objective
To clean, explore, and visualize the Netflix content catalog in order to uncover trends
in genres, ratings, countries, and content growth over time.

## 📁 Dataset
[Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
(~8,800 titles, columns: type, title, director, cast, country, date_added, release_year,
rating, duration, genres, description)

## 🛠️ Tools Used
- Python
- Pandas & NumPy — data cleaning and manipulation
- Matplotlib & Seaborn — data visualization
- Jupyter Notebook

## 📈 Visualizations
15 plots covering:
- Movies vs TV Shows split
- Content growth over the years
- Top 15 content-producing countries
- Rating distribution
- Movie duration (histogram, KDE, box plot)
- Top genres and top directors
- Release year trend
- Correlation heatmap
- Longest movies
- TV show season counts
- Content added by month

All chart images are saved to the `images/` folder.

## 🔍 Key Findings
_Fill this in after running the notebook — 5-8 of your strongest, most specific insights._

- Example: "More than 65% of Netflix content is rated TV-MA or TV-14, showing the platform
  primarily targets mature audiences."
- ...

## 🚀 Future Improvements
- Sentiment analysis on show descriptions
- Predictive modeling (e.g. genre classification)
- Interactive dashboard (Plotly / Streamlit)

## 📂 Project Structure
```
Netflix-Data-Analysis/
├── data.csv
├── notebook.ipynb
├── README.md
├── images/
└── requirements.txt
```

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
