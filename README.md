# 📊 Facebook Ads Campaign Performance Analysis

## 🔍 Overview

This project analyzes the performance of Facebook advertising campaigns using real marketing data.

The goal is to evaluate:

* Advertising efficiency
* Campaign performance
* Return on marketing investment (ROMI)
* Relationships between key metrics

The analysis is performed using **Python, Pandas, Matplotlib, and Seaborn**.

---

## 📁 Dataset

* Source: Facebook Ads dataset (`facebook_ads_data.csv`)
* Granularity: Daily campaign-level data
* Key features:

  * `ad_date`
  * `campaign_name`
  * `total_spend`
  * `total_value`
  * other performance metrics

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Key Business Questions

This analysis answers the following questions:

1. How did advertising spend change over time?
2. How effective were campaigns in terms of ROMI?
3. Which campaigns performed best?
4. How stable is campaign performance?
5. What is the distribution of ROMI?
6. Which metrics are most correlated with revenue (`total_value`)?
7. What is the relationship between ad spend and generated value?

---

## 📊 Analysis & Visualizations

### 1. Daily Performance (2021)

* Daily total ad spend
* Daily ROMI
* Rolling averages (trend smoothing)

📌 Insights:

* Allows identification of **trends, seasonality, and spikes**
* Rolling averages help reveal **underlying patterns**

📉 Charts:

* Line chart: Daily ad spend
* Line chart: Daily ROMI
* Rolling mean (7-day average)

---

### 2. Campaign-Level Analysis

* Total spend by campaign
* Total ROMI by campaign

📌 Insights:

* Identifies **high-performing vs underperforming campaigns**
* Helps optimize budget allocation

📉 Charts:

* Bar chart: Spend by campaign
* Bar chart: ROMI by campaign

---

### 3. ROMI Variability (Box Plot)

* Distribution of daily ROMI per campaign

📌 Insights:

* Shows **stability vs volatility**
* Detects **outliers and risky campaigns**

📉 Chart:

* Box plot: ROMI by campaign

---

### 4. ROMI Distribution

* Histogram of ROMI values

📌 Insights:

* Reveals whether returns are:

  * Normally distributed
  * Skewed
  * Contain extreme values

📉 Chart:

* Histogram of ROMI

---

### 5. Correlation Analysis

* Heatmap of correlations between all numeric variables

📌 Insights:

* Identifies **strong relationships between metrics**
* Helps understand **drivers of revenue (`total_value`)**

Key findings:

* Strong positive correlation between:

  * `total_spend` and `total_value`
* Weak or negative correlations highlight less impactful metrics

📉 Chart:

* Correlation heatmap

---

### 6. Spend vs Value Relationship

* Scatter plot with linear regression

📌 Insights:

* Visualizes the relationship between:

  * Advertising spend (`total_spend`)
  * Generated value (`total_value`)
* Helps evaluate **efficiency of scaling ad budgets**

📉 Chart:

* Scatter plot with regression line (Seaborn `lmplot`)

---

## 📌 Key Takeaways

* Advertising performance varies significantly across campaigns
* Some campaigns deliver **high ROMI but with high volatility**
* There is a **strong relationship between spend and revenue**, but not perfectly linear
* Increasing spend does not always guarantee proportional returns
* Data-driven optimization is essential for improving marketing efficiency


