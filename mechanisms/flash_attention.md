# FlashAttention

FlashAttention is an exact, hardware-aware attention algorithm that speeds up training and inference by reducing the memory read/write operations between GPU SRAM and HBM.

## 🖼️ Diagram
![FlashAttention Diagram](../images/flash_attention.png)

## 📄 Original Paper
- **Title:** [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)
- **Year:** 2022
- **Authors:** Dao et al.

## 💡 Key Concept
FlashAttention uses tiling to partition the attention matrix into blocks, processing them entirely within the fast SRAM to avoid the bottleneck of reading/writing to the slower HBM.
