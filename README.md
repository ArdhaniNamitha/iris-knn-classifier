# iris-knn-classifier

A machine learning project using the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers. The project includes data preprocessing, model training, accuracy evaluation, visualization of K effects, confusion matrix analysis, and 2D decision boundary plotting.

## Objective

The goal is to build a KNN model to classify Iris flowers based on their petal and sepal measurements. This project demonstrates how KNN can be applied to multi-class classification problems and visualized in low dimensions.

## Dataset Description

The dataset contains 150 samples of Iris flowers, with 50 samples each from:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each sample includes four features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

Target Variable: `Species`

Download Dataset: [iris.csv.xlsx](Iris.csv)

## Files Included

## Files Included

| File Name                 | Description                                                            |
|---------------------------|-------------------------------------------------------------------------|
| `README.md`               | Project overview and instructions                                       |
| `code(Task6).ipynb`       | Google Colab notebook with code, outputs, and all steps implemented     |
| `Iris.csv`                | Dataset used for training and evaluation                                |
| `accuracy.png`            | Plot showing accuracy across different values of K                      |
| `confusion matrix.png`    | Confusion matrix showing prediction performance                         |
| `decision boundaries.png` | Visualization of decision boundaries using two selected features        |


## Steps Covered in the Project

1. **Data Preprocessing**
   - Loaded the Iris dataset
   - Dropped the `Id` column
   - Normalized features using StandardScaler

2. **KNN Model Training**
   - Used KNeighborsClassifier from scikit-learn
   - Experimented with different values of K (1 to 20)
   - Selected the best K based on accuracy

3. **Model Evaluation**
   - Calculated accuracy using accuracy_score
   - Generated and displayed confusion matrix

4. **Decision Boundary Visualization**
   - Used PetalLengthCm and PetalWidthCm for 2D visualization
   - Plotted decision boundaries using a meshgrid

## How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook: `code(Task6).ipynb`
3. Upload the dataset: `Iris.csv`
4. Run the cells to:
   - Train the KNN model
   - View accuracy for different K values
   - Display the confusion matrix
   - Plot the decision boundaries

## Visuals

- View Accuracy Plot: [accuracy.png](accuracy.png)  
- View Confusion Matrix: [confusion matrix.png](confusion%20matrix.png)  
- View Decision Boundaries: [decision boundaries.png](decision%20boundaries.png)

