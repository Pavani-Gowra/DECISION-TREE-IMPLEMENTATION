# DECISION-TREE-IMPLEMENTATION

COMPANY : CODTECH IT SOLUTIONS

NAME : G PAVANI

INTERN ID : CT08DK681

DOMAIN : Machine Learning

DURATION : 8 weeks

MENTOR : NEELA SANTHOSH

*DESCRIPTION OF THE TASK*

Task 1: Build and Visualize a Decision Tree Model Using Scikit-learn

As part of my Machine Learning internship at CodTech IT Solutions, I completed Task 1, which involved building and visualizing a Decision Tree Classifier using Scikit-learn, one of the most widely used Python libraries for machine learning. The primary goal of this task was to select a dataset, train a Decision Tree model on it, and provide clear visualizations and analysis to understand how the model classifies or predicts outcomes.

**Tools and Technologies Used
  Programming Language: Python
  Python was the core language used due to its simplicity and extensive support for data science and machine learning tasks.

**Libraries:

  1.Scikit-learn: Used for implementing the Decision Tree classifier and splitting the dataset.

 2.Pandas: For loading and preprocessing the dataset.

 3.NumPy: For numerical computations.

 4.Matplotlib and Seaborn: For data visualization and exploring feature distributions.

 5.Graphviz and plot_tree from Scikit-learn: For visualizing the decision tree structure.

**Environment:  

  Jupyter Notebook was used to write, execute, and document the entire code interactively.

**Dataset Selection
For this task, I selected the Iris dataset, a classic dataset used in classification tasks. It contains 150 records of iris flowers, each described by four features:

->  Sepal length

->Sepal width

->Petal length

->Petal width

The target variable is the species of the flower (Setosa, Versicolor, or Virginica). The dataset is ideal for understanding how a decision tree splits data based on feature values to classify different categories.

**Steps to Perform the Task

1.Data Loading and Exploration:
Loaded the Iris dataset using Scikit-learn’s built-in load_iris() method.
Converted it into a Pandas DataFrame to make it easier to explore and manipulate.
Visualized the distribution of classes and features using Seaborn’s pairplot and boxplots to understand relationships.

2.Preprocessing:
Since the Iris dataset is already clean, minimal preprocessing was required.
Checked for null values and ensured data types were appropriate.
Split the dataset into training and testing sets using train_test_split() from Scikit-learn (typically 80% training and 20% testing).

3.Model Building:
Used DecisionTreeClassifier() from Scikit-learn.
Trained the model on the training dataset using the .fit() method.

4.Model Prediction and Evaluation:
Used the .predict() method to make predictions on the test set.
Evaluated the model using metrics such as accuracy, confusion matrix, and classification report.
Accuracy was computed using accuracy_score() from Scikit-learn.

5.Model Visualization:
Visualized the decision tree using plot_tree() which graphically represents how the model makes decisions.
Displayed feature importance scores to understand which features the model relied on most.

6.Model Interpretation:
Analyzed the tree splits to see how decisions were made.
Observed how the model classified different species based on petal and sepal measurements.

**Learning Outcomes :

Understood the concept of decision trees, how they recursively split data, and how overfitting can occur if the tree is too deep.

Learned how to visualize decision paths which makes it easier to explain the model's decisions.

Gained practical experience in model training, testing, and evaluation using real-world tools.

Learned how to interpret model outputs like feature importance and how they relate to predictions.

Conclusion :

This task gave me hands-on experience with one of the foundational machine learning algorithms—Decision Trees. I gained valuable skills in data preprocessing, model building, and visualization. The ability to interpret and explain the decision-making process of the model was one of the key highlights of this task. It set a strong foundation for more complex models and future tasks in this internship.
