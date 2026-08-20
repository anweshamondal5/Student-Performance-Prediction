# 🎓 Student Performance Prediction

A Machine Learning project that predicts **student academic performance** using demographic, behavioral, and academic features.

The project analyzes student-related factors such as study habits, attendance, extracurricular activities, career aspirations, and subject scores to build a predictive model for estimating student performance.

## 📌 Project Overview

Student academic performance can be influenced by several factors beyond classroom learning. This project uses Machine Learning to analyze these factors and predict a student's final academic performance.

The project follows a basic end-to-end Machine Learning workflow:

* Data collection and exploration
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature selection
* Model training
* Model evaluation
* Model serialization for future predictions

## 🎯 Objectives

* Analyze factors affecting student academic performance.
* Explore relationships between student habits and subject scores.
* Build a Machine Learning model for predicting student performance.
* Save the trained model for future use.

## 📊 Dataset

The project uses a student performance dataset containing **2,000 student records** and multiple demographic, behavioral, and academic attributes.

### Key Features

| Feature                      | Description                                 |
| ---------------------------- | ------------------------------------------- |
| `gender`                     | Student's gender                            |
| `part_time_job`              | Whether the student has a part-time job     |
| `absence_days`               | Number of absence days                      |
| `extracurricular_activities` | Participation in extracurricular activities |
| `weekly_self_study_hours`    | Weekly hours spent on self-study            |
| `career_aspiration`          | Student's career aspiration                 |
| `math_score`                 | Mathematics score                           |
| `history_score`              | History score                               |
| `physics_score`              | Physics score                               |
| `chemistry_score`            | Chemistry score                             |
| `biology_score`              | Biology score                               |
| `english_score`              | English score                               |
| `geography_score`            | Geography score                             |

The dataset is stored in `student-scores.csv`.

## 🧠 Machine Learning Workflow

```text
Student Dataset
      ↓
Data Loading
      ↓
Data Exploration & Analysis
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Trained Model
      ↓
Saved as .pkl
```

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computing
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook** – Development and experimentation
* **Pickle** – Model serialization

## 📁 Project Structure

```text
Student-Performance-Prediction/
│
├── student-scores.csv
│
├── student_score_model (1).ipynb
│
├── student_score_model.pkl
│
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/anweshamondal5/Student-Performance-Prediction.git
```

### 2. Navigate to the Project

```bash
cd Student-Performance-Prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch the Notebook

```bash
jupyter notebook
```

Open:

```text
student_score_model (1).ipynb
```

and run the cells sequentially.

## 💾 Trained Model

The trained Machine Learning model is saved as:

```text
student_score_model.pkl
```

The serialized model can be loaded later using Python's `pickle` module without retraining the model.

Example:

```python
import pickle

with open("student_score_model.pkl", "rb") as file:
    model = pickle.load(file)
```

## 📈 Key Learning Outcomes

Through this project, the following Machine Learning concepts are demonstrated:

* Data preprocessing
* Exploratory Data Analysis
* Feature analysis
* Supervised Machine Learning
* Model training and evaluation
* Model serialization
* Working with real-world tabular datasets

## 🔮 Future Improvements

Possible improvements to the project include:

* Comparing multiple Machine Learning algorithms.
* Hyperparameter tuning and cross-validation.
* Adding a user-friendly prediction interface using Streamlit.
* Providing visual explanations of model predictions.
* Deploying the prediction system as a web application.
* Adding more student-related behavioral and academic features.

## 👩‍💻 Author

**Anwesha Mondal**

B.Tech — Computer Science & Engineering (AI/ML)

GitHub: [@anweshamondal5](https://github.com/anweshamondal5)

## ⭐ Acknowledgement

This project was developed as a Machine Learning project to explore how data-driven techniques can be applied to understanding and predicting student academic performance.
