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
- Gradient Boosting Classifier  

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

### 📌 Example Result Summary  

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 0.9917171073590315 |
| Decision Tree | 0.9859827970691303 |
| Random Forest | 0.9925135393437401 |
| KNN | 0.9917171073590315 |
| SVM | 0.9942656897100988 |
| XGBoost | 0.9936285441223319 |

> 🏆 **Best Model:**
>
> 
> <img width="531" height="488" alt="SVM" src="https://github.com/user-attachments/assets/1b9ef20c-5793-4056-9d0c-f0d53ee266c7" />

#### FEATURE IMPORTANCE 

<img width="497" height="52" alt="Screenshot 2025-11-27 154144" src="https://github.com/user-attachments/assets/5794b0fa-934e-4e5d-b569-3f37cbd18001" />
<img width="989" height="590" alt="FEATURE_IMPORTANCE_XGB" src="https://github.com/user-attachments/assets/fcdd7aa2-9770-4322-ab8a-dd8c4182c4ca" />
<img width="989" height="590" alt="FEATURE_IMPORTANCE_rf" src="https://github.com/user-attachments/assets/de9f837f-94ea-4f3c-bc27-00f6db4069b9" />
<img width="990" height="590" alt="FEATURE_IMPORTANCE_GB" src="https://github.com/user-attachments/assets/2b580a10-fa91-4856-8fb8-35165daf10cc" />
<img width="990" height="590" alt="FEATURE_IMPORTANCE_dt" src="https://github.com/user-attachments/assets/753d6023-cd6b-4736-9b63-91275a4e2269" />

---

## 📉 Visualizations

The project includes:

- Class distribution chart
  
  <img width="580" height="511" alt="class_distribution" src="https://github.com/user-attachments/assets/7b8c4b9e-ed5a-431d-9725-d6a246737918" />

- Boxplots
  
  <img width="1149" height="601" alt="boxplot" src="https://github.com/user-attachments/assets/ceee641d-2f0d-4497-8120-e37b89807186" />

- Correlation heatmap

  <img width="863" height="623" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/cc737aa8-2bcf-44e3-9324-03728d115007" />

- Confusion matrices for all models

   <img width="534" height="470" alt="confusion_matrix_XGB" src="https://github.com/user-attachments/assets/deefadb7-54ef-45fb-bca9-da68d511e90f" />
   <img width="534" height="470" alt="confusion_matrix_SVM" src="https://github.com/user-attachments/assets/d85d945a-a53c-42b1-9f0b-beda3a384b64" />
   <img width="682" height="602" alt="confusion_matrix_RF" src="https://github.com/user-attachments/assets/6fa726a2-2efc-4cb1-a84c-de0228599236" />
   <img width="680" height="598" alt="confusion_matrix_LR" src="https://github.com/user-attachments/assets/2bb652ec-b2f7-49cb-b018-78dacdc2339b" />
   <img width="534" height="470" alt="confusion_matrix_KNN" src="https://github.com/user-attachments/assets/d7953af7-dacb-4802-a66c-f7627e21f92f" />
   <img width="534" height="470" alt="confusion_matrix_GB" src="https://github.com/user-attachments/assets/e3ad4937-13b9-40ff-8428-e7cdfd146bd3" />
   <img width="683" height="602" alt="confusion_matrix_DT" src="https://github.com/user-attachments/assets/8f904d5a-3154-46c1-a717-48111be92198" />




---

## 📚 Project Structure


![Untitled - Frame 1 (3)](https://github.com/user-attachments/assets/9df43fa3-40b5-48f3-846a-c394761ec228)



---

## 👨‍💻 Developer
 
  Nirudeeswar R
 
 📍 Chennai
 
 🎓 B.Tech CSE
 
 📧 nirudeeswarr14@gmail.com
