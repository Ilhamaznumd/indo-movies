---

# 🇮🇩 Indonesian Movies Exploratory Data Analysis

📂 **Project Description**  
This project aims to conduct *Exploratory Data Analysis (EDA)* on a dataset of over 1200 Indonesian films. This analysis helps understand film production trends, popular genres, user ratings, and many other interesting aspects.

---

## 📊 Dataset Information
The dataset used is taken from https://www.kaggle.com/datasets/dionisiusdh/imdb-indonesian-movies/data. This dataset has 11 main columns:
- `title`
- `year`
- `description`
- `genre`
- `rating`
- `users_rating`
- `votes`
- `languages`
- `directors`
- `actors`
- `runtime`

---

## 🔧 Preprocessing
Before EDA was performed, several data cleaning and transformation steps were performed:
- De-duplicate data.
- Ignore rows with missing values ​​in certain visualizations.
- Map categories by year group, votes group, and age rating.
- Clean the actor column from NaN to analyze the most actors.

---

## 📈 Exploratory Data Analysis
The analysis conducted includes:

- **Film Distribution by Year**
➔ Seeing the trend of film production per decade.

- **Film Genre Distribution**
➔ Analyzing which film genres are most produced.

- **User Rating Distribution**
➔ Analyzing the distribution of scores given by users.

- **Age Rating Distribution**
➔ Knowing the target age segmentation of the film.

- **Most Productive Directors**
➔ Who has produced the most films.

- **Most Productive Actors/Actresses**
➔ Who has starred in the most films.

- **Average Rating per Genre**
➔ Seeing which genres get the highest average ratings.

- **Distribution of Ratings from Audiences by Year**
➔ Seeing the trend of film ratings from audiences per year.

- **Movie Distribution by Runtime Category**
➔ Analyzes the category of how long the most-produced films are.

- **Wordcloud Description**
➔ Visualization of the most frequently occurring words in film descriptions.

---

## 📝 Important Notes
- Rows with missing values ​​in important columns (such as `description`, `genre`, `rating`, `directors`, `runtime`) are **ignored** during visualization to maintain analysis accuracy.
- Chart interpretation takes into account potential bias due to missing data.

---
