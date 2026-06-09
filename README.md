# Walmart Black Friday Sales Analysis

## Project Overview

This project analyzes customer purchase behavior from Walmart’s Black Friday sales dataset using Exploratory Data Analysis (EDA) and confidence interval analysis.

The main goal is to understand how purchase amount varies across gender and how other factors such as age, marital status, city category, occupation, current city stay, and product category influence spending patterns.

---

## Business Problem

Walmart wants to analyze customer purchase behavior, especially purchase amount, across different customer segments.

The key question is:

**Do women spend more on Black Friday than men?**

To answer this, the analysis also explores whether spending patterns differ by:

- Gender
- Age group
- Marital status
- City category
- Occupation
- Stay in current city years
- Product category

---

## Dataset

The dataset contains transactional purchase data from Walmart stores during Black Friday.

### Features Used

- `User_ID` – Unique customer ID
- `Product_ID` – Product ID
- `Gender` – Customer gender
- `Age` – Age group
- `Occupation` – Occupation code
- `City_Category` – City category (A, B, C)
- `StayInCurrentCityYears` – Years spent in current city
- `Marital_Status` – Marital status
- `ProductCategory` – Product category
- `Purchase` – Purchase amount

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

### 1. Exploratory Data Analysis
- Checked dataset structure
- Studied numerical and categorical distributions
- Explored purchase patterns

### 2. Univariate Analysis
- Purchase amount distribution
- Gender distribution
- Age distribution
- Occupation patterns
- City category analysis
- Marital status analysis
- Product category analysis

### 3. Bivariate Analysis
- Purchase amount by gender
- Purchase amount by age
- Purchase amount by marital status
- Purchase amount by city category
- Purchase amount by occupation
- Purchase amount by current city stay
- Purchase amount by product category

### 4. Multivariate Analysis
- Combined analysis of gender with:
  - City category
  - Marital status
  - Occupation
  - Stay in current city years
  - Product category

### 5. Confidence Interval Analysis
- Male vs Female purchase comparison
- Married vs Unmarried comparison
- Age group comparison
- Effect of sample size and confidence level using CLT

---

## Key Findings

### Gender Analysis
- Male customers spend more than female customers on average.
- Male customers also contribute more to total purchase amount.
- The 95% confidence intervals for male and female purchase amounts do not overlap, showing a statistically significant difference.

### City Category Analysis
- City B contributes the highest total purchase amount.
- City C shows the highest average purchase amount per transaction.

### Marital Status Analysis
- Married and unmarried customers have very similar average purchase amounts.
- Marital status does not appear to be a major driver of average spend.

### Occupation Analysis
- Certain occupations contribute more strongly to total sales.
- Male customers spend more across nearly all occupations.

### Stay in Current City Analysis
- Customers who have stayed 1–2 years in the current city contribute heavily to total purchases.
- Average purchase amounts remain fairly consistent across stay categories.

### Product Category Analysis
- Product categories 1, 5, and 8 generate the highest total purchases.
- Several product categories show higher average purchase values, indicating premium spending behavior.

### Age Group Analysis
- The `51–55` age group has the highest average purchase amount.
- The `0–17` age group has the lowest average purchase amount.
- Average spend generally increases with age.

### Confidence Interval Insights
- Male customers have a significantly higher average spend than female customers.
- Age group differences are visible, especially for the youngest and 51–55 segments.
- Larger sample sizes produce narrower confidence intervals.

---

## Business Recommendations

### 1. Target Male Customers Strategically
Since male customers show higher average and total spending, Walmart can design:
- Targeted promotions
- Product recommendations
- Category-specific offers for high-spend male segments

### 2. Focus on High-Value Age Groups
The `51–55` age group shows the highest average purchase amount.
This group can be targeted with:
- Premium product offers
- Loyalty benefits
- High-value bundles

### 3. Improve Female Customer Engagement
Although female customers spend less on average, Walmart can increase engagement through:
- Personalized promotions
- Better category recommendations
- Special Black Friday offers

### 4. Use City Category Insights
Since City B has the highest total spend and City C has the highest average spend:
- City B can be prioritized for scale
- City C can be targeted for premium offerings

### 5. Optimize Product Category Strategy
Product categories 1, 5, and 8 drive strong sales.
Walmart can:
- Increase inventory for top categories
- Bundle related products
- Create category-specific promotions

---

## Conclusion

This analysis shows that **women do not spend more than men on Black Friday** in this dataset.  
Male customers consistently show higher average and total purchase amounts across most segments.

The study also highlights that age, city category, and product category influence spending behavior, while marital status has a weaker effect on average purchase amount.

These insights can help Walmart improve:
- Customer segmentation
- Marketing strategy
- Product placement
- Promotion planning

---

## Repository Structure

```text
Walmart-Black-Friday-Analysis/
│
├── README.md
├── Walmart_case_study.ipynb
