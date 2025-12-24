# BTech Final Year Project  
## News Category Classification using Deep Learning

This repository contains my **B.Tech Final Year Project**, which focuses on **News Category Classification** using **Deep Learning and NLP** techniques.

The project uses **DistilBERT** for embeddings and **RNN / BiRNN / MLP hybrid models** for classification.

---

## 📂 Project Structure

- `news_category_model/` – Trained DistilBERT model and tokenizer files  
- `news_category_model_trainer/` – Training-related model artifacts  
- `*.ipynb` – Jupyter notebooks for experiments  
- `*.h5` – Trained Keras/TensorFlow models (**large files**)  
- `*.safetensors` – Transformer model files (**large files**)  
- `*.csv` – Datasets  
- `*.png / *.jpg` – Graphs, UI screenshots, results  

---

## ⚠️ Important: Large Files Stored with Git LFS

Some model files exceed **100 MB**. GitHub ZIP downloads will **not** include the actual models; instead, you will get a small pointer file (~KB).  

> Do NOT download using ZIP if you want full models.

---

## ✅ How to Download the Full Project (Original File Sizes)

Follow these steps to get **all files including large models**:

cd C:\Users\HP\Downloads
git clone https://github.com/yb0297/Btech-Final-Year-Project.git
cd Btech-Final-Year-Project
git lfs pull
