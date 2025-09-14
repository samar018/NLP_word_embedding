# Text Preprocessing with Hugging Face

## Overview

This project demonstrates a comprehensive text preprocessing pipeline for Natural Language Processing (NLP) tasks using Hugging Face transformers, SpaCy, and NLTK. The pipeline includes tokenization, lemmatization, stopword removal, and conversion of text into embeddings using a pretrained DistilBERT model.

The notebook also showcases how to apply this preprocessing to real-world datasets such as the IMDB movie reviews dataset for sentiment analysis.

## Features

- Tokenization using Hugging Face tokenizers
- Lemmatization with SpaCy
- Stopword removal using NLTK and SpaCy stopword lists
- Conversion of clean text into numerical embeddings with DistilBERT
- Example usage with the IMDB dataset from Hugging Face datasets library

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

Additionally, download the necessary SpaCy model and NLTK data:

```bash
python -m spacy download en_core_web_sm
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
```

## Usage

Open and run the Jupyter notebook `Word_embeddings_NLP/text_preprocessing_hf.ipynb` to explore the preprocessing steps and example usage.

The notebook covers:

- Tokenization and sentence splitting
- Lemmatization and part-of-speech tagging
- Stopword removal
- Creating embeddings from text using DistilBERT
- Applying preprocessing to the IMDB sentiment analysis dataset

## License

This project is provided as-is for educational purposes.
