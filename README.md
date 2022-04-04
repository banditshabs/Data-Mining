# Data-Mining
A Series of Data Preparations and Machine Learning to detect, find and learn from datasets.

# Lab 1: Exploratory Data Analysis
- load a data set from a CSV file to Pandas dataframe and generate descriptive statistics for its numerical and categorical attributes,
- plot the distribution of numerical and categorical attributes in a data set with a variety of potting techniques,
- utilise EDA for getting an intuitive insight into a data set.

# Lab 2: Data Preparation
encoding categorical features as numerical,
filling in missing values,
rescaling numerical features (i.e. columns) or normalising examples,
appropriately treating outliers/extreme values,
creating new features (i.e. columns) from the existing ones.

# Lab 3 - Clustering and Manifold Learning 
- Apply a clustering algorithm for partitioning a data set into clusters of similar examples.
- Use a manifold-learning technique to visualise a clustered data set with 3 or more numerical attributes as a 2D scatter plot.

# Lab 4: Comparison of Classifiers
- Replicate the classifier training and evaluation demonstrated in the example notebook Lab 4 - Comparison of Binary Classifiers.ipynb but with the dataset seeds.csv. You will need to formulate a binary classification problem and transform the type column accordingly.
- Train a third probabilistic classifier (e.g., MLPClassifier, Naive Bayes, kNN) with seeds.csv add compare it to both SVM and Random Forest. You may encounter warnings for 0 values of some of the metrics. Ignore them and aim at having at least one classifier that has acceptable results.

# Lab 5: Regression and Dimensionality Reduction
- This time we will use regression algorithms (i.e., algorithms for numeric prediction) instead of classifiers, but the same dimensionality reduction techniques can be used in classification pipelines. The second goal is to practice training regression models
- Add a third regression algorithm of your choice. Describe how it compares to Random Forest and Linear regression.
