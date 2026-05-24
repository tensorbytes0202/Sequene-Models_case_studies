# 🚀 NLP Projects Collection  
## Fine-Tuning BERT on SQuAD + Sentiment Analysis using LSTM

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge&logo=tensorflow"/>
  <img src="https://img.shields.io/badge/HuggingFace-Transformers-yellow?style=for-the-badge&logo=huggingface"/> 
  <img src="https://img.shields.io/badge/PyTorch-NLP-red?style=for-the-badge&logo=pytorch"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

# 📌 Overview

This repository contains two advanced Natural Language Processing (NLP) projects built using modern Deep Learning frameworks.

### 🔹 Projects Included
- 🧠 **Question Answering using BERT (SQuAD Dataset)**
- 🎬 **Sentiment Classification on IMDB Reviews using LSTM**

Both projects demonstrate:
- Data preprocessing
- Model training
- Fine-tuning
- Evaluation metrics
- Visualization of performance graphs
- Real-world NLP workflows

---

# 📂 Repository Structure

```bash
├── question_answering_using_bert__squad_dataset_1.ipynb
├── Sentiment_Classification_on_IMDB_Reviews_using_LSTM.ipynb
├── screenshots/
│   ├── bert_training_progress.png
│   ├── bert_loss_curve.png
│   ├── bert_token_distribution.png
│   ├── bert_train_vs_validation.png
│   ├── lstm_training_logs.png
│   ├── lstm_loss_graph.png
│   └── lstm_accuracy_graph.png
└── README.md
```

---

# 🧠 Project 1 — Question Answering using BERT

## 📖 Description

This project fine-tunes a pre-trained BERT model on the **Stanford Question Answering Dataset (SQuAD)** using Hugging Face Transformers.

The model learns to:
- Understand context paragraphs
- Predict accurate answer spans
- Perform extractive question answering

---

## ⚙️ Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Google Colab
- Matplotlib
- SQuAD Dataset

---

## 📊 Dataset Information

| Dataset | Training Samples | Validation Samples |
|----------|------------------|--------------------|
| SQuAD    | 87,599           | 10,570             |

---

# 📷 Training Screenshots

## 🔹 Dataset Loading

<p align="center">
  <img src="./screenshots/bert_training_progress.png" width="900"/>
</p>

---

## 🔹 Training Loss vs Steps

<p align="center">
  <img src="./screenshots/bert_loss_curve.png" width="800"/>
</p>

### 📈 Observation
- Initial loss decreases rapidly
- Model gradually stabilizes
- Final loss converges near **0.7**

---

## 🔹 Context Token Length Distribution

<p align="center">
  <img src="./screenshots/bert_token_distribution.png" width="800"/>
</p>

### 📈 Observation
- Most contexts lie between **120–250 tokens**
- Distribution helps in selecting max sequence length

---

## 🔹 Training vs Validation Loss

<p align="center">
  <img src="./screenshots/bert_train_vs_validation.png" width="700"/>
</p>

### 📈 Observation
- Both losses decrease consistently
- Indicates effective fine-tuning
- Minimal overfitting observed

---

# 🎬 Project 2 — Sentiment Classification using LSTM

## 📖 Description

This project performs binary sentiment classification on IMDB movie reviews using an LSTM-based Deep Learning model.

The model classifies reviews into:
- ✅ Positive
- ❌ Negative

---

## ⚙️ Technologies Used

- TensorFlow / Keras
- LSTM Networks
- IMDB Dataset
- NumPy
- Matplotlib

---

# 📷 Training Screenshots

## 🔹 Training Logs

<p align="center">
  <img src="./screenshots/lstm_training_logs.png" width="850"/>
</p>

---

## 🔹 Model Loss Graph

<p align="center">
  <img src="./screenshots/lstm_loss_graph.png" width="700"/>
</p>

### 📈 Observation
- Training loss continuously decreases
- Validation loss starts increasing after some epochs
- Indicates slight overfitting

---

## 🔹 Model Accuracy Graph

<p align="center">
  <img src="./screenshots/lstm_accuracy_graph.png" width="700"/>
</p>

### 📈 Observation
- Training accuracy reaches around **93%**
- Validation accuracy stabilizes around **85–87%**

---

# 🏆 Results Summary

| Project | Model | Accuracy |
|----------|-------|-----------|
| Question Answering | BERT | Strong QA Performance |
| Sentiment Analysis | LSTM | ~93% Training Accuracy |

---

# 🚀 How to Run

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

## 2️⃣ Install Dependencies

```bash
pip install transformers datasets torch tensorflow matplotlib numpy
```

---

## 3️⃣ Run Notebooks

### BERT QA Project
```bash
jupyter notebook question_answering_using_bert__squad_dataset_1.ipynb
```

### LSTM Sentiment Analysis
```bash
jupyter notebook Sentiment_Classification_on_IMDB_Reviews_using_LSTM.ipynb
```

---

# 📌 Key Learning Outcomes

✅ Fine-tuning Transformer Models  
✅ Sequence Modeling with LSTM  
✅ NLP Data Preprocessing  
✅ Tokenization & Padding  
✅ Visualization of Training Metrics  
✅ Model Evaluation Techniques  

---

# 🔮 Future Improvements

- Add RoBERTa / DistilBERT implementation
- Deploy models using Streamlit
- Add confusion matrix & F1-score
- Hyperparameter tuning
- Real-time inference API

---

# 👨‍💻 Author

### Aditya Sikarwar
AI Engineering Student | NLP & Deep Learning Enthusiast

---

# ⭐ Support

If you found this repository helpful:

⭐ Star the repo  
🍴 Fork the project  
📢 Share with others  

---

# 📜 License

This project is licensed under the MIT License.
