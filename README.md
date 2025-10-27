🌳 **Decision Trees & Random Forests – Heart Disease Prediction**

---

### 📘 Project Overview  
This project focuses on building and comparing **tree-based machine learning models** to predict heart disease.  
Using the Heart Disease dataset, we trained a **Decision Tree Classifier** and a **Random Forest Classifier**, analyzed overfitting, and identified key features influencing predictions.

---

### 🧰 Tools & Libraries Used  
- Python  
- Pandas – for data manipulation  
- NumPy – for numerical operations  
- Scikit-learn – for ML model training & evaluation  
- Matplotlib / Seaborn – for visualizations  

---

### 🧩 Steps Performed  

#### 1️⃣ Data Loading & Exploration  
- Loaded the dataset (`heart.csv`) using Pandas.  
- Checked for missing values and basic dataset info.  
- Explored class distribution of the target column.

#### 2️⃣ Data Preprocessing  
- Split data into features (`X`) and target (`y`).  
- Standardized the numeric features using `StandardScaler`.  
- Performed an 80-20 train-test split.

#### 3️⃣ Decision Tree Model  
- Trained a `DecisionTreeClassifier`.  
- Visualized the tree structure using `plot_tree`.  
- Evaluated using accuracy, confusion matrix, and classification report.

#### 4️⃣ Overfitting Control  
- Controlled tree growth using `max_depth=4`.  
- Compared accuracy before and after pruning.

#### 5️⃣ Random Forest Model  
- Trained a `RandomForestClassifier` with 100 trees.  
- Compared its performance against Decision Tree.  
- Observed improved generalization and stability.

#### 6️⃣ Feature Importance  
- Plotted feature importance to identify key factors influencing prediction (like age, cholesterol, etc.).

#### 7️⃣ Cross-Validation  
- Used 5-fold cross-validation to check model reliability.

---

### 📊 Results Summary  
| Model | Accuracy | Notes |
|--------|-----------|-------|
| Decision Tree | ~0.80 | May overfit training data |
| Pruned Tree | ~0.84 | Better generalization |
| Random Forest | ~0.88 | Best performance overall |

---

### ✅ Key Outcomes  
- Decision Trees are easy to interpret but can overfit.  
- Random Forests are more accurate and generalize better.  
- Feature importance helps explain the model's decisions.  

---

### 💾 Files Included  
- `heart.csv` — dataset  
- `DecisionTree_RandomForest.ipynb` — complete project code  
- `README.md` — documentation  

---

### 📚 Learning Outcome  
Through this project, I learned how to:  
- Implement Decision Trees and Random Forests.  
- Control overfitting using parameters like `max_depth`.  
- Evaluate models with accuracy, confusion matrix, and cross-validation.  
- Interpret feature importances visually.

---

### 🧑‍💻 Author  
**Ganesh R**  
*(Junior AI/ML Engineer Trainee)*
