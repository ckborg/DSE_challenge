# DSE challenge: Predicting formation of binary compounds with machine learning 

## Contents:

1. parse_csv.ipynb = Converts training and test data csvs to "ML-ready" state.

2. modeling.ipynb = Trains a random forest model on the data.
- example feautrization method from [matminer.](https://github.com/hackingmaterials/matminer_examples/blob/master/matminer_examples/machine_learning-nb/bulk_modulus.ipynb)
- example of PR curve method from [sklearn](https://scikit-learn.org/stable/auto_examples/model_selection/plot_precision_recall.html)

3. reformat_predictions.ipynb = Converts the classifier predictions back into the original vector format.