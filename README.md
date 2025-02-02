# Decision Tree Model for Real Estate Price Prediction

## 📚 **Project Overview**
This project focuses on building a **Decision Tree model** for predicting real estate prices using a structured dataset. The objective is to preprocess the data, address imbalance, train and optimize the model, and evaluate its performance using appropriate regression metrics.

---

## 🚀 **Objective**
- Perform **Exploratory Data Analysis (EDA)** and preprocess the dataset.
- Handle **data imbalance** using oversampling and undersampling techniques.
- Build and train a **Decision Tree Regressor**.
- Optimize the model through **hyperparameter tuning** and **pruning**.
- Evaluate model performance using regression metrics.
- Conduct residual and error analysis.

---

## 🧠 **Dataset Details**
The dataset is split into:
- **train.csv**: For training and validation.
- **test.csv**: For final model evaluation.

---

## 🛠️ **Tasks**

### **1. Data Preprocessing and Exploratory Data Analysis**
#### **Task 1: Understanding the Dataset**
- Provide an overview of the dataset.
- Perform statistical analysis on numerical columns (mean, standard deviation, min, max, percentiles).

#### **Task 2: Drop Irrelevant Columns**
- Remove columns with low correlation or poor predictive power.
- Justify the reasons for removing each column.

#### **Task 3: Encoding Categorical Features**
- Apply **Label Encoding** to categorical columns.
- Address challenges caused by high cardinality in certain variables.

#### **Task 4: Feature Scaling**
- Apply **Standard Scaler** to numerical features.
- Analyze the effect of scaling on Decision Tree model performance.

#### **Task 5: Target Variable Imbalance Detection**
- Analyze the target variable's distribution.
- Create price brackets: **Low**, **Medium**, **High**, and **Very High**.
- Visualize the distribution across these categories.

#### **Task 6: Handling Imbalanced Data**
- Apply **Random Undersampling** and **Random Oversampling**.
- Discuss the benefits and limitations of each technique.

---

### **2. Building Decision Tree Model**
#### **Task 1: Model Training**
- Train a **Decision Tree Regressor**.
- Visualize the tree structure.

#### **Task 2: Feature Importance and Hyperparameter Tuning**
- Extract and plot **Feature Importances**.
- Optimize hyperparameters using techniques like **Grid Search** or **Randomized Search**.

#### **Task 3: Pruning Decision Tree**
- Apply **Pre-pruning/Post-pruning** techniques.
- Compare pruned and unpruned models.

#### **Task 4: Handling Overfitting**
- Use **Cross-Validation** to prevent overfitting.
- Evaluate **Learning Curves** for training and validation data.

---

### **3. Model Evaluation and Error Analysis**
#### **Task 1: Model Evaluation**
- Evaluate the model using regression metrics:
   - **Mean Squared Error (MSE)**
   - **Mean Absolute Error (MAE)**
   - **R-squared (R²)**
- Compare performance on training and test datasets.

#### **Task 2: Residual and Error Analysis**
- Analyze residuals.
- Visualize prediction errors.

---

## 📊 **Evaluation Metrics**
- **MSE**: Measures mean squared difference between predictions and actual values.
- **MAE**: Measures average absolute difference.
- **R²**: Represents the proportion of variance explained by the model.

---

## 📈 **Results Visualization**
- Visualize decision tree structures.
- Plot feature importance.
- Display learning curves.
- Residual and error analysis graphs.

---

## 📝 **Conclusion**
- Demonstrated the effectiveness of **Decision Tree Regressor** for real estate price prediction.
- Optimized the model using **hyperparameter tuning** and **pruning**.
- Evaluated the model using key regression metrics.
- Provided insights into data preprocessing, feature engineering, and error analysis.

---

## 🤝 **Contributing**
Contributions are welcome! Please create an issue first for major changes.

---

## 📬 **Contact**
For questions or collaboration, feel free to reach out!

---
