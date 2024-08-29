# Awesome Self-Supervised Learning for Non-Sequential Tabular Data (SSL4NSTD)
![Version](https://img.shields.io/badge/Version-1.0-lightgrey.svg) 
![LastUpdated](https://img.shields.io/badge/LastUpdated-2024.06-lightblue.svg)
![Topic](https://img.shields.io/badge/Topic-SSL4NSTD-pink?logo=github)

This repository contains the frontier research on **self-supervised learning** for tabular data which has been a popular topic recently.<br>
This list is maintained by [Wei-Wei Du](https://wwweiwei.github.io/) and [Wei-Yao Wang](https://github.com/wywyWang). (Actively keep updating)<br>
If you have come across relevant resources or found some errors in this repository, feel free to open an issue or submit a PR.

## Survey Paper
[A Survey on Self-Supervised Learning for Non-Sequential Tabular Data](https://arxiv.org/abs/2402.01204)
### Citation
```bibtex
@article{DBLP:journals/corr/abs-2402-01204,
  author       = {Wei{-}Yao Wang and
                  Wei{-}Wei Du and
                  Derek Xu and
                  Wei Wang and
                  Wen{-}Chih Peng},
  title        = {A Survey on Self-Supervised Learning for Non-Sequential Tabular Data},
  journal      = {CoRR},
  volume       = {abs/2402.01204},
  year         = {2024}
}
```

## Papers
### Predictive Learning
* VIME: Extending the Success of Self- and Semi-supervised Learning to Tabular Domain (NeurIPS'20) [[Paper]](https://proceedings.neurips.cc/paper/2020/file/7d97667a3e056acab9aaf653807b4a03-Paper.pdf) [[Supplementary]](https://proceedings.neurips.cc/paper/2020/file/7d97667a3e056acab9aaf653807b4a03-Supplemental.pdf) [[Code]](https://github.com/jsyoon0823/VIME)
* TaBERT: Pretraining for Joint Understanding of Textual and Tabular Data (ACL'20) [[Paper]](https://arxiv.org/abs/2005.08314)
* 
* TABBIE: Pretrained Representations of Tabular Data (NAACL'21) [[Paper]](https://arxiv.org/abs/2105.02584)) [[Code]](https://github.com/SFIG611/tabbie)
* CORE: Self- and Semi-supervised Tabular Learning with COnditional REgularizations (NeurIPS'21) [[Paper]](https://sslneurips21.github.io/files/CameraReady/CORE_workshop.pdf)
* TabTransformer: Tabular Data Modeling Using Contextual Embeddings [[Paper]](https://arxiv.org/abs/2012.06678)
* TabNet: Attentive Interpretable Tabular Learning (AAAI'21) [[Paper]](https://arxiv.org/abs/1908.07442) [Code](https://github.com/dreamquark-ai/tabnet)
* Self-Supervision Enhanced Feature Selection with Correlated Gates (ICLR'22) [[Paper]](https://openreview.net/pdf?id=oDFvtxzPOx) [[Code]](https://github.com/chl8856/SEFS)
* TransTab: Learning Transferable Tabular Transformers Across Tables (NeurIPS'22) [[Paper]](https://arxiv.org/abs/2205.09328) [[Code]](https://github.com/RyanWangZf/transtab) [[Blog]](https://realsunlab.medium.com/transtab-learning-transferable-tabular-transformers-across-tables-1e34eec161b8)
* LIFT: Language-Interfaced Fine-Tuning for Non-language Machine Learning Tasks (NeurIPS'22) [[Paper]](https://arxiv.org/pdf/2206.06565.pdf) [[Code]](https://github.com/UW-Madison-Lee-Lab/LanguageInterfacedFineTuning)
* Self Supervised Pre-training for Large Scale Tabular Data (NeurIPS'22 TRL Workshop) [[Paper]](https://table-representation-learning.github.io/assets/papers/self_supervised_pre_training_f.pdf) [[Blog]](https://www.amazon.science/publications/self-supervised-pre-training-for-large-scale-tabular-data)
* Local Contrastive Feature Learning for Tabular Data (CIKM'22) [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3511808.3557630)
* Revisiting Self-Training with Regularized Pseudo-Labeling for Tabular Data (preprint-23) [[Paper]](https://arxiv.org/abs/2302.14013)
* Generative Table Pre-training Empowers Models for Tabular Prediction (EMNLP'23) [[Paper]](https://arxiv.org/pdf/2305.09696.pdf) [[Code]](https://github.com/ZhangTP1996/TapTap)
* TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second (ICLR'23) [[Paper]](https://arxiv.org/pdf/2207.01848.pdf) [[Code]](https://github.com/automl/TabPFN)
* STUNT: Few-shot Tabular Learning with Self-generated Tasks from Unlabeled Tables (ICLR'23) [[Paper]](https://arxiv.org/pdf/2303.00918.pdf) [[Code]](https://github.com/jaehyun513/STUNT)
* Language Models are Realistic Tabular Data Generators (ICLR'23) [[Paper]](https://arxiv.org/pdf/2210.06280.pdf) [[Code]](https://github.com/kathrinse/be_great)
* Self-supervised Representation Learning from Random Data Projectors (NeurIPS'23 TRL Workshop) [[Paper]](https://arxiv.org/pdf/2310.07756.pdf) [[Code]](https://github.com/layer6ai-labs/lfr)
* SwitchTab: Switched Autoencoders Are Effective Tabular Learners (AAAI'24) [[Paper]](https://arxiv.org/pdf/2401.02013.pdf)
* Making Pre-trained Language Models Great on Tabular Prediction (ICLR'24) [[Paper]](https://openreview.net/pdf?id=anzIzGZuLi)
* Binning as a Pretext Task: Improving Self-Supervised Learning in Tabular Domains (ICML'24) [[Paper]](https://arxiv.org/abs/2405.07414) [[Code]](https://github.com/kyungeun-lee/tabularbinning)

### Contrastive Learning
* SCARF: Self-Supervised Contrastive Learning using Random Feature Corruption (ICLR'22) [[Paper]](https://arxiv.org/pdf/2106.15147.pdf) [[Code]](https://github.com/clabrugere/pytorch-scarf)
* STab: Self-supervised Learning for Tabular Data (NeurIPS'22 Workshop on TRL) [[Paper]](https://openreview.net/pdf?id=EfR55bFcrcI)
* TransTab: Learning Transferable Tabular Transformers Across Tables (NeurIPS'22) [[Paper]](https://arxiv.org/pdf/2205.09328.pdf)
* PTaRL: Prototype-based Tabular Representation Learning via Space Calibration (ICLR'24) [[Paper]](https://openreview.net/pdf?id=G32oY4Vnm8)

### Hybrid Learning
* SubTab: Subsetting Features of Tabular Data for Self-Supervised Representation Learning (NeurIPS'21) [[Paper]](https://arxiv.org/pdf/2110.04361.pdf) [[Supplementary]](https://openreview.net/attachment?id=vrhNQ7aYSdr&name=supplementary_material) [[Code]](https://github.com/AstraZeneca/SubTab)
* SAINT: Improved Neural Networks for Tabular Data via Row Attention and Contrastive Pre-Training (NurIPS‘22 Workshop on TRL) [[Paper]](https://arxiv.org/pdf/2106.01342.pdf) [[Code]](https://github.com/somepago/saint)
* Transfer Learning with Deep Tabular Models (ICLR'23) [[Paper]](https://arxiv.org/pdf/2206.15306.pdf) [[Code]](https://github.com/LevinRoman/tabular-transfer-learning)
* DoRA: Domain-Based Self-Supervised Learning Framework for Low-Resource Real Estate Appraisal (CIKM'23) [[Paper]](https://arxiv.org/abs/2309.00855) [[Code]](https://github.com/wwweiwei/DoRA)
* ReConTab: Regularized Contrastive Representation Learning for Tabular Data (NeurIPS'23 Workshop on TRL) [[Paper]](https://arxiv.org/pdf/2310.18541.pdf)
* XTab: Cross-table Pretraining for Tabular Transformers (ICML'23) [[Paper]](https://arxiv.org/abs/2305.06090)
* UniTabE: A Universal Pretraining Protocol for Tabular Foundation Model in Data Science (ICLR'24) [[Paper]](https://arxiv.org/pdf/2307.09249.pdf)

## Benchmarks
| Benchmark    | Task                                  | #Datasets | Paper |
|--------------|---------------------------------------|-----------|-------|
| MLPCBench    | Classification                        | 40        | [Kadra et al., 2021](https://arxiv.org/abs/2106.11189)  |
| DLBench      | Classification, Regression            | 11        | [Shwartz-Ziv and Armon, 2022](https://arxiv.org/abs/2106.03253)  |
| TabularBench | Classification, Regression            | 45        | [Grinsztajn et al., 2022](https://arxiv.org/abs/2207.08815)  |
| TabZilla     | Classification                        | 36        | [McElfresh et al., 2023](https://arxiv.org/abs/2305.02997)  |
| TabPretNet   | Unlabeled, Classification, Regression | 2000      | [Ye et al., 2023](https://arxiv.org/abs/2307.04308)  |

## Tutorials
* Self-Supervised Learning: Self-Prediction and Contrastive Learning (NeurIPS'21) [[Website]](https://neurips.cc/virtual/2021/tutorial/21895)

## Workshops
* Table Representation Learning (NeurIPS) [[Website]](https://table-representation-learning.github.io/)

## Related Survey
* Deep Neural Networks and Tabular Data: A Survey [[Paper]](https://arxiv.org/abs/2110.01889)
* Self-Supervised Learning for Recommender Systems: A Survey (TKDE) [[Paper]](https://arxiv.org/pdf/2203.15876.pdf)
* Beyond Just Vision: A Review on Self-Supervised Representation Learning on Multimodal and Temporal Data [[Paper]](https://arxiv.org/abs/2206.02353)
* Self-Supervised Learning for Time Series Analysis: Taxonomy, Progress, and Prospects [[Paper]](https://arxiv.org/abs/2306.10125)
* On the Opportunities and Challenges of Foundation Models for Geospatial Artificial Intelligence [[Paper]](https://arxiv.org/abs/2304.06798)
* A Survey on Time-Series Pre-Trained Models [[Paper]](https://arxiv.org/abs/2305.10716)

## Tools & Libraries
* Pytorch Frame: A modular deep learning framework for building neural network models on heterogeneous tabular data [[Link]](https://github.com/pyg-team/pytorch-frame#implemented-deep-tabular-models)
* PyTorch Tabular: A Framework for Deep Learning with Tabular Data [[Link]](https://github.com/manujosephv/pytorch_tabular)
