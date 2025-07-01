# 🍿 Netflix User Behavior Analysis

## 📌 Problem Statement

As streaming platforms grow, understanding viewer preferences becomes essential.  
This project explores and analyzes Netflix user behavior to uncover **content preferences**, **binge-watching patterns**, and **genre popularity**.

---

## 🎯 Objective

- Analyze user behavior using multiple datasets:
  - Userbase data
  - Viewing activity
  - Title metadata
- Merge and clean data to generate **insightful visualizations**
- Highlight genre popularity, session patterns, and viewing time
- Support recommendations and content strategy with user insights

---

## 📦 Dataset Overview

### 1. `Netflix Userbase.csv`
- Demographics: Name, Age, Gender, Country, Subscription Type

### 2. `All_ViewingActivity.csv`
- Viewing session details: Profile, Title, Start Time, Duration

### 3. `netflix_titles.csv`
- Content metadata: Title, Genre

---

## 🔧 Key Data Preprocessing Steps

- Merged viewing activity with genre info using a cleaned title key
- Filled missing genres as `"Unknown"`
- Filtered columns to: `Profile Name`, `Start Time`, `Duration`, `Title`, `Genre`

---

## 📊 Visualizations Included

### 🔹 Top Watched Genres
![Top Genres](https://github.com/LAXMAN7795/Netflix-User-Behavior-Analysis/blob/6279baaa14f62d2e7e14df7eae68bf76b29bbab9/output/top_genres.png)

> Documentaries, Dramas, and Comedies emerge as the most-watched genres.

---

### 🔹 Top 10 Users by Watch Time
![Binge Sessions](https://github.com/LAXMAN7795/Netflix-User-Behavior-Analysis/blob/6ef9ea166ec23ee25c35cd729a1d1756ee610d0f/output/watch_hours_per_user.png)

---

### 🔹 Distribution of Binge-Watching Sessions
![Viewing Times](outputs/viewing_time_distribution.png)

> Peak activity seen during **evenings and weekends** — prime streaming hours.

---

### 🔹 User Engagement by Subscription Type
![Engagement by Plan](outputs/subscription_engagement.png)

> Premium users show higher average viewing durations, supporting plan-based engagement segmentation.

---

## 📁 Project Structure

├── Netflix_User_Behavior_Analysis.ipynb
├── datasets/
│ ├── Netflix Userbase.csv
│ ├── All_ViewingActivity.csv
│ └── netflix_titles.csv
├── outputs/
│ ├── top_genres.png
│ ├── watch_hours_per_user.png
│ ├── binge_behavior.png
│ └── ratings_vs_genres.png
└── README.md

---
## 🧠 Conclusion

This analysis provides key insights into **user preferences and behavior patterns** on Netflix.  
It can be used by product teams and marketers to:
- Tailor recommendations
- Optimize content scheduling
- Improve subscription plans and retention strategies

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn

---
## 🙌 Acknowledgments

Thanks to open-source datasets and the Netflix viewing format for enabling this behavioral analysis.
