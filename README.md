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
| 2024 | CVPR |   LangSplat   |        [LangSplat: 3D Language Gaussian Splatting](http://arxiv.org/abs/2312.16084)   |   [Code](https://langsplat.github.io/)    |
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



# Overview of Existing Methods of Editing for 3DGS Semantic Scene Understanding

| Year | Venue | Acronym | Title | Project/Code |
|------|-------|---------|-------|--------------|
| 2024 | ECCV | GaussianGrouping | [Gaussian grouping: Segment and edit anything in 3d scenes](https://link.springer.com/chapter/10.1007/978-3-031-73397-0_10) | [Code](https://langsplat.github.io/) |
| 2024 | ACM TOG | TIP-Editor | [Tip-editor: An accurate 3d editor following both text-prompts and image-prompts](https://dl.acm.org/doi/abs/10.1145/3658205) | [Code](https://zjy526223908.github.io/TIP-Editor/) |
| 2025 | ICLR | DreamCatalyst | [DreamCatalyst: Fast and High-Quality 3D Editing via Controlling Editability and Identity Preservation](https://arxiv.org/abs/2407.11394) | [Code](https://dream-catalyst.github.io/) |
| 2024 | CVPR | GaussianEditor | [Gaussianeditor: Swift and controllable 3d editing with gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Chen_GaussianEditor_Swift_and_Controllable_3D_Editing_with_Gaussian_Splatting_CVPR_2024_paper.html) | [Code](https://buaacyw.github.io/gaussian-editor/) |
| 2024 | ECCV | DGE | [Dge: Direct gaussian 3d editing by consistent multi-view editing](https://link.springer.com/chapter/10.1007/978-3-031-72904-1_5) | [Code](https://silent-chen.github.io/DGE/) |
| 2024 | N/A | GaussianVTON | [Gaussianvton: 3d human virtual try-on via multi-stage gaussian splatting editing with image prompting](https://arxiv.org/abs/2405.07472) | [Code](https://haroldchen19.github.io/gsvton/) |
| 2024 | N/A | Texture-GS | [Texture-GS: Disentangling the Geometry and Texture for 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.10050) | N/A |
| 2024 | N/A | GScream | [GScream: Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal](https://dl.acm.org/doi/10.1145/3681758.3698002) | N/A |
| 2024 | SA '24 | StyleGaussian | [StyleGaussian: Instant 3D Style Transfer with Gaussian Splatting](http://arxiv.org/abs/2404.13679) | [Code](https://kunhao-liu.github.io/StyleGaussian/) |
| 2024 | N/A | Infusion | [InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior](http://arxiv.org/abs/2404.11613) | [Code](https://johanan528.github.io/Infusion/) |
| 2024 | N/A | StyleSplat | [Stylesplat: 3d object style transfer with gaussian splatting](https://arxiv.org/abs/2407.09473) | N/A |
| 2024 | N/A | StylizedGS | [Stylizedgs: Controllable stylization for 3d gaussian splatting](https://arxiv.org/abs/2404.05220) | N/A |
| 2025 | CVPR | EditSplat | [EditSplat: Multi-View Fusion and Attention-Guided Optimization for View-Consistent 3D Scene Editing with 3D Gaussian Splatting](http://arxiv.org/abs/2412.11520) | [Code](https://kuai-lab.github.io/editsplat2024/) |
| 2024 | CVPR | GaussianEditorText | [Gaussianeditor: Editing 3d gaussians delicately with text instructions](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_GaussianEditor_Editing_3D_Gaussians_Delicately_with_Text_Instructions_CVPR_2024_paper.html) | [Code](https://gaussianeditor.github.io/) |
| 2024 | ECCV | GaussCtrl | [GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.08733) | [Code](https://gaussctrl.active.vision/) |
| 2024 | N/A | SemanticSplatStylization | [SemanticSplatStylization: Semantic scene stylization based on 3D Gaussian splatting and class-based style transfer](http://arxiv.org/abs/2404.11613) | N/A |
| 2024 | N/A | TIGER | [TIGER: Text-Instructed 3D Gaussian Retrieval and Coherent Editing](http://arxiv.org/abs/2405.14455) | [Code](https://xutanxing.github.io/TIGER/) |
| 2024 | IET Image Processing | PointnMove | [Point'n Move: Interactive scene object manipulation on Gaussian splatting radiance fields](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.13190) | N/A |
| 2024 | N/A | FruitNinja | [FruitNinja: 3D Object Interior Texture Generation with Gaussian Splatting](http://arxiv.org/abs/2411.12089) | N/A |
| 2024 | N/A | 360-INPAINTR | [360-INPAINTR: REFERENCE-GUIDED 3D INPAINTING FOR UNBOUNDED SCENES](https://openreview.net/pdf/ee332494bcd7f9e4b66494d65eb850f61e9a0b43.pdf) | N/A |

| 2024 | ACM MM     | N/A          | [3D Gaussian Editing with A Single Image](https://dl.acm.org/doi/pdf/10.1145/3664647.3680858) | N/A |
| 2024 | ECCV       | 3DEgo        | [3DEgo: 3D Editing on the Go!](https://arxiv.org/pdf/2407.10102) | [Code](https://3dego.github.io/) |
| 2024 | N/A        | 3DitScene    | [3DitScene: Editing Any Scene via Language-guided Disentangled Gaussian Splatting](https://arxiv.org/abs/2405.18424) | [Code](https://zqh0253.github.io/3DitScene/) |
| 2024 | N/A        | 3DSceneEditor | [3dsceneeditor: Controllable 3d scene editing with gaussian splatting](https://arxiv.org/abs/2412.01583) | [Code](https://ziyangyan.github.io/3DSceneEditor/) |
| 2024 | N/A        | ArtNVG       | [ArtNVG: Content-Style Separated Artistic Neighboring-View Gaussian Stylization](https://arxiv.org/abs/2412.18783) | N/A |
| 2024 | ACM TOG    | TIP-Editor   | [Tip-editor: An accurate 3d editor following both text-prompts and image-prompts](https://dl.acm.org/doi/abs/10.1145/3658205) | [Code](https://zjy526223908.github.io/TIP-Editor/) |
| 2024 | N/A        | N/A          | [Diffusion-Based Attention Warping for Consistent 3D Scene Editing](https://arxiv.org/abs/2412.07984) | [Code](https://attention-warp.github.io/) |
| 2024 | NeurIPS    | D-MiSo       | [D-miso: Editing dynamic 3d scenes using multi-gaussians soup](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c32319f4868da7613d78af9993100e42-Abstract-Conference.html) | [Code](https://github.com/waczjoan/D-MiSo) |
| 2025 | N/A        | N/A          | [Drag Your Gaussian: Effective Drag-Based Editing with Score Distillation for 3D Gaussian Splatting](https://arxiv.org/abs/2501.18672) | [Code](https://quyans.github.io/Drag-Your-Gaussian/) |
| 2025 | N/A        | Dragen3D     | [Dragen3D: Multiview Geometry Consistent 3D Gaussian Generation with Drag-Based Control](https://arxiv.org/abs/2502.16475) | N/A |
| 2024 | N/A        | DynamicAvatars | [DynamicAvatars: Accurate Dynamic Facial Avatars Reconstruction and Precise Editing with Diffusion Models](https://arxiv.org/abs/2411.15732) | N/A |
| 2024 | N/A        | N/A          | [Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting](https://arxiv.org/abs/2406.02541) | [Code](https://video-3dgs-project.github.io/) |
| 2024 | N/A        | N/A          | [Gaussian splatting in style](https://arxiv.org/abs/2403.08498) | N/A |
| 2024 | ACM MM     | GGAvatar     | [GGAvatar: Reconstructing Garment-Separated 3D Gaussian Splatting Avatars from Monocular Video](https://dl.acm.org/doi/abs/10.1145/3696409.3700241) | [Code](https://github.com/J-X-Chen/GGAvatar/) |
| 2024 | N/A        | GSEdit       | [Gsedit: Efficient text-guided editing of 3d objects via gaussian splatting](https://arxiv.org/abs/2403.05154) | N/A |
| 2024 | Computer Graphics Forum | GSEditPro | [GSEditPro: 3D Gaussian Splatting Editing with Attention‐based Progressive Localization](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15215) | N/A |
| 2024 | Computer Graphics Forum | G-Style   | [*𝒢*‐Style: Stylized Gaussian Splatting](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15259) | N/A |
| 2024 | N/A        | GS-VTON     | [GS-VTON: Controllable 3D Virtual Try-on with Gaussian Splatting](https://arxiv.org/abs/2410.05259) | [Code](https://yukangcao.github.io/GS-VTON/) |
| 2024 | N/A        | ICE-G       | [Ice-g: Image conditional editing of 3d gaussian splats](https://arxiv.org/abs/2406.08488) | [Code](https://ice-gaussian.github.io/) |
| 2024 | N/A        | InstantStyleGaussian | [Instantstylegaussian: Efficient art style transfer with 3d gaussian splatting](https://arxiv.org/abs/2408.04249) | N/A |
| 2024 | ECCV       | GScream     | [Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal](https://link.springer.com/chapter/10.1007/978-3-031-72646-0_1) | [Code](https://w-ted.github.io/publications/gscream/) |
| 2024 | N/A        | N/A         | [Localized Gaussian Splatting Editing with Contextual Awareness](https://arxiv.org/abs/2408.00083) | N/A |
| 2025 | N/A        | MultiDreamer3D | [MultiDreamer3D: Multi-concept 3D Customization with Concept-Aware Diffusion Guidance](https://arxiv.org/abs/2501.13449) | N/A |
| 2024 | N/A        | MvDrag3D    | [MvDrag3D: Drag-based Creative 3D Editing via Multi-view Generation-Reconstruction Priors](https://arxiv.org/abs/2410.16272) | [Code](https://chenhonghua.github.io/MyProjects/MvDrag3D/) |
| 2024 | N/A        | NeuralSurfacePriors | [Neural Surface Priors for Editable Gaussian Splatting](https://arxiv.org/abs/2411.18311) | [Code](https://github.com/WJakubowska/NeuralSurfacePriors) |
| 2024 | N/A        | PERSE       | [PERSE: Personalized 3D Generative Avatars from A Single Portrait](https://arxiv.org/abs/2412.21206) | [Code](https://hyunsoocha.github.io/perse/) |
| 2024 | SIGGRAPH   | PortraitGen | [Portrait video editing empowered by multimodal generative priors](https://dl.acm.org/doi/abs/10.1145/3680528.3687601) | [Code](https://ustc3dv.github.io/PortraitGen/) |
| 2024 | NeurIPS    | ProEdit     | [ProEdit: Simple Progression is All You Need for High-Quality 3D Scene Editing](https://arxiv.org/abs/2411.05006) | [Code](https://immortalco.github.io/ProEdit/) |
| 2024 | N/A        | ProGDF      | [ProGDF: Progressive Gaussian Differential Field for Controllable and Flexible 3D Editing](https://arxiv.org/abs/2412.08152) | N/A |
| 2024 | NeurIPS    | ReGS        | [ReGS: Reference-based Controllable Scene Stylization with Gaussian Splatting](https://proceedings.neurips.cc/paper_files/paper/2024/hash/076c1fa639a7190e216e734f0a1b3e7b-Abstract-Conference.html) | N/A |
| 2024 | N/A        | RefFusion   | [Reffusion: Reference adapted diffusion models for 3d scene inpainting](https://arxiv.org/abs/2404.10765) | [Code](https://reffusion.github.io/) |
| 2024 | N/A        | SGSST       | [SGSST: Scaling Gaussian Splatting StyleTransfer](https://arxiv.org/abs/2412.03371) | N/A |
| 2024 | N/A        | Trame       | [Trame: Trajectory-anchored multi-view editing for text-guided 3d gaussian splatting manipulation](https://arxiv.org/abs/2407.02034) | N/A |
| 2024 | ECCV       | N/A         | [View-consistent 3d editing with gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72761-0_23) | [Code](https://vcedit.github.io/) |
| 2024 | ECCV       | WaSt-3D     | [Wast-3d: Wasserstein-2 distance for scene-to-scene stylization on 3d gaussians](https://link.springer.com/chapter/10.1007/978-3-031-72664-4_17) | [Code](https://compvis.github.io/wast3d/) |





# Overview of Existing Methods of Generation for 3DGS Semantic Scene Understanding

| Year | Venue | Acronym | Title | Project/Code |
|------|-------|---------|-------|---------|
| 2024 | N/A   | LayoutYour3D | [Layout-your-3D: Controllable and Precise 3D Generation with 2D Blueprint](https://arxiv.org/abs/2410.15391) | [Code](https://colezwhy.github.io/layoutyour3d/) |
| 2024 | N/A   | GraphCanvas | [Graph Canvas for Controllable 3D Scene Generation](https://arxiv.org/abs/2412.00091) | [Code](N/A) |
| 2024 | N/A   | LayerPano3D | [Layerpano3d: Layered 3d panorama for hyper-immersive scene generation](https://arxiv.org/abs/2408.13252) | [Code](https://layerpano3d-web.github.io/) |
| 2024 | N/A   | SceneDreamer360 | [Scenedreamer360: Text-driven 3d-consistent scene generation with panoramic gaussian splatting](https://arxiv.org/abs/2408.13711) | [Code](https://github.com/liwrui/SceneDreamer360) |
| 2023 | N/A   | DreamGaussian | [Dreamgaussian: Generative gaussian splatting for efficient 3d content creation](https://arxiv.org/abs/2309.16653) | [Code](https://dreamgaussian.github.io/) |
| 2024 | CVPR  | GSGen | [Text-to-3d using gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Chen_Text-to-3D_using_Gaussian_Splatting_CVPR_2024_paper.html) | [Code](https://github.com/gsgen3d/gsgen) |
| 2024 | CVPR  | GaussianDreamer | [Gaussiandreamer: Fast generation from text to 3d gaussians by bridging 2d and 3d diffusion models](http://openaccess.thecvf.com/content/CVPR2024/html/Yi_GaussianDreamer_Fast_Generation_from_Text_to_3D_Gaussians_by_Bridging_CVPR_2024_paper.html) | [Code](https://arxiv.org/abs/2406.18462) |
| 2024 | N/A   | GaussianDreamerPro | [Gaussiandreamerpro: Text to manipulable 3d gaussians with highly enhanced quality](https://arxiv.org/abs/2406.18462) | [Code](https://arxiv.org/abs/2406.18462) |
| 2024 | N/A   | CompGS | [CompGS: Unleashing 2D Compositionality for Compositional Text-to-3D via Dynamically Optimizing 3D Gaussians](https://arxiv.org/abs/2410.20723) | [Code](https://chongjiange.github.io/compgs.html) |
| 2023 | N/A   | CG3D | [Cg3d: Compositional generation for text-to-3d via gaussian splatting](https://arxiv.org/abs/2311.17907) | [Code](https://asvilesov.github.io/CG3D/) |
| 2023 | N/A   | StableDreamer | [Stabledreamer: taming noisy score distillation sampling for text-to-3d](https://arxiv.org/abs/2312.02189) | [Code](N/A) |
| 2024 | ECCV  | GCS-BEG | [Connecting consistency distillation to score distillation for text-to-3d generation](https://link.springer.com/chapter/10.1007/978-3-031-72775-7_16) | [Code](https://github.com/LMozart/ECCV2024-GCS-BEG) |
| 2024 | N/A   | DreamMapping | [DreamMapping: High-Fidelity Text-to-3D Generation via Variational Distribution Mapping](https://arxiv.org/abs/2409.05099) | [Code](N/A) |
| 2024 | CVPR  | HumanGaussian | [Humangaussian: Text-driven 3d human generation with gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Liu_HumanGaussian_Text-Driven_3D_Human_Generation_with_Gaussian_Splatting_CVPR_2024_paper.html) | [Code](https://alvinliu0.github.io/projects/HumanGaussian) |
| 2024 | ECCV  | DreamScene | [Dreamscene: 3d gaussian-based text-to-3d scene generation via formation pattern sampling](https://link.springer.com/chapter/10.1007/978-3-031-72904-1_13) | [Code](https://dreamscene-project.github.io/) |
| 2024 | CVPR  | LucidDreamer | [Luciddreamer: Towards high-fidelity text-to-3d generation via interval score matching](http://openaccess.thecvf.com/content/CVPR2024/html/Liang_LucidDreamer_Towards_High-Fidelity_Text-to-3D_Generation_via_Interval_Score_Matching_CVPR_2024_paper.html) | [Code](https://github.com/EnVision-Research/LucidDreamer) |
| 2024 | N/A   | DreamerXL | [Dreamer XL: Towards High-Resolution Text-to-3D Generation via Trajectory Score Matching](https://arxiv.org/abs/2405.11252) | [Code](https://github.com/xingy038/Dreamer-XL) |
| 2025 | N/A   | GaussianMotion | [GaussianMotion: End-to-End Learning of Animatable Gaussian Avatars with Pose Guidance from Text](https://arxiv.org/abs/2502.11642) | [Code](N/A) |
| 2024 | N/A   | MVGaussian | [MVGaussian: High-Fidelity text-to-3D Content Generation with Multi-View Guidance and Surface Densification](https://arxiv.org/abs/2409.06620) | [Code](https://mvgaussian.github.io/) |
| 2024 | N/A   | GradeADreamer | [GradeADreamer: Enhanced Text-to-3D Generation Using Gaussian Splatting and Multi-View Diffusion](https://arxiv.org/abs/2406.09850) | [Code](https://github.com/trapoom555/GradeADreamer) |
| 2024 | ICML  | GALA3D | [Gala3d: Towards text-to-3d complex scene generation via layout-guided generative gaussian splatting](https://arxiv.org/abs/2402.07207) | [Code](https://gala3d.github.io/) |
| 2024 | 3DV   | MVControl | [Controllable text-to-3D generation via surface-aligned Gaussian splatting](https://arxiv.org/abs/2403.09981) | [Code](https://lizhiqi49.github.io/MVControl/) |
| 2023 | N/A   | Text2Immersion | [Text2immersion: Generative immersive scene with 3d gaussians](https://arxiv.org/abs/2312.09242) | [Code](https://ken-ouyang.github.io/text2immersion/index.html) |
| 2023 | ICCV  | Text2Room | [Text2room: Extracting textured 3d meshes from 2d text-to-image models](http://openaccess.thecvf.com/content/ICCV2023/html/Hollein_Text2Room_Extracting_Textured_3D_Meshes_from_2D_Text-to-Image_Models_ICCV_2023_paper.html) | [Code](https://lukashoel.github.io/text-to-room/) |
| 2024 | 3DV    | Realmdreamer        | [Realmdreamer: Text-driven 3d scene generation with inpainting and depth diffusion](https://arxiv.org/abs/2404.07199) | [Code](https://realmdreamer.github.io/) |
| 2024 | CVPR   | WonderJourney       | [Wonderjourney: Going from anywhere to everywhere](http://openaccess.thecvf.com/content/CVPR2024/html/Yu_WonderJourney_Going_from_Anywhere_to_Everywhere_CVPR_2024_paper.html) | [Code](https://kovenyu.com/wonderjourney/) |
| 2024 | N/A    | Art3D               | [Art3d: 3d gaussian splatting for text-guided artistic scenes generation](https://arxiv.org/abs/2405.10508) | [Code](N/A) |
| 2024 | N/A    | FastScene           | [Fastscene: Text-driven fast 3d indoor scene generation via panoramic gaussian splatting](https://arxiv.org/abs/2405.05768) | [Code](N/A) |
| 2024 | N/A    | HoloDreamer         | [Holodreamer: Holistic 3d panoramic world generation from text descriptions](https://arxiv.org/abs/2407.15187) | [Code](N/A) |
| 2024 | ECCV   | DreamScene360       | [Dreamscene360: Unconstrained text-to-3d scene generation with panoramic gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72658-3_19) | [Code](https://dreamscene360.github.io/) |
| 2024 | ECCV   | VFusion3D           | [Vfusion3d: Learning scalable 3d generative models from video diffusion models](https://link.springer.com/chapter/10.1007/978-3-031-72627-9_19) | [Code](https://junlinhan.github.io/projects/vfusion3d.html) |
| 2024 | N/A    | BrightDreamer       | [Brightdreamer: Generic 3d gaussian generative framework for fast text-to-3d synthesis](https://arxiv.org/abs/2403.11273) | [Code](https://vlislab22.github.io/BrightDreamer/) |
| 2025 | N/A    | Triflow             | [Taming Feed-forward Reconstruction Models as Latent Encoders for 3D Generative Models](https://arxiv.org/abs/2501.00651) | [Code](https://triflow.github.io/) |
| 2024 | N/A    | GaussianAnything    | [GaussianAnything: Interactive Point Cloud Latent Diffusion for 3D Generation](https://arxiv.org/abs/2411.08033) | [Code](https://nirvanalan.github.io/projects/ga/) |
| 2024 | N/A    | Flex3D              | [Flex3d: Feed-forward 3d generation with flexible reconstruction model and input view curation](https://arxiv.org/abs/2410.00890) | [Code](https://junlinhan.github.io/projects/flex3d/) |
| 2024 | WACV   | GANFusion           | [GANFusion: Feed-Forward Text-to-3D with Diffusion in GAN Space](https://arxiv.org/abs/2412.16717) | [Code](https://ganfusion.github.io/) |
| 2024 | N/A    | Prometheus          | [Prometheus: 3D-Aware Latent Diffusion Models for Feed-Forward Text-to-3D Scene Generation](https://arxiv.org/abs/2412.21117) | [Code](https://github.com/XDimLab/Prometheus) |
| 2025 | CVPR   | Turbo3D             | [Turbo3D: Ultra-fast Text-to-3D Generation](https://arxiv.org/abs/2412.04470) | [Code](https://turbo-3d.github.io/) |
| 2024 | IJCV   | Hyper3DG         | [Hyper-3dg: Text-to-3d gaussian generation via hypergraph](https://link.springer.com/article/10.1007/s11263-024-02298-y) | [Code](https://github.com/yjhboy/Hyper3DG) |
| 2024 | ECCV   | LGM              | [Lgm: Large multi-view gaussian model for high-resolution 3d content creation](https://link.springer.com/chapter/10.1007/978-3-031-73235-5_1) | [Code](https://me.kiui.moe/lgm/) |
| 2024 | N/A    | N/A              | [Atlas Gaussians Diffusion for 3D Generation](https://arxiv.org/abs/2408.13055) | N/A |
| 2024 | ECCV   | GVGEN            | [Gvgen: Text-to-3d generation with volumetric representation](https://link.springer.com/chapter/10.1007/978-3-031-73242-3_26) | [Code](https://sotamak1r.github.io/gvgen/) |
| 2024 | N/A    | N/A              | [Text-to-3D Gaussian Splatting with Physics-Grounded Motion Generation](https://arxiv.org/abs/2412.05560) | N/A |
| 2025 | N/A    | LAYOUTDREAMER    | [LAYOUTDREAMER: Physics-guided Layout for Text-to-3D Compositional Scene Generation](https://arxiv.org/abs/2502.01949) | N/A |
| 2024 | N/A    | DreamScape       | [DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling](https://arxiv.org/abs/2404.09227) | N/A |
| 2024 | CVPR   | Hash3D           | [Hash3d: Training-free acceleration for 3d generation](https://arxiv.org/abs/2404.06091) | [Code](https://adamdad.github.io/hash3D/) |
| 2024 | N/A    | DreamPolisher    | [Dreampolisher: Towards high-quality text-to-3d generation via geometric diffusion](https://arxiv.org/abs/2403.17237) | [Code](https://yuanze-lin.me/DreamPolisher_page/) |
| 2024 | NeurIPS| GSGAN            | [GSGAN: Adversarial Learning for Hierarchical Generation of 3D Gaussian Splats](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7d90c28e7820709792d969211815a2b3-Abstract-Conference.html) | [Code](https://hse1032.github.io/gsgan) |
| 2024 | ACM MM | Sketch3D         | [Sketch3D: Style-Consistent Guidance for Sketch-to-3D Generation](https://dl.acm.org/doi/abs/10.1145/3664647.3680641) | N/A |
| 2024 | NeurIPS| Wild-GS          | [Wild-gs: Real-time novel view synthesis from unconstrained photo collections](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bb11f79ad86f5e33e2a7c850cbdfed42-Abstract-Conference.html) | [Code](https://github.com/XuJiacong/Wild-GS) |
| 2025 | N/A    | GSV3D            | [GSV3D: Gaussian Splatting-based Geometric Distillation with Stable Video Diffusion for Single-Image 3D Object Generation](https://arxiv.org/abs/2503.06136) | N/A |
| 2024 | ECCV   | FSGS             | [Fsgs: Real-time few-shot view synthesis using gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72933-1_9) | [Code](https://zehaozhu.github.io/FSGS/) |
| 2024 | N/A    | PanoDreamer      | [PanoDreamer: 3D Panorama Synthesis from a Single Image](https://arxiv.org/abs/2412.04827) | [Code](https://people.engr.tamu.edu/nimak/Papers/PanoDreamer/index.html) |
| 2024 | N/A    | ScalingGaussian  | [ScalingGaussian: Enhancing 3D Content Creation with Generative Gaussian Splatting](https://arxiv.org/abs/2407.19035) | N/A |
| 2024 | N/A    | Physics3D        | [Physics3d: Learning physical properties of 3d gaussians via video diffusion](https://arxiv.org/abs/2406.04338) | [Code](https://liuff19.github.io/Physics3D/) |
| 2024 | N/A    | N/A              | [Enhancing Single Image to 3D Generation using Gaussian Splatting and Hybrid Diffusion Priors](https://arxiv.org/abs/2410.09467) | N/A |
| 2024 | N/A    | GECO             | [GECO: Generative Image-to-3D within a SECOnd](https://arxiv.org/abs/2405.20327) | N/A |
| 2024 | NeurIPS| ProlificDreamer  | [Prolificdreamer: High-fidelity and diverse text-to-3d generation with variational score distillation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/1a87980b9853e84dfb295855b425c262-Abstract-Conference.html) | [Code](https://ml.cs.tsinghua.edu.cn/prolificdreamer/) |
| 2024 | N/A    | DreamPhysics     | [Dreamphysics: Learning physical properties of dynamic 3d gaussians with video diffusion priors](https://arxiv.org/abs/2406.01476) | [Code](https://github.com/tyhuang0428/DreamPhysics) |
| 2023 | N/A    | Luciddreamer     | [Luciddreamer: Domain-free generation of 3d gaussian splatting scenes](https://arxiv.org/abs/2311.13384) | [Code](https://github.com/luciddreamer-cvlab/LucidDreamer) |
| 2024 | N/A    | VistaDream       | [VistaDream: Sampling multiview consistent images for single-view scene reconstruction](https://arxiv.org/abs/2410.16892) | [Code](https://github.com/WHU-USI3DV/VistaDream) |
| 2024 | N/A    | N/A              | [Multi-view Geometry-Aware Diffusion Transformer for Indoor Novel View Synthesis](https://openreview.net/forum?id=8hpJBfBjlZ) | N/A |
| 2024 | NeurIPS | DiffGS           | [Diffgs: Functional gaussian splatting diffusion](https://proceedings.neurips.cc/paper_files/paper/2024/hash/41fb2ecb5b7d1b505bca787de0a603dc-Abstract-Conference.html) | [Code](https://junshengzhou.github.io/DiffGS/) |
| 2024 | NeurIPS | Era3D            | [Era3d: high-resolution multiview diffusion using efficient row-wise attention](https://proceedings.neurips.cc/paper_files/paper/2024/hash/65a723bf7d8dad838c09178270d30e80-Abstract-Conference.html) | [Code](https://penghtyx.github.io/Era3D/) |
| 2025 | CVPR    | Splatter-360     | [Splatter-360: Generalizable 360 Gaussian Splatting for Wide-baseline Panoramic Images](https://arxiv.org/abs/2412.06250) | [Code](https://3d-aigc.github.io/Splatter-360/) |
| 2024 | N/A    | AGG              | [Agg: Amortized generative 3d gaussians for single image to 3d](https://arxiv.org/abs/2401.04099) | [Code](https://ir1d.github.io/AGG/) |
| 2024 | NeurIPS | HumanSplat       | [Humansplat: Generalizable single-image human gaussian splatting with structure priors](https://proceedings.neurips.cc/paper_files/paper/2024/hash/87affd2029375d1be123ccdab5334c55-Abstract-Conference.html) | [Code](https://humansplat.github.io/) |
| 2024 | N/A    | TriplaneGaussian | [Triplane meets gaussian splatting: Fast and generalizable single-view 3d reconstruction with transformers](http://openaccess.thecvf.com/content/CVPR2024/html/Zou_Triplane_Meets_Gaussian_Splatting_Fast_and_Generalizable_Single-View_3D_Reconstruction_CVPR_2024_paper.html) | [Code](https://zouzx.github.io/TriplaneGaussian/) |
| 2024 | ECCV    | GS-LRM           | [Gs-lrm: Large reconstruction model for 3d gaussian splatting](https://link.springer.com/chapter/10.1007/978-3-031-72670-5_1) | [Code](https://sai-bi.github.io/project/gs-lrm/) |
| 2024 | ECCV    | GRM              | [Grm: Large gaussian reconstruction model for efficient 3d reconstruction and generation](https://link.springer.com/content/pdf/10.1007/978-3-031-72633-0_1.pdf) | [Code](https://github.com/justimyhxu/grm) |
| 2024 | ACM MM  | Hi3D             | [Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models](https://dl.acm.org/doi/abs/10.1145/3664647.3681634) | [Code](https://github.com/yanghb22-fdu/Hi3D-Official) |
| 2024 | CVPR    | Ouroboros3D      | [Ouroboros3d: Image-to-3d generation via 3d-aware recursive diffusion](https://arxiv.org/abs/2406.03184) | [Code](https://costwen.github.io/Ouroboros3D/) |
| 2024 | N/A    | DiffusionGS      | [Baking gaussian splatting into diffusion denoiser for fast and scalable single-stage image-to-3d generation](https://arxiv.org/abs/2411.14384) | [Code](https://caiyuanhao1998.github.io/project/DiffusionGS/) |
| 2024 | ACM MM  | N/A              | [Large point-to-gaussian model for image-to-3d generation](https://dl.acm.org/doi/abs/10.1145/3664647.3680920) | N/A |
| 2024 | N/A    | GaussianPainter  | [GaussianPainter: Painting Point Cloud into 3D Gaussians with Normal Guidance](https://arxiv.org/abs/2412.17715) | [Code](https://github.com/zhou745/GaussianPainter) |
| 2024 | N/A    | Gaussianstego    | [Gaussianstego: A generalizable stenography pipeline for generative 3d gaussians splatting](https://arxiv.org/abs/2407.01301) | [Code](https://gaussian-stego.github.io/) |
| 2024 | N/A    | GeoGS3D          | [GeoGS3D: Single-view 3D Reconstruction via Geometric-aware Diffusion Model and Gaussian Splatting](https://arxiv.org/abs/2403.10242) | [Code](https://qjfeng.net/GeoGS3D/) |
| 2024 | N/A    | Cycle3D          | [Cycle3d: High-quality and consistent image-to-3d generation via generation-reconstruction cycle](https://arxiv.org/abs/2407.19548) | [Code](https://pku-yuangroup.github.io/Cycle3D/) |
| 2024 | ACM MM  | DreamInit        | [A general framework to boost 3d gs initialization for text-to-3d generation by lexical richness](https://dl.acm.org/doi/abs/10.1145/3664647.3680740) | [Code](https://vlislab22.github.io/DreamInit/) |
| 2024 | N/A    | NovelGS          | [NovelGS: Consistent Novel-view Denoising via Large Gaussian Reconstruction Model](https://arxiv.org/abs/2411.16779) | N/A |
