# Project_3_Fintech_logistic_regression

The attached Jupyter notebook is about a dataset on a Fintech company customer dataset classification using Logistic Regression and Ridge Regularization. The notebook has 7 sections.

1.	Problem Statement: Understanding the classification problem and the end goal of the project.
2.	Importing the data: The jupyter notebook was run on Google Colaboratory and this section deals with importing the necessary files needed for smoothly running the notebook.
3.	Exploratory Data Analysis and Data Visualization: This section deals with the description of the data fields, plotting histogram of the data, bar charts of the correlation between fields and the response variable (‘enrolled’), and a correlation matrix.
4.	Feature engineering: To test the model, a cut-off time of 2 days is decided after a user first installs the app, i.e., we will wait for 2 days after the user installs it to see if the model correctly predicted if the user will enroll in the paid version or not. Also, all the top_screens were created into their own columns and grouped by category (to avoid correlation)
5.	Data Preprocessing for Model Building: Splitting the data into training & testing and normalizing the data.
6.	Model Building: A logistic regression model with L2 penalty was trained on the data. 10-fold CV was applied to test for overfitting.
7.	Conclusion: Results of the model.
