# Heart_Disease_Project

## 📊 Dataset
- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Rows:** ~300  
- **Columns:** age, sex, cholesterol, blood pressure, max heart rate, etc.  
- **Target variable:** Presence of heart disease (`1`) or No heart disease (`0`).  

---

## ⚙️ Steps Performed
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Scaling numerical features  

2. **Dimensionality Reduction**
   - Applied PCA to reduce correlated features  

3. **Feature Selection**
   - Selected top features using statistical and model-based methods  

4. **Supervised Learning**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - SVM
   - Evaluated models: Accuracy, Precision, Recall, F1 Score, AUC Score 

5. **Unsupervised Learning**
   - K-Means clustering for patient segmentation
   - Hierarchical Clustering
   - Evaluated models: Silhouette score, ARI

6. **Hyperparameter Tuning**
   - Used GridSearchCV / RandomizedSearchCV  

7. **Final Model**
   - Best performing model saved as `final_model_tuned.pkl`  
