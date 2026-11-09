
DONT HAVE TIME TO READ THE WHOLE README.MD !!!! IN Simple:

Using machine learning to identify fake credit card transactions
and separate them from genuine ones.

In the whole traning and predicting part I try to analyse,
handling numerical column and categorical,
create and use pipeline(to make more easier workflow, ), 
using validations like CV(to get best accuracy by comparing test and train),
than i try many models by using many perameter.
Performance Evaluation: Compared models using ROC-AUC, 
Accuracy, Precision, Recall, 
and F1-Score to identify promising approaches.






***Data Collection & Inspection***
---what i did---
1.Loaded the training and test datasets.

1Checked dataset shape, data types, missing values, duplicates, and target distribution.

3.Exploratory Data Analysis (EDA)

4.Examined feature distributions and relationships.

5.Analyzed class imbalance in the target variable.

6.Data Preprocessing

7.Separated features and target variable.

8.Handled missing values using SimpleImputer.

9.Applied OneHotEncoder to categorical features.

10.Created separate preprocessing pipelines for different models.

11.Train-Validation Strategy

12.Used stratified cross-validation.

13.Implemented 5-Fold Cross-Validation for model comparison.

14.Handling Class Imbalance

15.Experimented with class_weight='balanced'.

16.Used scale_pos_weight for XGBoost.

Model used-

i.)Logistic Regression

ii.)XGBoost

iii.)Random Forest

iv)CatBoostClassifier

v.)LGBMClassifier

vi.)SVM (I tried this but took too much time thats why i didnt continue)

---Model Evaluation---

*Compared models using ROC-AUC, Accuracy, Precision, Recall, and F1-Score.

*Identified ROC-AUC as the primary evaluation metric.

*Model Comparison & Selection

*Compared baseline model performances.

*Selected promising models for further experimentation and optimization.

T*ools & Libraries

*Python, Pandas, NumPy, Scikit-learn, XGBoost, JupyterLab.

----Competition---

**Kaggle – Playground Series S6E11: Credit Card Fraud Detection**
