# 👥 User Analytics Dashboard — Python Project

> Exploring 100 real user profiles from a public API to extract business insights through data analysis and visualization.

---

## 🖼️ Project Preview

| Age Distribution | Blood Type Distribution |
|---|---|
| ![Age](Data%20Analytics%20Project/visualizations/age_distribution.png) | ![Blood](Data%20Analytics%20Project/visualizations/blood_type_donut.png) |

| Eye Color Heatmap | Role Distribution |
|---|---|
| ![Heatmap](Data%20Analytics%20Project/visualizations/eyecolor_gender_heatmap.png) | ![Roles](Data%20Analytics%20Project/visualizations/role_distribution.png) |

| Top 10 Cities | Gender in Top Cities |
|---|---|
| ![Cities](Data%20Analytics%20Project/visualizations/top_cities.png) | ![Gender](Data%20Analytics%20Project/visualizations/gender_top5_cities.png) |

---

## 🧠 Business Questions Answered

- Who are our users? (age, gender, location)
- Which cities have the highest user concentration?
- What roles do users have on the platform?
- Which departments and companies do they come from?
- Is there a pattern between gender and eye color or city?

---

## 🔍 What I Did

- Fetched live data from a public REST API using `requests`
- Explored the dataset — shape, dtypes, missing values, duplicates
- Cleaned and extracted nested JSON columns (city, country, company, department)
- Handled missing values in age, height, and weight
- Built 6 business-relevant visualizations with a custom color palette

---

## 💡 Key Insights

- **85% of users are regular users** — admins and moderators are scarce
- **Phoenix leads** with the highest user concentration across all cities
- **Gender distribution is balanced** across all major cities
- **Blood types are evenly spread** — no dominant group
- Users come from diverse departments suggesting **cross-industry appeal**

---

## 📁 Project Structure
```
repo/
├── Data Analytics Project/
│   ├── Data/
│   │   └── users.json
│   ├── visualizations/
│   │   ├── age_distribution.png
│   │   ├── top_cities.png
│   │   ├── blood_type_donut.png
│   │   ├── eyecolor_gender_heatmap.png
│   │   ├── gender_top5_cities.png
│   │   └── role_distribution.png
│   └── analysis.ipynb
├── Matplotlib/
├── NumPy/
├── Pandas/
├── Seaborn Basics & Styling/
└── README.md
```

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 🚀 How to Run
```bash
git clone https://github.com/samawael7/Data-Analytics-Libraries-in-python
pip install pandas requests seaborn matplotlib jupyter
jupyter notebook analysis.ipynb
```

---

*Built as part of a data engineering learning journey 🛠️*
