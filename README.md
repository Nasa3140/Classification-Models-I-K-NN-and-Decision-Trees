# Classification-Models-I-K-NN-and-Decision-Trees
Classification Models I: K-NN and Decision Trees
---
* **Student Result Prediction (K-NN)**
* **Spam Email Prediction (Decision Tree)**

---

```markdown
# 🧠 Machine Learning Mini Projects – KNN & Decision Tree

This repository contains two beginner-friendly machine learning classification projects built with **Python** and **scikit-learn**.

---

## 📁 1. Student Result Prediction (K-NN from Scratch)

### 📘 Problem:
Predict whether a student will **Pass or Fail** based on their scores in:
- Maths
- Computer Science

### 🛠 Method:
Implemented from scratch using the **K-Nearest Neighbors (K-NN)** algorithm and the **Euclidean Distance** formula.

### 🧾 Features:
- `maths` – score in Maths
- `cs` – score in Computer Science

### 🎯 Output:
- `Pass` or `Fail`

### ✅ Steps:
1. Create a dataset of students with scores and results.
2. Accept a new student query (e.g., maths = 6, cs = 8).
3. Calculate Euclidean distance to each student.
4. Sort by nearest distance.
5. Take top `k = 3` neighbors.
6. Predict the result by **majority voting**.

### 📦 Dependencies:
- `math` (for `sqrt()` function)

### ▶️ Sample Output:
```

Predicted Result: Pass

```

---

## 📁 2. Spam Email Prediction (Decision Tree Classifier)

### 📘 Problem:
Classify whether an email is **Spam** or **Not Spam** based on its structure.

### 🛠 Method:
Built using `DecisionTreeClassifier` from the **scikit-learn** library.

### 🧾 Features:
- `Subject_Length`: number of characters in subject
- `Num_Links`: how many links in the email
- `Has_CAPS`: whether subject contains capital letters (`1 = Yes`, `0 = No`)

### 🎯 Output:
- `Spam` or `Not Spam`

### ✅ Steps:
1. Prepare sample email dataset with known labels.
2. Train a Decision Tree model.
3. Make prediction on a new email.

### 📦 Dependencies:
- `pandas`
- `scikit-learn`

### ▶️ Sample Output:
```

Prediction: \['Spam']

````

---

## 💡 Learning Outcomes

- Understand classification with real-world analogies.
- Learn K-NN using raw Python (no ML libraries).
- Get hands-on with decision trees using scikit-learn.
- Learn about data preparation, model training, and prediction.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ml-knn-decisiontree-mini-projects.git
````

2. Open the `.ipynb` files using **Jupyter Notebook** or **VS Code**.

3. Run each cell step-by-step to see predictions.

---

## 📚 Folder Structure

```
📁 ml-knn-decisiontree-mini-projects/
│
├── 📄 Students Result Prediction.ipynb
├── 📄 Spam Email Prediction.ipynb
├── 📄 README.md
```

---

## 👩‍💻 Author

Made with ❤️ by \Nasira Mujawar(K)

---
