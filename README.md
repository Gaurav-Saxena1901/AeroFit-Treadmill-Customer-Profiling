# AeroFit Treadmill Customer Profiling & Case Study

## 📌 Project Overview
This project performs **Descriptive Analytics** on AeroFit's customer database to uncover the demographic and behavioral characteristics of users buying different treadmill models (`KP281`, `KP481`, and `KP781`). The ultimate goal is to optimize product recommendations for new customers and sharpen marketing segmentation.

## 📊 Key Insights & Analytics Summary

### 1. Customer Profiles
* **KP281 (Entry Level):** Accounts for **44.44%** of overall sales. It is a highly accessible model popular among both genders, particularly working professionals and young adults with low-to-medium income.
* **KP481 (Mid-Tier):** Accounts for **33.33%** of overall sales. Purchased evenly across mid-income demographics, leaning slightly towards customers with moderate fitness levels.
* **KP781 (Premium):** Accounts for **22.22%** of overall sales. It has a stark entry barrier; bought almost exclusively by **High-Income individuals** (primarily Male, 31.73% conditional probability vs. 9.21% Female) who rank themselves as elite fitness enthusiasts (Level 5).

### 2. Probability Framework (Key Highlights)
* **Marginal Probability of Purchase:** `KP281`: 44.44% | `KP481`: 33.33% | `KP781`: 22.22%
* **Conditional Probability (Gender given Product):** 72.5% of all `KP781` buyers exhibit a maximum fitness level of 5, making intense exercise habits the highest statistical predictor for premium model conversion.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Language:** Python
* **Libraries:** Pandas, NumPy, Seaborn, Matplotlib
* **Methodologies:** Univariate & Bivariate Exploratory Data Analysis (EDA), Outlier Detection, Two-Way Contingency Tables, Joint & Conditional Probability Calculation.

---

## 🚀 How to Explore the Analysis
1. Open the file `Business_case_Study_Aerofit.ipynb` directly in GitHub to view the executable code cells, statistical summaries, and visual distribution plots.
2. The analysis covers Data cleaning, Data visualization (Histograms, Boxplots, Heatmaps), and Probability metrics.
