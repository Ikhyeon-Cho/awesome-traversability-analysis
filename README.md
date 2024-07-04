# Awesome Traversability Analysis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome **terrain classification**, **traversability analysis** papers and codes for robotic navigation in the real-world 😎

<div align="center">
<strong>Last update: June, 2024 </strong>
<br>
<br>
Any PRs are welcome!

</div>

<div align="left">
</div>

<br>
<br>

**2024.05.17**  - Updated ICRA 2024 papers :) <br>
**2023.10.05**  - Updated IROS 2023 papers :) <br>

## Table of Contents
- [Survey papers](#survey-papers)
- [Awesome papers list](#awesome-papers-list)
  - [2023 - 2024 papers](#2023---2024-papers)
  - [Geometry-based](#geometry-based-approaches)
  - [Appearance-based](#appearance-based-approaches)
  - [Proprioception-based](#proprioception-based-approaches)
  - [Hybrid approaches](#hybrid-approaches)
  - [Terrain-aware Navigation](#terrain-aware-navigation)
- [Public Datasets](#public-datasets)
- [Libraries & Implementations]()


<br>

## Survey papers
- [Terrain traversability analysis methods for unmanned ground vehicles: A survey](https://www.sciencedirect.com/science/article/pii/S095219761300016X), Papadakis et al., Engineering Applications of Artificial Intelligence 2013 | [bibtex](./terrain_traversability_analysis.bib#L3-L12)

- [A Survey on Terrain Traversability Analysis for Autonomous Ground Vehicles: Methods, Sensors, and Challenges](https://www.journalfieldrobotics.org/Field_Robotics/Volume_2_files/Vol2_49.pdf), Borges et al., Journal of Field Robotics 2022 | [bibtex](./terrain_traversability_analysis.bib#L14-L22)

- [Learning-Based Methods of Perception and Navigation for Ground Vehicles in Unstructured Environments: A Review](https://www.mdpi.com/1424-8220/21/1/73), Guastella et al., Sensors 2020 | [bibtex](./terrain_traversability_analysis.bib#L24-L33)

- [A Survey of Traversability Estimation for Mobile Robots](https://ieeexplore.ieee.org/abstract/document/9869644), Sevastopoulos et al., IEEE Access 2022 | [arXiv](https://arxiv.org/abs/2204.10883)  | [bibtex](./terrain_traversability_analysis.bib#L35-L43)

- [Survey on Datasets for Perception in Unstructured Outdoor Environments](https://arxiv.org/html/2404.18750v1), Mortimer et al., Arxiv 2024 | [arXiv](https://arxiv.org/html/2404.18750v1)  | [bibtex](./terrain_traversability_analysis.bib#L45-L50)

<br>

## Awesome papers list

### 2023 - 2024 Papers

- [Pronav: Proprioceptive traversability estimation for legged robot navigation in outdoor environments](https://ieeexplore.ieee.org/abstract/document/10569052), Elnoor et al., RA-L 2024 | [arXiv](https://arxiv.org/abs/2307.09754)  | [bibtex](./traversability-papers-2023-2024.bib#L1-L7)

- [Evidential Semantic Mapping in Off-road Environments with Uncertainty-aware Bayesian Kernel Inference](https://arxiv.org/abs/2403.14138), Kim et al., arXiv 2024, | [arXiv](https://arxiv.org/abs/2403.14138)  | [bibtex](./traversability-papers-2023-2024.bib#L39-L44)

- [Learning Self-Supervised Traversability With Navigation Experiences of Mobile Robots: A Risk-Aware Self-Training Approach](https://ieeexplore.ieee.org/document/10468651), Cho et al., RA-L 2024| [bibtex](./traversability-papers-2023-2024.bib#L9-L15) | [Github](https://github.com/Ikhyeon-Cho/LeSTA) 

- [Robot-Dependent Traversability Estimation for Outdoor Environments using Deep Multimodal Variational Autoencoders](https://graz.elsevierpure.com/en/publications/robot-dependent-traversability-estimation-for-outdoor-environment), Eder et al., ICRA 2024 | [bibtex](./traversability-papers-2023-2024.bib#L17-L23)

- [Transformer-based Traversability Analysis for Autonomous Navigation in Outdoor Environments with Water Hazard](https://ieeexplore.ieee.org/abstract/document/10574380), Xu et al., T-IV 2024  | [bibtex](./traversability-papers-2023-2024.bib#L52-L58)

- [Learning-based Traversability Costmap for Autonomous Off-road Navigation](https://arxiv.org/abs/2406.08187), Zhu et al., arXiv 2024 | [arXiv](https://arxiv.org/abs/2406.08187)  | [bibtex](./traversability-papers-2023-2024.bib#L25-L30)

- [Learning Semantic Traversability with Egocentric Video and Automated Annotation Strategy](https://arxiv.org/abs/2406.02989), Kim et al., arXiv 2024 | [arXiv](https://arxiv.org/abs/2406.02989)  | [bibtex](./traversability-papers-2023-2024.bib#L32-L37)

- [TE-NeXt: A LiDAR-Based 3D Sparse Convolutional Network for Traversability Estimation](https://arxiv.org/abs/2406.01395), Santo et al., arXiv 2024 | [arXiv](https://arxiv.org/abs/2406.01395)  | [bibtex](./traversability-papers-2023-2024.bib#L46-L51)

- [History-Aware Planning for Risk-free Autonomous Navigation on Unknown Uneven Terrain](https://arxiv.org/abs/2406.01928), Wang et al., arXiv 2024 | [arXiv](https://arxiv.org/abs/2406.01928)  | [bibtex](./traversability-papers-2023-2024.bib#L53-L58)

- [Follow the Footprints: Self-supervised Traversability Estimation for Off-road Vehicle Navigation based on Geometric and Visual Cues](), Jeon et al., ICRA 2024 | [arXiv](https://arxiv.org/abs/2402.15363)  | [bibtex](./traversability-papers-2023-2024.bib#L60-L65) | [Github](https://github.com/yurimjeon1892/FtFoot)

- [Uncertainty-Aware Trajectory Planning: Using Uncertainty Quantification and Propagation in Traversability Prediction of Planetary Rovers](https://ieeexplore.ieee.org/abstract/document/10378974?casa_token=QUFregPS2CAAAAAA:GTJmw2awBTABxuh7CslF_pAOJE3feoxcKFcCSldDEUE8grrZToZjc_YIzc9zmfAbVqF1jd83), Takemura et al., RA-M 2024 | [bibtex](./traversability-papers-2023-2024.bib#L101-L107) 

- [V-STRONG: Visual Self-Supervised Traversability Learning for Off-road Navigation](), Jung et al., ICRA 2024  | [arXiv](https://arxiv.org/abs/2312.16016) | [bibtex](./traversability-papers-2023-2024.bib#L116-L121)

- [Probabilistic Traversability Model for Risk-Aware Motion Planning in Off-Road Environments](https://ieeexplore.ieee.org/abstract/document/10341350?casa_token=_DR0F3T-v2AAAAAA:5y33BO40ZgI59d21sLqW25-Xk6-XIo4fzkQhJHq4ebyRJUSm8ThI21VISBTkbcGOjDLj84eY), Cai et al., IROS 2023 | [arXiv](https://arxiv.org/abs/2210.00153) | [bibtex](./traversability-papers-2023-2024.bib#L67-L74) | [Github](https://github.com/mit-acl/mppi_numba)

- [Circular Accessible Depth: A Robust Traversability Representation for UGV Navigation](https://ieeexplore.ieee.org/abstract/document/10242384?casa_token=IxbQHcdGZioAAAAA:ICLEZ3BSFtW6pKGwTvchfKr8mhFo4fZMS6TBi8LJyWuStiIdBB6hNwvY-tUh8o9z2qJtfcRY), Xie et al., T-RO 2023 | [arXiv](https://arxiv.org/abs/2212.13676) | [bibtex](./traversability-papers-2023-2024.bib#L76-L82)

- [GrASPE: Graph Based Multimodal Fusion for Robot Navigation in Outdoor Environments](https://ieeexplore.ieee.org/abstract/document/10265189?casa_token=kt9H3AlDQ_wAAAAA:tP4LsqK02sclr959Z9IVbtqfG8MlkVUo0WlE5hHo2giIiNI9GiGjYZhTkj03JiqEFbWs7o9H), Weerakoon et al., RA-L 2023 | [arXiv](https://arxiv.org/abs/2209.05722) | [bibtex](./traversability-papers-2023-2024.bib#L84-L90)

- [Real-Time Elevation Mapping with Bayesian Ground Filling and Traversability Analysis for UGV Navigation](https://ieeexplore.ieee.org/abstract/document/10341662?casa_token=ACydI9DcFX4AAAAA:sYnlUnIsaUrz4Gwc4FOUd3nsoEP3VyFCaUPn2HgcE9czIm7Ns5FSodLLksV2_c7oJHw_P2tu), Xie et al., IROS 2023 | [bibtex](./traversability-papers-2023-2024.bib#L92-L99)

- [Fast Traversability Estimation for Wild Visual Navigation](https://www.roboticsproceedings.org/rss19/p054.html), Frey et al., RSS 2023  | [arXiv](https://arxiv.org/abs/2305.08510) | [bibtex](./traversability-papers-2023-2024.bib#L109-L114) | [Github](https://github.com/leggedrobotics/wild_visual_navigation)

- [MTG: Mapless Trajectory Generator with Traversability Coverage for Outdoor Navigation](), Liang et al., ICRA 2024 | [arXiv](https://arxiv.org/abs/2309.08214) | [bibtex](./traversability-papers-2023-2024.bib#L123-L128)

- [STAGE: Scalable and Traversability-Aware Graph Based Exploration Planner for Dynamically Varying Environments](), Patel et al., ICRA 2024 | [arXiv](https://arxiv.org/abs/2402.02566) | [bibtex](./traversability-papers-2023-2024.bib#L130-L135)

- [WayFASTER: A Self-Supervised Traversability Prediction for Increased Navigation Awareness](), Gasparino et al., ICRA 2024 | [arXiv](https://arxiv.org/abs/2402.00683) | [bibtex](./traversability-papers-2023-2024.bib#L137-L142) | [Github](https://github.com/matval/wayfaster)

- [Gaussian Process-Based Traversability Analysis for Terrain Mapless Navigation](), Leininger et al., ICRA 2024 | [arXiv](https://arxiv.org/abs/2403.19010) | [bibtex](./traversability-papers-2023-2024.bib#L144-L149) | [Github](https://github.com/abeleinin/gp-navigation)

- [A Framework for Real-Time Generation of Multi-Directional Traversability Maps in Unstructured Environments](), Huang et al., ICRA 2024

- [DreamWaQ: Learning Robust Quadrupedal Locomotion With Implicit Terrain Imagination via Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10161144?casa_token=EvUJUsgt1Y0AAAAA:mYMnFawkhoo6BwtSwMse83yucZa9cfkafze3NBF7xClfpLuco7dOfsIbKGQpUD8_hjxfOC7I), Nahrendra et al., ICRA 2023 | [arXiv](https://arxiv.org/abs/2301.10602) | [bibtex](./traversability-papers-2023-2024.bib#L151-L158)

- [Learning Off-Road Terrain Traversability With Self-Supervisions Only](https://ieeexplore.ieee.org/abstract/document/10146445?casa_token=wz4aKxIS5lUAAAAA:jStUgDTsD0VXUVRoKdZ_d9mZTm6iY0__P5gFfYGRxv3HkSU5SlipvQXgJxuvEsK0Tmsj458l), Seo et al., RA-L 2023 | [arXiv](https://arxiv.org/abs/2301.10602) | [bibtex](./traversability-papers-2023-2024.bib#L211-L220)

- [Risk-aware Path Planning via Probabilistic Fusion of Traversability Prediction for Planetary Rovers on Heterogeneous Terrains](https://ieeexplore.ieee.org/abstract/document/10161466?casa_token=Qw8Dk13W4kAAAAAA:d0ocGm37-Jbx4zdVCzhaI_SQbzudnAGqNRpiKF7BvS-3sD3iIx2_42uRc41f9p1v8Z5zHcg8), Endo et al., ICRA 2023 | [arXiv](https://arxiv.org/abs/2303.01169) | [bibtex](./traversability-papers-2023-2024.bib#L160-L167)

- [ScaTE: A Scalable Framework for Self- Supervised Traversability Estimation in Unstructured Environments](https://ieeexplore.ieee.org/abstract/document/10007922?casa_token=LDTK7EHAnaoAAAAA:DneyLRdeeFsGb7RYUbt5Myk1y5wMNx10bU93nEFm077n1cl1AY_T0dEGJIFhSRMEOjVUmFoc), Seo et al., RA-L 2023 | [arXiv](https://arxiv.org/abs/2209.06522) | [bibtex](./traversability-papers-2023-2024.bib#L169-L178)

- [Uncertainty Estimation for Planetary Robotic Terrain Segmentation](https://ieeexplore.ieee.org/abstract/document/10115611?casa_token=w8Ww6Ef-B0kAAAAA:LKhXXITxgsQmGRj7BC4YLcTSxiWa1esdt-t7tI9m9VVYTQldeepQlONKV9YhgbRAYoBzhQ3I), Muller et al., IEEE Aerospace Conference 2023 | [bibtex](./traversability-papers-2023-2024.bib#L180-L187)

- [State estimation and traversability map construction method of a quadruped robot on soft uneven terrain](https://onlinelibrary.wiley.com/doi/full/10.1002/rob.22175?casa_token=aoOT613YePkAAAAA%3AkvB-RApTpMVfCgdE5JTDg0UA_V4szcEuIKclXNXQFLVaEF4jSEsiT4harnVcyTPjjTWU89qDHqXMvw), Kang et al., Journal of Field Robotics 2023 | [bibtex](./traversability-papers-2023-2024.bib#L189-L198)

- [Traversability analysis for autonomous driving in complex environment: A LiDAR‐based terrain modeling approach](https://onlinelibrary.wiley.com/doi/full/10.1002/rob.22209?casa_token=9DInOLAdh2cAAAAA%3AcCts1biu5XgTKBzMrq0ISIJAkYd8X65uA4GHwoaoGAuHD8KY8N0IZQ1aAnvQnNYp_J6YfoY3H3sZiw), Xue et al., Journal of Field Robotics 2023 | [arXiv](https://arxiv.org/abs/2307.02060) | [bibtex](./traversability-papers-2023-2024.bib#L200-L209)

- [Terrain Classification Enhanced with Uncertainty for Space Exploration Robots from Proprioceptive Data](), Alvarez et al., LXAI @ ICML 2023 Regular Deadline Poster | [arXiv](https://arxiv.org/abs/2407.03241) | [bibtex](./traversability-papers-2023-2024.bib#L222-L226)

<br>

### Geometry-based approaches
<details open>
<summary>Representation Learning </summary>

- Real-Time Neural Dense Elevation Mapping for Urban Terrain With Uncertainty Estimations

- Neural Scene Representation for Locomotion on Structured Terrain

- Reconstructing Occluded Elevation Information in Terrain Maps With Self-Supervised Learning

- Learning-aided 3-D occupancy mapping with Bayesian generalized kernel inference

- Bayesian generalized kernel inference for terrain traversability mapping



</details>

<details open>
<summary>Uncertainty & risk estimation</summary>

- Probabilistic Traversability Model for Risk-Aware Motion Planning in Off-Road Environments

- Active Traversability Learning via Risk-Aware Information Gathering for Planetary Exploration Rovers

- These Maps are Made for Walking: Real-Time Terrain Property Estimation for Mobile Robots

- STEP: Stochastic Traversability Evaluation and Planning for Risk-Aware Off-road Navigation

- Probabilistic Terrain Mapping for Mobile Robots With Uncertain Localization



</details>

<details open>
<summary>Learning from demonstration</summary>

- Locomotion Policy Guided Traversability Learning using Volumetric Representations of Complex Environments

- A Self-Training Approach-Based Traversability Analysis for Mobile Robots in Urban Environments

- Adaptive Terrain Traversability Prediction based on Multi-Source Transfer Gaussian Processes

- ForestTrav: 3D LiDAR-Only Forest Traversability Estimation for Autonomous Ground Vehicles

- Forest Traversability Mapping (FTM): Traversability estimation using 3D voxel-based Normal Distributed Transform to enable forest navigation

- Learning Ground Traversability From Simulations

- Traversability Analysis for Mobile Robots in Outdoor Environments: A Semi-Supervised Learning Approach Based on 3D-Lidar Data

- Terrain Classification in Complex Three‐dimensional Outdoor Environments


</details>

<br>

### Appearance-based approaches
<details open>
<summary>Image segmentation </summary>

- GA-Nav: Efficient Terrain Segmentation for Robot Navigation in Unstructured Outdoor Environments

- TerraPN: Unstructured Terrain Navigation using Online Self-Supervised Learning

- Mars Terrain Segmentation with Less Labels

- Regressed Terrain Traversability Cost for Autonomous Navigation Based on Image Textures

- Learning terrain segmentation with classifier ensembles for autonomous robot navigation in unstructured environments

</details>

<details open>
<summary>Learning from demonstration</summary>

- Self-Supervised Traversability Prediction by Learning to Reconstruct Safe Terrain

- Safe Robot Navigation via Multi-Modal Anomaly Detection

- Where Should I Walk? Predicting Terrain Properties From Images Via Self-Supervised Learning

- GONet: A Semi-Supervised Deep Learning Approach For Traversability Estimation

- Find your own way: Weakly-supervised segmentation of path proposals for urban autonomy

</details>

<br>

### Proprioception-based approaches

- Multiclass Terrain Classification using Sound and Vibration from Mobile Robot Terrain Interaction

<br>

### Hybrid approaches

- TNS: Terrain Traversability Mapping and Navigation System for Autonomous Excavators

- Self-Supervised Visual Terrain Classification From Unsupervised Acoustic Feature Learning

- How Does It Feel? Self-Supervised Costmap Learning for Off-Road Vehicle Traversability

- How Rough Is the Path? Terrain Traversability Estimation for Local and Global Path Planning

- An Hybrid Approach to Improve the Performance of Encoder-Decoder Architectures for Traversability Analysis in Urban Environments

- Geometric and Visual Terrain Classification for Autonomous Mobile Navigation

- Terrain Classification in Complex Three‐dimensional Outdoor Environments

<br>

### Terrain-aware Navigation

<details open>
<summary>Reinforcement Learning </summary>

- BADGR: An Autonomous Self-Supervised Learning-Based Navigation System

- A Sim-to-Real Pipeline for Deep Reinforcement Learning for Autonomous Robot Navigation in Cluttered Rough Terrain

- TERP: Reliable Planning in Uneven Outdoor Environments using Deep Reinforcement Learning


</details>

<details open>
<summary>Traditional Planning & control </summary>

- Exploration of 3D terrains using potential fields with elevation-based local distortions

- Long-Term Robot Navigation in Indoor Environments Estimating Patterns in Traversability Changes

- Perceptive Locomotion in Rough Terrain – Online Foothold Optimization

- Driving on Point Clouds: Motion Planning, Trajectory Optimization, and Terrain Assessment in Generic Nonplanar Environments

- Navigation Planning for Legged Robots in Challenging Terrain

- Fuzzy Based Traversability Analysis for a Mobile Robot on Rough Terrain

</details>

<br>

## Public Datasets

### Structured urban environments

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)



### Unstructured terrains

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173)
