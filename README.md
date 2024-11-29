# Awesome-SBDD
Our survey paper: [A Systematic Survey in Geometric Deep Learning for Structure-based Drug Design](
https://arxiv.org/abs/2306.11768)

Papers about Structure-based Drug Design (SBDD)

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Created](https://img.shields.io/badge/Created-2023--06-green.svg) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)

<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/zaixizhang/Awesome-SBDD?color=yellow)  ![Forks](https://img.shields.io/github/forks/zaixizhang/Awesome-SBDD?color=blue&label=Fork) -->

This repository contains a list of papers on the Structure-based Drug Design; we categorize them based on their detailed tasks and methods.

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





### 2023 -- Binding-pose-generation





### 2022 -- Binding-pose-generation





### 2021 -- Binding-pose-generation






- [ ] Qiao, Zhuoran et al. “State-specific protein-ligand complex structure prediction with a multi-scale deep generative model.” arXiv preprint arXiv:2209.15171 (2021). [[Paper](https://arxiv.org/abs/2209.15171)]
- [ ] Stärk, Hannes, et al. "Equibind: Geometric deep learning for drug binding structure prediction." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/stark22b.html)][[Code](https://github.com/HannesStark/EquiBind)]
- [ ] Méndez-Lucio, Oscar, et al. "A geometric deep learning approach to predict binding conformations of bioactive molecules." Nature Machine Intelligence 3.12 (2021): 1033-1039. [[Paper](https://www.nature.com/articles/s42256-021-00409-9)][[Code](https://github.com/OptiMaL-PSE-Lab/DeepDock)]
- [ ] Lu, Wei, et al. "TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction." Advances in Neural Information Processing Systems. 2022. [[Paper](https://openreview.net/forum?id=MSBDFwGYwwt)][[Code](https://github.com/luwei0917/TankBind)]
- [ ] Masters, Matthew R., et al. "Deep learning model for efficient protein–ligand docking with implicit side-chain flexibility." Journal of Chemical Information and Modeling 63.6 (2023): 1695-1707. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01436)][[Code](https://github.com/MatthewMasters/EDM-Dock)]
- [ ] Nakata, Shuya, Yoshiharu Mori, and Shigenori Tanaka. "End-to-end protein–ligand complex structure generation with diffusion-based generative models." BMC bioinformatics 24.1 (2023): 1-18. [[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05354-5)][[Code](https://github.com/shuyana/DiffusionProteinLigand)]
- [ ] Corso, Gabriele, et al. "Diffdock: Diffusion steps, twists, and turns for molecular docking." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=kKF8_K-mBbS)][[Code](https://github.com/gcorso/DiffDock)]
- [ ] Zhou, Gengmo et al. “Uni-Mol: A Universal 3D Molecular Representation Learning Framework.” International Conference on Learning Representations (2023).[[Paper](https://openreview.net/pdf?id=6K2RM6wVqKu)][[Code](https://github.com/deepmodeling/Uni-Mol)]
- [ ] Zhang, Yangtian, et al. "E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking." International Conference on Learning Representations. 2023. [[Paper](https://openreview.net/forum?id=sO1QiAftQFv)]
- [ ] Wang, Zechen, et al. "A fully differentiable ligand pose optimization framework guided by deep learning and a traditional scoring function." Briefings in Bioinformatics 24.1 (2023): bbac520. [[Paper](https://academic.oup.com/bib/article-abstract/24/1/bbac520/6887112?redirectedFrom=fulltext)][[Code](https://github.com/zchwang/DeepRMSD-Vina_Optimization)]
- [ ] Mailoa, Jonathan P., et al. "Protein-Ligand Complex Generator & Drug Screening via Tiered Tensor Transform." arXiv preprint arXiv:2301.00984 (2023). [[Paper](https://arxiv.org/abs/2301.00984)]
- [ ] Huang, Yupeng et al. “DSDP: A Blind Docking Strategy Accelerated by GPUs.” Journal of chemical information and modeling (2023): n. pag. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00519)][[Code](https://github.com/PKUGaoGroup/DSDP)]
- [ ] Dong, Tiejun et al. “Equivariant Flexible Modeling of the Protein-Ligand Binding Pose with Geometric Deep Learning.” Journal of chemical theory and computation (2023): n. pag. [[Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.3c00273)][[Code](https://github.com/tiejundong/FlexPose)]
- [ ] Plainer, Michael, et al. "DiffDock-Pocket: Diffusion for Pocket-Level Docking with Sidechain Flexibility." Advances in Neural Information Processing Systems, Workshop. 2023. [[Paper](https://plainer.dev/assets/pdf/2023/DiffDock-Pocket.pdf)][[Code](https://anonymous.4open.science/r/DiffDock-Pocket-AQ32)]
- [ ] Lu, Wei et al. “DynamicBind: predicting ligand-specific protein-ligand complex structure with a deep equivariant generative model.” Nature Communications 15 (2024) [[Paper](https://www.nature.com/articles/s41467-024-45461-2)][[Code](https://github.com/luwei0917/DynamicBind)]
- [ ] Zhang, Xujun et al. “Efficient and accurate large library ligand docking with KarmaDock.” Nature Computational Science 3 (2023): 789 - 804. [[Paper](https://www.nature.com/articles/s43588-023-00511-5)][[Code](https://github.com/schrojunzhang/KarmaDock)]
- [ ] Cai, Heng et al. “CarsiDock: a deep learning paradigm for accurate protein–ligand docking and screening based on large-scale pre-training.” Chemical Science 15 (2023): 1449 - 1471. [[Paper](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc05552c)][[Code](https://github.com/carbonsilicon-ai/CarsiDock)]
- [ ] Pei, Qizhi et al. “FABind: Fast and Accurate Protein-Ligand Binding.” Advances in Neural Information Processing Systems. 2023. [[Paper](https://openreview.net/forum?id=PnWakgg1RL)][[Code](https://github.com/QizhiPei/FABind)]
- [ ] Yan, Jiaxian et al. “Multi-scale Iterative Refinement towards Robust and Versatile Molecular Docking.” ArXiv abs/2311.18574 (2023): n. pag. [[Paper](https://arxiv.org/abs/2311.18574)]
- [ ] Cao, Duanhua et al. “SurfDock is a Surface-Informed Diffusion Generative Model for Reliable and Accurate Protein-ligand Complex Prediction.” bioRxiv (2023): n. pag. [[Paper](https://www.biorxiv.org/content/10.1101/2023.12.13.571408v1.full.pdf)][[Code](https://github.com/CAODH/SurfDock)]
- [ ] Zhu, Jintao et al. “DiffBindFR: An SE(3) Equivariant Network for Flexible Protein-Ligand Docking.” (2023). [[Paper](https://arxiv.org/abs/2311.15201)][[Code](https://github.com/HBioquant/DiffBindFR)]
- [ ] Zhang, Runze et al. “PackDock: a Diffusion Based Side Chain Packing Model for Flexible Protein-Ligand Docking.” bioRxiv (2024): n. pag. [[Paper](https://www.biorxiv.org/content/10.1101/2024.01.31.578200v1.full.pdf)][[Code](https://github.com/Zhang-Runze/PackDock)]
- [ ] Huang, Yufei et al. “Re-Dock: Towards Flexible and Realistic Molecular Docking with Diffusion Bridge.” (2024). [[Paper](https://arxiv.org/pdf/2402.11459.pdf)]
- [ ] Jing, Bowen et al. “Equivariant Scalar Fields for Molecular Docking with Fast Fourier Transforms.” International Conference on Learning Representations, 2024 [[Paper](https://openreview.net/forum?id=BIveOmD1Nh)][[Code](https://github.com/bjing2016/scalar-fields)]
- [ ] Stärk, Hannes et al. "Harmonic Self-Conditioned Flow Matching for Multi-Ligand Docking and Binding Site Design." International Conference on Machine Learning, 2024 [[Paper](https://arxiv.org/abs/2310.05764)][[Code](https://github.com/HannesStark/FlowSite)]
- [ ] Alcaide, Eric et al. “Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction.” ArXiv abs/2405.11769 (2024): n. pag. [[Paper](https://arxiv.org/pdf/2405.11769)][[Code](https://github.com/deepmodeling/Uni-Mol/tree/main/unimol_docking_v2)]
- [ ] Gao, Kaiyuan et al. “FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation.” ArXiv abs/2403.20261 (2024): n. pag. [[Paper](https://arxiv.org/pdf/2403.20261)][[Code](https://github.com/QizhiPei/FABind/tree/main/FABind_plus)]
- [ ] Corso, Gabriele et al. “Deep Confident Steps to New Pockets: Strategies for Docking Generalization.” ArXiv (2024): n. pag. [[Paper](https://openreview.net/pdf?id=UfBIxpTK10)][[Code](https://github.com/gcorso/DiffDock)]
- [ ] Liu, Lihang et al. “Pre-Training on Large-Scale Generated Docking Conformations with HelixDock to Unlock the Potential of Protein-ligand Structure Prediction Models.” ArXiv abs/2310.13913 (2023): n. pag. [[Paper](https://arxiv.org/pdf/2310.13913)][[Code](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/molecular_docking/helixdock)]
- [ ] Bryant, Patrick et al. “Structure prediction of protein-ligand complexes from sequence information with Umol.” Nature Communications 15 (2023): n. pag. [[Paper](https://www.nature.com/articles/s41467-024-48837-6)][[Code](https://github.com/patrickbryant1/Umol)]
- [ ] Boitreaud, Jacques et al. “Chai-1: Decoding the molecular interactions of life.” bioRxiv (2024): n. pag. [[Paper](https://www.biorxiv.org/content/10.1101/2024.10.10.615955v2.full.pdf)][[Code](https://github.com/chaidiscovery/chai-lab)]
- [ ] Abramson, Josh et al. “Accurate structure prediction of biomolecular interactions with AlphaFold 3.” Nature 630 (2024): 493 - 500. [[Paper](https://www.nature.com/articles/s41586-024-07487-w)]
- [ ] Krishna, Rohith et al. “Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom.” bioRxiv (2023): n. pag. [[Paper](https://www.science.org/doi/10.1126/science.adl2528)][[Code](https://github.com/baker-laboratory/RoseTTAFold-All-Atom)]

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
- [ ] Li, Shuangli et al. “GIANT: Protein-Ligand Binding Affinity Prediction via Geometry-aware Interactive Graph Neural Network.” IEEE Transactions on Knowledge and Data Engineering (2023): n. pag. [[Paper](https://www.computer.org/csdl/journal/tk/2024/05/10250845/1Qpfiqmfqko)][[Code]()]
- [ ] Zheng, Kangjie et al. "ESM All-Atom: Multi-scale Protein Language Model for Unified Molecular Modeling." International Conference on Machine Learning, 2024 [[Paper](https://arxiv.org/abs/2403.12995)][[Code](https://github.com/zhengkangjie/ESM-AA)]
- [ ] Kong, Xiangzhe et al. "Generalist Equivariant Transformer Towards 3D Molecular Interaction Learning." International Conference on Machine Learning, 2024 [[Paper](https://arxiv.org/abs/2306.01474)][[Code](https://github.com/THUNLP-MT/GET)]
- [ ] Feng, Shikun et al. "Protein-ligand binding representation learning from fine-grained interactions." International Conference on Learning Representations, 2024 [[Paper](https://arxiv.org/abs/2311.16160)]

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
- [ ] Zhang, Odin et al. “ResGen is a pocket-aware 3D molecular generation model based on parallel multiscale modelling.” Nature Machine Intelligence 5 (2023): 1020 - 1030. [[Paper](https://www.nature.com/articles/s42256-023-00712-7)][[Code](https://github.com/HaotianZhangAI4Science/ResGen)]
- [ ] Zhang, Odin et al. “Learning on topological surface and geometric structure for 3D molecular generation.” Nature Computational Science 3 (2023): 849 - 859. [[Paper](https://www.nature.com/articles/s43588-023-00530-2)][[Code](https://github.com/HaotianZhangAI4Science/SurfGen)]
- [ ] Guan, Jiaqi et al. “DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design.” International Conference on Machine Learning (2023). [[Paper](https://proceedings.mlr.press/v202/guan23a/guan23a.pdf)][[Code](https://github.com/bytedance/DecompDiff)]
- [ ] Lin, Haitao et al. “Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration.” ArXiv abs/2306.13769 (2023): n. pag. [[Paper](https://openreview.net/pdf?id=lRG11M91dx)]
- [ ] Huang, Zhilin et al. "Protein-Ligand Interaction Prior for Binding-aware 3D Molecule Diffusion Models." International Conference on Learning Representations, 2024 [[Paper](https://openreview.net/pdf?id=qH9nrMNTIW)][[Code](https://github.com/YangLing0818/IPDiff)]
- [ ] Zhou, Xiangxin et al. "DecompOpt: Controllable and Decomposed Diffusion Models for Structure-based Molecular Optimization." International Conference on Learning Representations, 2024 [[Paper](https://openreview.net/forum?id=Y3BbxvAQS9)]
- [ ] Huang, Zhilin et al. "Interaction-based Retrieval-augmented Diffusion Models for Protein-specific 3D Molecule Generation." International Conference on Machine Learning, 2024 [[Paper](https://openreview.net/pdf?id=eejhD9FCP3)][[Code](https://github.com/YangLing0818/IRDiff)]

## Linker design
- [ ] Imrie, Fergus, et al. "Deep generative models for 3D linker design." Journal of chemical information and modeling 60.4 (2020): 1983-1995. [[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120)][[Code](https://github.com/oxpig/DeLinker)]
- [ ] Huang, Yinan, et al. "3dlinker: An e (3) equivariant variational autoencoder for molecular linker design." International Conference on Machine Learning. PMLR, 2022. [[Paper](https://proceedings.mlr.press/v162/huang22g/huang22g.pdf)][[Code](https://github.com/YinanHuang/3DLinker)]
- [ ] Chen, Hongming. "3D Based Generative PROTAC Linker Design with Reinforcement Learning." (2023). [[Paper](https://chemrxiv.org/engage/chemrxiv/article-details/646c5a71b3dd6a653095b6ec)]
- [ ] Igashov, Ilia, et al. "Equivariant 3d-conditional diffusion models for molecular linker design." arXiv preprint arXiv:2210.05274 (2022). [[Paper](https://arxiv.org/abs/2210.05274)][[Code](https://github.com/igashov/DiffLinker)]
- [ ] Guan, Jiaqi, et al. "LinkerNet: Fragment Poses and Linker Co-Design with 3D Equivariant Diffusion." Advances in Neural Information Processing Systems, 2023 [[Paper](https://openreview.net/pdf?id=6EaLIw3W7c)][[Code](https://github.com/guanjq/LinkerNet)]



