# Awesome-Attention
## Types of Attention Mechanisms in AI

Attention mechanisms allow neural networks to focus on specific parts of an input sequence, revolutionized Natural Language Processing (NLP), and formed the foundation of modern Transformer models.

## 1. Core Structural Types

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Self-Attention** | Relates different positions of a single sequence to compute a representation (e.g., matching a pronoun to its noun). | 2016 | [Cheng et al.](https://arxiv.org/abs/1601.06733) |
| **Cross-Attention** | Relates positions from two different sequences (e.g., Queries from one, Keys/Values from another). | 2017 | [Vaswani et al.](https://arxiv.org/abs/1706.03762) |
| **Multi-Head Attention** | Runs multiple attention mechanisms in parallel to attend to information from different representation subspaces. | 2017 | [Vaswani et al.](https://arxiv.org/abs/1706.03762) |

## 2. Global vs. Local Scope

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Global (Soft) Attention** | Attends to all words or patches in the input sequence simultaneously. Accurate but $O(N^2)$ complexity. | 2014 | [Bahdanau et al.](https://arxiv.org/abs/1409.0473) |
| **Local (Hard) Attention** | Focuses on a small, selected window of the input. Efficient but non-differentiable (often uses RL). | 2015 | [Xu et al.](https://arxiv.org/abs/1502.03044) |

## 3. Advanced LLM & Efficiency Optimizations

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **FlashAttention** | Exact, hardware-aware algorithm that speeds up training/inference by reducing GPU memory I/O. | 2022 | [Dao et al.](https://arxiv.org/abs/2205.14135) |
| **Multi-Query Attention (MQA)** | Uses multiple heads for Queries but a single head for Keys/Values to reduce KV cache size. | 2019 | [Shazeer](https://arxiv.org/abs/1911.02150) |
| **Grouped-Query Attention (GQA)** | Groups query heads to share Key/Value heads, balancing Multi-Head and Multi-Query performance. | 2023 | [Ainslie et al.](https://arxiv.org/abs/2305.13245) |
| **Sliding Window Attention** | Restricts attention to a fixed window around each token, reducing complexity from quadratic to linear. | 2020 | [Beltagy et al.](https://arxiv.org/abs/2004.05150) |

## 4. Multi-Modal & Domain-Specific Variants

| Attention Mechanism | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Cross-Modal Attention** | Aligns information across different media (e.g., mapping text tokens to visual patches). | 2015 | [Xu et al.](https://arxiv.org/abs/1502.03044) |
| **Spatial Attention** | Focuses on specific geometric regions within an image, emphasizing relevant visual features. | 2015 | [Jaderberg et al.](https://arxiv.org/abs/1506.02025) |
| **Channel Attention** | Evaluates inter-dependencies between feature map channels to emphasize meaningful object traits. | 2017 | [Hu et al.](https://arxiv.org/abs/1709.01507) |


---

## ✨ Star History


[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Attention&type=date&legend=bottom-right)](https://www.star-history.com/#ishandutta2007/Awesome-Attention&type=date&legend=bottom-right)

---

<div align="center">

**Made with ❤️ for the AI community**  
Last updated: June 2026

[**⬆ Back to Top**](#awesome-attention)

</div>
