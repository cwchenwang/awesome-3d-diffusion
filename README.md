# Awesome 3D Diffusion
This repo collects papers that use diffusion models for 3D generation.

🔥🔥🔥 Check out our collection of papers on 4D generation: https://github.com/cwchenwang/awesome-4d-generation

**Note**: This list is far from complete, please directly open a pull request if you want to add a paper or modify the information. You don't need to open an issue.

## Table of Contents
- [2D Diffusion with Pretraining](#2d-diffusion-with-pretraining)
  * [Text-to-3D Object Generation](#text-to-3d-object-generation)
  * [Compositional or Scene Generation](#text-to-3d-scene-generation)
  * [Image-to-3D](#image-to-3d)
  * [Human and Animal](#human-and-animal)
  * [3D Editing](#3d-editing)
  * [Texturing](#texturing)
  * [Multi-view Diffusion](#multi-view-diffusion)
- [2D Diffusion without Pretraining](#2d-diffusion-without-pretraining)
  * [3D Objects](#3d-objects)
  * [3D Scenes](#3d-scenes)
- [Diffusion in 3D Space](#diffusion-in-3d-space)
  * [Explicit Representation](#explicit-representation)
  * [Implicit Representation](#implicit-representation)
  * [Triplane](#triplane)
  * [Latent Representation](#latent-representation)
- [Diffusion for Motion](#diffusion-for-motion)
  * [Human Motion](#human-motion)



## 2D Diffusion with Pretraining
### Text-to-3D Object Generation
- [DreamFusion: Text-to-3D using 2D Diffusion](https://arxiv.org/abs/2209.14988), Poole et al., Arxiv 2022
- [Magic3D: High-Resolution Text-to-3D Content Creation](https://arxiv.org/abs/2211.10440), Lin et al., Arxiv 2022
- [Score jacobian chaining: Lifting pretrained 2d diffusion models for 3d generation](https://arxiv.org/abs/2212.00774), Wang et al., Arxiv 2022
- [Fantasia3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation](https://arxiv.org/abs/2303.13873), Chen et al., Arxiv 2023
- [Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation](https://arxiv.org/abs/2303.07937), Seo et al., Arxiv 2023
- [DITTO-NeRF: Diffusion-based Iterative Text To Omni-directional 3D Model](https://arxiv.org/abs/2304.02827), Seo et al., Arxiv 2023
- [TextMesh: Generation of Realistic 3D Meshes From Text Prompts](https://arxiv.org/abs/2304.12439), Tsalicoglou et al., Arxiv 2023
- [Let 2D Diffusion Model Know 3D-Consistency for Robust Text-to-3D Generation](https://arxiv.org/abs/2303.07937), Seo et al., Arxiv 2023
- [Text-driven Visual Synthesis with Latent Diffusion Prior](https://arxiv.org/abs/2302.08510), Liao et al., Arxiv 2023
- [Re-imagine the Negative Prompt Algorithm: Transform 2D Diffusion into 3D, alleviate Janus problem and Beyond](https://arxiv.org/abs/2304.04968), Armandpour et al., Arxiv 2023
- [HiFA: High-fidelity Text-to-3D with Advanced Diffusion Guidance](https://arxiv.org/abs/2305.18766), Zhu and Zhuang, Arxiv 2023
- [ATT3D: Amortized Text-to-3D Object Synthesis](https://arxiv.org/abs/2306.07349), Lorraine et al., Arxiv 2023
- [PanoGen: Text-Conditioned Panoramic Environment Generation for Vision-and-Language Navigation](https://arxiv.org/abs/2305.19195), Li and Bansal, Arxiv 2023
- [ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation](https://arxiv.org/abs/2305.16213), Wang et al., NeurIPS 2023.
- [DreamTime: An Improved Optimization Strategy for Text-to-3D Content Creation](http://arxiv.org/abs/2306.12422), Huang et al., Arxiv 2023
- [EfficientDreamer: High-Fidelity and Robust 3D Creation via Orthogonal-view Diffusion Prior](https://arxiv.org/abs/2308.13223), Zhao et al., Arxiv 2023
- [SweetDreamer: Aligning Geometric Priors in 2D Diffusion for Consistent Text-to-3D](https://arxiv.org/abs/2309.03453), Li et al., Arxiv 2023
- [DreamCraft3D: Hierarchical 3D Generation with Bootstrapped Diffusion Prior](http://arxiv.org/abs/2310.16818), Sun et al., Arxiv 2023
- [Text-to-3D with Classifier Score Distillation](http://arxiv.org/abs/2310.19415), Yu et al., Arxiv 2023
- [Instant3D: Instant Text-to-3D Generation](http://arxiv.org/abs/2311.08403), Li et al., Arxiv 2023
- [HyperFields: Towards Zero-Shot Generation of NeRFs from Text](http://arxiv.org/abs/2310.17075), Babu et al., ICML 2024
- [DreamSpace: Dreaming Your Room Space with Text-Driven Panoramic Texture Propagation](http://arxiv.org/abs/2310.13119), Yang et al., Arxiv 2023
- [Enhancing High-Resolution 3D Generation through Pixel-wise Gradient Clipping](http://arxiv.org/abs/2310.12474), Pan et al., Arxiv 2023
- [GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors](http://arxiv.org/abs/2310.08529), Yi et al., Arxiv 2023
- [LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2311.13384), Chung et al., Arxiv 2023
- [CG3D: Compositional Generation for Text-to-3D via Gaussian Splatting](http://arxiv.org/abs/2311.17907), Vilesov et al., Arxiv 2023
- [LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching](http://arxiv.org/abs/2311.11284), Liang et al., Arxiv 2023
- [StableDreamer: Taming Noisy Score Distillation Sampling for Text-to-3D](http://arxiv.org/abs/2312.02189), Guo et al., Arxiv 2023
- [DreamComposer: Controllable 3D Object Generation via Multi-View Conditions](http://arxiv.org/abs/2312.03611), Yang et al., Arxiv 2023
- [GraphDreamer: Compositional 3D Scene Synthesis from Scene Graphs](http://arxiv.org/abs/2312.00093), Gao et al., Arxiv 2023
- [X-Dreamer: Creating High-quality 3D Content by Bridging the Domain Gap Between Text-to-2D and Text-to-3D Generation](http://arxiv.org/abs/2312.00085), Ma et al., Arxiv 2023
- [HyperDreamer: Hyper-Realistic 3D Content Generation and Editing from a Single Image](https://arxiv.org/abs/2312.04543), Wu et al., SIGGRAPH ASIA 2023
- [RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D](https://arxiv.org/abs/2311.16918), Qiu et al., Arxiv 2023
- [Text-to-3D Generation with Bidirectional Diffusion using both 2D and 3D priors](https://arxiv.org/abs/2312.04963), Ding et al., Arxiv 2023
- [Sherpa3D: Boosting High-Fidelity Text-to-3D Generation via Coarse 3D Prior](https://arxiv.org/abs/2312.06655), Liu et al., Arxiv 2023
- [DreamPropeller: Supercharge Text-to-3D Generation with Parallel Sampling](https://arxiv.org/abs/2311.17082), Zhou et al., Arxiv 2023
- [UniDream: Unifying Diffusion Priors for Relightable Text-to-3D Generation](https://arxiv.org/abs/2312.08754), Liu et al., Arxiv 2023
- [Stable Score Distillation for High-Quality 3D Generation](https://arxiv.org/abs/2312.09305), Tang et al., Arxiv 2023
- [Text-Image Conditioned Diffusion for Consistent Text-to-3D Generation](https://arxiv.org/abs/2312.11774), He et al., Arxiv 2023
- [HexaGen3D: StableDiffusion is just one step away from Fast and Diverse Text-to-3D Generation](https://arxiv.org/abs/2401.07727), Mercier et al., Arxiv 2024
- [Repaint123: Fast and High-quality One Image to 3D Generation with Progressive Controllable 2D Repainting](https://arxiv.org/abs/2312.13271), Zhang et al., Arxiv 2023
- [Retrieval-Augmented Score Distillation for Text-to-3D Generation](https://arxiv.org/abs/2402.02972), Seo et al., Arxiv 2024
- [BrightDreamer: Generic 3D Gaussian Generative Framework for Fast Text-to-3D Synthesis](https://arxiv.org/abs/2403.11273), Jiang and Wang, Arxiv 2024
- [DreamReward: Text-to-3D Generation with Human Preference](https://arxiv.org/abs/2403.14613), Ye et al., Arxiv 2024
- [DreamFlow: High-Quality Text-to-3D Generation by Approximating Probability Flow](https://arxiv.org/abs/2403.14966), Lee et al., ICLR 2024
- [LATTE3D: Large-scale Amortized Text-To-Enhanced3D Synthesis](http://arxiv.org/abs/2403.15385), Xie et al., Arix 2024
- [DreamPolisher: Towards High-Quality Text-to-3D Generation via Geometric Diffusion](https://arxiv.org/abs/2403.17237), Lin et al., Arxiv 2024
- [VP3D: Unleashing 2D Visual Prompt for Text-to-3D Generation](https://arxiv.org/abs/2403.17001), Chen et al., CVPR 2024
- [Hash3D: Training-free Acceleration for 3D Generation](https://arxiv.org/abs/2404.06091), Yang and Wang, Arxiv 2024
- [MicroDreamer: Zero-shot 3D Generation in ∼20 Seconds by Score-based Iterative Reconstruction](https://arxiv.org/abs/2404.19525), Chen et al., Arxiv 2024
- [SketchDream: Sketch-based Text-to-3D Generation and Editing](https://arxiv.org/pdf/2405.06461), Liu et al., Arxiv 2024
- [Flow Score Distillation for Diverse Text-to-3D](https://arxiv.org/pdf/2405.10988), Yan et al., Arxiv 2024
- [Dreamer XL: Towards High-Resolution Text-to-3D Generation via Trajectory Score Matching](https://arxiv.org/abs/2405.11252), Miao et al., Arxiv 2024
- [Atlas3D: Physically Constrained Self-Supporting Text-to-3D for Simulation and Fabrication](https://arxiv.org/abs/2405.18515), Chen et al., Arxiv 2024
- [DIRECT-3D: Learning Direct Text-to-3D Generation on Massive Noisy 3D Data](https://arxiv.org/pdf/2406.04322), Liu et al., Arxiv 2024
- [Text-guided Controllable Mesh Refinement for Interactive 3D Modeling](https://arxiv.org/pdf/2406.01592), Chen et al., Arxiv 2024

### Compositional or Scene Generation
- [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989), Höllein et al., Arxiv 2023
- [SceneScape: Text-Driven Consistent Scene Generation](https://arxiv.org/abs/2302.01133), Fridman et al., Arxiv 2023
- [Compositional 3D Scene Generation using Locally Conditioned Diffusion](https://arxiv.org/abs/2303.12218), Po and Wetzstein, Arxiv 2023
- [Set-the-Scene: Global-Local Training for Generating Controllable NeRF Scenes](https://arxiv.org/abs/2303.13450), Cohen-Bar et al., Arxiv 2023
- [CompoNeRF: Text-guided Multi-object Compositional NeRF with Editable 3D Scene Layout](https://arxiv.org/abs/2303.13843), Lin et al., Arxiv 2023
- [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588), Zhang et al., Arxiv 2023
- [Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/abs/2310.03602), Fang et al., Arxiv 2023
- [SceneWiz3D: Towards Text-guided 3D Scene Composition](https://arxiv.org/abs/2312.08885), Zhang et al., Arxiv 2023
- [ShowRoom3D: Text to High-Quality 3D Room Generation Using 3D Priors](https://arxiv.org/abs/2312.13324), Mao et al., Arxiv 2023
- [Text2Street: Controllable Text-to-image Generation for Street Views](https://arxiv.org/abs/2402.04504), Su et al., Arxiv 2024
- [GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting](http://arxiv.org/abs/2402.07207), Zhou et al., Arxiv 2023
- [Sketch2NeRF: Multi-view Sketch-guided Text-to-3D Generation](https://arxiv.org/abs/2401.14257), Chen et al., Arxiv 2024
- [A Quantitative Evaluation of Score Distillation Sampling Based Text-to-3D](https://arxiv.org/abs/2402.18780), Fei et al., Arxiv 2024
- [DreamScene: 3D Gaussian-based Text-to-3D Scene Generation via Formation Pattern Sampling](https://arxiv.org/abs/2404.03575), Li et al., Arxiv 2024
- [DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting](https://arxiv.org/abs/2404.06903), Zhou et al., Arxiv 2024
- [RealmDreamer: Text-Driven 3D Scene Generation with Inpainting and Depth Diffusion](https://arxiv.org/abs/2404.07199), Shriram et al., Arxiv 2024
- [Urban Architect: Steerable 3D Urban Scene Generation with Layout Prior](https://arxiv.org/abs/2404.06780), Lu et al., Arxiv 2024
- [DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling](https://arxiv.org/abs/2404.09227), Yang et al., Arxiv 2024
- [Invisible Stitch: Generating Smooth 3D Scenes with Depth Inpainting](https://arxiv.org/abs/2404.19758), Engstler et al., Arxiv 2024
- [REPARO: Compositional 3D Assets Generation with Differentiable 3D Layout Alignment](https://arxiv.org/pdf/2405.18525), Han et al., Arxiv 2024
- [VividDream: Generating 3D Scene with Ambient Dynamics](https://arxiv.org/pdf/2405.20334), Lee et al., Arxiv 2024

### Image-to-3D
- [NeuralLift-360: Lifting An In-the-wild 2D Photo to A 3D Object with $360^{\deg}$ Views](https://arxiv.org/abs/2211.16431), Xu et al., CVPR 2023
- [NeRDi: Single-View NeRF Synthesis with Language-Guided Diffusion as General Image Priors](https://arxiv.org/abs/2212.03267), Deng et al., CVPR 2023
- [Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures](https://arxiv.org/abs/2211.07600), Metzer et al., CVPR 2023
- [RealFusion: 360{\deg} Reconstruction of Any Object from a Single Image](https://arxiv.org/abs/2302.10663), Melas-Kyriazi et al., Arxiv 2023
- [Make-It-3D: High-Fidelity 3D Creation from A Single Image with Diffusion Prior](https://arxiv.org/abs/2303.14184), Tang et al., Arxiv 2023
- [Zero-1-to-3: Zero-shot One Image to 3D Object](https://arxiv.org/abs/2303.11328), Liu et al., Arxiv 2023
- [DreamBooth3D: Subject-Driven Text-to-3D Generation](https://arxiv.org/abs/2303.13508), Raj et al., Arxiv 2023
- [DreamSparse: Escaping from Plato's Cave with 2D Frozen Diffusion Model Given Sparse Views](https://arxiv.org/abs/2306.03414), Yoo et al., Arxiv 2023
- [One-2-3-45: Any Single Image to 3D Mesh in 45 Seconds without Per-Shape Optimization](https://arxiv.org/abs/2306.16928), Liu et al., Arxiv 2023
- [Magic123: One Image to High-Quality 3D Object Generation Using Both 2D and 3D Diffusion Priors](https://arxiv.org/abs/2306.17843), Qian et al., Arxiv 2023
- [360◦ Reconstruction From a Single Image Using Space Carved Outpainting](https://arxiv.org/abs/2309.10279), Ryu et al., SIGGRAPH ASIA 2023
- [Viewpoint Textual Inversion: Unleashing Novel View Synthesis with Pretrained 2D Diffusion Models](http://arxiv.org/abs/2309.07986), Burgess et al., Arxiv 2023
- [IPDreamer: Appearance-Controllable 3D Object Generation with Image Prompts](https://arxiv.org/abs/2310.05375), Zeng et al.,
- [Customize-It-3D: High-Quality 3D Creation from A Single Image Using Subject-Specific Knowledge Prior](https://arxiv.org/abs/2312.11535), Huang et al., Arxiv 2023
- [HarmonyView: Harmonizing Consistency and Diversity in One-Image-to-3D](http://arxiv.org/abs/2312.15980), Woo et al., Arxiv 2023
- [Repaint123: Fast and High-quality One Image to 3D Generation with Progressive Controllable 2D Repainting](https://arxiv.org/abs/2312.13271), Zhang et al., Arxiv 2023
- [AGG: Amortized Generative 3D Gaussians for Single Image to 3D](https://arxiv.org/abs/2401.04099), Xu et al., Arxiv 2024
- [Part123: Part-aware 3D Reconstruction from a Single-view Image](https://arxiv.org/abs/2405.16888), Liu et al., SIGGRAPH Conference 2024
- [GECO: Generation Image-to-3D within a Second](https://arxiv.org/abs/2405.20327), Wang et al., Arxiv 2024
- [Fourier123: One Image to High-Quality 3D Object Generation with Hybrid Fourier Score Distillation](https://arxiv.org/pdf/2405.20669), Yang et al., Arxiv 2024
- [Unique3D: High-Quality and Efficient 3D Mesh Generation from a Single Image](https://arxiv.org/pdf/2405.20343), Wu et al., Arxiv 2024

### Human and Animal
- [DreamFace: Progressive Generation of Animatable 3D Faces under Text Guidance](https://arxiv.org/abs/2304.03117), Zhang et al., Arxiv 2023
- [AvatarCraft: Transforming Text into Neural Human Avatars with Parameterized Shape and Pose Control](https://arxiv.org/abs/2303.17606), Jiang et al., ICCV 2023
- [DreamAvatar: Text-and-Shape Guided 3D Human Avatar Generation via Diffusion Models](https://arxiv.org/abs/2304.00916), Cao et al., Arxiv 2023
- [DreamWaltz: Make a Scene with Complex 3D Animatable Avatars](https://arxiv.org/abs/2305.12529), Huang et al., Arxiv 2023
- [ZeroAvatar: Zero-shot 3D Avatar Generation from a Single Image](https://arxiv.org/abs/2305.16411), Weng et al., Arxiv 2023
- [AvatarBooth: High-Quality and Customizable 3D Human Avatar Generation](https://arxiv.org/abs/2306.09864), Zeng et al., Arxiv 2023
- [Farm3D: Learning Articulated 3D Animals by Distilling 2D Diffusion](https://arxiv.org/pdf/2304.10535.pdf) Jakab et al., Arxiv 2023
- [Anything 3D: Towards Single-view Anything Reconstruction in the Wild](https://arxiv.org/abs/2304.10261), Shen et al., Arxiv 2023
- [ARTIC3D: Learning Robust Articulated 3D Shapes from Noisy Web Image Collections](https://arxiv.org/abs/2306.04619), Yao et al., Arxiv 2023
- [TADA! Text to Animatable Digital Avatars](https://arxiv.org/abs/2308.10899), Liao et al., Arxiv 2023
- [Diffusion-Guided Reconstruction of Everyday Hand-Object Interaction Clips](https://arxiv.org/abs/2309.05663), Ye et al., ICCV 2023
- [Text-Guided Generation and Editing of Compositional 3D Avatars](http://arxiv.org/abs/2309.07125), Zhang et al., Arxiv 2023
- [HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting](https://arxiv.org/abs/2311.17061), Liu et al., Arxiv 2023
- [AvatarStudio: High-fidelity and Animatable 3D Avatar Creation from Text](https://arxiv.org/abs/2311.17917), Zhang et al., Arxiv 2023
- [Disentangled Clothed Avatar Generation from Text Descriptions](https://arxiv.org/abs/2312.05295), Wang et al., Arxiv 2023
- [SEEAvatar: Photorealistic Text-to-3D Avatar Generation with Constrained Geometry and Appearance](https://arxiv.org/abs/2312.08889), Xu et al., Arxiv 2023
- [GAvatar: Animatable 3D Gaussian Avatars with Implicit Mesh Learning](https://arxiv.org/abs/2312.11461), Yuan et al., Arxiv 2023
- [Make-A-Character: High Quality Text-to-3D Character Generation within Minutes](http://arxiv.org/abs/2312.15430), Ren et al., Arxiv 2023
- [Morphable Diffusion: 3D-Consistent Diffusion for Single-image Avatar Creation](https://arxiv.org/abs/2401.04728), Chen et al., Arxiv 2024

### 3D Editing
- [SKED: Sketch-guided Text-based 3D Editing](https://arxiv.org/abs/2303.10735), Mikaeili et al., Arxiv 2023
- [Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions](https://arxiv.org/abs/2303.12789), Haque et al., ICCV 2023
- [Instruct 3D-to-3D: Text Instruction Guided 3D-to-3D conversion](https://arxiv.org/abs/2303.15780), Kamata et al., Arxiv 2023
- [Edit-DiffNeRF: Editing 3D Neural Radiance Fields using 2D Diffusion Model](https://arxiv.org/abs/2306.09551), Yu et al., Arxiv 2023
- [Control4D: Dynamic Portrait Editing by Learning 4D GAN from 2D Diffusion-based Editor](https://arxiv.org/abs/2305.20082), Shao et al., Arxiv 2023
- [RePaint-NeRF: NeRF Editting via Semantic Masks and Diffusion Models](https://arxiv.org/abs/2306.05668), Zhou et al., Arxiv 2023
- [DreamEditor: Text-Driven 3D Scene Editing with Neural Fields](https://arxiv.org/abs/2306.13455), Zhuang et al., SIGRRAPH ASIA 2023
- [Language-driven Object Fusion into Neural Radiance Fields with Pose-Conditioned Dataset Updates](https://arxiv.org/abs/2309.11281), Shum et al., Arxiv 2023
- [ProteusNeRF: Fast Lightweight NeRF Editing using 3D-Aware Image Context](https://arxiv.org/abs/2310.09965), Wang et al., Arxiv 2023
- [ED-NeRF: Efficient Text-Guided Editing of 3D Scene using Latent Space NeRF](https://arxiv.org/abs/2310.02712), Park et al., Arxiv 2023
- [3D Paintbrush: Local Stylization of 3D Shapes with Cascaded Score Distillation](http://arxiv.org/abs/2311.09571), Decatur et al., Arxiv 2023
- [GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting](https://arxiv.org/abs/2311.14521), Chen et al., Arxiv 2023
- [Inpaint3D: 3D Scene Content Generation using 2D Inpainting Diffusion](http://arxiv.org/abs/2312.03869), Prabhu et al., Arxiv 2023
- [NeRFiller: Completing Scenes via Generative 3D Inpainting](http://arxiv.org/abs/2312.04560), Weber et al., Arxiv 2023
- [SHAP-EDITOR: Instruction-guided Latent 3D Editing in Seconds](https://arxiv.org/abs/2312.09246), Chen et al., Arxiv 2023
- [LatentEditor: Text Driven Local Editing of 3D Scenes](https://arxiv.org/abs/2312.09313), Khalid et al., Arxiv 2023
- [Free-Editor: Zero-shot Text-driven 3D Scene Editing](https://arxiv.org/abs/2312.13663), Karim et al., Arxiv 2023
- [SIGNeRF: Scene Integrated Generation for Neural Radiance Fields](https://arxiv.org/abs/2401.01647), Dihlmann et al., Arxiv 2023
- [Efficient-NeRF2NeRF: Streamlining Text-Driven 3D Editing with Multiview Correspondence-Enhanced Diffusion Models](https://arxiv.org/abs/2312.08563), Song et al., Arxiv 2024
- [ReplaceAnything3D: Text-Guided 3D Scene Editing with Compositional Neural Radiance Fields](https://arxiv.org/abs/2401.17895), Bartrum et al., Arxiv 2024
- [GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing](http://arxiv.org/abs/2403.08733), Wu et al., Arxiv 2024
- [View-Consistent 3D Editing with Gaussian Splatting](https://arxiv.org/abs/2403.11868), Wang et al., Arxiv 2024
- [Interactive3D: Create What You Want by Interactive 3D Generation](https://arxiv.org/abs/2404.16510), Dong et al., Arxiv 2024
- [DGE: Direct Gaussian 3D Editing by Consistent Multi-view Editing](https://arxiv.org/abs/2404.18929), Chen et al., Arxiv 2024
- [DATENeRF: Depth-Aware Text-based Editing of NeRFs](https://arxiv.org/pdf/2404.04526), Rojas et al., Arxiv 2024

### Texturing
- [TEXTure: Text-Guided Texturing of 3D Shapes](https://arxiv.org/abs/2302.01721), Richardson et al., Arxiv 2023
- [Text2Tex: Text-driven Texture Synthesis via Diffusion Models](https://arxiv.org/abs/2303.11396), Chen et al., Arxiv 2023
- [EucliDreamer: Fast and High-Quality Texturing for 3D Models with Stable Diffusion Depth](https://arxiv.org/abs/2311.15573), Le et al., Arxiv 2023
- [Paint3D: Paint Anything 3D with Lighting-Less Texture Diffusion Models](http://arxiv.org/abs/2312.13913), Zeng et al., Arxiv 2023
- [TextureDreamer: Image-guided Texture Synthesis through Geometry-aware Diffusion](https://arxiv.org/abs/2401.09416), Yeh et al., Arxiv 2024
- [MaPa: Text-driven Photorealistic Material Painting for 3D Shapes](https://arxiv.org/abs/2404.17569), Zheng et al., Arxiv 2024
- [DreamMat: High-quality PBR Material Generation with Geometry- and Light-aware Diffusion Models](https://arxiv.org/abs/2405.17176), Zhang et al., Arxiv 2024

### Multi-view Diffusion
- [MVDiffusion: Enabling Holistic Multi-view Image Generation with Correspondence-Aware Diffusion](https://arxiv.org/abs/2307.01097), Tang et al., Arxiv 2023
- [MVDream: Multi-view Diffusion for 3D Generation](https://arxiv.org/abs/2308.16512), Shi et al., Arxiv 2023
- [SyncDreamer: Generating Multiview-consistent Images from a Single-view Image](https://arxiv.org/abs/2309.03453), Liu et al., Arxiv 2023
- [Consistent123: Improve Consistency for One Image to 3D Object Synthesis](http://arxiv.org/abs/2310.08092), Weng et al., Arxiv 2023
- [Wonder3D: Single Image to 3D using Cross-Domain Diffusion](https://arxiv.org/abs/2310.15008), Long et al., Arxiv 2023
- [Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model](http://arxiv.org/abs/2310.15110), Shi et al., Arxiv 2023
- [TOSS:High-quality Text-guided Novel View Synthesis from a Single Image](http://arxiv.org/abs/2310.10644), Shi et al., Arxiv 2023
- [Text-Guided Texturing by Synchronized Multi-View Diffusion](https://arxiv.org/abs/2311.12891), Liu et al., Arxiv 2023
- [Direct2.5: Diverse Text-to-3D Generation via Multi-view 2.5D Diffusion](http://arxiv.org/abs/2311.15980), Lu et al., Arxiv 2023
- [ViVid-1-to-3: Novel View Synthesis with Video Diffusion Models](http://arxiv.org/abs/2312.01305), Kwak et al., Arxiv 2023
- [EpiDiff: Enhancing Multi-View Synthesis via Localized Epipolar-Constrained Diffusion](https://arxiv.org/abs/2312.06725), Huang et al., CVPR 2024
- [EscherNet: A Generative Model for Scalable View Synthesis](https://arxiv.org/abs/2402.03908), Kong et al., Arxiv 2024
- [LGM: Large Multi-View Gaussian Model for High-Resolution 3D Content Creation](https://arxiv.org/abs/2402.05054), Tang et al., Arxiv 2024
- [SPAD : Spatially Aware Multiview Diffusers](https://arxiv.org/abs/2402.05235), Kant et al., Arxiv 2024
- [MVDiffusion++: A Dense High-resolution Multi-view Diffusion Model for Single or Sparse-view 3D Object Reconstruction](https://arxiv.org/abs/2402.12712), Tang et al., Arxiv 2024
- [CRM: Single Image to 3D Textured Mesh with Convolutional Reconstruction Model](http://arxiv.org/abs/2403.05034), Wang et al., Arxiv 2024
- [V3D: Video Diffusion Models are Effective 3D Generators](https://arxiv.org/abs/2403.06738), Chen et al., Arxiv 2024
- [Envision3D: One Image to 3D with Anchor Views Interpolation](http://arxiv.org/abs/2403.08902), Pang et al., Arxiv 2024
- [Make-Your-3D: Fast and Consistent Subject-Driven 3D Content Generation](http://arxiv.org/abs/2403.09625), Liu et al., Arxiv 2024
- [Controllable Text-to-3D Generation via Surface-Aligned Gaussian Splatting](https://arxiv.org/abs/2403.09981), Li et al., Arxiv 2024
- [FDGaussian: Fast Gaussian Splatting from Single Image via Geometric-aware Diffusion Model](https://arxiv.org/abs/2403.10242), Feng et al., Arxiv 2024
- [Isotropic3D: Image-to-3D Generation Based on a Single CLIP Embedding](https://arxiv.org/abs/2403.10395), Liu et al., Arxiv 2024
- [SV3D: Novel Multi-view Synthesis and 3D Generation from a Single Image using Latent Video Diffusion](https://arxiv.org/abs/2403.12008), Vikram et al., Arxiv 2024
- [Generic 3D Diffusion Adapter Using Controlled Multi-View Editing](https://arxiv.org/abs/2403.12032), Chen et al., Arxiv 2024
- [VFusion3D: Learning Scalable 3D Generative Models from Video Diffusion Models](https://arxiv.org/abs/2403.12034), Han et al., Arxiv 2024
- [Garment3DGen: 3D Garment Stylization and Texture Generation](http://arxiv.org/abs/2403.19655), Zhang et al., Arxiv 2024
- [MVD-Fusion: Single-view 3D via Depth-consistent Multi-view Generation](https://arxiv.org/abs/2404.03656), Hu et al., CVPR 2024
- [Magic-Boost: Boost 3D Generation with Mutli-View Conditioned Diffusion](https://arxiv.org/abs/2404.06429), Yang et al., Arxiv 2024
- [InstantMesh: Efficient 3D Mesh Generation from a Single Image with Sparse-view Large Reconstruction Models](http://arxiv.org/abs/2404.07191), Xu et al., Arxiv 2024
- [Magic-Boost: Boost 3D Generation with Mutli-View Conditioned Diffusion](https://arxiv.org/abs/2404.06429), Yang et al., Arxiv 2024
- [Grounded Compositional and Diverse Text-to-3D with Pretrained Multi-View Diffusion Model](https://arxiv.org/pdf/2404.18065), Li et al., Arxiv 2024
- [Multi-view Image Prompted Multi-view Diffusion for Improved 3D Generation](https://arxiv.org/abs/2404.17419), Kim et al., Arxiv 2024
- [MVDiff: Scalable and Flexible Multi-View Diffusion for 3D Object Reconstruction from Single-View](https://arxiv.org/pdf/2405.03894), Bourigault et al., Arxiv 2024
- [CAT3D: Create Anything in 3D with Multi-View Diffusion Models](http://arxiv.org/abs/2405.10314), Gao et al., Arxiv 2024
- [CraftsMan: High-fidelity Mesh Generation with 3D Native Generation and Interactive Geometry Refiner](https://arxiv.org/abs/2405.14979), Li et al., Arxiv 2024
- [Ouroboros3D: Image-to-3D Generation via 3D-aware Recursive Diffusion](https://arxiv.org/pdf/2406.03184), Wen et al., Arxiv 2024

## 2D Diffusion without Pretraining
### 3D Objects
- [Novel View Synthesis with Diffusion Models](https://arxiv.org/abs/2210.04628), Watson et al., ICLR 2023
- [Generative Novel View Synthesis with 3D-Aware Diffusion Models](https://arxiv.org/abs/2304.02602), Chan et al., Arxiv 2023
- [NerfDiff: Single-image View Synthesis with NeRF-guided Distillation from 3D-aware Diffusion](https://arxiv.org/abs/2302.10109), Gu et al., ICML 2023
- [3DDesigner: Towards Photorealistic 3D Object Generation and Editing with Text-guided Diffusion Models](https://arxiv.org/abs/2211.14108), Li et al., Arxiv 2022
- [SparseFusSparseFusion: Distilling View-conditioned Diffusion for 3D Reconstruction](https://arxiv.org/abs/2212.00792), Zhou and Tulsiani, CVPR 2023
- [HoloDiffusion: Training a 3D Diffusion Model using 2D Images](https://arxiv.org/abs/2303.16509), Karnewar et al., CVPR 2023
- [Renderdiffusion: Image Diffusion for 3D Reconstruction, Inpainting and Generation](https://arxiv.org/abs/2211.09869), Anciukevičius et al., CVPR 2023
- [Diffusion with Forward Models: Solving Stochastic Inverse Problems Without Direct Supervision](https://arxiv.org/abs/2306.11719), Tewari et al., Arxiv 2023
- [3D-aware Image Generation using 2D Diffusion Models](https://arxiv.org/abs/2303.17905), Xiang et al., Arxiv 2023
- [Viewset Viewset Diffusion: (0-)Image-Conditioned 3D Generative Models from 2D Data](https://arxiv.org/abs/2306.07881), Szymanowicz et al., Arxiv 2023
- [HOLOFUSION: Towards Photo-realistic 3D Generative Modeling](https://arxiv.org/pdf/2308.14244.pdf), Karnewar et al., Arxiv 2023
- [ZeroNVS: Zero-Shot 360-Degree View Synthesis from a Single Real Image](http://arxiv.org/abs/2310.17994), Sargent et al., Arxiv 2023
- [Instant3D: Fast Text-to-3D with Sparse-view Generation and Large Reconstruction Model](https://arxiv.org/abs/2311.06214), Li et al., Arxiv 2023
- [DMV3D: Denoising Multi-View Diffusion using 3D Large Reconstruction Model](https://arxiv.org/abs/2311.09217), Xu et al., Arxiv 2023
- [LRM: Large Reconstruction Model for Single Image to 3D](https://arxiv.org/abs/2311.04400), Hong et al., Arxiv 2023
- [WildFusion: Learning 3D-Aware Latent Diffusion Models in View Space](https://arxiv.org/abs/2311.13570), Schwarz et al., Arxiv 2023
- [ViewFusion: Learning Composable Diffusion Models for Novel View Synthesis](https://arxiv.org/abs/2402.02906), Spiegl et al., Arxiv 2024

### 3D Scenes
- [Consistent View Synthesis with Pose-Guided Diffusion Models](https://arxiv.org/abs/2303.17598), Tseng et al., CVPR 2023
- [Long-Term Photometric Consistent Novel View Synthesis with Diffusion Models](https://arxiv.org/abs/2304.10700), Yu et al., Arxiv 2023 
- [DiffDreamer: Towards Consistent Unsupervised Single-view Scene Extrapolation with Conditional Diffusion Models](https://arxiv.org/abs/2211.12131), Cai et al., Arxiv 2023

## Diffusion in 3D Space
### 3D Gaussians
- [GVGEN: Text-to-3D Generation with Volumetric Representation](https://arxiv.org/abs/2403.12957), He et al., Arxiv 2024
- [GaussianCube: Structuring Gaussian Splatting using Optimal Transport for 3D Generative Modeling](http://arxiv.org/abs/2403.19655), Zhang et al., Arxiv 2024

### Point Cloud, Meshs, Volumes

- [Diffusion Probabilistic Models for 3D Point Cloud Generation](https://arxiv.org/pdf/2103.01458.pdf), Luo et al., CVPR 2021
- [3d shape generation and completion through point-voxel diffusion](https://arxiv.org/pdf/2104.03670), Zhou et al., Arxiv 2021
- [A Diffusion-ReFinement Model for Sketch-to-Point Modeling](https://link.springer.com/chapter/10.1007/978-3-031-26293-7_4), Kong et al., ACCV 2022
- [Controllable Mesh Generation Through Sparse Latent Point Diffusion Models](http://arxiv.org/pdf/2303.07938), Lyu et al., CVPR 2023
- [Point-E: A System for Generating 3D Point Clouds from Complex Prompts](https://arxiv.org/pdf/2212.08751), Nichol et al., ICML 2023
- [DiffFacto: Controllable Part-Based 3D Point Cloud Generation with Cross Diffusion](https://arxiv.org/pdf/2305.01921.pdf), Nakayama et al., Arxiv 2023
- [Sketch and Text Guided Diffusion Model for Colored Point Cloud Generation](https://arxiv.org/abs/2308.02874), Wu et al., ICCV 2023
- [DiT-3D: Exploring Plain Diffusion Transformers for 3D Shape Generation](https://arxiv.org/abs/2307.01831), Mo et al., Arxiv 2023
- [MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers](https://arxiv.org/abs/2311.15475), Siqqiqui et al., Arxiv 2023
- [ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model](http://arxiv.org/abs/2311.17618), Yin et al., Arxiv 2023
- [VolumeDiffusion: Flexible Text-to-3D Generation with Efficient Volumetric Encoder](https://arxiv.org/abs/2312.11459), Tang et al., Arxiv 2023
- [SPiC·E: Structural Priors in 3D Diffusion Models using Cross-Entity Attention](https://arxiv.org/abs/2311.17834), Sella et al., Arxiv 2023
- [PolyDiff: Generating 3D Polygonal Meshes with Diffusion Models](https://arxiv.org/abs/2312.11417), Alliegro et al., Arxiv 2023


### Implicit Representation

- [Learning A Diffusion Prior For Nerfs](https://arxiv.org/pdf/2304.14473.pdf), Yang et al., ICLRW 2023
- [Tetrahedral Diffusion Models for 3D Shape Generation](https://arxiv.org/pdf/2211.13220.pdf), Nikolai and Torben et al., Arxiv 2022
- [MeshDiffusion: Score-based Generative 3D Mesh Modeling](https://arxiv.org/pdf/2303.08133), Liu et al., ICLR 2023
- [Neural Wavelet-domain Diffusion for 3D Shape Generation](https://arxiv.org/pdf/2209.08725), Hui et al., SIGGRAPH Asia 2022 
- [Neural Wavelet-domain Diffusion for 3D Shape Generation, Inversion, and Manipulation](https://arxiv.org/pdf/2302.00190), Hu and Hui et al., Arxiv 2023
- [DiffRF: Rendering-Guided 3D Radiance Field Diffusion](https://arxiv.org/pdf/2212.01206.pdf), Muller et al., CVPR 2023
- [Locally Attentional SDF Diffusion for Controllable 3D Shape Generation](http://arxiv.org/pdf/2305.04461), Zheng et al., SIGGRAPH 2023
- [HyperDiffusion: Generating Implicit Neural Fields with Weight-Space Diffusion](https://arxiv.org/pdf/2303.17015), Erkoç et al., ICCV 2023
- [DiffComplete: Diffusion-based Generative 3D Shape Completion](https://arxiv.org/pdf/2306.16329), Chu et al., Arxiv 2023
- [DiffRoom: Diffusion-based High-Quality 3D Room Reconstruction and Generation](https://arxiv.org/pdf/2306.00519), Ju et al., Arxiv 2023
- [Surf-D: High-Quality Surface Generation for Arbitrary Topologies using Diffusion Models](https://arxiv.org/abs/2311.17050), Yu et al., Arxiv 2023

### Triplane

- [3D Neural Field Generation using Triplane Diffusion](https://arxiv.org/pdf/2211.16677.pdf), Shue et al., Arxiv 2022
- [DiffusionSDF: Conditional Generative Modeling of Signed Distance Functions](https://arxiv.org/pdf/2211.13757), Chou et al., Arxiv 2022
- [Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://arxiv.org/pdf/2212.06135.pdf), Wang et al., CVPR 2023
- [3DGen: Triplane Latent Diffusion for Textured Mesh Generation](https://arxiv.org/pdf/2303.05371), Gupta et al., Arxiv 2023
- [Single-Stage Diffusion NeRF: A Unified Approach to 3D Generation and Reconstruction](https://arxiv.org/pdf/2304.06714.pdf), Chen et al., Arxiv 2023
- [Learning Controllable 3D Diffusion Models from Single-view Images](https://arxiv.org/pdf/2304.06700), Gu et al., Arxiv 2023
- [Compress3D: a Compressed Latent Space for 3D Generation from a Single Image](https://arxiv.org/abs/2403.13524), Zhang et al., Arxiv 2024
- [Dual3D: Efficient and Consistent Text-to-3D Generation with Dual-mode Multi-view Latent Diffusion](https://arxiv.org/pdf/2405.09874), Li et al., Arxiv 2024
- [Direct3D: Scalable Image-to-3D Generation via 3D Latent Diffusion Transformer](https://arxiv.org/pdf/2405.14832), Wu et al., Arxiv 2024

### Latent Representation

- [GAUDI: A Neural Architect for Immersive 3D Scene Generation](https://arxiv.org/pdf/2207.13751.pdf), Bautista et al., NeurIPS 2022
- [LION: Latent Point Diffusion Models for 3D Shape Generation](https://arxiv.org/pdf/2210.06978.pdf), Zeng et al., NeurIPS 2022
- [Diffusion-SDF: Text-to-Shape via Voxelized Diffusion](https://arxiv.org/pdf/2212.03293), Li et al., CVPR 2023
- [3D-LDM: Neural Implicit 3D Shape Generation with Latent Diffusion Models](https://arxiv.org/pdf/2212.00842), Nam et al., Arxiv 2022
- [3DShape2VecSet: A 3D Shape Representation for Neural Fields and Generative Diffusion Models](http://arxiv.org/pdf/2301.11445), Zhang et al., SIGGRAPH 2023
- [Shap-E: Generating Conditional 3D Implicit Functions](https://arxiv.org/pdf/2305.02463.pdf), Jun et al., Arxiv 2023
- [StyleAvatar3D: Leveraging Image-Text Diffusion Models for High-Fidelity 3D Avatar Generation](https://arxiv.org/pdf/2305.19012), Zhang et al., Arxiv 2023
- [AutoDecoding Latent 3D Diffusion Models](https://arxiv.org/pdf/2307.05445), Ntavelis et al., Arxiv 2023
- [XCube: Large-Scale 3D Generative Modeling using Sparse Voxel Hierarchies](https://arxiv.org/abs/2312.03806), Ren et al., CVPR 2024 
- [LN3Diff: Scalable Latent Neural Fields Diffusion for Speedy 3D Generation](https://arxiv.org/abs/2403.12019), Lan et al., Arxiv 2024

## Novel Representations
- [X-Ray: A Sequential 3D Representation for Generation](https://arxiv.org/pdf/2404.14329), Hu et al., Arxiv 2024

## Diffusion for Motion

### Human Motion
- [Single Motion Diffusion](https://sinmdm.github.io/SinMDM-page/), Raab et al., ICLR 2024
- [OmniControl: Control Any Joint at Any Time for Human Motion Generation](https://arxiv.org/abs/2310.08580), Xie et al., ICLR 2024
- [Human Motion Diffusion as a Generative Prior](https://priormdm.github.io/priorMDM-page/), Shafir et al., ICLR 2024
- [MotionMix: Weakly-Supervised Diffusion for Controllable Motion Generation](https://arxiv.org/abs/2401.11115), Hoang et al., AAAI 2024
- [DNO: Optimizing Diffusion Noise Can Serve As Universal Motion Priors](https://korrawe.github.io/dno-project/), Karunratanakul et al., Arxiv 2023
- [RoHM: Robust Human Motion Reconstruction via Diffusion](https://arxiv.org/pdf/2401.08570.pdf), Zhang et al., Arxiv 2023
- [EMDM: Efficient Motion Diffusion Model for Fast, High-Quality Human Motion Generation](https://frank-zy-dou.github.io/projects/EMDM/index.html), Zhou et al., Arxiv 2023
- [DiffusionPhase: Motion Diffusion in Frequency Domain](https://arxiv.org/abs/2312.04036), Wan et al., Arxiv 2023
- [InterControl: Generate Human Motion Interactions by Controlling Every Joint](https://arxiv.org/abs/2311.15864), Wang et al., Arxiv 2023
- [AAMDM: Accelerated Auto-regressive Motion Diffusion Model](https://arxiv.org/abs/2401.06146), Li et al., Arxiv 2023
- [ReMoS: Reactive 3D Motion Synthesis for Two-Person Interactions](https://vcai.mpi-inf.mpg.de/projects/remos/), Ghosh et al., Arxiv 2023
- [HOI-Diff: Text-Driven Synthesis of 3D Human-Object Interactions using Diffusion Models](https://arxiv.org/abs/2312.06553), Peng et al., Arxiv 2023
- [Controllable Motion Diffusion Model](https://arxiv.org/abs/2306.00416), Shi et al., Arxiv 2023
- [MAS: Multi-view Ancestral Sampling for 3D motion generation using 2D diffusion](https://arxiv.org/abs/2310.14729), Kapon et al., Arxiv 2023
- [CG-HOI: Contact-Guided 3D Human-Object Interaction Generation](https://arxiv.org/pdf/2311.16097.pdf), Diller et al., Arxiv 2023
- [A Unified Framework for Multimodal, Multi-Part Human Motion Synthesis](https://arxiv.org/pdf/2311.16471.pdf), Zhou et al., Arxiv 2023
- [Controllable Motion Synthesis and Reconstruction with Autoregressive Diffusion Models](https://arxiv.org/abs/2304.04681), Yin et al., Arxiv 2023
- [Guided Motion Diffusion for Controllable Human Motion Synthesis](https://openaccess.thecvf.com/content/ICCV2023/papers/Karunratanakul_Guided_Motion_Diffusion_for_Controllable_Human_Motion_Synthesis_ICCV_2023_paper.pdf), Karunratanakul et al., ICCV 2023
- [Hierarchical Generation of Human-Object Interactions with Diffusion Probabilistic Models](https://openaccess.thecvf.com/content/ICCV2023/html/Pi_Hierarchical_Generation_of_Human-Object_Interactions_with_Diffusion_Probabilistic_Models_ICCV_2023_paper.html), Pi et al., ICCV 2023
- [PhysDiff: Physics-Guided Human Motion Diffusion Model](https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_PhysDiff_Physics-Guided_Human_Motion_Diffusion_Model_ICCV_2023_paper.pdf), Yuan et al., ICCV 2023
- [Priority-Centric Human Motion Generation in Discrete Latent Space](https://openaccess.thecvf.com/content/ICCV2023/papers/Kong_Priority-Centric_Human_Motion_Generation_in_Discrete_Latent_Space_ICCV_2023_paper.pdf), Kong et al., ICCV 2023
- [ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_ReMoDiffuse_Retrieval-Augmented_Motion_Diffusion_Model_ICCV_2023_paper.pdf), Zhang et al., ICCV 2023
- [Flame: Free-form language-based motion synthesis & editing](https://ojs.aaai.org/index.php/AAAI/article/view/25996), Kim et al., AAAI 2023
- [Object Motion Guided Human Motion Synthesis](https://arxiv.org/abs/2309.16237), Li et al., SIG ASIA 2023, TOG 2023
- [Controllable Group Choreography using Contrastive Diffusion](https://arxiv.org/abs/2310.18986), Le et al., TOG 2023
- [Listen, denoise, action! Audio-driven motion synthesis with diffusion models](https://arxiv.org/abs/2211.09707), Alexanderson et al., SIG 2023, TOG 2023
- [GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents](https://aubrey-ao.github.io/publication/gesturediffuclip/) Ao et al., SIG 2023, TOG 2023
- [Taming Diffusion Models for Audio-Driven Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_Taming_Diffusion_Models_for_Audio-Driven_Co-Speech_Gesture_Generation_CVPR_2023_paper.pdf), Zhu et al., CVPR 2023
- [MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis](https://openaccess.thecvf.com/content/CVPR2023/papers/Dabral_Mofusion_A_Framework_for_Denoising-Diffusion-Based_Motion_Synthesis_CVPR_2023_paper.pdf), Dabral et al., CVPR 2023
- [Executing your Commands via Motion Diffusion in Latent Space](https://arxiv.org/abs/2212.04048), Jiang et al., CVPR 2023
- [MDM: Human Motion Diffusion Model](https://guytevet.github.io/mdm-page/), Tevet et al., ICLR 2023
- [MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html), Zhang et al., Arxiv 2022
