# 🧠 Customer Behaviour Classification

This capstone project predicts whether a customer will purchase a product based on demographic information using machine learning models. It also includes a GUI deployment using the Tkinter library.

---

## 📌 Project Objective

To build a machine learning classification model that predicts customer purchasing behavior and deploy it through a user-friendly desktop interface.

---

## 📊 Dataset

The dataset `Customer_Behaviour.csv` contains details about 400 clients, including:

- User ID (removed during preprocessing)
- Gender
- Age
- Estimated Salary
- Purchased (Target Variable)

---

## 🔍 Workflow Overview

### 🧼 Data Preprocessing
- Handled missing values (none in dataset)
- Encoded Gender (Male → 0, Female → 1)
- Feature scaling using `StandardScaler`
- Train-test split (80/20)

### 📈 Data Visualization
- Correlation heatmap
- Gender vs Purchase count plot
- Age distribution plot
- Pairplot to analyze feature relations

### 🤖 Models Used
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

All models were evaluated using cross-validation. The model with the highest score was selected for deployment.

---

## 🖥 Deployment

The best model was deployed using a Tkinter GUI, allowing users to input customer details (Gender, Age, Salary) and predict purchase behavior in real-time.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Tkinter (for GUI)
- Jupyter Notebook

---

## 🛠️ Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/BasilBiju1217/customer-behaviour-classification.git
   cd customer-behaviour-classification
