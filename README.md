# Credit Card Customer Behavior & Financial Analytics

**Exploratory Data Analysis | Python | Pandas | NumPy | Matplotlib | Seaborn**

## Project Overview

This project analyzes credit card customer behavior, spending patterns, repayment trends, and financial performance for a fictional banking organization, PSPD Bank.

The objective is to transform customer and transaction data into meaningful business insights using Python-based data cleaning, exploratory data analysis (EDA), aggregation, and visualization.

## Business Objectives

- Understand customer spending and repayment behavior.
- Identify the most popular spending categories.
- Analyze spending patterns across cities and age groups.
- Compare monthly spending and repayment trends.
- Estimate bank interest earnings using the case study's stated assumptions.
- Identify top customers based on repayment.
- Explore yearly and monthly spending patterns.

## Tech Stack

| Technology | Application |
|---|---|
| Python | Data analysis and programming |
| Pandas | Data manipulation and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |

## Dataset Description

The case study uses three datasets:

1. **Customer Acquisition:** Customer details and card information.
2. **Spend:** Credit card transaction and spending records.
3. **Repayment:** Customer repayment records.

> **Data availability:** The original course-provided datasets are not included in this repository. Do not redistribute them unless you have the required permission and the applicable licence allows it.

## Data Cleaning & Preparation

The case study specifies these preparation rules:

- Replace customer ages below 18 with the mean age.
- Replace spending amounts exceeding a customer's credit limit with 50% of that customer's limit.
- Replace repayment amounts exceeding a customer's credit limit with the customer's limit.
- Prepare date fields for time-based analysis.
- Standardize inconsistent category labels where required.

## Exploratory Data Analysis

### 1. Customer & Transaction Overview

- Count distinct customers.
- Count distinct transaction categories.
- Calculate average monthly customer spending.
- Calculate average monthly customer repayment.

### 2. Financial Analysis

- Compare monthly spending and repayment.
- Calculate monthly profit using the case study's definition.
- Estimate bank interest at a monthly rate of 2.9%, applying interest only to positive monthly profit.

**Case study formulas**

```text
Monthly Profit = Monthly Repayment - Monthly Spend

Bank Interest = max(Monthly Profit, 0) * 2.9%
```

### 3. Customer Behavior Analysis

- Identify the top five product types by spending.
- Find the city with the maximum spend.
- Compare spending across age groups.
- Identify the top ten customers by repayment.

### 4. Time-Based & Geographical Analysis

- Analyze city-wise yearly spending by product.
- Compare monthly spending across cities.
- Compare yearly spending on air tickets.
- Examine monthly spending patterns by product and look for seasonality.

### 5. Reusable Python Function

The case study asks for a user-defined function that identifies the top ten repayment customers for each city based on a selected card product and time period.

The function accepts:
- Card product: Gold, Silver, or Platinum.
- Time period: Yearly or Monthly.

## Key Learning Outcomes

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Data aggregation with Pandas.
- Merging multiple datasets.
- Date and time-based analysis.
- Conditional data transformations.
- Business-oriented financial calculations.
- Data visualization and interpretation.
- Writing reusable Python functions.

## Repository Structure

```text
credit-card-customer-behavior-analysis/
├── Credit_Card_Case_Study.ipynb
├── README.md
└── requirements.txt
```

If you are authorized to use the source data, place the required CSV files in the location expected by the notebook. Keep private or restricted data out of the public repository.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/credit-card-customer-behavior-analysis.git
cd credit-card-customer-behavior-analysis
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

3. Make the required, authorized input datasets available at the paths expected by the notebook.

4. Start Jupyter:

```bash
jupyter notebook
```

5. Open `Credit_Card_Case_Study.ipynb` and run the notebook cells.

## Conclusion

This project applies Python and exploratory data analysis to credit card data to examine customer behavior, spending and repayment trends, and financial performance. It demonstrates a practical workflow for turning transaction data into business-oriented analysis.

---

**Author:** Your Name  
**Domain:** Data Analytics | Financial Analytics | Exploratory Data Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn
