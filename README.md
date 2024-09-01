Question 1:
Methodology: Use Pandas functions to explore and analyze the dataset.

Assumptions:
The dataset is well-formatted and follows a standard format for the Iris datase
Analysis:

Examine the first five rows to understand the dataset's structure.
2. Converting DataFrame to NumPy Array

Methodology:

Convert the DataFrame to a NumPy array.
Split the array into features and labels.
Assumptions:

The last column is the label and the first four columns are features.
Analysis:

The shapes and unique labels give insights into the dataset structure.
3. Visualization and Dimensionality Reduction

Methodology:

Use scatter plots to visualize pairwise attribute relationships.
Apply t-SNE and PCA for dimensionality reduction and visualization.
Assumptions:

The features are suitable for visualization and dimensionality reduction.
Analysis:

Pairwise scatter plots help in understanding class separability.
t-SNE and PCA reveal how well classes are separated in reduced dimensions
4. Histogram of Each Attribute

Methodology:

Plot histograms for each feature using matplotlib.
Assumptions:

Features are numeric and can be plotted directly.
Analysis:

Histograms reveal the distribution of each feature and can indicate skewness or outliers.
5. Compute Statistics

Methodology:

Use NumPy to compute statistics for the features.
Assumptions:

Features are numeric.
Question 2: Clustering using K-Means Algorithm
Methodology:

Implement k-means clustering from scratch.
Evaluate clustering performance using Precision, Recall, and F-score.
Assumptions:

The dataset is well-formed and contains 300 features per word.
Plots and Results:

Implement k-means clustering:

Implement Euclidean Distance and Cosine Similarity-based clustering algorithms.
Evaluate performance for k=1 to k=10:

Compute Precision, Recall, and F-score.
Question 3: Linear Regression
Methodology:

Implement and test a custom regression model.
Compare with LinearRegression from sklearn.
Assumptions:

The dataset is well-structured with features and a target variable.
Plots and Results:

Custom Regression Class Implementation:

Implement .predict() method.
Perform k-fold cross-validation and calculate MSE.
Sklearn Linear Regression:

Compare MSE results using sklearn's implementation.
