# Natural Language Processing: Language Modeling and Text Representation

This repository contains NLP coursework notebooks covering language modeling, text preprocessing, word embeddings, and text classification/clustering experiments.

## Topics covered

- **N-gram language models** — implementation of N-gram counting and conditional probability estimation.
- **Smoothing** — experiments with backoff smoothing and absolute discounting.
- **Perplexity** — evaluation of language models on held-out text.
- **Persian text preprocessing** — normalization and tokenization with Hazm, including stop-word removal, stemming, and lemmatization.
- **Word representations** — Word2Vec and GloVe embeddings, including document-level vector representations.
- **Text classification and clustering** — experiments with KNN, Random Forest, SVM, TF-IDF features, and Self-Organizing Maps (SOM).

## Repository structure

```text
.
├── NLP-02-2-HW1.pdf
├── codes/
│   ├── p2.ipynb
│   ├── p3.ipynb
│   ├── p4.ipynb
│   ├── train.csv
│   ├── val.csv
│   └── test.csv
└── report/
```

## Main technologies

- Python
- pandas and NumPy
- NLTK
- Hazm
- Gensim
- scikit-learn
- MiniSom
- Jupyter Notebook

## Getting started

Install the main dependencies:

```bash
pip install numpy pandas nltk hazm gensim scikit-learn minisom jupyter
```

Open the notebooks in `codes/` with Jupyter. Some experiments use pretrained GloVe vectors; provide the required vector file and adjust notebook paths if it is stored elsewhere.

## Data

The `train.csv`, `val.csv`, and `test.csv` files are used by the notebooks. Preserve their relative locations or update the paths in the notebooks before running them.

## Notes

The repository contains coursework experiments and original reports. The notebooks may represent separate parts of the assignment and can have different data or pretrained-model requirements.
