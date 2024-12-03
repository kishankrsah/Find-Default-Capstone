# Dataset Link https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud




# Find-Default-Capstone-

# Prediction of Credit Card Fraud

**Created By**: Kishan Kumar  

In this analysis, I performed a comprehensive exploration and modeling process for credit card fraud detection using an imbalanced dataset. The steps included:
- **Data Exploration and Preprocessing**: Loading and exploring the dataset, visualizing class imbalance, and performing necessary preprocessing steps.
- **Correlation Analysis**: Investigating the correlations between features to identify potential redundancies and understand feature relationships.
- **Handling Imbalanced Data**: Applying techniques such as undersampling and oversampling to address class imbalance, ensuring that our models could better learn from the minority class.
- **Model Training and Evaluation**: Training and evaluating various classifiers, including Logistic Regression, Decision Tree, and Random Forest, using metrics such as confusion matrices, classification reports, ROC-AUC scores, and ROC curves.
- **Model Saving**: Saving the trained models for future use, ensuring easy loading and application for predictions on new data.

**Key Findings**:
- **Feature Correlations**: Our correlation analysis revealed important relationships between features, guiding future feature selection and engineering.
- **Model Performance**: The Random Forest Classifier demonstrated high accuracy in detecting fraud, showing that it is a strong candidate for deployment. The ROC-AUC scores and ROC curves provided insights into each model’s performance, particularly in distinguishing between fraudulent and non-fraudulent transactions.
- **Impact of Imbalance Handling**: Techniques for balancing the dataset were essential in improving model performance and ensuring that the minority class (fraudulent transactions) was adequately represented in the training process.

