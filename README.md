
# AI Research Project | Fake News Detection & News Category Classification

This repository contains the **extended implementation of my B.Tech Final Year Project**, focused on **Fake News Detection and News Category Classification using Deep Learning and Natural Language Processing (NLP).**

The project builds upon my **IEEE conference research paper** and introduces additional improvements including **DistilBERT based classification and a GUI application for real-time predictions.**

Research Paper:
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

---

# Project Overview

With the rapid growth of digital media platforms, identifying **misinformation and automatically categorizing news articles** has become a critical challenge.

This project develops a **hybrid Artificial Intelligence system** capable of:

• Detecting **fake vs real news articles**
• Classifying news into **multiple categories**
• Providing **real-time predictions through a graphical interface**

The system combines **deep learning architectures with transformer-based embeddings** to improve classification accuracy.

---

# Key Features

* Fake News Detection using **Bidirectional Recurrent Neural Networks (BiRNN)**
* News Category Classification using **DistilBERT Transformer**
* Hybrid **BiRNN + MLP architecture**
* NLP preprocessing pipeline
* Real-time prediction through **Tkinter GUI**
* Performance evaluation using **accuracy, precision, recall and F1-score**
* Training visualization and performance graphs

---

# AI / Machine Learning Technologies

### Programming Language

Python

### Deep Learning

* Recurrent Neural Networks (RNN)
* Bidirectional RNN (BiRNN)
* Multi Layer Perceptron (MLP)
* Transformer Models

### Natural Language Processing

* Tokenization
* Stopword Removal
* Stemming
* Lemmatization
* Text Padding

### Libraries & Frameworks

* TensorFlow / Keras
* PyTorch
* HuggingFace Transformers
* Scikit-learn
* NumPy
* Pandas
* Matplotlib

---

# Model Architecture

The system consists of **two major AI pipelines**.

## 1️⃣ Fake News Detection

A **hybrid deep learning architecture** is used for binary classification.

BiRNN → Feature Extraction
↓
MLP → Classification
↓
Output: Fake / Real

Performance Achieved

Accuracy: **95.44%**

---

## 2️⃣ News Category Classification

For multi-class classification, the project uses a **DistilBERT Transformer model** to generate contextual embeddings and perform category prediction.

Performance Achieved

Accuracy: **95.12%**

---

# Dataset

The models were trained using publicly available datasets:

* **IFND (Indian Fake News Dataset)**
* **News Category Dataset**

Data was preprocessed using standard NLP techniques before model training.

---

# Graphical User Interface

The project includes a **Tkinter-based GUI application** that allows users to interact with the trained models.

Users can:

* Enter news text
* Detect if the article is **fake or real**
* Predict the **news category**

This provides a **real-time demonstration of the trained AI models.**

---

# Research Publication

This project is based on the research paper:

**Fake News Detection using Bidirectional Recurrent Neural Networks**

Published in an **IEEE Conference** and indexed in **Scopus / Web of Science.**

Paper Link
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

---

# Repository Structure

```
Btech-Final-Year-Project
│
├── news_category_model/
│   └── DistilBERT trained model files
│
├── news_category_model_trainer/
│   └── training artifacts
│
├── *.ipynb
│   └── Jupyter notebooks for experiments and training
│
├── *.h5
│   └── trained deep learning models
│
├── *.safetensors
│   └── transformer model weights
│
├── *.csv
│   └── datasets used for training
│
└── *.png / *.jpg
    └── results, training graphs and GUI screenshots
```

---

# Screenshots

The repository includes visual outputs such as:

* Model training accuracy graphs
* Confusion matrix results
* GUI application interface
* Prediction outputs

These demonstrate the performance and usability of the AI system.

---

# Author

Yogesh Yelewad
B.Tech Electronics and Computer Engineering
SRM Institute of Science and Technology

LinkedIn
[https://www.linkedin.com/in/yogeshyelewad](https://www.linkedin.com/in/yogeshyelewad)

GitHub
[https://github.com/yb0297](https://github.com/yb0297)

---

# Acknowledgment

This project was completed as part of my **B.Tech Final Year Project at SRM Institute of Science and Technology** under faculty guidance.

---

# License

This repository is shared for **research and educational purposes only.**

 show you **one small section that makes AI recruiters immediately trust the project more (almost like a production ML repo)**.
