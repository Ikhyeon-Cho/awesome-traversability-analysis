<div align="center">

# Awesome Traversability Analysis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome **terrain classification**, **traversability analysis** papers and codes for robotic navigation in the real-world 😎


<strong>Last update: June, 2024 </strong>
<br>
<br>
Keep updating... Any PRs are welcome! 😃

----
</div>

<div align="left">
</div>

### Notice
**2024.05.17**  - Updated **ICRA 2024** papers <br>
**2023.10.05**  - Updated **IROS 2023** papers <br>
<br>

> Type 'GitHub' in the search bar for finding open-sourced projects 

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

- [Learning Self-Supervised Traversability With Navigation Experiences of Mobile Robots: A Risk-Aware Self-Training Approach](https://ieeexplore.ieee.org/document/10468651), Cho et al., RA-L 2024| [bibtex](./traversability-papers-2023-2024.bib#L9-L15) | [Github](https://github.com/Ikhyeon-Cho/LeSTA)


- [Robot-Dependent Traversability Estimation for Outdoor Environments using Deep Multimodal Variational Autoencoders](https://graz.elsevierpure.com/en/publications/robot-dependent-traversability-estimation-for-outdoor-environment), Eder et al., ICRA 2024 | [bibtex](./traversability-papers-2023-2024.bib#L17-L23)

- [Transformer-based Traversability Analysis for Autonomous Navigation in Outdoor Environments with Water Hazard](https://ieeexplore.ieee.org/abstract/document/10574380), Xu et al., T-IV 2024  | [bibtex](./traversability-papers-2023-2024.bib#L52-L58)

- [Evidential Semantic Mapping in Off-road Environments with Uncertainty-aware Bayesian Kernel Inference](https://arxiv.org/abs/2403.14138), Kim et al., arXiv 2024, | [arXiv](https://arxiv.org/abs/2403.14138)  | [bibtex](./traversability-papers-2023-2024.bib#L39-L44)

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

- [Traversability-aware Adaptive Optimization for Path Planning and Control in Mountainous Terrain](https://ieeexplore.ieee.org/abstract/document/10496162/), Yoo et al., RA-L 2024 | [arXiv](https://arxiv.org/abs/2404.03274) | [bibtex](./traversability-papers-2023-2024.bib#L228-234)

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
<summary>Dense Terrain Modeling </summary>

- [Probabilistic Terrain Mapping for Mobile Robots With Uncertain Localization](https://ieeexplore.ieee.org/document/8392399), Fankhauser et al., RA-L 2018 | [bibtex](./terrain_traversability_analysis.bib#L60-L69) | [Github](https://github.com/ANYbotics/elevation_mapping)

- [OctoMap: An efficient probabilistic 3D mapping framework based on octrees](https://link.springer.com/article/10.1007/s10514-012-9321-0), Hornung et al., Autonomous Robots 2013 | [bibtex](./terrain_traversability_analysis.bib#L71-L79) | [Github](https://github.com/OctoMap/octomap)

- [Voxblox: Incremental 3D Euclidean Signed Distance Fields for On-Board MAV Planning](https://ieeexplore.ieee.org/abstract/document/8202315), Oleynikova et al., IROS 2017 | [arXiv](https://arxiv.org/abs/1611.03631) | [bibtex](./terrain_traversability_analysis.bib#L81-L88) | [Github](https://github.com/ethz-asl/voxblox)

</details>

<details open>
<summary>Terrain Representation Learning </summary>

- [Occupancy Networks: Learning 3D Reconstruction in Function Space](https://openaccess.thecvf.com/content_CVPR_2019/html/Mescheder_Occupancy_Networks_Learning_3D_Reconstruction_in_Function_Space_CVPR_2019_paper.html), Mescheder et al., CVPR 2019 | [arXiv](https://arxiv.org/abs/1812.03828) | [bibtex](./terrain_traversability_analysis.bib#L90-L96) | [Github](https://github.com/autonomousvision/occupancy_networks)

- [Learning-aided 3-D occupancy mapping with Bayesian generalized kernel inference](https://ieeexplore.ieee.org/abstract/document/8713569), Doherty et al., T-RO 2019 | [bibtex](./terrain_traversability_analysis.bib#L98-L107) | [Github](https://github.com/RobustFieldAutonomyLab/la3dm)

- [DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation](http://openaccess.thecvf.com/content_CVPR_2019/html/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.html), Part et al., CVPR 2019 | [arXiv](https://arxiv.org/abs/1901.05103) | [bibtex](./terrain_traversability_analysis.bib#L109-L115) | [Github](https://github.com/facebookresearch/DeepSDF)

- [Real-Time Neural Dense Elevation Mapping for Urban Terrain With Uncertainty Estimations](https://ieeexplore.ieee.org/abstract/document/9992063/), Yang et al., RA-L 2022 | [arXiv](https://arxiv.org/abs/2208.03467) | [bibtex](./terrain_traversability_analysis.bib#L117-L126)

- [Neural Scene Representation for Locomotion on Structured Terrain](https://ieeexplore.ieee.org/abstract/document/9801620/), Hoeller et al., RA-L 2022 | [arXiv](https://arxiv.org/abs/2206.08077) | [bibtex](./terrain_traversability_analysis.bib#L128-L137)

- [Reconstructing Occluded Elevation Information in Terrain Maps With Self-Supervised Learning](https://ieeexplore.ieee.org/abstract/document/9676411/), Stolzle et al., RA-L 2022 | [arXiv](https://arxiv.org/abs/2109.07150) | [bibtex](./terrain_traversability_analysis.bib#L139-L148) | [Github](https://github.com/mstoelzle/solving-occlusion)

- [Bayesian generalized kernel inference for terrain traversability mapping](http://proceedings.mlr.press/v87/shan18a.html), Shan et al., CoRL 2018 | [arXiv](https://arxiv.org/abs/2301.00523) | [bibtex](./terrain_traversability_analysis.bib#L150-L157) | [Github](https://github.com/TixiaoShan/BGK_traversability_mapping)

- [RoadBEV: Road Surface Reconstruction in Bird’s Eye View](), Zhao et al., arXiv 2024 | [arXiv](https://arxiv.org/abs/2404.06605) | [bibtex](./terrain_traversability_analysis.bib#L159-L164) | [Github](https://github.com/ztsrxh/RoadBEV)

</details>

<details open>
<summary>Uncertainty & risk estimation</summary>

- [Active Traversability Learning via Risk-Aware Information Gathering for Planetary Exploration Rovers](https://ieeexplore.ieee.org/abstract/document/9894664/), Endo et al., RA-L 2022 | [bibtex](./terrain_traversability_analysis.bib#L166-L175)

- [EVORA: Deep Evidential Traversability Learning for Risk-Aware Off-Road Autonomy](), Cai et al., arXiv 2023 | [arXiv](https://arxiv.org/abs/2311.06234) | [bibtex](./terrain_traversability_analysis.bib#L177-L182)

- [These Maps are Made for Walking: Real-Time Terrain Property Estimation for Mobile Robots](https://ieeexplore.ieee.org/abstract/document/9792203/), Ewen et al., RA-L 2022 | [arXiv](https://arxiv.org/abs/2205.12925) | [bibtex](./terrain_traversability_analysis.bib#L184-L193) | [Github](https://github.com/roahmlab/sel_map)

- [STEP: Stochastic Traversability Evaluation and Planning for Risk-Aware Off-road Navigation](https://www.roboticsproceedings.org/rss17/p021.html), Fan et al., RSS 2021 | [arXiv](https://arxiv.org/abs/2103.02828) | [bibtex](./terrain_traversability_analysis.bib#L195-L203)



</details>


<details open>
<summary>Learning from demonstration</summary>

- [Locomotion Policy Guided Traversability Learning using Volumetric Representations of Complex Environments](https://ieeexplore.ieee.org/abstract/document/9982190/), Frey et al., IROS 2022 | [arXiv](https://arxiv.org/abs/2203.15854) | [bibtex](./terrain_traversability_analysis.bib#L205-L212)

- [A Self-Training Approach-Based Traversability Analysis for Mobile Robots in Urban Environments](https://ieeexplore.ieee.org/abstract/document/9561394/), Lee et al., ICRA 2021 | [bibtex](./terrain_traversability_analysis.bib#L214-L221)

- [Adaptive Terrain Traversability Prediction based on Multi-Source Transfer Gaussian Processes](https://ieeexplore.ieee.org/abstract/document/9636528/), Inotsume et al., IROS 2021 | [bibtex](./terrain_traversability_analysis.bib#L223-L230)

- [ForestTrav: 3D LiDAR-Only Forest Traversability Estimation for Autonomous Ground Vehicles](https://ieeexplore.ieee.org/abstract/document/10458917/), Ruetz et al., IEEE Access 2024 | [arXiv](https://arxiv.org/abs/2305.12705) | [bibtex](./terrain_traversability_analysis.bib#L232-L238)

- [Forest Traversability Mapping (FTM): Traversability estimation using 3D voxel-based Normal Distributed Transform to enable forest navigation](https://ieeexplore.ieee.org/abstract/document/9981401/), Ruetz et al., IROS 2022 | [bibtex](./terrain_traversability_analysis.bib#L240-L247)

- [Learning Ground Traversability From Simulations](https://ieeexplore.ieee.org/abstract/document/8280544/), Chavez et al., RA-L 2018 | [arXiv](https://arxiv.org/abs/1709.05368) | [bibtex](./terrain_traversability_analysis.bib#L249-L258) | [Github](https://github.com/romarcg/traversability_estimation)

- [Traversability Analysis for Mobile Robots in Outdoor Environments: A Semi-Supervised Learning Approach Based on 3D-Lidar Data](https://ieeexplore.ieee.org/abstract/document/7139749/), Suger et al., ICRA 2015 | [bibtex](./terrain_traversability_analysis.bib#L260-L267)

- [Terrain Classification in Complex Three‐dimensional Outdoor Environments](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.21521), Santamaria et al., Journal of Field Robotics 2015 | [bibtex](./terrain_traversability_analysis.bib#L269-L278)


</details>

<br>

### Appearance-based approaches
<details open>
<summary>Image segmentation </summary>

- [GA-Nav: Efficient Terrain Segmentation for Robot Navigation in Unstructured Outdoor Environments](https://ieeexplore.ieee.org/abstract/document/9810192/), Guan et al., RA-L 2022 | [arXiv](https://arxiv.org/abs/2103.04233) | [bibtex](./terrain_traversability_analysis.bib#L280-L289) | [Github](https://github.com/rayguan97/GANav-offroad)

- [TerraPN: Unstructured Terrain Navigation using Online Self-Supervised Learning](https://ieeexplore.ieee.org/abstract/document/9981942/), Sathyamoorthy et al., IROS 2022 | [arXiv](https://arxiv.org/abs/2202.12873) | [bibtex](./terrain_traversability_analysis.bib#L291-L298) | [Github](https://github.com/AdarshJS/terrapn)

- [Mars Terrain Segmentation with Less Labels](https://ieeexplore.ieee.org/abstract/document/9843245/), Goh et al., AERO 2022 | [arXiv](https://arxiv.org/abs/2202.00791) | [bibtex](./terrain_traversability_analysis.bib#L300-L307)

- [Regressed Terrain Traversability Cost for Autonomous Navigation Based on Image Textures](https://www.mdpi.com/2076-3417/10/4/1195), Bekhti et al., Applied Sciences 2020 | [bibtex](./terrain_traversability_analysis.bib#L309-L318)

- [Learning terrain segmentation with classifier ensembles for autonomous robot navigation in unstructured environments](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.20279), Procopio et al., Journal of Field Robotics 2009 | [bibtex](./terrain_traversability_analysis.bib#L320-L329)

</details>

<details open>
<summary>Learning from demonstration</summary>

- [Self-Supervised Traversability Prediction by Learning to Reconstruct Safe Terrain](https://ieeexplore.ieee.org/abstract/document/9981368/), Schmid et al., IROS 2022 | [arXiv](https://arxiv.org/abs/2208.01329) | [bibtex](./terrain_traversability_analysis.bib#L331-L338)

- [Safe Robot Navigation via Multi-Modal Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/8963641/), Wellhausen et al., RA-L 2020 | [arXiv](https://arxiv.org/abs/2001.07934) | [bibtex](./terrain_traversability_analysis.bib#L340-L349) | [Github](https://github.com/leggedrobotics/anomaly_navigation)

- [Where Should I Walk? Predicting Terrain Properties From Images Via Self-Supervised Learning](https://ieeexplore.ieee.org/abstract/document/8627373/), Wellhausen et al., RA-L 2019 | [bibtex](./terrain_traversability_analysis.bib#L351-L360)

- [GONet: A Semi-Supervised Deep Learning Approach For Traversability Estimation](https://ieeexplore.ieee.org/abstract/document/8594031/), Hirose et al., IROS 2018 | [arXiv](https://arxiv.org/abs/1803.03254) | [bibtex](./terrain_traversability_analysis.bib#362-L369) | [Github](https://github.com/NHirose/GONET)

- [Find your own way: Weakly-supervised segmentation of path proposals for urban autonomy](https://ieeexplore.ieee.org/abstract/document/7989025/), Barnes et al., ICRA 2017 | [arXiv](https://arxiv.org/abs/1610.01238) | [bibtex](./terrain_traversability_analysis.bib#L371-L378)

</details>

<br>

### Proprioception-based approaches

- [Deep Spatiotemporal Models for Robust Proprioceptive Terrain Classification](https://journals.sagepub.com/doi/abs/10.1177/0278364917727062), Valada et al., IJRR 2017 | [arXiv](https://arxiv.org/abs/1804.00736) | [bibtex](./terrain_traversability_analysis.bib#L389-L398)

- [Multiclass Terrain Classification using Sound and Vibration from Mobile Robot Terrain Interaction](https://ieeexplore.ieee.org/abstract/document/9636237/), Libby et al., IROS 2021 | [bibtex](./terrain_traversability_analysis.bib#L380-L387)



<br>

### Hybrid approaches

- [TNS: Terrain Traversability Mapping and Navigation System for Autonomous Excavators](https://www.roboticsproceedings.org/rss18/p049.html), Guan et al., RSS 2022 | [arXiv](https://arxiv.org/abs/2109.06250) | [bibtex](./terrain_traversability_analysis.bib#L400-L408)

- [Self-Supervised Visual Terrain Classification From Unsupervised Acoustic Feature Learning](https://ieeexplore.ieee.org/abstract/document/9247267/), Zurn et al., T-RO 2020 | [arXiv](https://arxiv.org/abs/1912.03227) | [bibtex](./terrain_traversability_analysis.bib#L410-L419)

- [How Does It Feel? Self-Supervised Costmap Learning for Off-Road Vehicle Traversability](https://ieeexplore.ieee.org/abstract/document/10160856/), Castro et al., ICRA 2023 | [arXiv](https://arxiv.org/abs/2209.10788) | [bibtex](./terrain_traversability_analysis.bib#L421-L428)

- [How Rough Is the Path? Terrain Traversability Estimation for Local and Global Path Planning](https://ieeexplore.ieee.org/abstract/document/9721819/), Waibel et al., T-ITS 2022 | [bibtex](./terrain_traversability_analysis.bib#L430-L439)

- [An Hybrid Approach to Improve the Performance of Encoder-Decoder Architectures for Traversability Analysis in Urban Environments](https://ieeexplore.ieee.org/abstract/document/9827248/), Fusaro et al., IV 2022 | [bibtex](./terrain_traversability_analysis.bib#L441-L448)

- [Geometric and Visual Terrain Classification for Autonomous Mobile Navigation](https://ieeexplore.ieee.org/abstract/document/8206092/), Schilling et al., IROS 2017 | [bibtex](./terrain_traversability_analysis.bib#L450-L457)

<br>

### Terrain-aware Navigation

<details open>
<summary>Reinforcement Learning </summary>

- [BADGR: An Autonomous Self-Supervised Learning-Based Navigation System](https://ieeexplore.ieee.org/abstract/document/9345970/), Kahn et al., RA-L 2021 | [arXiv](https://arxiv.org/abs/2002.05700) | [bibtex](./terrain_traversability_analysis.bib#L459-468) | [Github](https://github.com/gkahn13/badgr)

- [A Sim-to-Real Pipeline for Deep Reinforcement Learning for Autonomous Robot Navigation in Cluttered Rough Terrain](https://ieeexplore.ieee.org/abstract/document/9468918/), Hu et al., RA-L 2021 | [bibtex](./terrain_traversability_analysis.bib#L470-L479)

- [TERP: Reliable Planning in Uneven Outdoor Environments using Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9812238/), Weerakoon et al., ICRA 2022 | [arXiv](https://arxiv.org/abs/2109.05120) | [bibtex](./terrain_traversability_analysis.bib#L481-488) | [Github](https://github.com/kasunweerkoon/terp)


</details>

<details open>
<summary>Traditional Planning & Control </summary>

- [Exploration of 3D terrains using potential fields with elevation-based local distortions](https://ieeexplore.ieee.org/abstract/document/9197577), Maffei et al., ICRA 2020 | [bibtex](./terrain_traversability_analysis.bib#L490-L497)

- [Long-Term Robot Navigation in Indoor Environments Estimating Patterns in Traversability Changes](https://ieeexplore.ieee.org/abstract/document/9197078/), Nardi et al., ICRA 2020 | [arXiv](https://arxiv.org/abs/1909.12733) | [bibtex](./terrain_traversability_analysis.bib#L499-L506)

- [Perceptive Locomotion in Rough Terrain – Online Foothold Optimization](https://ieeexplore.ieee.org/abstract/document/9134750), Jenelten et al., RA-L 2020 | [bibtex](./terrain_traversability_analysis.bib#L508-L517)

- [Driving on Point Clouds: Motion Planning, Trajectory Optimization, and Terrain Assessment in Generic Nonplanar Environments](https://onlinelibrary.wiley.com/doi/full/10.1002/rob.21700), Krusi et al., Journal of Field Robotics 2017 | [bibtex](./terrain_traversability_analysis.bib#L519-L528)

- [Navigation Planning for Legged Robots in Challenging Terrain](https://ieeexplore.ieee.org/abstract/document/7759199/), Wermelinger et al., IROS 2016 | [bibtex](./terrain_traversability_analysis.bib#L530-L539) | [Github](https://github.com/leggedrobotics/traversability_estimation)

- [Fuzzy Based Traversability Analysis for a Mobile Robot on Rough Terrain](https://ieeexplore.ieee.org/abstract/document/7139753), Tanaka et al., ICRA 2015 | [bibtex](./terrain_traversability_analysis.bib#L541-L550)

</details>

<br>

## Public Datasets

### Structured urban environments
- [KITTI VIsion Benchmark Suite](http://www.cvlibs.net/datasets/kitti/) : Stereo Camera images, LiDAR pointclouds, GPS/IMU  data
- [SemanticKITTI](http://semantic-kitti.org/index.html) : LiDAR points labeled with semantic class
- [nuScenes](https://www.nuscenes.org) : The data from 6 cameras, 1 LiDAR, 5 radars, and GPS/IMU
- [BDD100k](https://bdd-data.berkeley.edu/) : Video images annotated for object detection, lane detection, action recognition.
- [Cityscapes](https://www.cityscapes-dataset.com/) : semantic segmentation with high-resolution images annotated at the pixel level
- [KAIST Urban Dataset](https://sites.google.com/view/complex-urban-dataset/home) : The data from LiDAR, cameras (stereo, thermal, and panoramic), GPS, and IMU.

See more datasets at:
- [awesome-autonomous-driving-dataasets](https://github.com/lhyfst/awesome-autonomous-driving-datasets)
- [awesome-slam-datasets](https://github.com/youngguncho/awesome-slam-datasets)


### Unstructured terrains
- [RELLIS-3D](https://www.unmannedlab.org/research/RELLIS-3D) : Data with Stereo Camera images, LiDAR pointclouds, GPS/IMU
- [RUGD](http://rugd.vision/) : Video dataset annotated with pixel-wise labels
- [BotanicGarden](https://github.com/robot-pesg/BotanicGarden) : Stereo camera images, LiDAR pointclouds, GPS/IMU, Wheel encoders
- [GOOSE](https://goose-dataset.de/) : Data with Stereo Camera images, LiDAR pointclouds, GPS/IMU
