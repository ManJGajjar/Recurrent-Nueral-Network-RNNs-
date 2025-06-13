# Recurrent Nueral Network (RNNs)
# 🔁 RNN: Sequence Parity Classifier

This project implements a simple Recurrent Neural Network (RNN) using TensorFlow/Keras to classify integer sequences based on the parity of their sum (even or odd).

## 📌 Description

- Generates random sequences of integers.
- Classifies them as `0` (even sum) or `1` (odd sum).
- Uses a simple RNN layer followed by a Dense output layer.

## 🧪 Dataset

Synthetic data:
- `1000` random integer sequences
- Variable sequence lengths, padded to fixed length
- Binary classification (even/odd)

## 🧱 Model Architecture

- `SimpleRNN` layer with 32 units
- `Dense` output layer with sigmoid activation

✅ Tasks Completed in the Notebook
 - Data generation: Random sequences and labels (even/odd sum).
 - Data preprocessing: Padding sequences using pad_sequences.
 - Model creation: Keras Sequential model with SimpleRNN and Dense layers.
 - Model compilation and training.
 - Evaluation using accuracy.

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:

```bash
pip install -r requirements.txt
