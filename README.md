# Data-Analysis-With-Python-Netflix-Movie-Analysis

# 📺 Netflix Movie Data Analysis

A data-driven project analyzing 9,000+ Netflix movie entries to extract actionable insights for business decisions. This project explores trends in genre, popularity, vote averages, and annual releases using Exploratory Data Analysis (EDA) techniques.

---

## 📌 Table of Contents

* [🔍 Project Overview](#project-overview)
* [🎯 Objectives](#objectives)
* [📂 Dataset Description](#dataset-description)
* [🧪 Questions Answered](#questions-answered)
* [📈 Key Insights](#key-insights)
* [🛠️ Tech Stack](#tech-stack)
* [📊 Visualizations](#visualizations)
* [📌 How to Run](#how-to-run)
* [✅ Results Summary](#results-summary)

---

## 🔍 Project Overview

Netflix, originally a DVD rental company, has grown into a global streaming giant. With millions of users and a massive content library, Netflix heavily relies on data to guide its content strategy.
This project performs EDA on a large Netflix movie dataset to uncover valuable insights into what drives success on the platform.

---

## 🎯 Objectives

* Identify the most frequently released genres.
* Discover which movies are most/least popular.
* Analyze which year had the highest number of movie releases.
* Understand the relationship between vote averages and popularity.

---

## 📂 Dataset Description

The dataset contains over 9,000 movie entries with the following key columns:

| Column Name    | Description                |
| -------------- | -------------------------- |
| `title`        | Movie title                |
| `genre`        | Movie genres               |
| `release_year` | Year of release            |
| `popularity`   | Popularity score (numeric) |
| `vote_average` | Average user rating        |
| `vote_count`   | Total votes received       |

---

## 🧪 Questions Answered

1. What is the most frequent genre of movies released on Netflix?
2. Which movie has the highest vote average?
3. What movie got the highest popularity? What’s its genre?
4. What movie got the lowest popularity? What’s its genre?
5. Which year had the most filmed movies?

---

## 📈 Key Insights

* **Drama** is the most frequent genre on Netflix.
* The movie with the **highest vote average** is *The Godfather*.
* The most **popular movie** is *Extraction* (Action/Thriller).
* The **least popular movie** is *Kuch Bheege Alfaaz* (Drama/Romance).
* **2021** saw the highest number of Netflix movie releases.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas 🐼
* Matplotlib & Seaborn 📊
* Jupyter Notebook 📓

---

## 📊 Visualizations

* Bar plot of movie genres
* Histogram of popularity
* Line chart for number of movies per year
* Scatter plot of vote average vs popularity

---

## 📌 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/netflix-movie-analysis.git
```

2. Navigate to the project folder

```bash
cd netflix-movie-analysis
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the notebook

```bash
jupyter notebook Netflix_Movie_Analysis.ipynb
```

---

## ✅ Results Summary

Netflix’s content strategy benefits from frequent drama releases, action thrillers for popularity, and a growing number of films year by year. These insights can inform future production and marketing efforts.

Author 
Vishwanath kulal
