# 🧠 Next Word Prediction Using LSTM

This project implements a deep learning-based **Next Word Prediction** system using **LSTM (Long Short-Term Memory)** networks. It uses text from Shakespeare's *Hamlet* and provides a simple **Streamlit web interface** for users to input text and receive predictions for the next word.

---

### 🚀 Features

- Trains an LSTM model on sequential n-gram data
- Clean text preprocessing and tokenization
- Padded sequence generation for uniform input
- Next-word prediction using trained LSTM
- Web UI built using Streamlit
- Includes additional GRU experiments for comparison

---

### 📁 Project Structure
├── app.py # Streamlit app for prediction
├── experiments.ipynb # LSTM model training notebook
├── GRU_RNN_experiments.ipynb # GRU-based training experiment
├── hamlet.txt # Text dataset (Shakespeare's Hamlet)
├── next_word_lstm.h5 # Trained LSTM model
├── next_word_GRU.h5 # Trained GRU model
├── tokenizer.pickle # Saved tokenizer object
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

### 🧠 Model Architecture

The LSTM model uses the following layers:
- Embedding layer (100-dim vectors)
- LSTM layer (150 units) + Dropout
- LSTM layer (100 units)
- Dense layer with Softmax activation for word classification

---

### 🧪 How It Works

1. The model is trained on *n-gram* sequences from Shakespeare’s Hamlet.
2. Each input is a sequence of words, and the output is the next word in that sequence.
3. Once trained, the model can predict the next word for any given input sentence.

---

### 📷 Demo Screenshot

<img src="https://github.com/yourusername/Next_Word_Prediction_Using_LSTM/raw/main/demo_screenshot.png" alt="Demo Screenshot" width="600"/>

---

### Install Dependencies 

pip install -r requirements.txt

-----

### Run the Streamlit App

streamlit run app.py

-----

### 📊 Results

The model achieves decent accuracy for classical text prediction and demonstrates the effectiveness of LSTMs in learning language patterns.

-----

### 👨‍💻 Author

- Vibhu Pratap

- GitHub: vibhupratap-007

