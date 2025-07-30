
# 🎓 Student Marks & Grades Prediction Project

This data science project analyzes and predicts student marks based on their study time and number of courses taken. It involves data cleaning, grade assignment, statistical summaries, predictive modeling using machine learning, and data visualization.

---

## 📁 Project Structure

- **Part 1:** Student Marks and Grades Summary
- **Part 2:** Machine Learning Models for Marks Prediction
- **Part 3:** Data Visualization of Patterns and Distributions

---

## 📌 Features

- Calculates **total and average marks** for each student
- Assigns **letter grades** based on average marks
- Computes **class average** and identifies the **topper**
- Trains three ML models: `Linear Regression`, `Decision Tree`, and `Random Forest`
- Predicts student marks from input features
- Generates **multiple visualizations** to understand data patterns

---

## 📂 Dataset

The project uses a dataset named `Student_Marks.csv` with the following fields:

- `number_courses`: Number of courses taken
- `time_study`: Time spent studying (in hours)
- `Marks`: Final score of the student

> **Note:** Ensure this CSV file is available in the working directory or uploaded to your Colab session.

---

## 🚀 Getting Started

### 1. Clone or Upload Project

If running locally, clone the repo or upload files to your preferred environment.

### 2. Install Requirements

Most libraries used are standard in Google Colab, but if running locally:

```bash
pip install pandas scikit-learn matplotlib seaborn numpy
```

### 3. Run the Script

Open the `data_science_project_guvi.py` file and run the cells sequentially in Jupyter or Colab.

---

## 📊 Model Summary

| Model                  | MAE   | MSE   | RMSE  | R²     |
|------------------------|-------|-------|--------|--------|
| Linear Regression      | ✅    | ✅    | ✅     | ✅     |
| Decision Tree Regressor| ✅    | ✅    | ✅     | ✅     |
| Random Forest Regressor| ✅    | ✅    | ✅     | ✅     |

> Actual values will be printed during script execution.

---

## 📈 Visualizations

The project includes:
- Scatter plot: `Time Study vs Marks`
- Histogram: `Marks Distribution`
- Bar chart: `Grade Frequency`
- Box plot: `Marks by Number of Courses`

---

## 🧠 Machine Learning Workflow

1. Split data into training/test sets
2. Train models with `number_courses` and `time_study` as features
3. Evaluate performance using standard regression metrics
4. Predict new student marks

---

## 📌 Example Prediction

```python
new_student_data = pd.DataFrame({
    'number_courses': [5, 7, 3],
    'time_study': [4.0, 6.5, 2.0]
})

predicted_marks = model.predict(new_student_data)
```

---

## 📌 Credits

Project by: [Your Name]  
Guided by: GUVI Data Science Capstone Framework

---

## ✅ To Do (Optional Enhancements)

- Add support for more features like `student age`, `gender`, etc.
- Implement classification models for grade prediction
- Deploy using Flask or Streamlit for web access

---

## 📬 Contact

For any queries or collaborations, feel free to reach out!
