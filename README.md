# 🎓 Placement Prediction using Simple Linear Regression

## 📌 Project Overview

This project is a **Machine Learning Placement Prediction Model** developed using **Simple Linear Regression**.

The main objective of this project is to predict a student's **placement package** based on their **CGPA**.

The dataset contains **200 records** with two columns:

* **CGPA** – Student's academic performance
* **Package** – Placement package

The model learns the relationship between CGPA and package and predicts the expected placement package for a given CGPA.

---

## 📊 Dataset

The dataset used in this project is `placement.csv`.

It contains **200 rows** and **2 columns**:

| Column    | Description                 |
| --------- | --------------------------- |
| `cgpa`    | Student's CGPA              |
| `package` | Student's placement package |

The `cgpa` is used as the **independent variable**, while `package` is used as the **dependent variable**.

> **Note:** Package values are represented in LPA (Lakhs Per Annum).

---

## 🤖 Machine Learning Algorithm

### Simple Linear Regression

**Simple Linear Regression** is used to find the relationship between one independent variable and one dependent variable.

In this project:

* **Independent Variable:** CGPA
* **Dependent Variable:** Package

The model learns a best-fit linear relationship between CGPA and placement package.

The general equation is:

```text
Package = m × CGPA + c
```

Where:

* `m` = slope
* `c` = intercept
* `CGPA` = input
* `Package` = predicted output

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Check Missing Values
   ↓
Select CGPA and Package
   ↓
Create Linear Regression Model
   ↓
Train the Model
   ↓
Enter CGPA
   ↓
Predict Placement Package
```

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas**
* **Scikit-learn**
* **Google Colab**

---

## 🔮 Prediction

After training the model, the user can enter a CGPA as input.

The trained Linear Regression model then predicts the expected placement package based on the relationship learned from the dataset.

For example:

```text
Enter your CGPA: 8.5

Predicted Package: [Model Prediction] LPA
```

The actual prediction depends on the data available in `placement.csv`.

---

## 🎯 Project Objective

The main objective of this project is to understand the basic workflow of a **Machine Learning Regression Problem** and implement a Simple Linear Regression model for placement package prediction.

---

## 📚 Key Learning

Through this project, I learned:

* Basics of Machine Learning
* Simple Linear Regression
* Independent and dependent variables
* Loading datasets using Pandas
* Basic dataset exploration
* Creating a Linear Regression model
* Training a Machine Learning model
* Making predictions
* Taking user input for prediction

---

## 📁 Project Structure

```text
Placement-Prediction-Linear-Regression/
│
├── Placement_Prediction.ipynb
├── placement.csv
└── README.md
```

---

## 🚀 How to Run

### Google Colab

1. Open `Placement_Prediction.ipynb` in Google Colab.
2. Upload `placement.csv`.
3. Run all the cells.
4. Enter your CGPA when prompted.
5. The model will predict the placement package.

### Local Machine

Install the required libraries:

```bash
pip install pandas scikit-learn
```

Then open the notebook using **Jupyter Notebook** or **VS Code**.

---

## 👨‍💻 Author

**Krishna Bagul**

B.Tech Computer Science Student

Interested in **Data Science, Machine Learning & AI**

---

## ⭐ Future Improvements

* Add train-test split
* Evaluate the model using regression metrics
* Visualize the relationship between CGPA and package
* Plot the regression line
* Add more features related to placement
* Implement Multiple Linear Regression
* Develop a web application for placement prediction
