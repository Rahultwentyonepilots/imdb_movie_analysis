# 🎬 IMDB Movie Data Analysis  

## 📌 Overview  
This project analyzes a dataset of **5,000+ IMDB movies** to uncover insights on:  
- Movie profitability (budget vs. gross revenue)  
- Audience preferences and voting patterns  
- Top directors and their average ratings  
- Popular genres by IMDB score  
- Actor influence on reviews (Leonardo DiCaprio, Brad Pitt, Meryl Streep)  

The analysis uses **data cleaning, exploratory data analysis (EDA), and visualization** to provide a structured understanding of what drives a movie’s success.  

---

## 📊 Dataset  
- **Source:** Provided `IMDB_Movies.csv` (28 features, 5,043 rows).  
- **Key Columns:**  
  - `movie_title` – Name of the movie  
  - `director_name` – Director of the movie  
  - `budget` – Production budget  
  - `gross` – Worldwide gross revenue  
  - `genres` – Genre(s) of the movie  
  - `imdb_score` – IMDB rating  
  - `num_voted_users` – Number of audience votes  

---

## 🛠️ Tools & Technologies  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📈 Key Insights  

- **💰 Most Profitable Movies:**  
  - *Avatar, Titanic, Jurassic World, Avengers* topped the list.  

- **⭐ IMDB Top 250:**  
  - Created ranking of highest-rated movies with >25k votes.  
  - Included non-English classics (*Amélie, Oldboy, A Separation, Baahubali*).  

- **🎬 Top Directors:**  
  - Christopher Nolan, Alfred Hitchcock, and Tony Kaye had the highest average IMDB scores.  

- **🎭 Popular Genres:**  
  - *Crime, Drama, Fantasy, Mystery* genres achieved top ratings.  

- **👨‍🎤 Actor Analysis:**  
  - Leonardo DiCaprio had the **highest critic & user reviews** compared to Brad Pitt and Meryl Streep.  

- **📅 Audience Voting Trends:**  
  - Voting activity exploded in the **2000s and 2010s**, showing growing global engagement.  

---

## 📂 Project Structure  

```
IMDB-Movie-Analysis/
│── data/
│   └── IMDB_Movies.csv
│── notebooks/
│   └── IMDB_movie_analysis.ipynb
│── reports/
│   └── IMDB_movie_analysis.pdf
│── images/
│   └── (charts and visualizations)
│── README.md
│── requirements.txt
```

---

## 🚀 How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/IMDB-Movie-Analysis.git
   cd IMDB-Movie-Analysis
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**  
   ```bash
   jupyter notebook notebooks/IMDB_movie_analysis.ipynb
   ```

---

## 📌 Sample Visualizations  

### Top 10 Profitable Movies  
![Top Profitable Movies](images/top_10_profitable_movies.png)  

### Top 10 Directors by Average IMDB Score  
![Top Directors](images/top_10_directors.png)  

### Audience Voting Trends by Decade  
![Voting Trends](images/voting_trends.png)  

---

## 🔮 Future Scope  
- Build ML models to **predict profitability and IMDB scores**.  
- Integrate **social media sentiment (Twitter, YouTube reviews)**.  
- Extend analysis to **modern OTT datasets (Netflix, Prime, etc.)**.  
- Add **actor/crew-level performance models** for deeper insights.  

---

## ✨ Key Learnings  
This project demonstrates:  
- Handling messy real-world data with missing values and duplicates.  
- Using EDA to extract actionable insights from large datasets.  
- Effective data visualization for storytelling.  
- Applying Python for entertainment & business analytics.  

---

📌 **Author:** Rahul P.  
