# 📧 Email Spam Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

Email Spam Detection is a Machine Learning project that classifies messages as **Spam** or **Ham (Not Spam)**. It uses Natural Language Processing (NLP) techniques to preprocess text and a **Multinomial Naive Bayes** classifier to accurately detect spam messages.

This project demonstrates the complete machine learning pipeline, from data preprocessing to model training and prediction.

---

## 🚀 Features

- 📩 Detects Spam and Ham messages
- 🧹 Text preprocessing and cleaning
- 🔤 Converts text into numerical features using CountVectorizer
- 🤖 Machine Learning model using Multinomial Naive Bayes
- 📊 Model evaluation with accuracy score
- ⚡ Fast and efficient predictions

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Jupyter Notebook

---

## 📂 Project Structure

```
Email-Spam-Detection/
│
├── spam.csv
├── Email_Spam_Detection.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/dipesh88-ui/E-Spam-Detection.git
```

Move into the project directory:

```bash
cd E-Spam-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Email_Spam_Detection.ipynb
```

Run all cells to train the model and test predictions.

---

## 📊 Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Text Preprocessing
4. Feature Extraction using CountVectorizer
5. Train-Test Split
6. Model Training (Multinomial Naive Bayes)
7. Model Evaluation
8. Spam Prediction

---

## 📈 Algorithms Used

- Multinomial Naive Bayes
- CountVectorizer (Feature Extraction)

---

## 📷 Sample Prediction

| Input Message | Prediction |
|--------------|------------|
| Congratulations! You have won ₹10,000. Click here now! | 🚫 Spam |
| Hi, are we meeting today at 5 PM? | ✅ Ham |

---

## 📌 Future Improvements

- Deploy using Streamlit or Flask
- Add TF-IDF Vectorizer
- Improve accuracy using advanced ML models
- Support multiple languages
- Add Email (.eml) file classification

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Dipesh Kumar**

- GitHub: https://github.com/dipesh88-ui

---

## ⭐ Support

If you found this project useful, don't forget to **Star ⭐ the repository**.
