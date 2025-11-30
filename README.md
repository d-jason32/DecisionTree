# Decision Tree Assignment

Instructions
Part 1: Implementing the Decision Tree

    Create a Node class that represents a decision node in the tree. Each node should store:
        The feature used for splitting
        The threshold value for splitting
        References to the left and right child nodes
        The class label if it is a leaf node

    Create a DecisionTree class with the following methods:
        fit(X, y): Trains the decision tree using a given dataset.
        _grow_tree(X, y, depth): Recursively splits the dataset to build the tree.
        _best_split(X, y): Determines the best feature and threshold for splitting.
        _entropy(y): Computes entropy to measure information gain.
        predict(X): Predicts labels for given inputs by traversing the tree.

    Implement pruning techniques to avoid overfitting:
        Pre-pruning: Stop growing the tree if a node has fewer than a minimum number of samples.
        Post-pruning: Prune the tree after training by evaluating the model’s performance on a validation set.

Part 2: Working with a Different Dataset

    Choose a dataset other than the Iris dataset (e.g., Titanic dataset, Heart Disease dataset, or any classification dataset from sklearn.datasets or Kaggle).
    Preprocess the dataset (handle missing values, encode categorical variables, etc.).
    Split the dataset into training and testing sets.

Part 3: Evaluating the Model

    Train your decision tree model using the training set.
    Apply pruning techniques and compare results with and without pruning.
    Evaluate the model using accuracy, precision, recall, and F1-score.

Part 4: Analysis and Discussion

    Compare your decision tree’s performance with sklearn.tree.DecisionTreeClassifier.
    Analyze the impact of pruning techniques and explain how they affected accuracy and overfitting.
    Suggest improvements to enhance the model's performance.

Deliverables

    Python script (.py) containing:
        The implemented Decision Tree class
        Code for data preprocessing, training, and evaluation
        Implementation of pruning techniques
    A brief report (1-2 pages) in .pdf format summarizing:
        The dataset and preprocessing steps
        The impact of pruning on decision tree performance
        Comparison with sklearn.tree.DecisionTreeClassifier
        Insights and possible improvements

Bonus (Optional):

    Implement Cross-Validation to optimize tree hyperparameters.
    Implement Feature Importance Analysis to understand which features contribute most to predictions.

