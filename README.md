# creditCardFraud
Credit card fraud detection project. Data is sourced from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud and can be publicly downloaded.

Data preprocessing
- Performed feature scaling and data balancing by undersampling
- Used correlation matrix to perform feature selection

Data Analysis
- Outlier detection and removal
- Clustering and dimensionality reduction
- Optimized hyperparameter with gridSearch
- Performed undersampling using nearMiss technique during cross-validation
- Plotted and compared ROC and learning curves for the various classifiers used

Testing
- Applied confusion matrix and utilized classification_report to determine best classifier
