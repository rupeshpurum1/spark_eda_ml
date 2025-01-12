
# Analyzing Consumer Finance Complaints with Apache Spark

## Overview

This project explores consumer financial complaints using Apache Spark's SQL and MLlib libraries. It includes data preparation, exploratory data analysis (EDA), machine learning model implementation, and insights generation. The primary focus is on uncovering trends, understanding consumer grievances, and building predictive models to classify or interpret complaints effectively.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Data Preparation](#data-preparation)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Machine Learning Models Implementation](#machine-learning-models-implementation)
5. [Further Data Processing](#further-data-processing)
6. [Model Evaluation and Comparison](#model-evaluation-and-comparison)
7. [Analysis and Insights](#analysis-and-insights)
8. [Conclusion](#conclusion)
9. [References](#references)

---

## Dataset Details

- **Source:** [Consumer Finance Protection Bureau (CFPB)](https://www.consumerfinance.gov/data-research/consumer-complaints/search/)
- **Collected On:** October 31, 2024
- **Time Range:** Last 3 years of data
- **Size:** Approximately 1.6 GB
- **Format:** CSV
- **Observations:** Over 1.2 million complaints

### Key Fields:
- **Date received:** Date the CFPB received the complaint.
- **Product:** Type of financial product (e.g., mortgage, credit card).
- **Issue:** Primary concern in the complaint (e.g., billing error).
- **Company:** Entity receiving the complaint.
- **Consumer complaint narrative:** Description of the issue from the consumer's perspective.
- **Tags:** Metadata such as "Older American" or "Servicemember."
- **Response metrics:** Includes fields like "Timely response?" and "Consumer disputed?"

---

## Project Steps

1. **Data Preparation:**
   - Load data into Spark.
   - Handle missing values and adjust schemas.
   - Optimize storage using formats like Parquet.

2. **Exploratory Data Analysis (EDA):**
   - Analyze trends using Spark SQL queries.
   - Generate visualizations to highlight key insights (e.g., top issues, regions, and product categories).

3. **Machine Learning Implementation:**
   - Models applied: Logistic Regression, Decision Tree, and Naive Bayes.
   - Tasks: Feature engineering, hyperparameter tuning, and metrics evaluation.

4. **Insights and Reporting:**
   - Interpret EDA and model findings.
   - Relate outcomes to business objectives.
   - Compile actionable recommendations.

---

## Tools and Libraries Used

- **Python**
- **Apache Spark SQL**
- **Spark MLlib**
- **Google Colab** (Optional for mounting data and interactive analysis)

---

## How to Run

1. Clone the repository and set up a Python environment with required libraries.
2. Load the dataset by downloading it from the [CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/search/).
3. Execute the notebook sequentially, ensuring access to Spark runtime.

---

## Results

The project delivers insights into complaint patterns, predictive capabilities for complaint categorization, and business recommendations. Detailed results and visualizations are available in the notebook under the respective sections.

---

## References

- [Consumer Finance Protection Bureau](https://www.consumerfinance.gov/data-research/consumer-complaints/search/)
- Spark Documentation: [Apache Spark](https://spark.apache.org/)

--- 
