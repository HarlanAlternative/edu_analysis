# Parenting Style and Parent-Child Relationship Analysis

## Project Overview

This project examines the relationship between parenting styles and parent-child relationship quality using survey data. The analysis combines traditional statistical methods with machine learning techniques, and is implemented across three platforms: SPSS, R, and Python.

The goal is to provide both interpretable statistical results and complementary predictive insights.

---

## Research Questions

1. What parenting style dimensions can be identified from the questionnaire data?
2. How do different parenting styles relate to parent-child relationship outcomes?

---

## Data Description

The dataset consists of questionnaire responses measuring:

- Parenting Style (PS-Q1 to PS-Q24)
- Parent-Child Relationship (PCR-Q1 to PCR-Q30)

Several items are reverse-coded before analysis. Composite scores and latent factors are derived using factor analysis.

---

## Methods

### Factor Analysis

Principal Component Analysis (PCA) with varimax rotation is used to extract latent variables.

Extracted parenting style dimensions:
- Authoritative  
- Authoritarian  
- Permissive  

Extracted relationship dimensions:
- Closeness  
- Dependency  
- Conflict  

---

### Descriptive Statistics and Reliability

- Summary statistics are computed for all derived variables  
- Internal consistency is assessed using Cronbach’s alpha  

---

### Correlation Analysis

Correlation matrices are used to examine associations between parenting styles and relationship outcomes.

---

### Multiple Linear Regression

Three regression models are estimated:

- Closeness ~ Parenting styles  
- Dependency ~ Parenting styles  
- Conflict ~ Parenting styles  

Both raw and standardized coefficients are reported.

---

### Mediation Analysis

A mediation model is tested to examine indirect effects, for example:

- Authoritative → Dependency → Closeness  

This is implemented using structural equation modeling (SEM).

---

### Path Analysis

A path model is used to summarize the relationships between parenting styles and all three outcome variables simultaneously.

---

### Machine Learning Models

To complement statistical analysis, several machine learning models are applied:

- Random Forest  
- Lasso Regression  
- Ridge Regression  

These models are used to:

- Evaluate predictive performance  
- Identify important predictors  
- Compare with regression-based results  

---

## Key Findings

- Authoritative parenting is positively associated with closeness  
- Authoritarian parenting shows stronger association with conflict  
- Dependency may act as a mediating factor  
- Machine learning models produce consistent variable importance rankings with regression results  

---


## Tools and Technologies

- SPSS  
- R (psych, lavaan, ggplot2)  
- Python (pandas, sklearn, statsmodels, matplotlib)  

