# Sonar Rock vs Mine Prediction

This project is a Machine Learning classification system that predicts whether an underwater object is a **Rock** or a **Mine** based on sonar signal data.  
The prediction is done using a **Logistic Regression** model trained on the **Sonar Dataset**.

---

## 📌 Project Overview

Sonar signals are used to detect underwater objects. Based on the reflected signals, this model predicts:

- 🪨 **Rock**
- 💣 **Mine**

This is a supervised binary classification problem solved using **Logistic Regression**.

---

## 🧠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Files in This Repository

- `Rock_vs_Mine_Prediction.ipynb`  
  → Jupyter Notebook containing:
  - Data loading  
  - Data preprocessing  
  - Model training  
  - Model evaluation  
  - Prediction system  

- `sonar data.csv`  
  → Dataset used to train and test the model.

- `README.md`  
  → Project documentation.

---

## 📊 Dataset Information

- The dataset contains sonar signal readings.
- Each row represents one object detected by sonar.
- The last column is the **label**:
  - `R` → Rock  
  - `M` → Mine  
- All other columns are numerical features used for prediction.

---

## ⚙️ How the Project Works

1. **Load Dataset**  
   - The CSV file is loaded using Pandas.

2. **Preprocessing**  
   - Features and labels are separated.
   - Data is split into training and testing sets.

3. **Train Model**  
   - A **Logistic Regression** model is trained on training data.

4. **Evaluate Model**  
   - Accuracy is calculated on training and testing data.

5. **Make Prediction**  
   - New sonar input data is given to the trained model.
   - The model predicts Rock or Mine.

---

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
