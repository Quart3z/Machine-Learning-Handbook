## k-Fold Cross Validation
Use to measure the skill of machine learning models, deciding whether the numerical results quantifying hypothesized relationships between variables, are acceptable as description of the data

1. Randomly shuffle the dataset
2. Divide the dataset into K-folds, each fold consists of a unique combination of training and test set
3. For each fold
    - Initialize the model
    - Train the model
    - Evaluate using validation set
    - Save the score and remove trained model
4. Average the evaluation score of all folds

