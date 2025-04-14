# 📦 Bootstrap Analysis of Highest Paying Job in San Francisco (2019)

**Author:** Jullian Alcantara  
**Tools Used:** Python, `pandas`, `numpy`, `matplotlib`

---

## 📌 Project Overview

This project applies **bootstrap resampling techniques** to estimate confidence intervals for the highest-paying job in **San Francisco's 2019 city employee salary dataset**. The goal was to explore salary distributions and use resampling methods to quantify uncertainty in salary estimates.

---

## 🎯 Objective

- Identify the highest-paying job title in San Francisco city government (2019)
- Apply **bootstrap resampling** to estimate confidence intervals for salary averages
- Visualize the distribution of bootstrap sample means and interpret salary variability  

---

## 📈 Dataset

- **San Francisco City Employee Salary Data (2019)**  
- Source: [DataSF.org](https://data.sfgov.org/)

---

## ⚙️ Methodology

1. **Data Cleaning**
   - Loaded and cleaned the salary dataset using **Pandas**
   - Filtered relevant salary columns and identified the top-paying job title

2. **Bootstrap Resampling**
   - Applied **NumPy** random resampling to generate thousands of bootstrap samples
   - Calculated the mean salary for each sample
   - Computed a 95% confidence interval for the mean salary of the highest-paid role  

3. **Visualization**
   - Used **Matplotlib** to plot histograms of bootstrap sample means  
   - Visualized the confidence interval range for easy interpretation

---

## 📊 Key Results

- The **Chief Investment Officer** role was identified as the highest-paying position in 2019.
- Bootstrap analysis provided a 95% confidence interval for this role’s average compensation.
- Demonstrated how bootstrap resampling can quantify uncertainty in salary data analysis.


## 📚 Learnings

Gained hands-on experience using bootstrap resampling for statistical inference
Applied NumPy and Matplotlib for statistical visualization and analysis
Reinforced understanding of confidence intervals in real-world salary datasets

---

## 📂 How to Run

```bash
# Install dependencies
pip install pandas numpy matplotlib

# Run the notebook
Open 'Bootstrap_SF_Salary_Analysis.ipynb' in Jupyter or VS Code



