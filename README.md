# 📊 Netflix Data Analysis Project

An exploratory data analysis (EDA) project using a Netflix-based dataset to uncover insights about content trends, popularity, and genre patterns over time.

---

## 🔍 Project Overview

This project involves cleaning, exploring, and visualizing movie and TV show data. The analysis aims to answer key questions such as:

- What is the most frequent genre of movies released on Netflix?
- Which genre has the highest vote average?
- What movie has the highest popularity, and what are its genres?
- What movie has the lowest popularity, and what are its genres?
- Which year saw the highest number of movies filmed?

---

## 📁 Dataset

- **File Used**: `mymoviesdb.csv`

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📌 Key Features

- Data cleaning (handling missing values, formatting dates, etc.)
- Exploratory data analysis (EDA)
- Visualizations using Matplotlib and Seaborn
- Insight generation based on popularity, votes, and genres

---

# 📈 Visualizations

Here are some key visualizations generated during the Netflix movie dataset analysis:

---

### 🎭 Genre Distribution

A bar chart showing the number of titles in each genre using Seaborn’s `catplot`.

- **Insight**: *Drama* appears most frequently, followed by *Comedy* and *Action*.
- **Plot Type**: Horizontal bar chart (categorical count)

---

### ⭐ Vote Average Distribution

A visual count of movies based on their vote averages.

- **Insight**: Most titles fall within mid-range vote averages (e.g., 5 to 7).
- **Plot Type**: Horizontal bar chart (categorical count)

---

### 📅 Release Date Distribution

A histogram representing the frequency of movie release years.

- **Insight**: A large cluster of releases occurred between 2000 and 2022, peaking in 2020.
- **Plot Type**: Histogram

---

### 📊 Top-Rated Genres by Popularity

Bar chart showing which genres are most popular based on vote counts and average rating.

- **Insight**: Drama again leads in popularity, reaffirming its dominance across metrics.
- **Plot Type**: Grouped or stacked bar plot

---

### 🕒 Movie Production Over Time

Line or bar chart showing how many movies were produced each year.

- **Insight**: The dataset shows the highest production year is **2020**.
- **Plot Type**: Line or bar chart

---

### 🌍 Content by Country (Optional if included)

A bar chart showing which countries produced the most content.

- **Insight**: Typically, the USA leads in content count.
- **Plot Type**: Vertical bar chart

---

### ☁️ (Optional) Word Cloud of Movie Descriptions

A fun visual displaying the most common words used in movie descriptions.

- **Insight**: Common words include terms like "life", "love", "family", and "journey", hinting at recurring themes.
- **Plot Type**: Word Cloud

---

Each plot was generated using Matplotlib and Seaborn, ensuring high-quality, informative visuals.



---

## ✅ Conclusion

**Q1: What is the most frequent genre in the dataset?**  
➡️ *Drama* is the most frequent genre in the dataset, appearing in over **14%** of the entries among 19 other genres.

**Q2: Which genre has the highest votes?**  
➡️ With over **25.5%** of movies receiving votes, *Drama* again leads with more than **18.5%** of the most-voted movies.

**Q3: What movie got the highest popularity and what are its genres?**  
➡️ *Spider-Man: No Way Home* has the highest popularity in the dataset, categorized under **Action**, **Adventure**, and **Science Fiction**.

**Q4: What movie got the lowest popularity and what are its genres?**  
➡️ *The United States, Thread* has the lowest popularity and belongs to **Music**, **Drama**, **War**, **Sci-Fi**, and **History** genres.

**Q5: Which year has the most filmed movies?**  
➡️ The year **2020** recorded the highest number of movies filmed in the dataset.

---

## 🧪 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Netflix_data_analysis.git
