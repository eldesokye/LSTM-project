# 🔤 LSTM Project – Next Word Prediction

This repository contains an **LSTM-based Deep Learning project** for **next-word prediction** using natural language processing (NLP). The project includes model training, experimentation, and a simple application interface for inference.

It is designed as a **learning and portfolio project** demonstrating how recurrent neural networks (LSTM) can be applied to sequence modeling tasks in NLP.

---

## 📌 Project Overview

The goal of this project is to train an **LSTM neural network** that learns word sequences from a text corpus and predicts the **next word** given a sequence of previous words.

Key highlights:

* Text preprocessing and tokenization
* LSTM model training using Keras / TensorFlow
* Saved trained model and tokenizer
* Simple Python app for inference
* Experimentation notebook

---

## 🗂️ Project Structure

```text
LSTM-project/
│
├── app.py                 # Application script for running predictions
├── experiments.ipynb      # Model training & experimentation notebook
├── next_word_lstm.h5      # Trained LSTM model
├── tokenizer.pickle       # Saved tokenizer
├── hamlet.txt             # Training text corpus
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
├── LICENSE                # MIT License
└── .gitignore
```

---

## 🧠 Model Description

* **Architecture**: LSTM (Long Short-Term Memory)
* **Task**: Next-word prediction
* **Input**: Sequence of words
* **Output**: Predicted next word

The model was trained on the provided text corpus (`hamlet.txt`) and saved as `next_word_lstm.h5` along with its tokenizer.

---

## 🛠️ Tech Stack

* **Python 3.9+**
* **TensorFlow / Keras**
* **NumPy**
* **Pickle**
* **Jupyter Notebook**

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/eldesokye/LSTM-project.git
cd LSTM-project
```

### 2️⃣ Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\\Scripts\\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

You can run the prediction app using:

```bash
python app.py
```

The script will:

* Load the trained LSTM model
* Load the tokenizer
* Accept a text prompt
* Predict the next word

---

## 🧪 Training & Experiments

Model training and experiments were conducted in:

```text
experiments.ipynb
```

This notebook includes:

* Text preprocessing
* Sequence generation
* Model architecture definition
* Training process
* Evaluation and testing

---

## 📈 Example Use Case

```text
Input:  "To be or not to"
Output: "be"
```

(Example output may vary depending on training and randomness.)

---

## 🔮 Future Improvements

* Add Beam Search for better predictions
* Train on larger datasets
* Add temperature sampling
* Build a FastAPI or Streamlit interface
* Deploy the model as an API

---

## 👨‍💻 Author

**Hesham El Desoky**
Machine Learning & Backend Engineer

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

⭐ If you find this project helpful, consider giving it a star!
