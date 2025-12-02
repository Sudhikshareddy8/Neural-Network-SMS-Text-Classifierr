# 📱 Neural Network SMS Text Classifier

This project is part of the **FreeCodeCamp Machine Learning with Python Certification**.

It classifies SMS messages as **"ham" (normal messages)** or **"spam" (advertisements)** using a **Neural Network**.

---

## 🚀 Features
- Uses the **SMS Spam Collection Dataset**
- Preprocesses and tokenizes SMS text
- Converts text to numeric sequences for training
- Builds a **Neural Network classifier** using TensorFlow/Keras
- Implements a `predict_message(message)` function that returns:
  - Probability of ham/spam (0–1)
  - Final label: `"ham"` or `"spam"`
- Evaluates model performance on test data

---

## 🧪 How to Run

### ▶️ **Using Google Colab**
1. Open the notebook: `sms_classifier.ipynb`
2. Click **Runtime → Run all**
3. After training, use:

```python
predict_message("your message here")
