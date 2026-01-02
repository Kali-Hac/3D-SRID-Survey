# 3D Skeleton Based Person Re-Identification (SRID)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

A professionally curated list of resources (papers, codes, data, etc.) on **3D Skeleton Based Person Re-ID (SRID)**.
It is collected and organized based on the [first comprehensive SRID survey](https://arxiv.org/pdf/2401.15296.pdf).

We will continuously update it with the latest resources. Should you find any missed resources (papers/codes) or errors, please feel free to open an issue or contribute a pull request.

For more papers and resources on Skeleton-Based Models (Action Recognition, Pose Estimation, etc.) from top-tier AI conferences and journals, kindly refer to [This Repo](https://github.com/Kali-Hac/Awesome-Skeleton-Based-Models).

## Survey Paper
[Recognizing Identities From Human Skeletons: A Survey on 3D Skeleton Based Person Re-Identification](https://arxiv.org/pdf/2401.15296.pdf)

By [Haocong Rao](https://scholar.google.com.sg/citations?user=JkT65uQAAAAJ&hl=zh-CN&oi=ao) and [Chunyan Miao](https://scholar.google.com.sg/citations?user=fmXGRJgAAAAJ&hl=zh-CN).

## Archives and Resources
<!-- vscode-markdown-toc -->
- [**Overview of SRID Task**](#Overview-of-SRID-Task)
- [**Taxonomy of SRID Research**](#Taxonomy-of-SRID-Research)
- [**Overview of Milestones in SRID**](#Overview-of-Milestones-in-SRID)
- [**Performance and Efficiency Comparison of State-of-the-Art Models**](#Performance-and-Efficiency-Comparison-of-State-of-the-Art-Models)
- [**Benchmark Datasets**](#benchmark-datasets)
- [**Studies by Different Categories**](#Studies-by-Different-Categories)
	- [**Hand-Crafted Modeling**](#Hand-Crafted-Modeling)
	- [**Sequence Based Modeling**](#Sequence-Based-Modeling)
	- [**Graph Based Modeling**](#Graph-Based-Modeling)
- [**Studies by Different Years**](#Studies-by-Different-Years)
	- [**2025**](#2025)
	- [**2024**](#2024)
	- [**2023**](#2023)
	- [**2022**](#2022)
	- [**2021**](#2021)
	- [**2020**](#2020)
	- [**2019**](#2019)
	- [**2018**](#2018)
	- [**2017**](#2017)
	- [**2016**](#2016)
	- [**2015**](#2015)
	- [**2014**](#2014)
	- [**Before 2014**](#before-2014)
- [**Leaderboard**](#leaderboard)


## Overview of SRID Task
**Overview of 3D skeleton based person re-ID (SRID) task with hand-crafted, sequence-based or graph-based modeling to learn effective body and motion features for identity recognition.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/Overview_task.jpg)


## Taxonomy of SRID Research
**Structure of this survey with the taxonomy of SRID research. Representative branches and SRID methods are listed.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/taxonomy_overview.jpg)

## Overview of Milestones in SRID
**Overview of research origin and technical advancements of SRID within the person re-ID community (Zoom in and follow the timeline for the best view).**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/SRID-Timeline.jpg)


## Performance and Efficiency Comparison of State-of-the-Art Models
**Parameter sizes (Millions), computational complexity (Giga Floating Point Operations (GFLOPs)), and KS20 Rank-1 accuracy of state-of-the-art deep learning based methods for SRID (Red: Sequence-based models; Green: Graph-based models).**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/model_comparison_fig.jpg)


<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## **Benchmark Datasets**
**Overview of SRID benchmark datasets. The number of skeletons in training is reported. “S” denotes single or egocentric view. RGB-estimated 3D and 2D skeleton datasets are listed. $^{\star}$ denotes an interdisciplinary benchmark for gait and disease prediction.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/Dataset_Overview.jpeg)


## **Studies by Different Categories**
**Property comparison of existing hand-crafted, sequence-based, and graph-based methods. Representative gait recognition methods using skeleton data are also compared. We report the parameter sizes (Million) and summarize their properties.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/Method_property_comparison.jpg)

### Hand-Crafted Modeling

- [Re-visiting k-Reciprocal Distance Re-ranking for Skeleton-Based Person Re-identification](https://ieeexplore.ieee.org/document/9913633) (_IEEE Signal Processing Letters 2022_)

- [Person Re-Identification from Different Views based on Dynamic Linear Combination of Distances](https://lilloa.univ-lille.fr/bitstream/handle/20.500.12210/57071/https:/halshs.archives-ouvertes.fr/halshs-03145152/document?sequence=1) (_Multimedia Tools and Applications 2021_) [[Github](https://github.com/Elaoud/re-id)] ![](https://img.shields.io/github/stars/Elaoud/re-id.svg?style=social)

- [Enhanced skeleton and face 3D data for person re-identification from depth cameras](https://doi.org/10.24963/ijcai.2020/125) (_Computers \& Graphics 2019_)

- [Cross-context analysis for long-term view-point invariant person re-identification via soft-biometrics using depth sensor](https://www.scitepress.org/papers/2018/66206/66206.pdf) (_VISIGRAPP 2018_)

- [Analysis of skeletal shape trajectories for person re-identifications](https://link.springer.com/chapter/10.1007/978-3-319-70353-4_12) (_International Conference on Advanced Concepts for Intelligent Vision Systems 2017_)

- [Human identification from freestyle walks using posture-based gait feature](https://ieeexplore.ieee.org/abstract/document/8007293) (_IEEE Transactions on Information Forensics and Security 2017_)

- [Long term person re-identification from depth cameras using facial and skeleton data](https://www.researchgate.net/profile/Stefano-Berretti/publication/325161671_Long_Term_Person_Re-identification_from_Depth_Cameras_Using_Facial_and_Skeleton_Data/links/5b84ffc892851c1e1236dd11/Long-Term-Person-Re-identification-from-Depth-Cameras-Using-Facial-and-Skeleton-Data.pdf) (_ICPR 2016_)


- [People re-identification using 3D descriptor with skeleton information](https://ieeexplore.ieee.org/abstract/document/7333986) (_International Conference on Informatics, Electronics \& Vision 2015_)

- [Multimodal person reidentification using RGB-D cameras](https://ieeexplore.ieee.org/abstract/document/7088601) (_IEEE Transactions on Circuits and Systems for Video Technology 2015_)

- [Person Identification Using Anthropometric and Gait Data from Kinect Sensor](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9680) (_AAAI 2015_)

- [One-Shot Person Re-identification with a Consumer Depth Camera](https://doi.org/10.1007/978-1-4471-6296-4\_8) (_Person Re-Identification 2014_)

- [3D reconstruction of freely moving persons for re-identification with a depth sensor](https://doi.org/10.24963/ijcai.2020/125) (_ICRA 2014_)

- [A feature-based approach to people re-identification using skeleton keypoints](https://www.researchgate.net/profile/Matteo-Munaro/publication/286624461_A_feature-based_approach_To_people_re-identification_using_skeleton_keypoints/links/566ea2f008ae1a797e406d8a/A-feature-based-approach-To-people-re-identification-using-skeleton-keypoints.pdf) (_ICRA 2014_)


### Sequence-Based Modeling

- [Person identification by walking gesture using skeleton sequences](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_18) (_Advanced Concepts for Intelligent Vision Systems 2020_)

- [Learning 3D spatiotemporal gait feature by convolutional network for person identification](https://www.sciencedirect.com/science/article/abs/pii/S0925231220302381) (_Neurocomputing 2020_)

- [A model-based gait recognition method with body pose and human prior knowledge](http://r.web.umkc.edu/rlyfv/papers/poseGait.pdf) (_Pattern Recognition 2020_) [[Github](https://github.com/RijunLiao/PoseGait)] ![](https://img.shields.io/github/stars/RijunLiao/PoseGait.svg?style=social) (PoseGait is extended for SRID in recent studies from 2021-2023)

- [Self-Supervised Gait Encoding with Locality-Aware Attention for Person Re-Identification](https://doi.org/10.24963/ijcai.2020/125) (_IJCAI 2020_) [[Github](https://github.com/Kali-Hac/SGE-LA)] ![](https://img.shields.io/github/stars/Kali-Hac/SGE-LA.svg?style=social)

- [A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification](https://arxiv.org/abs/2009.03671) (_IEEE Transactions on Pattern Analysis and Machine Intelligence 2021_) [[Github](https://github.com/Kali-Hac/Locality-Awareness-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/Locality-Awareness-SGE.svg?style=social)

- [Human Identification System Using 3D Skeleton-Based Gait Features and LSTM Model](https://www.sciencedirect.com/science/article/abs/pii/S1047320321002807) (_Journal of Visual Communication and Image Representation 2022_)

- [SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2022_) [[Github](https://github.com/Kali-Hac/SimMC)] ![](https://img.shields.io/github/stars/Kali-Hac/SimMC.svg?style=social)
  
- [Hierarchical Skeleton Meta-prototype Contrastive Learning with Hard Skeleton Mining for Unsupervised Person Re-identification](https://arxiv.org/pdf/2307.12917)  (_International Journal of Computer Vision 2024_) [[Github](https://github.com/Kali-Hac/Hi-MPC)] ![](https://img.shields.io/github/stars/Kali-Hac/Hi-MPC.svg?style=social)

### Graph-Based Modeling

- [SM-SGE: A Self-Supervised Multi-Scale Skeleton Graph Encoding Framework for Person Re-Identification](https://doi.org/10.1145/3474085.3475330) (_ACM MM 2021_) [[Github](https://github.com/Kali-Hac/SM-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/SM-SGE.svg?style=social)

- [Multi-Level Graph Encoding with Structural-Collaborative Relation Learning for Skeleton-Based Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2021_) [[Github](https://github.com/Kali-Hac/MG-SCR)] ![](https://img.shields.io/github/stars/Kali-Hac/MG-SCR.svg?style=social)

- [Skeleton Prototype Contrastive Learning with Multi-level Graph Relation Modeling for Unsupervised Person Re-identification](https://arxiv.org/pdf/2208.11814) (_Arxiv (Preprint) 2022_) [[Github](https://github.com/Kali-Hac/SPC-MGR)] ![](https://img.shields.io/github/stars/Kali-Hac/SPC-MGR.svg?style=social)

- [TranSG: Transformer-based Skeleton Graph Prototype Contrastive Learning with Structure-Trajectory Prompted Reconstruction for Person Re-identification](http://openaccess.thecvf.com/content/CVPR2023/papers/Rao_TranSG_Transformer-Based_Skeleton_Graph_Prototype_Contrastive_Learning_With_Structure-Trajectory_Prompted_CVPR_2023_paper.pdf) (_CVPR 2023_) [[Github](https://github.com/Kali-Hac/TranSG)] ![](https://img.shields.io/github/stars/Kali-Hac/TranSG.svg?style=social)

- [Motif Guided Graph Transformer with Combinatorial Skeleton Prototype Learning for Skeleton-Based Person Re-Identification](https://arxiv.org/pdf/2412.09044) (_AAAI 2025_) [[Github](https://github.com/Kali-Hac/MoCos)] ![](https://img.shields.io/github/stars/Kali-Hac/MoCos.svg?style=social)


## Studies by Different Years
### **2025**
- [Motif Guided Graph Transformer with Combinatorial Skeleton Prototype Learning for Skeleton-Based Person Re-Identification](https://arxiv.org/pdf/2412.09044) (_AAAI 2025_) [[Github](https://github.com/Kali-Hac/MoCos)] ![](https://img.shields.io/github/stars/Kali-Hac/MoCos.svg?style=social)

### **2024**
- [Hierarchical Skeleton Meta-prototype Contrastive Learning with Hard Skeleton Mining for Unsupervised Person Re-identification](https://arxiv.org/pdf/2307.12917)  (_International Journal of Computer Vision 2024_) [[Github](https://github.com/Kali-Hac/Hi-MPC)] ![](https://img.shields.io/github/stars/Kali-Hac/Hi-MPC.svg?style=social)

### **2023**
- [TranSG: Transformer-based Skeleton Graph Prototype Contrastive Learning with Structure-Trajectory Prompted Reconstruction for Person Re-identification](http://openaccess.thecvf.com/content/CVPR2023/papers/Rao_TranSG_Transformer-Based_Skeleton_Graph_Prototype_Contrastive_Learning_With_Structure-Trajectory_Prompted_CVPR_2023_paper.pdf) (_CVPR 2023_) [[Github](https://github.com/Kali-Hac/TranSG)] ![](https://img.shields.io/github/stars/Kali-Hac/TranSG.svg?style=social)


### **2022**
- [SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2022_) [[Github](https://github.com/Kali-Hac/SimMC)] ![](https://img.shields.io/github/stars/Kali-Hac/SimMC.svg?style=social)

- [Re-visiting k-Reciprocal Distance Re-ranking for Skeleton-Based Person Re-identification](https://ieeexplore.ieee.org/document/9913633) (_IEEE Signal Processing Letters 2022_)

- [Skeleton Prototype Contrastive Learning with Multi-level Graph Relation Modeling for Unsupervised Person Re-identification](https://arxiv.org/pdf/2208.11814) (_Arxiv (Preprint) 2022_) [[Github](https://github.com/Kali-Hac/SPC-MGR)] ![](https://img.shields.io/github/stars/Kali-Hac/SPC-MGR.svg?style=social)

- [Human Identification System Using 3D Skeleton-Based Gait Features and LSTM Model](https://www.sciencedirect.com/science/article/abs/pii/S1047320321002807) (_Journal of Visual Communication and Image Representation 2022_)

### **2021**
- [SM-SGE: A Self-Supervised Multi-Scale Skeleton Graph Encoding Framework for Person Re-Identification](https://doi.org/10.1145/3474085.3475330) (_ACM MM 2021_) [[Github](https://github.com/Kali-Hac/SM-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/SM-SGE.svg?style=social)

- [Multi-Level Graph Encoding with Structural-Collaborative Relation Learning for Skeleton-Based Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2021_) [[Github](https://github.com/Kali-Hac/MG-SCR)] ![](https://img.shields.io/github/stars/Kali-Hac/MG-SCR.svg?style=social)

- [A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification](https://arxiv.org/abs/2009.03671) (_IEEE Transactions on Pattern Analysis and Machine Intelligence 2021_) [[Github](https://github.com/Kali-Hac/Locality-Awareness-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/Locality-Awareness-SGE.svg?style=social)

- [Person Re-Identification from Different Views based on Dynamic Linear Combination of Distances](https://lilloa.univ-lille.fr/bitstream/handle/20.500.12210/57071/https:/halshs.archives-ouvertes.fr/halshs-03145152/document?sequence=1) (_Multimedia Tools and Applications 2021_) [[Github](https://github.com/Elaoud/re-id)] ![](https://img.shields.io/github/stars/Elaoud/re-id.svg?style=social)

### **2020**
- [Self-Supervised Gait Encoding with Locality-Aware Attention for Person Re-Identification](https://doi.org/10.24963/ijcai.2020/125) (_IJCAI 2020_) [[Github](https://github.com/Kali-Hac/SGE-LA)] ![](https://img.shields.io/github/stars/Kali-Hac/SGE-LA.svg?style=social)

<!--
- [Human skeleton mutual learning for person re-identification](https://doi.org/10.1016/j.neucom.2019.12.120) (_Neurocomputing 2020_)
-->

- [Learning 3D spatiotemporal gait feature by convolutional network for person identification](https://www.sciencedirect.com/science/article/abs/pii/S0925231220302381) (_Neurocomputing 2020_)

- [A model-based gait recognition method with body pose and human prior knowledge](http://r.web.umkc.edu/rlyfv/papers/poseGait.pdf) (_Pattern Recognition 2020_) [[Github](https://github.com/RijunLiao/PoseGait)] ![](https://img.shields.io/github/stars/RijunLiao/PoseGait.svg?style=social) (PoseGait is extended for SRID in recent studies from 2021-2023)

- [Person identification by walking gesture using skeleton sequences](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_18) (_Advanced Concepts for Intelligent Vision Systems 2020_)


### **2019**
<!-- 
- [SKEPRID: Pose and Illumination Change-Resistant Skeleton-Based Person Re-Identification](https://dl.acm.org/doi/pdf/10.1145/3243217) (_ACM Transactions on Multimedia Computing, Communications, and Applications 2019_)
-->

- [Enhanced skeleton and face 3D data for person re-identification from depth cameras](https://doi.org/10.24963/ijcai.2020/125) (_Computers\&Graphics 2019_)

### **2018**
- [Cross-context analysis for long-term view-point invariant person re-identification via soft-biometrics using depth sensor](https://www.scitepress.org/papers/2018/66206/66206.pdf) (_VISIGRAPP 2018_)

### **2017**
- [Human identification from freestyle walks using posture-based gait feature](https://ieeexplore.ieee.org/abstract/document/8007293) (_IEEE Transactions on Information Forensics and Security 2017_)

- [Context-aware person re-identification in the wild via fusion of gait and anthropometric features](https://vislab.isr.tecnico.ulisboa.pt/wp-content/uploads/2017/05/anambiar_BWild2017.pdf) (_International Conference on Automatic Face \& Gesture Recognition 2017_)

### **2016**
- [Long term person re-identification from depth cameras using facial and skeleton data](https://www.researchgate.net/profile/Stefano-Berretti/publication/325161671_Long_Term_Person_Re-identification_from_Depth_Cameras_Using_Facial_and_Skeleton_Data/links/5b84ffc892851c1e1236dd11/Long-Term-Person-Re-identification-from-Depth-Cameras-Using-Facial-and-Skeleton-Data.pdf) (_ICPR 2016_)

### **2015**
- [Person Identification Using Anthropometric and Gait Data from Kinect Sensor](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9680) (_AAAI 2015_)

- [People re-identification using 3D descriptor with skeleton information](https://ieeexplore.ieee.org/abstract/document/7333986) (_International Conference on Informatics, Electronics \& Vision 2015_)

- [Multimodal person reidentification using RGB-D cameras](https://ieeexplore.ieee.org/abstract/document/7088601) (_IEEE Transactions on Circuits and Systems for Video Technology 2015_)

### **2014**
- [3D reconstruction of freely moving persons for re-identification with a depth sensor](https://doi.org/10.24963/ijcai.2020/125) (_ICRA 2014_)

- [A feature-based approach to people re-identification using skeleton keypoints](https://www.researchgate.net/profile/Matteo-Munaro/publication/286624461_A_feature-based_approach_To_people_re-identification_using_skeleton_keypoints/links/566ea2f008ae1a797e406d8a/A-feature-based-approach-To-people-re-identification-using-skeleton-keypoints.pdf) (_ICRA 2014_)

- [One-Shot Person Re-identification with a Consumer Depth Camera](https://doi.org/10.1007/978-1-4471-6296-4\_8) (_Person Re-Identification 2014_)
  
### Before 2014
- [Re-identification with RGB-D Sensors](https://doi.org/10.1007/978-3-642-33863-2\_43) (_ECCV Workshop 2012_)


##  **Leaderboard**
**Performance comparison of existing hand-crafted, sequence-based, and graph-based methods on different benchmark datasets (BIWI (S/W), IAS-Lab (A/B), KS20). Representative gait recognition methods using skeleton data are also compared following the same person re-ID evaluation protocol.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/Leaderboard.jpg)

## **Prospects**
**Interdisciplinary application landscape of SRID across three primary domains: healthcare (green box), embodied AI (yellow box), and security (purple box). Please zoom in for better view.**

![image](https://github.com/Kali-Hac/3D-SRID-Survey/blob/main/overview/Prospects.jpg)

## Citation
If you found this paper/repository useful, please consider citing:
```bash
@article{rao2026survey,
  title={A Survey on 3D Skeleton Based Person Re-Identification: Taxonomy, Advances, Challenges, and Interdisciplinary Prospects},
  author={Rao, Haocong and Miao, Chunyan},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2026}
}
```
