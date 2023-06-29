# Iris Flower Classification Report

## Introduction
In this project, the task was to train a machine learning model that can classify iris flowers into their respective species based on their measurements. The iris flower dataset consists of three species: setosa, versicolor, and virginica.

## 1. Exploratory Data Analysis (EDA)
Before developing the classification model, exploratory data analysis was performed to gain insights into the dataset.

### Dataset Information
The iris dataset contains the following columns:
- SepalLengthCm: sepal length in centimeters
- SepalWidthCm: sepal width in centimeters
- PetalLengthCm: petal length in centimeters
- PetalWidthCm: petal width in centimeters
- Species: iris species (setosa, versicolor, or virginica)

### Summary Statistics
Summary statistics of the dataset were calculated to understand the distribution and range of each feature.

### Visualizations
Various visualizations were created to explore the dataset:
- Pairplot: A pairplot was generated to visualize the distribution of each feature and their relationships with each other, with different species shown in different colors.
- Boxplots: Boxplots were created to compare the distributions of features across different iris species, providing insights into their variations.
- Correlation Matrix: A correlation matrix heatmap was plotted to examine the relationships between features, highlighting their correlation strengths.

## 2. Model Development and Evaluation
After the EDA, a classification model was developed using different machine learning algorithms to classify iris flowers based on their measurements. The following models were trained and evaluated:

### Logistic Regression
- The dataset was split into training and testing sets.
- The features were scaled using standardization.
- A logistic regression model was created and trained on the training data.
- Predictions were made on the testing set, and a classification report and confusion matrix were generated.
- The accuracy of the model was calculated and displayed.

### Additional Models
In addition to logistic regression, three other models were trained and evaluated:
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

For each model, the same steps as in logistic regression were followed:
- The model was trained on the training data.
- Predictions were made on the testing set, and a classification report and confusion matrix were generated.
- The accuracy of each model was calculated and displayed.

## Results and Conclusion
The classification report, confusion matrices, and accuracy scores for each model are summarized below:

### Logistic Regression
- Accuracy: 1.0  

### Support Vector Machine (SVM)
- Accuracy: 1.0

### Decision Tree
- Accuracy: 1.0

### Random Forest
- Accuracy: 1.0

All four models achieved the same accuracy of 1.0, indicating that they performed equally well on the iris flower classification task.

In conclusion, a machine learning model was successfully developed and evaluated for classifying iris flowers into their respective species based on their measurements. The models achieved high accuracy, demonstrating their effectiveness in predicting the iris flower species.
