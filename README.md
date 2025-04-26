# 🌸 Iris Flower Classification

## 📌 Overview & Objective

The **Iris Flower Classification** project aims to build a robust machine learning model that accurately identifies Iris flowers into three species: *Iris-setosa*, *Iris-versicolor*, and *Iris-virginica*. The model leverages sepal and petal measurements from the famous Iris dataset to classify flowers, while highlighting the most significant features influencing this classification.

---

## 🔍 Project Highlights

- **End-to-End Pipeline:** From data loading and preprocessing to model training, evaluation, and visualization.
- **Data Preprocessing:** Clean the data, handle missing values (if any), and standardize features.
- **Modeling:** Utilize a Random Forest Classifier for its capability to handle non-linear patterns and for multi-class classification robustness.
- **Evaluation:** The model is assessed with key performance metrics including accuracy, confusion matrix, and detailed classification reports. In addition, feature importance is analyzed to reveal which measurements are most influential.
- **Visualization:** Performance metrics and feature importances are visualized using bar charts for clear, intuitive insights.


---

## 🚀 Methodology & Approach

### 1. Data Preprocessing
- **Data Loading:**  
  Use Python's *pandas* library to load the `IRIS.csv` dataset.
- **Feature Extraction & Cleaning:**  
  Extract the four numerical features (*sepal_length*, *sepal_width*, *petal_length*, *petal_width*) and the target variable (*species*).  
  Handle missing values (if any) and ensure the data is consistent.
- **Feature Scaling:**  
  Standardize the numerical features to ensure a smooth training process.

### 2. Model Selection & Training
- **Model Choice:**  
  A **Random Forest Classifier** is implemented due to its robustness and efficiency in dealing with multi-class problems.
- **Training Process:**  
  The dataset is divided into training and testing sets using stratification to maintain class balance. The model is trained on the scaled training data.

### 3. Performance Evaluation
- **Performance Metrics:**  
  Evaluate the model using:
  - **Accuracy Score**
  - **Confusion Matrix** – Visualizing the distribution of correct and incorrect predictions.
  - **Classification Report** – Detailing precision, recall, and F1-scores per class.
- **Feature Importance:**  
  Analyze and visualize the importance of each feature using bar charts to determine which sepal/petal measurements most influence the classification.

---

## 📊 Evaluation Results
When you run the project, you'll obtain:
- **High Classification Accuracy:** The model is designed to achieve high accuracy in species identification.
- **Detailed Reporting:** A comprehensive classification report and confusion matrix, providing insights into prediction errors.
- **Feature Insights:** Visualization of feature importance, highlighting the significance of petal measurements over sepal measurements for this task (typically).

---

## 🏃 How to Run the Project

### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shreeja-29/Iris-Flower-Classification.git
   cd Iris-Flower-Classification
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Place the Dataset:**
   Ensure that `IRIS.csv` (found in the `data/` folder) is available, or add your version of the Iris dataset in the same folder.
4. **Run the Code:**
   - **Script:**  
     ```bash
     python src/iris_classification.py
     ```
   - **Notebook:**  
     Open and run the notebook in the `notebooks/` directory for an interactive experience.

---
