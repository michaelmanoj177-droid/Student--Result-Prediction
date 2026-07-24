# 🎓 Student Result Prediction using Machine Learning

This project predicts whether a student will **Pass** or **Fail** based on their academic scores and attendance using the **Logistic Regression** algorithm from Scikit-learn.

---

## 📌 Project Overview

Student performance prediction is an important application of Machine Learning in education. This project uses student marks and attendance to train a Logistic Regression model that classifies students as **Pass (1)** or **Fail (0)**.

The notebook demonstrates the complete workflow, including:

- Creating the dataset
- Data preprocessing
- Feature scaling
- Splitting data into training and testing sets
- Training a Logistic Regression model
- Evaluating model performance

---

## 🚀 Features

- Simple and beginner-friendly implementation
- Uses Scikit-learn's Logistic Regression
- Standardizes input features using StandardScaler
- Splits data into training and testing datasets
- Evaluates the model using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix

---

## 📂 Dataset

The dataset is created manually inside the notebook.

### Features

| Feature | Description |
|---------|-------------|
| Maths | Marks obtained in Mathematics |
| Science | Marks obtained in Science |
| English | Marks obtained in English |
| Attendance | Attendance percentage |
| Result | Target Variable (1 = Pass, 0 = Fail) |

### Sample Data

| Maths | Science | English | Attendance | Result |
|-------:|--------:|---------:|-----------:|-------:|
| 90 | 85 | 88 | 95 | 1 |
| 45 | 40 | 42 | 60 | 0 |
| 78 | 80 | 75 | 90 | 1 |
| 35 | 38 | 30 | 55 | 0 |
| 88 | 90 | 85 | 98 | 1 |

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn

---

## 📦 Required Libraries

Install the required libraries using:

```bash
pip install pandas scikit-learn
```

---

## 📁 Project Structure

```
Student-Result-Prediction/
│
├── Student_Result_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/student-result-prediction.git
```

2. Navigate to the project folder.

```bash
cd student-result-prediction
```

3. Install dependencies.

```bash
pip install -r requirements.txt
```

4. Open the notebook.

```bash
jupyter notebook Student_Result_Prediction.ipynb
```

or run it in **Google Colab**.

---

## 🧠 Machine Learning Algorithm

**Logistic Regression**

The Logistic Regression classifier predicts whether a student will pass or fail based on the input features after standardizing the data using `StandardScaler`.

---

## 📊 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

Example:

```
Accuracy: 100%

Classification Report

Precision
Recall
F1-score

Confusion Matrix
[[TN FP]
 [FN TP]]
```

---

## 🔮 Example Prediction

### Input

```
Maths = 80
Science = 78
English = 82
Attendance = 90
```

### Output

```
Predicted Result : PASS
```

---

## 🔧 Future Improvements

- Use a larger real-world dataset
- Save the trained model using Pickle
- Build a web application using Flask or Streamlit
- Add data visualization
- Compare multiple Machine Learning algorithms
- Deploy the project on Render or Heroku

---

## 📜 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Your Name**

- GitHub: https://github.com/your-username
- Email: your-email@example.com

---

⭐ If you found this project useful, don't forget to star the repository!
