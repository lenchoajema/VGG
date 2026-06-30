# VGGNet
- Architecture Study This repository is a **fork** of a VGGNet (Simonyan & Zisserman, ICLR 2015) implementation in TensorFlow, used for personal study of large-scale CNN architectures and ImageNet-scale training pipelines.
- **Note:** This is not my original implementation or training run.
- I forked this repository to study how VGG-19 is structured, how the data pipeline handles the ImageNet dataset (1.26M images, 1000 classes), and how the preprocessing steps (isotropic rescaling, random crop, PCA colour augmentation, mean subtraction) are implemented in practice.
## What I studied 
- VGG-19 architecture: 16 conv layers + 3 FC layers, all 3×3 kernels
- ImageNet data loading and augmentation pipeline
- Training configuration for large-scale image classification
- The original paper's design rationale for using small, stacked filters
## Reference Simonyan, K. & Zisserman, A. (2015). 
- Very Deep Convolutional Networks for Large-Scale Image Recognition. ICLR 2015. arxiv.org/abs/1409.1556
## My own related work For my own original deep learning implementation, see: github.com/lenchoajema/optical-flow-raft-study 
RAFT optical flow inference notebook, built and run independently as part of my PhD application preparation. 
## Author Lencho Ajema Negese github.com/lenchoajema | ORCID: 0009-0004-6093-8890 MSc thesis (original work): "Target Identification and Event Analysis of UAV-Based Images Using Deep Learning" — Adama Science and Technology University, 2022
