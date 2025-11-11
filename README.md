# 🌾 Global Food & Agriculture Dashboard — FAO Dataset (Power BI)

## 📊 Overview
This project presents an **interactive Power BI dashboard** built from the **FAO Global Food & Agriculture Statistics** dataset.  
The dashboard provides insights into global trends in agriculture, forestry, land use, and production across countries from **1961–2007**.  

The raw data was obtained from [Kaggle - Global Food & Agriculture Statistics](https://www.kaggle.com/datasets/unitednations/global-food-agriculture-statistics) and processed using Python before being visualized in Power BI.

---

## 🧠 Objectives
- Clean, merge, and preprocess multiple FAO data files  
- Perform **Exploratory Data Analysis (EDA)** to identify important metrics  
- Build **interactive dashboards** to explore trends by:
  - Country  
  - Year  
  - Agricultural category (crops, livestock, land, forests, etc.)  
  - Economic elements (production, import/export, etc.)  
- Support **data-driven decisions** through visual storytelling  

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy)** | Data cleaning, preprocessing, merging |
| **Matplotlib / Plotly** | Exploratory Data Analysis (EDA) |
| **Power BI Desktop** | Dashboard visualization |
| **KaggleHub** | Dataset import |
| **Parquet/CSV** | Optimized data storage and loading |

---

## 📂 Folder Structure
project_root/
│
├── cleaned_data/
│ ├── country_year_summary.csv
│ ├── element_summary.csv
│ ├── global_yearly.csv
│ ├── total_by_country.csv
│ ├── year_category_summary.csv
│ └── fao_all_cleaned.parquet
│
├── notebooks/
│ └── preprocessing_and_eda.ipynb
│
├── dashboard/
│ └── Code_canvas_dashboard.pbix
│
└── README.md




