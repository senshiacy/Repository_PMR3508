# MNIST Dataset Classifier Model

This project intends to explore data analysis about [MNIST dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) and predict a label (a number between 0 to 9) for a handwritting numberic image.

## Methodology and Results

Firstly, we focused on applying exploratory data analysis and visualization over the dataset in order to obtain statistical patterns and other insights, using Pandas, Matplotlib, Seaborn and Numpy. After that, we dealt with outliers, missing values, encoding forms and standard scalers to improve the model's performance.

Moreover, we applied feature engineering and correlation matrix to verify which attributes was able to be discarded and reduce data dimensionality.

Furthermore, we modeled a classifier using neural networks from scikit-learn. In order to obtain good hyperparameters, cross-validation and grid search was requested.

Finally, we got experience with metrics to evalute each model, like confusion matrix, accuracy, precision, recall and f1 score, besides loss curve to interpret overfitting and underfitting.

Basing on test dataset, the best model, got **97.57%** in accuracy, **97.55%** in precision, **97.55%** in recall and **97.55%** in F1 score.