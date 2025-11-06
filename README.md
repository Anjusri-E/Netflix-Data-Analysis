# 🎬 Netflix Data Cleaning, Analysis & Visualization

### 📊 *End-to-End Data Science Project by Anjusree E*  
*(Data Science Intern @ Unified Mentor)*  

---

## 🧠 Project Overview
This project explores and analyzes Netflix’s catalog of movies and TV shows to uncover insights about content types, genres, countries, release years, and audience ratings.  
It demonstrates an end-to-end **data cleaning, feature engineering, and visualization process** using Python.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, wordcloud  
- **Tools:** Jupyter Notebook, VS Code  
- **Visualization:** Seaborn & Matplotlib  

---

## 📂 Dataset Information
- **Raw File:** `netflix1.csv`  
- **Cleaned Output:** `netflix_cleaned.csv`  


---

## 🧹 Data Cleaning Steps
1. Removed duplicate rows and irrelevant data.  
2. Handled missing values (`NaN`, blanks, "Unknown").  
3. Converted `date_added` into proper `datetime` format.  
4. Extracted new features:
   - `year_added` (Year added to Netflix)
   - `month_added`
   - `num_genres` (Number of genres per title)
5. Cleaned text fields and standardized formats.  
6. Saved cleaned dataset as `netflix_cleaned.csv`.

---

## 📊 Exploratory Data Analysis (EDA)

| # | Analysis | Insight | Plot File |
|---|-----------|----------|-----------|
| 1 | Movies vs TV Shows | Netflix has more Movies than TV Shows | `plots/movies_vs_tv.png` |
| 2 | Ratings Distribution | Majority rated TV-MA / TV-14 | `plots/rating_distribution.png` |
| 3 | Top Countries | USA, India, UK lead | `plots/top_countries.png` |
| 4 | Top Genres | Dramas & Comedies dominate | `plots/top_genres.png` |
| 5 | Titles Added by Year | Sharp growth 2015–2018 | `plots/titles_by_year.png` |
| 6 | Top Directors | Few directors produce multiple titles | `plots/top_directors.png` |
| 7 | Word Cloud | Common words reflect emotional themes | `plots/wordcloud_titles.png` |

---

## 💡 Key Insights
- 🎞 Movies make up about 70 % of Netflix’s catalog.  
- 🌍 USA leads in production, followed by India and UK.  
- 📈 Rapid expansion occurred between 2015 – 2018.  
- 🎭 Drama and Comedy dominate the platform.  
- 🔞 Most titles are rated TV-MA or TV-14.  
- 🎬 A small number of directors contribute many titles.  

---

📁 Repository Structure
Netflix_Project/
├── netflix_analysis.ipynb        # Main analysis notebook
├── netflix_cleaned.csv           # Cleaned dataset
├── netflix1.csv                  # Raw dataset (optional)
├── requirements.txt              # Project dependencies
├── plots/                        # Folder containing all saved visualizations
│   ├── movies_vs_tv.png
│   ├── rating_distribution.png
│   ├── top_countries.png
│   ├── top_genres.png
│   ├── titles_by_year.png
│   ├── top_directors.png
│   └── wordcloud_titles.png
└── README.md

⚙️ How to Run This Project

Clone this repository:

git clone https://github.com/Anjusri-E/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis


Install dependencies:

pip install -r requirements.txt


Open the notebook:

netflix_analysis.ipynb


Run all cells sequentially (Kernel → Restart & Run All)

🚀 Future Enhancements

Build an interactive dashboard using Power BI or Plotly

Predict Netflix ratings using machine learning models

Compare Netflix with Amazon Prime / Disney+ datasets

✨ Author

👩‍💻 Anjusree E
📚 Data Science Intern @ Unified Mentor
🔗 GitHub Profile

🔗 LinkedIn Profile

✅ End of Project

“Data tells the story — analysis gives it meaning.”