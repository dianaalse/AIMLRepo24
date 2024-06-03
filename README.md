README
This Jupyter notebook demonstrates the use of a Random Forest Classifier to classify network traffic data as either "normal" or "attack" traffic. The key steps involved are:

1. Importing and preprocessing the data, including converting categorical features to numerical codes.
2. Fitting a basic Random Forest Classifier and evaluating its performance on a test set.
3. Performing hyperparameter tuning using GridSearchCV to optimize the model's F1-score.
4. Analyzing the feature importances to identify the most influential variables in the classification.

The final optimized model achieves an accuracy of 83% and an F1-score of 0.86 on the test set, indicating strong predictive performance. The top features include network traffic characteristics like data load, rate, and TCP round-trip time. This model could be used to enhance network security by automatically detecting and flagging potential cyber attacks, helping organizations protect their systems and data more effectively. The interpretability of the Random Forest model also allows for better understanding of the underlying patterns in the data, which can inform future security measures and policies.

