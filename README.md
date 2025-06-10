# 🌿 Plant Disease Detection System

A web-based application built with Streamlit that uses a trained deep learning model to detect plant diseases from leaf images.

---

## 🚀 Features

- Predicts 38 types of plant diseases using image input.
- Fast and accurate deep learning model (TensorFlow/Keras).
- Interactive UI built with Streamlit.
- Simple navigation:
  - **Home** – Overview and instructions.
  - **About** – Dataset insights.
  - **Disease Recognition** – Upload and diagnose.
- Mobile and desktop compatible.

---

## 🛠 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Model**: TensorFlow / Keras
- **Dataset Source**: Kaggle
- **IDE Used**: Jupyter Notebook, VS Code

---

## ⚙️ How It Works

1. User uploads a leaf image via the Disease Recognition tab.
2. The model preprocesses and resizes the image.
3. It runs a prediction and outputs the most likely disease class.
4. The app displays the class name and related information (optional).

---

## 📦 Installation

```bash
git clone https://github.com/vishussingh24/Plant_Disease_Detection.git
cd Plant_Disease_Detection
pip install -r requirements.txt
streamlit run main.py