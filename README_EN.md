# Awesome-Diffusion-Acceleration-Cache
## Repository Description
A curated list of research papers, resources, and advancements on Diffusion Cache and related efficient diffusion model acceleration techniques.

This repository aims to provide a comprehensive and up-to-date collection of academic works focused on Diffusion Cache — a promising approach for accelerating diffusion models by caching intermediate features or latent states. It includes papers on model efficiency, memory optimization, reuse mechanisms, and inference speed-up in diffusion-based generative systems.

## 📊 Papers Table

| Publication Date | Conference/Journal | Method Name | Paper Title | Architecture | Domain | Institution | Paper Link | Code Repository |
|------------------|-------------------|-------------|-------------|--------------|--------|-------------|------------|-----------------|
| 2023.05 | AAAI 2024 | FISEdit | Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference | Unet | Image Generation | Peking University | [Paper](https://arxiv.org/pdf/2305.17423) | [Code](https://github.com/Hankpipi/diffusers-hetu) |
| 2023.12 | - | DeepCache | DeepCache: Accelerating Diffusion Models for Free | Unet | - | National University of Singapore | [Paper](https://arxiv.org/pdf/2312.00858) | [Code](https://github.com/horseee/DeepCache) |
| 2023.12 | - | Block Caching | Cache Me if You Can: Accelerating Diffusion Models through Block Caching | Unet | - | Meta GenAI | [Paper](https://arxiv.org/pdf/2312.03209) | - |
| 2023.12 | - | Approximate Caching | Approximate Caching for Efficiently Serving Diffusion Models | - | - | Adobe | [Paper](https://arxiv.org/pdf/2312.04429) | - |
| 2024.04 | - | T-GATE V1 | Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models | - | - | KAUST | [Paper](https://arxiv.org/pdf/2404.02747v1) | [Code](https://github.com/HaozheLiu-ST/T-GATE) |
| 2024.04 | - | T-GATE V2 | Faster Diffusion via Temporal Attention Decomposition | - | - | KAUST | [Paper](https://arxiv.org/pdf/2404.02747) | - |
| 2024.06 | - | Layer Caching | Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching | - | - | National University of Singapore | [Paper](https://arxiv.org/pdf/2406.01733) | [Code](https://github.com/horseee/learning-to-cache/) |
| 2024.06 | - | ∆-DiT | ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers | DiT | Image Generation | Fudan | [Paper](https://arxiv.org/pdf/2406.01125) | - |
| 2024.07 | - | ElasticCache-LVLM | Efficient Inference of Vision Instruction-Following Models with Elastic Cache | - | - | Tsinghua | [Paper](https://arxiv.org/pdf/2407.18121) | [Code](https://github.com/liuzuyan/ElasticCache) |
| 2024.07 | - | FORA | FORA: Fast-Forward Caching in Diffusion Transformer Acceleration | DiT | Image Generation | Microsoft | [Paper](https://arxiv.org/pdf/2407.01425) | [Code](https://github.com/prathebaselva/FORA) |
| 2024.07 | - | VCUT | Faster Image2Video Generation: A Closer Look at CLIP Image Embedding's Impact on Spatio-Temporal Cross-Attentions | - | - | The University of Western Australia | [Paper](https://arxiv.org/pdf/2407.19205) | - |
| 2024.09 | - | TokenCache | Token Caching for Diffusion Transformer Acceleration | - | - | University of Chinese Academy of Sciences | [Paper](https://arxiv.org/pdf/2409.18523) | - |
| 2024.09 | - | FRDiff | FRDiff: Feature Reuse for Universal Training-free Acceleration of Diffusion Models | - | - | Pohang University of Science and Technology | [Paper](https://arxiv.org/pdf/2312.03517) | [Code](https://github.com/Jungwon-Lee/FRDiff) |
| 2024.10 | - | FasterCache | FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality | - | - | - | [Paper](https://arxiv.org/pdf/2410.19355) | [Code](https://github.com/Vchitect/FasterCache) |
| 2024.10 | ICLR 2025 | ToCa | ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching | DiT | - | Shanghai Jiao Tong University | - | - |
| 2024.11 | - | AdaCache | Adaptive Caching for Faster Video Generation with Diffusion Transformers | - | Video Generation | Meta | [Paper](https://adacache-dit.github.io/clarity/adacache_meta.pdf) | [Code](https://github.com/AdaCache-DiT/AdaCache) |
| 2024.11 | CVPR 2025 | TeaCache | Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model | - | Image Generation, Video Generation | Alibaba | [Paper](https://arxiv.org/pdf/2411.19108) | [Code](https://github.com/LiewFeng/TeaCache) |
| 2024.11 | - | LazyDiT | LazyDiT: Lazy Learning for the Acceleration of Diffusion Transformers | DiT | Video Generation | Adobe Research | [Paper](https://arxiv.org/pdf/2412.12444) | - |
| 2024.11 | - | Ca2-VDM | Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing | - | - | - | [Paper](https://arxiv.org/pdf/2411.16375) | [Code](https://github.com/Dawn-LX/CausalCache-VDM/) |
| 2024.11 | - | SmoothCache | SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers | - | - | Roblox | [Paper](https://arxiv.org/pdf/2411.10510) | [Code](https://github.com/Roblox/SmoothCache) |
| 2024.11 | - | SkipCache | Accelerating Vision Diffusion Transformers with Skip Branches | - | - | Shanghai Jiao Tong University | - | - |
| 2024.12 | ICLR 2025 | DuCa | Accelerating Diffusion Transformers with Dual Feature Caching | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | - |
| 2025.01 | - | FBCache | Fastest HunyuanVideo Inference with Context Parallelism and First Block Cache on NVIDIA L20 GPUs | - | - | - | - | - |
| 2025.01 | - | FlexCache | FlexCache: Flexible Approximate Cache System for Video Diffusion | - | - | - | - | - |
| 2025.01 | - | DaTo | Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free | - | - | Shanghai Jiao Tong University | [Paper](https://arxiv.org/pdf/2501.00375) | - |
| 2025.02 | - | PAB | Real-Time Video Generation with Pyramid Attention Broadcast | - | - | National University of Singapore | [Paper](https://arxiv.org/pdf/2408.12588) | [Code](https://github.com/NUS-HPC-AI-Lab/OpenDiT) |
| 2025.03 | ICCV 2025 | TaylorSeer | From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/TaylorSeer) |
| 2025.03 | - | FEB-Cache | FEB-Cache: Frequency-Guided Exposure Bias Reduction for Enhancing Diffusion Transformer Caching | - | - | University of Science and Technology of China | [Paper](https://arxiv.org/pdf/2503.07120) | [Code](https://github.com/aSleepyTree/EB-Cache) |
| 2025.03 | - | CacheQuant | CacheQuant: Comprehensively Accelerated Diffusion Models | - | - | University of Chinese Academy of Sciences | [Paper](https://arxiv.org/pdf/2503.01323) | [Code](https://github.com/BienLuky/CacheQuant) |
| 2025.03 | - | QuantCache | QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation | - | - | Shanghai Jiao Tong University | [Paper](https://arxiv.org/pdf/2503.06545) | [Code](https://github.com/JunyiWuCode/QuantCache) |
| 2025.04 | - | AB-Cache | AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse | - | - | - | - | - |
| 2025.04 | ACM MM 2025 | ClusCa | Compute only 16 tokens in one timestep: Accelerating Diffusion Transformers with Cluster-Driven Feature Caching | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/zhixin-zheng/ClusCa) |
| 2025.04 | ACM MM 2025 | SpeCa | SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.04 | - | FeMO | Accelerate Diffusion Transformers with Feature Momentum | DiT | Image Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.04 | - | ICC | Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition | - | - | Peking University | [Paper](https://arxiv.org/pdf/2505.05829) | [Code](https://github.com/ccccczzy/icc) |
| 2025.05 | - | FastCache | FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation | - | - | - | - | - |
| 2025.06 | - | DBPrune | DBPrune: Dynamic Block Prune with Residual Caching | - | - | Vipshop | - | - |
| 2025.06 | - | DBCache | DBCache: Dual Block Caching for Diffusion Transformers | - | - | Vipshop | - | - |
| 2025.06 | - | BACache | Block-wise Adaptive Caching for Accelerating Diffusion Policy | - | - | Peking University | [Paper](https://arxiv.org/pdf/2506.13456) | - |
| 2025.07 | - | FoCa | Forecast then Calibrate: Feature Caching as ODE for Efficient Diffusion Transformers | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | HiCache | HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | WaveEx | WaveEx: Accelerating Flow Matching-based Speech Generation via Wavelet-guided Extrapolation | - | Speech Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | GOC | Accelerating Diffusion Transformer via Gradient-Optimized Cache | - | - | University of Science and Technology of China | [Paper](https://arxiv.org/pdf/2503.05156) | [Code](https://github.com/qiujx0520/GOC_ICCV2025) |
| 2025.08 | - | TaoCache | TaoCache: Structure-Maintained Video Generation Acceleration | - | - | Huawei | [Paper](https://arxiv.org/pdf/2508.08978) | - |
| 2025.09 | - | Z-Cache | Z-Cache: Accelerating Diffusion Transformers via Self-Reflection | DiT | Image Generation, Video Generation | Shanghai Jiao Tong University | - | [Code](https://github.com/Shenyi-Z/Cache4Diffusion/) |

## 📈 Statistics

- **Total Papers**: 47
- **Our Group Papers**: 12
- **Papers with Code**: 25
- **Papers in Top Conferences**: 8

## 🎯 Research Directions

### Architecture Types
- **Unet-based**: 3 papers
- **DiT-based**: 15 papers
- **Others**: 29 papers

### Application Domains
- **Image Generation**: 15 papers
- **Video Generation**: 12 papers
- **Speech Generation**: 1 paper
- **General**: 19 papers

## 🔗 Useful Links

- [Paperlists.csv](./Paperlists.csv) - Complete paper list with detailed information

## 📝 How to Contribute

1. Fork this repository
2. Add new papers to `Paperlists.csv`
3. Update the README table
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Thanks to all researchers and contributors who have worked on diffusion model acceleration and caching techniques. 