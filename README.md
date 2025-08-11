# Task 5 – Decision Trees & Random Forests (AI & ML Internship)

## 📌 Objective
Learn and apply tree-based models (Decision Trees & Random Forests) for classification tasks. Perform EDA, control overfitting, interpret feature importance, and evaluate using cross-validation.

---

## 📂 Dataset
**Heart Disease Dataset** – [Kaggle Link](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## 🛠 Tools Used
- Python 3.x
- Pandas, NumPy – Data handling
- Matplotlib, Seaborn – Data visualization
- Scikit-learn – Model training & evaluation

---

## 📊 Exploratory Data Analysis (EDA)
- Target distribution plot
- Correlation heatmap
- Histograms for numeric features
- Boxplots for outlier detection

---

## 🤖 Models Trained
1. **Decision Tree (Default)**
2. **Decision Tree (Pruned)** – `max_depth=4`, `min_samples_split=5`, `min_samples_leaf=2`
3. **Random Forest** – 100 estimators

---

## 📈 Results

| Model                     | Test Accuracy | CV Accuracy |
|---------------------------|--------------:|------------:|
| Decision Tree (Default)   | 0.9853         | 0.9914      |
| Decision Tree (Pruned)    | 0.8000         | 0.8390      |
| Random Forest             | 0.9853         | 0.9939      |

---

## 📌 Key Insights
- **Random Forest** had the highest cross-validation accuracy.
- Pruning reduced overfitting but also lowered accuracy.
- Feature importance analysis revealed top predictors like `cp`, `thalach`, and `oldpeak`.

---

## 📷 Visualizations Included
- Correlation heatmap
- Decision Tree plot
- Feature importance bar chart
- Model performance heatmap

---

## 📜 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python task5_decision_tree_random_forest.py
