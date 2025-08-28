## **1. Titanic Survival Prediction**
- **Task Type:** Classification  
- **Dataset:** Titanic dataset (Seaborn inbuilt dataset; publicly available)  
- **Objective:** Predict whether a passenger survived or not.  
- **Steps Performed:**
  1. Loaded and explored dataset.
  2. Handled missing values and encoded categorical features.
  3. Performed EDA using plots and correlations.
  4. Split dataset into train and test sets.
  5. Trained multiple models: Logistic Regression, Decision Tree, Random Forest.
  6. Evaluated models using accuracy, confusion matrix, and classification report.

---

## **2. Iris Flower Classification**
- **Task Type:** Classification  
- **Dataset:** Iris dataset (Scikit-learn inbuilt; publicly available)  
- **Objective:** Predict the species of iris flowers.  
- **Steps Performed:**
  1. Loaded and explored dataset.
  2. Checked for missing values and cleaned dataset (if required).
  3. Split dataset into train and test sets.
  4. Trained models: Decision Tree, Random Forest.
  5. Evaluated models using accuracy and classification report.
  6. Saved best model (`iris_rf_model.pkl`).

---

## **3. Housing Price Prediction**
- **Task Type:** Regression  
- **Dataset:** California Housing dataset (Scikit-learn inbuilt; publicly available)  
- **Objective:** Predict median house value based on features.  
- **Steps Performed:**
  1. Loaded and explored dataset.
  2. Split dataset into features (X) and target (y).
  3. Handled missing values (if any) and performed EDA.
  4. Split dataset into train and test sets.
  5. Trained models: Linear Regression, Decision Tree Regressor, Random Forest Regressor.
  6. Evaluated models using RMSE, MAE, and R² score.
  7. Saved best model (`housing_model.pkl`).

---

## **How to Use**
1. Clone or download the repository.  
2. Open the `.ipynb` notebooks in Jupyter Notebook or VS Code.  
3. Run each notebook step-by-step to reproduce results.  
4. Optional: Load the saved `.pkl` models to make predictions without retraining.

---

## **Note**
- All datasets used are **publicly available**.  
- This project demonstrates **data loading, cleaning, EDA, model training, evaluation, and saving models** for both classification and regression tasks.

