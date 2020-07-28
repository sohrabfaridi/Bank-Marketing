# Bank-Marketing
A kaggle competition for data science.
<p>
After doing some visualization and preprocessing, I splitted data in two set: train and test and I did crossvalidation over all models and used test set just one time after selecting the best model.<br> 
For this binary classification I tried diffrent machine learning algorithms: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting.<br>
Since our data is imbalanced and predicting True positive is important, acuuracy score was not useful so I selected : "average-precision" to evaluate models. And at last after selecting best model, for selecting best threshold, The best way was to compare "macro-averages" on train-set.<br>
For the last step after picking model and best threshold all without using test-set, The model will be evaluate on the test set.
</p>
