# Day 1 - Data Analysis and Return Risk Identification

## Project Title

**An Explainable LLM-Based Return Validation and Risk Assessment System Using RAG**

## Day 1 Objective

The objective of Day 1 is to create and analyze customer return data and identify return risk levels for building the return validation system.

## Dataset

A dataset containing **500 customer return records** was created using Python.

The dataset contains the following information:

- Return ID
- Product Category
- Days After Delivery
- Product Condition
- Return Reason
- Payment Method
- Product Price
- Customer Rating
- Previous Returns
- Within Policy Period
- Return Approved

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Excel

## Day 1 Activities

### 1. Dataset Creation

Created a structured dataset containing customer return information for different product categories.

### 2. Exploratory Data Analysis

Analyzed the dataset to understand:

- Product categories
- Return reasons
- Product conditions
- Return approval status
- Policy period
- Customer ratings
- Previous customer returns

### 3. Risk Score Calculation

A risk score was calculated for each return request using factors such as:

- Days after delivery
- Product condition
- Previous returns
- Customer rating

### 4. Risk Level Classification

Each return request was classified into three risk levels:

- **LOW** - Low return risk
- **MEDIUM** - Moderate return risk
- **HIGH** - High return risk

### 5. High-Risk Category Analysis

Product categories were analyzed based on their risk scores and high-risk cases to identify categories requiring more attention during return validation.

## Day 1 Outcome

At the end of Day 1:

- The return dataset was successfully created.
- Exploratory data analysis was completed.
- Risk scores were calculated.
- Return requests were classified into risk levels.
- High-risk product categories were identified.

The results from Day 1 will be used as the foundation for the **LLM-based return validation and RAG policy analysis** in the next stages of the project.

## Project Progress

**Day 1 - Completed ✅**

**Next:** Day 2 - Return Risk Analysis and LLM Workflow
