# Bank Customer Churn Analysis

## Project Overview
Customer retention is a critical challenge in the banking industry. This project analyzes bank customer data to identify key factors that influence customer churn and provides actionable insights to help reduce churn and improve customer retention strategies.

The analysis uses descriptive statistics, exploratory data analysis (EDA), data visualization, and statistical hypothesis testing to understand customer behavior and churn patterns.

---

## Objectives
- Identify key drivers of customer churn
- Analyze churn trends across demographics and regions
- Evaluate the impact of customer behavior, product usage, and engagement
- Provide data-driven recommendations to improve customer retention

---

## Dataset Information
- Total Records: 10,000 customers
- Target Variable: `Exited`  
  - 1 = Customer Churned  
  - 0 = Customer Retained

### Key Features
- Demographics: Age, Gender, Geography
- Financial: CreditScore, Balance, EstimatedSalary
- Behavioral: NumOfProducts, IsActiveMember, HasCrCard
- Customer Feedback: Complain, Satisfaction Score
- Card Details: Card Type, Point Earned

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (Chi-square test, T-test)
- Jupyter Notebook

---

## Analysis Performed
- Data cleaning and validation
- Descriptive statistics (mean, median, mode)
- Distribution analysis using histograms and boxplots
- Correlation analysis and heatmaps
- Customer segmentation by age, gender, and geography
- Hypothesis testing to validate churn drivers

---

## Key Insights
- Customers aged 40–50 are more likely to churn
- Female customers show a slightly higher churn rate than male customers
- Customers from Germany have significantly higher churn compared to France and Spain
- Customers with only 1–2 products are more likely to churn
- Inactive members have a much higher churn rate
- Customers who raised complaints are highly likely to churn
- Card type, salary, and reward points have no significant impact on churn

---

## Business Recommendations
- Implement targeted retention strategies for customers aged 40–50
- Focus on high-risk regions like Germany with personalized engagement plans
- Encourage customers to adopt multiple banking products
- Increase customer engagement to improve active membership
- Strengthen complaint resolution processes to reduce churn

---

## Project Structure

├── data/ # Dataset files
├── notebook/ # Jupyter Notebook with analysis
├── visuals/ # Charts and plots
└── README.md # Project documentation


---

## Conclusion
This project demonstrates how data analysis and statistical testing can be used to identify churn drivers and support data-driven decision-making in the banking sector.





