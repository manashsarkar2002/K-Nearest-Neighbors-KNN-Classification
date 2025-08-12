# K-Nearest Neighbors (KNN) Classification on Iris Dataset

This project demonstrates the use of the **K-Nearest Neighbors** algorithm for classifying iris flower species based on their physical measurements.  
The workflow includes **data preprocessing, normalization, model training, hyperparameter tuning, evaluation, and decision boundary visualization**.

---

## 📂 Dataset
We use the famous [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris), which contains 150 samples of iris flowers with the following features:
- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)

**Target Classes:**
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## 📊 Steps Implemented

1. **Load & Explore Dataset**
   - Read the CSV file (`Iris.csv`)
   - Extract features and labels

2. **Normalize Features**
   - Use `StandardScaler` to normalize feature values

3. **Train-Test Split**
   - Split data into 80% training and 20% testing

4. **Model Training**
   - Use `KNeighborsClassifier` from `sklearn`
   - Experiment with multiple values of **K** (1, 3, 5, 7, 9)

5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix

6. **Visualization**
   - Plot **Accuracy vs K**
   - Visualize **decision boundaries** for first two features
