# CA03 – Decision Tree Algorithm
## Background
The dataset is obtained from the Census Bureau and represents salaries of people
along with seven demographic variables. The following is a description of our dataset:
• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
• Number of attributes (Columns): 7
• Number of instances (Rows): 48,842
## Instruction
### Step 1 - Getting Started
The data is provided in a .csv file. Download the data and other files for this
assignment from the following GitHub link. There is a column indicating the rows to be
used as “Training Data” and “Testing Data”. You can split the files based on this column
value.
https://github.com/ArinB/MSBA-CA-03-Decision-Trees
### Step 2 - Data Quality Analysis 
Perform a Data Quality Analysis to find missing values, outliers, NaNs etc.Then, display descriptive statistics of each column. Finally, Perform necessary data cleansing and transformation based on your observations from the data quality analysis
### Step 3 - Exploratory Data Analysis
Perform EDA of the income group with respect to the seven explanatory variables and display graphical representations
### Step 4 - Build Decision Tree Classifier Models
Use “DecisionTreeClassifier” algorithm from scikit learn. Find details of sklearn tree
algorithm below. Scitkit Learn implements an optimized version of CART algorithm and
can be used for binary class as well as multi-class classifications. It can be used for
classification, as well as regression
### Step 5 - Evaluate Decision Tree Performance
Calculate and display the following Confusion Matrix, Accuracy, Precision, Recall, F1 Score, AUC Value, ROC Curve in the notebook. 
### Step 6 - Tune Decision Tree Performance
Try varying FOUR of the hyperparameters manually, as per the following table, and
train / score your model for each set of these hyperparameters. Record your Tree’s
performance with respect to each of these sets of hyperparameters in the Model
Performance section of the following table.
