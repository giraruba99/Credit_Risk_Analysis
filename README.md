# Credit_Risk_Analysis
Credit risk analysis based on Machine learning is going on here.

## Purpose and overview
- The main purpose of this analysis is to analyze the data at hand collected and based on the result we are going to determine the credit risk. The financial industry is very watchful for uncertainty and wants assurance not to take risky decisions.

- Credit companies put Machine Learning techniques in place to learn detailed data of a credit applicant to gauge the if it is safe/risky to approve the credit application. That is exactly what we are doing in this project.

## Result
- credit Risk Resampling:
1. Oversampling

![Oversampling](https://user-images.githubusercontent.com/89214854/150619785-3c388430-161f-4b1a-a49e-457a46f76ac0.png)


  * The `low-risk` and `high-risk` precision was 100% and 1% respectively.
  * The `low-risk` and `high-risk` recall came back 69% and 66% respectively.
  * And the balanced accuracy score was 68%.

2. Undersamlping

![Undersampling](https://user-images.githubusercontent.com/89214854/150619791-3082cab4-a5ab-4289-9bea-356e076f480b.png)


  * The `low-risk` and `high-risk` precision was 100% and 1% respectively.
  * The `low-risk` and `high-risk` recall came back 48% and 75% respectively.
  * And the balanced accuracy score was 61%.

3. SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/89214854/150619807-646fbc02-a2db-4b4b-84dc-ec0f11807d95.png)

  * The `low-risk` and `high-risk` precision was 100% and 1% respectively.
  * The `low-risk` and `high-risk` recall came back 66% and 71% respectively.
  * And the balanced accuracy score was 69%.

4. Combination (Over and Under) Sampling

![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/89214854/150619826-6a3160e6-caba-4faf-aa64-86ad47ce484a.png)


  * The `low-risk` and `high-risk` precision was 100% and 1% respectively.
  * The `low-risk` and `high-risk` recall came back 46% and 72% respectively.
  * And the balanced accuracy score was 59%.

5. Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/89214854/150619841-ac45ff09-815d-4282-bf0a-b55a06eba9ef.png)

  
  * The `low-risk` and `high-risk` precision was 100% and 4% respectively.
  * The `low-risk` and `high-risk` recall came back 88% and 71% respectively.
  * And the balanced accuracy score was 79%.

6. Easy Ensemble AdaBoost Classifier

  * The `low-risk` and `high-risk` precision was 100% and 9% respectively.
  * The `low-risk` and `high-risk` recall came back 94% and 89% respectively.
  * And the balanced accuracy score was 92%.

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/89214854/150619852-8cd3c15f-1e09-46d6-86c6-ff62e899ff38.png)


- From all six models of machine learning matrixes, we learned:

  * Easy Ensemble AdaBoost Classifier got the best Balanced Accuracy Score-> 92%.
  * Easy Ensemble AdaBoost Classifier got the best Recall score-> 94%

## Conclusion
 
  - Finally, we can conclude that, Easy Ensemble AdaBoost Classifier was the best matrix, with the best possible recall and accuracy rates. 
  - This model precision was also great as it predict the high risk. Thus, this machine learning model looks effective in identifying risks based on the provided data. This is the beauty of machine learning!!!
