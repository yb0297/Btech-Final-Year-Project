# Fake News Detection and News Categorization System

## Overview
This project implements an AI-based system for detecting fake news articles and categorizing news topics using Natural Language Processing and Deep Learning techniques.

The project extends my published IEEE research work by implementing an improved system with an interactive GUI for real-time predictions and additional experimentation with modern transformer models.

Research Paper:
Fake News Detection Using Bidirectional RNN  
IEEE Xplore: https://ieeexplore.ieee.org/document/11042304

This repository contains the extended implementation of the research with additional features and a user interface.

---

# Problem Statement
The rapid spread of misinformation on online platforms makes it difficult to verify the authenticity of news articles. This project aims to build an automated system capable of identifying fake news using deep learning models trained on real-world datasets.

---

# Key Features

• Fake vs Real news classification  
• News category prediction  
• NLP text preprocessing pipeline  
• Deep learning based classification models  
• Interactive GUI for real-time prediction  
• Extended implementation of published IEEE research  

---

# Dataset

Two publicly available datasets were used for training and evaluation:

1. IFND Dataset (Indian Fake News Dataset)
2. Kaggle News Category Dataset

Approximate Dataset Size:
• ~50,000 news samples  
• Balanced fake and real news distribution  

---

# Machine Learning & Deep Learning Models

### Fake News Detection
Bidirectional Recurrent Neural Network (BiRNN)

Architecture:
Embedding Layer → BiRNN → Dense Layer → MLP Classifier

### News Categorization
DistilBERT Transformer Model

Used for multi-class classification of news topics.

---

# NLP Preprocessing Pipeline

The following preprocessing techniques were applied:

1. Text cleaning
2. Tokenization
3. Stopword removal
4. Stemming
5. Lemmatization
6. Sequence padding
7. Text vectorization

Libraries used:
NLTK, Scikit-learn, TensorFlow, PyTorch

---

# Model Performance

| Model | Task | Accuracy |
|------|------|------|
| BiRNN + MLP | Fake News Detection | 95.44% |
| DistilBERT | News Categorization | 95.12% |

Evaluation metrics used:
• Accuracy  
• Precision  
• Recall  
• F1 Score  
• Confusion Matrix  

---

# System Architecture

Input News Text  
↓  
Text Preprocessing  
↓  
Tokenization & Vectorization  
↓  
Deep Learning Model  
(BiRNN / DistilBERT)  
↓  
Prediction Output  
(Fake / Real or Category)

---

# Graphical User Interface

This implementation includes a GUI application that allows users to input news text and receive real-time predictions.

GUI Features:

• User input field for news text  
• Fake/Real prediction output  
• News category prediction  
• Simple and interactive interface  

---

# Technologies Used

Programming Languages:
Python

Machine Learning / AI:
TensorFlow  
PyTorch  
Scikit-learn  

NLP Libraries:
NLTK  
Transformers  

Data Analysis:
NumPy  
Pandas  

Visualization:
Matplotlib

Development Tools:
Jupyter Notebook  
VS Code

---


---

# Research Publication

This project is based on my published research paper:

Fake News Detection Using Bidirectional RNN  
IEEE Conference Publication

IEEE Xplore Link:
https://ieeexplore.ieee.org/document/11042304

This repository contains the extended implementation with additional experimentation and a GUI interface.

---

# Future Improvements

• Deploy the model as a web application  
• Integrate real-time news APIs  
• Improve performance using larger transformer models  
• Build a browser extension for fake news detection  

---

# Author

Yogesh Yelewad  
B.Tech Electronics and Computer Engineering  
SRM Institute of Science and Technology

LinkedIn:  
https://www.linkedin.com/in/yogeshyelewad

GitHub:  
https://github.com/yb0297

