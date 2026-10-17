# Predicting Electric Vehicle (EV) Penetration in West Africa Using a Data-Driven Model

## Project Overview

This project investigates the potential penetration of electric vehicles (EVs) across West Africa using a data-driven machine learning approach. The study explores how economic, demographic, infrastructural, environmental, technological, and policy-related factors associated with EV adoption in countries with established electric vehicle markets can be used to assess EV penetration levels in West African countries.

The project addresses the challenge of predicting EV adoption in a region where electric mobility is still developing and where differences in infrastructure, electricity access, affordability, government policies, and public awareness may influence adoption.

Using secondary data from developed countries with established EV markets and data from 15 West African countries, the project develops and evaluates classification models to categorise EV penetration levels as low, medium, or high.

The objective is to demonstrate how machine learning and data analytics can support evidence-based assessments of EV adoption potential and contribute to discussions about sustainable transportation in West Africa.

## Project Objectives

- Investigate factors associated with electric vehicle adoption in countries with established EV markets.
- Identify relevant features that may influence EV penetration in West African countries.
- Prepare and analyse datasets containing economic, demographic, infrastructural, environmental, and policy-related indicators.
- Apply machine learning classification algorithms to predict EV penetration categories.
- Compare model performance using appropriate classification evaluation metrics.
- Explore how data-driven predictions can inform understanding of electric mobility development in West Africa.

## Dataset and Features

The project uses secondary data collected from relevant sources to examine EV adoption patterns and the conditions that may support electric mobility.

The first dataset covers 20 developed countries with established EV adoption, comprising 39 observations and 18 variables. These data are used to investigate relationships between country-level indicators and EV penetration.

The second dataset covers 15 West African countries, with 15 observations used to assess and classify EV penetration levels.

### Key Features

The analysis considers a range of indicators associated with electric vehicle adoption, including:

- **Economic indicators:** GDP per capita, inflation, and fuel prices.
- **Demographic indicators:** Population, urbanisation, and unemployment.
- **Energy and infrastructure:** Electricity access, renewable energy share, and EV charging station availability.
- **Government policies:** EV incentives and policies supporting electric mobility.
- **Technology and digital readiness:** ICT readiness and related indicators.
- **Public awareness:** Awareness and sentiment towards electric vehicles.
- **EV adoption indicators:** Variables used to examine EV penetration and classify adoption levels.

These features provide a multidimensional view of the conditions that may influence the transition to electric mobility.

## Methodology

### 1. Data Collection and Preparation

Secondary data were collected from relevant sources to construct datasets for developed countries with established EV markets and West African countries.

The data preparation process involved organising variables, preparing features for modelling, and defining EV penetration categories for the classification task.

### 2. Exploratory Data Analysis

The datasets were examined to understand the distribution of variables and explore relationships between country-level characteristics and EV adoption.

The analysis considered economic development, electricity access, charging infrastructure, policy support, and other factors that may influence EV penetration.

### 3. Feature Selection and Engineering

Relevant country-level features were prepared for use in predictive modelling. The objective was to identify indicators that could help explain differences in EV adoption and support the classification of EV penetration levels in West Africa.

### 4. Machine Learning Modelling

Several classification algorithms were investigated and compared, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- Gradient Boosting and XGBoost
- Support Vector Machine (SVM)

The models were evaluated to investigate their suitability for predicting EV penetration categories from the available country-level data.

### 5. EV Penetration Classification

EV penetration in West African countries was classified into three categories based on the project's defined thresholds:

- **Low penetration:** 0–1%
- **Medium penetration:** 1–5%
- **High penetration:** Above 5%

The categories were encoded numerically as 0, 1, and 2 for classification modelling.

### 6. Model Evaluation

The models were assessed using classification metrics, including:

- Accuracy
- Precision
- Recall
- F1-score

These metrics were used to compare predictive performance and examine the models' ability to classify EV penetration levels.

The modelling process also considered the limitations associated with the small dataset and the potential for overfitting and variation in results across different random seeds.

## Technologies and Tools

- Python
- Pandas
- NumPy
- PySpark
- Scikit-learn and machine learning libraries, as applicable to the implementation
- Jupyter Notebook
- Data preprocessing and feature engineering
- Classification modelling and model evaluation

## Key Areas of Investigation

The project explores how differences in economic development, electricity access, renewable energy, charging infrastructure, policy support, fuel prices, and public awareness may be associated with EV penetration.

It applies machine learning to investigate whether patterns identified in countries with established EV markets can help classify EV adoption levels in West Africa.

The project also highlights the challenges of applying predictive models to small datasets and countries with different economic and infrastructural conditions.

## Limitations

The analysis is constrained by the availability and consistency of secondary data, the small number of observations in the West African dataset, and differences between developed EV markets and emerging markets.

Consequently, the predictions should be interpreted as exploratory classifications rather than definitive forecasts of future EV adoption. Further research using larger datasets, additional observations over time, and locally validated indicators would help strengthen the reliability and generalisability of the models.

## Conclusion

This project demonstrates the application of data analytics and machine learning to investigate electric vehicle penetration in West Africa. By examining features associated with EV adoption in countries with established markets and applying classification models to West African country data, the study explores how data-driven approaches can contribute to understanding the region's electric mobility potential.

The project combines predictive modelling with a regional sustainability challenge, highlighting the importance of economic conditions, infrastructure, electricity access, policy support, and public awareness in the transition towards electric transportation.

## Project Notebook

Explore the complete analysis, code, and modelling workflow in the Jupyter Notebook:

[View the EV Penetration Project on GitHub](https://github.com/Chimzi20/dissertation/blob/main/ev-final-project.ipynb)

## Author

**Nkiri Chimzi Francis**

GitHub: [@Chimzi20](https://github.com/Chimzi20)
