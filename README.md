# 🎬 Netflix Data Analysis (Pandas + Matplotlib)

## 📌 Project Overview

This project analyzes the Netflix dataset to uncover insights about content distribution, trends, and patterns using **Pandas, NumPy, and Matplotlib**.

The goal is to perform **data cleaning, exploratory data analysis (EDA), and visualization** to understand how Netflix content has evolved over time.

---

## 📂 Dataset

* Source: Netflix dataset (CSV)
* Contains information about:

  * Title
  * Type (Movie / TV Show)
  * Cast, Director
  * Country
  * Release Year
  * Rating
  * Duration
  * Date Added

---

## 🧹 Data Cleaning Steps

* Handled missing values in categorical columns
* Converted `date_added` to datetime format
* Extracted numeric values from `duration`
* Converted data types (`category`, `int`)
* Removed inconsistencies (spaces, nulls)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 1. Movies vs TV Shows

* Compared distribution of Movies and TV Shows
* Visualized using bar chart

### 🔹 2. Content Growth Over Time

* Analyzed number of movies released per year
* Observed rapid growth after 2000

### 🔹 3. Top Countries

* Identified top 10 content-producing countries
* Compared Movies vs TV Shows using stacked bar chart

### 🔹 4. Categorical Analysis

* Count distribution of:

  * Type
  * Country
  * Rating

---

## 📈 Key Insights

* 📌 Movies dominate Netflix content compared to TV Shows
* 📌 Significant growth in content after 2000
* 📌 USA is the leading content producer
* 📌 Most content is targeted towards mature audiences (TV-MA)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib

---

## 📊 Visualizations

* Bar Charts
* Line Graphs
* Stacked Bar Charts

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── data/
├── outputs/
│   └── plots/
├── netflix_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Future Improvements

* Add Seaborn for advanced visualization
* Build recommendation system
* Apply Machine Learning models

---

## 👨‍💻 Author

* Ramavath Manthru Naik

---

⭐ If you like this project, give it a star!
