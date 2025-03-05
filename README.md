# 🚀 RNN-Based Next-Word Prediction Model

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange.svg)](https://www.tensorflow.org/)

---

## 🔍 Overview

This project implements an RNN-based language model using TensorFlow/Keras to predict the next word in a sentence. The model is trained on a text dataset after comprehensive data preprocessing, including lowercasing, punctuation removal, and tokenization. It employs a sliding-window approach to create input-output sequences, enabling the model to generate plausible next-word predictions based on user input.

**Technologies & Libraries:**
- **Python 3** (NumPy, regex, JSON, etc.)
- **TensorFlow/Keras** for deep learning
- **Matplotlib** for visualizing training performance

---

## ✨ Features

- **Advanced Text Preprocessing:**  
  Cleans data by converting text to lowercase, removing punctuation, and eliminating extra spaces.

- **Robust Tokenization & Sequencing:**  
  Converts text into numerical sequences using a sliding window technique, enabling effective training for next-word prediction.

- **Deep Learning Model:**  
  Uses an Embedding layer combined with two stacked SimpleRNN layers to capture temporal dependencies in text.

- **Training Insights:**  
  Automatically stores training metrics (loss and accuracy) in a JSON file for detailed performance visualization.

- **Interactive Prediction:**  
  Provides a command-line interface for users to input a phrase and receive a next-word prediction.




