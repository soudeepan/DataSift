# DataSift: Optimizing Classification Methods for Enhanced Predictive Analysis

## Objective:

This project aims to determine the most suitable classification method for a given dataset. The selected classification algorithms for evaluation include:

* **K-Nearest Neighbors (KNN)**

* **Naive Bayes**

* **Logistic Regression**

* **Decision Trees**

* **Random Forest**

* **Bagging**


## Methodology:

Dataset: Utilize a representative dataset for the classification task.

**Algorithms**:

* Implement KNN for classification.
* Apply Naive Bayes algorithm.
* Employ Logistic Regression.
* Utilizing Decision Tree.
* Appling Random Forest.
* Employ Bagging.

**Evaluation**:

* Compare the predictions of each algorithm with the actual (ground truth) values.
* Measure and analyze the performance metrics for each method.

**Outcome**:

* Identify the classification algorithm that demonstrates the highest accuracy and reliability.
* Present a comparative analysis of the performance of KNN, Naive Bayes, Logistic Regression, Decision Tree, Random Forest and Bagging.

## Data Preprocessing
  
**Dataset Source**: [/www.kaggle.com/datasets/michau96/classification-syntetic-data-for-practice/](https://www.kaggle.com/datasets/michau96/classification-syntetic-data-for-practice/)

Note: The original file has 32 columns, the first column being index but it was unlabeled. The file was editted to make 'Index' as the first label for removal using drop() function.

**Dataset Characteristics**:

* Size: 1 million rows

* Columns: 31


The database contains exactly 1 million rows and 31 columns. The first 30 columns are explanatory variables, of which: the first 10 were generated using distributions from the numpy.random package, the next 10 were generated using the function np.random.randint and the last 10 using np.random.choice using various probabilities. The last column is the "class", i.e. the explained variable which can take the value 0 or 1.

