# Awesome-Diffusion-Acceleration-Cache
## 项目描述
这是一个关于扩散模型加速缓存技术的研究论文、资源和进展的精选列表。

本仓库旨在提供一个全面且最新的学术工作集合，专注于扩散缓存——一种通过缓存中间特征或潜在状态来加速扩散模型的有前景的方法。它包括关于模型效率、内存优化、重用机制和基于扩散的生成系统中推理加速的论文。

## 📊 论文表格

| 发表时间 | 会议/期刊 | 方法名称 | 论文名称 | 架构 | 方向 | 论文单位 | 论文链接 | 代码仓库 |
|---------|-----------|----------|----------|------|------|----------|----------|----------|
| 2023.05 | AAAI 2024 | FISEdit | Accelerating Text-to-Image Editing via Cache-Enabled Sparse Diffusion Inference | Unet | 图片生成 | Peking University | [论文](https://arxiv.org/pdf/2305.17423) | [代码](https://github.com/Hankpipi/diffusers-hetu) |
| 2023.12 | - | DeepCache | DeepCache: Accelerating Diffusion Models for Free | Unet | - | National University of Singapore | [论文](https://arxiv.org/pdf/2312.00858) | [代码](https://github.com/horseee/DeepCache) |
| 2023.12 | - | Block Caching | Cache Me if You Can: Accelerating Diffusion Models through Block Caching | Unet | - | Meta GenAI | [论文](https://arxiv.org/pdf/2312.03209) | - |
| 2023.12 | - | Approximate Caching | Approximate Caching for Efficiently Serving Diffusion Models | - | - | Adobe | [论文](https://arxiv.org/pdf/2312.04429) | - |
| 2024.04 | - | T-GATE V1 | Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models | - | - | KAUST | [论文](https://arxiv.org/pdf/2404.02747v1) | [代码](https://github.com/HaozheLiu-ST/T-GATE) |
| 2024.04 | - | T-GATE V2 | Faster Diffusion via Temporal Attention Decomposition | - | - | KAUST | [论文](https://arxiv.org/pdf/2404.02747) | - |
| 2024.06 | - | Layer Caching | Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching | - | - | National University of Singapore | [论文](https://arxiv.org/pdf/2406.01733) | [代码](https://github.com/horseee/learning-to-cache/) |
| 2024.06 | - | ∆-DiT | ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers | DiT | 图片生成 | Fudan | [论文](https://arxiv.org/pdf/2406.01125) | - |
| 2024.07 | - | ElasticCache-LVLM | Efficient Inference of Vision Instruction-Following Models with Elastic Cache | - | - | Tsinghua | [论文](https://arxiv.org/pdf/2407.18121) | [代码](https://github.com/liuzuyan/ElasticCache) |
| 2024.07 | - | FORA | FORA: Fast-Forward Caching in Diffusion Transformer Acceleration | DiT | 图片生成 | Microsoft | [论文](https://arxiv.org/pdf/2407.01425) | [代码](https://github.com/prathebaselva/FORA) |
| 2024.07 | - | VCUT | Faster Image2Video Generation: A Closer Look at CLIP Image Embedding's Impact on Spatio-Temporal Cross-Attentions | - | - | The University of Western Australia | [论文](https://arxiv.org/pdf/2407.19205) | - |
| 2024.09 | - | TokenCache | Token Caching for Diffusion Transformer Acceleration | - | - | University of Chinese Academy of Sciences | [论文](https://arxiv.org/pdf/2409.18523) | - |
| 2024.09 | - | FRDiff | FRDiff: Feature Reuse for Universal Training-free Acceleration of Diffusion Models | - | - | Pohang University of Science and Technology | [论文](https://arxiv.org/pdf/2312.03517) | [代码](https://github.com/Jungwon-Lee/FRDiff) |
| 2024.10 | - | FasterCache | FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality | - | - | - | [论文](https://arxiv.org/pdf/2410.19355) | [代码](https://github.com/Vchitect/FasterCache) |
| 2024.10 | ICLR 2025 | ToCa | ToCa: Accelerating Diffusion Transformers with Token-wise Feature Caching | DiT | - | Shanghai Jiao Tong University | - | - |
| 2024.11 | - | AdaCache | Adaptive Caching for Faster Video Generation with Diffusion Transformers | - | 视频生成 | Meta | [论文](https://adacache-dit.github.io/clarity/adacache_meta.pdf) | [代码](https://github.com/AdaCache-DiT/AdaCache) |
| 2024.11 | CVPR 2025 | TeaCache | Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model | - | 图片生成, 视频生成 | Alibaba | [论文](https://arxiv.org/pdf/2411.19108) | [代码](https://github.com/LiewFeng/TeaCache) |
| 2024.11 | - | LazyDiT | LazyDiT: Lazy Learning for the Acceleration of Diffusion Transformers | DiT | 视频生成 | Adobe Research | [论文](https://arxiv.org/pdf/2412.12444) | - |
| 2024.11 | - | Ca2-VDM | Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing | - | - | - | [论文](https://arxiv.org/pdf/2411.16375) | [代码](https://github.com/Dawn-LX/CausalCache-VDM/) |
| 2024.11 | - | SmoothCache | SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers | - | - | Roblox | [论文](https://arxiv.org/pdf/2411.10510) | [代码](https://github.com/Roblox/SmoothCache) |
| 2024.11 | - | SkipCache | Accelerating Vision Diffusion Transformers with Skip Branches | - | - | Shanghai Jiao Tong University | - | - |
| 2024.12 | ICLR 2025 | DuCa | Accelerating Diffusion Transformers with Dual Feature Caching | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | - |
| 2025.01 | - | FBCache | Fastest HunyuanVideo Inference with Context Parallelism and First Block Cache on NVIDIA L20 GPUs | - | - | - | - | - |
| 2025.01 | - | FlexCache | FlexCache: Flexible Approximate Cache System for Video Diffusion | - | - | - | - | - |
| 2025.01 | - | DaTo | Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free | - | - | Shanghai Jiao Tong University | [论文](https://arxiv.org/pdf/2501.00375) | - |
| 2025.02 | - | PAB | Real-Time Video Generation with Pyramid Attention Broadcast | - | - | National University of Singapore | [论文](https://arxiv.org/pdf/2408.12588) | [代码](https://github.com/NUS-HPC-AI-Lab/OpenDiT) |
| 2025.03 | ICCV 2025 | TaylorSeer | From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/TaylorSeer) |
| 2025.03 | - | FEB-Cache | FEB-Cache: Frequency-Guided Exposure Bias Reduction for Enhancing Diffusion Transformer Caching | - | - | University of Science and Technology of China | [论文](https://arxiv.org/pdf/2503.07120) | [代码](https://github.com/aSleepyTree/EB-Cache) |
| 2025.03 | - | CacheQuant | CacheQuant: Comprehensively Accelerated Diffusion Models | - | - | University of Chinese Academy of Sciences | [论文](https://arxiv.org/pdf/2503.01323) | [代码](https://github.com/BienLuky/CacheQuant) |
| 2025.03 | - | QuantCache | QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation | - | - | Shanghai Jiao Tong University | [论文](https://arxiv.org/pdf/2503.06545) | [代码](https://github.com/JunyiWuCode/QuantCache) |
| 2025.04 | - | AB-Cache | AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse | - | - | - | - | - |
| 2025.04 | ACM MM 2025 | ClusCa | Compute only 16 tokens in one timestep: Accelerating Diffusion Transformers with Cluster-Driven Feature Caching | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/zhixin-zheng/ClusCa) |
| 2025.04 | ACM MM 2025 | SpeCa | SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.04 | - | FeMO | Accelerate Diffusion Transformers with Feature Momentum | DiT | 图片生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.04 | - | ICC | Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition | - | - | Peking University | [论文](https://arxiv.org/pdf/2505.05829) | [代码](https://github.com/ccccczzy/icc) |
| 2025.05 | - | FastCache | FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation | - | - | - | - | - |
| 2025.06 | - | DBPrune | DBPrune: Dynamic Block Prune with Residual Caching | - | - | Vipshop | - | - |
| 2025.06 | - | DBCache | DBCache: Dual Block Caching for Diffusion Transformers | - | - | Vipshop | - | - |
| 2025.06 | - | BACache | Block-wise Adaptive Caching for Accelerating Diffusion Policy | - | - | Peking University | [论文](https://arxiv.org/pdf/2506.13456) | - |
| 2025.07 | - | FoCa | Forecast then Calibrate: Feature Caching as ODE for Efficient Diffusion Transformers | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | HiCache | HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | WaveEx | WaveEx: Accelerating Flow Matching-based Speech Generation via Wavelet-guided Extrapolation | - | 语音生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |
| 2025.07 | - | GOC | Accelerating Diffusion Transformer via Gradient-Optimized Cache | - | - | University of Science and Technology of China | [论文](https://arxiv.org/pdf/2503.05156) | [代码](https://github.com/qiujx0520/GOC_ICCV2025) |
| 2025.08 | - | TaoCache | TaoCache: Structure-Maintained Video Generation Acceleration | - | - | Huawei | [论文](https://arxiv.org/pdf/2508.08978) | - |
| 2025.09 | - | Z-Cache | Z-Cache: Accelerating Diffusion Transformers via Self-Reflection | DiT | 图片生成, 视频生成 | Shanghai Jiao Tong University | - | [代码](https://github.com/Shenyi-Z/Cache4Diffusion/) |

## 📈 统计信息

- **总论文数**: 47
- **本组论文**: 12
- **有代码的论文**: 25
- **顶级会议论文**: 8

## 🎯 研究方向

### 架构类型
- **Unet-based**: 3篇论文
- **DiT-based**: 15篇论文
- **其他**: 29篇论文

### 应用领域
- **图片生成**: 15篇论文
- **视频生成**: 12篇论文
- **语音生成**: 1篇论文
- **通用**: 19篇论文

## 🔗 有用链接

- [Paperlists.csv](./Paperlists.csv) - 包含详细信息的完整论文列表

## 📝 如何贡献

1. Fork 本仓库
2. 在 `Paperlists.csv` 中添加新论文
3. 更新 README 表格
4. 提交 pull request

## 📄 许可证

本项目采用 MIT 许可证 - 详情请参见 [LICENSE](LICENSE) 文件。

## 🙏 致谢

感谢所有致力于扩散模型加速和缓存技术研究的研究者和贡献者。 