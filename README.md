# Neural_Network_SMS_Text-Classifier-
# 📩 Neural Network SMS Text Classifier

A Deep Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using TensorFlow and Keras.

This project was developed as part of the **freeCodeCamp Machine Learning with Python Certification**.

---

## 📌 Project Overview

The goal of this project is to build a neural network capable of predicting whether an SMS message is spam or not.

The model is trained on a labeled SMS dataset and uses Natural Language Processing (NLP) techniques to preprocess text before classification.

---

## 🚀 Features

- Classifies SMS messages into Spam or Ham
- Text preprocessing using TensorFlow
- Neural Network built with TensorFlow/Keras
- High prediction accuracy
- Predicts probability scores
- Tested using freeCodeCamp evaluation

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Google Colab

---

## 📂 Dataset

The project uses the SMS Spam Collection dataset provided by freeCodeCamp.

Classes:
- Ham (Not Spam)
- Spam

---

## 🧠 Model Architecture

- Text Vectorization Layer
- Embedding Layer
- Global Average Pooling
- Dense Hidden Layer
- Output Layer (Sigmoid Activation)

Loss Function:
- Binary Crossentropy

Optimizer:
- Adam

Metric:
- Accuracy

---

## 📊 Results

The trained model successfully classifies SMS messages with high accuracy and passes the freeCodeCamp testing requirements.

Example Predictions:

| Message | Prediction |
|---------|------------|
| Congratulations! You have won a prize. | Spam |
| Are we meeting tomorrow? | Ham |
| Call now to claim your reward! | Spam |
| I'll reach home by 6 PM. | Ham |

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Neural_Network_SMS_Text-Classifier.git
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install required libraries.

```bash
pip install tensorflow pandas numpy
```

4. Run all notebook cells.

---

## 📁 Project Structure

```
Neural_Network_SMS_Text-Classifier/
│
├── Copy of fcc_sms_text_classification.ipynb
├── README.md
└── LICENSE
```

---

## 🎯 Certification

This project is part of the **freeCodeCamp Machine Learning with Python Certification**.

---

## 👩‍💻 Author

**Siddi Kiranmayi**

GitHub: https://github.com/siddikiranmayi-cloud

---

## ⭐ Acknowledgements

- freeCodeCamp
- TensorFlow
- Google Colab
- Keras
