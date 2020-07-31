# CA04 – Ensemble Models
## 1. Data Source and Contents
The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset: • Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ] • Number of attributes (Columns): 7 • Number of instances (Rows): 48,842## 2. Finding Optimal Value of a key Hyper-parameter
For Ensemble Models, one of the key hyper-parameter is number of “estimators”.
## 3. Building a Random Forest Model
Using Notebook, and the same data source from CA03, train a Random Forest Model.
Using similar approach of Section 2 above, plot a graph of Accuracy vs. n_estimator.
Use n_estimator values as [50,100,150,200,250,300,350,400,450,500].
## 4. Building AdaBoost, Gradient Boost (classifier) and XGB Model
Repeat the process of Section 3 above for all three models
## 5. Compare Performance
Keep all common Hyper-parameters same for four models (Random Forest, AdaBoost,
Gradient Boost, XGB), run them again and create a performance comparison table
within your code and print
