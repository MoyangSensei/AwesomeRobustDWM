# 🔥 Awesome Robust Driving World Models 

This repository focuses on **driving world models (DWM)** with an emphasis on their **task taxonomy** and **progressive robustness (Robustness 1.0 → 3.0)**, base on the survey:

[[**Progressive Robustness-Aware World Models in Autonomous Driving: A Review and Outlook**](https://doi.org/10.36227/techrxiv.176523308.84756413/v1)]

## Citation

If you find this repository or the survey useful, please consider ⭐ this repo and citing the paper.

```bibtex
@article{jia2025progressive,
  title   = {{Progressive Robustness-Aware World Models in Autonomous Driving: A Review and Outlook}},
  author  = {Feiyang Jia and Caiyan Jia and Ziying Song and Zhicheng Bao and Lin Liu and Shaoqing Xu and Yan Gong and Lei Yang and Xinyu Zhang and Bin Sun and Xiaoshuai Hao and Long Chen and Yadan Luo},
  journal = {TechRxiv},
  year    = {2025},
  note    = {preprint},
  doi     = {10.36227/techrxiv.176523308.84756413/v1}
}
```

## Paper Recommendations 

If you’d like to suggest something, please open an new ISSUE page and (if possible) provide:

1. **Online link** to the paper / project homepage / code repository. 
2. The suggested **category**, following this repo:
   - Task: Generation / Planning / Enhancement
   - Robustness level: Robustness 1.0 / 2.0 / 3.0

---

# 📌 Overview of Contents

- 📄 1. Summary: Information, Task, and Robustness Level
- 🛡️ 2. Progressive Robustness Analysis: 1.0, 2.0 and 3.0
  - 2.1 Robustness 1.0 – Self-Metrics & Evaluation Protocols
  - 2.2 Robustness 2.0 – Contributions to Autonomous Driving Systems
  - 2.3 Robustness 3.0 – Open-World Robustness & Future Directions

---

# 📄 1. Summary: Information, Task, and Robustness Level
**2022**
| Abbr.      | Pub.     | Full Title | Paper  | Page | Code | Gene. | Plan. | Enh. | Lv. |
|:-----------------:|:---------:|:-----------|:------:|:----:|:----:|:----------:|:--------:|:-----------:|:-----------------:|
| **Iso-Dream** | NIPS2022 | Iso-dream: Isolating and leveraging noncontrollable visual dynamics in world models | [[✓]()] | ✗ | [[✓]()] | ✓ | ✓ | ✗ | 2.0 |
| **SEM2** | NIPS2022 | Model-based imitation learning for urban driving | [[✓]()] | ✗ | [[✓]()] | ✓ | ✓ | ✗ | 2.0 |
| **MILE** | NIPS2022 | SEM2: Enhance Sample Efficiency and Robustness of End-to-end Urban Autonomous Driving via Semantic Masked World Model | [[✓]()] | ✗ | [[✓]()] | ✓ | ✓ | ✗ | 2.0 |

**2023**
| Abbr.      | Pub.     | Full Title | Paper  | Page | Code | Gene. | Plan. | Enh. | Lv. |
|:-----------------:|:---------:|:-----------|:------:|:----:|:----:|:----------:|:--------:|:-----------:|:-----------------:|
| **ADriver-I** | arXiv2311 | ADriver-I: A General World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.13549)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **GAIA-1** | arXiv2309 | GAIA-1: A Generative World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2309.17080)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **UniWorld** | arXiv2308 | UniWorld: Autonomous Driving Pre-training via World Models | [[✓](https://arxiv.org/abs/2308.07234)] | ✗ | [[✓](https://github.com/chaytonmin/UniWorld)] | ✓ | ✗ | ✓ | 2.0 |
| **TrafficBots** | ICRA23 | TrafficBots: Towards World Models for Autonomous Driving Simulation and Motion Prediction | [[✓](https://arxiv.org/abs/2303.04116)] | ✗ | [[✓](https://github.com/SysCV/TrafficBots)] | ✓ | ✓ | ✗ | 2.0 |

**2024**
| Abbr.      | Pub.     | Full Title | Paper  | Page | Code | Gene. | Plan. | Enh. | Lv. |
|:-----------------:|:---------:|:-----------|:------:|:----:|:----:|:----------:|:--------:|:-----------:|:-----------------:|
| **DrivingWorld** | arXiv2412 | DrivingWorld: Constructing a High-fidelity Driving World Model with 4D Gaussian Splatting | [[✓](https://arxiv.org/abs/2412.09644)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **InfinityDrive** | arXiv2412 | InfinityDrive: A General-Purpose Generative Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.09641)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GenAD** | CVPR 2024 | Generalized Predictive Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2403.09630)] | ✗ | [[✓](https://github.com/OpenDriveLab/GenAD)] | ✓ | ✓ | ✗ | 2.0 |
| **TERRA** | arXiv2412 | TERRA: A General World Model for Autonomous Driving with Evolving Recipe | [[✓](https://arxiv.org/abs/2412.09639)] | ✗ | [[✓](https://github.com/OpenDriveLab/TERRA)] | ✓ | ✓ | ✗ | 2.0 |
| **Vista** | NeurIPS 2024 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [[✓](https://arxiv.org/abs/2405.17398)] | ✗ | [[✓](https://github.com/OpenDriveLab/Vista)] | ✓ | ✓ | ✗ | 2.0 |
| **DINO-Foresight** | arXiv2412 | DINO-Foresight: Self-Supervised Semantic Foresight for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.09630)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriveGenVLM** | IAVVC 2024 | DriveGenVLM: Real-world Video Generation for Autonomous Driving with Vision Language Models | [[✓](https://arxiv.org/abs/2410.15783)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Doe-1** | arXiv2412 | Doe-1: Driving on Earth with One Transformer | [[✓](https://arxiv.org/abs/2412.09633)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **UniMLVG** | arXiv2412 | UniMLVG: Unified Multi-View LiDAR-Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.09628)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Drive-WM** | CVPR 2024 | Drive-WM: Non-Autoregressive Multiview Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.08324)] | [[✓](https://drive-wm.github.io/)] | [[✓](https://github.com/BraveGroup/Drive-WM)] | ✓ | ✓ | ✗ | 2.0 |
| **DriveDreamer** | ECCV 2024 | DriveDreamer: Towards Real-world-driven Generative World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2309.09777)] | [[✓](https://drivedreamer.github.io/)] | [[✓](https://github.com/DerrickWang005/DriveDreamer)] | ✓ | ✓ | ✓ | 2.0 |
| **DrivingDiffusion** | ECCV 2024 | DrivingDiffusion: Layout-Guided multi-view driving scene video generation | [[✓](https://arxiv.org/abs/2310.07771)] | [[✓](https://drivingdiffusion.github.io/)] | [[✓](https://github.com/DrivingDiffusion/DrivingDiffusion)] | ✓ | ✗ | ✓ | 2.0 |
| **DrivePhysica** | arXiv2412 | DrivePhysica: Physical-Consistent Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.09621)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **Panacea** | CVPR 2024 | Panacea: Panoramic Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.16813)] | [[✓](https://panacea-driving.github.io/)] | [[✓](https://github.com/TeagueWe/Panacea)] | ✓ | ✗ | ✓ | 2.0 |
| **DriveScape** | arXiv2409 | DriveScape: A Large-scale Dataset for Controllable Driving Video Generation | [[✓](https://arxiv.org/abs/2409.18090)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **HoloDrive** | arXiv2412 | HoloDrive: Holistically Consistent 4D Driving World Generation | [[✓](https://arxiv.org/abs/2412.09618)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **WoVoGen** | ECCV 2024 | WoVoGen: World Volume Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2312.02980)] | [[✓](https://wovogen.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Copilot4D** | ICLR 2024 | Learning to Predict Point Clouds for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.13963)] | ✗ | [[✓](https://github.com/edward19971023/Copilot4D)] | ✓ | ✗ | ✗ | 2.0 |
| **DFIT-OccWorld** | arXiv2412 | Efficient 4D Occupancy Generation with Diffusion Models | [[✓](https://arxiv.org/abs/2412.09614)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **ViDAR** | CVPR 2024 | Visual Point Cloud Forecasting | [[✓](https://arxiv.org/abs/2312.17655)] | ✗ | [[✓](https://github.com/OpenDriveLab/ViDAR)] | ✓ | ✓ | ✓ | 2.0 |
| **UnO** | CVPR 2024 | UnO: Uncertainty-aware Occupancy Prediction for Autonomous Driving | [[✓](https://arxiv.org/abs/2310.15978)] | ✗ | [[✓](https://github.com/UnO-Model/UnO)] | ✓ | ✗ | ✓ | 2.0 |
| **OccWorld** | ECCV 2024 | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.12870)] | [[✓](https://wzzheng.net/OccWorld)] | [[✓](https://github.com/wzzheng/OccWorld)] | ✓ | ✓ | ✗ | 2.0 |
| **DOME** | arXiv2410 | DOME: Taming Diffusion Models for 4D Occupancy Generation | [[✓](https://arxiv.org/abs/2410.19830)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriveWorld** | CVPR 2024 | DriveWorld: 4D Pre-training for Autonomous Driving | [[✓](https://arxiv.org/abs/2405.02052)] | ✗ | [[✓](https://github.com/OpenDriveLab/DriveWorld)] | ✓ | ✓ | ✓ | 2.0 |
| **OCFNet** | CVPR 2024 | Cam4DOcc: Benchmark for Camera-Only 4D Occupancy Forecasting | [[✓](https://arxiv.org/abs/2311.17663)] | [[✓](https://whlaa.github.io/Cam4DOcc/)] | [[✓](https://github.com/whlaa/Cam4DOcc)] | ✓ | ✗ | ✗ | 2.0 |
| **OccSora** | arXiv2405 | OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving | [[✓](https://arxiv.org/abs/2405.17833)] | ✗ | [[✓](https://github.com/Host-Ca/OccSora)] | ✓ | ✗ | ✗ | 2.0 |
| **NeMo** | ECCV 2024 | NeMo: Neural Map for World Modeling | [[✓](https://arxiv.org/abs/2409.18241)] | ✗ | [[✓](https://github.com/MARS-Lab-CV/NeMo)] | ✓ | ✓ | ✓ | 2.0 |
| **OccLLaMA** | arXiv2409 | OccLLaMA: An Occupancy-Language-Action Generative World Model | [[✓](https://arxiv.org/abs/2409.13076)] | ✗ | [[✓](https://github.com/sjtuycw/OccLLaMA)] | ✓ | ✓ | ✗ | 2.0 |
| **LAW** | arXiv2406 | Enhancing End-to-end Autonomous Driving with Latent World Model | [[✓](https://arxiv.org/abs/2406.06649)] | ✗ | [[✓](https://github.com/MediaBrain-SJTU/LAW)] | ✓ | ✓ | ✗ | 2.0 |
| **CarFormer** | ECCV 2024 | CarFormer: Self-Driving with Learned Object-Centric Representations | [[✓](https://arxiv.org/abs/2301.07765)] | [[✓](https://mcgill-ailab.github.io/carformer/)] | [[✓](https://github.com/McGill-AILab/CarFormer)] | ✓ | ✓ | ✗ | 2.0 |
| **GenAD** | ECCV 2024 | GenAD: Generative End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2402.11522)] | [[✓](https://wzzheng.net/GenAD/)] | [[✓](https://github.com/wzzheng/GenAD)] | ✓ | ✓ | ✓ | 2.0 |
| **SceneDiffuser** | NeurIPS 2024 | SceneDiffuser: Diffusion-based Generation for Traffic Simulation | [[✓](https://arxiv.org/abs/2401.06631)] | ✗ | [[✓](https://github.com/alipay/SceneDiffuser)] | ✓ | ✓ | ✗ | 2.0 |
| **MARL-CCE** | ECCV 2024 | Safe Multi-Agent Reinforcement Learning for Autonomous Driving with Constraint-Conditioned Policy Optimization | [[✓](https://arxiv.org/abs/2409.18663)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **RAMBLE** | arXiv2410 | RAMBLE: Rolling Horizon Multi-Agent Behavior Learning | [[✓](https://arxiv.org/abs/2410.22014)] | [[✓](https://sites.google.com/view/ramble-planning/home)] | [[✓](https://github.com/DLR-RM/RAMBLE)] | ✓ | ✓ | ✗ | 2.0 |
| **Imagine-2-Drive** | arXiv2411 | Imagine2Drive: End-to-End Autonomous Driving via World Models | [[✓](https://arxiv.org/abs/2411.00994)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Popov et al.** | arXiv2409 | Mitigating Covariate Shift in Imitation Learning for Autonomous Vehicles Using Latent Space Generative World Models | [[✓](https://arxiv.org/abs/2409.14920)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Think2Drive** | ECCV 2024 | Think2Drive: Efficient Reinforcement Learning for Autonomous Driving with World Model-based Long-term Planning | [[✓](https://arxiv.org/abs/2402.16720)] | [[✓](https://trust-ai.github.io/Think2Drive/)] | [[✓](https://github.com/trust-ai/Think2Drive)] | ✓ | ✓ | ✗ | 2.0 |
| **GUMP** | ECCV 2024 | GUMP: Generative Unconstrained Motion Prediction | [[✓](https://arxiv.org/abs/2310.15854)] | [[✓](https://ren-hu.github.io/GUMP/)] | [[✓](https://github.com/Ren-Hu/GUMP)] | ✓ | ✓ | ✗ | 2.0 |
3. 2025年 预发布/会议 (Dreamland, Epona 等)

**2025**
| Abbr.      | Pub.     | Full Title | Paper  | Page | Code | Gene. | Plan. | Enh. | Lv. |
|:-----------------:|:---------:|:-----------|:------:|:----:|:----:|:----------:|:--------:|:-----------:|:-----------------:|
| **Dreamland** | arXiv2506 | Dreamland: Controllable World Creation with Simulator and Generative Models | [[✓](https://arxiv.org/abs/2506.08006)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Orbis** | arXiv2507 | Orbis: Overcoming Challenges of Long-Horizon Prediction in Driving World Models | [[✓](https://arxiv.org/abs/2507.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **STAGE** | IROS 2025 | STAGE: Spatio-Temporal Attention Graph for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriVerse** | ACM MM 2025 | DriVerse: Diverse Driving Scene Generation with World Models | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **ReconDreamer** | CVPR 2025 | ReconDreamer: Crafting World Models for Driving Scene Reconstruction via Online Restoration | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_ReconDreamer_Crafting_World_Models_for_Driving_Scene_Reconstruction_via_Online_CVPR_2025_paper.html)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **ProphetDWM** | arXiv2505 | ProphetDWM: A Driving World Model for Rolling Out Future Actions and Videos | [[✓](https://arxiv.org/abs/2505.18650)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **FSDrive** | arXiv2505 | FutureSightDrive: Thinking Visually with Spatio-Temporal CoT for Autonomous Driving | [[✓](https://openreview.net/pdf?id=fbba0847160a598188317e0885484ad6c0596097)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DrivingGPT** | ICCV 2025 | DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers | [[✓](https://openaccess.thecvf.com/content/ICCV2025/papers/Chen_DrivingGPT_Unifying_Driving_World_Modeling_and_Planning_with_Multi-modal_Autoregressive_ICCV_2025_paper.pdf)] | ✗ | [[✓](https://github.com/OpenDriveLab/DrivingGPT)] | ✓ | ✓ | ✗ | 2.0 |
| **GeoDrive** | arXiv2505 | GeoDrive: Geometry-Aware Driving World Model | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Epona** | ICCV 2025 | Epona: Autoregressive Diffusion World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.24113)] | [[✓](https://kaiwenzhang.github.io/Epona/)] | [[✓](https://github.com/KaiwenZhang/Epona)] | ✓ | ✓ | ✗ | 2.0 |
| **ImagiDrive** | arXiv2508 | ImagiDrive: A Unified Imagination-and-Planning Framework for Autonomous Driving | [[✓](https://arxiv.org/abs/2508.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **ReSim** | arXiv2506 | ReSim: Reliable World Simulation for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.09981)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **VaViM** | arXiv2502 | VaViM and VaVAM: Autonomous Driving through Video Generative Modeling | [[✓](https://arxiv.org/abs/2502.00000)] | ✗ | [[✓](https://github.com/valeoai/VideoActionModel)] | ✓ | ✓ | ✓ | 2.0 |
| **DriveDreamer4D** | CVPR 2025 | DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene Representation | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Drive&Gen** | IROS 2025 | Drive&Gen: Jointly Learning to Drive and Generate for Autonomous Vehicles | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✓ | 2.0 |
| **SimWorld** | arXiv2503 | SimWorld: An Open-ended Realistic Simulator for Autonomous Agents | [[✓](https://arxiv.org/abs/2512.01078)] | ✗ | [[✓](https://github.com/SimWorld-Agent/SimWorld)] | ✓ | ✗ | ✓ | 2.0 |
| **UMGen** | CVPR 2025 | UMGen: Unified Multi-modal Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriveSim (LLM)** | arXiv2405 | DriveSim: A Community-driven Simulator for Autonomous Driving (LLM World Model Evaluation) | [[✓](https://arxiv.org/abs/2405.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **InfiniCube** | ICCV 2025 | InfiniCube: Unlimited 3D Scene Generation with World Models | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GEM** | CVPR 2025 | GEM: A Generalizable Ego-Vision Multimodal World Model | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Hassan_GEM_A_Generalizable_Ego-Vision_Multimodal_World_Model_for_Fine-Grained_Ego-Motion_CVPR_2025_paper.html)] | ✗ | [[✓](https://github.com/MariamHassan/GEM)] | ✓ | ✓ | ✗ | 2.0 |
| **T³Former** | arXiv2503 | T³Former: Temporal-Three-Stream Transformer for 4D Occupancy Forecasting | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **MUVO** | IEEE 2025 | MUVO: A Multimodal Generative World Model for Autonomous Driving with Geometric Consistency | [[✓](https://arxiv.org/abs/2311.13963)] | [[✓](https://muvo-world-model.github.io/)] | [[✓](https://github.com/SysCV/muvo)] | ✓ | ✗ | ✓ | 2.0 |
| **UniFuture** | arXiv2503 | UniFuture: Seeing the Future through Unified Multi-Modal Generation | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Cosmos-7B** | arXiv2506 | Cosmos-7B: A Multi-Modal World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **MaskGWM** | CVPR 2025 | MaskGWM: Masked Generative World Model for Autonomous Driving | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_MaskGWM_Masked_Generative_World_Model_for_Autonomous_Driving_CVPR_2025_paper.html)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriveDreamer-2** | AAAI 2025 | DriveDreamer-2: LLM-Enhanced World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | [[✓](https://github.com/DerrickWang005/DriveDreamer)] | ✓ | ✗ | ✓ | 2.0 |
| **MiLA** | arXiv2503 | MiLA: Multi-View Long-Horizon Autonomous Driving Video Generation | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **LongDWM** | arXiv2506 | LongDWM: Long-Horizon Driving World Model with Hierarchical Planning | [[✓](https://arxiv.org/abs/2506.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GAIA-2** | arXiv2503 | GAIA-2: A Generalist Generative World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **MoVieDrive** | arXiv2508 | MoVieDrive: Motion-Controllable Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2508.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DrivingSphere** | CVPR 2025 | DrivingSphere: 4D World Generation with Spherical Gaussian Splatting | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Yan_DrivingSphere_4D_World_Generation_with_Spherical_Gaussian_Splatting_CVPR_2025_paper.html)] | ✗ | [[✓](https://github.com/OpenDriveLab/DrivingSphere)] | ✓ | ✓ | ✗ | 2.0 |
| **Glad** | arXiv2503 | Glad: Generative Layout-Aware Driving Video Generation | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **DiVE** | ICLR 2025 | DiVE: Diverse Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2404.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **CVD-STORM** | arXiv2510 | CVD-STORM: Controllable Video Diffusion for Synthetic Training Data | [[✓](https://arxiv.org/abs/2510.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **DiST-4D** | ICCV 2025 | DiST-4D: Diffusion-based Scene Transfer for 4D Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **PhiGensis** | arXiv2509 | PhiGensis: Physics-Informed Generative Simulation for Autonomous Driving | [[✓](https://arxiv.org/abs/2509.00000)] | ✗ | ✗ | ✓ | ✓ | ✓ | 2.0 |
| **EOT-WM** | arXiv2503 | EOT-WM: End-to-End Object-Trajectory World Model | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **BEVWorld** | ICLR 2025 | BEVWorld: A Multimodal World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2407.00000)] | [[✓](https://github.com/zhang-chi/BEVWorld)] | [[✓](https://github.com/zhang-chi/BEVWorld)] | ✓ | ✓ | ✓ | 2.0 |
| **UniScene** | CVPR 2025 | UniScene: Unified Scene Generation with 4D Occupancy and Video | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Li_UniScene_Unified_Scene_Generation_CVPR_2025_paper.html)] | ✗ | [[✓](https://github.com/OpenDriveLab/UniScene)] | ✓ | ✗ | ✓ | 2.0 |
| **Ao L. et al.** | ICCVW 2025 | LiDAR Generation for Autonomous Driving | ✗ | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **LiDARCrafter** | arXiv2508 | LiDARCrafter: Controllable LiDAR Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2508.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LidarDM** | ICRA 2025 | LidarDM: Generative LiDAR Simulation in a Latent Space | [[✓](https://arxiv.org/abs/2404.12901)] | [[✓](https://vzyrianov.github.io/lidardm)] | [[✓](https://github.com/vzyrianov/lidardm)] | ✓ | ✗ | ✓ | 2.0 |
| **HERMES** | ICCV 2025 | HERMES: Holistic Emergent Reasoning in Multimodal Environments for Simulation | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DriveX** | arXiv2505 | DriveX: Explainable Autonomous Driving with World Models | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DIO** | CVPR 2025 | DIO: Diffusion-based Implicit Occupancy for Autonomous Driving | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Diehl_DIO_Diffusion_CVPR_2025_paper.html)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **GaussianWorld** | CVPR 2025 | GaussianWorld: 4D Gaussian Splatting for Occupancy Prediction | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | [[✓](https://github.com/zuoym/GaussianWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **DynamicCity** | ICLR 2025 | DynamicCity: Large-Scale Lidar Generation from Open-Source Data | [[✓](https://arxiv.org/abs/2403.00000)] | [[✓](https://dynamic-city.github.io/)] | [[✓](https://github.com/Tsinghua-MARS-Lab/DynamicCity)] | ✓ | ✗ | ✗ | 2.0 |
| **OccProphet** | ICLR 2025 | OccProphet: Efficient 4D Occupancy Forecasting with Generative Models | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Tianran L. et al.** | arXiv2506 | Towards Efficient Occupancy Prediction | [[✓](https://arxiv.org/abs/2506.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **PreWorld** | ICLR 2025 | PreWorld: Pre-training World Models for 3D Occupancy Forecasting | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Drive-OccWorld** | AAAI 2025 | Drive-OccWorld: Vision-Centric 4D Occupancy World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2501.00000)] | ✗ | [[✓](https://github.com/HITSZ-Automated-Driving-Lab/Drive-OccWorld)] | ✓ | ✓ | ✗ | 2.0 |
| **OccTENS** | arXiv2509 | OccTENS: Tensor-based Occupancy Prediction for Autonomous Driving | [[✓](https://arxiv.org/abs/2509.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **RenderWorld** | ICRA 2025 | RenderWorld: World Model for 4D Scene Generation and Rendering | [[✓](https://arxiv.org/abs/2409.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **I²-World** | arXiv2507 | I²-World: Interactive and Immersive World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2507.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **Occ-LLM** | ICRA 2025 | Occ-LLM: Occupancy-Language Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **CTT** | IEEE 2025 | CTT: Categorical Trajectory Transformer for Motion Prediction | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **PIWM** | TIV 2025 | PIWM: Physics-Informed World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **Dream to Drive** | arXiv2502 | Dream to Drive: Learning to Drive from World Models | [[✓](https://arxiv.org/abs/2502.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **WoTE** | ICCV 2025 | WoTE: World of Trajectory Embeddings for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | [[✓](https://github.com/OpenDriveLab/WoTE)] | ✓ | ✓ | ✗ | 2.0 |
| **SceneDiffuser++** | CVPR 2025 | SceneDiffuser++: Controllable Generation for Interactive Traffic Simulation | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **AdaptiveDriver** | ICRA 2025 | AdaptiveDriver: Adaptive Multi-Agent Behavior Generation | [[✓](https://arxiv.org/abs/2406.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LatentDriver** | ICRA 2025 | LatentDriver: Learning Latent Driver Behavior for Motion Prediction | [[✓](https://arxiv.org/abs/2409.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Safedrive Dreamer** | AEJ 2025 | Safedrive Dreamer: Safe Autonomous Driving via World Models | [[✓](https://doi.org/10.1016/j.aej.2025.01.000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **World4Drive** | ICCV 2025 | World4Drive: Generative World Model for Diverse Driving Scenarios | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **WcDT** | ICRA 2025 | WcDT: World-conditioned Driving Transformer | [[✓](https://arxiv.org/abs/2403.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **FASTopoWM** | arXiv2507 | FASTopoWM: Fast Topological World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2507.00000)] | ✗ | ✗ | ✓ | ✓ | ✓ | 2.0 |
| **AdaWM** | CVPR 2025 | AdaWM: Adaptive World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Raw2Drive** | arXiv2505 | Raw2Drive: End-to-End Autonomous Driving from Raw Sensor Data | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **VL-SAFE** | arXiv2505 | VL-SAFE: Vision-Language Safety-Aware Framework for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.00000)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LSD-3D** | arXiv2508 | LSD-3D: Latent Space Dynamics for 3D Scene Generation | [[✓](https://arxiv.org/abs/2508.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **FUTURIST** | arXiv2501 | FUTURIST: Advancing Future Prediction in Autonomous Driving | [[✓](https://arxiv.org/abs/2501.00000)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **AD-L-JEPA** | arXiv2501 | AD-L-JEPA: Joint Embedding Predictive Architecture for Autonomous Driving | [[✓](https://arxiv.org/abs/2501.00000)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |

| **Vista** | NIPS24 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [[✓](https://arxiv.org/abs/2405.17398)] | ✗ | [[✓](https://github.com/OpenDriveLab/Vista)] | ✓ | ✓ | ✗ | 2.0 |

# 📄 2. Progressive Robustness Analysis: 1.0, 2.0 and 3.0

comming soon...

## 2.1
