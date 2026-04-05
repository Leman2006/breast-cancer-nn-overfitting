🧠 Breast Cancer Classification & Overfitting Analysis

This project focuses on building a neural network model to classify breast cancer data and analyze overfitting behavior using deep learning techniques.

📌 Project Objective
Develop a binary classification model
Analyze overfitting using training and validation metrics
Apply regularization techniques to improve generalization
📊 Dataset
Breast Cancer Dataset (from Scikit-learn)
30 numerical features
Target:
0 → Malignant
1 → Benign
⚙️ Technologies Used
Python
TensorFlow / Keras
Scikit-learn
NumPy
Matplotlib
🏗️ Model Architecture
Fully Connected Neural Network (Dense layers)
Batch Normalization
Dropout Layers
L2 Regularization
🛠️ Techniques Applied
Train / Validation Split
Feature Scaling (StandardScaler)
EarlyStopping
Overfitting Analysis using training curves
📈 Results
Compared training and validation performance
Observed overfitting behavior
Improved model generalization using:
Dropout
L2 Regularization
Early Stopping
📷 Visualization

The model performance is evaluated using:

Training vs Validation Loss
Training vs Validation Accuracy

(Add your training plot image here if available)

🚀 How to Run
Clone the repository:
git clone https://github.com/Leman2006/breast-cancer-nn-overfitting.git
cd breast-cancer-nn-overfitting
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook
📎 Project Structure
breast-cancer-nn-overfitting/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
💡 Key Takeaways
Overfitting is a common issue in neural networks
Regularization techniques are essential for better generalization
Validation metrics are critical for evaluating model performance
📌 Future Improvements
Add confusion matrix and classification report
Compare with traditional ML models (Logistic Regression, SVM)
Hyperparameter tuning
Cross-validation
