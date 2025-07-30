# 🔮 Next Word Prediction using GRU (RNN)

This project uses a **Gated Recurrent Unit (GRU)** model to perform **next-word prediction** on a text dataset. Built with **TensorFlow/Keras**, it demonstrates how deep learning can be applied to language modeling and text generation.

---

## 📊 Features

- 🧠 Builds a character-level or word-level prediction model using **GRU**
- 📚 Trains on a custom text dataset (e.g., stories, articles)
- 🔁 Uses sequential text input for predicting the next word/token
- 💾 Saves model after training (`next_word_gru_model.h5`)
- 📈 Plots loss during training for model performance tracking

---

## 🧰 Tech Stack

- **Python 3.10+**
- **TensorFlow / Keras**
- **NumPy / Matplotlib**
- **NLTK / re** (for preprocessing)

---

## 📂 Dataset

- You can use **any large text corpus** (e.g., novels, articles)
- Text is tokenized, converted to sequences, and mapped for prediction
- Sample dataset provided in `data.txt`

---

## 🚀 Installation


**1. Clone the repo**
- git clone https://github.com/Kuntalsvyas/Next-Word-Prediction-GRU.git
- cd Next-Word-Prediction-GRU

**2. Create and activate a virtual environment**
- python -m venv venv
- source venv/bin/activate  # On Windows: venv\Scripts\activate

**3. Install the dependencies**
- pip install -r requirements.txt

**4. Run the training script**
- python next_word_gru.py

---

# 🧪 How It Works
- Load and clean text data
- Tokenize and create input sequences
- Train a GRU-based neural network
- Predict the next word given a partial sentence

---

# 📌 Future Enhancements
 - Add LSTM or Transformer-based model
 - Deploy with Streamlit for live demo
 - Add text temperature control for creative generation

---

# 🙌 Author
Built with 💡 by Kuntal Vyas
If you found this helpful, please ⭐ the repo!
