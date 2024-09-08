# Ethereum-Transactions-Fraud-Detection

Ethereum Fraud Transaction Prediction

Project Description:
This project aims to develop a machine learning model capable of accurately predicting fraudulent transactions on the Ethereum blockchain. By analyzing various transaction features, the model aims to identify suspicious patterns and mitigate financial losses.

Technologies:

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Data:

A dataset containing 50 columns of Ethereum transaction data.
Methodology:

Exploratory Data Analysis (EDA):

Conducted correlation analysis to identify relationships between features.
Utilized medium imputation to handle missing values.
Dropped columns with low variance or minimal predictive power.
Generated box plots to visualize feature distributions and identify outliers.
Class Imbalance Handling:

Applied the Synthetic Minority Over-sampling Technique (SMOTE) to address the class imbalance in the target variable (fraudulent vs. non-fraudulent transactions).
Model Development:

Implemented three classification models: Logistic Regression, Random Forest Classifier, and XGB Classifier.
Trained each model on the preprocessed dataset.
Hyperparameter Tuning:

Employed GridSearchCV to optimize the hyperparameters of each model, improving performance and generalization.
Evaluation:

Assessed model performance using precision, a metric that measures the proportion of correctly predicted positive instances.
Results:

Achieved precision scores of 87%, 91%, and 96% for Logistic Regression, Random Forest Classifier, and XGB Classifier, respectively.
Demonstrated the effectiveness of the selected models and hyperparameter tuning in predicting fraudulent Ethereum transactions.
Future Work:

Explore other classification algorithms (e.g., Support Vector Machines, Neural Networks) for potential improvements.
Incorporate additional features or data sources to enhance model accuracy.
Investigate techniques to reduce false positives and false negatives.
