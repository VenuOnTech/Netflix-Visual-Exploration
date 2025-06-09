# Netflix-Visual-Exploration

# 🎬 Netflix Movies and TV Shows - Exploratory Data Analysis (EDA)

Explore the inner workings of Netflix’s content library using Python!  
This project dives deep into the Netflix dataset (~8,800 rows, 12 columns) to uncover insights about content type, genres, release trends, top countries, directors, and more — all through clear visualizations and analysis.

---

## 📁 Dataset Information

- **Source**: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) (Kaggle)
- **Rows**: ~8,800
- **Columns**: 12
- **Attributes**:
  - Title, Type (Movie/TV Show), Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre, Description

---

## 📌 Objectives

- Perform data cleaning and feature engineering
- Analyze trends in content addition over time
- Visualize top genres, ratings, and content-producing countries
- Explore top directors and actor insights
- Conduct basic sentiment analysis on content descriptions

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| `Pandas` | Data manipulation |
| `Seaborn` / `Matplotlib` | Static visualizations |
| `Plotly` | Interactive visualizations |
| `TextBlob` | Sentiment analysis of descriptions |
| `Google Colab` | Notebook development & execution |

---

## 📊 Key Insights

- Movies dominate Netflix's content, but TV shows are rapidly increasing.
- Most content was added between 2018–2020, suggesting aggressive expansion.
- The **USA**, **India**, and **UK** are the top content producers.
- Genres like **Dramas**, **International TV**, and **Comedies** are most popular.
- Many content descriptions show a neutral to slightly positive tone in sentiment.

---

## 🔍 Noteworthy Features

- ✅ Modular plotting functions for reuse  
- ✅ Visual and text-based analysis  
- ✅ Clean, well-commented code structure  
- ✅ Observations listed below each visualization  
- ✅ Interactive charts using Plotly  
- ✅ Sentiment polarity distribution using `TextBlob`

---

## 📁 Project Structure

netflix-eda-project/  
├── Business Insights from Netflix Dataset Using Python & Visualization Tools.ipynb # Jupyter Notebook (main analysis)  
├── netflix_titles.csv # Dataset (uploaded in Colab)  
└── README.md # Project description  


---

## 🚀 How to Use

1. Clone the repo or open `Business Insights from Netflix Dataset Using Python & Visualization Tools.ipynb` in [Google Colab](https://colab.research.google.com/drive/1hgG3_JEExWIwAXWx87zd7ZZUfbcyZfB4?usp=sharing)
2. Upload the dataset file (`netflix_titles.csv`)
3. Run the notebook to explore the analysis step-by-step

---

## 📌 Future Improvements

- Build an interactive dashboard using Streamlit
- Recommend content based on genre and description using NLP
- Time-series modeling to forecast Netflix content trends

---

> **“In God we trust, all others must bring data.” – W. Edwards Deming**
