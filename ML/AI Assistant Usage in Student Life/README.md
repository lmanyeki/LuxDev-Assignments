### ML Classification Project

Get the dataset here: --> https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic
#### 📌 Overview

This project predicts two targets from session data:

**UsedAgain** → likelihood of reuse

**FinalOutcome** → overall session result

Seven machine learning models are trained, tuned, and compared.

#### ⚙️ Models

Logistic Regression

Decision Tree

Random Forest

Naive Bayes

KNN

Gradient Boosting

XGBoost

#### 🛠️ Setup
git clone https://github.com/yourusername/ml-classification.git
cd ml-classification
pip install -r requirements.txt


- requirements.txt

pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

#### 📊 Workflow

Data preprocessing: drop irrelevant cols, encode, scale if needed.

Split: 80% train / 20% test.

Train models.

Evaluate with accuracy, confusion matrix, classification report.

Cross-validation + GridSearchCV for tuning.

Compare results.


#### 📈 Evaluation Metrics

Accuracy

Precision / Recall / F1-score

Cross-validation

Hyperparameter tuning

#### 🔮 Next Steps

Add feature engineering

Optimize Gradient Boosting & XGBoost

Try model stacking