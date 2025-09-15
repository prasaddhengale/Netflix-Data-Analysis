# 📊 Netflix-Data-Analysis
## 📌 Project Overview
This project analyzes the Netflix dataset (2008 - 2019) with Python to uncover patterns in content production, ratings, genres, and country contributions.
The goal is to showcase data cleaning, visualization, and exploratory data analysis (EDA) skills using Python, Pandas, Matplotlib, and Seaborn.

---

## 🛠️ Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Environment: Jupyter Notebook

---

## 📂 Dataset
- **File:** 'netflix_titles_nov_2019.csv' (included in this repository)
- **Size:** 2.14 MB (~5,800 Movies + TV Shows)
- **Source:** [Netflix Shows and Movies - Exploratory Analysis](https://www.kaggle.com/code/shivamb/netflix-shows-and-movies-exploratory-analysis/input)

---

## 📊 Analysis & Visualizations
🔹 1. Data Cleaning
- Handled missing values in country, rating, cast, and director.
- Converted date_added to datetime format.
- Removed duplicates for a clean dataset.

🔹 2. Content Growth Over Time
- Visualized the number of titles added per year and month.

🔹 3. Genre vs Country Heatmap
- Exploded multiple genres & countries.
- Created a heatmap of Top 10 countries vs Top 10 genres.

🔹 4. Actor-Genre Analysis
- Identified Top 10 actors with most Netflix appearances.
- Plotted heatmap of their genre distribution.

🔹 5. Ratings vs Country Distribution
- Created stacked bar chart for rating distribution across Top 10 countries.

🔹 6. TV Shows with Most Seasons
- Extracted season count from duration column.
- Visualized Top 20 longest-running TV shows.

🔹 7. Movie Duration by Rating
- Calculated average duration of movies per rating category.
- Compared trends for adult vs kids’ content.

---

## 📷 Sample Visuals
<img width="1019" height="815" alt="download" src="https://github.com/user-attachments/assets/7b6a1c32-ee8a-4f12-a3fc-543fd569dc9b" />
<img width="1190" height="590" alt="download" src="https://github.com/user-attachments/assets/1b21a6aa-af9a-49e2-a76d-e141383664c3" />

---

## 📌 Key Insights
- Netflix content production has grown exponentially since 2015.
- The United States & India dominate Netflix’s content library.
- Drama, Comedy, and International Movies are the most common genres.
- David Attenborough and Anupam Kher are among the most frequent actors in Netflix titles.
- Children’s movies are shorter, while adult-rated movies have longer average durations.

---

## 🚀 How to Run
- Download the notebook and dataset from this repo.
- Open the notebook in Jupyter and run all cells.
