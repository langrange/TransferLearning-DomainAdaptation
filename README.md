# TransferLearning-DomainAdaptation
## Some notes when survey on domain adaptatin

## Overview paper
* Transfer Learning For Cross-Dataset Recognition: A Survey [[Arxiv 2018]](https://arxiv.org/abs/1802.03601v4)

## Transfer Learning
* Correlation Congruence for Knowledge Distillation [[Arxiv 2019]](https://arxiv.org/abs/1904.01802)

Correlation congruence for konwledge distillation 不仅可以实现基于样本个体信息的转移，还可以转移样本之间的关系
* EASY TRANSFER LEARNING BY EXPLOITING INTRA-DOMAIN STRUCTURES [[Arxiv 2019]](https://arxiv.org/pdf/1904.01376v2.pdf)

文章提出了一种实用的易传递学习（EasyTL）方法，它不需要进行模型选择和超参数调整，同时获得了具有竞争力的性能，挖掘域内结构来进行迁移，使用Intra-domain Programming来替换原来的Softmax的分类器。
## GAN-based
* Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [[Arxiv 2017]](https://arxiv.org/abs/1703.10593)

文章可以实现不同域的图像到图像的相互转换

## Semantic Segmentation
* Learning from Synthetic Data - Addressing Domain Shift for Semantic Segmentation [[Arxiv 2018]](https://arxiv.org/abs/1711.06969)
* Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes [[Arxiv ICCV'2017]](https://arxiv.org/abs/1707.09465)
* FCNs in the Wild: Pixel-level Adversarial and Constraint-based Adaptation [[Arxiv 2016]](https://arxiv.org/abs/1612.02649)

## Detection
* A Robust Learning Approach to Domain Adaptive Object Detection [[Arxiv 2019]](https://arxiv.org/abs/1904.02361)
* Strong-Weak Distribution Alignment for Adaptive Object Detection [[Arxiv 2019]](https://arxiv.org/abs/1812.04798)

网络的底层特征进行强对齐，高层特征进行弱对齐

## Accelerate speed
* Accelerating Deep Unsupervised Domain Adaptation with Transfer Channel Pruning [[Arxiv 2019]](https://arxiv.org/abs/1904.02654)

首次从加速的角度来对无监督领域自适应进行优化,Transfer Channel Pruning能够通过剪除不太重要的信道来压缩深度UDA模型，同时通过减少跨域分布的差异来学习可转移的特征。
