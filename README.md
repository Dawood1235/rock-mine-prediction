Rock vs Mine Prediction using Sonar Data

This project uses Machine Learning (Logistic Regression) to classify whether an object detected by sonar signals is a Rock or a Mine.

The dataset contains sonar readings bounced off underwater objects, and the model learns patterns to make predictions.

📌 Project Overview

The goal of this project is to build a binary classification model that can distinguish between:

Rock
Mine

We use the Sonar dataset, which contains 60 numerical features representing sound wave reflections.

🧠 Algorithm Used
Logistic Regression

A supervised learning algorithm used for binary classification:

Works well for linearly separable data
Outputs probability between 0 and 1
Simple and efficient for baseline models
📊 Dataset Information
Total Features: 60
Target Classes:
R → Rock
M → Mine
Data Type: Numerical sonar signal values
⚙️ Workflow
Import dataset
Data preprocessing
Train-test split
Model training (Logistic Regression)
Model evaluation
Accuracy calculation
🧪 Model Performance
Training Accuracy: 83.42%
Testing Accuracy: 76.19%
🧾 Libraries Used
Python 🐍
NumPy
Pandas
Scikit-learn
🚀 How to Run the Project
Clone the repository:
🚀 How to Run the Project
# Clone repository
git clone https://github.com/your-username/rock-mine-prediction.git

# Move into directory
cd rock-mine-prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py
📈 Results

The Logistic Regression model performs well on sonar data and is able to classify rocks and mines with good accuracy. Performance may vary depending on train-test split and data preprocessing.

📌 Future Improvements
-Try advanced models (SVM, Random Forest, XGBoost)
-Hyperparameter tuning
-Feature selection techniques
-Cross-validation for better evaluation
