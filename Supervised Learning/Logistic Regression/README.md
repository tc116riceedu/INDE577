# **Logistic Regression**

This project demonstrates a simple implementation of **Logistic Regression** using the **Student Performance Dataset** from the UCI Machine Learning Repository. The goal is to predict whether a student will pass or fail based on factors like study time, past failures, and absences.



## **Overview**

- Uses a supervised learning algorithm (**Logistic Regression**)
- Dataset: `student-por.csv` from UCI Machine Learning Repository
- Predicts student performance as **Pass (1)** or **Fail (0)** based on `G3` (final grade)
- Preprocesses categorical features and encodes them for model training
- Evaluates model performance using accuracy, classification report, and confusion matrix



## **Files Included**

- `student-por.csv` — Dataset used for training and testing  
- `Student_Logistic_Regression.ipynb` — Main Jupyter notebook with code, explanations, graphs, and model evaluation  
- `README.md` — This file  



## **Technologies Used**

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  



## **Dataset Source**

UCI Machine Learning Repository:  
[https://archive.ics.uci.edu/ml/datasets/student+performance](https://archive.ics.uci.edu/ml/datasets/student+performance)



## **What’s Covered**

- Data cleaning and preprocessing  
- Feature engineering (binary classification based on grade)  
- Label encoding for categorical variables  
- Binary logistic regression implementation using `sklearn.linear_model.LogisticRegression`  
- Probability estimation using sigmoid function  
- Model evaluation with:
  - Accuracy score  
  - Classification report (Precision, Recall, F1-Score)  
  - Confusion matrix and its visualization  



## **References**

1. **Logistic Regression – Concept and Formula**  
   GeeksforGeeks. *ML | Logistic Regression*  
   [https://www.geeksforgeeks.org/implementation-of-logistic-regression-using-python/](https://www.geeksforgeeks.org/implementation-of-logistic-regression-using-python/)  

2. **Scikit-learn Documentation – Logistic Regression**  
   Scikit-learn Developers  
   [https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

3. **Understanding Precision, Recall, and F1-Score**  
   Towards Data Science  
   [https://towardsdatascience.com/precision-recall-and-f1-score-8577a9917e47](https://towardsdatascience.com/precision-recall-and-f1-score-8577a9917e47)

4. **Dataset Source – Student Performance Data**  
   UCI Machine Learning Repository  
   [https://archive.ics.uci.edu/ml/datasets/student+performance](https://archive.ics.uci.edu/ml/datasets/student+performance)



### Image Credit

- **Logistic Function Diagram**  
  Source: Dataaspirant | How Logistic Regression Works 
  [https://dataaspirant.com/how-logistic-regression-model-works//](https://dataaspirant.com/how-logistic-regression-model-works/)


