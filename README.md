# Classifying Breast Cancer Patients Using Multiclass Multivariate Logistic Regression Model
Logisitic regression helps us classify a dependent variable. In this project, we will use this technique to classify breast cancer patients as having moderately malignant(1), malignant(2), or extremly malignant(3) tumor. We'll use **one-versus-all appraoch** in our multiclass logistic regression model.

We will use [data](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer) having 9 categorical features. We'll engineer new features in this project to train and test our logistic regression model apart from converting categorical features to numeric ones.

Remember, the probability of successfully predicting the extent of breast cancer malignancy with three classes is 33.3%. This is because we have to randomly pick 1 out of 3 options. If our model gives us results better than this, it means the logistic regression has improved our capability of classifying the patient with respect to malignancy of the disease.

**The Jupyter Notebook (code) of this project can be found [here.](https://nbviewer.org/github/hussam95/Portfolio/blob/eab9e46de40922dfe94f75c541853b435c09b5d5/Logistic_Regression_Breast_Cancer_Classification%28Multiclass%29.ipynb)**

As a part of the experiment, I used another classification model, **Decision Tree**, on the same dataset with a view to compare and contrast its performance with logistic regression model. You can view the Jupyter Notebook of this experiment [here.](https://nbviewer.org/github/hussam95/Portfolio/blob/92e48b200630dff8da5100105a04766b477a6150/Decision_Tree_and_Logistic_Regression_Comparison.ipynb)
