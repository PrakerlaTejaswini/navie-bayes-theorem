# navie-bayes-theorem

Naive Bayes Classifier for Heart Disease Prediction

This project implements a **Naive Bayes classification algorithm** to predict the presence of heart disease based on various patient health metrics. 
It uses the `heart.csv` dataset, containing features like age, blood pressure, cholesterol level, and chest pain type. 
The model is trained using the `GaussianNB` approach from scikit-learn, suitable for continuous data.

After training the model and evaluating it on the test set, the following results were observed:

- **Accuracy**: ~84.2%
-  **Precision**: ~88.2%
-  **Recall**: ~84.1%
-  **F1-Score**: ~86.1%

The confusion matrix showed strong performance with minimal false predictions, indicating that the Naive Bayes classifier can effectively distinguish between patients with and without heart disease.
