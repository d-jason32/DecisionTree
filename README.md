# Decision Tree Assignment

## Implementation

1. Node class that represents a decision node in the tree.
2. Each node stores a feature used for splitting, the threshold value for splitting, a reference to the left and right child nodes, and a label for leaf nodes.
3. DecisionTree class with fit(X,y), _grow_tree, best split, entropy and predict.
4. Pre pruning and post pruning
5. Load the breast cancer data set with preprocessing and split into training and test sets.

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
