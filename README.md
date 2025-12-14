# 📘 Natural Language Processing

## 📌 Overview

This repository contains implementations and experiments related to **Natural Language Processing (NLP)** developed as part of academic coursework and personal exploration in Artificial Intelligence.

The project focuses on applying both **classical NLP techniques** and **deep learning–based approaches** using Python and PyTorch.  
It is designed from an engineering perspective, emphasizing clarity, reproducibility, and proper evaluation of models.

---

## 🎯 Objectives

- Apply fundamental NLP techniques such as text preprocessing, tokenization, and vectorization.
- Train and evaluate supervised models for text classification tasks.
- Explore deep learning approaches for language modeling and classification.
- Provide well-documented notebooks suitable for academic and professional reference.

---

## 🗂 Repository Structure

```
ProcesamientoLenguageNatural/
├── README.md
├── README.es.md
├── requirements.txt
├── torch_helpers.py
├── spa-eng/
│   └── spa.txt
├── TP1/
│   └── Desafio_1.ipynb
├── TP2/
│   ├── tp2.ipynb
│   └── songs_dataset/
├── TP3/
│   └── TP3.ipynb
└── TP4/
    ├── Tp4.ipynb
    ├── tp4.py
    └── graphics/
```

### Contents

- **TP1/** - Introduction to word embeddings and vectorization
- **TP2/** - Language models and text generation
- **TP3/** - Recurrent architectures (RNN/LSTM) for classification
- **TP4/** - Seq2Seq with attention and Transformers for machine translation
- **torch_helpers.py** - Utilities for tokenization, padding, and training
- **spa-eng/** - Tatoeba Spanish-English translation dataset

---

## ⚙️ Installation & Setup

### Requirements

- Python 3.8+
- Jupyter Notebook
- PyTorch
- NumPy, Pandas

### Clone the repository

```bash
git clone https://github.com/sbiagiola/ProcesamientoLenguageNatural.git
cd ProcesamientoLenguageNatural
```

### (Optional) Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate    # Linux / macOS
.venv\Scripts\activate       # Windows
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run assignments

1. Navigate to the desired assignment folder (TP1/, TP2/, TP3/, TP4/)
2. Open the corresponding notebook
3. Execute cells in order

### Notebook structure

Each assignment includes:

- **Introduction**: Context and objectives
- **Data preparation**: Loading, cleaning, and tokenization
- **Implementation**: Model architectures and definitions
- **Training**: Hyperparameter configuration and optimization
- **Evaluation**: Performance metrics and result analysis
- **Conclusions**: Interpretation and lessons learned

## 🧪 Topics Covered

### TP1 - Word Embeddings
- Text vectorization (Bag of Words, TF-IDF)
- Word2Vec and pre-trained embeddings
- Semantic similarity analysis

### TP2 - Language Models
- N-grams and word prediction
- Text generation
- Author classification

### TP3 - Recurrent Networks
- RNN and LSTM architectures
- Sequence classification
- Variable-length sequence handling

### TP4 - Seq2Seq and Transformers
- English-Spanish machine translation
- Bidirectional LSTM with Bahdanau attention
- Transformer architecture
- Model comparison and performance analysis

## 🧰 Technologies Used
| Technology       | Description                   |
|------------------|-------------------------------|
| Python           | Main programming language     |
| Jupyter Notebook | Interactive experimentation   |
| PyTorch          | Deep learning framework       |
| NumPy / Pandas   | Data processing               |
| Markdown         | Documentation                 |

## 📫 Contributions
- Fork the repository
- Open an issue to report bugs or suggest improvements
- Submit a pull request

## 📄 License
- MIT License — academic and commercial use allowed with attribution

## 👤 Author
- Sebastián Biagiola — Electronic Engineer, AI Specialization
- GitHub: https://github.com/sbiagiola
