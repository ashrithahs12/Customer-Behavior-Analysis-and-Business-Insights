# Customer-Behavior-Analysis-and-Business-Insights


## Project Overview

This project focuses on analyzing mall customer data using Python to understand customer behavior, identify spending patterns, and generate meaningful business insights.

The analysis uses statistical techniques and data visualization to study customer age, annual income, spending scores, and gender-based differences. It also applies hypothesis testing and confidence intervals to support data-driven business decisions.

## Objectives

- Understand and explore the Mall Customer Segmentation dataset.
- Perform descriptive statistical analysis.
- Visualize customer distributions using histograms and boxplots.
- Compare customer spending patterns based on gender.
- Analyze relationships between age, annual income, and spending scores.
- Perform hypothesis testing and calculate confidence intervals.
- Generate business insights and marketing recommendations.

## Dataset Description

The project uses the **Mall Customer Segmentation Dataset**, which contains customer information.

| Column | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands |
| Spending Score (1-100) | Customer spending score |

- Total records: 200 customers
- Total columns: 5

## Technologies Used

- Python
- Pandas – Data manipulation and analysis
- Matplotlib – Data visualization
- SciPy – Statistical analysis
- Google Colab

## Project Workflow

### 1. Data Understanding
- Loaded and explored the dataset.
- Checked dataset dimensions, data types, and missing values.
- Identified numerical and categorical features.

### 2. Descriptive Analysis
- Calculated mean, median, and standard deviation.
- Examined customer age, annual income, and spending score distributions.

### 3. Data Visualization
- Created histograms to understand data distributions.
- Used boxplots to identify potential outliers.

### 4. Group-Based Analysis
- Compared average spending scores and annual income between male and female customers.

### 5. Correlation Analysis
- Studied the relationship between annual income and spending score.
- Examined the relationship between age and spending score.

### 6. Inferential Statistics
- Performed an independent samples t-test to determine whether male and female customers have significantly different spending scores.
- Used a 5% significance level.

### 7. Confidence Interval
- Calculated a 95% confidence interval for the average customer spending score.

### 8. Business Insights
- Identified customer spending patterns.
- Suggested marketing strategies based on customer behavior.
- Provided recommendations for improving customer engagement.

## Key Findings

| Analysis | Result |
|---|---|
| Average Age | 38.85 |
| Average Annual Income | 60.56 |
| Average Spending Score | 50.20 |
| Female Average Spending Score | 51.53 |
| Male Average Spending Score | 48.51 |
| Income vs Spending Correlation | 0.01 |
| Age vs Spending Correlation | -0.327 |
| T-test P-value | 0.4137 |
| 95% Confidence Interval | (46.60, 53.80) |

## Important Insights

- Female customers have a slightly higher average spending score than male customers.
- Annual income has almost no linear relationship with spending score.
- Age shows a weak negative relationship with spending score.
- The t-test indicates that the difference in average spending scores between male and female customers is not statistically significant.
- Customer spending behavior can provide useful information for developing targeted marketing strategies.

## Business Recommendations

- Focus on customers with higher spending scores through loyalty programs and special offers.
- Develop personalized marketing campaigns based on customer preferences.
- Encourage younger customers to engage with promotional activities.
- Avoid depending only on annual income or gender when designing marketing strategies.
- Use customer behavior analysis to improve customer engagement and business decisions.


## Conclusion

This project demonstrates how Python and statistical techniques can be used to understand customer behavior and support business decision-making. Through data analysis, visualization, and hypothesis testing, meaningful insights were identified that can help businesses develop better customer-focused marketing strategies.


**Project Type:** Minor Project – Data Analysis

**Domain:** Data Science & Business Analytics

**Language:** Python
