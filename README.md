# PLNet: A Hybrid-Structured Framework for High-Definition Medical Image Segmentation

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/monai?logo=monai)
![GitHub repo size](https://img.shields.io/github/repo-size/lzw514601882/PLNet)
![GitHub forks](https://img.shields.io/github/forks/lzw514601882/PLNet)
[![GitHub](https://img.shields.io/github/stars/lzw514601882/PLNet)](https://github.com/lzw514601882/PLNet)

## Key Innovation
- 🧠 A parallel multi-encoder segmentation framework: We introduce a novel parallel architecture that jointly exploits CNN, Transformer, and Mamba encoders to capture local textures, global context, and long-range dependencies for medical image segmentation, while maintaining a lightweight and efficient design.

- 🔑 MoE-based feature selection and fusion mechanism: We propose a Mixture-of-Experts module to selectively aggregate complementary features from multiple encoders, coupled with a lightweight MLP decoder to generate multi-level semantic representations with reduced redundancy and computational overhead.

- 🚀 Strong performance with high efficiency across datasets: Extensive experiments on multiple medical image segmentation benchmarks demonstrate that PLNet consistently outperforms CNN-, Transformer-, Mamba-, and hybrid-based methods, achieving state-of-the-art accuracy, robustness, and generalisation under favorable computational complexity.


## Abstract
Although general medical image segmentation models have shown good overall performance, accurately capturing boundary details remains challenging due to the small proportion of target regions and the presence of noise that reduces edge contrast. In this study, we propose a hybrid framework, PLNet, for precise segmentation of medical images. PLNet incorporates a specially designed lightweight CVT encoder, which consists of three sub-encoders: a CNN encoder for capturing local details, a ViT encoder with self-attention, and a VSSM encoder with recurrent mechanisms for modelling long-range dependencies and global contextual information. Additionally, a MoE module is integrated to selectively extract key features, suppress redundant information, and reduce computational complexity without compromising segmentation accuracy. Experimental results demonstrate that PLNet achieves superior performance across multiple medical image datasets. On skin cancer images, it attains an IoU of 79.57\% and a Dice score of 88.62\%, with a computational cost of only 26.15 GFLOPs and 21.47M parameters. Compared with existing state-of-the-art models, PLNet improves segmentation accuracy while substantially reducing computational demands.

## Main structure
