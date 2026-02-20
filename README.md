# Snigdha Pakala's Portfolio
A portfolio of projects in Python, R, and SQL demonstrating applied statistics, data science, and visualization skills.

## [Project 1: Causal Mediation Analysis of Triglyceride-Glucose Index & Cardiovascular Mortality](https://github.com/snigdhapakala/Causal-Mediation-Analysis)

This is a graduate-level research project analyzing the relationship between metabolic risk factors and cardiovascular mortality using nationally representative health survey data. The study applies causal mediation techniques to decompose total effects into direct and pathway-mediated components.

- **Data:**  Integrated multiple NHANES survey cycles with linked National Death Index mortality records for longitudinal analysis.
- **Study Design:** Observational cohort framework with time-to-event outcomes.
- **Techniques:** Data harmonization across survey cycles, covariate adjustment, interaction modeling.
- **Statistical Methods:** Regression-based causal mediation analysis to decompose total effects into direct and indirect (mediated) effects.
- **Inference:** Bootstrap confidence intervals, sensitivity analysis for mediation assumptions, robustness checks.

The analysis provides a structured causal framework for understanding interacting metabolic mechanisms contributing to cardiovascular mortality risk.

The full research paper can be found [here.](https://github.com/snigdhapakala/Causal-Mediation-Analysis/blob/main/Causal%20Mediation%20Analysis.pdf)

## [Project 2: Smoking Behavior Prediction Using Machine Learning](https://github.com/snigdhapakala/Smoking-Behavior-ML)

This is a project I did during my master's program that analyzes smoking behavior through interpretable machine learning techniques, using the 2020 Behavioral Risk Factor Surveillance System (BRFSS) dataset. 

- **Data:**  Over 300,000 records from BRFSS, including demographic, health, and behavioral features.
- **Techniques:** one-hot/ordinal/custom encoding, z-score normalization
- **Algorithms:** Logistic regression, Random Forest, XGBoost, Multilayer Perceptron Neural Network with 2 hidden layers, ReLU activation, and dropout regularization
- **Modeling:** SHAP values, permutation importance, t-SNE visualization, ablation studies
- **Evaluation metrics:** ROC AUC, Brier Score, Precision, Recall, F1-score, Calibration curves, Expected Calibration Error (ECE)  

The comprehensive approach balances predictive power with interpretability, offering insights into smoking risk factors valuable for public health interventions.

The research paper I wrote for this project can be found [here.](https://github.com/snigdhapakala/Smoking-Behavior-ML/blob/main/Research_Paper_Smoking_Behavior_ML.pdf)

## [Project 2: Pneumococcal Vaccination Campaign Analysis with Bayesian Hierarchical Modeling](https://github.com/snigdhapakala/Bayesian_Statistics_Vaccination_Campaign_Effectiveness)

This is a project from my master’s program using R that evaluates pneumococcal vaccination campaign effectiveness using Bayesian hierarchical statistical modeling on CDC BRFSS data (2018–2021).

- **Data:** CDC BRFSS survey (2018–2021), adult vaccination coverage stratified by geography, demographics, and time period  
- **Techniques:**  Bayesian hierarchical modeling, STAN for Bayesian inference with prior/posterior predictive checks  
- **Statistical & Data Science Methods:** Binomial likelihood with logit link, Region-specific intercepts with global hyperpriors, MCMC parametric estimation
- **Evaluation Metrics:** Convergence diagnostics (Rhat, ESS, trace plots, autocorrelation)  

The full report is available in [here.](https://github.com/snigdhapakala/Bayesian_Statistics_Vaccination_Campaign_Effectiveness/blob/main/Bayesian_Statistics_Report.pdf)

## [Project 3: Statistical Analysis of Emergency Service Claims by Income Category](https://github.com/snigdhapakala/Statistical-Analysis-Emergency-Claims-Income)

This project analyzes the relationship between socioeconomic status and frequency of emergency service claims using Medicare and IRS income data.

- **Data**: Combines 2022 Medicare Physician Other Practitioners claims data with ZIP code-level Adjusted Gross Income (AGI) from IRS
- **Scope**: Examines disparities in emergency service use across high-poverty and affluent ZIP codes defined by income brackets
- **Methods**: Data cleaning, merging datasets, EDA, log transformation for skewness reduction, normalization of claim frequencies per beneficiary group
- **Statistical Analysis**: Linear regression with heteroskedasticity-consistent standard errors, Welch two-sample t-test comparing claim rates, Residual diagnostics including Q-Q plots and tests for normality and homoscedasticity

The project provides a statistical framework combining regression modeling with robust inference and comprehensive visualization to examine income-based disparities in emergency healthcare usage.

My project report can be found [here.](https://github.com/snigdhapakala/Statistical-Analysis-Emergency-Claims-Income/blob/main/Paper_Statistical_Analysis_Emergency_Claims.pdf)
