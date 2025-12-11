# 📊 IMDB Movie Dataset – Exploratory Data Analysis (EDA)

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset of movies collected from **IMDB using web scraping**.
The goal is to uncover insights related to movie performance, genres, ratings, revenue, actors, directors, runtime patterns, and regional trends.

---

## 📁 **Project Overview**

Movies vary widely in **genre, region, language, runtime, ratings, votes, and box office revenue**.
Understanding which factors contribute to a movie’s success is challenging.

This project analyzes **500 movies across 12 attributes** scraped directly from IMDB.

### 🎯 **Objectives**

* Identify the **most popular genres**
* Analyze **ratings, votes, and revenue patterns**
* Compare movie industries: **Hollywood, Bollywood, Tollywood**
* Study release trends **over the years**
* Understand **runtime patterns**
* Examine relationships between **ratings, votes, and revenue**

---

## 🛠️ **Tools & Technologies Used**

### **Languages & Platform**

* Python 3.12
* Jupyter Notebook

### **Python Libraries**

#### **Data Extraction**

* BeautifulSoup
* Regular Expressions (re)
* Pandas
* NumPy

#### **Data Analysis**

* Pandas
* NumPy

#### **Visualization**

* Matplotlib
* Seaborn

---

## 📦 **Dataset Details**

* **Source:** Scraped from **IMDB.com** using BeautifulSoup
* **Shape:** *500 rows × 12 columns*
* **Key Columns:**
  `Title`, `Year`, `Genre`, `Rating`, `Runtime`, `Votes`, `Gross`, `Region`, `Certificate`, `Language`, `Actor`, `Director`

---

## 🧹 **Data Cleaning & Preprocessing**

### ✔ Runtime Column

Converted values like **"2h 8min" → 128 minutes** using custom parsing.


### ✔ Rating Column

Extracted numeric rating from noisy strings using regex.
Example: `"59% (69) 7.1 (2k) 100%" → 7.1`


### ✔ Title Column

Separated movie title and year:
`"Baahubali (2024)" → Title: Baahubali, Year: 2024`


---

## 📊 **Exploratory Data Analysis**

### 🔹 Rating Distribution

Most films rated **6.5–8.5**, showing general audience acceptance.


### 🔹 Genre Popularity

**Action and Drama** are the dominant genres.


### 🔹 Region Comparison

Hollywood leads in movie count and revenue due to budgets and global reach.


### 🔹 Top 10 Highest Grossing Movies

Mostly Hollywood and Action films with strong star power and marketing.


### 🔹 Directors with Most Movies

Directors having more films show consistency and industry preference.


### 🔹 Movies Per Year

Film releases show an upward trend over the years.


### 🔹 Runtime Patterns

Most movies fall between **120–160 minutes** (standard industry length).


### 🔹 Actor Frequency

Top actors appear repeatedly, indicating high demand.


### 🔹 Correlation Analysis

Strong positive correlation between **Votes and Gross Revenue**.
Longer runtime ≠ more success.


---

## 📝 **Key Insights**

* Action & Drama are the most released genres.
* Hollywood dominates in production and revenue.
* Most movies have positive audience ratings.
* More audience votes lead to higher revenue.
* Industry growth is visible with more movie releases every year.

---

## ✅ **Conclusion**

Movie success is influenced mainly by:

* **Genre**
* **IMDB Ratings**
* **Audience Reach (Votes)**

Hollywood films earn more due to global distribution and large-scale production.
Typical runtime for successful movies is **120–160 minutes**.


---

## 👨‍💻 **Contributors**

* **M. Anil Kumar**
* **A. Malla Reddy**
