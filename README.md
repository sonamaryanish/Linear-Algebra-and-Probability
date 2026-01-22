
Applied Linear Algebra and Probability techniques to analyze the Wine Quality Dataset. The dataset consists of 1599 rows and 12 columns, detailing various chemical properties of red and white wines and their quality scores.

The dataset contains 1599 samples of wine, with features such as acidity, alcohol content, pH, residual sugar, and others, alongside the target variable, wine quality.
1. Loads the dataset and handles any missing data by replacing null values with the mean value of the respective column.
2. Extracts the following columns as vectors: alcohol,citric acid.
3. Selects two features (e.g., alcohol and density) from the dataset and calculate the covariance matrix using np.cov(X.T), where X is the feature matrix consisting of the selected columns
4. Performs eigen decomposition on the covariance matrix you computed above. Identifies and interpret the results:Identifies the top 2 eigenvalues of the covariance matrix,Identify the corresponding eigenvectors.
5. Finds the wine quality which is most common in the dataset. 
