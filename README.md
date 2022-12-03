# Cardiovascular-Risk-Prediction
Supervised ML (Classification)
<img src="https://www.genengnews.com/wp-content/uploads/2021/12/GettyImages-1293132839-scaled-e1640204438522.jpg " width="800" height="500"/>

Heart disease is one the major cause of moribity and mortality globally. A heart attack happens when the flow of oxygen-rich blood to a section of heart muscle suddenly becomes blocked and the heart can’t get oxygen. If blood flow isn’t restored quickly, the section of heart muscle begins to die.

Doctors and Scientists across the globe have started to look into Machine Learning Techniques to develop screening tools.

## Problem statement:

In this project, we shall be giving you a walk through on the development of a screening tool for predicting whether a patient has a 10-year risk of developing coronary heart disease (CHD) based on their present health conditions using different Machine Learning Techniques.

## Approach:

Here first we imported data set and performed EDA where we got valuable insights and further we Encoded the Categorical Columns, Feature scaling and fitting into the models.  At first we tried with basic logistic regression but soon realized we will need a much more complex model and so we then used a Decision Tree Classifier, Random Forest Classifier, XGB Model Classifier, KNN Classifier and SVM Classifier compared the results for improvement in the model fitting to understand the better results of the model as well as the metrics.

## Conclusion: 

The analysis is done with Cardio-Vascular data. Six classification techniques Logistic Regression, Decision Tree, Random Forest, XG Boosting, K Nearest Neighbors and Support Vector Machines are used to predict the Risk here. This statistical data analysis shows interesting outcomes in prediction methods and also in an exploratory data analysis.

## The experimental results show that:

* In the given dataset we observe that Coronary heart disease increases from age 51 to 67 then decreases.
* We draw the count plot and observe that no. of male heart patients is more than female and also notice that male get early age heart diseases as compared to females.
* We observe no. of heart patients who smoke more than as compared to those who won’t and also notice that those who smoke get early heart disease as compared to those who won’t.
* We draw the bar plot and observe that no. of cigsperday taken by male is more than female. So, male heart patients are more as compared to females.
* We draw the boxplot and observe that female BMI (The BMI is defined as the body mass divided by the square of the body height, and is expressed in units of kg/m²) is more than male BMI. that’s leads to OVERWEIGHT and So, female CHD patients is more than male CHD patients.
* We draw the boxplot and observe that female Cholesterol is more than male Cholesterol.  that’s leads to OVERWEIGHT and So, in that case also female CHD patients is more than male CHD patients.
* We Observe that Female heart disease patients has more Heart Rate as compared to male heart disease patients.
* We also observe that male heart disease patients have more glucose level as compared to female heart disease patients.
* In the Models Evaluation Table (Testing set) our auc-roc score is more 0.80 except Logistic regression and Decision Tree. So we can say that our model predicted the classes in a good manner.
* XGBClassifier is performing well which has the best Recall, Precision, F1-Score and Accuracy Score.

