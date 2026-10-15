# Urdu NLP: Tokenization and Statistical Language Modeling

## Project Overview

This project presents an implementation of foundational Natural Language Processing techniques, with a particular focus on statistical language modeling and Urdu text processing.

It explores linguistic preprocessing, probabilistic language models, smoothing techniques, and Byte Pair Encoding (BPE) for subword segmentation.

## Project Objectives

- Develop an NLP preprocessing pipeline for raw text.
- Implement tokenization, stemming, lemmatization, POS tagging, and Named Entity Recognition.
- Build unigram and bigram language models.
- Investigate Laplace smoothing and language model perplexity.
- Implement Byte Pair Encoding for Urdu text segmentation.
- Analyze Urdu word frequencies and n-gram distributions.

## Technologies and Libraries

- Python
- Jupyter Notebook
- NLTK
- BeautifulSoup
- NumPy
- Matplotlib
- Regular Expressions

## Methodology

**1. Text Preprocessing**

Text extraction, normalization, tokenization, stopword removal, stemming, lemmatization, POS tagging, and named entity recognition.

**2. Statistical Language Modeling**

Implementation of unigram and bigram language models, including Laplace-smoothed variants and perplexity-based evaluation.

**3. Urdu Text Processing**

Urdu Unicode normalization, BPE-based segmentation, corpus statistics, and unigram, bigram, and trigram frequency analysis.

## Datasets

The coursework uses the Brown Corpus, English web text, and Urdu text resources. Dataset sources and redistribution permissions should be documented before release.

## Results

### Language Model Perplexity Comparison

| Model | Fiction | Romance |
|---|---:|---:|
| Unigram | 10.1981 | 14.1140 |
| Smoothed Unigram (Laplace) | 1408.8456 | 1328.2123 |
| Bigram | 4.1392 | 4.2556 |
| Smoothed Bigram (Laplace) | 3616.9912 | 3446.2366 |

### Preliminary Findings

The unsmoothed bigram model produced the lowest reported perplexity on both evaluation sets. Laplace-smoothed models showed considerably higher perplexity values.

These results are preliminary. The perplexity implementation, unseen n-gram handling, and evaluation consistency require validation before drawing definitive conclusions.

Additional repository outputs include generated sentences, Urdu segmentation results, and n-gram analysis artifacts.

The repository contains generated language model outputs, Urdu segmentation results, and analysis artifacts.

Quantitative results and interpretation will be documented after verification of the executable notebook.

## Future Improvements

- Compare BPE against alternative subword tokenization algorithms.
- Evaluate segmentation quality using manually annotated Urdu text.
- Investigate language modeling approaches for low-resource languages.
- Extend experiments to multilingual transformer-based models.

## Project Type

Academic coursework implementation and NLP portfolio project.
