<div align="center">

![Awesome Attention Banner](banner.svg)

# 🧠 Awesome Attention Mechanisms

[![Stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Attention?style=for-the-badge&color=gold)](https://github.com/ishandutta2007/Awesome-Attention/stargazers)
[![Forks](https://img.shields.io/github/forks/ishandutta2007/Awesome-Attention?style=for-the-badge&color=blue)](https://github.com/ishandutta2007/Awesome-Attention/network/members)
[![Issues](https://img.shields.io/github/issues/ishandutta2007/Awesome-Attention?style=for-the-badge&color=red)](https://github.com/ishandutta2007/Awesome-Attention/issues)
[![License](https://img.shields.io/github/license/ishandutta2007/Awesome-Attention?style=for-the-badge&color=green)](LICENSE)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/badge.svg)](https://github.com/sindresorhus/awesome)

**A comprehensive guide to Attention Mechanisms that powered the Transformer revolution in NLP, Computer Vision, and Generative AI.**

[Explore Types](#-types-of-attention-mechanisms) • [Efficiency Optimizations](#3-advanced-llm--efficiency-optimizations) • [Multi-Modal](#4-multi-modal--domain-specific-variants) • [Star History](#-star-history)

</div>

---

## 📖 Overview

Attention mechanisms allow neural networks to focus on specific parts of an input sequence, revolutionized **Natural Language Processing (NLP)**, and formed the foundation of modern **Transformer models** and **Large Language Models (LLMs)** like GPT-4, Claude, and Llama.

This repository serves as a technical roadmap for researchers and developers to understand the evolution of attention from early RNN-based models to hardware-aware optimizations.

---

## 🛠 Types of Attention Mechanisms

### 1. Core Structural Types 🏗️

The fundamental building blocks used in almost all modern Transformer architectures.

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Self-Attention** | Relates different positions of a single sequence to compute a representation. | 2016 | [Cheng et al.](https://arxiv.org/abs/1601.06733) |
| **Cross-Attention** | Relates positions from two different sequences (e.g., Encoder-Decoder). | 2017 | [Vaswani et al.](https://arxiv.org/abs/1706.03762) |
| **Multi-Head Attention** | Runs multiple attention mechanisms in parallel for diverse subspace learning. | 2017 | [Vaswani et al.](https://arxiv.org/abs/1706.03762) |

### 2. Global vs. Local Scope 🌐

Defining how much of the context window the model "sees" at once.

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Global (Soft) Attention** | Attends to all words/patches simultaneously. Accurate but $O(N^2)$. | 2014 | [Bahdanau et al.](https://arxiv.org/abs/1409.0473) |
| **Local (Hard) Attention** | Focuses on a small window. Efficient but non-differentiable (uses RL). | 2015 | [Xu et al.](https://arxiv.org/abs/1502.03044) |

### 3. Advanced LLM & Efficiency Optimizations ⚡

Cutting-edge variants designed to reduce memory bottlenecks and speed up inference for long-context LLMs.

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **FlashAttention** | Hardware-aware algorithm reducing GPU memory I/O. | 2022 | [Dao et al.](https://arxiv.org/abs/2205.14135) |
| **Multi-Query Attention (MQA)** | Single Key/Value head for multiple Query heads to save KV cache. | 2019 | [Shazeer](https://arxiv.org/abs/1911.02150) |
| **Grouped-Query Attention (GQA)** | Balanced approach grouping queries to share KV heads. | 2023 | [Ainslie et al.](https://arxiv.org/abs/2305.13245) |
| **Sliding Window Attention** | Fixed window attention, reducing complexity from quadratic to linear. | 2020 | [Beltagy et al.](https://arxiv.org/abs/2004.05150) |

### 4. Multi-Modal & Domain-Specific Variants 🎨

Extensions for Computer Vision, Image Generation, and Multi-modal tasks.

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Cross-Modal Attention** | Aligns information across media (e.g., Text-to-Image). | 2015 | [Xu et al.](https://arxiv.org/abs/1502.03044) |
| **Spatial Attention** | Focuses on specific geometric regions within an image. | 2015 | [Jaderberg et al.](https://arxiv.org/abs/1506.02025) |
| **Channel Attention** | Evaluates inter-dependencies between feature map channels. | 2017 | [Hu et al.](https://arxiv.org/abs/1709.01507) |

---

## ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Attention&type=date&legend=bottom-right)](https://www.star-history.com/#ishandutta2007/Awesome-Attention&type=date&legend=bottom-right)

---

<div align="center">

### 🤝 Contributing
Contributions are welcome! If you have a paper or a new mechanism to add, please open a PR.

**Made with ❤️ for the AI community**  
Last updated: June 2026

[**⬆ Back to Top**](#-awesome-attention-mechanisms)

</div>
