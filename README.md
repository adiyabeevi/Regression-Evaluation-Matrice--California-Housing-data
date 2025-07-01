# Regression-Evaluation-Matrice--California-Housing-data
This project demonstrates the application of regression models on the **California Housing dataset**, focusing on comprehensive evaluation and model tuning techniques.

---

##  Objective

To evaluate different regression techniques in supervised learning by:
- Preprocessing and exploring the dataset
- Implementing and comparing 5 regression algorithms
- Performing cross-validation and hyperparameter tuning
- Selecting the best model using multiple metrics

---

## Dataset

- **Source**: `fetch_california_housing` from `sklearn.datasets`
- **Target**: Median house price
- **Features**: Median income, house age, average rooms, population, etc.

---

## 🔧 Models Used

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **Support Vector Regressor (SVR)**

---

## Evaluation Metrics

Each model is evaluated using:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score (R²)**

### Additional Techniques
- **Cross-Validation**: 5-fold used for all models
- **Hyperparameter Tuning**: GridSearchCV used for fine-tuning (e.g., Random Forest)
 
Key Insights
Ensemble models (Random Forest & Gradient Boosting) showed high accuracy and generalization.

SVR and Decision Tree models performed relatively poorly without tuning.

Cross-validation ensures stability and robustness of model comparison.

Repository Structure
Copy
regression-evaluation-metrics
 ┣ 📄 Regression_Evaluation_Metrics_Assignment.ipynb
 ┗ 📄 README.md
