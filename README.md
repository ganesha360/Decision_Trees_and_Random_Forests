🌳 Decision Trees & Random Forests – Heart Disease Prediction

📘 Project Overview  
This project focuses on building and comparing **tree-based machine learning models** to predict heart disease.  
Using the Heart Disease dataset, we trained a **Decision Tree Classifier** and a **Random Forest Classifier**, analyzed overfitting, and identified key features influencing predictions.

🧰 Tools & Libraries Used  
- Python  
- Pandas – data handling  
- NumPy – numerical operations  
- Scikit-learn – model training, evaluation, and visualization  
- Matplotlib / Seaborn – data visualization  

🧩 Steps Performed  

1️⃣ **Data Loading & Exploration**  
   - Loaded the dataset (`heart.csv`) using Pandas.  
   - Explored data structure, missing values, and class distribution.

2️⃣ **Data Preprocessing**  
   - Split data into features (`X`) and target (`y`).  
   - Standardized the numeric features using `StandardScaler`.  
   - Performed an 80-20 train-test split.  

3️⃣ **Decision Tree Model**  
   - Trained a `DecisionTreeClassifier`.  
   - Visualized the tree structure.  
   - Evaluated using accuracy, confusion matrix, and classification report.  

4️⃣ **Overfitting Control**  
   - Limited tree depth using `max_depth=4`.  
   - Compared accuracy before and after pruning.  

5️⃣ **Random Forest Model**  
   - Trained a `RandomForestClassifier` with 100 trees.  
   - Compared its accuracy and stability against Decision Tree.  

6️⃣ **Feature Importance**  
   - Plotted feature importance to identify which attributes most affect predictions (e.g., age, cholesterol, etc.).  

7️⃣ **Cross-Validation**  
   - Used 5-fold cross-validation to measure average model accuracy.  

📊 Results Summary  
| Model | Accuracy | Notes |
|--------|-----------|-------|
| Decision Tree | ~0.80 | May overfit on training data |
| Pruned Tree | ~0.84 | Better generalization |
| Random Forest | ~0.88 | Best performance overall |

✅ **Key Outcomes**  
- Decision Trees are simple but prone to overfitting.  
- Random Forests give higher accuracy and generalization.  
- Feature importance helps explain model predictions.  

💾 **Files Included**  
- `heart.csv` — dataset  
- `DecisionTree_RandomForest.ipynb` — full code  
- `README.md` — documentation  

📚 **Learning Outcome**  
Through this project, I learned how to:  
- Implement Decision Trees and Random Forests.  
- Control model complexity using parameters like `max_depth`.  
- Evaluate models using confusion matrix, accuracy, and cross-validation.  
- Interpret feature importances effectively.  

🧑‍💻 **Author**  
**Ganesh R**  
*(Junior AI/ML Engineer Trainee)*
