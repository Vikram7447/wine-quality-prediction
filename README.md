# wine-quality-prediction
# 🍷 Wine Quality Prediction

This project aims to predict the quality of wine based on its chemical properties using various classification algorithms. It provides practical insights into how machine learning can be used in the food and beverage industry — specifically in viticulture and wine assessment.

---

## 📂 Dataset

The dataset used contains physicochemical test results (numerical features) for different wine samples, along with a quality score (target variable) rated between 0–10.

**Source**: [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

**Filename**: `WineQT.csv`

### 🔑 Key Features

- `fixed acidity`  
- `volatile acidity`  
- `citric acid`  
- `residual sugar`  
- `chlorides`  
- `free sulfur dioxide`  
- `total sulfur dioxide`  
- `density`  
- `pH`  
- `sulphates`  
- `alcohol`

**Target**:
- `quality` (an integer score)

---

## 🧪 Objective

- Predict the **quality of wine** using chemical attributes.
- Evaluate and compare the performance of multiple classification models.
- Gain insights into which features most influence wine quality.

---

## 🧠 Models Used

Three classifiers were trained and tested on the dataset:

1. **Random Forest Classifier**
2. **Stochastic Gradient Descent (SGD) Classifier**
3. **Support Vector Classifier (SVC)**

---

## 🔎 Data Preprocessing

- Checked for and handled any missing values
- Dropped unnecessary column: `Id`
- Performed `train_test_split` (80% training, 20% testing)
- Standardized features if needed (for SVC and SGD)

---

## 📊 Visualizations

- Bar plot of wine quality distribution
- Heatmap of correlation matrix
- Confusion matrix for each classifier

*(Add sample plots/screenshots if available)*

---

## 📈 Results

| Model               | Accuracy Score |
|---------------------|----------------|
| Random Forest       | **0.XX**       |
| SGD Classifier      | 0.XX           |
| Support Vector (SVC)| 0.XX           |

- **Random Forest** achieved the highest accuracy and overall precision.
- **SGD** performed moderately well but with lower recall on minority classes.
- **SVC** struggled due to overlapping feature space in multi-class targets.

---

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (sklearn)

