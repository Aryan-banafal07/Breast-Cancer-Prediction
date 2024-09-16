Breast Cancer Prediction using Support Vector Machine (SVM)
This project implements a machine learning model to predict the likelihood of breast cancer based on patient data. The model uses features such as tumor characteristics to assist in early diagnosis and treatment planning. The project focuses on applying a Support Vector Machine (SVM) with a linear kernel for classification.

Features
Data Preprocessing: The dataset undergoes feature scaling using StandardScaler for improved model performance.
Model Training: An SVM model is trained on a subset of the data (training set), and predictions are made on the test set.
Performance Evaluation: A confusion matrix and accuracy score are used to evaluate the performance of the model on the test set.
Visualization: A 2D visualization of the decision boundary is provided for a selected subset of features (radius_mean and texture_mean).
Libraries Used
numpy
pandas
matplotlib
scikit-learn
Confusion Matrix and Accuracy Score
lua
Copy code
[[88  2]
 [ 2 51]]
Accuracy: 97.2%
Visualization of SVM Classifier (Training Set)
The decision boundary is visualized for two selected features using a color-coded contour plot, demonstrating the separation between malignant and benign cases.

How to Use
Clone this repository.
Install the necessary Python libraries from requirements.txt.
Replace the dataset with your own or use the existing one.
Run the script in a Jupyter notebook or Python environment.
Dataset
Ensure that the dataset used follows the expected structure where the labels are mapped to M for malignant and B for benign, which are then converted to binary values.

