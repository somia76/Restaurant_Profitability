# Restaurant Menu Items Profitability. 
## This project aimed to Classify the Restaurant Menu Items Profitability (Low - Medium - High).

### Project Overview: 
In this project, I utilized a dataset from Kaggle: https://www.kaggle.com/datasets/rabieelkharoua/predict-restaurant-menu-items-profitability/data. This dataset provides insights into restaurant menu optimization, aiming to maximize profitability by analyzing menu item categories, ingredients, prices, and profitability indicators.

### EDA : 
By Asking various Queation and using charts and plots like pie plot, countplot,...etc to answer them, we could expore the dataset well and get the relation among the features.  


### Data Preprocessing: 
- Drop Duplicated Values.
- Handling Categorical Features: By using one hot encoding and label encoding and other techniques, we could convert the categorical data to numerical one. this step make it easier to building the model.
- Train & Test Split the data.

### Building Models: 
1. Support vector classifier.
2. Random Forest.
3. Gradient Boosting.
4. KNeihbors.


### Results: 
here are the accuracy of each one: 
1. SVC accuracy : 82.53424657534246%.
svc confusion matrix: 
[[  0  29   5]
 [  0 136   7]
 [  0  10 105]] 
2. Random Forest accuracy : 85.61643835616438%.
randomforest confusion matrix: 
[[ 22   7   5]
 [  2 126  15]
 [  6   7 102]]
3. GradientBoosting accuracy : 61.64383561643836%. 
GradientBoostin confusion matrix: 
[[  0  32   2]
 [  0 140   3]
 [  0  75  40]]
4. Kneighbors accuracy : 85.61643835616438%.
Kneighbors confusion matrix: 
[[ 22   6   6]
 [  6 123  14]
 [  3   7 105]]



### Highlight: 
- Random Forest algorithm showed higher accuracy and best Confusion matrix.
  
