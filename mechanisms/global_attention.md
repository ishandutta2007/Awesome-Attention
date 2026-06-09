# Global (Soft) Attention

Global attention considers all hidden states of the encoder when calculating the context vector for each decoder step.

## 🖼️ Diagram
![Global Attention Diagram](../images/global_attention.png)

## 📄 Original Paper
- **Title:** [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)
- **Year:** 2014
- **Authors:** Bahdanau et al.

## 💡 Key Concept
Global attention places "soft" weights over all source positions. It is differentiable and can be trained using backpropagation, but can be computationally expensive for long sequences.
