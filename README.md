# 📊 E-Commerce Customer Behaviour & Hypothesis Testing Analysis

This project analyzes 5,000 e-commerce orders from ShopSmart India to understand customer behaviour, spending patterns, and the impact of product and operational changes on business performance.

Using statistical hypothesis testing and A/B testing, this project demonstrates how data-driven decisions can improve conversion rates, customer targeting, and operational efficiency.

> **📌 Portfolio Note:** This project uses a simulated e-commerce dataset created for portfolio and analytical demonstration purposes. The business questions, statistical analysis, findings, and recommendations demonstrate the analytical approach and are not based on confidential or proprietary client data.

---

## 🎯 Project Objective

The goal of this project is to apply statistical analysis and hypothesis testing to answer real-world business questions such as:

- Are we delivering faster than the industry standard?
- Do certain customer segments spend more?
- Do different cities generate different order values?
- Does device type influence conversion rates?
- Did the new checkout button improve conversions?

---

## 🧠 Statistical Techniques Used

This project applies several statistical methods commonly used in data analytics and experimentation.

| Test | Business Question | Confidence Interval |
|---|---|---|
| **One-Sample T-Test** | Is average delivery time different from the industry benchmark? | 95% CI for population mean |
| **Two-Sample T-Test (Welch)** | Do female customers spend more than male customers? | 95% CI for difference in means |
| **ANOVA** | Are order values different across cities? | Post-hoc Tukey HSD |
| **Chi-Square Test** | Does device type affect conversion rate? | — |
| **Z-Test (Two-Proportion)** | Is Mobile conversion different from Desktop conversion? | 95% CI for difference in proportions |
| **Z-Test (A/B Test)** | Did the new checkout button increase conversions? | — |

---

## 📊 Confidence Interval Analysis

Confidence intervals were calculated alongside hypothesis tests to provide an estimated range for population parameters and differences between groups.

### One-Sample T-Test

A 95% confidence interval was calculated for the population mean delivery time.

**Result:**

> **95% CI: 4.25 – 4.34 days**

This indicates that the population mean delivery time is estimated to lie between approximately 4.25 and 4.34 days.

---

### Two-Sample Welch T-Test

A 95% confidence interval was calculated for the difference in average order value between male and female customers.

The difference was calculated as:

> **Male Average Order Value − Female Average Order Value**

**Result:**

> **95% CI: −₹366.60 to −₹284.75**

Since the interval does not include 0, there is statistically significant evidence of a difference in average order value between the two groups.

The negative interval indicates that female customers have a higher average order value than male customers.

---

### Two-Proportion Z-Test

A 95% confidence interval was calculated for the difference in conversion rates between Mobile and Desktop users.

The difference was calculated as:

> **Mobile Conversion Rate − Desktop Conversion Rate**

**Result:**

> **95% CI: −5.36 to −1.37 percentage points**

Since the interval does not include 0, there is statistically significant evidence of a difference in conversion rates between Mobile and Desktop users.

The negative interval indicates that Mobile users have a lower conversion rate than Desktop users.

---

## 📈 Key Insights

### 🚚 Faster Delivery Performance

Average delivery time is **4.29 days**, which is significantly faster than the 5-day industry benchmark.

📌 **Business Impact:**

This could potentially be used as a competitive advantage in marketing campaigns.

---

### 👩 High-Value Female Customer Segment

Female customers have a higher average order value compared to male customers.

📌 **Business Impact:**

Targeted promotions for female shoppers could potentially increase revenue.

---

### 🏙 City-Level Spending Differences

ANOVA analysis shows that order values differ significantly across cities, with **Bengaluru showing the highest spending levels**.

Post-hoc Tukey HSD analysis was used to identify differences between individual city pairs.

📌 **Business Impact:**

Marketing budgets can be optimized by focusing on high-value cities.

---

### 📱 Mobile Conversion Opportunity

Mobile devices generate the highest traffic but the lowest conversion rate.

A two-proportion Z-test comparing Mobile and Desktop users also showed a statistically significant difference in conversion rates.

📌 **Business Impact:**

Improving the mobile checkout experience could potentially increase sales.

---

### 🧪 Successful A/B Test

The new orange checkout button increased conversion rate from:

**8.9% → 12.0%**

The difference was statistically significant based on a two-proportion Z-test.

📌 **Business Impact:**

The results support rolling out the new design more broadly, subject to validation with real production data.

---

## 💼 Business Recommendations

Based on the analysis:

- Promote fast delivery as a competitive advantage
- Create targeted marketing campaigns for female customers
- Focus marketing investment on high-spending cities
- Improve the mobile checkout experience
- Consider implementing the orange checkout button more broadly after validating the result with real production data

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains **5,000 simulated e-commerce transactions** including:

- Customer demographics
- Order value
- Device type
- Traffic source
- Delivery time
- Conversion behaviour
- Payment method

> **⚠️ Data Disclaimer:** The dataset is simulated and was created for portfolio demonstration and statistical analysis practice. It does not represent real ShopSmart India customer data or confidential business information. Therefore, the findings and recommendations should be considered illustrative rather than actual business results.

---

## 🚀 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- A/B Testing
- Statistical Analysis
- Confidence Interval Analysis
- Data Visualization
- Business Insight Generation
- Data Storytelling
- Python for Data Analysis

---

## 📄 Reports

PDF versions of the analysis are included for easier viewing without running the Jupyter Notebook.

---

## 👨‍💻 Author

**Ratnajit Chakraborty**

📧 Email: rajhere1997@gmail.com
**Linkedin** https://www.linkedin.com/in/ratnajit-chakraborty-076ab520a

🔗 LinkedIn: https://www.linkedin.com/in/ratnajit-chakraborty-076ab520a

💻 GitHub: https://github.com/rajhere097
