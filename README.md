<h1 align="center">🏠 ANOVA Analysis of Host Response Time vs Log Price</h1>
<p align="center"><em>Descriptive Statistics • ANOVA • Multiple Comparison Corrections • Airbnb Dataset</em></p>

---

## 🔹 Project Summary

This project investigates the relationship between **host response time categories** and **log prices** of accommodations using data from Inside Airbnb (affiliated with Airbnb). The dataset contains **232 observations**, with response times categorized as:

* Within a few hours
* Within an hour
* Within a day

A **one-way ANOVA** revealed a significant difference in mean log prices among response time categories (p < 0.05). **Pairwise t-tests** indicated specific differences, particularly between 'within a few hours' and 'within an hour' (p = 0.0064).

To address **Type I error** in multiple testing, both **Bonferroni** and **Tukey’s HSD** corrections were applied:

* **Bonferroni:** No significant differences after adjustment (conservative approach)
* **Tukey HSD:** Significant difference detected between 'within a few hours' and 'within an hour' (p = 0.0192)

The study highlights nuanced price variations based on host response time and demonstrates the importance of multiple comparison corrections.

---

## 🎯 Project Objective

* Conduct a **comprehensive analysis** of log_price and host_response_time.
* Perform **descriptive statistics** and visualize frequency distributions.
* Validate assumptions with **Levene’s test** (variance) and **Shapiro-Wilk test** (normality).
* Conduct **one-way ANOVA** to identify overall differences in log_price across response time groups.
* Perform **pairwise t-tests** and apply **Bonferroni** and **Tukey’s HSD corrections** for multiple comparisons.
* Provide a nuanced understanding of log_price variations relative to host response times.

---

## 🛠️ Tools & Techniques

* **Language:** R
* **Libraries:** dplyr, ggplot2, stats
* **Statistical Tests:** Levene’s test, Shapiro-Wilk test, One-way ANOVA, Pairwise t-tests, Bonferroni correction, Tukey’s HSD

---

## 📊 Key Findings

* Significant mean differences in log prices among response time categories (ANOVA, p < 0.05)
* Bonferroni correction is conservative; no post-adjustment significance
* Tukey HSD detected significant difference between 'within a few hours' and 'within an hour' (p = 0.0192)
* Non-adjusted tests suggest caution due to Type I error (p = 0.064)
* Host response time influences log prices, but additional factors may provide deeper insights

---

## 💡 Reflection

* The project emphasizes **statistical rigor** in multiple comparisons.
* Demonstrates importance of **correction methods** in hypothesis testing.
* Future work should explore variables like **distance to city center** and **amenities** to fully understand pricing dynamics.

---

<p align="center"><em>Careful statistical analysis reveals meaningful insights into host responsiveness and pricing patterns.</em></p>
