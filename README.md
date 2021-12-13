# Classifying Breast Cancer Patients Using Multiclass Multivariate Logistic Regression Model
Logisitic regression helps us classify a dependent variable. In this project, we will use this technique to classify breast cancer patients as having moderately malignant(1), malignant(2), or extremly malignant(3) tumor. We'll use **one-versus-all appraoch** in our multiclass logistic regression model.

We will use [data](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer) having 9 categorical features. We'll engineer new features in this project to train and test our logistic regression model apart from converting categorical features to numeric ones.

Remember, the probability of successfully predicting the extent of breast cancer malignancy with three classes is 33.3%. This is because we have to randomly pick 1 out of 3 options. If our model gives us results better than this, it means the logistic regression has improved our capability of classifying the patient with respect to malignancy of the disease.

**The Jupyter Notebook (code) of this project can be found [here.](https://nbviewer.org/github/hussam95/Portfolio/blob/eab9e46de40922dfe94f75c541853b435c09b5d5/Logistic_Regression_Breast_Cancer_Classification%28Multiclass%29.ipynb)**

As a part of the experiment, I further tried 3 different ML models on the dataset:

- Simple Decision Tree
- Support Vector Machine with RBF kernel
- Ensembled Decision Tree/Random Forest

The overall accuracy for all these models (with near optimal parameters) seemed to converge in high 40s range. Our models generally are as good as the data they get. And since we have tried different classification models to rule out the possibility of inherent limitations of a single model, it only makes sense to say that we acheived the best we could given the data we had.

Moreover, it is also important to highlight that different models classify different target classes with varying accuracies. And depending upon which class we want to predict the best, we can select a model accordingly. 

**Click [here](https://nbviewer.org/github/hussam95/Portfolio/blob/88428c695c0bff36d5b38638a6766121cf54930a/4%20models%20breast%20cancer.ipynb) to view Jupyter Notebook (code) of this experiment.**

**P.S: This is a self initiated project with an aim to understand, compare, and contrast high level working of different classification models.** 
