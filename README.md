# 📰 Neural Headline Generation with Seq2Seq + VAE + Beam Search

This project implements a **neural sequence-to-sequence (seq2seq) model** for **automated headline generation** from news articles, trained on the **Gigaword** dataset. It integrates powerful components like **Bidirectional GRUs**, **Attention Mechanisms**, **Variational Autoencoders (VAEs)**, and **Beam Search** decoding to produce context-aware and coherent headlines.

---

## 🧩 Motivation

Automatically summarizing and condensing large bodies of text into meaningful headlines is a key challenge in natural language generation. This project combines several state-of-the-art deep learning techniques to explore the frontiers of abstractive summarization and controlled text generation.

---

## 🧠 Model Architecture

- **Encoder**:  
  - Bidirectional GRU-based encoder processes input news article sequences from both directions.
  
- **Latent Space**:
  - A **Variational Autoencoder (VAE)** captures latent representations of input sequences, allowing richer semantic modeling and improved generalization.

- **Decoder**:
  - Attention-enhanced GRU decoder attends to relevant parts of the input.
  - Uses **Beam Search** during inference for generating high-quality, coherent summaries.

---

## 🛠️ Technologies Used

- **Python 3**
- **TensorFlow / Keras**
- **NumPy / Pandas**
- **Gigaword Dataset** (preprocessed subset)
- **Matplotlib / Seaborn** for visualization

---

## 🧪 Key Features

- 🧠 **Seq2Seq Modeling**: Encoder-decoder architecture tailored for text generation
- 🔁 **Bidirectional GRUs**: Captures both past and future context
- 🌀 **VAE Integration**: Models variability in semantic structure via probabilistic latent space
- 🎯 **Attention Mechanism**: Improves focus and relevance of generated headlines
- 🧭 **Beam Search Decoding**: Enhances fluency and contextuality during generation
