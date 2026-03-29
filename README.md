# Churn_prediction
Build a ML model for churn prediction and compared many classification models to find out the best one.

# Dataset
I have used Customer churn dataset which contains 88167 rows and 12 columns were present

# Steps Performed 
1.Data Preprocessing:
 -feature mapping was done  by selecting relevant features and renamed them as per the required fields that is important fields

 2.Encoding:
 -Converted categorical data into numerical format using one hot encoding

 3.Standardization:
 -feature sacling was done to normalize and class imbalance was checked and there was no requirement of using techniques like SMOTE

 4.Train-Test Split
- Split dataset into training and testing sets (80% training, 20% testing)

# Models Used
-Logistic Regression
-Decision Tree
-Random Forest
-Gradient Boosting

# Model Evaluation
-Accuracy
-Confusion Matrix
-ROC curve
-Precision,Recall,and f1-score

# Model accuracy
-Logistic Regression: ~68%
-Decision Tree: ~80%
-Random Forest: ~79%
-Gradient Boosting: ~80%

-Logistic Regression
-Decision Tree
-Random Forest
-Gradient Boosting

-Gradient Boosting performed the best with stable accuracy and no overfitting.
-The model showed strong ability to distinguish between churn and non-churn customers.

# Takeaways

- Customers with lower purchases and income are more likely to churn
- Ensemble models performed better than simple models
- Machine learning models significantly outperformed rule-based logic

# Rule based logic

- Rule accuracy was around 50%, which is much lower than ML models
- This highlights the advantage of machine learning in capturing complex patterns

# visualization:
- Model Accuracy Comparison
- Model Accuracy Comparison
- ROC Curve
- Feature Importance Plot
- Correlation Heatmap

# conclusion Conclusion
This project shows a complete machine learning pipeline for customer churn prediction.
Among all models, Gradient Boosting achieved the best performance with good accuracy and stability.
Machine learning models are proved to be more effective than rule-based approaches in solving real-world business problems.


