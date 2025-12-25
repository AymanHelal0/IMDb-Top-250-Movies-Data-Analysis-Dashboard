# 🎬 IMDB Top 250 Movies Dashboard

## 📌 Overview

This project is an **interactive data analysis dashboard** built to explore and analyze the **Top 250 Movies on IMDB**. The dashboard provides insights into movie ratings, categories, decades, reviewers, and trends over time.

A key highlight of this project is the **data acquisition directly from the web (IMDB website)** and the extensive **data cleaning and transformation process using Power Query** before building the final dashboard.

The dashboard is designed with a **Dark / Night-friendly color theme** to enhance visual clarity and user experience.

---

## 🌐 Data Source

* **Source:** IMDB Website (Top 250 Movies)
* **Data Type:** Web-scraped tabular data
* **Records:** Top 250 Movies

### Data Attributes Include:

* Movie Title
* Rating
* Number of Reviewers
* Duration (Minutes)
* Movie Category (PG, PG-13, R, etc.)
* Release Year
* Decade

---

## 🧹 Data Preparation (Power Query)

Since the dataset was extracted directly from a **web URL**, significant preprocessing was required:

* Extracted structured tables from web content
* Removed unnecessary columns and metadata
* Cleaned inconsistent text and symbols
* Converted data types (numbers, dates, durations)
* Created calculated columns:

  * Movie Decade
  * Rating Categories
* Handled missing and duplicated values
* Ensured data quality before visualization

This step was essential to transform raw web data into a reliable analytical dataset.

---

## 🎯 Project Objectives

* Analyze rating distribution across movie categories
* Study trends of movie ratings by decade
* Identify most common movie categories
* Compare audience engagement using number of reviewers
* Highlight top-rated movies

---

## 🛠 Tools & Technologies

* **Data Visualization:** Power BI
* **Data Cleaning & Transformation:** Power Query
* **Data Source:** Web URL (IMDB)
* **Design Theme:** Dark / Night Mode

---

## 📊 Dashboard Features

### 🔹 Key Performance Indicators (KPIs)

* Total Movies (250)
* Total Reviewers
* Average Movie Duration
* Maximum Rating
* Minimum Rating

---

### 🔹 Movies Table View

* Ranked list of IMDB Top 250 Movies
* Includes:

  * Movie Name
  * Duration
  * Number of Reviewers
  * Rating
  * Category
  * Decade
  * Year

---

### 🔹 Movies by Decade

* Line chart showing number of movies released per decade
* Highlights growth and decline trends in movie production

---

### 🔹 Movies by Category

* Donut chart representing distribution of movies by category (PG, PG-13, R, etc.)

---

### 🔹 Movies by Decade & Category

* Stacked bar chart combining decade and category analysis
* Shows how movie classifications evolved over time

---

### 🔹 Average Rating by Decade

* Line chart showing average movie ratings per decade
* Reveals quality trends across different eras

---

### 🔹 Top Movies by Rating

* Bar chart displaying the highest-rated movies

---

### 🔹 Reviewers Analysis

* Bar chart showing number of reviewers by movie category
* Helps measure audience engagement

---

## 🎛 Interactivity

* **Category Slicer:** Filter movies by rating category
* **Year Slicer:** Filter movies by release year
* Dynamic cross-filtering across all visuals

---

## 🌙 Dashboard Theme

* Designed using a **Dark / Gold Night Mode**
* Improves readability and reduces eye strain
* Consistent color palette across all visuals

---

## 📌 Key Insights

* PG-13 and R movies dominate the Top 250 list
* Certain decades show higher average ratings
* Viewer engagement varies significantly by category
* Older classic movies maintain high ratings despite fewer reviewers

---

## 🚀 Future Enhancements

* Automate data refresh from IMDB
* Add genre-level analysis
* Compare IMDB ratings with other platforms
* Add sentiment analysis from reviews

---

## 👤 Author

* **Project Type:** Web Data Analysis & Visualization
* **Focus Area:** Entertainment Analytics

---

⭐ If you find this project useful, feel free to star the repository!
