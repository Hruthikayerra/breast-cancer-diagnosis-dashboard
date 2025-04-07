# breast-cancer-diagnosis-dashboard
EDA and dashboard on breast cancer dataset using Tableau

# 🧠 Breast Cancer Diagnosis Analysis & Dashboard

This project analyzes the **Breast Cancer Wisconsin (Diagnostic)** dataset to identify key differences between **benign** and **malignant** tumors using statistical analysis, visualizations, and a Tableau dashboard.

---

## 🎯 Objectives

- Understand and clean the dataset
- Perform exploratory data analysis (EDA)
- Visualize important patterns in tumor features
- Build an interactive Tableau dashboard
- Summarize insights for early cancer detection

---

## 📁 Repository Structure

```
breast-cancer-diagnosis-dashboard/
│
├── dashboard_screenshots/                 # Images of dashboard and plots
├── data/                                  # Dataset files (CSV format)
├── Breast_Cancer_Wisconsin_Updated.ipynb  # EDA in Jupyter Notebook
├── Breast Cancer Wisconsin.docx           # Summary report for submission
├── Breast Cancer Wisconsin.pdf           # Optional PDF export
└── README.md                              # Project overview (this file)
```

---

## 📊 Tools Used

- **Python** (Pandas, Seaborn, Matplotlib) for data analysis
- **Tableau** for dashboard creation
- **Jupyter Notebook** for exploration and cleaning
- **Word** for formal reporting

---

## 🔍 Key Insights

- **Tumor size and border irregularity** are strong indicators of malignancy.
- **Malignant tumors** have higher radius, area, and concavity.
- Features like **radius_mean, area_mean, and concavity_mean** show clear separation.
- A **correlation heatmap** shows that many features are strongly related, helping with feature selection.

---

## 📊 Sample Visualizations

Visuals used in the Tableau dashboard:

- Diagnosis distribution pie chart
- Histogram of tumor radius
- Boxplot of concavity_mean
- Bar chart of texture and smoothness
- Correlation heatmap

---

## ✅ How to Use

1. Open the `Breast_Cancer_Wisconsin_Updated.ipynb` notebook to run the analysis.
2. Use `correlation_data.csv` to build a heatmap in Tableau.
3. View the Tableau dashboard screenshots in `dashboard_screenshots/`.
4. Read the summary in `Final_Report.docx`.

---

## 📌 Credits

Dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data  
Dashboard and analysis by **Hruthika Yerra**
