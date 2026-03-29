In this project, multiple machine learning models were built and compared to predict customer churn. The main aim was to understand which model performs best and why.

Logistic Regression was used as a starting point. It is a simple model and helped in getting a basic understanding of how the features relate to churn. However, its performance was lower compared to other models because it cannot capture complex patterns well.

Next, Decision Tree was used. This model was able to handle non-linear relationships in the data and gave better accuracy than Logistic Regression. It was also easy to interpret, but it can sometimes overfit the data.

Random Forest was then applied to improve the performance of Decision Tree. By combining multiple trees, it reduced overfitting and provided more stable results. The accuracy improved further, making it a strong model.

Gradient Boosting gave the best performance among all models. It works by learning from previous mistakes step by step, which helps it capture complex patterns more effectively. It showed high accuracy and balanced performance, making it the best choice for this problem.

A rule-based approach was also implemented for comparison. It used simple conditions based on features like purchases and income. However, its accuracy was much lower (around 50%), showing that simple rules are not enough for predicting churn in real-world scenarios.

Overall, machine learning models clearly outperformed the rule-based approach. Among them, Gradient Boosting was the most effective and was selected as the final model for churn prediction.