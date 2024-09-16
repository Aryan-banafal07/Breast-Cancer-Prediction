**Breast Cancer Prediction using Support Vector Machine (SVM)**
This project implements a machine learning model to predict the likelihood of breast cancer based on patient data. The model utilizes features such as tumor characteristics to assist in early diagnosis and treatment planning. The focus is on applying a Support Vector Machine (SVM) with a linear kernel for classification.

**Features**
Data Preprocessing:
Feature scaling using StandardScaler to normalize the data for improved model performance.
Model Training:
Training an SVM model on a subset of the data (training set).
Making predictions on the test set.
Performance Evaluation:
Evaluating the model using a confusion matrix and accuracy score.
Visualization:
2D visualization of the decision boundary for selected features (radius_mean and texture_mean).
Libraries Used
numpy
pandas
matplotlib
scikit-learn
Confusion Matrix and Accuracy Score
plaintext
Copy code
Confusion Matrix:
[[88  2]
 [ 2 51]]

**Accuracy: 97.20%**
Visualization of SVM Classifier (Training Set)
A color-coded contour plot visualizes the decision boundary for the two selected features, demonstrating the separation between malignant and benign cases.

How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/Aryan-banafal7/Breast-Cancer-Prediction.git
Install the necessary Python libraries:
bash
Copy code
pip install -r requirements.txt

Run the script:
Execute the script in a Jupyter notebook or Python environment.
Dataset
Ensure that the dataset follows the expected structure, with labels mapped to M for malignant and B for benign, which are then converted to binary values.
