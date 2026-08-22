# 🎬 Netflix Data Analysis

An end-to-end Data Analysis project using Python and Pandas to explore Netflix Movies and TV Shows. The project focuses on data exploration, business questions, data visualization, and extracting meaningful business insights from the dataset.

---

## 📌 Project Overview

This project analyzes a Netflix dataset to understand the distribution and characteristics of Movies and TV Shows available in the dataset.

The analysis answers several business questions related to:

- Content types
- Countries
- Release years
- Ratings
- Genres
- Directors
- Actors
- Netflix content added by year
- Movie durations
- Movies vs TV Shows percentages

The project was developed in **Jupyter Notebook** using Python data analysis and visualization libraries.

---

## 🎯 Business Questions

The project answers the following business questions:

1. How many Movies and TV Shows are available on Netflix?
2. Which countries have produced the most Netflix content?
3. Which release years have the highest number of Netflix titles?
4. Which rating is the most common on Netflix?
5. Which genres are the most common on Netflix?
6. Which directors have directed the most Netflix titles?
7. Which actors appear in the highest number of Netflix titles?
8. In which year did Netflix add the most titles?
9. What is the distribution of movie durations on Netflix?
10. What percentage of Netflix content consists of Movies versus TV Shows?

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 🔍 Exploratory Data Analysis

The following EDA techniques were performed:

- Displaying the first rows of the dataset
- Checking dataset information
- Generating summary statistics
- Checking missing values
- Checking duplicate records
- Checking dataset shape
- Inspecting column names
- Checking data types

The dataset contained no missing values or duplicate records that required cleaning for the analyzed fields.

---

## 📊 Key Business Insights

### 1. Content Type

The dataset contains:

- **55 Movies**
- **41 TV Shows**

Movies represent approximately **57.3%** of the dataset, while TV Shows represent approximately **42.7%**.

---

### 2. Top Countries

The **United States** has the highest number of titles with **23 titles**.

Other leading countries include:

- Japan — **14 titles**
- United Kingdom — **7 titles**
- India — **7 titles**

---

### 3. Release Year

**2021** is the most common release year with **50 titles**.

Other important years include:

- 2020 — **8 titles**
- 2018 — **4 titles**
- 2013 — **3 titles**

This shows that the dataset is strongly concentrated around recent releases.

---

### 4. Most Common Rating

**TV-MA** is the most common rating with **31 titles**.

Other common ratings include:

- TV-PG — **17**
- TV-14 — **17**
- PG-13 — **8**
- TV-Y7 — **8**

---

### 5. Most Common Genres

**International Movies** are the most common genre with **27 titles**.

Other common genres include:

- International TV Shows — **20**
- Action & Adventure — **20**
- Dramas — **14**
- Anime Features — **12**
- Comedies — **11**
- TV Dramas — **11**

---

### 6. Top Directors

**Toshiya Shinohara** directed the highest number of titles among the listed directors, with **4 titles**.

Other leading directors include:

- Masahiko Murata — **3 titles**
- Hajime Kamegaki — **2 titles**
- Delhiprasad Deenadayalan — **2 titles**

The dataset contains **63 unique directors**.

---

### 7. Top Actors

**Junko Takeuchi** and **Chie Nakamura** appear in the highest number of titles, with **8 titles each**.

Other frequently appearing actors include:

- Kazuhiko Inoue — **6 titles**
- Houko Kuwashima — **5 titles**
- Showtaro Morikubo — **5 titles**

The dataset contains **661 unique actors**.

---

### 8. Netflix Titles Added by Year

The available `date_added` records show that **96 titles were added to Netflix in 2021**.

2021 is the only year represented in the available `date_added` records in this dataset.

---

### 9. Movie Duration

Movie durations were extracted from the `duration` column and visualized using a histogram.

The visualization helps understand how movie lengths are distributed across the dataset.

---

### 10. Movies vs TV Shows

Movies represent approximately **57.3%** of the dataset.

TV Shows represent approximately **42.7%**.

Therefore, Movies have a larger share of the content in this dataset.

---

## 📈 Visualizations

The project includes several visualizations:

- Movies vs TV Shows
- Top 10 Countries
- Top Release Years
- Rating Distribution
- Top 10 Genres
- Top Directors
- Top Actors
- Netflix Titles Added by Year
- Movie Duration Distribution
- Movies vs TV Shows Percentage

All important visualizations were saved as PNG files for use in the project and GitHub documentation.

---

## 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
│
├── images/
│   ├── Movies_TV_Shows.png
│   ├── Top_10_Countries.png
│   ├── Top_Release_Years.png
│   ├── Ratings.png
│   ├── Top_10_Genres.png
│   ├── Top_Directors.png
│   ├── Top_Actors.png
│   ├── Add_year.png
│   ├── Duration_distribution.png
│   └── movie_tvshow.png
│
└── README.md


---

## 👨‍💻 Author

Yahya Khan

GitHub: https://github.com/yahyakhan1775

LinkedIn: www.linkedin.com/in/yahyakhan1775
