# Next Word Prediction with PyTorch

This repository contains my **first PyTorch project**, where I built a simple **Next Word Prediction** model using deep learning. The goal of this project is to understand the basics of PyTorch, neural networks, and how language models work at a fundamental level.

---

## 📌 Project Overview

Next Word Prediction is a common Natural Language Processing (NLP) task where a model predicts the most likely next word given a sequence of previous words.

In this project, I:

* Learned the **PyTorch workflow** (tensors → model → loss → optimizer → training loop)
* Implemented a **basic neural network** for word prediction
* Practiced text preprocessing and vocabulary creation
* Trained and tested the model on sample text data

This project is meant for **learning purposes** and is intentionally kept simple.

---

## 🧠 Model Description

* The model takes a sequence of words as input
* Each word is converted into a numerical representation
* A neural network learns patterns in word sequences
* The model predicts the **next most probable word**

> This is **not** a large language model (LLM), but a beginner-friendly implementation to understand the core concepts behind language modeling.

---

## 🛠️ Technologies Used

* **Python**
* **PyTorch**
* **Jupyter Notebook**

---

## 📂 Files in This Repository

* `next_word_pred.ipynb` – Jupyter Notebook containing:

  * Data preprocessing
  * Model definition
  * Training loop
  * Prediction examples
* `README.md` – Project documentation (this file)

---

## ▶️ How to Run the Project

1. Clone the repository

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install required dependencies

   ```bash
   pip install torch numpy jupyter
   ```

3. Open the notebook

   ```bash
   jupyter notebook next_word_pred.ipynb
   ```

4. Run all cells to train the model and see predictions

---

## 📊 Example Output

After training, the model can predict the next word based on an input sequence, for example:

```
Input: "deep learning is"
Predicted word: "fun"
```

(The actual output may vary depending on training and data.)

---

## 🚀 What I Learned

* Basics of **PyTorch tensors and modules**
* How training loops work
* Loss functions and optimizers
* How text can be converted into numbers for models
* Core ideas behind NLP models

---

