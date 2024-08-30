# Diabetes-Prediction-ML
## Dataset Description
Diabetes is a group of metabolic disorders characterized by high blood sugar levels over a prolonged period. If untreated, it can lead to serious complications such as cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

![Diabetes-prediction-using-Machine-Learning-1024x768](https://github.com/user-attachments/assets/ca82e62f-dd72-4dbf-9950-f70287f4072e)

Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Symptoms of high blood sugar include frequent urination, increased thirst, and increased hunger. If left untreated, diabetes can cause many complications. Acute complications can include diabetic ketoacidosis, hyperosmolar hyperglycemic state, or death. Serious long-term complications include cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

# Objective
We will try to build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?

# Details about the dataset
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.


### Classifiers and Their Accuracy Scores
We evaluated several machine learning classifiers on the dataset to determine which model performs best. Below are the classifiers and their corresponding accuracy scores:

| Classifier               | Accuracy Score         |
|--------------------------|------------------------|
| Logistic Regression       | 0.8759680961738527     |
| K-Nearest Neighbors (KNN) | 0.9167148306554156     |
| Decision Tree             | 0.9396601548953878     |
| Random Forest             | 0.960524794821408      |
| SGD Classifier            | 0.8763148768928447     |
| Gradient Boosting         | 0.8938850999884407     |
| CatBoost Classifier       | 0.9497167957461565     |
| XGBoost Classifier        | 0.9415096520633452     |
| LGBM Classifier           | 0.9063692058721535     |
| AdaBoost Classifier       | 0.9000693561437985     |
| Bagging Classifier        | 0.956652410125997      |

## Results
After evaluating various machine learning models, the **Random Forest Classifier** emerged as the best-performing model with an accuracy score of **0.9605**. This indicates that the Random Forest model is the most reliable in predicting whether a patient has diabetes based on the diagnostic features available in the dataset.

![4932629a-c0f3-457f-98a2-37be841edbde](https://github.com/user-attachments/assets/45b89a87-3156-4ab2-ac55-c3c43da32a7e)

Other models that performed well include:
- **Bagging Classifier** with an accuracy score of **0.9567**.
- **CatBoost Classifier** with an accuracy score of **0.9497**.
- **XGBoost Classifier** with an accuracy score of **0.9415**.

These results suggest that ensemble methods like Random Forest, Bagging, and Boosting (CatBoost, XGBoost) are particularly effective for this classification problem.

## Conclusion
The Random Forest Classifier is recommended for predicting diabetes due to its high accuracy. However, other ensemble methods such as Bagging and Boosting also show strong performance and could be considered depending on the specific requirements and constraints of the deployment environment.

---

This results section provides a clear summary of the findings, helping to highlight the best-performing models and draw conclusions from the analysis.

