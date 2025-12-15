# \# Heart Disease Prediction (Machine Learning)

# 

# This project applies machine learning techniques to predict the presence of heart disease using clinical patient data. The focus of this work is not only on predictive performance, but also on responsible evaluation, medical interpretation, and ethical considerations.

# 

# ---

# 

# \## 🎯 Problem Statement

# 

# Heart disease is a major global health concern, and early identification of at-risk patients can support preventive care. The goal of this project is to build a classification model that predicts whether a patient has heart disease based on clinical attributes.

# 

# In medical prediction tasks, different types of errors have unequal consequences. Missing a patient with heart disease (false negative) is more harmful than incorrectly flagging a healthy individual (false positive). Therefore, this project prioritizes recall and clinically meaningful evaluation metrics over raw accuracy.

# 

# ---

# 

# \## 📊 Dataset

# 

# The dataset consists of commonly used clinical features such as:

# \- Age

# \- Resting blood pressure

# \- Serum cholesterol

# \- Maximum heart rate

# \- Chest pain type

# \- Other diagnostic indicators

# 

# The data represents historical clinical records and is used strictly for educational and analytical purposes.

# 

# ---

# 

# \## 🧠 Methodology

# 

# The workflow followed in this project includes:

# \- Data preprocessing and feature separation

# \- Exploratory data analysis to validate clinical plausibility

# \- Train / validation / test splitting with reproducibility

# \- Model training using multiple classical machine learning algorithms

# \- Evaluation using recall, precision, F1-score, and ROC-AUC

# 

# Tree-based and linear models were compared, with emphasis on interpretability and error trade-offs rather than model complexity.

# 

# ---

# 

# \## 📈 Model Evaluation

# 

# Accuracy was not used as the primary metric due to its limitations in medical settings. Instead:

# \- \*\*Recall\*\* was prioritized to minimize false negatives

# \- \*\*ROC-AUC\*\* was used to assess overall discriminative performance

# \- Confusion matrices were analyzed to understand error distribution

# 

# The final model selection reflects a deliberate trade-off between sensitivity and false positives, aligning with real-world clinical decision-making.

# 

# ---

# 

# \## 📓 Main Notebook

# 

# \- `notebooks/heart\_disease\_prediction.ipynb`  

# &nbsp; \*(Recommended starting point)\*

# 

# Older exploratory notebooks are preserved in:

# \- `notebooks/legacy/`

# 

# ---

# 

# \## ⚠️ Limitations

# 

# \- The dataset is relatively small and may not generalize to broader populations

# \- The analysis is descriptive and non-causal

# \- Lifestyle, genetic, and longitudinal factors are not included

# \- The model is not validated on external clinical data

# 

# ---

# 

# \## 🧠 Learning Outcomes

# 

# This project reinforced the importance of:

# \- Aligning evaluation metrics with domain-specific risks

# \- Interpreting model behavior in a real-world context

# \- Acknowledging uncertainty and limitations in ML systems

# 

# ---

# 

# \## 🔄 Project Evolution

# 

# This project was originally created as a learning exercise and later revisited to reflect a deeper understanding of model evaluation, medical context, and responsible machine learning practices.

# 

# ---

# 

# \## ⚠️ Disclaimer

# 

# This project is intended for \*\*educational purposes only\*\* and should not be used as a medical diagnostic tool.



