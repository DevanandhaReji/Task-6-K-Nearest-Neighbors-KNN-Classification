# Task-6-K-Nearest-Neighbors-KNN-Classification
Task 6: K-Nearest Neighbors (KNN) Classification
Tools and Libraries Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


### 1. Load the Dataset
The Iris dataset was loaded using `sklearn.datasets.load_iris()`. This dataset is often used for testing classification models.

### 2. Normalize the Features
Since KNN is a distance-based algorithm, we normalized the features using `StandardScaler`. This ensures all features contribute equally to the distance calculations.

### 3. Split into Training and Test Sets
We split the data into 80% training and 20% testing using `train_test_split()` to evaluate the model properly.

### 4. Train the KNN Model
We used `KNeighborsClassifier` from `sklearn.neighbors` with `k = 5` as a starting value and trained the model on the training data.

### 5. Make Predictions
The trained model was used to predict the classes for the test data.

### 6. Evaluate the Model
We evaluated the model using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**

