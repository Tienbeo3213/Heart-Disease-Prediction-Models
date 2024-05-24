Description:
  This project involves the development of various machine learning models to predict heart disease. 
  The models implemented include K-Nearest Neighbors (KNN), Naive Bayes (GaussianNB), Logistic Regression, Decision Tree, Random Forest, and Artificial Neural Networks (ANN). 
  The objective is to evaluate and compare the performance of these models in predicting heart disease based on a given dataset.

Role:
  - Data preprocessing
  - Model development
  - Evaluation and comparison of different algorithms

Technologies Used:
  - Python
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib...

Model Performance Summary:

- GaussianNB (Naive Bayes):
    Accuracy Score: 72.07%
    Cross Validation Score: 90.93%
    ROC_AUC Score: 67.81
    Weighted Average F1 Score: 0.78
    Overview: Suitable for scenarios requiring speed and simplicity, but not ideal for highly imbalanced data.
  
- Logistic Regression:
    Accuracy Score: Improved over GaussianNB
    ROC_AUC Score: 70.98
    Weighted Average F1 Score: 0.81
    Overview: A better choice for simple problems with balanced data compared to GaussianNB.
  
- KNeighbors Classifier:
    Accuracy Score: 87.36%
    Weighted Average F1 Score: 0.88
    ROC_AUC Score: 59.03
    Overview: High overall prediction accuracy but low ROC_AUC Score. Suitable when the F1 Score is more important than the ROC_AUC Score.
  
- Decision Tree Classifier:
    Accuracy Score: 86.97%
    Weighted Average F1 Score: 0.88
    ROC_AUC Score: 58.21
    Overview: Simple and easy to understand, but not effective in terms of ROC_AUC Score.
  
- Random Forest Classifier
    Accuracy Score: 89.20%:
    Weighted Average F1 Score: 0.89
    Cross Validation Score: 98.58%
    ROC_AUC Score: 58.49
    Overview: The strongest model tested, with the highest accuracy and F1 Score. Despite not having the highest ROC_AUC Score, it performs better than several other models.
  
- Artificial Neural Networks (ANN)
    Macro Average F1 Score: 0.60 (reflecting poor performance on the minority class)
    Weighted Average F1 Score: 0.89 (better performance considering class imbalance)
    Overview: Highlights the disparity in performance between majority and minority classes, emphasizing the model's stronger performance on the majority class.

Conclusion:
Based on the provided metrics, the Random Forest Classifier stands out as the best model for this heart disease prediction task, with the highest accuracy and Weighted Average F1 Score.
While its ROC_AUC Score is not the highest, the model's other strengths make it the most robust choice.
