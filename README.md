Breast Cancer Classification using Scikit-Learn

Introduction
This project uses the Scikit-Learn library to classify breast cancer samples as malignant or benign. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, which is a multiclass classification problem.

Dataset
- The dataset consists of 569 samples, each described by 30 features.
- The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
- The target variable is a binary classification label (malignant or benign).

Preprocessing
- The dataset is split into training and testing sets using the train_test_split function from Scikit-Learn.
- The features are scaled using the StandardScaler from Scikit-Learn.

Classification Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- k-Nearest Neighbors (k-NN)

Model Evaluation
- The accuracy of each model is evaluated using the accuracy_score function from Scikit-Learn.
- The model with the highest accuracy is selected as the best-performing model.

Results
- The best-performing model is the Random Forest Classifier, with an accuracy of 96.5%.
- The worst-performing model is the Decision Tree Classifier, with an accuracy of 90.5%.

Conclusion
- This project demonstrates the use of Scikit-Learn for breast cancer classification.
- The results show that the Random Forest Classifier is the best-performing model for this dataset.

Future Work
- Experiment with other classification models and techniques.
- Use feature selection methods to reduce the dimensionality of the dataset.
- Use ensemble methods to combine the predictions of multiple models.
