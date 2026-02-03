<div align="center">
  <h1>🛒 Walmart Black Friday Spending Analysis</h1>
  <h2>Confidence Intervals & Central Limit Theorem</h2>
  <p><strong>Statistical deep-dive into customer purchase behavior by gender, age group, and marital status</strong></p>

  <!-- Clean Socialify banner – choose ONE style (I recommend the first for dark/light auto theme) -->
 

  <!-- Alternative light version if you prefer -->

  <img src="https://socialify.git.ci/ravindrasudha/Walmart-Confidence-Interval-and-CLT/image?custom_language=Python&description=1&forks=1&issues=1&language=1&logo=https%3A%2F%2Fencrypted-tbn0.gstatic.com%2Fimages%3Fq%3Dtbn%3AANd9GcTn7vLAq1blnq8v5qDn7ObGnM3oIgAyl0Za0Q%26s&name=1&owner=1&pulls=1&stargazers=1&theme=Light" alt="Socialify banner - Light theme" width="720"/>
  

  <br/>

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Seaborn-FF6384?style=for-the-badge&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Statistics-4CAF50?style=for-the-badge&logo=google-analytics&logoColor=white" alt="Statistics"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Last%20Updated-Jul%202025-success?style=for-the-badge&logo=git&logoColor=white" alt="Last Updated"/>

</div>

<br/>
## 🎯 Project Overview

**Problem Statement**  
Walmart wants to understand **who spends more on Black Friday** — men or women? With an estimated 50 million customers, the company needs reliable insights into spending patterns by gender, age, and marital status to optimize marketing campaigns, inventory planning, and promotional strategies.

**Business Goal**  
Use statistical tools (**Confidence Intervals** and **Central Limit Theorem**) to make data-driven decisions about customer segmentation, targeted promotions, and resource allocation during high-traffic sales events like Black Friday.

**Dataset**  
- Source: Black Friday transactional data (commonly from Kaggle / public retail datasets)  
- Rows: ~550,000 transactions  
- Key Columns: User_ID, Product_ID, Gender, Age (binned), Occupation, City_Category, StayInCurrentCityYears, Marital_Status, ProductCategory, Purchase (amount in ₹)

**Key Statistical Techniques Applied**  
- Descriptive statistics & visualization  
- Central Limit Theorem (CLT) for sample mean distribution  
- 95% Confidence Intervals for population mean spending  
- Comparison across segments (gender, age, marital status)

## 📊 Key Business Insights & Recommendations

1. **Men spend significantly more than women on average** during Black Friday → gender is a strong segmentation variable.  
   → **Action**: Prioritize male-targeted promotions for high-value categories (electronics, gadgets).

2. **Age group 26–50 years is the highest spending segment** → core revenue driver.  
   → **Action**: Run personalized loyalty programs, exclusive deals, and app notifications for this group.

3. **Marital status shows no significant difference in spending** → ineffective segmentation criterion.  
   → **Action**: Stop using marital status for campaign targeting; redirect budget to age & gender.

4. **Lower spending in 0–17 and 51+ age groups** → opportunity for value-driven offers.  
   → **Action**: Introduce budget combos, student/senior discounts, and bundle deals.

5. **High-value outliers detected** → potential bulk/premium buyers.  
   → **Action**: Analyze outliers separately for VIP/loyalty program opportunities.

**Statistical Confidence**: 95% CIs confirm that differences (especially gender) are meaningful and not due to sampling variation.

## 🖼️ Project Screenshots

<!-- Replace with your actual screenshot URLs from repo (upload to /screenshots folder) -->
<div align="center">
  <img src="https://github.com/ravindrasudha/Walmart-Confidence-Interval-and-CLT/raw/main/screenshots/age_spending_distribution.png" alt="Age vs Spending Distribution" width="45%"/>
  <img src="https://github.com/ravindrasudha/Walmart-Confidence-Interval-and-CLT/raw/main/screenshots/gender_confidence_interval.png" alt="Gender Confidence Intervals" width="45%"/>
  <br/><br/>
  <img src="https://github.com/ravindrasudha/Walmart-Confidence-Interval-and-CLT/raw/main/screenshots/marital_status_comparison.png" alt="Marital Status Analysis" width="45%"/>
  <img src="https://github.com/ravindrasudha/Walmart-Confidence-Interval-and-CLT/raw/main/screenshots/purchase_outliers.png" alt="Purchase Amount Outliers" width="45%"/>
</div>

## 🚀 Features

- Clean data exploration & preprocessing  
- Visual storytelling with distribution plots, boxplots & bar charts  
- Application of CLT to justify normality of sample means  
- Calculation & interpretation of 95% Confidence Intervals for key segments  
- Clear business recommendations backed by statistical evidence  
- Reproducible Jupyter Notebook with detailed comments

## 🛠️ Installation & Usage

1. Clone the repository  
   ```bash
   git clone https://github.com/ravindrasudha/Walmart-Confidence-Interval-and-CLT.git
   cd Walmart-Confidence-Interval-and-CLT
