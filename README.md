# Quora Duplicate Question Classifier (Streamlit App)

This project is a **Quora Duplicate Question Classifier** built using **Python**, **scikit-learn**, and **Streamlit**.  
It predicts whether two questions submitted by a user convey the same meaning — a classic NLP semantic similarity problem originally from the **Quora Question Pairs Dataset**.

---

## 🚀 Features

- Predicts whether two questions are **duplicates** or **not duplicates**
- Trained on the Quora Question Pairs dataset (`train.csv`)
- ML pipeline includes text cleaning, vectorization (TF-IDF), and classification
- Interactive **Streamlit web app** for real-time predictions
- Simple, clean UI for testing multiple question pairs

---

## 📁 Project Structure
```bash
├── train.csv # Quora question pairs training data
├── Untitled.ipynb # Notebook: EDA, preprocessing, training
├── app.py # Streamlit app for prediction
├── model.pkl (optional) # Serialized trained model
├── requirements.txt # Dependencies
└── README.md # Documentation

```

---

## 🧠 Model Overview

This classifier determines if *Question 1* and *Question 2* are semantically equivalent.

### Pipeline includes:
- **Text preprocessing**
- **TF-IDF vectorization**  
- **Machine learning models** (Logistic Regression / SVM / etc.)
- **Binary classification output:**  
  - `Duplicate`  
  - `Not Duplicate`

The model can handle paraphrased, reworded, or partially similar questions.

---

## ▶️ Running the App Locally

### 1. Install required packages

pip install -r requirements.txt
2. Launch Streamlit app
bash
Copy code
streamlit run app.py
3. Usage
Enter Question 1

Enter Question 2

Click Find

The classifier will display either:

Duplicate ✔️
or
Not Duplicate ❌
## 🛠️ Technologies Used
```
Python

pandas

NumPy

scikit-learn

Streamlit

Jupyter Notebook
```

📸 Demo Screenshot
