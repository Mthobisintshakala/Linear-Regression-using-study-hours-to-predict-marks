# 🎓 Student Marks Prediction using Linear Regression

This project demonstrates how **Simple Linear Regression** can be used to predict a student's exam score based on the number of hours they studied. The model was built and trained using Python, with performance evaluated using the R² score.

---

## 📌 Objective

To develop a linear regression model that predicts **student marks** based on the **number of hours** they spend studying.

---

## 🧾 Dataset Features

- `Hours` – Number of hours a student studied  
- `Scores` – Marks obtained by the student

---

## 🧠 Model Overview

- Model Used: `LinearRegression` from `sklearn.linear_model`
- Evaluation Metric: **R² score**
- Model Accuracy: **Approximately 70% (0.70 R² score)**
  <img width="1462" height="176" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/dc18bbce-78eb-4b60-8417-c2b68722322e" />


This indicates that **70% of the variation in marks** can be explained by the number of hours studied — making it a reasonably accurate model.

The graph below shows the model’s prediction results using the testing dataset.

<img width="1407" height="773" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/18d43954-c0d8-4b9c-90a6-9849267e2fdc" />

- The **cyan triangles** represent the original test values (actual student marks).
- The **red line** represents the predicted values from the linear regression model.
- The photo above shows the actual vs predicted results and demonstrates the effectiveness of the model on testing data.





