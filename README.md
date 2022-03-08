<b>Kyphosis Prediction</b>

Kyphosis is  an abnormally excessive convex curvature of the spine. 
The dataset used in this project contains data whether the state of Kyphosis is present / absent after the operation , Age of the person (in months), the number is a number of vertebrae involved in the operation and the start is the no. of first or the top most vertebrae that was operated on.

Applied decision tree and random forest algorithm on the  data set to predict whether the condition of Kyphosis is present or absent in an individual and on comparing the output result of both model, Random Forest yields better result. 

<pre>
➡️Import all the essential libraries
➡️ Import the dataset
➡️ Check the information of dataset like no of entries, no of columns
➡️ Data analysis and visualisatiion using seaborn and matplotlib 
➡️ Split the data in training and test set
➡️ Import DecisionTreeClassifier from sklearn.tree for classificaion
➡️ Create a model 'dtree' for DecisionTreeClassifier
➡️ Fit the trained data in model
➡️ Predict the values on passing the test data set to model 'dtree'
➡️ From sklearn.metrics import classification_report and confusion_matrix.
➡️ Print the output values
➡️ from sklearn.ensemble import RandomForestClassifier
➡️ Create a RandomForestClassifier model 'rfc' and provide estimators=100
➡️ Fit the training data set in model
➡️ Predict the output of test data by passing in the model
➡️ From sklearn.metrics import classification_report and confusion_matrix.
➡️ Print the output values
➡️ On comparing the output values, we observe that the random forest yields better result than a single decision tree.
</pre>
