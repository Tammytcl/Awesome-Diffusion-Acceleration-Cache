<div align=center>

# 🎨 Awesome Diffusion Acceleration Cache 🚀

<p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-100+-pink)

👐👐 If you would like to contribute to this repository, feel free to email me at `ljc.mytcl@gmail.com`! 👐👐

</p>

</div>

## Repository Description
A curated list of research papers, resources, and advancements on Diffusion Cache and related efficient diffusion model acceleration techniques.

This repository aims to provide a comprehensive and up-to-date collection of academic works focused on Diffusion Cache — a promising approach for accelerating diffusion models by caching intermediate features or latent states. It includes papers on model efficiency, memory optimization, reuse mechanisms, and inference speed-up in diffusion-based generative systems.

**This repository is maintained by EPIC Lab at Shanghai Jiao Tong University**


## 🔥 Update News

* **`2025/08/24`** 🤗🤗 We release an open-source repo for diffusion model acceleration and caching techniques!

## 📊 Papers Table

| # | Date | Conference | Paper Title | Institution |
|----|------------------|-------------------|-------------|-------------|
| 1 | 2023.05 | AAAI 2024 | **`[FISEdit]`** Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference [Paper](https://arxiv.org/pdf/2305.17423) [Code](https://github.com/Hankpipi/diffusers-hetu) | Peking University |
| 2 | 2023.12 | - | **`[DeepCache]`** DeepCache: Accelerating Diffusion Models for Free [Paper](https://arxiv.org/pdf/2312.00858) [Code](https://github.com/horseee/DeepCache) | National University of Singapore |
| 3 | 2023.12 | - | **`[Block Caching]`** Cache Me if You Can: Accelerating Diffusion Models through Block Caching [Paper](https://arxiv.org/pdf/2312.03209) | Meta GenAI |
| 4 | 2023.12 | - | **`[Approximate Caching]`** Approximate Caching for Efficiently Serving Diffusion Models [Paper](https://arxiv.org/pdf/2312.04429) | Adobe |
| 5 | 2024.04 | - | **`[T-GATE V1]`** Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models [Paper](https://arxiv.org/pdf/2404.02747v1) [Code](https://github.com/HaozheLiu-ST/T-GATE) | KAUST |
| 6 | 2024.04 | - | **`[T-GATE V2]`** Faster Diffusion via Temporal Attention Decomposition [Paper](https://arxiv.org/pdf/2404.02747) | KAUST |
| 7 | 2024.06 | - | **`[Layer Caching]`** Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching [Paper](https://arxiv.org/pdf/2406.01733) [Code](https://github.com/horseee/learning-to-cache/) | National University of Singapore |
| 8 | 2024.06 | - | **`[∆-DiT]`** ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers [Paper](https://arxiv.org/pdf/2406.01125) | Fudan |
| 9 | 2024.07 | - | **`[ElasticCache-LVLM]`** Efficient Inference of Vision Instruction-Following Models with Elastic Cache [Paper](https://arxiv.org/pdf/2407.18121) [Code](https://github.com/liuzuyan/ElasticCache) | Tsinghua |
| 10 | 2024.07 | - | **`[FORA]`** FORA: Fast-Forward Caching in Diffusion Transformer Acceleration [Paper](https://arxiv.org/pdf/2407.01425) [Code](https://github.com/prathebaselva/FORA) | Microsoft |
| 11 | 2024.07 | - | **`[VCUT]`** Faster Image2Video Generation: A Closer Look at CLIP Image Embedding's Impact on Spatio-Temporal Cross-Attentions [Paper](https://arxiv.org/pdf/2407.19205) | The University of Western Australia |
| 12 | 2024.09 | - | **`[TokenCache]`** Token Caching for Diffusion Transformer Acceleration [Paper](https://arxiv.org/pdf/2409.18523) | University of Chinese Academy of Sciences |
| 13 | 2024.09 | - | **`[FRDiff]`** FRDiff: Feature Reuse for Universal Training-free Acceleration of Diffusion Models [Paper](https://arxiv.org/pdf/2312.03517) [Code](https://github.com/Jungwon-Lee/FRDiff) | Pohang University of Science and Technology |
| 14 | 2024.10 | - | **`[FasterCache]`** FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality [Paper](https://arxiv.org/pdf/2410.19355) [Code](https://github.com/Vchitect/FasterCache) | - |
| 15 | 2024.10 | ICLR 2025 | **`[ToCa]`** ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching | Shanghai Jiao Tong University |
| 16 | 2024.11 | - | **`[AdaCache]`** Adaptive Caching for Faster Video Generation with Diffusion Transformers [Paper](https://adacache-dit.github.io/clarity/adacache_meta.pdf) [Code](https://github.com/AdaCache-DiT/AdaCache) | Meta |
| 17 | 2024.11 | CVPR 2025 | **`[TeaCache]`** Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model [Paper](https://arxiv.org/pdf/2411.19108) [Code](https://github.com/LiewFeng/TeaCache) | Alibaba |
| 18 | 2024.11 | - | **`[LazyDiT]`** LazyDiT: Lazy Learning for the Acceleration of Diffusion Transformers [Paper](https://arxiv.org/pdf/2412.12444) | Adobe Research |
| 19 | 2024.11 | - | **`[Ca2-VDM]`** Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing [Paper](https://arxiv.org/pdf/2411.16375) [Code](https://github.com/Dawn-LX/CausalCache-VDM/) | - |
| 20 | 2024.11 | - | **`[SmoothCache]`** SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers [Paper](https://arxiv.org/pdf/2411.10510) [Code](https://github.com/Roblox/SmoothCache) | Roblox |
| 21 | 2024.11 | - | **`[SkipCache]`** Accelerating Vision Diffusion Transformers with Skip Branches | Shanghai Jiao Tong University |
| 22 | 2024.12 | ICLR 2025 | **`[DuCa]`** Accelerating Diffusion Transformers with Dual Feature Caching | Shanghai Jiao Tong University |
| 23 | 2025.01 | - | **`[FBCache]`** Fastest HunyuanVideo Inference with Context Parallelism and First Block Cache on NVIDIA L20 GPUs | - |
| 24 | 2025.01 | - | **`[FlexCache]`** FlexCache: Flexible Approximate Cache System for Video Diffusion | - |
| 25 | 2025.01 | - | **`[DaTo]`** Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free [Paper](https://arxiv.org/pdf/2501.00375) | Shanghai Jiao Tong University |
| 26 | 2025.02 | - | **`[PAB]`** Real-Time Video Generation with Pyramid Attention Broadcast [Paper](https://arxiv.org/pdf/2408.12588) [Code](https://github.com/NUS-HPC-AI-Lab/OpenDiT) | National University of Singapore |
| 27 | 2025.03 | ICCV 2025 | **`[TaylorSeer]`** From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers [Code](https://github.com/Shenyi-Z/TaylorSeer) | Shanghai Jiao Tong University |
| 28 | 2025.03 | - | **`[FEB-Cache]`** FEB-Cache: Frequency-Guided Exposure Bias Reduction for Enhancing Diffusion Transformer Caching [Paper](https://arxiv.org/pdf/2503.07120) [Code](https://github.com/aSleepyTree/EB-Cache) | University of Science and Technology of China |
| 29 | 2025.03 | - | **`[CacheQuant]`** CacheQuant: Comprehensively Accelerated Diffusion Models [Paper](https://arxiv.org/pdf/2503.01323) [Code](https://github.com/BienLuky/CacheQuant) | University of Chinese Academy of Sciences |
| 30 | 2025.03 | - | **`[QuantCache]`** QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation [Paper](https://arxiv.org/pdf/2503.06545) [Code](https://github.com/JunyiWuCode/QuantCache) | Shanghai Jiao Tong University |
| 31 | 2025.04 | - | **`[AB-Cache]`** AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse | - |
| 32 | 2025.04 | ACM MM 2025 | **`[ClusCa]`** Compute only 16 tokens in one timestep: Accelerating Diffusion Transformers with Cluster-Driven Feature Caching [Code](https://github.com/zhixin-zheng/ClusCa) | Shanghai Jiao Tong University |
| 33 | 2025.04 | ACM MM 2025 | **`[SpeCa]`** SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |
| 34 | 2025.04 | - | **`[FeMO]`** Accelerate Diffusion Transformers with Feature Momentum [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |
| 35 | 2025.04 | - | **`[ICC]`** Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition [Paper](https://arxiv.org/pdf/2505.05829) [Code](https://github.com/ccccczzy/icc) | Peking University |
| 36 | 2025.05 | - | **`[FastCache]`** FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation | - |
| 37 | 2025.06 | - | **`[DBPrune]`** DBPrune: Dynamic Block Prune with Residual Caching | Vipshop |
| 38 | 2025.06 | - | **`[DBCache]`** DBCache: Dual Block Caching for Diffusion Transformers | Vipshop |
| 39 | 2025.06 | - | **`[BACache]`** Block-wise Adaptive Caching for Accelerating Diffusion Policy [Paper](https://arxiv.org/pdf/2506.13456) | Peking University |
| 40 | 2025.07 | - | **`[FoCa]`** Forecast then Calibrate: Feature Caching as ODE for Efficient Diffusion Transformers [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |
| 41 | 2025.07 | - | **`[HiCache]`** HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |
| 42 | 2025.07 | - | **`[WaveEx]`** WaveEx: Accelerating Flow Matching-based Speech Generation via Wavelet-guided Extrapolation [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |
| 43 | 2025.07 | - | **`[GOC]`** Accelerating Diffusion Transformer via Gradient-Optimized Cache [Paper](https://arxiv.org/pdf/2503.05156) [Code](https://github.com/qiujx0520/GOC_ICCV2025) | University of Science and Technology of China |
| 44 | 2025.08 | - | **`[TaoCache]`** TaoCache: Structure-Maintained Video Generation Acceleration [Paper](https://arxiv.org/pdf/2508.08978) | Huawei |
| 45 | 2025.09 | - | **`[Z-Cache]`** Z-Cache: Accelerating Diffusion Transformers via Self-Reflection [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) | Shanghai Jiao Tong University |





## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Thanks to all researchers and contributors who have worked on diffusion model acceleration and caching techniques. 