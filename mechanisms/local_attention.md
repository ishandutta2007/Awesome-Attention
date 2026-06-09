# Local (Hard) Attention

Local attention focuses on a small, selected window of the input sequence rather than the entire sequence.

## 🖼️ Diagram
![Local Attention Diagram](../images/local_attention.png)

## 📄 Original Paper
- **Title:** [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)
- **Year:** 2015
- **Authors:** Xu et al.

## 💡 Key Concept
Hard attention makes a discrete choice about which part of the input to focus on. While more efficient, it is often non-differentiable and requires techniques like reinforcement learning for training.
