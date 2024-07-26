# Hybrid of CoAtNet and ConvMLP

### Notebook for creating 5 different hybrids from CoAtNet and ConvMLP models with the CIFAR-10 dataset

## CoAtNet

 Zihang Dai, Hanxiao Liu, Quoc V. Le, Mingxing Tan “CoAtNet: Marrying
 Convolution and Attention for All Data Sizes”, 2021, arXiv:2106.04803, DOI
 10.48550/arXiv.2106.04803, https://arxiv.org/pdf/2106.04803v2.pdf

https://github.com/chinhsuanwu/coatnet-pytorch/tree/master

## ConvMLP

 Jiachen Li, Ali Hassani, Steven Walton, Humphrey Shi. ConvMLP: Hierarchical
 Convolutional MLPs for Vision: arXiv:2109.04454v2 [cs.CV] 18 Sep 2021, DOI
 10.48550/arXiv.2109.04454, https://arxiv.org/pdf/2109.04454v2.pdf

 https://github.com/SHI-Labs/Convolutional-MLPs

## Dataset 

CIFAR-10

https://www.kaggle.com/c/cifar-10/


### How to use

In the last 5 blocks of the notebook, there are models for 5 experiments. The selected model should be pasted in the block where the CoAtNet model is defined (the fifth block from the top).

The CIFAR-10 data should have the following structure: cifar10/[train][test]/[class1][class2][class3]...
