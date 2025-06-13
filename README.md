# 🧠 Emotion Detection from Text Messages

This project uses machine learning and natural language processing (NLP) to detect human emotions from written text.

## 📌 Project Objective
To classify text messages into emotional categories such as joy, sadness, anger, fear, love, surprise, trust, anticipation, and neutral using a custom dataset and Logistic Regression model.

## 🛠 Tools & Technologies
- Python
- Scikit-learn
- Pandas
- TfidfVectorizer
- Logistic Regression
- Google Colab / Jupyter Notebook

## 🚀 How to Run
1. Clone this repository or open `emotion_detection.ipynb` in Google Colab.
2. Upload the `train_extended.txt` dataset.
3. Run all cells to train the model.
4. Enter a custom message to predict emotion.

## 🔍 Sample Input/Output
```python
Input: "I'm so proud of myself!"
Output: joy

Input: "Why did you do that?!"
Output: anger
```

## 📁 Project Structure
- `emotion_detection.ipynb` – Full notebook
- `emotion_detection.py` – Optional script version
- `train_extended.txt` – Labeled training data
- `README.md` – Project overview and instructions

## ✨ Future Improvements
- Upgrade to deep learning models like BERT
- Add real-time web interface using Streamlit
- Expand dataset with real-world sentences
