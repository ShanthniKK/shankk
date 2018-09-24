                                                         PREDICTING ADULT INCOME

For predicting an adult income , we use corresponding data set and algorithm used is Two Class Boosted Decision Tree. 
Two Class Boosted Decision Tree:
•	A boosted decision tree is an ensemble learning method in which the second tree corrects for the errors of the first tree, the third tree corrects for the errors of the first and second trees, and so forth. 
•	Predictions are based on the entire ensemble of trees together that makes the prediction. 
•	The result is the average of the result of each decision tree. 

EXPERIMENTAL SETUP:
1. Open blank experiment and name it.
2. Drop pre-imported data “Adult Senses income”  from  the saved datasets.
3. Select only the required fields from the dataset for the prediction using project column functions.
4. Hook up the dataset and project column function and launch it by selecting only required fields.
5. Drag and drop the Two Class Boosted Decision Tree from the Machine Learning section.
6.use split data function to split out data. we split our data into 0.8(for training the model) and 0.2(for testing). 
7. use the Train Model function and connect it to the Two Class Boosted Decision Tree and split data.
8. Run the Train Model and launch column selector. In this case it is income.
9.To see how well our model is performing use Score Model. Connect Score model and Train model.
10. Connect Evaluate model and Score model to visualize the evaluate model.
11. To publish the model as Web service create another experiment. Here connect Web service function and score model and connect score model and web service output.
12. Before executing remove the income field from the data set.
 

 

 





