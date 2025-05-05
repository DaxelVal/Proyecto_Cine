# 🎬 Movie Analytics Dashboard

This repository presents a data analytics dashboard that explores various aspects of the film industry using a cleaned movie dataset. The entire process was conducted using Python (Colab), SQL, Power BI, and Figma for dashboard design. The goal is to uncover trends in popularity, perceived quality, and genre evolution across years and decades.

---

## ✨ Project Objective

The project aims to:

- Explore the dataset and identify patterns in movie popularity and quality.
- Determine the most popular and best-rated genres.
- Understand how production has evolved over the years.
- Build a visual dashboard to communicate insights effectively.

---

## 🧼 Data Cleaning and Preparation

The dataset (`df_merged`) was merged and cleaned in Google Colab. Key transformations included:

- Handling missing values and formatting dates.
- Splitting multi-genre entries.
- Converting data types for numerical operations.

---

## 🔍 Exploratory Data Analysis

### 📌 Popularity Distribution by Year and Genre (2000–Present)

**Visualization:** Boxplot

**What it shows:** The distribution of popularity scores (e.g., number of votes) by genre and year. This allows for a visual comparison of how different genres have performed over time.

![Descripción de la imagen](foto.jpg)

**Insight:** Action and Animation genres show higher variation in popularity, while Drama shows more consistency.

---

### 📌 Perceived Quality by Genre (Average Ratings)

**Visualization:** Boxplot of `avg_vote` grouped by genre

**What it shows:** Highlights genres with higher average ratings.

*Embed image here*

**Insight:** Documentaries and Dramas tend to receive the highest average votes, implying stronger perceived quality.

---

### 📌 Popularity vs. Quality Comparison

**Visualization:** Scatter plot of votes vs. average_vote with regression line

**What it shows:** Whether movies with high popularity are also perceived as high quality.

*Embed image here*

**Insight:** A slight positive correlation indicates that popular movies often receive decent ratings, though outliers exist.

---

### 📌 Movie Production Over Time

**Metric:** Number of movies per decade

**What it shows:** Trends in how the volume of film production has changed across time.

*Embed image here*

**Insight:** Film production has significantly increased in the 2000s and beyond.

---

## 📈 Key KPIs (Power BI)

- **Year with Most Releases**: Dynamically calculated year with the highest count of movies.
- **Most Popular Genre**: Based on total votes.
- **Best Rated Genre**: Based on average ratings.
- **Genre Trends by Decade**: Highlights the rise or decline of specific genres over decades.

---

## 🎨 Dashboard Layout (UX/UI)

The dashboard was prototyped in Figma with a clear layout for usability:

- **Header:** Filters and title
- **Sidebar:** Controls for selecting year/genre
- **Main Section:** Visual insights and KPIs
- **Footer:** Dataset information and credits

*Embed Figma dashboard image here*

---

## 🛠️ Tools & Technologies

- **Python (Colab)**: Data wrangling and EDA
- **SQLite**: Filtering and querying data
- **Power BI**: Creating visualizations and dashboards
- **Figma**: UX/UI layout design

---

## 📂 Repository Structure

```
├── README.md
├── dashboard.pbix
├── data/
│   └── df_merged_cleaned.csv
└── analysis/
    ├── exploratory.ipynb
    └── queries.sql
```

---

## 👏 Author

Developed by Daxel Valenciano 

---

## 🧠 Summary

This dashboard helps users explore whether the most viewed movies are also the best rated, which genres dominate in popularity or quality, and how movie production has evolved over time. It combines statistical analysis with visual storytelling, offering a powerful tool for insights into the film industry.

Perfect for academic, portfolio, or interview purposes.
