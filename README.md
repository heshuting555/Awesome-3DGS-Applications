# semantic-3DGS-splatting
Welcome to the official repository of our journal paper:
# Overview of Existing Datasets for 3DGS Semantic Scene Understanding

Legend: *‘Centricity’ refers to scene and/or object-centric datasets, respectively denoted with S and O above.*

| Datasets with URL   | Venue     | #Scenes | #Imgs  | Centricity | Type   | Data Modalities   | Annotations                                   |
|---------------------|-----------|---------|--------|------------|--------|-------------------|-----------------------------------------------|
| [3DMV-VQA](#)       | CVPR 2023 | 5000    | 600K   | S+O        | Indoor | RGB               | Visual question & answer                      |
| [NeRDS 360](#)      | ICCV 2023 | 75      | 15k    | S+O        | Urban  | Synthetic         | 3D object boxes; 2D panoptic segmentation    |
| [ScanNet++](#)      | ICCV 2023 | 460     | 3.7M   | S          | Indoor | RGB-D             | 2D/3D panoptic segmentation                  |
| [KITTI-360](#)      | PAMI 2022 | 10      | 150K   | S+O        | Urban  | RGB & LiDAR       | 2D/3D object boxes; 2D panoptic segmentation |
| [SHIFT](#)          | CVPR 2022 | 4850    | 2.5M   | S+O        | Urban  | Synthetic         | 2D/3D object boxes; 2D panoptic segmentation |
| [HM3D Sem](#)       | arXiv 2023| 216     | -      | S          | Indoor | Mesh              | 3D semantic                                  |

# Overview of Existing Methods of Segmentation for 3DGS Semantic Scene Understanding


| Year   | Venue     | #Domain| Paper Title            |  Project                                 |
|---------------------|-----------|--------------------|---------------------------|-------------|
|   2024   | CVPR |   Segmentation & Detection   |        [LangSplat: 3D Language Gaussian Splatting](http://arxiv.org/abs/2312.16084)   |   https://langsplat.github.io/    |
|  2024   | CVPR |   Segmentation & Editing   |     [Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields](http://arxiv.org/abs/2312.03203)       | [https://feature-3dgs.github.io/](https://feature-3dgs.github.io/) |
| 2024 | CVPR |  Segmentation & Editing |[Language Embedded 3D Gaussians for Open-Vocabulary Scene Understanding](http://arxiv.org/abs/2311.18482) |  | https://buaavrcg.github.io/LEGaussians
|  |  |Segmentation & Editing  | [GOI: Find 3D Gaussians of Interest with an Optimizable Open-vocabulary Semantic-space Hyperplane](http://arxiv.org/abs/2405.17596)  | https://quyans.github.io/GOI-Hyperplane/ |
| 2023 |  | Segmentation & Detection | [ 3D Vision-Language Gaussian Splatting](http://arxiv.org/abs/2410.07577) | N/A |
|  2024|  |Segmentation  | [ Point Cloud Unsupervised Pre-training via 3D Gaussian Splatting](https://arxiv.org/abs/2411.18667) | N/A  |
| 2024 |  | Segmentation |[ FMGS: Foundation Model Embedded 3D Gaussian Splatting for Holistic 3D Scene Understanding](http://arxiv.org/abs/2401.01970)  |  |
| 2024 |  | Segmentation | [ Improving 2D Feature Representations by 3D-Aware Fine-Tuning](http://arxiv.org/abs/2407.20229) | https://ywyue.github.io/FiT3D |
| 2024 |  | Segmentation | [ OpenGaussian: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding](http://arxiv.org/abs/2406.02058) | https://3d-aigc.github.io/OpenGaussian |
| 2024 |  | Segmentation | [ DCSEG: Decoupled 3D Open-Set Segmentation using Gaussian Splatting](http://arxiv.org/abs/2412.10972) |  |
|2024  |  | Segmentation | [ Open Vocabulary 3D Scene Understanding via Geometry Guided Self-Distillation](http://arxiv.org/abs/2410.07577) |  |
| 2024 |  | Segmentation | [ SuperGSeg: Open-Vocabulary 3D Segmentation with Structured Super-Gaussians](http://arxiv.org/abs/2412.10231) |  |
| 2024 |  | Segmentation | [ FastLGS: Speeding up Language Embedded Gaussians with Feature Grid Mapping](http://arxiv.org/abs/2406.01916) |  |
| 2024 | ECCV | Segmentation | [ EgoLifter: Open-world 3D Segmentation for Egocentric Perception](http://arxiv.org/abs/2403.18118) |  |
| 2024 |  | Segmentation & Detection | [ EFD-3DGS: Flexible Disentangled 3DGS for Scenes Understanding and Manipulation](https://xusy2333.com/paper/FD-3DGS.pdf) |  |


# Overview of Existing Methods of Editing for 3DGS Semantic Scene Understanding

| Year   | Venue     | #Domain| Paper Title            |  Project                                 |
|---------------------|-----------|--------------------|---------------------------|-------------|
|   2024   | CVPR |   Segmentation & Editing   |   Gaussian Grouping: Segment and Edit Anything in 3D Scenes[(http://arxiv.org/abs/2312.16084)](http://arxiv.org/abs/2312.00732)   |   https://langsplat.github.io/    |
|2024  | ACM Transactions on Graphics |Editing  | [TIP-Editor: An Accurate 3D Editor Following Both Text-Prompts And Image-Prompts]http://arxiv.org/abs/2401.14828 | N/A  |
| 2024 | CVPR | Editing | DreamCatalyst: Fast and High-Quality 3D Editing via Controlling Editability and Identity Preservation[(http://arxiv.org/abs/2401.01970)](http://arxiv.org/abs/2407.11394)  |  |
|2024  |CVPR  | Editing | GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting[(http://arxiv.org/abs/2407.20229)](https://ieeexplore.ieee.org/document/10655963/) |  |
| 2024 | ECCV | Editing | DGE: Direct Gaussian 3D Editing by Consistent Multi-view Editing[(http://arxiv.org/abs/2412.10972)](http://arxiv.org/abs/2404.18929) |  |
| 2024 |CVPR  | Editing | GS-VTON: Controllable 3D Virtual Try-on with Gaussian Splatting[(http://arxiv.org/abs/2410.07577)](http://arxiv.org/abs/2410.05259) |  |
| 2024 |  | Editing | [Texture-GS: Disentangling the Geometry and Texture for 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.10050) |  |
| 2024 |  | Editing | [Gaussian Frosting: Editable Complex Radiance Fields with Real-Time Rendering](http://arxiv.org/abs/2403.14554) |  |
| 2024 |  | Editing | [GScream: Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal](https://dl.acm.org/doi/10.1145/3681758.3698002) |  |
| 2024 | SA '24: SIGGRAPH Asia 2024 Technical Communications | Editing | [StyleGaussian: Instant 3D Style Transfer with Gaussian Splatting](http://arxiv.org/abs/2404.13679) |  |
| 2024 |  | Editing | [HyperStyle3D: Text-Guided 3D Portrait Stylization via Hypernetworks](http://arxiv.org/abs/2304.09463) |  |
| 2024 |  | Editing | [InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior](http://arxiv.org/abs/2404.11613) |  |
| 2024 |  | Editing | [3D Gaussian Editing with A Single Image](https://dl.acm.org/doi/pdf/10.1145/3664647.3680858) |  |
| 2024 |  | Editing | [InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior](http://arxiv.org/abs/2404.11613) |  |
| 2024 |  | Editing | [EditSplat: Multi-View Fusion and Attention-Guided Optimization for View-Consistent 3D Scene Editing with 3D Gaussian Splatting](http://arxiv.org/abs/2412.11520) |  |
| 2024 |  | Editing | [InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior](http://arxiv.org/abs/2404.11613) |  |
| 2024 |  | Editing | [GaussianEditor: Editing 3D Gaussians Delicately with Text Instructions](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_GaussianEditor_Editing_3D_Gaussians_Delicately_with_Text_Instructions_CVPR_2024_paper.pdf) |  |
| 2024 |  | Editing | [3DitScene: Editing Any Scene via Language-guided Disentangled Gaussian Splatting](http://arxiv.org/abs/2404.11613) |  |
| 2024 |  | Editing | [GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.08733) |  |
| 2024 |  | Editing | [SemanticSplatStylization: Semantic scene stylization based on 3D Gaussian splatting and class-based style transfer](http://arxiv.org/abs/2404.11613) |  |
| 2024 |  | Editing | [CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding](http://arxiv.org/abs/2404.14249) |  |
| 2024 |  | Editing | [TIGER: Text-Instructed 3D Gaussian Retrieval and Coherent Editing](http://arxiv.org/abs/2405.14455) |  |
| 2024 |  | Editing | [SpectralGaussians: Semantic, spectral 3D Gaussian splatting for multi-spectral scene representation, visualization and analysis](https://arxiv.org/pdf/2408.06975?)|  |
| 2024 |  | Editing | [360-INPAINTR: REFERENCE-GUIDED 3D INPAINTING FOR UNBOUNDED SCENES](https://openreview.net/pdf/ee332494bcd7f9e4b66494d65eb850f61e9a0b43.pdf) |  |
| 2024 |  | Editing & Segmentation | [Point'n Move: Interactive scene object manipulation on Gaussian splatting radiance fields](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.13190)|  |
| 2024 |  | Editing & Generation | [FruitNinja: 3D Object Interior Texture Generation with Gaussian Splatting](http://arxiv.org/abs/2411.12089) |  |
| 2024 |  | Editing | [360-INPAINTR: REFERENCE-GUIDED 3D INPAINTING FOR UNBOUNDED SCENES](https://openreview.net/pdf/ee332494bcd7f9e4b66494d65eb850f61e9a0b43.pdf) |  |

# Overview of Existing Methods of Generation for 3DGS Semantic Scene Understanding


| Year   | Venue     | #Domain| Paper Title            |  Project                                 |
|---------------------|-----------|--------------------|---------------------------|-------------|
|  |  | Generation | [GVGEN: Text-to-3D Generation with Volumetric Representation] |  |
|  |  | Generation | [Event3DGS: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion] |  |
|  |  | Generation | [SplatFlow: Multi-View Rectified Flow Model for 3D Gaussian Splatting Synthesis](https://arxiv.org/abs/2411.16443) |  |
|  |  | Generation | [LIVE-GS: LLM Powers Interactive VR by Enhancing Gaussian Splatting](http://arxiv.org/abs/2412.09176) |  |
|  |  | Generation | [Event3DGS: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion] |  |
|  |  | Generation | [Event3DGS: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion] |  |
|  |  | Generation | [Event3DGS: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion] |  |
|  |  | Generation | [Event3DGS: Event-Based 3D Gaussian Splatting for High-Speed Robot Egomotion] |  |



# Overview of Existing Methods of Decetion for 3DGS Semantic Scene Understanding

Legend: *‘Centricity’ refers to scene and/or object-centric datasets, respectively denoted with S and O above.*

| Methods   | Venue     | #Domain| Detail                                   |
|---------------------|-----------|--------------------|---------------------------|
|     3D Vision-Language Gaussian Splatting           | CVPR 2023 | Segmentation & Detection     |        https://arxiv.org/abs/2410.07577           |
