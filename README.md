# ML_projects
# 🧠 Predictive Keyboard using PyTorch

A neural network–based predictive text model inspired by smartphone keyboards.  
It learns from text data and suggests the next possible words based on the previous context using an LSTM (Long Short-Term Memory) network.

---

## 🚀 Overview

This project demonstrates how to build a simple **predictive keyboard** using **PyTorch** and **NLP techniques**.  
It trains an LSTM model on a text corpus (e.g., Sherlock Holmes stories) and predicts the next word in a sequence.

---

## 🧩 Features

- Tokenizes and encodes text data using `nltk`.
- Builds training sequences for next-word prediction.
- Implements a **custom LSTM model** (`PredictiveKeyboard`).
- Trains the model using **CrossEntropyLoss** and **Adam optimizer**.
- Provides a `suggest_next_words()` function for top-k next-word suggestions.

---

## 🏗️ Model Architecture

**`PredictiveKeyboard`** (PyTorch model):
- Embedding layer
- LSTM layer
- Fully connected output layer  
- Softmax activation for word prediction

---

## 📚 Dataset

You can use any large plain-text dataset.  
In this example, the project uses:
