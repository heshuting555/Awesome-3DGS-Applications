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


| Year   | Venue     | Acronym | Paper Title            |  Project/Code                                 |
|---------------------|-----------|--------------------|---------------------------|-------------|
| 2024 | CVPR |   LangSplat   |        [LangSplat: 3D Language Gaussian Splatting](http://arxiv.org/abs/2312.16084)   |   [Code](https://langsplat.github.io/))    |
| 2024 | CVPR |   Feature 3DGS   |     [Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields](http://arxiv.org/abs/2312.03203)       | [Code](https://feature-3dgs.github.io/) |
| 2024 | CVPR |  LEGaussian |[Language Embedded 3D Gaussians for Open-Vocabulary Scene Understanding](http://arxiv.org/abs/2311.18482) | [Code](https://buaavrcg.github.io/LEGaussians) | 
| 2024 | ACM MM | GOI  | [GOI: Find 3D Gaussians of Interest with an Optimizable Open-vocabulary Semantic-space Hyperplane](http://arxiv.org/abs/2405.17596)  | [Code](https://quyans.github.io/GOI-Hyperplane/) |
| - | N/A | 3D visionlanguage Gaussian splatting | [ 3D Vision-Language Gaussian Splatting](http://arxiv.org/abs/2410.07577) | N/A |
| - | N/A | GS3 | [ Point Cloud Unsupervised Pre-training via 3D Gaussian Splatting](https://arxiv.org/abs/2411.18667) | N/A |
| 2024 | IJCV | FMGS |[ FMGS: Foundation Model Embedded 3D Gaussian Splatting for Holistic 3D Scene Understanding](http://arxiv.org/abs/2401.01970)  | [Code](https://xingxingzuo.github.io/fmgs/) |
| 2024 | ECCV | FiT3D | [ Improving 2D Feature Representations by 3D-Aware Fine-Tuning](http://arxiv.org/abs/2407.20229) | [Code](https://ywyue.github.io/FiT3D) |
| 2024 | NeurIPS | OpenGaussian | [ OpenGaussian: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding](http://arxiv.org/abs/2406.02058) | [Code](https://3d-aigc.github.io/OpenGaussian) |
| - | N/A | DCSEG | [ DCSEG: Decoupled 3D Open-Set Segmentation using Gaussian Splatting](http://arxiv.org/abs/2412.10972) | [Code](https://github.com/lusxvr/dcseg)  | 
| - | N/A | SuperGSeg | [ SuperGSeg: Open-Vocabulary 3D Segmentation with Structured Super-Gaussians](http://arxiv.org/abs/2412.10231) | N/A |
| 2025 | AAAI | FastLGS | [ FastLGS: Speeding up Language Embedded Gaussians with Feature Grid Mapping](http://arxiv.org/abs/2406.01916) | [Code](https://george-attano.github.io/FastLGS/)|
| 2024 | ECCV | EgoLifter | [ EgoLifter: Open-world 3D Segmentation for Egocentric Perception](http://arxiv.org/abs/2403.18118) | [Code](https://egolifter.github.io/) |
| 2024 | ECCV | Click-Gaussian | [ Click-Gaussian: Interactive Segmentation to Any 3D Gaussians](https://arxiv.org/abs/2407.11793) | [Code](https://seokhunchoi.github.io/Click-Gaussian/) |
| - | N/A | CGC | [ Contrastive Gaussian Clustering: Weakly Supervised 3D Scene Segmentation](https://arxiv.org/abs/2404.12784) | N/A |
| 2025 | CVPR | InstanceGaussian | [ InstanceGaussian: Appearance-Semantic Joint Gaussian Representation for 3D Instance-Level Perception](https://arxiv.org/abs/2411.19235) | [Code](https://lhj-git.github.io/InstanceGaussian/) |
| 2024 | ECCV | N2F2 | [ N2F2: Hierarchical Scene Understanding with Nested Neural Feature Fields](https://arxiv.org/abs/2403.10997) | N/A |
| 2025 | AAAI | SAGA | [ Segment Any 3D Gaussians](https://arxiv.org/abs/2312.00860) | [Code](https://jumpat.github.io/SAGA/) |
| 2025 | ECCV | Gaussian Grouping | [ Gaussian Grouping: Segment and Edit Anything in 3D Scenes](https://arxiv.org/abs/2312.00732) | [Code](https://github.com/lkeab/gaussian-grouping) |
| - | N/A  | SAGD | [ SAGD: Boundary-Enhanced Segment Anything in 3D Gaussian via Gaussian Decomposition](https://arxiv.org/abs/2401.17857) | N/A  |
| - | N/A  | SLGaussian | [ SLGaussian: Fast Language Gaussian Splatting in Sparse Views](http://arxiv.org/abs/2412.08331) | N/A  |
| - | N/A  | CLIP-GS | [ CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding](http://arxiv.org/abs/2404.14249) | [Code](https://gbliao.github.io/CLIP-GS.github.io/)  |
| 2024 | NeurIPS  | GaussianCut | [ GaussianCut: Interactive segmentation via graph cut for 3D Gaussian Splatting](http://arxiv.org/abs/2411.07555) | N/A  |
| 2023 | NeurIPS  | SA3D | [ Segment Anything in 3D with Radiance Fields](http://arxiv.org/abs/2304.12308) |[Code](https://github.com/Jumpat/SegmentAnythingin3D) |
| 2024 | BMVC  | RT-GS2 | [ RT-GS2: Real-Time Generalizable Semantic Segmentation for 3D Gaussian Representations of Radiance Fields](http://arxiv.org/abs/2405.18033) | N/A |
| 2025 | WACV  | GaussianBeV | [ GaussianBeV: 3D Gaussian Representation meets Perception Models for BeV Segmentation](http://arxiv.org/abs/2407.14108) | N/A |
| - | N/A  | GSemSplat| [ GSemSplat: Generalizable Semantic 3D Gaussian Splatting from Uncalibrated Image Pairs](http://arxiv.org/abs/2412.16932) | N/A |
| - | N/A  | Semantic Gaussians | [ Semantic Gaussians: Open-Vocabulary Scene Understanding with 3D Gaussian Splatting](http://arxiv.org/abs/2403.15624) | [Code](https://sharinka0715.github.io/semantic-gaussians/) |
| - | N/A  | CoSegGaussians | [ Learning Segmented 3D Gaussians via Efficient Feature Unprojection for Zero-shot Neural Scene Segmentation](http://arxiv.org/abs/2405.18033) | [Code](https://David-Dou.github.io/CoSegGaussians) |
| - | N/A  | LangSurf | [ LangSurf: Language-Embedded Surface Gaussians for 3D Scene Understanding](https://arxiv.org/abs/2412.17635) | [Code](https://langsurf.github.io) |
| - | N/A  | GradiSeg | [ GradiSeg: Gradient-Guided Gaussian Segmentation with Enhanced 3D Boundary Precision](http://arxiv.org/abs/2412.00392) | N/A |
| - | N/A  | GLS | [ GLS: Geometry-aware 3D Language Gaussian Splatting](http://arxiv.org/abs/2411.18066) | [Code](https://github.com/JiaxiongQ/GLS) |
| - | N/A  | Gaga | [ Gaga: Group Any Gaussians via 3D-aware Memory Bank](https://arxiv.org/abs/2404.07977) | [Code](https://www.gaga.gallery/) |
| 2024 | ECCV  | FlashSplat| [ FlashSplat: 2D to 3D Gaussian Splatting Segmentation Solved Optimally](http://arxiv.org/abs/2409.08270) | [Code](https://github.com/florinshen/FlashSplat) |

| - | N/A  | N/A | [ RT-GS2: Real-Time Generalizable Semantic Segmentation for 3D Gaussian Representations of Radiance Fields](http://arxiv.org/abs/2401.05925) | Code |

# Overview of Existing Methods of Editing for 3DGS Semantic Scene Understanding

| Year   | Venue     | #Domain| Paper Title            |  Project                                 |
|---------------------|-----------|--------------------|---------------------------|-------------|
|   2024   | ECCV |   Segmentation & Editing   |   [Gaussian grouping: Segment and edit anything in 3d scenes](https://link.springer.com/chapter/10.1007/978-3-031-73397-0_10)   |   https://langsplat.github.io/    |
|2024  | ACM TOG                                             | Editing                | [Tip-editor: An accurate 3d editor following both text-prompts and image-prompts](https://dl.acm.org/doi/abs/10.1145/3658205) | [TIP-Editor: Text-Image Guided 3D Scene Editing](https://zjy526223908.github.io/TIP-Editor/) |
| 2025 | ICLR | Editing | [DreamCatalyst: Fast and High-Quality 3D Editing via Controlling Editability and Identity Preservation](https://arxiv.org/abs/2407.11394) | https://dream-catalyst.github.io/ |
|2024  |CVPR  | Editing | [Gaussianeditor: Swift and controllable 3d editing with gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Chen_GaussianEditor_Swift_and_Controllable_3D_Editing_with_Gaussian_Splatting_CVPR_2024_paper.html) | [GaussianEditor](https://buaacyw.github.io/gaussian-editor/) |
| 2024 | ECCV | Editing | [Dge: Direct gaussian 3d editing by consistent multi-view editing](https://link.springer.com/chapter/10.1007/978-3-031-72904-1_5) | [DGE: Direct Gaussian 3D Editing by Consistent Multi-view Editing](https://silent-chen.github.io/DGE/) |
| 2024 |                                                     | Editing | [Gaussianvton: 3d human virtual try-on via multi-stage gaussian splatting editing with image prompting](https://arxiv.org/abs/2405.07472)http://arxiv.org/abs/2410.05259) | [GaussianVTON: 3D Human Virtual Try-ON via Multi-Stage Gaussian Splatting Editing with Image Prompting](https://haroldchen19.github.io/gsvton/) |
| 2024 |  | Editing | [Texture-GS: Disentangling the Geometry and Texture for 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.10050) | N/A |
| 2024 |  | Editing | [GScream: Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal](https://dl.acm.org/doi/10.1145/3681758.3698002) | N/A |
| 2024 | SA '24: SIGGRAPH Asia 2024 Technical Communications | Style transfer | [StyleGaussian: Instant 3D Style Transfer with Gaussian Splatting](http://arxiv.org/abs/2404.13679) | [StyleGaussian: Instant 3D Style Transfer with Gaussian Splatting](https://kunhao-liu.github.io/StyleGaussian/) |
| 2024 |  | Editing | [InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior](http://arxiv.org/abs/2404.11613) | [Infusion](https://johanan528.github.io/Infusion/) |
| 2024 |                                                     | Style Transfer         | [Stylesplat: 3d object style transfer with gaussian splatting](https://arxiv.org/abs/2407.09473) | N/A |
|      |                                                     | Style Transfer         | [Stylizedgs: Controllable stylization for 3d gaussian splatting](https://arxiv.org/abs/2404.05220) | N/A |
| 2025 | CVPR | Editing | [EditSplat: Multi-View Fusion and Attention-Guided Optimization for View-Consistent 3D Scene Editing with 3D Gaussian Splatting](http://arxiv.org/abs/2412.11520) | [EditSplat: Multi-View Fusion and Attention-Guided Optimization](https://kuai-lab.github.io/editsplat2024/) |
| 2024 | CVPR | Editing | [Gaussianeditor: Editing 3d gaussians delicately with text instructions](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_GaussianEditor_Editing_3D_Gaussians_Delicately_with_Text_Instructions_CVPR_2024_paper.html) | [GaussianEditor: Editing 3D Gaussians Delicately with Text Instructions](https://gaussianeditor.github.io/) |
| 2024 | ECCV | Editing | [GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.08733) | [GaussCtrl](https://gaussctrl.active.vision/) |
| 2024 |  | Editing | [SemanticSplatStylization: Semantic scene stylization based on 3D Gaussian splatting and class-based style transfer](http://arxiv.org/abs/2404.11613) | N/A |
| 2024 |  | Editing | [TIGER: Text-Instructed 3D Gaussian Retrieval and Coherent Editing](http://arxiv.org/abs/2405.14455) | [TIGER](https://xutanxing.github.io/TIGER/) |
| 2024 | IET Image Processing | Editing & Segmentation | [Point'n Move: Interactive scene object manipulation on Gaussian splatting radiance fields](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.13190)| N/A |
| 2024 |  | Editing & Generation | [FruitNinja: 3D Object Interior Texture Generation with Gaussian Splatting](http://arxiv.org/abs/2411.12089) | N/A |
| 2024 |  | Editing | [360-INPAINTR: REFERENCE-GUIDED 3D INPAINTING FOR UNBOUNDED SCENES](https://openreview.net/pdf/ee332494bcd7f9e4b66494d65eb850f61e9a0b43.pdf) | N/A |
| 2024 | ACM MM | Editing | [3D Gaussian Editing with A Single Image](https://dl.acm.org/doi/pdf/10.1145/3664647.3680858) | N/A |
| 2024 | ECCV | Editing | [3DEgo: 3D Editing on the Go!](https://arxiv.org/pdf/2407.10102) | https://3dego.github.io/ |
| 2024 | | Editing | [3DitScene: Editing Any Scene via Language-guided Disentangled Gaussian Splatting](https://arxiv.org/abs/2405.18424) | [3DitScene](https://zqh0253.github.io/3DitScene/) |
| 2024 | | Editing | [3dsceneeditor: Controllable 3d scene editing with gaussian splatting](https://arxiv.org/abs/2412.01583) | [3DSceneEditor: Controllable 3D Scene Editing with Gaussian Splatting](https://ziyangyan.github.io/3DSceneEditor/) |
| 2024 | | Style transfer | [ArtNVG: Content-Style Separated Artistic Neighboring-View Gaussian Stylization](https://arxiv.org/abs/2412.18783) | N/A |
| 2024 | ACM TOG | Editing | [Tip-editor: An accurate 3d editor following both text-prompts and image-prompts](https://dl.acm.org/doi/abs/10.1145/3658205) | [TIP-Editor: Text-Image Guided 3D Scene Editing](https://zjy526223908.github.io/TIP-Editor/) |
| 2024 | | Editing | [Diffusion-Based Attention Warping for Consistent 3D Scene Editing](https://arxiv.org/abs/2412.07984) | [Diffusion-Based Attention Warping for Consistent 3D Scene Editing](https://attention-warp.github.io/) |
| 2024 | NeurIPS | Editing | [D-miso: Editing dynamic 3d scenes using multi-gaussians soup](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c32319f4868da7613d78af9993100e42-Abstract-Conference.html) | https://github.com/waczjoan/D-MiSo |
| 2025 | | Editing | [Drag Your Gaussian: Effective Drag-Based Editing with Score Distillation for 3D Gaussian Splatting](https://arxiv.org/abs/2501.18672) | [Drag Your Gaussian: Effective Point-Based Editing with Score Distillation for 3D Gaussian Splatting](https://quyans.github.io/Drag-Your-Gaussian/) |
| 2025 | | Editing | [Dragen3D: Multiview Geometry Consistent 3D Gaussian Generation with Drag-Based Control](https://arxiv.org/abs/2502.16475) | N/A |
| 2024 | | Editing | [DynamicAvatars: Accurate Dynamic Facial Avatars Reconstruction and Precise Editing with Diffusion Models](https://arxiv.org/abs/2411.15732) | N/A |
| 2024 | | Editing | [Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting](https://arxiv.org/abs/2406.02541) | [Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting](https://video-3dgs-project.github.io/) |
| 2024 | | Style Transfer | [Gaussian splatting in style](https://arxiv.org/abs/2403.08498) | N/A |
| 2024 | ACM MM | Editing | [GGAvatar: Reconstructing Garment-Separated 3D Gaussian Splatting Avatars from Monocular Video](https://dl.acm.org/doi/abs/10.1145/3696409.3700241) | https://github.com/J-X-Chen/GGAvatar/ |
| 2024 | | Editing | [Gsedit: Efficient text-guided editing of 3d objects via gaussian splatting](https://arxiv.org/abs/2403.05154) | N/A |
| 2024 | Computer Graphics Forum | Editing | [GSEditPro: 3D Gaussian Splatting Editing with Attention‐based Progressive Localization](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15215) | N/A |
| 2024 | Computer Graphics Forum | Style Transfer | [*𝒢*‐Style: Stylized Gaussian Splatting](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15259) | N/A |
| 2024 | | Editing | [GS-VTON: Controllable 3D Virtual Try-on with Gaussian Splatting](https://arxiv.org/abs/2410.05259) | [GS-VTON](https://yukangcao.github.io/GS-VTON/) |
| 2024 | | Editing | [Ice-g: Image conditional editing of 3d gaussian splats](https://arxiv.org/abs/2406.08488) | [ICE-G](https://ice-gaussian.github.io/) |
| 2024 | | Style Transfer | [Instantstylegaussian: Efficient art style transfer with 3d gaussian splatting](https://arxiv.org/abs/2408.04249) | N/A |
| 2024 | ECCV | Editing | [Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal](https://link.springer.com/chapter/10.1007/978-3-031-72646-0_1) | [GScream](https://w-ted.github.io/publications/gscream/) |
| 2024 | | Editing | [Localized Gaussian Splatting Editing with Contextual Awareness](https://arxiv.org/abs/2408.00083) | N/A |
| 2025 | | Editing | [MultiDreamer3D: Multi-concept 3D Customization with Concept-Aware Diffusion Guidance](https://arxiv.org/abs/2501.13449) | N/A |
| 2024 | | Editing | [MvDrag3D: Drag-based Creative 3D Editing via Multi-view Generation-Reconstruction Priors](https://arxiv.org/abs/2410.16272) | [MVDrag3D: Drag-based Creative 3D Editing via Multi-view Generation-Reconstruction Priors.](https://chenhonghua.github.io/MyProjects/MvDrag3D/) |
| 2024 | | Editing | [Neural Surface Priors for Editable Gaussian Splatting](https://arxiv.org/abs/2411.18311) | [github.com](https://github.com/WJakubowska/NeuralSurfacePriors) |
| 2024 | | Editing | [PERSE: Personalized 3D Generative Avatars from A Single Portrait](https://arxiv.org/abs/2412.21206) | [PERSE: Personalized 3D Generative Avatars from A Single Portrait](https://hyunsoocha.github.io/perse/) |
| 2024 | SIGGRAPH | Editing | [Portrait video editing empowered by multimodal generative priors](https://dl.acm.org/doi/abs/10.1145/3680528.3687601) | [PortraitGen](https://ustc3dv.github.io/PortraitGen/) |
| 2024 | NeurIPS | Editing | [ProEdit: Simple Progression is All You Need for High-Quality 3D Scene Editing](https://arxiv.org/abs/2411.05006) | [ProEdit: Simple Progression is All You Need for High-Quality 3D Scene Editing](https://immortalco.github.io/ProEdit/) |
| 2024 | | Editing | [ProGDF: Progressive Gaussian Differential Field for Controllable and Flexible 3D Editing](https://arxiv.org/abs/2412.08152) | N/A |
| 2024 | NeurIPS | Style Transfer | [ReGS: Reference-based Controllable Scene Stylization with Gaussian Splatting](https://proceedings.neurips.cc/paper_files/paper/2024/hash/076c1fa639a7190e216e734f0a1b3e7b-Abstract-Conference.html) | N/A |
| 2024 | | Editing | [Reffusion: Reference adapted diffusion models for 3d scene inpainting](https://arxiv.org/abs/2404.10765) | [RefFusion: Reference Adapted Diffusion Models for 3D Scene Inpainting](https://reffusion.github.io/) |
| 2024 | | Style Transfer | [SGSST: Scaling Gaussian Splatting StyleTransfer](https://arxiv.org/abs/2412.03371) | N/A |
| 2024 | | Editing | [Trame: Trajectory-anchored multi-view editing for text-guided 3d gaussian splatting manipulation](https://arxiv.org/abs/2407.02034) | N/A |
| 2024 | ECCV | Editing | [View-consistent 3d editing with gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72761-0_23) | [ECCV 2024\] View-consistent 3D Editing with Gaussian Splatting](https://vcedit.github.io/) |
| 2024 | ECCV | Editing | [Wast-3d: Wasserstein-2 distance for scene-to-scene stylization on 3d gaussians](https://link.springer.com/chapter/10.1007/978-3-031-72664-4_17) | [WaSt-3D: Wasserstein-2 Distance for Scene-to-Scene Stylization on 3D Gaussians](https://compvis.github.io/wast3d/) |



# Overview of Existing Methods of Generation for 3DGS Semantic Scene Understanding


| Year   | Venue     | #Domain| Paper Title            |  Project                                 |
|---------------------|-----------|:-------------------|---------------------------|-------------|
| 2024 |  | Optimization-based | [Layout-your-3D: Controllable and Precise 3D Generation with 2D Blueprint](https://arxiv.org/abs/2410.15391) | [Layout-Your-3D: Controllable and Precise 3D Generation with 2D Blueprint](https://colezwhy.github.io/layoutyour3d/) |
| 2024 |         | Optimization-based | [Graph Canvas for Controllable 3D Scene Generation](https://arxiv.org/abs/2412.00091) | N/A |
| 2024 |  | Optimization-based | [Layerpano3d: Layered 3d panorama for hyper-immersive scene generation](https://arxiv.org/abs/2408.13252) | [LayerPano3D: Layered 3D Panorama for Hyper-Immersive Scene Generation](https://layerpano3d-web.github.io/) |
| 2024 |         | Optimization-based | [Scenedreamer360: Text-driven 3d-consistent scene generation with panoramic gaussian splatting](https://arxiv.org/abs/2408.13711) | https://github.com/liwrui/SceneDreamer360 |
| 2023 |         | Optimization-based | [Dreamgaussian: Generative gaussian splatting for efficient 3d content creation](https://arxiv.org/abs/2309.16653) | [DreamGaussian](https://dreamgaussian.github.io/)            |
| 2024 | CVPR    | Optimization-based | [Text-to-3d using gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Chen_Text-to-3D_using_Gaussian_Splatting_CVPR_2024_paper.html) | https://github.com/gsgen3d/gsgen                             |
| 2024 | CVPR    | Optimization-based | [Gaussiandreamer: Fast generation from text to 3d gaussians by bridging 2d and 3d diffusion models](http://openaccess.thecvf.com/content/CVPR2024/html/Yi_GaussianDreamer_Fast_Generation_from_Text_to_3D_Gaussians_by_Bridging_CVPR_2024_paper.html) | [Gaussiandreamerpro: Text to manipulable 3d gaussians with highly enhanced quality](https://arxiv.org/abs/2406.18462) |
| 2024 |         | Optimization-based | [Gaussiandreamerpro: Text to manipulable 3d gaussians with highly enhanced quality](https://arxiv.org/abs/2406.18462) | [Gaussiandreamerpro: Text to manipulable 3d gaussians with highly enhanced quality](https://arxiv.org/abs/2406.18462) |
| 2024 |         | Optimization-based | [CompGS: Unleashing 2D Compositionality for Compositional Text-to-3D via Dynamically Optimizing 3D Gaussians](https://arxiv.org/abs/2410.20723) | [CompGS: Unleashing 2D Compositionality for Compositional Text-to-3D via Dynamically Optimizing 3D Gaussians](https://chongjiange.github.io/compgs.html) |
| 2023 |         | Optimization-based | [Cg3d: Compositional generation for text-to-3d via gaussian splatting](https://arxiv.org/abs/2311.17907) | [CG3D: Compositional Generation for Text-to-3D via Gaussian Splatting](https://asvilesov.github.io/CG3D/) |
| 2023 |         | Optimization-based | [Stabledreamer: taming noisy score distillation sampling for text-to-3d](https://arxiv.org/abs/2312.02189) | N/A |
| 2024 | ECCV    | Optimization-based | [Connecting consistency distillation to score distillation for text-to-3d generation](https://link.springer.com/chapter/10.1007/978-3-031-72775-7_16) | https://github.com/LMozart/ECCV2024-GCS-BEG |
| 2024 |         | Optimization-based | [DreamMapping: High-Fidelity Text-to-3D Generation via Variational Distribution Mapping](https://arxiv.org/abs/2409.05099) | N/A |
| 2024 | CVPR    | Optimization-based | [Humangaussian: Text-driven 3d human generation with gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Liu_HumanGaussian_Text-Driven_3D_Human_Generation_with_Gaussian_Splatting_CVPR_2024_paper.html) | [HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting](https://alvinliu0.github.io/projects/HumanGaussian) |
| 2024 | ECCV    | Optimization-based | [Dreamscene: 3d gaussian-based text-to-3d scene generation via formation pattern sampling](https://link.springer.com/chapter/10.1007/978-3-031-72904-1_13) | [DreamScene](https://dreamscene-project.github.io/) |
| 2024 | CVPR    | Optimization-based | [Luciddreamer: Towards high-fidelity text-to-3d generation via interval score matching](http://openaccess.thecvf.com/content/CVPR2024/html/Liang_LucidDreamer_Towards_High-Fidelity_Text-to-3D_Generation_via_Interval_Score_Matching_CVPR_2024_paper.html) | https://github.com/EnVision-Research/LucidDreamer |
| 2024 |         | Optimization-based | [Dreamer XL: Towards High-Resolution Text-to-3D Generation via Trajectory Score Matching](https://arxiv.org/abs/2405.11252) | [GitHub - xingy038/Dreamer-XL](https://github.com/xingy038/Dreamer-XL) |
| 2025 |         | Optimization-based | [GaussianMotion: End-to-End Learning of Animatable Gaussian Avatars with Pose Guidance from Text](https://arxiv.org/abs/2502.11642) | N/A |
| 2024 |         | Optimization-based | [MVGaussian: High-Fidelity text-to-3D Content Generation with Multi-View Guidance and Surface Densification](https://arxiv.org/abs/2409.06620) | [MVGaussian](https://mvgaussian.github.io/) |
| 2024 |         | Optimization-based | [GradeADreamer: Enhanced Text-to-3D Generation Using Gaussian Splatting and Multi-View Diffusion](https://arxiv.org/abs/2406.09850) | https://github.com/trapoom555/GradeADreamer |
| 2024 | ICML    | Optimization-based | [Gala3d: Towards text-to-3d complex scene generation via layout-guided generative gaussian splatting](https://arxiv.org/abs/2402.07207) | [GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guidedGenerative Gaussian Splatting](https://gala3d.github.io/) |
| 2024 | 3DV     | Optimization-based | [Controllable text-to-3D generation via surface-aligned Gaussian splatting](https://arxiv.org/abs/2403.09981) | [Controllable Text-to-3D Generation via Surface-Aligned Gaussian Splatting](https://lizhiqi49.github.io/MVControl/) |
| 2023 |         | Optimization-based | [Text2immersion: Generative immersive scene with 3d gaussians](https://arxiv.org/abs/2312.09242) | https://ken-ouyang.github.io/text2immersion/index.html |
| 2023 | ICCV    | Optimization-based | [Text2room: Extracting textured 3d meshes from 2d text-to-image models](http://openaccess.thecvf.com/content/ICCV2023/html/Hollein_Text2Room_Extracting_Textured_3D_Meshes_from_2D_Text-to-Image_Models_ICCV_2023_paper.html) | https://lukashoel.github.io/text-to-room/ |
| 2024 | 3DV     | Optimization-based | [Realmdreamer: Text-driven 3d scene generation with inpainting and depth diffusion](https://arxiv.org/abs/2404.07199) | https://realmdreamer.github.io/ |
| 2024 | CVPR    | Optimization-based | [Wonderjourney: Going from anywhere to everywhere](http://openaccess.thecvf.com/content/CVPR2024/html/Yu_WonderJourney_Going_from_Anywhere_to_Everywhere_CVPR_2024_paper.html) | [WonderJourney](https://kovenyu.com/wonderjourney/) |
| 2024 |         | Optimization-based | [Art3d: 3d gaussian splatting for text-guided artistic scenes generation](https://arxiv.org/abs/2405.10508) | N/A |
| 2024 |         | Optimization-based | [Fastscene: Text-driven fast 3d indoor scene generation via panoramic gaussian splatting](https://arxiv.org/abs/2405.05768) | N/A |
| 2024 |         | Optimization-based | [Holodreamer: Holistic 3d panoramic world generation from text descriptions](https://arxiv.org/abs/2407.15187) | N/A |
| 2024 | ECCV    | Optimization-based | [Dreamscene360: Unconstrained text-to-3d scene generation with panoramic gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72658-3_19) | [DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting](https://dreamscene360.github.io/) |
| 2024 |         | Feed Forward       | [Vfusion3d: Learning scalable 3d generative models from video diffusion models](https://link.springer.com/chapter/10.1007/978-3-031-72627-9_19) | [VFusion3D: Learning Scalable 3D Generative Models from Video Diffusion Models](https://junlinhan.github.io/projects/vfusion3d.html) |
| 2024 |         | Feed Forward       | [Brightdreamer: Generic 3d gaussian generative framework for fast text-to-3d synthesis](https://arxiv.org/abs/2403.11273) | [BrightDreamer](https://vlislab22.github.io/BrightDreamer/) |
| 2025 |         | Feed Forward       | [Taming Feed-forward Reconstruction Models as Latent Encoders for 3D Generative Models](https://arxiv.org/abs/2501.00651) | https://triflow.github.io/ |
| 2024 |         | Feed Forward       | [GaussianAnything: Interactive Point Cloud Latent Diffusion for 3D Generation](https://arxiv.org/abs/2411.08033) | https://nirvanalan.github.io/projects/ga/ |
| 2024 |         | Feed Forward       | [Flex3d: Feed-forward 3d generation with flexible reconstruction model and input view curation](https://arxiv.org/abs/2410.00890) | https://junlinhan.github.io/projects/flex3d/ |
| 2024 | WACV    | Feed Forward       | [GANFusion: Feed-Forward Text-to-3D with Diffusion in GAN Space](https://arxiv.org/abs/2412.16717) | [GANFusion](https://ganfusion.github.io/) |
| 2024 |         | Feed Forward       | [Prometheus: 3D-Aware Latent Diffusion Models for Feed-Forward Text-to-3D Scene Generation](https://arxiv.org/abs/2412.21117) | [GitHub - XDimLab/Prometheus: Prometheus: 3D-Aware Latent Diffusion Models for Feed-Forward Text-to-3D Scene Generation](https://github.com/XDimLab/Prometheus) |
| 2025 | CVPR    | Feed Forward       | [Turbo3D: Ultra-fast Text-to-3D Generation](https://arxiv.org/abs/2412.04470) | [Turbo3D: Ultra-fast Text-to-3D Generation](https://turbo-3d.github.io/) |
| 2024 | IJCV    | Feed Forward       | [Hyper-3dg: Text-to-3d gaussian generation via hypergraph](https://link.springer.com/article/10.1007/s11263-024-02298-y) | https://github.com/yjhboy/Hyper3DG |
| 2024 | ECCV    | Feed Forward       | [Lgm: Large multi-view gaussian model for high-resolution 3d content creation](https://link.springer.com/chapter/10.1007/978-3-031-73235-5_1) | [LGM](https://me.kiui.moe/lgm/) |
| 2024 |         | Feed Forward       | [Atlas Gaussians Diffusion for 3D Generation](https://arxiv.org/abs/2408.13055) | N/A |
| 2024 | ECCV    | Feed Forward       | [Gvgen: Text-to-3d generation with volumetric representation](https://link.springer.com/chapter/10.1007/978-3-031-73242-3_26) | [GVGEN:Text-to-3D Generation with Volumetric Representation](https://sotamak1r.github.io/gvgen/) |
| 2024 |         | Optimization-based | [Text-to-3D Gaussian Splatting with Physics-Grounded Motion Generation](https://arxiv.org/abs/2412.05560) | N/A |
| 2025 |         | Optimization-based | [LAYOUTDREAMER: Physics-guided Layout for Text-to-3D Compositional Scene Generation](https://arxiv.org/abs/2502.01949) | N/A |
| 2024 |         | Optimization-based | [DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling](https://arxiv.org/abs/2404.09227) | N/A |
| 2024 | CVPR    | Optimization-based | [Hash3d: Training-free acceleration for 3d generation](https://arxiv.org/abs/2404.06091) | [Hash3D](https://adamdad.github.io/hash3D/) |
| 2024 |         | Optimization-based | [Dreampolisher: Towards high-quality text-to-3d generation via geometric diffusion](https://arxiv.org/abs/2403.17237) | https://yuanze-lin.me/DreamPolisher_page/ |
| 2024 | NeurIPS | Feed Forward       | [GSGAN: Adversarial Learning for Hierarchical Generation of 3D Gaussian Splats](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7d90c28e7820709792d969211815a2b3-Abstract-Conference.html) | https://hse1032.github.io/gsgan |
| 2024 | ACM MM  | Optimization-based | [Sketch3D: Style-Consistent Guidance for Sketch-to-3D Generation](https://dl.acm.org/doi/abs/10.1145/3664647.3680641) | N/A |
| 2024 | NeurIPS | Optimization-based | [Wild-gs: Real-time novel view synthesis from unconstrained photo collections](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bb11f79ad86f5e33e2a7c850cbdfed42-Abstract-Conference.html) | [github.com](https://github.com/XuJiacong/Wild-GS) |
| 2025 |         | Optimization-based | [GSV3D: Gaussian Splatting-based Geometric Distillation with Stable Video Diffusion for Single-Image 3D Object Generation](https://arxiv.org/abs/2503.06136) | N/A |
| 2024 | ECCV    | Optimization-based | [Fsgs: Real-time few-shot view synthesis using gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72933-1_9) | [FSGS](https://zehaozhu.github.io/FSGS/) |
| 2024 |         | Optimization-based | [PanoDreamer: 3D Panorama Synthesis from a Single Image](https://arxiv.org/abs/2412.04827) | [PanoDreamer: Optimization-Based Single Image to 360 3D Scene With Diffusion](https://people.engr.tamu.edu/nimak/Papers/PanoDreamer/index.html) |
| 2024 |         | Optimization-based | [ScalingGaussian: Enhancing 3D Content Creation with Generative Gaussian Splatting](https://arxiv.org/abs/2407.19035) | N/A |
| 2024 |         | Optimization-based | [Physics3d: Learning physical properties of 3d gaussians via video diffusion](https://arxiv.org/abs/2406.04338) | https://liuff19.github.io/Physics3D/ |
| 2024 |         | Optimization-based | [Enhancing Single Image to 3D Generation using Gaussian Splatting and Hybrid Diffusion Priors](https://arxiv.org/abs/2410.09467) | N/A |
| 2024 |         | Optimization-based | [GECO: Generative Image-to-3D within a SECOnd](https://arxiv.org/abs/2405.20327) | N/A |
| 2024 | NeurIPS | Optimization-based | [Prolificdreamer: High-fidelity and diverse text-to-3d generation with variational score distillation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1a87980b9853e84dfb295855b425c262-Abstract-Conference.html) | [ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation](https://ml.cs.tsinghua.edu.cn/prolificdreamer/) |
| 2024 |         | Optimization-based | [Dreamphysics: Learning physical properties of dynamic 3d gaussians with video diffusion priors](https://arxiv.org/abs/2406.01476) | https://github.com/tyhuang0428/DreamPhysics |
| 2023 |         | Optimization-based | [Luciddreamer: Domain-free generation of 3d gaussian splatting scenes](https://arxiv.org/abs/2311.13384) | https://github.com/luciddreamer-cvlab/LucidDreamer |
| 2024 |         | Optimization-based | [VistaDream: Sampling multiview consistent images for single-view scene reconstruction](https://arxiv.org/abs/2410.16892) | https://github.com/WHU-USI3DV/VistaDream |
| 2024 |         | Optimization-based | [Multi-view Geometry-Aware Diffusion Transformer for Indoor Novel View Synthesis](https://openreview.net/forum?id=8hpJBfBjlZ) | N/A |
| 2024 | NeurIPS | Feed Forward       | [Diffgs: Functional gaussian splatting diffusion](https://proceedings.neurips.cc/paper_files/paper/2024/hash/41fb2ecb5b7d1b505bca787de0a603dc-Abstract-Conference.html) | [DiffGS](https://junshengzhou.github.io/DiffGS/) |
| 2024 | NeurIPS | Feed Forward       | [Era3d: high-resolution multiview diffusion using efficient row-wise attention](https://proceedings.neurips.cc/paper_files/paper/2024/hash/65a723bf7d8dad838c09178270d30e80-Abstract-Conference.html) | https://penghtyx.github.io/Era3D/ |
| 2025 | CVPR    | Feed Forward       | [Splatter-360: Generalizable 360 Gaussian Splatting for Wide-baseline Panoramic Images](https://arxiv.org/abs/2412.06250) | https://3d-aigc.github.io/Splatter-360/ |
| 2024 |         | Feed Forward       | [Agg: Amortized generative 3d gaussians for single image to 3d](https://arxiv.org/abs/2401.04099) | https://ir1d.github.io/AGG/ |
| 2024 | NeurIPS | Feed Forward       | [Humansplat: Generalizable single-image human gaussian splatting with structure priors](https://proceedings.neurips.cc/paper_files/paper/2024/hash/87affd2029375d1be123ccdab5334c55-Abstract-Conference.html) | [HumanSplat: Generalizable Single-Image Human Gaussian Splatting with Structure Priors](https://humansplat.github.io/) |
| 2024 |         | Feed Forward       | [Triplane meets gaussian splatting: Fast and generalizable single-view 3d reconstruction with transformers](http://openaccess.thecvf.com/content/CVPR2024/html/Zou_Triplane_Meets_Gaussian_Splatting_Fast_and_Generalizable_Single-View_3D_Reconstruction_CVPR_2024_paper.html) | [Triplane Meets Gaussian Splatting: Fast and Generalizable Single-View 3D Reconstruction with Transformers](https://zouzx.github.io/TriplaneGaussian/) |
| 2024 | ECCV    | Feed Forward       | [Gs-lrm: Large reconstruction model for 3d gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72670-5_1) | https://sai-bi.github.io/project/gs-lrm/ |
| 2024 | ECCV    | Feed Forward       | [Grm: Large gaussian reconstruction model for efficient 3d reconstruction and generation](https://link.springer.com/content/pdf/10.1007/978-3-031-72633-0_1.pdf) | https://github.com/justimyhxu/grm |
| 2024 | ACM MM  | Feed Forward       | [Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models](https://dl.acm.org/doi/abs/10.1145/3664647.3681634) | https://github.com/yanghb22-fdu/Hi3D-Official |
| 2024 | CVPR    | Feed Forward       | [Ouroboros3d: Image-to-3d generation via 3d-aware recursive diffusion](https://arxiv.org/abs/2406.03184) | https://costwen.github.io/Ouroboros3D/ |
| 2024 |         | Feed Forward       | [Baking gaussian splatting into diffusion denoiser for fast and scalable single-stage image-to-3d generation](https://arxiv.org/abs/2411.14384) | https://caiyuanhao1998.github.io/project/DiffusionGS/ |
| 2024 | ACM MM  | Feed Forward       | [Large point-to-gaussian model for image-to-3d generation](https://dl.acm.org/doi/abs/10.1145/3664647.3680920) | N/A |
| 2024 |         | Feed Forward       | [GaussianPainter: Painting Point Cloud into 3D Gaussians with Normal Guidance](https://arxiv.org/abs/2412.17715) | https://github.com/zhou745/GaussianPainter |
| 2024 |         | Feed Forward       | [Gaussianstego: A generalizable stenography pipeline for generative 3d gaussians splatting](https://arxiv.org/abs/2407.01301) | https://gaussian-stego.github.io/ |
| 2024 |         | Feed Forward       | [GeoGS3D: Single-view 3D Reconstruction via Geometric-aware Diffusion Model and Gaussian Splatting](https://arxiv.org/abs/2403.10242) | https://qjfeng.net/GeoGS3D/ |
| 2024 |         | Feed Forward       | [Cycle3d: High-quality and consistent image-to-3d generation via generation-reconstruction cycle](https://arxiv.org/abs/2407.19548) | https://pku-yuangroup.github.io/Cycle3D/ |
| 2024 | ACM MM  | Optimization-based | [A general framework to boost 3d gs initialization for text-to-3d generation by lexical richness](https://dl.acm.org/doi/abs/10.1145/3664647.3680740) | https://vlislab22.github.io/DreamInit/ |
| 2024 |         | Feed Forward       | [NovelGS: Consistent Novel-view Denoising via Large Gaussian Reconstruction Model](https://arxiv.org/abs/2411.16779) | N/A |



# Overview of Existing Methods of Decetion for 3DGS Semantic Scene Understanding

Legend: *‘Centricity’ refers to scene and/or object-centric datasets, respectively denoted with S and O above.*

| Methods   | Venue     | #Domain| Detail                                   |
|---------------------|-----------|--------------------|---------------------------|
|     3D Vision-Language Gaussian Splatting           | CVPR 2023 | Segmentation & Detection     |        https://arxiv.org/abs/2410.07577           |
