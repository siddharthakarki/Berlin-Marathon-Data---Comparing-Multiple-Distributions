
# 🏃‍♀️ **Berlin Marathon Analysis: Comparing Finish Times Across Age Groups**

## 📌 Project Overview  
This project analyzes the **Berlin Marathon** data, focusing on **women runners** across different age groups to investigate how **age influences marathon performance**. The study compares **finish times** across six age categories and applies statistical tests to identify significant differences.

## 📊 Dataset Information  
- **Source**: [Berlin Marathon Data on Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/berlin-marathons-data)  
- **Restricted to**: Female participants  
- **Variables**:  
  - **`agegroup`**: Categorized into **30, 35, 40, 45, 50, 55 years**  
  - **`time`**: Runner’s **finish time in seconds**  

---

## 🚀 **Key Objectives**  

✔️ **Descriptive Statistics**: Summarize **finish time distributions** across age groups.  
✔️ **Global Comparison**: Conduct **one-way ANOVA** to test for significant differences.  
✔️ **Pairwise Comparisons**: Apply **two-sample tests** to compare age groups.  
✔️ **Multiple Testing Corrections**: Use **Bonferroni and Tukey’s HSD** to adjust p-values.  
✔️ **Assumption Checking**: Verify **normality** and **variance homogeneity** before statistical tests.  

---

## 🔍 **Methodology & Statistical Approach**  

### ✅ 1. Descriptive Analysis  
- Frequency distribution of age groups  
- Summary statistics of finish times (mean, median, variance)  
- Visualizations: **bar charts, histograms, boxplots**  

### ✅ 2. Global Hypothesis Testing  
- **Null Hypothesis (H₀)**: No significant difference in finish times between age groups.  
- **Alternative Hypothesis (H₁)**: At least one group differs significantly.  
- **Test Used**: **One-way ANOVA**  
- **Assumptions Checked**:  
  - **Normality** (Shapiro-Wilk test, QQ plots)  
  - **Homogeneity of Variances** (Levene’s test)  

### ✅ 3. Pairwise Comparisons  
- **Two-sample t-tests** for all age group pairs  
- **Multiple testing corrections**:  
  - **Bonferroni correction** (more conservative)  
  - **Tukey’s Honest Significant Difference (HSD)** (balanced approach)  
- **Tukey’s Confidence Intervals** for mean differences  

### ✅ 4. Comparison of Correction Methods  
- Analyze the impact of **Bonferroni vs. Tukey’s HSD** on significance levels.  
- Compare **raw p-values** vs. **adjusted p-values**.  

---

## 📈 **Key Findings**  

### 📍 Descriptive Insights  
✔️ **Age group 30** had the highest participation, while **55** had the lowest.  
✔️ Finish times followed a **right-skewed distribution**, with increasing variability in older groups.  

### 📍 Statistical Testing Results  
✔️ **ANOVA** found significant differences between age groups (**F = 5.463, p = 5.215 × 10⁻⁵**).  
✔️ **Pairwise t-tests** detected significant differences between **30, 35 vs. 50, 55**.  
✔️ **Bonferroni correction** confirmed fewer significant differences due to conservativeness.  
✔️ **Tukey’s HSD** provided balanced results and confidence intervals, making it the **preferred method**.  

### 📍 Performance Trends  
✔️ **Older runners tend to have longer finish times**, indicating **age-related endurance decline**.  
✔️ Increased **variability** in finish times with age suggests **greater performance dispersion**.  

---

## 🛠 **Technologies Used**  

📊 **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`  
📈 **Jupyter Notebook** for interactive analysis  
📝 **Markdown & LaTeX** for documentation  

---

## 📢 **Conclusion & Future Work**  

- 🔹 **Age significantly affects marathon performance**, with **older groups showing slower finish times**.  
- 🔹 **Tukey’s HSD** is a **more balanced** approach for multiple comparisons than Bonferroni.  
- 🔹 Future studies could incorporate factors like **training experience, weather conditions, and race strategy** for deeper insights.  

---

## 💡 **Contributors**  

👤 **Siddhartha Karki**  
📧 Sidkarki999@gmail.com 
🌐 www.linkedin.com/in/siddhartha-karki
📌 **Support & Contributions**  
⭐ **If you found this project useful, give it a star!**  
💬 **Feedback and contributions are welcome!** 🎯  
