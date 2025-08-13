# Iris-dataset
KNN Classification on Iris Dataset
This project implements the K-Nearest Neighbors (KNN) algorithm to classify flower species in the Iris dataset. The workflow includes:

1.Data Loading – Imported Iris dataset from CSV.

2.Feature Selection – Dropped unnecessary columns and separated features (X) from target (y).

3.Data Normalization – Scaled features using StandardScaler to ensure equal weight in distance calculations.

4.Train-Test Split – Divided data into 80% training and 20% testing sets.

5.Model Training – Trained a KNN classifier (initially with K=3) using scikit-learn.

6.Model Evaluation – Measured accuracy and visualized results with a confusion matrix.

7.K Value Optimization – Tested K values from 1 to 20 and plotted accuracy vs K to select the best parameter.

The results show how K impacts classification performance, helping to select the most accurate model.
