# Awesome Self-supervised Learning for Tabular Data
![Version](https://img.shields.io/badge/Version-1.0-lightgrey.svg) 
![LastUpdated](https://img.shields.io/badge/LastUpdated-2024.01-lightblue.svg)
![Topic](https://img.shields.io/badge/Topic-SSL%20for%20Tabular%20Data-pink?logo=github)

This repository contains the frontier research on **self-supervised learning** for tabular data which has been a popular topic recently.<br>
This list is maintained by [Wei-Wei Du](https://wwweiwei.github.io/) and [Wei-Yao Wang](https://github.com/wywyWang). (Actively keep updating)

## Papers
### Predictive Learning
* [VIME: Extending the Success of Self- and Semi-supervised Learning to Tabular Domain (NeurIPS'20)](https://proceedings.neurips.cc/paper/2020/file/7d97667a3e056acab9aaf653807b4a03-Paper.pdf)
    *  [Supplementary](https://proceedings.neurips.cc/paper/2020/file/7d97667a3e056acab9aaf653807b4a03-Supplemental.pdf)
    *  [Code](https://github.com/jsyoon0823/VIME)
* [TaBERT: Pretraining for Joint Understanding of Textual and Tabular Data (ACL'20)](https://arxiv.org/abs/2005.08314)
* [CORE: Self- and Semi-supervised Tabular Learning with COnditional REgularizations (NeurIPS'21)](https://sslneurips21.github.io/files/CameraReady/CORE_workshop.pdf)
* [TabTransformer: Tabular Data Modeling Using Contextual Embeddings](https://arxiv.org/abs/2012.06678)
* [TabNet: Attentive Interpretable Tabular Learning (AAAI'21)](https://arxiv.org/abs/1908.07442)
    * [Code](https://github.com/dreamquark-ai/tabnet)
* [Self-Supervision Enhanced Feature Selection with Correlated Gates (ICLR'22)](https://openreview.net/pdf?id=oDFvtxzPOx)
    * [Code](https://github.com/chl8856/SEFS)
* [TransTab: Learning Transferable Tabular Transformers Across Tables (NeurIPS'22)](https://arxiv.org/abs/2205.09328)
    * [Code](https://github.com/RyanWangZf/transtab)
    * [Blog](https://realsunlab.medium.com/transtab-learning-transferable-tabular-transformers-across-tables-1e34eec161b8)
* [LIFT: Language-Interfaced Fine-Tuning for Non-language Machine Learning Tasks (NeurIPS'22)](https://arxiv.org/pdf/2206.06565.pdf)
    * [Code](https://github.com/UW-Madison-Lee-Lab/LanguageInterfacedFineTuning)
* [Self Supervised Pre-training for Large Scale Tabular Data (NeurIPS'22 TRL Workshop)](https://table-representation-learning.github.io/assets/papers/self_supervised_pre_training_f.pdf)
   * [Blog](https://www.amazon.science/publications/self-supervised-pre-training-for-large-scale-tabular-data)
* [Local Contrastive Feature Learning for Tabular Data (CIKM'22)](https://dl.acm.org/doi/pdf/10.1145/3511808.3557630)
* [Revisiting Self-Training with Regularized Pseudo-Labeling for Tabular Data (preprint-23)](https://arxiv.org/abs/2302.14013)
* [Generative Table Pre-training Empowers Models for Tabular Prediction (EMNLP'23)](https://arxiv.org/pdf/2305.09696.pdf)
   * [Code](https://github.com/ZhangTP1996/TapTap)
* [TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second (ICLR'23)](https://arxiv.org/pdf/2207.01848.pdf)
   * [Code](https://github.com/automl/TabPFN)
* [STUNT: Few-shot Tabular Learning with Self-generated Tasks from Unlabeled Tables (ICLR'23)](https://arxiv.org/pdf/2303.00918.pdf)
   * [Code](https://github.com/jaehyun513/STUNT)
* [Language Models are Realistic Tabular Data Generators (ICLR'23)](https://arxiv.org/pdf/2210.06280.pdf)
   * [Code](https://github.com/kathrinse/be_great)
* [Self-supervised Representation Learning from Random Data Projectors (NeurIPS'23 TRL Workshop)](https://arxiv.org/pdf/2310.07756.pdf)
   * [Code](https://github.com/layer6ai-labs/lfr)
* [SwitchTab: Switched Autoencoders Are Effective Tabular Learners (AAAI'24)](https://arxiv.org/pdf/2401.02013.pdf)
* [Making Pre-trained Language Models Great on Tabular Prediction (ICLR'24)](https://openreview.net/pdf?id=anzIzGZuLi)

### Contrastive Learning
* [SCARF: Self-Supervised Contrastive Learning using Random Feature Corruption (ICLR'22)](https://arxiv.org/pdf/2106.15147.pdf)
   * [Code](https://github.com/clabrugere/pytorch-scarf)
* [STab: Self-supervised Learning for Tabular Data (NeurIPS'22 Workshop on TRL)](https://openreview.net/pdf?id=EfR55bFcrcI)
* [TransTab: Learning Transferable Tabular Transformers Across Tables (NeurIPS'22)](https://arxiv.org/pdf/2205.09328.pdf)
* [PTaRL: Prototype-based Tabular Representation Learning via Space Calibration (ICLR'24)](https://openreview.net/pdf?id=G32oY4Vnm8)

### Hybrid Learning
* [SubTab: Subsetting Features of Tabular Data for Self-Supervised Representation Learning (NeurIPS'21)](https://arxiv.org/pdf/2110.04361.pdf)
    * [Supplementary](https://openreview.net/attachment?id=vrhNQ7aYSdr&name=supplementary_material)
    * [Code](https://github.com/AstraZeneca/SubTab)
* [SAINT: Improved Neural Networks for Tabular Data via Row Attention and Contrastive Pre-Training (NurIPS‘22 Workshop on TRL)](https://arxiv.org/pdf/2106.01342.pdf)
    * [Code](https://github.com/somepago/saint)
* [Transfer Learning with Deep Tabular Models (ICLR'23)](https://arxiv.org/pdf/2206.15306.pdf)
    * [Code](https://github.com/LevinRoman/tabular-transfer-learning)
* [DoRA: Domain-Based Self-Supervised Learning Framework for Low-Resource Real Estate Appraisal (CIKM'23)](https://arxiv.org/abs/2309.00855)
   * [Code](https://github.com/wwweiwei/DoRA)
* [ReConTab: Regularized Contrastive Representation Learning for Tabular Data (NeurIPS'23 Workshop on TRL)](https://arxiv.org/pdf/2310.18541.pdf)
* [XTab: Cross-table Pretraining for Tabular Transformers (ICML'23)](https://arxiv.org/abs/2305.06090)
* [UniTabE: A Universal Pretraining Protocol for Tabular Foundation Model in Data Science (ICLR'24)](https://arxiv.org/pdf/2307.09249.pdf)

## Tutorials
* [Self-Supervised Learning: Self-Prediction and Contrastive Learning (NeurIPS'21)](https://neurips.cc/virtual/2021/tutorial/21895)

## Related Survey
* [Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects](https://arxiv.org/abs/2306.10125)
* [Deep Neural Networks and Tabular Data: A Survey](https://arxiv.org/abs/2110.01889)
* [Self-Supervised Learning for Recommender Systems: A Survey (TKDE)](https://arxiv.org/pdf/2203.15876.pdf)

## Tools & Libraries
#### Python
* [Pytorch Frame: A modular deep learning framework for building neural network models on heterogeneous tabular data](https://github.com/pyg-team/pytorch-frame#implemented-deep-tabular-models)
* [PyTorch Tabular: A Framework for Deep Learning with Tabular Data](https://github.com/manujosephv/pytorch_tabular)
