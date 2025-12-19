# PLNet: A Hybrid-Structured Framework for High-Definition Medical Image Segmentation

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/monai?logo=monai)
![GitHub repo size](https://img.shields.io/github/repo-size/lzw514601882/PLNet)
![GitHub forks](https://img.shields.io/github/forks/lzw514601882/PLNet)
[![GitHub](https://img.shields.io/github/stars/lzw514601882/PLNet)](https://github.com/lzw514601882/PLNet)

## Key Innovation
- 🧠 A parallel multi-encoder segmentation framework: We introduce a novel parallel architecture that jointly exploits CNN, Transformer, and Mamba encoders to capture local textures, global context, and long-range dependencies for medical image segmentation, while maintaining a lightweight and efficient design.

- 🔑 MoE-based feature selection and fusion mechanism: We propose a Mixture-of-Experts module to selectively aggregate complementary features from multiple encoders, coupled with a lightweight MLP decoder to generate multi-level semantic representations with reduced redundancy and computational overhead.

- 🚀 Strong performance with high efficiency across datasets: Extensive experiments on multiple medical image segmentation benchmarks demonstrate that PLNet consistently outperforms CNN-, Transformer-, Mamba-, and hybrid-based methods, achieving state-of-the-art accuracy, robustness, and generalisation under favorable computational complexity.
