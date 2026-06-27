# 🩺 NFHS-5 State-Level Health Indicator Analysis

A comprehensive data analysis and visualization project based on the **National Family Health Survey (NFHS-5)** dataset. This project explores major health indicators across Indian states using **Python**, **Pandas**, **Matplotlib**, **Seaborn**, and **Folium**, providing statistical insights and interactive geographic visualizations.

---

## 📌 Project Overview

The National Family Health Survey (NFHS-5) provides detailed information about the health and nutrition status of India's population. This project analyzes selected state-level health indicators and presents them through exploratory data analysis (EDA) and interactive maps.

The project focuses on identifying health trends, comparing states, and visualizing the distribution of obesity, anaemia, hypertension, and blood sugar levels.

---

## 🎯 Objectives

- Load and clean the NFHS-5 dataset.
- Analyze important health indicators across Indian states.
- Compare male and female obesity levels.
- Identify states with high hypertension prevalence.
- Explore relationships between obesity and anaemia.
- Visualize state-wise health statistics using interactive maps.
- Build an end-to-end data analysis workflow suitable for beginners.

---

## 📊 Dataset

**Source:** Kaggle

Dataset Used:

- National Family Health Survey (NFHS-5) 2019–2020
- State-wise Health Indicators

The dataset contains health statistics such as:

- Male Obesity (%)
- Female Obesity (%)
- Child Anaemia (%)
- Women Anaemia (%)
- Male Hypertension (%)
- Female Hypertension (%)
- Male High Blood Sugar (%)
- Female High Blood Sugar (%)

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Google Colab | Development Environment |
| Pandas | Data Cleaning & Analysis |
| NumPy | Numerical Computations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Folium | Interactive Maps |
| GeoJSON | Geographic Boundaries |

---

## 📂 Project Structure

```
NFHS5-Health-Analysis/
│
├── NFHS5_Kaggle_Analysis.ipynb
├── archive.zip
├── README.md
└── outputs/
    ├── charts/
    └── maps/
```

---

## 🚀 Project Workflow

### Phase 1 – Data Preparation

- Upload Kaggle dataset
- Extract ZIP file
- Load CSV into Pandas
- Clean missing values
- Convert numeric columns
- Create additional analysis columns

---

### Phase 2 – Exploratory Data Analysis

Performed analyses include:

- Distribution of obesity rates
- Top states with highest hypertension
- Female vs Male obesity comparison
- Scatter plot of obesity vs anaemia
- Correlation analysis
- Statistical summaries

---

### Phase 3 – Geographic Visualization

Interactive maps built using Folium:

- Choropleth Map
- State-wise Circle Markers
- Health summary popups
- Color-coded health indicators

---

## 📈 Visualizations

The notebook generates multiple visualizations including:

- Grouped Bar Charts
- Scatter Plots
- Correlation Heatmaps
- Choropleth Maps
- Interactive State Markers

---

## 📌 Key Analysis

The project examines:

- State-wise obesity distribution
- Hypertension prevalence
- Anaemia among women and children
- Gender obesity gap
- Geographic variation in health indicators
- Relationships between different health metrics

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/NFHS5-Health-Analysis.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn folium
```

### Open the notebook

```bash
jupyter notebook NFHS5_Kaggle_Analysis.ipynb
```

or upload the notebook directly into **Google Colab**.

---

## 📦 Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import folium
```

---

## 📊 Sample Outputs

The project produces:

- Cleaned dataset
- Summary statistics
- Comparative visualizations
- Interactive state maps
- Health indicator insights

---

## 💡 Learning Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Geographic Data Visualization
- Interactive Mapping
- Feature Engineering
- Statistical Analysis
- Python for Data Science

---

## 🔮 Future Enhancements

- District-level analysis
- Time-series comparison with future NFHS surveys
- Machine Learning for health prediction
- Dashboard using Streamlit
- Power BI integration
- Automated report generation

---

## 👨‍💻 Author

**N. Rithish Barath**

Computer Science Engineering Student

Passionate about:

- Data Science
- Artificial Intelligence
- Machine Learning
- Data Visualization
- Python Development

---

## 📜 License

This project is intended for educational and academic purposes.

---

## ⭐ Acknowledgements

- National Family Health Survey (NFHS-5)
- Ministry of Health and Family Welfare, Government of India
- Kaggle
- Pandas
- Matplotlib
- Seaborn
- Folium

---

> **"Transforming public health data into meaningful insights through analytics and visualization."**
