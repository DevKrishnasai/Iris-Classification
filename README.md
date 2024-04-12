# Iris Species Prediction

This project aims to predict the species of Iris flowers using machine learning algorithms. The dataset used in this project contains measurements for 150 Iris flowers from three different species: Setosa, Versicolor, and Virginica. The features in the dataset include sepal length, sepal width, petal length, and petal width.

## Dataset

The dataset used in this project is available in the file `iris.csv`, which contains the following columns:

- SepalLengthCm: Length of the sepal in centimeters
- SepalWidthCm: Width of the sepal in centimeters
- PetalLengthCm: Length of the petal in centimeters
- PetalWidthCm: Width of the petal in centimeters
- Species: The species of the Iris flower (Setosa, Versicolor, Virginica)

## Data Preprocessing

- The `Id` column was dropped as it was not necessary for the analysis.
- Outliers in the `SepalWidthCm` column were removed using the IQR method.
- The dataset was split into training and testing sets with a 75-25 ratio.

## Exploratory Data Analysis (EDA)

- The distribution of the species in the dataset was visualized using bar plots.
- Pair plots and heatmaps were used to visualize the relationships between different features and the target variable.

## Model Building

- Six different machine learning models were used for prediction: Logistic Regression, K-Nearest Neighbors, Decision Tree, Naive Bayes, Random Forest, and Support Vector Machine (SVM).
- The models were trained on the training dataset and evaluated on the testing dataset.
- The accuracy scores and confusion matrices were used to evaluate the performance of each model.

## Model Comparison

- The accuracy scores of all six models were compared to determine the best-performing model for this dataset.
- The ROC curve was plotted for each model to visualize the trade-off between true positive rate and false positive rate.

## Conclusion

- The SVM model performed the best among all models, achieving an accuracy of X% on the testing dataset.
- The K-Nearest Neighbors model also performed well, with an accuracy of Y% and a good ROC score.

## Future Work

- Fine-tuning hyperparameters of the SVM and K-Nearest Neighbors models to improve their performance.
- Exploring other machine learning algorithms and ensemble methods to further improve the accuracy of the predictions.
