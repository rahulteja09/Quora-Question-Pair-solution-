# Quora-Question-Pair-solution-
My solution to <a href="https://www.kaggle.com/c/quora-question-pairs/overview/description"> Quora Question Pair kaggle contest </a> using  Logistic regression and Linear Svm and gbdt model.

Results obtained:
<table style="width:100%">
<tr>
    <th>Model</th>
    <th>Hyper-parameter</th> 
    <th>Log Loss</th>
  </tr>
  <tr>
    <td>Logistic Regression with L2</td>
    <td>  10*-6   </td> 
    <td> 0.5689 </td>
  </tr>
  <tr>
    <td>Logistic Regression with L1 </td>
    <td>10*-6 </td> 
    <td> 0.5596</td>
  </tr>
  <tr>
    <td> Linear SVM with L1  </td>
    <td>  0.0001  </td> 
    <td>0.5948 </td>
  </tr>
  <tr>
    <td> Linear SVM with L2  </td>
    <td>  10*-5  </td> 
    <td>0.5697 </td>
  </tr>
  <tr>
    <td>  XGBoost   </td>
    <td>  [n_estimators=118,max_depth=5,gamma=10,subsample=0.8]   </td> 
    <td> 0.4163 </td>
  </tr>
  
</table>
XGBoost Model got the lowest Log loss of 0.4163 

