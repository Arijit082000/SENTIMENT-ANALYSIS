# Instagram Sentiment Analysis: Traditional NLP (VADER) vs LLM (RoBERTa)

##  Project Overview

This repository compares two different approaches for sentiment analysis
on Instagram comments:

1.  **Traditional NLP using NLTK VADER**
2.  **Transformer-based Large Language Model (RoBERTa)**

Both models analyze the same Instagram comments after preprocessing,
emoji handling, and language translation. The purpose of this project is
to compare a lightweight lexicon-based approach with a modern
transformer-based language model.

------------------------------------------------------------------------

##  Objectives

-   Analyze Instagram comments.
-   Handle emojis and multilingual text.
-   Compare Traditional NLP with Transformer-based NLP.
-   Evaluate differences in sentiment predictions.
-   Understand the advantages and limitations of both methods.

------------------------------------------------------------------------

##  Repository Structure

    ├── Sentiment Analysis Using NLTK.ipynb
    ├── Sentiment Analysis Using RoBERTa.ipynb
    ├── README.md

------------------------------------------------------------------------

#  Project 1: Traditional NLP using NLTK VADER

### Workflow

-   Load Instagram comments dataset
-   Emoji preprocessing
-   Translate comments to English
-   Clean text
-   Apply VADER Sentiment Analyzer
-   Classify into Positive, Neutral and Negative
-   Visualize sentiment distribution

### Technologies

-   Python
-   Pandas
-   NLTK
-   VADER
-   Emoji
-   Deep Translator
-   Matplotlib

### Advantages

-   Fast
-   Lightweight
-   No GPU required

### Limitations

-   Rule-based
-   Limited contextual understanding
-   Less accurate for complex sentences

------------------------------------------------------------------------

#  Project 2: Transformer-based NLP using RoBERTa

### Workflow

-   Load Instagram comments
-   Emoji preprocessing
-   Translate comments to English
-   Load pretrained RoBERTa model
-   Predict sentiment using Transformer
-   Visualize results

### Technologies

-   Python
-   Pandas
-   Transformers
-   Hugging Face
-   RoBERTa
-   PyTorch

### Advantages

-   Context-aware
-   Better semantic understanding
-   Higher accuracy

### Limitations

-   Slower inference
-   Larger model size
-   Higher computational requirements

------------------------------------------------------------------------

#  VADER vs RoBERTa Comparison

  Feature                 VADER            RoBERTa
  ----------------------- ---------------- ----------------------
  Type                    Lexicon-Based    Transformer LLM
  Speed                   ⭐⭐⭐⭐⭐       ⭐⭐⭐
  Accuracy                ⭐⭐⭐           ⭐⭐⭐⭐⭐
  Context Understanding   Limited          Excellent
  Resource Requirement    Low              High
  Best Use Case           Small projects   Production-grade NLP

------------------------------------------------------------------------

#  Future Improvements

-   Fine-tune RoBERTa
-   Build a Streamlit app
-   Compare with BERT and DistilBERT
-   Deploy on Hugging Face Spaces

------------------------------------------------------------------------

##  Author

**Arijit Dasgupta**

