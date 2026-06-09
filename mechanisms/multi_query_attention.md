# Multi-Query Attention (MQA)

Multi-Query Attention uses multiple heads for Queries, but only a single key and value head.

## 🖼️ Diagram
![Multi-Query Attention Diagram](../images/mqa_gqa.png)

## 📄 Original Paper
- **Title:** [Fast Transformer Decoding: One Write-Head is All You Need](https://arxiv.org/abs/1911.02150)
- **Year:** 2019
- **Authors:** Shazeer

## 💡 Key Concept
By sharing a single Key and Value head across all Query heads, MQA drastically reduces the size of the KV cache, which speeds up inference and reduces memory bandwidth requirements.
