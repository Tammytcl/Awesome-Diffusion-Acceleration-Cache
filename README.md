<div align=center>

# 🎨 Awesome Diffusion Acceleration Cache 🚀

<p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-68+-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)
![GitHub stars](https://img.shields.io/github/stars/EPIC-Lab/Awesome-Diffusion-Acceleration-Cache.svg?style=social)

👐👐 If you would like to contribute to this repository, feel free to email me at `ljc.mytcl@gmail.com`! 👐👐

</p>

</div>

## 📚 <span id="head1"> *Repository Description* </span>

A curated list of research papers, resources, and advancements on **Diffusion Cache** and related efficient diffusion model acceleration techniques.

This repository aims to provide a comprehensive and up-to-date collection of academic works focused on Diffusion Cache — a promising approach for accelerating diffusion models by caching intermediate features or latent states. It includes papers on model efficiency, memory optimization, reuse mechanisms, and inference speed-up in diffusion-based generative systems.

**This repository is maintained by EPIC Lab at Shanghai Jiao Tong University**


## 🔥 <span id="head1"> *Update News* </span>

* **`2025/03/10`** 💥💥 We propose [TaylorSeer](https://arxiv.org/abs/2503.06923), achieving ~5× acceleration for DiTs with Taylor expansion-based feature forecasting!

* **`2024/12/24`** 💥💥 Our work [DuCa](https://arxiv.org/abs/2412.18911) has been accepted by **ICLR 2025**! Congratulations to all collaborators!

* **`2024/10/12`** 🚀🚀 We release our work [ToCa](https://arxiv.org/abs/2410.05317), achieving nearly lossless acceleration of **1.51×** on FLUX, **1.93×** on PixArt-α, and **2.36×** on OpenSora!

* **`2024/08/24`** 🤗🤗 We release an open-source repo for diffusion model acceleration and caching techniques!


## 📚 <span id="head1"> *Contents* </span>

- [Awesome Diffusion Acceleration Cache](#-awesome-diffusion-acceleration-cache-)
  - [U-Net Based Caching](#u-net-based-caching)
  - [Diffusion Transformer (DiT) Caching](#diffusion-transformer-dit-caching)
    - [Block-Level Caching](#block-level-caching)
    - [Layer-Level Caching](#layer-level-caching)
    - [Token-Level Caching](#token-level-caching)
    - [Attention-Level Caching](#attention-level-caching)
  - [Video Generation Caching](#video-generation-caching)
  - [Multi-Modal & Others](#multi-modal--others)


## 💬 <span id="head1"> *Keywords* </span>

![](https://img.shields.io/badge/Method_Abbreviation-blue) ![](https://img.shields.io/badge/Application-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)


## 📝 <span id="head1"> *Papers* </span>

### 2023

- **[1] Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference**, AAAI 2024.
  
  *Yu, Zihao and Li, Haoyang and Fu, Fangcheng and Miao, Xupeng and Cui, Bin.*

  [[Paper](https://arxiv.org/pdf/2305.17423)] [[Code](https://github.com/Hankpipi/diffusers-hetu)] ![](https://img.shields.io/badge/FISEdit-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/Sparse_Diffusion-orange)

- **[2] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/U_Net_Caching-orange)

- **[3] Cache Me if You Can: Accelerating Diffusion Models through Block Caching**, CVPR 2024.

  *Wimbauer, Felix and Wu, Bichen and Schoenfeld, Edgar and Dai, Xiaoliang and others.*

  [[Paper](https://arxiv.org/pdf/2312.03209)] ![](https://img.shields.io/badge/Block_Caching-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Block_Level_Cache-orange)

- **[4] Approximate Caching for Efficiently Serving Diffusion Models**, NSDI 2024.
  
  *Adobe Research Team.*

  [[Paper](https://arxiv.org/pdf/2312.04429)] ![](https://img.shields.io/badge/Approximate_Caching-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Serving_System-orange)

- **[5] Faster Diffusion: Rethinking the Role of the Encoder for Diffusion Model Inference**, NeurIPS 2024.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and others.*

  [[Paper](https://arxiv.org/pdf/2312.09608)] [[Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/FasterDiffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Encoder_Caching-orange)


### 2024

- **[6] Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models**, arXiv 2024.

  *Liu, Haozhe and Zhang, Wentian and Xie, Jinheng and others.*

  [[Paper](https://arxiv.org/pdf/2404.02747v1)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATE_V1-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Attention_Gating-orange)

- **[7] Faster Diffusion via Temporal Attention Decomposition**, TMLR 2024.

  *Liu, Haozhe and Zhang, Wentian and Xie, Jinheng and Faccio, Francesco and others.*

  [[Paper](https://arxiv.org/pdf/2404.02747)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATE_V2-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Attention_Decomposition-orange)

- **[8] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching**, NeurIPS 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Mi, Michael Bi and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2406.01733)] [[Code](https://github.com/horseee/learning-to-cache/)] ![](https://img.shields.io/badge/L2C-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Layer_Caching-orange)

- **[9] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and others.*

  [[Paper](https://arxiv.org/pdf/2406.01125)] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Delta_Cache-orange)

- **[10] DiTFastAttn: Attention Compression for Diffusion Transformer Models**, NeurIPS 2024.

  *Yuan, Zhihang and Lu, Pu and Zhang, Hanling and Ning, Xuefei and others.*
  
  [[Paper](https://arxiv.org/pdf/2406.08552)] [[Code](https://github.com/thu-nics/DiTFastAttn)] ![](https://img.shields.io/badge/DiTFastAttn-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Attention_Compression-orange)

- **[11] Efficient Inference of Vision Instruction-Following Models with Elastic Cache**, ECCV 2024.
  
  *Liu, Zuyan and others.*

  [[Paper](https://arxiv.org/pdf/2407.18121)] [[Code](https://github.com/liuzuyan/ElasticCache)] ![](https://img.shields.io/badge/ElasticCache-blue) ![](https://img.shields.io/badge/Vision_Language-green) ![](https://img.shields.io/badge/KV_Cache-orange)

- **[12] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and others.*

  [[Paper](https://arxiv.org/pdf/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Fast_Forward_Cache-orange)

- **[13] Faster Image2Video Generation: A Closer Look at CLIP Image Embedding's Impact on Spatio-Temporal Cross-Attentions**, arXiv 2024.

  *University of Western Australia Research Team.*

  [[Paper](https://arxiv.org/pdf/2407.19205)] ![](https://img.shields.io/badge/VCUT-blue) ![](https://img.shields.io/badge/Image2Video-green) ![](https://img.shields.io/badge/Cross_Attention_Cache-orange)

- **[14] Token Caching for Diffusion Transformer Acceleration**, arXiv 2024.

  *Jinming Lou and Wenyang Luo and Yufan Liu and Bing Li and others.*

  [[Paper](https://arxiv.org/pdf/2409.18523)] ![](https://img.shields.io/badge/TokenCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Cache-orange)

- **[15] FRDiff: Feature Reuse for Universal Training-free Acceleration of Diffusion Models**, ECCV 2024.
  
  *Lee, Jungwon and Park, Suhyeon and others.*

  [[Paper](https://arxiv.org/pdf/2312.03517)] [[Code](https://github.com/Jungwon-Lee/FRDiff)] ![](https://img.shields.io/badge/FRDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Feature_Reuse-orange)

- **[16] FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality**, arXiv 2024.

  *Zhengyao Lv and Chenyang Si and Junhao Song and Zhenyu Yang and others.*
  
  [[Paper](https://arxiv.org/pdf/2410.19355)] [[Code](https://github.com/Vchitect/FasterCache)] ![](https://img.shields.io/badge/FasterCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Dynamic_Feature_Reuse-orange)

- **[17] ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching**, ICLR 2025.

  *Chang Zou and Xuyang Liu and Ting Liu and Siteng Huang and Linfeng Zhang.*
  
  [[Paper](https://arxiv.org/pdf/2410.05317)] [[Code](https://github.com/Shenyi-Z/ToCa)] ![](https://img.shields.io/badge/ToCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[18] HarmoniCa: Harmonizing Training and Inference for Better Feature Caching in Diffusion Transformer Acceleration**, ICML 2025.

  *SenseTime Research Team.*
  
  [[Paper](https://arxiv.org/pdf/2410.01723)] [[Code](https://github.com/ModelTC/HarmoniCa)] ![](https://img.shields.io/badge/HarmoniCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Training+Inference-orange)

- **[19] Adaptive Caching for Faster Video Generation with Diffusion Transformers**, arXiv 2024.

  *Kumara Kahatapitiya and Haozhe Liu and Sen He and Ding Liu and others.*
  
  [[Paper](https://adacache-dit.github.io/clarity/adacache_meta.pdf)] [[Code](https://github.com/AdaCache-DiT/AdaCache)] ![](https://img.shields.io/badge/AdaCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Adaptive_Cache-orange)

- **[20] Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model**, CVPR 2025.

  *Liu, Feng and Zhang, Shiwei and Wang, Xiaofeng and Wei, Yujie and others.*
  
  [[Paper](https://arxiv.org/pdf/2411.19108)] [[Code](https://github.com/LiewFeng/TeaCache)] ![](https://img.shields.io/badge/TeaCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Timestep_Embedding-orange)

- **[21] LazyDiT: Lazy Learning for the Acceleration of Diffusion Transformers**, AAAI 2025.

  *Rice, Shawn and others.*

  [[Paper](https://arxiv.org/pdf/2412.12444)] [[Code](https://github.com/shawnricecake/lazydit)] ![](https://img.shields.io/badge/LazyDiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Lazy_Learning-orange)

- **[22] Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing**, ICML 2025.

  *Gao, Kaifeng and Shi, Jiaxin and Zhang, Hanwang and others.*
  
  [[Paper](https://arxiv.org/pdf/2411.16375)] [[Code](https://github.com/Dawn-LX/CausalCache-VDM/)] ![](https://img.shields.io/badge/Ca2_VDM-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Causal_Cache-orange)

- **[23] SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers**, CVPR eLVM 2024.

  *Roblox Research Team.*

  [[Paper](https://arxiv.org/pdf/2411.10510)] [[Code](https://github.com/Roblox/SmoothCache)] ![](https://img.shields.io/badge/SmoothCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Audio_Generation-green) ![](https://img.shields.io/badge/Smooth_Cache-orange)

- **[24] Accelerating Diffusion Transformers with Dual Feature Caching**, ICLR 2025.

  *Chang Zou and Evelyn Zhang and Runlin Guo and Haohang Xu and Conghui He and others.*
  
  [[Paper](https://arxiv.org/pdf/2412.18911)] [[Code](https://github.com/Shenyi-Z/DuCa)] ![](https://img.shields.io/badge/DuCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Dual_Feature_Cache-orange)


### 2025

- **[25] Fastest HunyuanVideo Inference with Context Parallelism and First Block Cache on NVIDIA L20 GPUs**, arXiv 2025.

  *Zheng, Zeyi and others.*

  [[Paper](-)] [[Code](https://github.com/chengzeyi/ParaAttention)] ![](https://img.shields.io/badge/FBCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Context_Parallel-orange) ![](https://img.shields.io/badge/First_Block_Cache-orange)

- **[26] FlexCache: Flexible Approximate Cache System for Video Diffusion**, arXiv 2025.

  *University of Waterloo Research Team.*

  [[Paper](https://arxiv.org/pdf/2501.04012)] ![](https://img.shields.io/badge/FlexCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Approximate_Cache-orange)

- **[27] Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free**, arXiv 2025.

  *Evelyn Zhang and Bang Xiao and Jiayi Tang and Qianli Ma and Chang Zou and others.*

  [[Paper](https://arxiv.org/pdf/2501.00375)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Caching-orange)

- **[28] Accelerating Diffusion Transformer via Error-Optimized Cache**, arXiv 2025.

  *University of Science and Technology of China Research Team.*

  [[Paper](https://arxiv.org/pdf/2501.19243)] [[Code](https://github.com/qiujx0520/EOC_MM2025)] ![](https://img.shields.io/badge/Error_Optimized_Cache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Error_Optimization-orange)

- **[29] Real-Time Video Generation with Pyramid Attention Broadcast**, ICLR 2025.

  *Xuanlei Zhao and Xiaolong Jin and Kai Wang and Yang You.*
  
  [[Paper](https://arxiv.org/pdf/2408.12588)] [[Code](https://github.com/NUS-HPC-AI-Lab/OpenDiT)] ![](https://img.shields.io/badge/PAB-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Pyramid_Attention-orange)

- **[30] MoDM: Efficient Serving for Image Generation via Mixture-of-Diffusion Models**, arXiv 2025.

  *University of Michigan Research Team.*

  [[Paper](https://arxiv.org/pdf/2503.11972)] [[Code](https://github.com/stsxxx/MoDM)] ![](https://img.shields.io/badge/MoDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Mixture_of_Models-orange)

- **[31] BlockDance: Reuse Structurally Similar Spatio-Temporal Features to Accelerate Diffusion Transformers**, CVPR 2025.

  *Fudan University Research Team.*

  [[Paper](https://arxiv.org/pdf/2503.15927)] ![](https://img.shields.io/badge/BlockDance-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Spatial_Temporal_Reuse-orange)

- **[32] From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers**, ICCV 2025.

  *Chang Zou and others.*

  [[Paper](https://arxiv.org/pdf/2503.06923)] [[Code](https://github.com/Shenyi-Z/TaylorSeer)] ![](https://img.shields.io/badge/TaylorSeer-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Taylor_Expansion-orange)

- **[33] FEB-Cache: Frequency-Guided Exposure Bias Reduction for Enhancing Diffusion Transformer Caching**, arXiv 2025.

  *Xu, Haohang and Zou, Chang and Liu, Xuyang and Guo, Runlin and He, Conghui and others.*
  
  [[Paper](https://arxiv.org/pdf/2503.07120)] [[Code](https://github.com/aSleepyTree/EB-Cache)] ![](https://img.shields.io/badge/FEB_Cache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Frequency_Guided-orange)

- **[34] CacheQuant: Comprehensively Accelerated Diffusion Models**, CVPR 2025.

  *Zhang, Evelyn and Tang, Jiayi and others.*

  [[Paper](https://arxiv.org/pdf/2503.01323)] [[Code](https://github.com/BienLuky/CacheQuant)] ![](https://img.shields.io/badge/CacheQuant-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Cache+Quantization-orange)

- **[35] QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation**, ICCV 2025.

  *Wu, Junyi and Zou, Chang and Liu, Xuyang and Guo, Runlin and Xu, Haohang and others.*
  
  [[Paper](https://arxiv.org/pdf/2503.06545)] [[Code](https://github.com/JunyiWuCode/QuantCache)] ![](https://img.shields.io/badge/QuantCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Quantization+Cache-orange)

- **[36] AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse**, arXiv 2025.

  *Xu, Haohang and Zou, Chang and Liu, Xuyang and Guo, Runlin and He, Conghui and others.*
  
  [[Paper](https://arxiv.org/pdf/2504.10540)] ![](https://img.shields.io/badge/AB_Cache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Adams_Bashforth-orange)

- **[37] ProfilingDiT: Model Reveals What to Cache: Profiling-Based Feature Reuse for Video Diffusion Models**, arXiv 2025.

  *Huazhong University of Science and Technology Research Team.*

  [[Paper](https://arxiv.org/pdf/2504.03140)] [[Code](https://github.com/GeekGuru123/ProfilingDiT)] ![](https://img.shields.io/badge/ProfilingDiT-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Profiling_Based-orange)

- **[38] Compute only 16 tokens in one timestep: Accelerating Diffusion Transformers with Cluster-Driven Feature Caching**, ACM MM 2025.

  *Zheng, Zhixin and Zou, Chang and Liu, Xuyang and others.*
  
  [[Paper](https://arxiv.org/pdf/2509.10312v1)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion)] ![](https://img.shields.io/badge/ClusCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Cluster_Cache-orange)

- **[39] SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching**, ACM MM 2025.

  *Zou, Chang and Liu, Xuyang and Guo, Runlin and others.*
  
  [[Paper](-)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/SpeCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Speculative_Cache-orange)

- **[40] Accelerate Diffusion Transformers with Feature Momentum**, arXiv 2025.

  *Liu, Xuyang and Zou, Chang and Guo, Runlin and others.*
  
  [[Paper](-)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/FeMO-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Momentum-orange)

- **[41] Foresight: Adaptive Layer Reuse for Accelerated and High-Quality Text-to-Video Generation**, NeurIPS 2025.

  *The University of British Columbia and d-Matrix Research Team.*

  [[Paper](https://arxiv.org/pdf/2506.00329)] [[Code](https://github.com/STAR-Laboratory/foresight)] ![](https://img.shields.io/badge/Foresight-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Adaptive_Layer_Reuse-orange)

- **[42] ParaStep: Communication-Efficient Diffusion Denoising Parallelization via Reuse-then-Predict Mechanism**, arXiv 2025.

  *Shanghai Jiao Tong University Research Team.*

  [[Paper](https://arxiv.org/pdf/2505.14741)] ![](https://img.shields.io/badge/ParaStep-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Parallel-orange)

- **[43] RainFusion: Adaptive Video Generation Acceleration via Multi-Dimensional Visual Redundancy**, arXiv 2025.

  *Huawei Technologies Co., Ltd Research Team.*

  [[Paper](https://arxiv.org/pdf/2505.21036)] ![](https://img.shields.io/badge/RainFusion-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Visual_Redundancy-orange)

- **[44] Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition**, CVPR 2025.

  *Qiu, Jianxin and others.*

  [[Paper](https://arxiv.org/pdf/2505.05829)] [[Code](https://github.com/ccccczzy/icc)] ![](https://img.shields.io/badge/ICC-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Increment_Calibrated-orange) ![](https://img.shields.io/badge/SVD-orange)

- **[45] FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation**, CVPR 2025.

  *Liu, Noak and others.*

  [[Paper](https://arxiv.org/pdf/2505.20353)] [[Code](https://github.com/NoakLiu/FastCache-xDiT)] ![](https://img.shields.io/badge/FastCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Linear_Approximation-orange)

- **[46] Chipmunk: Training-Free Acceleration of Diffusion**, ICML 2025.

  *University of California Research Team.*

  [[Paper](https://arxiv.org/pdf/2506.03275)] [[Code](https://github.com/sandyresearch/chipmunk)] ![](https://img.shields.io/badge/Chipmunk-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Training_Free-orange)

- **[47] ECAD: Evolutionary Caching to Accelerate Your Off-the-Shelf Diffusion Model**, arXiv 2025.

  *University of Maryland Research Team.*

  [[Paper](https://arxiv.org/pdf/2506.15682)] [[Code](https://github.com/aniaggarwal/ecad)] ![](https://img.shields.io/badge/ECAD-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Evolutionary_Caching-orange)

- **[48] MagCache: Fast Video Generation with Magnitude-Aware Cache**, arXiv 2025.

  *Peking University Research Team.*

  [[Paper](https://arxiv.org/pdf/2506.09045)] [[Code](https://github.com/Zehong-Ma/MagCache)] ![](https://img.shields.io/badge/MagCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Magnitude_Aware-orange)

- **[49] DBPrune: Dynamic Block Prune with Residual Caching**, arXiv 2025.

  *Vipshop Research Team.*

  [[Paper](-)] [[Code](https://github.com/vipshop/cache-dit)] ![](https://img.shields.io/badge/DBPrune-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Block_Pruning-orange)

- **[50] DBCache: Dual Block Caching for Diffusion Transformers**, arXiv 2025.

  *Vipshop Research Team.*

  [[Paper](-)] [[Code](https://github.com/vipshop/cache-dit)] ![](https://img.shields.io/badge/DBCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Dual_Block_Cache-orange)

- **[51] Block-wise Adaptive Caching for Accelerating Diffusion Policy**, arXiv 2025.

  *Zhang, Yunbo and Liu, Zhenyu and others.*

  [[Paper](https://arxiv.org/pdf/2506.13456)] ![](https://img.shields.io/badge/BACache-blue) ![](https://img.shields.io/badge/Diffusion_Policy-green) ![](https://img.shields.io/badge/Adaptive_Cache-orange)

- **[52] Accelerating Vision Diffusion Transformers with Skip Branches**, ICCV 2025.

  *Chen, Guanjie and Zhao, Xinyu and Zhou, Yucheng and Chen, Tianlong and Yu, Cheng.*

  [[Paper](https://arxiv.org/pdf/2411.17616v1)] [[Code](https://github.com/OpenSparseLLMs/Skip-DiT)] ![](https://img.shields.io/badge/SkipCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Skip_Branch-orange)

- **[53] Forecast then Calibrate: Feature Caching as ODE for Efficient Diffusion Transformers**, arXiv 2025.

  *Zou, Chang and Liu, Xuyang and Guo, Runlin and others.*

  [[Paper](https://arxiv.org/pdf/2508.16211)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/FoCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/ODE-orange)

- **[54] HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching**, arXiv 2025.

  *Guo, Runlin and Zou, Chang and Liu, Xuyang and others.*

  [[Paper](https://arxiv.org/pdf/2508.16984)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/HiCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Hermite_Polynomial-orange)

- **[55] WaveEx: Accelerating Flow Matching-based Speech Generation via Wavelet-guided Extrapolation**, arXiv 2025.

  *Guo, Runlin and Zou, Chang and Liu, Xuyang and others.*

  [[Paper](-)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/WaveEx-blue) ![](https://img.shields.io/badge/Speech_Generation-green) ![](https://img.shields.io/badge/Wavelet-orange)

- **[56] EasyCache: Less is Enough: Training-Free Video Diffusion Acceleration via Runtime-Adaptive Caching**, arXiv 2025.

  *Huazhong University of Science and Technology Research Team.*

  [[Paper](https://arxiv.org/pdf/2507.02860)] [[Code](https://github.com/H-EmbodVis/EasyCache)] ![](https://img.shields.io/badge/EasyCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Runtime_Adaptive-orange)

- **[57] Accelerating Diffusion Transformer via Gradient-Optimized Cache**, ICCV 2025.

  *Qiu, Jianxin and others.*

  [[Paper](https://arxiv.org/pdf/2503.05156)] [[Code](https://github.com/qiujx0520/GOC_ICCV2025)] ![](https://img.shields.io/badge/GOC-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Gradient_Optimized-orange)

- **[58] TaoCache: Structure-Maintained Video Generation Acceleration**, arXiv 2025.

  *Huawei Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.08978)] ![](https://img.shields.io/badge/TaoCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Structure_Maintained-orange)

- **[59] DiCache: Let Diffusion Model Determine Its Own Cache**, arXiv 2025.

  *Shanghai Jiao Tong University Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.17356)] [[Code](https://github.com/Bujiazi/DiCache)] ![](https://img.shields.io/badge/DiCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Self_Determined-orange)

- **[60] HERO: Hierarchical Extrapolation and Refresh for Efficient World Model**, arXiv 2025.

  *Tsinghua University Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.17588)] ![](https://img.shields.io/badge/HERO-blue) ![](https://img.shields.io/badge/World_Model-green) ![](https://img.shields.io/badge/Hierarchical-orange)

- **[61] ERTACache: Error Rectification and Timesteps Adjustment for Efficient Diffusion**, arXiv 2025.

  *ByteDance Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.21091)] [[Code](https://github.com/bytedance/ERTACache)] ![](https://img.shields.io/badge/ERTACache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Error_Rectification-orange)

- **[62] OmniCache: A Trajectory-Oriented Global Perspective on Training-Free Cache Reuse for Diffusion Transformer Models**, ICCV 2025.

  *Zhipu AI Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.16212)] ![](https://img.shields.io/badge/OmniCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Trajectory_Oriented-orange)

- **[63] MixCache: Mixture-of-Cache for Video Diffusion Transformer Acceleration**, arXiv 2025.

  *Sun Yat-sen University Research Team.*

  [[Paper](https://arxiv.org/pdf/2508.12691v1)] ![](https://img.shields.io/badge/MixCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Mixture_of_Cache-orange)

- **[64] Z-Cache: Accelerating Diffusion Transformers via Self-Reflection**, arXiv 2025.

  *Zou, Chang and Liu, Xuyang and Guo, Runlin and others.*

  [[Paper](-)] [[Code](https://github.com/Shenyi-Z/Cache4Diffusion/)] ![](https://img.shields.io/badge/Z_Cache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Self_Reflection-orange)

- **[65] SpecDiff: Accelerating Diffusion Model Inference with Self-Speculation**, arXiv 2025.

  *Shanghai Jiao Tong University Research Team.*

  [[Paper](https://arxiv.org/pdf/2509.13848)] ![](https://img.shields.io/badge/SpecDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Self_Speculation-orange)

- **[66] BWCache: Accelerating Video Diffusion Transformers through Block-Wise Caching**, arXiv 2025.

  *Beijing Normal University Research Team.*

  [[Paper](https://arxiv.org/pdf/2509.13789)] ![](https://img.shields.io/badge/BWCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Block_Wise-orange)

- **[67] DiTReducio: A Training-Free Acceleration for DiT-Based TTS via Progressive Calibration**, arXiv 2025.

  *Xiamen University, Zhejiang University, Wuhan University Research Team.*

  [[Paper](https://arxiv.org/pdf/2509.09748)] ![](https://img.shields.io/badge/DiTReducio-blue) ![](https://img.shields.io/badge/TTS-green) ![](https://img.shields.io/badge/Progressive_Calibration-orange)

- **[68] LightningCP: Lightning Fast Caching-based Parallel Denoising Prediction for Accelerating Talking Head Generation**, arXiv 2025.

  *Nanyang Technological University Research Team.*

  [[Paper](https://arxiv.org/pdf/2509.00052)] ![](https://img.shields.io/badge/LightningCP-blue) ![](https://img.shields.io/badge/Talking_Head-green) ![](https://img.shields.io/badge/Parallel_Denoising-orange)




## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Thanks to all researchers and contributors who have worked on diffusion model acceleration and caching techniques. 
