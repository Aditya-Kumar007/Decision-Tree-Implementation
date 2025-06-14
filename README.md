# Decision-Tree-Implementation
# Company :- CODTECH IT SOLUTIONS
# Name :- Aditya Kumar
# Inter ID :- CT04DN879
# Domain :- Machine Learning
# Duration :- 4 Weeks
# Mentor :- Neela Santosh
# TASK DESCRIPTION
This project explores the development and visualization of a Decision Tree Classifier using the Scikit-Learn library in Python. The dataset employed for training the model is the widely recognized Iris dataset, an essential resource in machine learning. It contains four key features—sepal length, sepal width, petal length, and petal width—that help distinguish between three iris flower species: Setosa, Versicolor, and Virginica. The objective is to build a model capable of accurately classifying new iris samples based on these characteristics.

Data Handling and Preparation
To begin, the necessary libraries are imported, including pandas and numpy for data manipulation, matplotlib for visualization, and Scikit-Learn modules such as DecisionTreeClassifier, plot_tree, and evaluation metrics. The load_iris() function from Scikit-Learn retrieves the dataset, extracting its feature values and target labels for subsequent processing.

The dataset is then segmented into training and testing subsets using the train_test_split() function. This ensures that the model is trained on a portion of the data while being evaluated on unseen examples, thereby simulating real-world predictive capabilities.

Building the Decision Tree Model
A Decision Tree Classifier is constructed utilizing DecisionTreeClassifier(). The splitting criteria are determined using the Gini index, specified by setting the criterion parameter to 'gini'. Additionally, the depth of the tree is restricted to three levels (max_depth=3) to enhance visual clarity and prevent excessive complexity or overfitting. Once trained with the fit() method, the model generates predictions on the test data.

Decision Tree Visualization
A crucial aspect of this implementation is the graphical representation of the trained Decision Tree using the plot_tree() function. This visualization vividly illustrates the decision-making process, showing feature threshold-based splits at each node. Each node serves as a decision checkpoint, while the leaves indicate final classifications. To improve interpretability, color coding, feature labels, and class names are integrated into the diagram. Moreover, the export_text() function generates a textual depiction of the tree’s rules, offering an easily comprehensible explanation of its logic.

Model Evaluation and Feature Importance
To assess the model’s predictive ability, performance metrics such as accuracy, a classification report, and a confusion matrix are utilized. These metrics provide insights into how well the classifier distinguishes between iris species. Furthermore, feature importance analysis is conducted through a horizontal bar chart, highlighting the most influential attributes in the model’s decision-making process.
# Output
Output.png
