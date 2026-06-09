# Sliding Window Attention

Sliding Window Attention restricts the attention mechanism to a fixed window size around each token.

## 🖼️ Diagram
![Sliding Window Attention Diagram](../images/sliding_window.png)

## 📄 Original Paper
- **Title:** [Longformer: The Long-Document Transformer](https://arxiv.org/abs/2004.05150)
- **Year:** 2020
- **Authors:** Beltagy et al.

## 💡 Key Concept
Instead of quadratic complexity relative to sequence length, sliding window attention has linear complexity. Information still propagates across the entire sequence through stacked layers.
