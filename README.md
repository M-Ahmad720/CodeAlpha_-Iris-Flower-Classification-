# 🌸 Iris Flower Classification (ML Project)

This is a machine learning project based on the famous Iris flower dataset. The goal is to classify iris flowers into three species — Setosa, Versicolor, and Virginica — based on four flower measurements using various classification algorithms.

# 📁 Project Structure

| Folder/File         | Description                         |
| ------------------- | ----------------------------------- |
| iris\_Project.ipynb | Main Jupyter/Colab notebook         |
| Iris.csv            | Dataset file                        |
| iris\_model.joblib  | Saved trained model (Random Forest) |
| README.md           | Project overview and instructions   |

# 📌 Objective

Build an end-to-end machine learning pipeline using:
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Model Training (KNN, SVM, Logistic Regression, Random Forest)
Model Evaluation (Accuracy, Confusion Matrix, Classification Report)
Hyperparameter Tuning using GridSearchCV
Model Saving for future deployment


# 🧠 Algorithms Used

✅ Logistic Regression
✅ K-Nearest Neighbors (KNN)
✅ Support Vector Machine (SVM)
✅ Random Forest Classifier (Best Performing)

# 📊 Results
| Model               | Accuracy             |
| ------------------- | -------------------- |
| Dummy Classifier    | \~33% (baseline)     |
| Logistic Regression | \~97%                |
| KNN                 | \~96%–98%            |
| SVM                 | \~98%                |
| Random Forest       | ✅ 100% (on test set) |


# 🔬 Technologies Used

Python 🐍
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Google Colab / Jupyter Notebook
joblib (for saving models)🔬 Technologies Used


# 📁 Dataset Information

Dataset: Iris Dataset from UCI Machine Learning Repository
Total samples: 150
## Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
## Target classes:
Iris-setosa
Iris-versicolor
Iris-virginica

# 📦 Model Saving
The best model (Random Forest) is saved using joblib:
**joblib.dump(model, 'iris_model.joblib')**
You can load it later for prediction without retraining.

# ✅ Conclusion

Created a full ML pipeline from data loading to model deployment
Multiple models trained and compared using cross-validation
Achieved up to 100% accuracy on the test set
Prepared for real-world deployment with saved model and clean code

# 👨‍💻 Author
**Name: Muhammad Ahmad**
