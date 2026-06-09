# Awesome-Attention
## Types of Attention Mechanisms in AI

Attention mechanisms allow neural networks to focus on specific parts of an input sequence, revolutionized Natural Language Processing (NLP), and formed the foundation of modern Transformer models.

## 1. Core Structural Types

* **Self-Attention (Scaled Dot-Product Attention):** Relates different positions of a single sequence to compute a representation of the same sequence (e.g., matching a pronoun to its noun within a sentence).
* **Cross-Attention:** Relates positions from two different sequences. The Queries come from one sequence, while the Keys and Values come from another (e.g., translating English to French).
* **Multi-Head Attention:** Runs multiple self-attention mechanisms (heads) in parallel. This allows the model to jointly attend to information from different representation subspaces at different positions.

## 2. Global vs. Local Scope

* **Global (Soft) Attention:** Attends to all words or patches in the input sequence simultaneously. It is highly accurate but computationally expensive ($O(N^2)$ complexity).
* **Local (Hard) Attention:** Focuses only on a small, selected window of the input sequence. It is computationally efficient but non-differentiable, often requiring reinforcement learning to train.

## 3. Advanced LLM & Efficiency Optimizations

Deploying Large Language Models (LLMs) requires specialized attention variants to overcome the memory bottlenecks of long context windows:

* **FlashAttention:** An exact, hardware-aware attention algorithm. It speeds up training and inference by reducing the memory read/write operations between GPU SRAM and HBM.
* **Multi-Query Attention (MQA):** Uses multiple heads for Queries, but only a single key and value head. This drastically reduces the size of the KV cache and speeds up inference.
* **Grouped-Query Attention (GQA):** A middle ground between Multi-Head and Multi-Query attention. It groups query heads together, with each group sharing a single Key/Value head, balancing speed and accuracy.
* **Sliding Window Attention (Local/Sparse Attention):** Restricts the attention mechanism to a fixed window size around each token, reducing computational complexity from quadratic to linear.

## 4. Multi-Modal & Domain-Specific Variants

* **Cross-Modal Attention:** Aligns information across different types of media, such as mapping text tokens to visual patches in image generators (e.g., Stable Diffusion, Midjourney).
* **Spatial Attention:** Focuses on specific geometric regions within an image, driving early convolutional neural networks (CNNs) in computer vision tasks.
* **Channel Attention:** Evaluates the inter-dependencies between feature map channels to emphasize meaningful object characteristics in image recognition.

