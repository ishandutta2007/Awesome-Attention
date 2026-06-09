# Grouped-Query Attention (GQA)

Grouped-Query Attention is a middle ground between Multi-Head and Multi-Query attention.

## 🖼️ Diagram
![Grouped-Query Attention Diagram](../images/mqa_gqa.png)

## 📄 Original Paper
- **Title:** [GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints](https://arxiv.org/abs/2305.13245)
- **Year:** 2023
- **Authors:** Ainslie et al.

## 💡 Key Concept
GQA groups query heads together, with each group sharing a single Key/Value head. This balances the speed of MQA with the quality of MHA.
