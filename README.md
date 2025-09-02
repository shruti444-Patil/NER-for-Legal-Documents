# 📑 Legal Document NER — Streamlit App

This repository contains a Named Entity Recognition (NER) system for **Legal Documents** using a **CNN + BiLSTM** model, deployed with **Streamlit**.

## 🚀 Features
- Train a CNN + RNN (BiLSTM) based NER model
- Evaluate performance (F1 score, classification report)
- Upload legal documents (TXT) and extract entities
- Simple UI powered by Streamlit

## 🛠 Installation
```bash
git clone https://github.com/yourusername/legal-ner-app.git
cd legal-ner-app
pip install -r requirements.txt
```

## ▶️ Run the App
```bash
streamlit run app.py
```

## 📂 Project Structure
```
legal-ner-app/
│-- app.py              # Main Streamlit application
│-- requirements.txt    # Python dependencies
│-- README.md           # Documentation
```

## 📊 Model
- Embedding Layer
- CNN Layer (Conv1D + GlobalMaxPooling)
- BiLSTM Layer
- TimeDistributed Dense for entity classification

## ⚖️ Notes
- Replace the dummy dataset with your **legal domain dataset (CoNLL format)** for real training.
- Extend file upload to support **PDF/DOCX** if needed.

---
👨‍💻 Developed for legal AI research and experimentation.
