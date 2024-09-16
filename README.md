# Breast Cancer Prediction using Support Vector Machine (SVM)
This project implements a machine learning model to predict the likelihood of breast cancer based on patient data. The model utilizes features such as tumor characteristics to assist in early diagnosis and treatment planning. The focus is on applying a Support Vector Machine (SVM) with a linear kernel for classification.

# Features
Data Preprocessing:
Handles missing values and scales features using StandardScaler for improved model performance.
Model Training:
Trains an SVM model on a subset of the data (training set).
Makes predictions on the test set.
Performance Evaluation:
Evaluates the model using a confusion matrix and accuracy score.
Visualization:
Provides a 2D visualization of the decision boundary for selected features (radius_mean and texture_mean).
Technologies Used
NumPy: Numerical operations and array manipulation.
Pandas: Data manipulation and preprocessing.
Matplotlib: Data visualization.
Scikit-learn: Machine learning algorithms and metrics.
Python: Programming language used.
Installation

Clone the Repository

git clone https://github.com/Aryan-banafal07/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction
Set Up a Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies

pip install -r requirements.txt
Run the Script

Execute the script in a Python environment or Jupyter notebook.

Evaluation
Confusion Matrix:

[[88  2]
 [ 2 51]]
# Accuracy: 97.20%

Visualization
A color-coded contour plot visualizes the decision boundary for the two selected features, demonstrating the separation between malignant and benign cases.

Usage
Place the dataset file (dataset.csv) in the project directory.
Run the script to preprocess the data, train the model, and generate the visualizations.
Troubleshooting
Error Handling: Check for errors in dataset formatting or missing files.
File Format Issues: Ensure that the dataset is in CSV format with correct encoding.
Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements.

Contact
For questions or feedback, please contact [(https://aryanbanafal.vercel.app)].
