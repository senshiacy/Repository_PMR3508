# Adult Dataset Classifier Models

This project intends to explore data analysis about [Adult dataset](https://archive.ics.uci.edu/dataset/2/adult) and predict if the anual richness of a person will be over 50K, basing on other attributes (such as age, workclass, education and marital-status).

## Methodology and Results

Firstly, we focused on applying exploratory data analysis and visualization over the dataset in order to obtain statistical patterns and other insights, using Pandas, Matplotlib, Seaborn and Numpy. After that, we dealt with outliers, missing values, encoding forms and standard scalers to improve the model's performance.

Moreover, we applied feature engineering and correlation matrix to verify which attributes was able to be discarded and reduce data dimensionality.

Furthermore, we tried model classifiers using KNN, SVM, Logistic Regression, Random Forest and Ada Boost. In order to obtain good hyperparameters, cross-validation and grid search was requested.

Finally, we got experience with metrics to evalute each model, like confusion matrix, accuracy, precision, recall and f1 score.

Basing on test dataset, the best model, Ada Boost, got **86.72%** in accuracy, **83.01%** in precision, **78.49%** in recall and **80.36%** in F1 score.