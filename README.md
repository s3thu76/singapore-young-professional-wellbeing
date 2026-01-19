# Work Pressure, Recovery, and Sustainable Well-Being in Singapore

This project analyzes how work pressure, recovery, and boundary control relate to mental well-being among young professionals in Singapore.  
It demonstrates an end-to-end survey-driven analytics workflow with a focus on interpretability, inference, and social good.

---

## Research Question

How do work intensity, pressure, and recovery mechanisms relate to sustainable mental well-being among young professionals in Singapore?

---

## Methods

- Survey design with Likert-scale and ordinal items
- Data cleaning and normalization
- Construction of a **Mental Well-Being Index**
- Reverse-coding of pressure indicators
- Exploratory data analysis and visualization
- Multivariate regression (OLS with categorical controls)
- Bootstrap confidence intervals
- Predictive modeling (logistic regression with 5-fold CV ROC-AUC)
- Mediation analysis (pressure → exhaustion → well-being)
- Quantile regression to assess heterogeneous effects

---

## Key Findings

- Mental well-being is strongly negatively associated with work pressure
- Longer work hours and reduced recovery correlate with lower sustainability
- Exhaustion partially mediates the relationship between pressure and well-being
- Pressure effects are strongest among individuals with already low well-being
- Industry-level differences suggest unequal exposure to pressure

---

## Social Good Implications

- Reducing after-hours expectations may substantially improve well-being
- Recovery time and boundary control matter as much as total hours
- High-pressure industries may require targeted, structural interventions
- Policies should focus on **sustainability**, not just productivity

---

## How to Run

```bash
pip install -r requirements.txt
