# TransferLearning-DomainAdaptation
## Some notes when survey on domain adaptation

## Overview paper
* Transfer Learning For Cross-Dataset Recognition: A Survey [[Arxiv 2018]](https://arxiv.org/abs/1802.03601v4)

## Transfer Learning
* Correlation Congruence for Knowledge Distillation [[Arxiv 2019]](https://arxiv.org/abs/1904.01802)
   
   Correlation congruence for konwledge distillation 不仅可以实现基于样本个体信息的转移，还可以转移样本之间的关系
* EASY TRANSFER LEARNING BY EXPLOITING INTRA-DOMAIN STRUCTURES [[Arxiv 2019]](https://arxiv.org/pdf/1904.01376v2.pdf)
   
   文章提出了一种实用的易传递学习（EasyTL）方法，它不需要进行模型选择和超参数调整，同时获得了具有竞争力的性能，挖掘域内结构来进行迁移，使用Intra-domain Programming来替换原来的Softmax的分类器。
* Adaptive Batch Normalization for practical domain adaptation[[Pattern Recognition 2018]](https://www.sciencedirect.com/science/article/abs/pii/S003132031830092X)
* Maximum Classifier Discrepancy for Unsupervised Domain Adaptation [[Arxiv 2018]](https://arxiv.org/abs/1712.02560)

* Looking back at Labels - A Class based Domain Adaptation Technique [[Arxiv 2019]](https://arxiv.org/abs/1904.01341)
* Cross-Domain Weakly-Supervised Object Detection through Progressive Domain Adaptation [[Arxiv 2018]](https://arxiv.org/abs/1803.11365)
* GLoMo Unsupervisedly Learned Relational Graphs [[Arxiv 2018]](https://arxiv.org/abs/1806.05662)

   学习目标样本之间的隐关系图
* AlignGAN - Learning to Align Cross-Domain Images with Conditional Generative Adversarial Networks [[Arxiv 2017]](https://arxiv.org/abs/1707.01400)
* Adversarial Discriminative Domain Adaptation [[Arxiv 2017]](https://arxiv.org/pdf/1702.05464.pdf)
* Deep Transfer Learning with Joint Adaptation Networks [[Arxiv 2017]](https://arxiv.org/abs/1605.06636)
* Unsupervised Domain Adaptation with Residual Transfer Networks [[Arxiv 2017]](https://arxiv.org/abs/1602.04433)

* Deep coral-Correlation alignment for deep domain adaptation [[Arxiv 2016]](https://arxiv.org/abs/1607.01719)
* Beyond Sharing Weights for Deep Domain Adaptation [[Arxiv 2016]](https://arxiv.org/abs/1603.06432)

   采用两个Streams，相应层中的权重是相关的，但不是共享的
* Simultaneous Deep Transfer Across Domains and Tasks [[Arxiv 2015]](https://arxiv.org/abs/1510.02192)



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
* Domain Adaptive Faster R-CNN for Object Detection in the Wild [[Arxiv 2018]](https://arxiv.org/abs/1803.03243)
  
  网络的底层特征进行强对齐，高层特征进行弱对齐
* Cross-Domain Weakly-Supervised Object Detection through Progressive Domain Adaptation [[CVPR 2018]](https://arxiv.org/abs/1803.11365)

## Accelerate speed
* Accelerating Deep Unsupervised Domain Adaptation with Transfer Channel Pruning [[Arxiv 2019]](https://arxiv.org/abs/1904.02654)
   
   首次从加速的角度来对无监督领域自适应进行优化,Transfer Channel Pruning能够通过剪除不太重要的信道来压缩深度UDA模型，同时通过减少跨域分布的差异来学习可转移的特征。

## Application
* Unsupervised Domain Adaptation for Multispectral Pedestrian Detection [[Arxiv 2019]](https://arXiv.org/pdf/1904.03692v1.pdf)

   通过迭代生成Pseudo Annotation以及更新设计的目标域多谱探测器(光学探测器和热学探测器)的参数
   
