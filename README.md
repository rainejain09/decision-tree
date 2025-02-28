## Overview
This project applies data preprocessing techniques to the *Social_Network_Ads* dataset and trains a *Decision Tree Classifier* to predict whether a user purchases a product based on age and estimated salary.

## Steps Involved
1. *Load Dataset*: The dataset is loaded using Pandas.
2. *Data Preprocessing*:
   - Extract relevant features (Age & EstimatedSalary) and target variable (Purchased).
   - Split the dataset into *training* and *testing* sets.
   - Apply *feature scaling* using StandardScaler.
3. *Train Decision Tree Classifier*:
   - Use entropy as the criterion for classification.
   - Fit the model on the training data.
4. *Evaluate Model*:
   - Make predictions on the test set.
   - Calculate accuracy using accuracy_score.
5. *Visualize Decision Tree*:
   - Display the decision tree structure using plot_tree.

## Dependencies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## How to Run
1. Ensure the dataset *Social_Network_Ads.csv* is in the working directory.
2. Run the Python script to preprocess data, train the model, evaluate performance, and visualize the tree.
3. Check the accuracy and the plotted decision tree.

## Output
- *Accuracy Score* displayed in percentage.
- *Decision Tree Visualization* showing the decision-making process.
