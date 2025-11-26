# 🍽️ NutriClass: Food Classification Using Nutritional Data

NutriClass is a machine learning project designed to classify food items into categories based on their nutritional attributes.  
Using traditional ML algorithms and a structured data pipeline, the project demonstrates how nutritional values like calories, protein, carbs, fat, and sugar can be used to predict the food type efficiently.

---

## 📌 Project Objectives

- Build a machine learning classification system using nutritional data.
- Preprocess and analyze food data with EDA techniques.
- Train and compare multiple ML models for multi-class classification.
- Identify the best-performing model.
- Provide insights into feature relevance and model behavior.

---

## 📊 Dataset Description

The dataset contains nutritional information for various food items, including:

### **Numeric Features**
- Calories  
- Protein  
- Fat  
- Carbs  
- Sugar  
- Fiber  
- Sodium  
- Cholesterol  
- Glycemic Index  
- Water Content  
- Serving Size  

### **Categorical Features**
- Meal_Type (breakfast, lunch, dinner, snack)  
- Preparation_Method (raw, fried, grilled, etc.)

### **Binary Features**
- Is_Vegan  
- Is_Gluten_Free  

### 🎯 **Target Column**
- `Food_Name`

---

## 🧪 Exploratory Data Analysis (EDA)

The following EDA steps were performed:

- Basic dataset exploration (`info()`, `describe()`)
- Checking missing values & duplicates
- Class distribution plot for `Food_Name`
- Boxplots for detecting outliers
- Correlation heatmap for numeric attributes

---

## 🔧 Data Preprocessing

- Handling missing values (imputation/removal)
- Removing duplicates  
- One-hot encoding of categorical columns  
- Label encoding the target (`Food_Name`)
- Converting boolean fields to integers (0/1)
- Feature scaling using StandardScaler  
- Train-Test split (80/20 with stratification)

---

## 🤖 Machine Learning Models Used

Trained and compared multiple classifiers:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- XGBoost  
- (*Optional*) Gradient Boosting Classifier  

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

### 📌 Example Result Summary  
(Evaluate using your notebook output)

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ... |
| Decision Tree | ... |
| Random Forest | ... |
| KNN | ... |
| SVM | ... |
| XGBoost | ... |

> 🏆 **Best Model:** Replace this with your actual best model (e.g., XGBoost or Random Forest)

---

## 📉 Visualizations

The project includes:

- Class distribution chart  
- Boxplots  
- Correlation heatmap  
- Confusion matrices for all models  
- (Optional) Feature importance for tree-based models  

---

## 📚 Project Structure

