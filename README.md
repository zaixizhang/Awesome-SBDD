# Awesome-SBDD: Papers on Structure-based Drug Design (SBDD)
Link to the survey paper: [Geometric Deep Learning for Structure-Based Drug Design: A Survey](
https://arxiv.org/abs/2306.11768)

<div align=center><img src="https://github.com/zaixizhang/Awesome-SBDD/blob/main/tasks.png" width="700"/></div>

This repository contains a list of papers on the Structure-based Drug Design; we categorize them based on their detailed tasks and methods. Specifically, **we focus our scope on tasks related to the protein-ligand binding interface**, including *binding site prediction, binding pose generation, de novo ligand generation, linker design, protein pocket generation, and binding affinity prediction*.

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Created](https://img.shields.io/badge/Created-2023--06-green.svg) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)

<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)  ![Forks](https://img.shields.io/github/forks/zaixizhang/Awesome-SBDD?color=blue&label=Fork) -->

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

## Table of Contents                                           
- [Binding site prediction](#binding-site-prediction)
  - [2024 -- Binding site prediction](#2024----Binding-site-prediction)
  - [2023 -- Binding site prediction](#2023----Binding-site-prediction)
  - [2022 -- Binding site prediction](#2022----Binding-site-prediction)
  - [2021 -- Binding site prediction](#2021----Binding-site-prediction)
  - [2019 -- Binding site prediction](#2019----Binding-site-prediction)
  - [2017 -- Binding site prediction](#2017----Binding-site-prediction)                   
- [Binding pose generation](#binding-pose-generation)
  - [2024 -- Binding pose generation](#2024----Binding-pose-generation)
  - [2023 -- Binding pose generation](#2023----Binding-pose-generation)
  - [2022 -- Binding pose generation](#2022----Binding-pose-generation)
  - [2021 -- Binding pose generation](#2021----Binding-pose-generation)             
- [Binding affinity prediction](#binding-affinity-prediction)
  - [2024 -- Binding affinity prediction](#2024----Binding-affinity-prediction)
  - [2023 -- Binding affinity prediction](#2023----Binding-affinity-prediction)
  - [2022 -- Binding affinity prediction](#2022----Binding-affinity-prediction)
  - [2021 -- Binding affinity prediction](#2021----Binding-affinity-prediction)
  - [2020 -- Binding affinity prediction](#2020----Binding-affinity-prediction)
  - [2019 -- Binding affinity prediction](#2019----Binding-affinity-prediction)
  - [2018 -- Binding affinity prediction](#2018----Binding-affinity-prediction)               
- [De novo ligand generation](#de-novo-ligand-generation)
  - [2024 -- De novo ligand generation](#2024----De-novo-ligand-generation)
  - [2023 -- De novo ligand generation](#2023----De-novo-ligand-generation)
  - [2022 -- De novo ligand generation](#2022----De-novo-ligand-generation)
  - [2021 -- De novo ligand generation](#2021----De-novo-ligand-generation)
  - [2020 -- De novo ligand generation](#2020----De-novo-ligand-generation)   
- [Linker design](#linker-design)
  - [2023 -- Linker design](#2023----Linker-design)
  - [2022 -- Linker design](#2022----Linker-design)
  - [2020 -- Linker design](#2020----Linker-design)
- [Protein Pocket Generation](#protein-pocket-generation)
  - [2023 -- Protein pocket generation](#2023----Protein-pocket-generation)
  - [2022 -- Protein pocket generation](#2022----Protein-pocket-generation)
  - [2020 -- Protein pocket generation](#2020----Protein-pocket-generation)


## Binding site prediction

### 2024 -- Binding-site-prediction
**Surface-VQMAE: Vector-quantized Masked Auto-encoders on Molecular Surfaces**  
Wu, Fang et al  
*International Conference on Machine Learning, 2024*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=szxtVHOh0C)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0b0ae49d2c933576d81146ac1ca7ff97f7ab910b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/smiles724/VQMAE)
![Stars](https://img.shields.io/github/stars/smiles724/VQMAE?color=yellow&style=social)


### 2023 -- Binding-site-prediction
**PeSTo: parameter-free geometric deep learning for accurate prediction of protein binding interfaces**  
Krapp, Lucien F., et al  
*Nature Communications 14 (2023): 2175*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-37701-8)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fec43befb0c7acfc2bf9a79e5bf41e0920c5b3382%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/LBM-EPFL/PeSTo)
![Stars](https://img.shields.io/github/stars/LBM-EPFL/PeSTo?color=yellow&style=social)


**Predicting the locations of cryptic pockets from single protein structures using the PocketMiner graph neural network**  
Meller, Artur, et al  
*Nature Communications 14 (2023): 1177*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36699-3)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F71e2caca1f97e1d0521de3cea1733bec9f8e13d1%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Mickdub/gvp/tree/pocket_pred)
![Stars](https://img.shields.io/github/stars/Mickdub/gvp?color=yellow&style=social)


**EquiPocket: an E (3)-Equivariant Geometric Graph Neural Network for Ligand Binding Site Prediction**  
Zhang, Yang, et al  
*arXiv preprint arXiv:2302.12177 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2302.12177)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F97b2c62fe4dacae931e2df1eefa633da81a79108%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**NodeCoder: a graph-based machine learning platform to predict active sites of modeled protein structures**  
Abdollahi, Nasim, et al  
*arXiv preprint arXiv:2302.03590 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2302.03590)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F37833e363260ff052f41927d64d4bcb9d0b79ba7%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/NasimAbdollahi/NodeCoder)
![Stars](https://img.shields.io/github/stars/NasimAbdollahi/NodeCoder?color=yellow&style=social)


**DSDP: A Blind Docking Strategy Accelerated by GPUs**  
Huang, Yupeng et al  
*Journal of chemical information and modeling (2023)*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00519)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb3f9ed5db9a0280d8c604ce18337bae8587c37d1%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/PKUGaoGroup/DSDP)
![Stars](https://img.shields.io/github/stars/PKUGaoGroup/DSDP?color=yellow&style=social)


### 2022 -- Binding-site-prediction  
**ScanNet: an interpretable geometric deep learning model for structure-based protein binding site prediction**  
Tubiana, Jérôme, Dina Schneidman-Duhovny, and Haim J. Wolfson  
*Nature Methods 19.6 (2022): 730-739*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-022-01490-7)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe4ceed180abd39a2602f28c80b30fb4d41583054%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/jertubiana/ScanNet)
![Stars](https://img.shields.io/github/stars/jertubiana/ScanNet?color=yellow&style=social)


### 2021 -- Binding-site-prediction
**Fast end-to-end learning on protein surfaces**  
Sverrisson, Freyr, et al  
*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2021*  
[![](https://img.shields.io/badge/CVPR_2021-Paper-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openaccess.thecvf.com/content/CVPR2021/papers/Sverrisson_Fast_End-to-End_Learning_on_Protein_Surfaces_CVPR_2021_paper.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1f089508bbcd0a5c083cb6077adb133774eca5d7%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/FreyrS/dMaSIF)
![Stars](https://img.shields.io/github/stars/FreyrS/dMaSIF?color=yellow&style=social)


**PUResNet: prediction of protein-ligand binding sites using deep residual neural network**  
Qiao, Zhuoran et al  
*arXiv preprint arXiv:2209.15171 (2021)*  
[![](https://img.shields.io/badge/jcheminf_biomedcentral-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00547-7)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbf5a88b16e2f6e8fcc0a5629e4cd4b6bacd2fed6%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/jivankandel/PUResNet)
![Stars](https://img.shields.io/github/stars/jivankandel/PUResNet?color=yellow&style=social)


### 2019 -- Binding-site-prediction
**Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning**  
Gainza, Pablo et al  
*Nature Methods 17 (2019): 184-192*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-019-0666-6)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe4f2c471d27ced746f26cc6e8337ea5cb7c8faf3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/lpdi-epfl/masif)
![Stars](https://img.shields.io/github/stars/lpdi-epfl/masif?color=yellow&style=social)


### 2017 -- Binding-site-prediction
**Protein interface prediction using graph convolutional networks**  
Fout, Alex, et al  
*Advances in neural information processing systems 30 (2017)*  
[![](https://img.shields.io/badge/proceedings_neurips_cc-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.neurips.cc/paper_files/paper/2017/file/f507783927f2ec2737ba40afbd17efb5-Paper.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc751ab01aedc2888a7fe6e8b4f77ab1afa94072f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/fouticus/pipgcn)
![Stars](https://img.shields.io/github/stars/fouticus/pipgcn?color=yellow&style=social)


**DeepSite: protein-binding site predictor using 3D-convolutional neural networks**  
Jiménez, José, et al  
*Bioinformatics 33.19 (2017): 3036-3042*  
[![](https://img.shields.io/badge/academic-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bioinformatics/article/33/19/3036/3859178)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F43fa427d81f0c575826a6c39644ce1489cdb9cfb%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


## Binding pose generation
### 2024 -- Binding-pose-generation
**DynamicBind: predicting ligand-specific protein-ligand complex structure with a deep equivariant generative model**  
Lu, Wei et al  
*Nature Communications 15 (2024)*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-024-45461-2)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F51894ffcf778630e7b021bc473d13d028a3b9158%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luwei0917/DynamicBind)
![Stars](https://img.shields.io/github/stars/luwei0917/DynamicBind?color=yellow&style=social)


**PackDock: a Diffusion Based Side Chain Packing Model for Flexible Protein-Ligand Docking**  
Zhang, Runze et al  
*bioRxiv (2024): n. pag*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2024.01.31.578200v1.full.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F770f53f09f541b96d0e3693ae4066b897ef9d9f5%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Zhang-Runze/PackDock)
![Stars](https://img.shields.io/github/stars/Zhang-Runze/PackDock?color=yellow&style=social)


**Re-Dock: Towards Flexible and Realistic Molecular Docking with Diffusion Bridge**  
Huang, Yufei et al  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2402.11459.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F68981c9aba4c06176f3c062b94c3e6861371bdb6%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**Equivariant Scalar Fields for Molecular Docking with Fast Fourier Transforms**  
Jing, Bowen et al  
*International Conference on Learning Representations, 2024*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=BIveOmD1Nh)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd633a97b6fb0227eb38c6987d819085132d97c54%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/bjing2016/scalar-fields)
![Stars](https://img.shields.io/github/stars/bjing2016/scalar-fields?color=yellow&style=social)


**Harmonic Self-Conditioned Flow Matching for Multi-Ligand Docking and Binding Site Design**  
Stärk, Hannes et al  
*International Conference on Machine Learning, 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2310.05764)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9e8dd85c321403bcfb26313ede7116f760672d33%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HannesStark/FlowSite)
![Stars](https://img.shields.io/github/stars/HannesStark/FlowSite?color=yellow&style=social)


**Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction**  
Alcaide, Eric et al  
*ArXiv abs/2405.11769 (2024)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2405.11769)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd03bcd5003d5f35d536f9e9b7ae5c4194de93295%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/deepmodeling/Uni-Mol/tree/main/unimol_docking_v2)
![Stars](https://img.shields.io/github/stars/deepmodeling/Uni-Mol?color=yellow&style=social)


**FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation**  
Gao, Kaiyuan et al  
*ArXiv abs/2403.20261 (2024): n. pag*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2403.20261)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6594ec85ba41682c2ae0b2c205a92ec372f0ec4b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/QizhiPei/FABind/tree/main/FABind_plus)
![Stars](https://img.shields.io/github/stars/QizhiPei/FABind?color=yellow&style=social)


**Deep Confident Steps to New Pockets: Strategies for Docking Generalization**  
Corso, Gabriele et al  
*ArXiv (2024): n. pag*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=UfBIxpTK10)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa2af79d2c6a75919d586590487cc3b39b42a94c2%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/gcorso/DiffDock)
![Stars](https://img.shields.io/github/stars/gcorso/DiffDoc?color=yellow&style=social)


**Chai-1: Decoding the molecular interactions of life**  
Boitreaud, Jacques et al  
*bioRxiv (2024): n. pag*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2024.10.10.615955v2.full.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd6352ba03f73056e7b0dbfab3adab6f367866827%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/chaidiscovery/chai-lab)
![Stars](https://img.shields.io/github/stars/chaidiscovery/chai-lab?color=yellow&style=social)


**Accurate structure prediction of biomolecular interactions with AlphaFold 3**  
Abramson, Josh et al  
*Nature 630 (2024): 493 - 500*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41586-024-07487-w)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7572ba7f604ef95d7acdd657ebac458106bd35df%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


### 2023 -- Binding-pose-generation
**Deep learning model for efficient protein–ligand docking with implicit side-chain flexibility**  
Masters, Matthew R., et al  
*Journal of Chemical Information and Modeling 63.6 (2023): 1695-1707*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01436)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb29d66e1c466bd248232eee0d987118b258fb18e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/MatthewMasters/EDM-Dock)
![Stars](https://img.shields.io/github/stars/MatthewMasters/EDM-Dock?color=yellow&style=social)


**End-to-end protein–ligand complex structure generation with diffusion-based generative models**  
Nakata, Shuya, Yoshiharu Mori, and Shigenori Tanaka  
*BMC bioinformatics 24.1 (2023): 1-18*  
[![](https://img.shields.io/badge/biomedcentral-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05354-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5711400d6fbba28fc776a3b85b6890b62934f64f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/shuyana/DiffusionProteinLigand)
![Stars](https://img.shields.io/github/stars/shuyana/DiffusionProteinLigand?color=yellow&style=social)


**Diffdock: Diffusion steps, twists, and turns for molecular docking**  
Corso, Gabriele, et al  
*International Conference on Learning Representations. 2023*  
[![](https://img.shields.io/badge/openriview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=kKF8_K-mBbS)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe99604e2da48483b633247c13dd4ad5f46196562%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/gcorso/DiffDock)
![Stars](https://img.shields.io/github/stars/gcorso/DiffDock?color=yellow&style=social)


**Uni-Mol: A Universal 3D Molecular Representation Learning Framework**  
Zhou, Gengmo et al  
*International Conference on Learning Representations (2023)*  
[![](https://img.shields.io/badge/openriview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=6K2RM6wVqKu)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F11f42721f56f36a64638677ccde7784040829656%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/deepmodeling/Uni-Mol)
![Stars](https://img.shields.io/github/stars/deepmodeling/Uni-Mol?color=yellow&style=social)


**E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking**  
 Zhang, Yangtian, et al  
*International Conference on Learning Representations. 2023*  
[![](https://img.shields.io/badge/openriview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=sO1QiAftQFv)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9946caf3a8a381f880fe6452c960429ebe8b1440%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**A fully differentiable ligand pose optimization framework guided by deep learning and a traditional scoring function**  
Wang, Zechen, et al  
*Briefings in Bioinformatics 24.1 (2023): bbac520*  
[![](https://img.shields.io/badge/academic-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bib/article-abstract/24/1/bbac520/6887112?redirectedFrom=fulltext)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F848a94c3cf71a05a45a63fed26bd4e297ebd15e3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zchwang/DeepRMSD-Vina_Optimization)
![Stars](https://img.shields.io/github/stars/zchwang/DeepRMSD-Vina_Optimization?color=yellow&style=social)


**Protein-Ligand Complex Generator & Drug Screening via Tiered Tensor Transform**  
Mailoa, Jonathan P., et al  
*arXiv preprint arXiv:2301.00984 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2301.00984)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F05f9e05a00dccc7fd3d3c3c090b6efb7aabfdede%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**DSDP: A Blind Docking Strategy Accelerated by GPUs**  
Huang, Yupeng et al  
*Journal of chemical information and modeling (2023)*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00519)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb3f9ed5db9a0280d8c604ce18337bae8587c37d1%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/PKUGaoGroup/DSDP)
![Stars](https://img.shields.io/github/stars/PKUGaoGroup/DSDP?color=yellow&style=social)


**Equivariant Flexible Modeling of the Protein-Ligand Binding Pose with Geometric Deep Learning**  
Dong, Tiejun et al  
*Journal of chemical theory and computation (2023)*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.3c00273)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff2633ad706a8537bd7d8d89561d4bbad71373380%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/tiejundong/FlexPose)
![Stars](https://img.shields.io/github/stars/tiejundong/FlexPose?color=yellow&style=social)


**DiffDock-Pocket: Diffusion for Pocket-Level Docking with Sidechain Flexibility**  
Plainer, Michael, et al  
*Advances in Neural Information Processing Systems, Workshop. 2023*  
[![](https://img.shields.io/badge/plainer-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://plainer.dev/assets/pdf/2023/DiffDock-Pocket.pdf)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://anonymous.4open.science/r/DiffDock-Pocket-AQ32)


**Efficient and accurate large library ligand docking with KarmaDock**  
Zhang, Xujun et al  
*Nature Computational Science 3 (2023): 789 - 804*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s43588-023-00511-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F190320029c58f7e3c1ce8fa9b908d3c88a27df2f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/schrojunzhang/KarmaDock)
![Stars](https://img.shields.io/github/stars/schrojunzhang/KarmaDock?color=yellow&style=social)


**CarsiDock: a deep learning paradigm for accurate protein–ligand docking and screening based on large-scale pre-training**  
Cai, Heng et al  
*Chemical Science 15 (2023): 1449 - 1471*  
[![](https://img.shields.io/badge/rsc-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc05552c)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F12f90a54c1f94981ba4f129be8b220b4b8282a6b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/carbonsilicon-ai/CarsiDock)
![Stars](https://img.shields.io/github/stars/carbonsilicon-ai/CarsiDock?color=yellow&style=social)


**FABind: Fast and Accurate Protein-Ligand Binding**  
 Pei, Qizhi et al  
*Advances in Neural Information Processing Systems. 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=PnWakgg1RL)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fef5fceee2925cb8441bf1de100b67a33eeeef3a3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/QizhiPei/FABind)
![Stars](https://img.shields.io/github/stars/QizhiPei/FABind?color=yellow&style=social)


**Multi-scale Iterative Refinement towards Robust and Versatile Molecular Docking**  
Yan, Jiaxian et al  
*ArXiv abs/2311.18574 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2311.18574)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbedc29f7b553bd322df265e2c5a215f1dfd19b4e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**SurfDock is a Surface-Informed Diffusion Generative Model for Reliable and Accurate Protein-ligand Complex Prediction**  
Cao, Duanhua et al  
*bioRxiv (2023): n. pag*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.12.13.571408v1.full.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F48753fd45da00aa39a4a14841683158f73625d38%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/CAODH/SurfDock)
![Stars](https://img.shields.io/github/stars/CAODH/SurfDock)?color=yellow&style=social)


**DiffBindFR: An SE(3) Equivariant Network for Flexible Protein-Ligand Docking**  
Zhu, Jintao et al    
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2311.15201)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F04911aa5c3b5d6d07507a0079ebbe6c504a462ae%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HBioquant/DiffBindFR)
![Stars](https://img.shields.io/github/stars/HBioquant/DiffBindFR?color=yellow&style=social)


**Pre-Training on Large-Scale Generated Docking Conformations with HelixDock to Unlock the Potential of Protein-ligand Structure Prediction Models**  
Liu, Lihang et al  
*ArXiv abs/2310.13913 (2023): n. pag*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2310.13913)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe0b05305ce09e20d64394753ac2eca2f7aaf7d9d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/molecular_docking/helixdock)
![Stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleHelix?color=yellow&style=social)


**Structure prediction of protein-ligand complexes from sequence information with Umol**  
Bryant, Patrick et al  
*Nature Communications 15 (2023): n. pag*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-024-48837-6)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3660911f955c532c186de3b52b03396c851c0aac%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/patrickbryant1/Umol)
![Stars](https://img.shields.io/github/stars/patrickbryant1/Umol?color=yellow&style=social)


**Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom**  
Krishna, Rohith et al  
*bioRxiv (2023): n. pag*  
[![](https://img.shields.io/badge/science-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.science.org/doi/10.1126/science.adl2528)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbbd97deb6e06fe24c5f20fa85e1f276e3065f99f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/baker-laboratory/RoseTTAFold-All-Atom)
![Stars](https://img.shields.io/github/stars/baker-laboratory/RoseTTAFold-All-Atom?color=yellow&style=social)


### 2022 -- Binding-pose-generation
**Equibind: Geometric deep learning for drug binding structure prediction**  
Stärk, Hannes, et al  
*International Conference on Machine Learning. PMLR, 2022*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/stark22b.html)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5309f4bcb15e3dafbed759488551c1650b55dd81%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HannesStark/EquiBind)
![Stars](https://img.shields.io/github/stars/HannesStark/EquiBind?color=yellow&style=social)


**TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction**  
Lu, Wei, et al  
*Advances in Neural Information Processing Systems. 2022*  
[![](https://img.shields.io/badge/openriview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=MSBDFwGYwwt)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb886797dc34c91f186629403d7c7e2092fc25083%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luwei0917/TankBind)
![Stars](https://img.shields.io/github/stars/luwei0917/TankBind?color=yellow&style=social)


### 2021 -- Binding-pose-generation
**State-specific protein-ligand complex structure prediction with a multi-scale deep generative model**  
Qiao, Zhuoran et al  
*arXiv preprint arXiv:2209.15171 (2021)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2209.15171)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc9561b15c25ca781ccf1a384e978e28341bac0e4%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**A geometric deep learning approach to predict binding conformations of bioactive molecules**  
Méndez-Lucio, Oscar, et al   
*Nature Machine Intelligence 3.12 (2021)*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s42256-021-00409-9)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2e17cc055f7313d3c4ebd48c07a6026a408bed9c%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/OptiMaL-PSE-Lab/DeepDock)
![Stars](https://img.shields.io/github/stars/OptiMaL-PSE-Lab/DeepDock?color=yellow&style=social)


## Binding affinity prediction

### 2024 -- Binding-affinity-prediction
**ESM All-Atom: Multi-scale Protein Language Model for Unified Molecular Modeling**  
Zheng, Kangjie et al  
*International Conference on Machine Learning, 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2403.12995)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbbfc82109297ca06cd8c163c3aeaa1b4d1a23fb9%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zhengkangjie/ESM-AA)
![Stars](https://img.shields.io/github/stars/zhengkangjie/ESM-AA?color=yellow&style=social)


**Generalist Equivariant Transformer Towards 3D Molecular Interaction Learning**  
Kong, Xiangzhe et al  
*International Conference on Machine Learning, 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2306.01474)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3187b8fe34086d71135787ad12afe6eb8993ce1f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/THUNLP-MT/GET)
![Stars](https://img.shields.io/github/stars/THUNLP-MT/GET?color=yellow&style=social)


**Protein-ligand binding representation learning from fine-grained interactions**  
Feng, Shikun et al  
*International Conference on Learning Representations, 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2311.16160)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fea273532f62f021accbdc4c703f52abae3aebdce%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


### 2023 -- Binding-affinity-prediction
**Geometric Interaction Graph Neural Network for Predicting Protein–Ligand Binding Affinities from 3D Structures (GIGN)**  
Yang, Ziduo, et al  
*The Journal of Physical Chemistry Letters 14.8 (2023): 2020-2033*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jpclett.2c03906)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F09e85279b10e1532e05bf8a18389a0d398cd0503%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/guaguabujianle/GIGN)
![Stars](https://img.shields.io/github/stars/guaguabujianle/GIGN?color=yellow&style=social)


**Multi-task Bioassay Pre-training for Protein-ligand Binding Affinity Prediction**  
Yan, Jiaxian, et al  
*arXiv preprint arXiv:2306.04886 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2306.04886)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa3f5fa0897ba260aa3d89ba6fc358f742f379a55%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**Improving drug-target affinity prediction via feature fusion and knowledge distillation**  
Lu, Ruiqiang, et al  
*Briefings in Bioinformatics 24.3 (2023)*  
[![](https://img.shields.io/badge/academic-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bib/article/24/3/bbad145/7142721)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2cec660ffaa9c7001afaf37b4fc2ef756ad89808%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/RuiqiangLu/KIDA)
![Stars](https://img.shields.io/github/stars/RuiqiangLu/KIDA?color=yellow&style=social)


**GIANT: Protein-Ligand Binding Affinity Prediction via Geometry-aware Interactive Graph Neural Network**  
Li, Shuangli et al  
*IEEE Transactions on Knowledge and Data Engineering (2023): n. pag*  
[![](https://img.shields.io/badge/computer-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.computer.org/csdl/journal/tk/2024/05/10250845/1Qpfiqmfqko)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff7695ab8f60d121321b7fd30c44c6d503035d06e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zaixizhang/Awesome-SBDD/blob/main)
![Stars](https://img.shields.io/github/stars/Awesome-SBDD/blob?color=yellow&style=social)


### 2022 -- Binding-affinity-prediction
**PIGNet: a physics-informed deep learning model toward generalized drug–target interaction predictions**  
Moon, Seokhyun, et al  
*Chemical Science 13.13 (2022): 3661-3673*  
[![](https://img.shields.io/badge/rsc-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc06946b)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8019fb16bbb35f60d5d9c4052b91739e24879be3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/ACE-KAIST/PIGNet)
![Stars](https://img.shields.io/github/stars/ACE-KAIST/PIGNet?color=yellow&style=social)


**Protein-ligand interaction graphs: Learning from ligand-shaped 3d interaction graphs to improve binding affinity prediction**  
Moesser, Marc A., et al  
*bioRxiv (2022): 2022-03*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2022.03.04.483012v1)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb0e1fd72034388c6163f6002a6228bead3ff9a37%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/MarcMoesser/Protein-Ligand-Interaction-Graphs)
![Stars](https://img.shields.io/github/stars/MarcMoesser/Protein-Ligand-Interaction-Graphs?color=yellow&style=social)


**Efficient and Accurate Physics-aware Multiplex Graph Neural Networks for 3D Small Molecules and Macromolecule Complexes**  
Zhang, Shuo, Yang Liu, and Lei Xie  
*arXiv preprint arXiv:2206.02789 (2022)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2206.02789)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F833ff3cc34c73267ce8265a3c09081fcfeb95325%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


### 2021 -- Binding-affinity-prediction
**Structure-aware interactive graph neural networks for the prediction of protein-ligand binding affinity**  
Li, Shuangli, et al  
*Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining. 2021*  
[![](https://img.shields.io/badge/acm-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://dl.acm.org/doi/abs/10.1145/3447548.3467311)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fef41b29312860bc284640e35ab499053f4966bbf%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/agave233/SIGN)
![Stars](https://img.shields.io/github/stars/agave233/SIGN?color=yellow&style=social)


**Multi-scale representation learning on proteins**  
Somnath, Vignesh Ram, Charlotte Bunne, and Andreas Krause  
*Advances in Neural Information Processing Systems 34 (2021): 25244-25255*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=-xEk43f_EO6)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7c8c1b97463a976e0a133fd72425d6b4cb12c1bc%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/vsomnath/holoprot)
![Stars](https://img.shields.io/github/stars/vsomnath/holoprot?color=yellow&style=social)


**Interactiongraphnet: A novel and efficient deep graph representation learning framework for accurate protein–ligand interaction predictions**  
Jiang, Dejun, et al  
*Journal of medicinal chemistry 64.24 (2021): 18209-18232*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01830)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F517c7e17ff67d70c0a57d4da6acda0ec13f58d75%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zjujdj/IGN)
![Stars](https://img.shields.io/github/stars/zjujdj/IGN?color=yellow&style=social)


**Intrinsic-extrinsic convolution and pooling for learning on 3d protein structures**  
Hermosilla, Pedro, et al  
*International Conference on Learning Representations. 2021*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=l0mSUROpwY)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F18939e167782868f9d5c63e1c7908c1bf70eb284%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/phermosilla/IEConv_proteins)
![Stars](https://img.shields.io/github/stars/phermosilla/IEConv_proteins?color=yellow&style=social)


**Improved protein–ligand binding affinity prediction with structure-based deep fusion inference**  
Jones, Derek, et al  
*Journal of chemical information and modeling 61.4 (2021)*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01306)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcbba6806a864086b5ddf56a0db7462eab2271f30%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/llnl/fast)
![Stars](https://img.shields.io/github/stars/llnl/fast?color=yellow&style=social)


### 2020 -- Binding-affinity-prediction
**RosENet: improving binding affinity prediction by leveraging molecular mechanics energies with an ensemble of 3D convolutional neural networks**  
Hassan-Harrirou, Hussein, Ce Zhang, and Thomas Lemmin  
*Journal of chemical information and modeling 60.6 (2020): 2791-2802*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00075)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1e186ceeff16b19d1f705edef2d662d20fc5ad39%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/DS3Lab/RosENet/tree/master)
![Stars](https://img.shields.io/github/stars/DS3Lab/RosENet?color=yellow&style=social)


### 2019 -- Binding-affinity-prediction
**DeepAtom: A framework for protein-ligand binding affinity prediction**  
Li, Yanjun, et al  
*2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE, 2019*  
[![](https://img.shields.io/badge/ieee-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://ieeexplore.ieee.org/document/8982964)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb212b0270cf5874f9a1c8e0b4cb144c49dfc2eca%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/YanjunLi-CS/DeepAtom_SupplementaryMaterials)
![Stars](https://img.shields.io/github/stars/YanjunLi-CS/DeepAtom_SupplementaryMaterials?color=yellow&style=social)


### 2018 -- Binding-affinity-prediction
**Development and evaluation of a deep learning model for protein–ligand binding affinity prediction**  
Stepniewska-Dziubinska, Marta M., Piotr Zielenkiewicz, and Pawel Siedlecki  
*Bioinformatics 34.21 (2018): 3666-3674*  
[![](https://img.shields.io/badge/academic-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bioinformatics/article/34/21/3666/4994792)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9114a51ef81d88f256e574df1ac8f1a59416f54f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://gitlab.com/cheminfIBB/pafnucy)
![Stars](https://img.shields.io/github/stars/cheminfIBB/pafnucy?color=yellow&style=social)


## De novo ligand generation

### 2024 -- De-novo-ligand-generation
**Protein-Ligand Interaction Prior for Binding-aware 3D Molecule Diffusion Models**  
Huang, Zhilin et al  
*International Conference on Learning Representations, 2024*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=qH9nrMNTIW)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F93d587ece496aceafc5ffa66f9ebdf74a8538a62%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/YangLing0818/IPDiff)
![Stars](https://img.shields.io/github/stars/YangLing0818/IPDiff?color=yellow&style=social)


**DecompOpt: Controllable and Decomposed Diffusion Models for Structure-based Molecular Optimization**  
Zhou, Xiangxin et al  
*International Conference on Learning Representations, 2024*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=Y3BbxvAQS9)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F864abba6a2b3dc2cf4bb94e5e562d42fa7095814%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**Interaction-based Retrieval-augmented Diffusion Models for Protein-specific 3D Molecule Generation**  
Huang, Zhilin et al  
*International Conference on Machine Learning, 2024*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=eejhD9FCP3)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4976f7d7f97a83ab255a57d266c19cf094f2652a%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/YangLing0818/IRDiff)
![Stars](https://img.shields.io/github/stars/YangLing0818/IRDiff?color=yellow&style=social)


### 2023 -- De-novo-ligand-generation
**Equivariant Shape-Conditioned Generation of 3D Molecules for Ligand-Based Drug Design**  
Adams, Keir, and Connor W. Coley  
*International Conference on Learning Representations. 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=4MbGnp4iPQ)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7a78ce6533d26135b087c7c85f79749f09c0d2d0%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/keiradams/SQUID)
![Stars](https://img.shields.io/github/stars/keiradams/SQUID?color=yellow&style=social)


**Prefixmol: Target-and chemistry-aware molecule design via prefix embedding**  
Gao, Zhangyang, et al  
*arXiv preprint arXiv:2302.07120 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2302.07120)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5db270f86b42193812f7cecb943167ce7aa45aaa%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**Molecule generation for target protein binding with structural motifs**  
Zhang, Zaixi, et al  
*International Conference on Learning Representations. 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=Rq13idF0F73)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3d8e9601710eab43a89c0c49a9aaea44e6209b8e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zaixizhang/FLAG)
![Stars](https://img.shields.io/github/stars/zaixizhang/FLAG?color=yellow&style=social)


**Learning Subpocket Prototypes for Generalizable Structure-based Drug Design**  
Zhang, Zaixi, and Qi Liu  
*International Conference on Machine Learning. PMLR, 2023*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2305.13997)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7ae6e65ff850fcd95669a5e8ac71b8f4abaabaf9%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zaixizhang/DrugGPS_ICML23)
![Stars](https://img.shields.io/github/stars/zaixizhang/DrugGPS_ICML23?color=yellow&style=social)


**Lingo3DMol: Generation of a Pocket-based 3D Molecule using a Language Model**  
Wang, Lvwei, et al  
*arXiv preprint arXiv:2305.10133 (2023)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2305.10133)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F50f0dce9ab62001e3d1132169a7a14529c7bd75f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://sw3dmg.stonewise.cn/#/)


**An Equivariant Generative Framework for Molecular Graph-Structure Co-Design**  
Zhang, Zaixi, et al  
*bioRxiv (2023): 2023-04*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.04.13.536803v1)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa46c12129e2b195d7d68e4faf9e36a90ea60246b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zaixizhang/MolCode)
![Stars](https://img.shields.io/github/stars/zaixizhang/MolCode?color=yellow&style=social)


**GraphVF: Controllable Protein-Specific 3D Molecule Generation with Variational Flow**  
Sun, Fang, et al  
*arXiv preprint arXiv:2304.12825 (2023)*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=IB5Njg_ztYB)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9543241def67c49a97b9fcbd1f57b565e8053a4a%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/franco-solis/graphvf-code)
![Stars](https://img.shields.io/github/stars/franco-solis/graphvf-code?color=yellow&style=social)


**Structure-Based Drug Design via Semi-Equivariant Conditional Normalizing Flows**  
Rozenberg, Eyal, Ehud Rivlin, and Daniel Freedman  
*ICLR 2023-Machine Learning for Drug Discovery workshop. 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=TY5iNiUSo-)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F10cd1b2b3e148cf1b2bc65086883aea0d91b7e7b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**3d equivariant diffusion for target-aware molecule generation and affinity prediction**  
Guan, Jiaqi, et al  
*International Conference on Learning Representations. 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=kJqXEPXMsE0)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F59713b444d3268528416f23fe860ba63bb03fc04%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/guanjq/targetdiff)
![Stars](https://img.shields.io/github/stars/guanjq/targetdiff?color=yellow&style=social)


**ResGen is a pocket-aware 3D molecular generation model based on parallel multiscale modelling**  
Zhang, Odin et al  
*Nature Machine Intelligence 5 (2023): 1020 - 1030*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-022-01490-7)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ffee3cf16cd3e3bf0e57f19bb98e8557384a2bfbc%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HaotianZhangAI4Science/ResGen)
![Stars](https://img.shields.io/github/stars/HaotianZhangAI4Science/ResGen?color=yellow&style=social)


**Learning on topological surface and geometric structure for 3D molecular generation**  
Zhang, Odin et al  
*Nature Computational Science 3 (2023): 849 - 859*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s43588-023-00530-2)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F031eb3367cc24fe568a6e7c77df53cb935d7b86f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HaotianZhangAI4Science/SurfGen)
![Stars](https://img.shields.io/github/stars/HaotianZhangAI4Science/SurfGen?color=yellow&style=social)


**DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design**  
Guan, Jiaqi et al  
*International Conference on Machine Learning (2023)*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v202/guan23a/guan23a.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd086b0e2fb58024ce264e985334eddd1314f0e7b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/bytedance/DecompDiff)
![Stars](https://img.shields.io/github/stars/bytedance/DecompDiff?color=yellow&style=social)


**Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration**  
Lin, Haitao et al  
*ArXiv abs/2306.13769 (2023): n. pag*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=lRG11M91dx)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe499649e26e12971a6d62a23491d64620913af72%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


### 2022 -- De-novo-ligand-generation
**Reinforced genetic algorithm for structure-based drug design**  
Fu, Tianfan, et al  
*Advances in Neural Information Processing Systems 35 (2022): 12325-12338*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.neurips.cc/paper_files/paper/2022/file/4fe1859112230a032c7143a9adc3be78-Paper-Conference.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa2d6e9091d3474392a6e2e9b91b0b657afaa4bf0%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/futianfan/reinforced-genetic-algorithm)
![Stars](https://img.shields.io/github/stars/futianfan/reinforced-genetic-algorithm?color=yellow&style=social)


**Relation: A deep generative model for structure-based de novo drug design**  
Wang, Mingyang, et al  
*Journal of Medicinal Chemistry 65.13 (2022): 9478-9492*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00732)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F15215eb9ad3826cb538f3eded033f054bb37be45%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/micahwang/RELATION)
![Stars](https://img.shields.io/github/stars/micahwang/RELATION?color=yellow&style=social)


**Synthesis-driven design of 3D molecules for structure-based drug discovery using geometric transformers**  
Li, Yibo, Jianfeng Pei, and Luhua Lai  
*arXiv preprint arXiv:2301.00167 (2022)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2301.00167)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F81f5792e7bce2ff5edc2148e6f46989e372e14e8%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**Pocket2mol: Efficient molecular sampling based on 3d protein pockets**  
Peng, Xingang, et al  
*International Conference on Machine Learning. PMLR, 2022*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/peng22b.html)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fecd7332cd3d34220a8cf01c30385da123c61dff0%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/pengxingang/Pocket2Mol)
![Stars](https://img.shields.io/github/stars/pengxingang/Pocket2Mol?color=yellow&style=social)


**Zero-Shot 3D Drug Design by Sketching and Generating**  
Long, Siyu, et al  
*arXiv preprint arXiv:2209.13865 (2022)*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=H_xAgRM7I5N)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe6857bd08cbe550642a8048c27dc069142d342d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/longlongman/DESERT)
![Stars](https://img.shields.io/github/stars/longlongman/DESERT?color=yellow&style=social)


**Generating 3d molecules for target protein binding**  
Liu, Meng, et al  
*International Conference on Machine Learning. PMLR, 2022*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/liu22m/liu22m.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd22a60973ca65a2e4e39b5a69c0370f02b255c0d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/divelab/GraphBP)
![Stars](https://img.shields.io/github/stars/divelab/GraphBP?color=yellow&style=social)


**Structure-based drug design with equivariant diffusion models**  
Schneuing, Arne, et al  
*arXiv preprint arXiv:2210.13695 (2022)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2210.13695)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F522d00e2540df1c4a4c4b7f8da843ffd937f77c4%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/arneschneuing/DiffSBDD)
![Stars](https://img.shields.io/github/stars/arneschneuing/DiffSBDD?color=yellow&style=social)


**DiffBP: Generative Diffusion of 3D Molecules for Target Protein Binding**  
Lin, Haitao, et al  
*arXiv preprint arXiv:2211.11214 (2022)*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/liu22m/liu22m.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F84e07c84a411ec5ed0828049d777b9cb8129c14d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/divelab/GraphBP)
![Stars](https://img.shields.io/github/stars/divelab/GraphBP?color=yellow&style=social)


### 2021 -- De-novo-ligand-generation
**Structure-based de novo drug design using 3D deep generative models**  
Li, Yibo, Jianfeng Pei, and Luhua Lai  
*Chemical science 12.41 (2021): 13664-13675*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc04444c)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F02b86623755c6541a3799c26b31bd8f2918ce3f8%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**A 3D generative model for structure-based drug design**  
Luo, Shitong, et al  
*Advances in Neural Information Processing Systems 34 (2021): 6229-6239*  
[![](https://img.shields.io/badge/papers-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://papers.nips.cc/paper/2021/hash/314450613369e0ee72d0da7f6fee773c-Abstract.html)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd651f7b09f554482bc7a5ffa1381dda1dc73050c%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luost26/3D-Generative-SBDD)
![Stars](https://img.shields.io/github/stars/luost26/3D-Generative-SBDD?color=yellow&style=social)


### 2020 -- De-novo-ligand-generation
**AutoGrow4: an open-source genetic algorithm for de novo drug design and lead optimization**  
Spiegel, Jacob O., and Jacob D. Durrant  
*Journal of cheminformatics 12.1 (2020): 1-16*  
[![](https://img.shields.io/badge/biomedcentral-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00429-4)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc7d6f62ca7e5e857c0bca2cf2675d43953dc6a42%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://durrantlab.pitt.edu/autogrow4/)


**Generating 3d molecular structures conditional on a receptor binding site with deep generative models**  
Masuda, Tomohide, Matthew Ragoza, and David Ryan Koes  
*arXiv preprint arXiv:2010.14442 (2020)*  
[![](https://img.shields.io/badge/rsc-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc05976a)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4b525c91a75f90c3ecd478324c0c77e0f839c675%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/mattragoza/LiGAN)
![Stars](https://img.shields.io/github/stars/mattragoza/LiGAN?color=yellow&style=social)


## Linker design

### 2023 -- Linker-design
**3D Based Generative PROTAC Linker Design with Reinforcement Learning**  
Chen, Hongming  
[![](https://img.shields.io/badge/chemrxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://chemrxiv.org/engage/chemrxiv/article-details/646c5a71b3dd6a653095b6ec)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe5ae0dfbf7d51f7f2783371faed11b51dac0e416%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)


**LinkerNet: Fragment Poses and Linker Co-Design with 3D Equivariant Diffusion**  
Guan, Jiaqi, et al  
*Advances in Neural Information Processing Systems, 2023*  
[![](https://img.shields.io/badge/openreview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/pdf?id=6EaLIw3W7c)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcc18b11785f7f5d15c261143e55c86fe70048d58%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/guanjq/LinkerNet)
![Stars](https://img.shields.io/github/stars/guanjq/LinkerNet?color=yellow&style=social)


### 2022 -- Linker-design
**3dlinker: An e (3) equivariant variational autoencoder for molecular linker design**  
Huang, Yinan, et al  
*International Conference on Machine Learning. PMLR, 2022*  
[![](https://img.shields.io/badge/proceedings_mlr_press-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/huang22g/huang22g.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fe2e8523d0010f5481e01dff6ef81c34bbafd2124%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/YinanHuang/3DLinker)
![Stars](https://img.shields.io/github/stars/YinanHuang/3DLinker?color=yellow&style=social)


**Equivariant 3d-conditional diffusion models for molecular linker design**  
Igashov, Ilia, et al  
*arXiv preprint arXiv:2210.05274 (2022)*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2210.05274)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd592f4630586b03bb8eb653908fb0f8ee5a35f1f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/igashov/DiffLinker)
![Stars](https://img.shields.io/github/stars/igashov/DiffLinker?color=yellow&style=social)


### 2020 -- Linker-design
**Deep generative models for 3D linker design**  
Imrie, Fergus, et al  
*Journal of chemical information and modeling 60.4 (2020)*  
[![](https://img.shields.io/badge/acs-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa1aed6c0f20b659bb0c5f559c6d33584d51c5aab%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/oxpig/DeLinker)
![Stars](https://img.shields.io/github/stars/oxpig/DeLinker?color=yellow&style=social)

## Protein Pocket Generation

### 2023 -- Protein-pocket-generation

