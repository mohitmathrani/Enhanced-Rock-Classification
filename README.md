This project focuses on applying different classification algorithms to a rock dataset to predict rock categories based on 19 different rock features. The dataset includes two files: aggregateRockData.xlsx and norm540.txt. The former contains the rock category number (1 = Igneous, 2 = Metamorphic, 3 = Sedimentary), while the latter includes columns 4 to 22, representing the attributes (features) for prediction.

Project Tasks:

Data Exploration:

Display statistical values for each attribute.
Visualize attribute distributions using histograms.
Identify attributes requiring special treatment.
Data Analysis:

Compute the Pearson Correlation Coefficient (PCC) between attributes.
Generate scatter plots to analyze relationships between attributes and labels.
Data Splitting:

Split data into 60% training, 20% testing, and 20% validation sets.
Verify that test and validation portions are representative of the entire dataset.
Classifier Training and Hyperparameter Tuning:

Train Multinomial Logistic Regression with hyperparameter tuning (C, solver, max iterations).
Train Support Vector Machines with kernel options (C, kernel, degree, gamma).
Train Random Forest classifier with hyperparameter tuning (number of trees, max depth, min samples split, min samples leaf).
Ensemble Modeling:

Combine classifiers into an ensemble.
Evaluate ensemble performance on the validation set.
Test the best performing ensemble on the test set.
Findings:

The project aims to achieve an accuracy above 80% on the validation set.
The performance of each classifier is evaluated using classification accuracy, precision, recall, and F1 score.
Feature importance is analyzed for the Random Forest classifier.
Discussions are provided on the impact of hyperparameters on classifier performance.
The best performing ensemble model is identified and tested on the test set.
Findings and insights from each step of the project are summarized and discussed in detail.
