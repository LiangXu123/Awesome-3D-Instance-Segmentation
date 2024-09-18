
# Awesome-3D-Instance-Segmentation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)  <a href="" target='_blank'><img src="https://visitor-badge.laobi.icu/badge?page_id=activevisionlab.llm3d&left_color=gray&right_color=blue">

## 🏠 About
Papers and codes for 3D Instance Segmentation for Indoor Scenes. 😎 

This is an active repository, you can watch for following the latest advances. If you find it useful, please kindly star this repo.


### Closed-Vocabulary 3D Segmentation
|  ID |       keywords       |    Institute (first)    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2022-10-06 |  Mask3D |    RWTH  | [Mask3d: Mask transformer for 3d semantic instance segmentation](https://arxiv.org/pdf/2312.11557.pdf)                                                                                | ICRA2023 | [github](https://github.com/JonasSchult/Mask3D) |
| 2023-03-01 |  ISBNet |    VinAI  | [ISBNet: a 3D Point Cloud Instance Segmentation Network with Instance-aware Sampling and Box-aware Dynamic Convolution](https://arxiv.org/abs/2303.00246)                                                                                | CVPR2023 | [github](https://github.com/VinAIResearch/ISBNet) |


### Open-Vocabulary 3D Segmentation
|  ID |       keywords       |    Institute (first)    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2022-11-28 |       OpenScene       |      ETHz      | [OpenScene: 3D Scene Understanding with Open Vocabularies](https://arxiv.org/pdf/2211.15654.pdf)                                                             |   CVPR2023  | [github](https://github.com/pengsongyou/openscene) |                                                                 | OpenReview | [github]() |
| 2022-11-29 |        PLA        |     HKU    | [PLA: Language-Driven Open-Vocabulary 3D Scene Understanding](https://arxiv.org/pdf/2211.16312.pdf)       |CVPR2023|  [github](https://github.com/CVMI-Lab/PLA) |
| 2023-05-01 |  3D-OVS |    NTU  | [Weakly Supervised 3D Open-vocabulary Segmentation](https://arxiv.org/pdf/2305.14093)                                                                                | NeurIPS2023 | [github](https://github.com/Kunhao-Liu/3D-OVS) |
| 2023-05-01 |  OV3D  |    KAIST  | [Open-Vocabulary 3D Semantic Segmentation with Foundation Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Jiang_Open-Vocabulary_3D_Semantic_Segmentation_with_Foundation_Models_CVPR_2024_paper.pdf)                                                                            | Arxiv | [project]() |
| 2023-9-1|  OpenIns3D |    Cambridge  | [OpenIns3D: Snap and Lookup for 3D Open-vocabulary Instance Segmentation](https://arxiv.org/pdf/2309.00616.pdf)                                                                                | Arxiv | [github](https://zheninghuang.github.io/OpenIns3D/) |                                                                 |   ICCV2023| [github]() |
| 2023-10-29|  OpenMask3D |    ETH  | [OpenMask3D: Open-Vocabulary 3D Instance Segmentation](https://openmask3d.github.io/static/pdf/openmask3d.pdf)                                                                                | NeurIPS2023 | [github](https://openmask3d.github.io/) |    
| 2023-11-6 |  OVIR-3D |    Rutgers University  | [OVIR-3D: Open-Vocabulary 3D Instance Retrieval Without Training on 3D Data](https://arxiv.org/pdf/2311.02873.pdf) | CoRL2023 | [github](https://github.com/shiyoung77/OVIR-3D/) |
| 2023-11-18 |  LEGaussians |    Beihang University  | [LEGaussians: Language Embedded 3D Gaussians for Open-Vocabulary Scene Understanding](https://arxiv.org/pdf/2311.18482.pdf)                                                                                | CVPR2024 | [github](https://github.com/buaavrcg/LEGaussians) |
| 2023-12-11 |  SAI3D |    PKU  | [SAI3D: Segment Any Instance in 3D Scenes](https://arxiv.org/pdf/2312.11557.pdf)                                                                                | CVPR2024 | [github](https://yd-yin.github.io/SAI3D) |
| 2023-12-18 |  Open3DIS |    VinAI  | [Open3DIS: Open-vocabulary 3D Instance Segmentation with 2D Mask Guidance](https://arxiv.org/pdf/2312.10671.pdf)                                                                                | CVPR2024 | [github](https://open3dis.github.io/) |
| 2024-01-01 |  MaskClustering |    PKU  | [MaskClustering: View Consensus based Mask Graph Clustering for Open-Vocabulary 3D Instance Segmentation](https://arxiv.org/pdf/2401.07745)       
| 2024-06-01 |  Open-YOLO 3D |    MBZUAI  | [Open-YOLO 3D: Towards Fast and Accurate Open-Vocabulary 3D Instance Segmentation](https://arxiv.org/html/2406.02548v1)                                                                            | Arxiv | [github](https://github.com/aminebdj/OpenYOLO3D) |
| 2024-08-16 |  Dual-Path |    KAIST  | [Zero-Shot Dual-Path Integration Framework for Open-Vocabulary 3D Instance Segmentation](https://openaccess.thecvf.com/content/CVPR2024W/OpenSUN3D/papers/Ton_Zero-Shot_Dual-Path_Integration_Framework_for_Open-Vocabulary_3D_Instance_Segmentation_CVPRW_2024_paper.pdf)                                                                            | Arxiv | [project]() |


## 3D Benchmarks
|  Date |       keywords       |    Institute    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2017-01-14 | ScanNet | Stanford University | [ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes](https://arxiv.org/abs/1702.04405) | CVPR2017| [github](https://github.com/ScanNet/ScanNet) |
| 2017-09-18 | Matterport3D | Princeton University | [Matterport3D: Learning from RGB-D Data in Indoor Environments](https://niessner.github.io/Matterport/) | 3DV| [github](https://niessner.github.io/Matterport/) |
| 2019-01-13 | Replica | Facebook | [The Replica dataset: A digital replica of indoor spaces](https://arxiv.org/pdf/1906.05797) | Arxiv| [github](https://github.com/facebookresearch/Replica-Dataset/) |
| 2021-11-07 | ARKitScenes | Apple | [ARKitScenes: A Diverse Real-World Dataset For 3D Indoor Scene Understanding Using Mobile RGB-D Data](https://arxiv.org/abs/2111.08897) | Arxiv| [github](https://github.com/apple/ARKitScenes) |
| 2021-09-28 | KITTI-360 | Zhejiang University | [KITTI-360: A Novel Dataset and Benchmarks for Urban Scene Understanding in 2D and 3D](https://www.cvlibs.net/datasets/kitti-360/) | PAMI2021| [project](https://www.cvlibs.net/datasets/kitti-360/) |
| 2021-11-07 | ScanNet++ | TUM | [ScanNet++: A High-Fidelity Dataset of 3D Indoor Scenes](https://arxiv.org/abs/2308.11417) | CVPR2023| [github](https://cy94.github.io/scannetpp/) |



## Contributing

your contributions are always welcome!

I will keep some pull requests open if I'm not sure if they are awesome for 3D Instance Segmentation, you could vote for them by adding 👍 to them.
