# Awesome-SBDD
Papers about Structure-based Drug Design (SBDD)

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Created](https://img.shields.io/badge/Created-2021--09-green.svg) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)

<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)  ![Forks](https://img.shields.io/github/forks/zaixizhang/Awesome-SBDD?color=blue&label=Fork) -->

This repository contains a list of papers on the Structure-based Drug Design; we categorize them based on their detailed tasks and methods.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

## Table of Contents                                           
- [Binding site prediction](#binding-site-prediction)                     
- [Binding pose generation](#binding-pose-generation)             
- [Binding affinity prediction](#binding-affinity-prediction)               
- [De novo ligand generation](#de-novo-ligand-generation)   
- [Linker design](#linker-design) 


## Binding site prediction
- [ ] Gainza, Pablo et al. “Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning.” Nature Methods 17 (2019): 184-192. [[Paper](https://www.nature.com/articles/s41592-019-0666-6)][[Code](https://github.com/lpdi-epfl/masif)]
- [ ] Sverrisson, Freyr, et al. "Fast end-to-end learning on protein surfaces." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2021. [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Sverrisson_Fast_End-to-End_Learning_on_Protein_Surfaces_CVPR_2021_paper.pdf)][[Code](https://github.com/FreyrS/dMaSIF)]
- [ ] Krapp, Lucien F., et al. "PeSTo: parameter-free geometric deep learning for accurate prediction of protein binding interfaces." Nature Communications 14 (2023): 2175. [[Paper](https://www.nature.com/articles/s41467-023-37701-8)][[Code](https://github.com/LBM-EPFL/PeSTo)]
- [ ] Tubiana, Jérôme, Dina Schneidman-Duhovny, and Haim J. Wolfson. "ScanNet: an interpretable geometric deep learning model for structure-based protein binding site prediction." Nature Methods 19.6 (2022): 730-739. [[Paper](https://www.nature.com/articles/s41592-022-01490-7)][[Code](https://github.com/jertubiana/ScanNet)]
- [ ] Meller, Artur, et al. "Predicting the locations of cryptic pockets from single protein structures using the PocketMiner graph neural network." Nature Communications 14 (2023): 1177. [[Paper](https://www.nature.com/articles/s41467-023-36699-3)][[Code](https://github.com/Mickdub/gvp/tree/pocket_pred)]
- [ ] Fout, Alex, et al. "Protein interface prediction using graph convolutional networks." Advances in neural information processing systems 30 (2017). [[Paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/f507783927f2ec2737ba40afbd17efb5-Paper.pdf)][[Code](https://github.com/fouticus/pipgcn)]
- [ ] Zhang, Yang, et al. "EquiPocket: an E (3)-Equivariant Geometric Graph Neural Network for Ligand Binding Site Prediction." arXiv preprint arXiv:2302.12177 (2023). [[Paper](https://arxiv.org/abs/2302.12177)]
- [ ] Abdollahi, Nasim, et al. "NodeCoder: a graph-based machine learning platform to predict active sites of modeled protein structures." arXiv preprint arXiv:2302.03590 (2023). [[Paper](https://arxiv.org/abs/2302.03590)][[Code](https://github.com/NasimAbdollahi/NodeCoder)]
- [ ] Jiménez, José, et al. "DeepSite: protein-binding site predictor using 3D-convolutional neural networks." Bioinformatics 33.19 (2017): 3036-3042. [[Paper](https://academic.oup.com/bioinformatics/article/33/19/3036/3859178)]
- [ ] Kandel, Jeevan, Hilal Tayara, and Kil To Chong. "PUResNet: prediction of protein-ligand binding sites using deep residual neural network." Journal of cheminformatics 13.1 (2021): 1-14. [[Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00547-7)][[Code](https://github.com/jivankandel/PUResNet)]

## Binding pose generation
- [ ] Stärk, Hannes, et al. "Equibind: Geometric deep learning for drug binding structure prediction." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/stark22b.html)][[Code](https://github.com/HannesStark/EquiBind)]
- [ ] Méndez-Lucio, Oscar, et al. "A geometric deep learning approach to predict binding conformations of bioactive molecules." Nature Machine Intelligence 3.12 (2021): 1033-1039. [[Paper](https://www.nature.com/articles/s42256-021-00409-9)][[Code](https://github.com/OptiMaL-PSE-Lab/DeepDock)]
- [ ] Lu, Wei, et al. "TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction." Advances in Neural Information Processing Systems. 2022. [[Paper](https://openreview.net/forum?id=MSBDFwGYwwt)][[Code](https://github.com/luwei0917/TankBind)]
- [ ] Masters, Matthew R., et al. "Deep learning model for efficient protein–ligand docking with implicit side-chain flexibility." Journal of Chemical Information and Modeling 63.6 (2023): 1695-1707. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01436)][[Code](https://github.com/MatthewMasters/EDM-Dock)]
- [ ] Nakata, Shuya, Yoshiharu Mori, and Shigenori Tanaka. "End-to-end protein–ligand complex structure generation with diffusion-based generative models." BMC bioinformatics 24.1 (2023): 1-18. [[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05354-5)][[Code](https://github.com/shuyana/DiffusionProteinLigand)]
- [ ] Corso, Gabriele, et al. "Diffdock: Diffusion steps, twists, and turns for molecular docking." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=kKF8_K-mBbS)][[Code](https://github.com/gcorso/DiffDock)]
- [ ] Qiao, Zhuoran et al. “State-specific protein-ligand complex structure prediction with a multi-scale deep generative model.” arXiv preprint arXiv:2209.15171 (2021). [[Paper](https://arxiv.org/abs/2209.15171)]
- [ ] Zhang, Yangtian, et al. "E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=sO1QiAftQFv)]
- [ ] Wang, Zechen, et al. "A fully differentiable ligand pose optimization framework guided by deep learning and a traditional scoring function." Briefings in Bioinformatics 24.1 (2023): bbac520. [[Paper](https://academic.oup.com/bib/article-abstract/24/1/bbac520/6887112?redirectedFrom=fulltext)][[Code](https://github.com/zchwang/DeepRMSD-Vina_Optimization)]
- [ ] Mailoa, Jonathan P., et al. "Protein-Ligand Complex Generator & Drug Screening via Tiered Tensor Transform." arXiv preprint arXiv:2301.00984 (2023). [[Paper](https://arxiv.org/abs/2301.00984)]

## Binding affinity prediction
- [ ] Li, Shuangli, et al. "Structure-aware interactive graph neural networks for the prediction of protein-ligand binding affinity." Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining. 2021. [[Paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467311)][[Code](https://github.com/agave233/SIGN)]
- [ ] Moon, Seokhyun, et al. "PIGNet: a physics-informed deep learning model toward generalized drug–target interaction predictions." Chemical Science 13.13 (2022): 3661-3673. [[Paper](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc06946b)][[Code](https://github.com/ACE-KAIST/PIGNet)]
- [ ] Somnath, Vignesh Ram, Charlotte Bunne, and Andreas Krause. "Multi-scale representation learning on proteins." Advances in Neural Information Processing Systems 34 (2021): 25244-25255. [[Paper](https://openreview.net/forum?id=-xEk43f_EO6)][[Code](https://github.com/vsomnath/holoprot)]
- [ ] Moesser, Marc A., et al. "Protein-ligand interaction graphs: Learning from ligand-shaped 3d interaction graphs to improve binding affinity prediction." bioRxiv (2022): 2022-03. [[Paper](https://www.biorxiv.org/content/10.1101/2022.03.04.483012v1)][[Code](https://github.com/MarcMoesser/Protein-Ligand-Interaction-Graphs)]
- [ ] Zhang, Shuo, Yang Liu, and Lei Xie. "Efficient and Accurate Physics-aware Multiplex Graph Neural Networks for 3D Small Molecules and Macromolecule Complexes." arXiv preprint arXiv:2206.02789 (2022). [[Paper](https://arxiv.org/abs/2206.02789)]
- [ ] Jiang, Dejun, et al. "Interactiongraphnet: A novel and efficient deep graph representation learning framework for accurate protein–ligand interaction predictions." Journal of medicinal chemistry 64.24 (2021): 18209-18232. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01830)][[Code](https://github.com/zjujdj/IGN)]
- [ ] Yang, Ziduo, et al. "Geometric Interaction Graph Neural Network for Predicting Protein–Ligand Binding Affinities from 3D Structures (GIGN)." The Journal of Physical Chemistry Letters 14.8 (2023): 2020-2033. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jpclett.2c03906)][[Code](https://github.com/guaguabujianle/GIGN)]
- [ ] Yan, Jiaxian, et al. "Multi-task Bioassay Pre-training for Protein-ligand Binding Affinity Prediction." arXiv preprint arXiv:2306.04886 (2023). [[Paper](https://arxiv.org/abs/2306.04886)]
- [ ] Stepniewska-Dziubinska, Marta M., Piotr Zielenkiewicz, and Pawel Siedlecki. "Development and evaluation of a deep learning model for protein–ligand binding affinity prediction." Bioinformatics 34.21 (2018): 3666-3674. [[Paper](https://academic.oup.com/bioinformatics/article/34/21/3666/4994792)][[Code](https://gitlab.com/cheminfIBB/pafnucy)]
- [ ] Li, Yanjun, et al. "DeepAtom: A framework for protein-ligand binding affinity prediction." 2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE, 2019. [[Paper](https://ieeexplore.ieee.org/document/8982964)][[Code](https://github.com/YanjunLi-CS/DeepAtom_SupplementaryMaterials)]
- [ ] Hassan-Harrirou, Hussein, Ce Zhang, and Thomas Lemmin. "RosENet: improving binding affinity prediction by leveraging molecular mechanics energies with an ensemble of 3D convolutional neural networks." Journal of chemical information and modeling 60.6 (2020): 2791-2802. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00075)][[Code](https://github.com/DS3Lab/RosENet/tree/master)]
- [ ] Hermosilla, Pedro, et al. "Intrinsic-extrinsic convolution and pooling for learning on 3d protein structures." International Conference on Learning Representations. 2021. [[Paper](https://openreview.net/forum?id=l0mSUROpwY)][[Code](https://github.com/phermosilla/IEConv_proteins)]
- [ ] Lu, Ruiqiang, et al. "Improving drug-target affinity prediction via feature fusion and knowledge distillation." Briefings in Bioinformatics 24.3 (2023): bbad145. [[Paper](https://academic.oup.com/bib/article/24/3/bbad145/7142721)][[Code](https://github.com/RuiqiangLu/KIDA)]
- [ ] Jones, Derek, et al. "Improved protein–ligand binding affinity prediction with structure-based deep fusion inference." Journal of chemical information and modeling 61.4 (2021): 1583-1592. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01306)][[Code](https://github.com/llnl/fast)]

## De novo ligand generation
- [ ] Spiegel, Jacob O., and Jacob D. Durrant. "AutoGrow4: an open-source genetic algorithm for de novo drug design and lead optimization." Journal of cheminformatics 12.1 (2020): 1-16. [[Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00429-4)][[Code](https://durrantlab.pitt.edu/autogrow4/)]
- [ ] Fu, Tianfan, et al. "Reinforced genetic algorithm for structure-based drug design." Advances in Neural Information Processing Systems 35 (2022): 12325-12338. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/4fe1859112230a032c7143a9adc3be78-Paper-Conference.pdf)][[Code](https://github.com/futianfan/reinforced-genetic-algorithm)]
- [ ] Masuda, Tomohide, Matthew Ragoza, and David Ryan Koes. "Generating 3d molecular structures conditional on a receptor binding site with deep generative models." arXiv preprint arXiv:2010.14442 (2020). [[Paper](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc05976a)][[Code](https://github.com/mattragoza/LiGAN)]
- [ ] Wang, Mingyang, et al. "Relation: A deep generative model for structure-based de novo drug design." Journal of Medicinal Chemistry 65.13 (2022): 9478-9492. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00732)][[Code](https://github.com/micahwang/RELATION)]
- [ ] Adams, Keir, and Connor W. Coley. "Equivariant Shape-Conditioned Generation of 3D Molecules for Ligand-Based Drug Design." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=4MbGnp4iPQ)][[Code](https://github.com/keiradams/SQUID)]
- [ ] Li, Yibo, Jianfeng Pei, and Luhua Lai. "Structure-based de novo drug design using 3D deep generative models." Chemical science 12.41 (2021): 13664-13675. [[Paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc04444c)]
- [ ] Li, Yibo, Jianfeng Pei, and Luhua Lai. "Synthesis-driven design of 3D molecules for structure-based drug discovery using geometric transformers." arXiv preprint arXiv:2301.00167 (2022). [[Paper](https://arxiv.org/abs/2301.00167)]
- [ ] Luo, Shitong, et al. "A 3D generative model for structure-based drug design." Advances in Neural Information Processing Systems 34 (2021): 6229-6239. [[Paper](https://papers.nips.cc/paper/2021/hash/314450613369e0ee72d0da7f6fee773c-Abstract.html)][[Code](https://github.com/luost26/3D-Generative-SBDD)]
- [ ] Peng, Xingang, et al. "Pocket2mol: Efficient molecular sampling based on 3d protein pockets." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/peng22b.html)][[Code](https://github.com/pengxingang/Pocket2Mol)]
- [ ] Long, Siyu, et al. "Zero-Shot 3D Drug Design by Sketching and Generating." arXiv preprint arXiv:2209.13865 (2022). [[Paper](https://openreview.net/forum?id=H_xAgRM7I5N)][[Code](https://github.com/longlongman/DESERT)]
- [ ] Gao, Zhangyang, et al. "Prefixmol: Target-and chemistry-aware molecule design via prefix embedding." arXiv preprint arXiv:2302.07120 (2023). [[Paper](https://arxiv.org/abs/2302.07120)]
- [ ] Zhang, Zaixi, et al. "Molecule generation for target protein binding with structural motifs." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=Rq13idF0F73)][[Code](https://github.com/zaixizhang/FLAG)]
- [ ] Zhang, Zaixi, and Qi Liu. "Learning Subpocket Prototypes for Generalizable Structure-based Drug Design." International Conference on Machine Learning. PMLR, 2023. [[Paper](https://arxiv.org/abs/2305.13997)][[Code](https://github.com/zaixizhang/DrugGPS_ICML23)]
- [ ] Wang, Lvwei, et al. "Lingo3DMol: Generation of a Pocket-based 3D Molecule using a Language Model." arXiv preprint arXiv:2305.10133 (2023). [[Paper](https://arxiv.org/abs/2305.10133)][[Code](https://sw3dmg.stonewise.cn/#/)]
- [ ] Liu, Meng, et al. "Generating 3d molecules for target protein binding." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/liu22m/liu22m.pdf)][[Code](https://github.com/divelab/GraphBP)]
- [ ] Zhang, Zaixi, et al. "An Equivariant Generative Framework for Molecular Graph-Structure Co-Design." bioRxiv (2023): 2023-04. [[Paper](https://www.biorxiv.org/content/10.1101/2023.04.13.536803v1)][[Code](https://github.com/zaixizhang/MolCode)]
- [ ] Sun, Fang, et al. "GraphVF: Controllable Protein-Specific 3D Molecule Generation with Variational Flow." arXiv preprint arXiv:2304.12825 (2023). [[Paper](https://openreview.net/forum?id=IB5Njg_ztYB)][[Code](https://github.com/franco-solis/graphvf-code)]
- [ ] Rozenberg, Eyal, Ehud Rivlin, and Daniel Freedman. "Structure-Based Drug Design via Semi-Equivariant Conditional Normalizing Flows." ICLR 2023-Machine Learning for Drug Discovery workshop. 2023. [[Paper](https://openreview.net/forum?id=TY5iNiUSo-)]
- [ ] Schneuing, Arne, et al. "Structure-based drug design with equivariant diffusion models." arXiv preprint arXiv:2210.13695 (2022). [[Paper](https://arxiv.org/abs/2210.13695)][[Code](https://github.com/arneschneuing/DiffSBDD)]
- [ ] Guan, Jiaqi, et al. "3d equivariant diffusion for target-aware molecule generation and affinity prediction." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=kJqXEPXMsE0)][[Code](https://github.com/guanjq/targetdiff)]
- [ ] Lin, Haitao, et al. "DiffBP: Generative Diffusion of 3D Molecules for Target Protein Binding." arXiv preprint arXiv:2211.11214 (2022). [[Paper](https://proceedings.mlr.press/v162/liu22m/liu22m.pdf)][[Code](https://github.com/divelab/GraphBP)]

## Linker design
- [ ] Imrie, Fergus, et al. "Deep generative models for 3D linker design." Journal of chemical information and modeling 60.4 (2020): 1983-1995. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120)][[Code](https://github.com/oxpig/DeLinker)]
- [ ] Huang, Yinan, et al. "3dlinker: An e (3) equivariant variational autoencoder for molecular linker design." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/huang22g/huang22g.pdf)][[Code](https://github.com/YinanHuang/3DLinker)]
- [ ] Chen, Hongming. "3D Based Generative PROTAC Linker Design with Reinforcement Learning." (2023). [[Paper](https://chemrxiv.org/engage/chemrxiv/article-details/646c5a71b3dd6a653095b6ec)]
- [ ] Igashov, Ilia, et al. "Equivariant 3d-conditional diffusion models for molecular linker design." arXiv preprint arXiv:2210.05274 (2022). [[Paper](https://arxiv.org/abs/2210.05274)][[Code](https://github.com/igashov/DiffLinker)]
