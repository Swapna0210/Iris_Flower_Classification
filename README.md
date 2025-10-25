# Iris_Flower_Classification
Classifies iris flowers into Setosa, Versicolor, and Virginica using the Iris dataset. Features include sepal and petal length and width. Implements machine learning models like KNN, Decision Tree, and SVM. Includes data analysis, visualization, model training, and evaluation for accurate predictions.
# Iris Flower Classification

## Project Overview
The **Iris Flower Classification** project is a machine learning application that classifies iris flowers into three species: **Setosa, Versicolor, and Virginica**, based on their physical characteristics. The project uses the famous **Iris dataset** by Ronald Fisher (1936) and demonstrates fundamental concepts of **data preprocessing, exploratory data analysis (EDA), and supervised machine learning**.

---

## Dataset
The dataset contains **150 samples**, with each sample having **four features**:

- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  

Each species has **50 samples**, making it a balanced dataset.

The dataset can be accessed from **[scikit-learn datasets](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset)** or **Kaggle**.

---

## Project Steps

1. **Data Loading**  
   Load the Iris dataset into Python using **pandas** or **scikit-learn**.

2. **Data Preprocessing**  
   - Check for missing values  
   - Encode categorical labels (if needed)  
   - Scale features for some models

3. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions with **histograms, boxplots, or violin plots**  
   - Examine relationships between features using **scatter plots or pair plots**  
   - Analyze correlation using a **heatmap**

4. **Model Training**  
   Train and compare multiple machine learning models:  
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Support Vector Machine (SVM)

5. **Model Evaluation**  
   Evaluate models using:  
   - Accuracy  
   - Precision, Recall, F1-Score  
   - Confusion Matrix

6. **Visualization & Insights**  
   Visualize predictions and important features to interpret the model.

---

## Libraries Used

- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## How to Run

1. Clone the repository:  
   ```bash
   git clone <repository_url>

