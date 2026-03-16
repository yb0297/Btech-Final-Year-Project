
# AI Research Project | Fake News Detection & News Category Classification using Deep Learning

This repository contains the extended implementation of my **B.Tech Final Year AI Research Project**, focused on **Fake News Detection and News Category Classification using Deep Learning and Natural Language Processing (NLP).**

The project extends the work presented in my **IEEE Conference research paper** and includes additional experimentation, model improvements, and a **GUI-based real-time prediction system.**

Research Paper (IEEE Xplore)
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

## PROJECT DESCRIPTION

With the rapid growth of online news platforms, the spread of **misinformation and unverified content** has become a major global challenge. Automatically detecting fake news and organizing news content into categories is an important task in modern information systems.

This project develops an **AI-based intelligent news analysis system** capable of:

• Detecting **fake vs real news articles**
• Classifying news into **multiple categories**
• Providing **real-time predictions using a graphical interface**

The system combines **deep learning architectures with transformer-based embeddings** to achieve high classification accuracy and reliable predictions.

## KEY CONTRIBUTIONS

• Developed a **Hybrid Deep Learning Architecture (BiRNN + MLP)** for fake news detection
• Implemented **DistilBERT Transformer model** for news category classification
• Built a **complete NLP preprocessing pipeline** for text cleaning and feature preparation
• Achieved **95%+ classification accuracy** across tasks
• Designed a **GUI-based AI application using Tkinter** for real-time predictions
• Published the research findings in an **IEEE Conference (Scopus / Web of Science indexed)**

## TECHNOLOGIES USED

Programming
Python

Artificial Intelligence
Machine Learning
Deep Learning
Natural Language Processing

Deep Learning Models
Recurrent Neural Networks (RNN)
Bidirectional Recurrent Neural Networks (BiRNN)
Multi-Layer Perceptron (MLP)
DistilBERT Transformer

Libraries and Frameworks
TensorFlow / Keras
PyTorch
HuggingFace Transformers
Scikit-learn
NumPy
Pandas
Matplotlib

## NATURAL LANGUAGE PROCESSING PIPELINE

The text data is processed through several NLP preprocessing stages before model training:

• Tokenization
• Stopword removal
• Stemming
• Lemmatization
• Text padding
• Feature encoding

## MODEL ARCHITECTURE

The project consists of **two major AI pipelines**.

1. Fake News Detection

A hybrid deep learning architecture was designed to classify news as **fake or real**.

Architecture Flow

BiRNN
↓
Feature Extraction
↓
MLP Classifier
↓
Prediction (Fake / Real)

Model Performance

Accuracy Achieved: **95.44%**

2. News Category Classification

A **DistilBERT Transformer model** is used for contextual embedding and multi-class news classification.

Categories include examples such as:

• Politics
• Sports
• Technology
• Science
• Entertainment
• World News

Model Performance

Accuracy Achieved: **95.12%**

## DATASETS

The models were trained using publicly available datasets.

IFND (Indian Fake News Dataset)
News Category Dataset

These datasets were cleaned, preprocessed, and transformed using NLP techniques before training.

## GRAPHICAL USER INTERFACE

To demonstrate the AI models interactively, a **Tkinter-based GUI application** was developed.

The GUI allows users to:

• Enter news text
• Detect whether the news is **fake or real**
• Predict the **news category**
• View prediction results instantly

This provides a **real-time AI prediction system** that showcases the trained models.

## RESEARCH PUBLICATION

This project is based on the research paper:

Fake News Detection using Bidirectional Recurrent Neural Networks

Published in an **IEEE Conference** and indexed in:

Scopus
Web of Science

Paper Link
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

## REPOSITORY STRUCTURE

Btech-Final-Year-Project

.ipynb_checkpoints/
Notebook checkpoints

logs/
Training logs and experiment outputs

news_category_model/
DistilBERT trained model files

news_category_model_trainer/
Training related artifacts

hybrid_model.h5
Trained Hybrid BiRNN + MLP model

tokenizer.pkl
Saved tokenizer used for text preprocessing

label_encoder.pkl
Label encoding for classification tasks

training_history.pkl
Model training history and metrics

DistilBERT for News Category Classification.ipynb
mlprnn.ipynb
mlpbirnn.ipynb
Jupyter notebooks used for model training and experimentation

NEWS.csv
CATEGORY.csv
Datasets used for model training

PNG / JPG Images
Model graphs
Confusion matrices
Classification reports
GUI interface screenshots
Prediction outputs

## PROJECT VISUALIZATION

The repository includes visual results demonstrating model performance:

• Training accuracy graphs
• Confusion matrices
• Classification reports
• Model performance plots
• GUI screenshots
• Real-time prediction results

## AUTHOR

Yogesh Yelewad
B.Tech Electronics and Computer Engineering
SRM Institute of Science and Technology

LinkedIn
[https://www.linkedin.com/in/yogeshyelewad](https://www.linkedin.com/in/yogeshyelewad)

GitHub
[https://github.com/yb0297](https://github.com/yb0297)

## ACKNOWLEDGMENT

This project was completed as part of my **B.Tech Final Year Research Project at SRM Institute of Science and Technology** under faculty guidance.

## LICENSE

This repository is shared for **research and educational purposes only**.

---

✅ This version is **stronger for recruiters because it highlights**

• AI research
• IEEE publication
• deep learning models
• NLP pipeline
• real application (GUI)
• model performance
• structured project explanation
