# Multi-Head Attention

Multi-head attention runs multiple attention mechanisms (heads) in parallel, allowing the model to jointly attend to information from different representation subspaces at different positions.

## 🖼️ Diagram
![Multi-Head Attention Diagram](../images/multi_head_attention.png)

## 📄 Original Paper
- **Title:** [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- **Year:** 2017
- **Authors:** Vaswani et al.

## 💡 Key Concept
Instead of performing a single attention function, multi-head attention linearly projects the queries, keys, and values $h$ times with different, learned linear projections.
