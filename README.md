# Iris-Flower Clasification Project

## Project Overview
This project trains a K-Nearest Neighbors classifier on the **Iris dataset** to predict the species of iris flowers based on sepal and petal measurements. The model is built using Python and several libraries including `pandas`, `seaborn`, `matplotlib`, and `scikit-learn`.

![](https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png)

Image Courtesy: https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png



## Project Description
The **Iris Flower Classification** project focuses on developing a machine learning model to classify iris flowers into their respective species based on specific measurements. Iris flowers are classified into three species: **setosa**, **versicolor**, and **virginica**, each of which exhibits distinct characteristics in terms of measurements. The model aims to automate the classification process, offering a practical solution for identifying iris species based on sepal length, sepal width, petal length, and petal width.


## Dataset Description

The **Iris dataset** consists of 150 records of iris flowers, each with four features:

- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)

The dataset has three classes (species of iris flowers):
- `Iris-setosa`
- `Iris-versicolor`
- `Iris-virginica`

The goal is to predict the species of the iris flower based on the four features.

## Model Training

1. The data is loaded from the UCI Machine Learning Repository using the `pandas` library.
2. The dataset is explored using functions like `head()` and `describe()` to view the structure and statistics.
3. A pair plot is generated using the `seaborn` library to visualize the relationships between the features.
4. The data is split into **training** (70%) and **test** (30%) sets using the `train_test_split()` function from `scikit-learn`.
5. A KNN classifier is created using `KNeighborsClassifier(n_neighbors=3)` and trained on the training set.
## Prediction

Once the model is trained, it is used to predict the class of flowers in the test set. Predictions are made using the `predict()` method.
- Additionally, predictions for new data points can also be made.
  
## Results
This model achieves a high accuracy of 100% ontest data. These results suggest the model is effective.
## Results

The performance of the model is evaluated using a **classification report**, which provides metrics like precision, recall, F1-score, and accuracy.



