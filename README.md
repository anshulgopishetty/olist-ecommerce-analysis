# Olist E-Commerce Sales Analysis

## Project Overview

This project explores the **Olist Brazilian E-Commerce dataset** to understand sales performance, customer purchasing behavior, product category performance, customer satisfaction, and delivery operations.

The goal of this project is to use exploratory data analysis (EDA) to identify meaningful business patterns and translate data into actionable business insights.

## Business Objectives

The analysis focuses on answering questions such as:

- Which product categories generate the most revenue?
- Which states contribute the most to overall sales?
- How do average order values differ across regions?
- What percentage of customers make repeat purchases?
- Do repeat customers generate more revenue than one-time customers?
- Which product categories receive better customer reviews?
- How frequently do delivery delays occur, and how do they vary across regions?
- Are there product categories with high revenue but relatively low customer satisfaction?
- How is revenue changing over time?
- What does customer purchasing behavior reveal about retention opportunities?

## Dataset

This project uses the Olist Brazilian E-Commerce Public Dataset, which contains information about orders, customers, products, sellers, payments, reviews, and deliveries.

The dataset is publicly available on Kaggle:

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The datasets were combined and analyzed to explore different aspects of the e-commerce business.

## Tools and Technologies

- **Python** – Data analysis
- **Pandas** – Data manipulation and aggregation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## Analysis Performed

### 1. Sales and Revenue Analysis
- Revenue by product category
- Product prices and freight costs
- Sales distribution across Brazilian states
- Average order value by state
- Revenue trends over time

### 2. Customer Analysis
- Customer purchase frequency
- One-time versus repeat customers
- Repeat purchase rate
- Revenue contribution from repeat customers
- Customer lifetime revenue
- Customer segmentation based on purchasing behavior

### 3. Product Category Analysis
- Number of items sold by category
- Average product prices
- Category-level revenue
- Customer review scores by category
- Categories with high revenue but relatively low review scores
- Repeat purchasing behavior across categories

### 4. Delivery and Order Analysis
- Late delivery percentage
- Average delivery delay
- Delivery performance across states
- Order cancellations and unavailable products
- Regional differences in delivery performance

### 5. Data Visualization
Visualizations were created to understand:
- Revenue trends
- Product price distributions
- Category-level revenue comparisons
- Relationships between numerical variables
- Correlations between selected variables

## Key Business Findings

The analysis revealed several important patterns:

1. **Revenue growth:** Revenue increased over the observed period, with a substantial increase from 2016 to 2017.

2. **Customer retention:** Most customers made only one purchase. The repeat customer rate was approximately **3.12%**, highlighting a potential customer retention challenge.

3. **Repeat customer value:** Repeat customers tended to generate more revenue per customer than one-time customers.

4. **Customer concentration:** A relatively small group of customers contributed a significant amount of revenue and could be classified as high-value customers based on lifetime revenue.

5. **Product category performance:** Some categories performed well in both revenue generation and customer review scores, while others generated substantial revenue despite comparatively weaker review scores.

6. **Delivery performance:** Delivery delays and order-related issues varied across regions and product categories.

Overall, customer retention, repeat purchasing, and delivery performance emerged as important areas for further business investigation.

## Project Structure

```text
olist-ecommerce-analysis/
│
├── data/
│   └── Dataset CSV files
│
├── notebooks/
│   └── olist_analysis.ipynb
│
├── README.md
└── .gitignore
```

## How to Run the Project

1. Clone or download this repository.
2. Make sure the dataset CSV files are available inside the `data/` folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the notebook using Jupyter Notebook or VS Code.
5. Run the notebook cells from top to bottom to reproduce the analysis.

## Conclusion

This project demonstrates the use of Python for exploratory data analysis in an e-commerce business context.

By examining sales, customer behavior, product categories, reviews, and delivery performance, the analysis identifies patterns that can help businesses better understand their operations and customers.

The findings also highlight opportunities for further investigation, particularly around customer retention and repeat purchasing behavior.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** E-Commerce  
**Language:** Python