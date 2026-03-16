
# AI Research Project | Fake News Detection & News Category Classification

This repository contains the extended implementation of my **B.Tech Final Year Project**, focused on **Fake News Detection and News Category Classification using Deep Learning and Natural Language Processing (NLP).**

The project builds upon my **IEEE conference research paper** and introduces additional improvements including **DistilBERT-based classification and a GUI application for real-time predictions.**

Research Paper
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

## PROJECT OVERVIEW

With the rapid growth of digital media platforms, identifying misinformation and automatically categorizing news articles has become a critical challenge.

This project develops a **hybrid Artificial Intelligence system** capable of:

• Detecting fake vs real news articles
• Classifying news into multiple categories
• Providing real-time predictions through a graphical interface

The system combines **deep learning architectures with transformer-based embeddings** to improve classification accuracy.

## KEY FEATURES

• Fake News Detection using **Bidirectional Recurrent Neural Networks (BiRNN)**
• News Category Classification using **DistilBERT Transformer**
• Hybrid **BiRNN + MLP deep learning architecture**
• Complete **NLP preprocessing pipeline**
• Real-time prediction using **Tkinter GUI application**
• Performance evaluation using **accuracy, precision, recall and F1-score**
• Visualization of model training and performance metrics

## AI / MACHINE LEARNING TECHNOLOGIES

Programming Language
Python

Deep Learning Models
• Recurrent Neural Networks (RNN)
• Bidirectional RNN (BiRNN)
• Multi-Layer Perceptron (MLP)
• DistilBERT Transformer Model

Natural Language Processing
• Tokenization
• Stopword Removal
• Stemming
• Lemmatization
• Text Padding

Libraries and Frameworks
• TensorFlow / Keras
• PyTorch
• HuggingFace Transformers
• Scikit-learn
• NumPy
• Pandas
• Matplotlib

## MODEL ARCHITECTURE

The project contains two AI pipelines.

Fake News Detection

A hybrid deep learning architecture is used for binary classification.

BiRNN → Feature Extraction
MLP → Classification
Output → Fake / Real

Model Accuracy Achieved
95.44%

News Category Classification

The project uses **DistilBERT Transformer embeddings** to perform multi-class news category classification.

Model Accuracy Achieved
95.12%

## DATASETS

The models were trained using publicly available datasets.

• IFND (Indian Fake News Dataset)
• News Category Dataset

The datasets were cleaned and processed using standard NLP techniques before model training.

## GRAPHICAL USER INTERFACE

The project includes a **Tkinter-based GUI application** for real-time news prediction.

The interface allows users to:

• Enter news text
• Detect whether the news is **fake or real**
• Predict the **news category**

The GUI demonstrates the trained AI models in a **user-friendly interactive format.**

## RESEARCH PUBLICATION

This project is based on the research paper:

Fake News Detection using Bidirectional Recurrent Neural Networks

Published in an **IEEE Conference** and indexed in **Scopus / Web of Science.**

Paper Link
[https://ieeexplore.ieee.org/document/11042304](https://ieeexplore.ieee.org/document/11042304)

## REPOSITORY STRUCTURE

Btech-Final-Year-Project

.ipynb_checkpoints/
Notebook checkpoints

logs/
Training logs

news_category_model/
DistilBERT trained model files

news_category_model_trainer/
Training related artifacts

hybrid_model.h5
Trained hybrid BiRNN + MLP model

tokenizer.pkl
Saved tokenizer used for preprocessing

label_encoder.pkl
Label encoding for classification

training_history.pkl
Model training history

DistilBERT for News Category Classification.ipynb
mlprnn.ipynb
mlpbirnn.ipynb
Jupyter notebooks for training and experimentation

NEWS.csv
CATEGORY.csv
Datasets used for model training

Multiple PNG / JPG images
Model graphs
Confusion matrices
GUI screenshots
Prediction outputs

## PROJECT VISUALS

The repository includes visual outputs demonstrating model performance and application interface.

Examples include:

• Model accuracy graphs
• Confusion matrices
• Classification reports
• GUI interface screenshots
• Real-time prediction outputs

## AUTHOR

Yogesh Yelewad
B.Tech Electronics and Computer Engineering
SRM Institute of Science and Technology

LinkedIn
[https://www.linkedin.com/in/yogeshyelewad](https://www.linkedin.com/in/yogeshyelewad)

GitHub
[https://github.com/yb0297](https://github.com/yb0297)

## ACKNOWLEDGMENT

This project was completed as part of my **B.Tech Final Year Project at SRM Institute of Science and Technology** under faculty guidance.

## LICENSE

This repository is shared for **research and educational purposes only.**

---

If you want, I can also show you **3 small GitHub improvements that will make your project look like a professional AI research repository instead of a student project** (this matters a lot for recruiters).
