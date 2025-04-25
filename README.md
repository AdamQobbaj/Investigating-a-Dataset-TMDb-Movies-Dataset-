
# 🎬 Investigating the TMDb Movies Dataset

This project analyzes the [TMDb Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) to uncover insights about movie trends, genres, popularity, and financial performance. Conducted using Python and Jupyter Notebook, this project emphasizes data cleaning, manipulation, and visualization.

---

## 📊 Project Overview

The goal of this project is to perform an exploratory data analysis (EDA) on the TMDb dataset, which contains information about 10,000 movies. The analysis addresses questions like:

- How has movie production changed over time?
- What are the most common genres?
- Do higher budgets lead to higher revenue?
- What’s the relationship between runtime and popularity?

---

## 🔍 Research Questions

1. **What kinds of properties are associated with movies that have high revenue?**
2. **Which genres are most popular from year to year?**
3. **What is the average runtime of movies, and how has it changed over time?**
4. **Do high budgets always mean high revenue?**
5. **Which year had the most movie releases?**

---

## 🧪 Data Cleaning and Manipulation

A thorough data cleaning and wrangling process was performed using `pandas`:

- Dropped irrelevant columns: `homepage`, `tagline`, `keywords`, `id`, etc.
- Removed duplicate entries.
- Filtered out rows with zero `budget` or `revenue`.
- Converted `release_date` to datetime and extracted `release_year`.
- Created new columns:
  - `profit = revenue - budget`
  - Separated multiple genres using string operations.

---

## 📊 Data Analysis Highlights

- 📈 **Revenue Correlation**: There is a weak positive correlation between budget and revenue.
- 🎭 **Genre Popularity**: Drama and Comedy are the most common genres. Action movies tend to generate higher revenue.
- ⏱️ **Movie Runtime**: The average runtime is around 110 minutes. Shorter films are more common post-2000.
- 💰 **Top Performers**: 
  - *Avatar* had the highest revenue.
  - *The Warrior’s Way* had the highest budget.
  - *The Story of Film: An Odyssey* had the highest rating (9.2).

---

## 📁 Repository Structure

- `Investigate_a_Dataset.ipynb`: Main Jupyter Notebook with code and analysis.
- `Investigate_a_Dataset.html`: Exported version of the notebook for easy viewing.
- `tmdb-movies.csv`: The dataset file used in the project.
- `README.md`: Project summary and guide.

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib 
- Jupyter Notebook

---


## 📄 License

This project is licensed for educational use.
