# Supervised_ML_Challenge
## Prediction: I beleive that the Random Forest Classifier will give better results that the Logistic Regression model:
* RFC is suitable in our case as it does not focus on interpretability.
* In addition, the main focus of the project would benefit more from trained decision trees that lead to the prediction.
* Finally, RFC adds additional randomness to the model while growing the decision trees, which results in a wide diversity that results a better model.

## Conclusion
* The RFC testing model score of 0.99438 is higher than the Logistic Regression testing model score of 0.99381
* The above numbers do explain my prediction. As the model is looking at credit risk evaluation model, the decision tree usage would be a great benefit.
* The RFC forest had a total of 50 trees that the model averaged to get the model score.
* Both models had a test score > train score which is not best practice. This is where i had to add hyper-parameters to both models to make it a more normal model where the train model score is higher than the test model score