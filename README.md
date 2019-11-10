# Quora-Question-Pair-solution-
My solution to <a href="https://www.kaggle.com/c/quora-question-pairs/overview/description"> Quora Question Pair kaggle contest </a> using  Logistic regression and Linear Svm and gbdt model.

Results obtained:
+-----------------------------+-------------------------------------------------------+----------+
|            Model            |                 Hyper-parameter(alpha)                | Log Loss |
+-----------------------------+-------------------------------------------------------+----------+
| Logistic Regression with L2 |                         10*-6                         |  0.5689  |
| Logistic Regression with L1 |                         10*-6                         |  0.5596  |
|      Linear SVM with L1     |                         0.0001                        |  0.5948  |
|      Linear SVM with L2     |                         10*-5                         |  0.5697  |
|           XGBoost           | [n_estimators=118,max_depth=5,gamma=10,subsample=0.8] |  0.4163  |
+-----------------------------+-------------------------------------------------------+----------+
XGBoost Model got the lowest Log loss of 0.4163 

