# Exploring Gen-AI

# Core Concepts: Natural Language Processing (NLP)

This repository explores the fundamental building blocks of modern language models, progressing from basic text processing to advanced deep learning architectures.

## 1. Artificial Intelligence (AI)
The broader field of creating systems capable of performing tasks that typically require human intelligence. In this context, we focus on **NLP (Natural Language Processing)**—teaching machines to understand, interpret, and generate human language.

## 2. Tokenization
The first step in any NLP pipeline. It is the process of breaking raw text into smaller units called **tokens** (words, sub-words, or characters).
* *Concept:* Converting the sentence `"AI is great"` into `["AI", "is", "great"]`.

## 3. Embeddings
The translation of tokens into **vectors** (lists of numbers). This places words in a multi-dimensional geometric space where words with similar meanings are located close together.
* *Concept:* Mathematically, the vector for "King" minus "Man" plus "Woman" results in a vector closest to "Queen."

## 4. Gensim
A specialized library used for **unsupervised semantic modeling**. It focuses on extracting meaning from raw text using statistics.
* *Key Capabilities:* It is the industry standard for training **Word2Vec** (creating embeddings) and **Topic Modeling** (discovering abstract themes in large document collections) without needing labeled data.

## 5. Attention Mechanism
A breakthrough technique that allows models to "focus" on different parts of a sentence when processing a specific word. It solves the problem of context.
* *Concept:* In the sentence *"The animal didn't cross the street because **it** was too tired"*, attention helps the model understand that *"it"* refers to the *animal*, not the *street*.

## 6. Transformers
The modern architecture that replaced older sequential models (like RNNs). Transformers utilize **Self-Attention** mechanisms to process entire sequences of data simultaneously (parallel processing).
* *Significance:* This architecture is the foundation of modern Large Language Models (like BERT and GPT), allowing for faster training on massive datasets.