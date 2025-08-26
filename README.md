# 🔤 NLP Tokenizers Exploration

This repository contains a Jupyter Notebook (`tokenizers.ipynb`) that demonstrates how to use and compare different **tokenization techniques** in Natural Language Processing (NLP).  
The notebook covers tokenizers from Hugging Face Transformers, NLTK, and TorchText, and shows how they process text into tokens for downstream machine learning tasks.

## 🚀 Features
- Tokenization with **Hugging Face Transformers**:
  - `BertTokenizer` (BERT base uncased)
  - `XLNetTokenizer` (XLNet base cased)
- Tokenization with **NLTK** (`word_tokenize`)
- Tokenization with **TorchText** (`get_tokenizer`)
- Building a vocabulary with TorchText
- Inspecting token IDs, vocabulary mappings, and unknown tokens

## 📂 Project Structure
.
├── tokenizers.ipynb # Main notebook with tokenizer experiments
└── README.md # Project documentation

## 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Install dependencies:
  ```bash
  pip install transformers torch==2.2.0 torchtext==0.17.0 nltk
Download NLTK resources (inside Python):

import nltk
nltk.download("punkt")

📖 Usage

Clone this repository:

git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>


Open the notebook:

jupyter notebook tokenizers.ipynb


Run cells to explore:

Hugging Face tokenizers (BertTokenizer, XLNetTokenizer)

NLTK word_tokenize

TorchText get_tokenizer and vocabulary building

📊 Example Output
🔹 BERT Tokenizer
['learned', 'token', '##ization', 'from', 'online']

🔹 XLNet Tokenizer
['▁learned', '▁tokenization', '▁from', '▁online']

🔹 NLTK
['learned', 'tokenization', 'from', 'online']

🔹 TorchText
['learned', 'tokenization', 'from', 'online']

🔹 Vocabulary (TorchText)
{'<unk>': 0, 'learned': 1, 'tokenization': 2, 'from': 3, 'online': 4}

📌 Learning Outcomes

Understand differences between subword-based tokenizers (BERT/XLNet) and word-based tokenizers (NLTK/TorchText).

See how tokenization affects downstream tasks in NLP.

Learn how to build vocabularies for training models.

🤝 Contributing

This is a personal/academic learning project. Contributions are welcome via issues or pull requests.

⚖️ License

All Rights Reserved.
This project is for personal, academic, or internal use. You may not copy, modify, distribute, or use it commercially without explicit permission.
