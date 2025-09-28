# Snigdha Pakala's Portfolio
A portfolio of projects in Python, R, and SQL demonstrating applied statistics, data science, and visualization skills.

# [Project 1: Smoking Behavior Prediction Using Machine Learning]

This is a project I did during my master's program that analyzes smoking behavior through interpretable machine learning techniques, using the 2020 Behavioral Risk Factor Surveillance System (BRFSS) dataset.

**Data:**  
- Over 300,000 records from BRFSS, including demographic, health, and behavioral features.

**Models and Techniques:**  
- **Classical Models:**
  - Logistic Regression (baseline)
  - Random Forest (hyperparameter tuned with grid search)
  - XGBoost (log-loss evaluation metric)
- **Neural Network Model:**
  - Multilayer Perceptron (MLP) with two hidden layers (64, 32 neurons)
  - ReLU activations, dropout regularization (0.3 dropout rate)
  - Trained with Adam optimizer for 20 epochs
  - Random feature masking as regularization to reduce overfitting
- **Preprocessing:**  
  - One-hot encoding for categorical features  
  - Ordinal encoding for ordered categories (e.g., general health)  
  - Custom encoding for diabetic condition  
  - StandardScaler z-score normalization for continuous variables 

**Evaluation and Interpretability:**  
- Metrics: ROC AUC, Brier Score, Precision, Recall, F1-score, Calibration curves  
- Model interpretability with SHAP values for feature importance  
- Permutation importance analysis and ablation studies on key features  
- Visualization of latent space via t-SNE to observe clustering of smoker/non-smoker groups  
- Expected Calibration Error (ECE) to assess probabilistic output reliability from MLP  

**Key Findings:**  
- XGBoost achieved the highest ROC AUC of 0.684, with Random Forest close behind at 0.679.  
- Logistic regression showed weaker performance, indicating nonlinear relationships in the data.  
- Important predictors included general health status, diabetic condition, age category, and alcohol consumption.  
- Visualization and SHAP dependence plots highlighted how combined factors like age and poor health increase smoking risk.  
- The MLP model, though slightly less performant, was well-calibrated and benefited from dropout and feature masking to reduce overfitting.  
- Ablation studies confirmed the critical impact of features like AgeCategory and General Health on model performance.

The comprehensive approach balances predictive power with interpretability, offering insights into smoking risk factors valuable for public health interventions.
