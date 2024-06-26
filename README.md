# Credit-Card-Fraud-Detection
Overview This project aims to build a model to detect fraudulent credit card transactions. The dataset contains information about credit card transactions, including both legitimate and fraudulent ones, from January 1, 2019, to December 31, 2020. The data covers credit cards of 1000 customers and transactions with 800 merchants.

Dataset
The dataset consists of two files:
fraudTrain.csv: Training dataset
fraudTest.csv: Test dataset

Steps Taken
1. Data Loading and Exploration
Loaded the datasets using pandas.
Displayed the first few rows to understand the structure.
Explored the dataset using info(), describe(), and value counts of the target variable.
2. Data Visualization
Visualized the distribution of the target variable (fraudulent vs. legitimate transactions).
Created a correlation heatmap for numeric features.
Visualized the distribution of transaction amounts for fraud and non-fraud cases.
3. Data Preprocessing
Identified and handled missing values.
Converted categorical variables to numeric using one-hot encoding for low cardinality features and target encoding for high cardinality features.
Ensured the train and test datasets have the same columns.
Separated features and target variable.
4. Feature Scaling
Scaled the features using StandardScaler from scikit-learn.
5. Model Training and Evaluation
Trained Logistic Regression, Decision Tree, and Random Forest models.
Evaluated each model using confusion matrix, classification report, and accuracy score.
6. Model Comparison
Compared the performance of the models using a bar plot.
Results
Logistic Regression



- Accuracy: 0.9999

### Model Comparison
- Accuracy of Logistic Regression: 0.9998
- Accuracy of Decision Tree: 0.9998
- Accuracy of Random Forest: 0.9999

![Model Comparison](model_comparison.png)

## Conclusion
The Random Forest model performed the best with the highest accuracy. All models achieved high accuracy, demonstrating their effectiveness in detecting fraudulent credit card transactions.

## How to Use
1. Clone this repository.
2. Place `fraudTrain.csv` and `fraudTest.csv` in the project directory.
3. Run the Jupyter notebook to preprocess the data, train the models, and visualize the results.

## Files
- `Credit_Card_Fraud_Detection.ipynb`: Jupyter notebook containing the code.
- `fraudTrain.csv`: Training dataset.
- `fraudTest.csv`: Test dataset.
- `model_comparison.png`: Comparison of model accuracies.





