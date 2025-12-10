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
| **Iso-Dream** | NIPS2022 | Iso-dream: Isolating and leveraging noncontrollable visual dynamics in world models | [[✓](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9316769afaaeeaad42a9e3633b14e801-Abstract-Conference.html)] | ✗ | [[✓](https://github.com/panmt/Iso-Dream)] | ✓ | ✓ | ✗ | 2.0 |
| **SEM2** | NIPS2022 | Model-based imitation learning for urban driving | [[✓](https://arxiv.org/abs/2210.04017)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **MILE** | NIPS2022 | SEM2: Enhance Sample Efficiency and Robustness of End-to-end Urban Autonomous Driving via Semantic Masked World Model | [[✓](https://proceedings.neurips.cc/paper_files/paper/2022/hash/827cb489449ea216e4a257c47e407d18-Abstract-Conference.html)] | ✗ | [[✓](https://github.com/wayveai/mile)] | ✓ | ✓ | ✗ | 2.0 |

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
| **SEM2** | TITS | Enhance Sample Efficiency and Robustness of End-to-end Urban Autonomous Driving via Semantic Masked World Model | [[✓](https://ieeexplore.ieee.org/abstract/document/10538211/)] | ✗ | [[✓](https://github.com/TRAILab/SEM2)] | ✓ | ✓ | ✗ | 2.0 |
| **Vista** | NeurIPS 2024 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [[✓](https://arxiv.org/abs/2405.17398)] | ✗ | [[✓](https://github.com/OpenDriveLab/Vista)] | ✓ | ✓ | ✗ | 2.0 |
| **SceneDiffuser** | NeurIPS 2024 | SceneDiffuser: Efficient and Controllable Driving Simulation Initialization and Rollout | [[✓](https://arxiv.org/abs/2412.12129)] | ✗ | [[✓](https://github.com/alipay/SceneDiffuser)] | ✓ | ✓ | ✗ | 2.0 |
| **DrivingDojo** | NeurIPS 2024 | DrivingDojo Dataset: Advancing Interactive and Knowledge-Enriched Driving World Model | [[✓](https://arxiv.org/abs/2410.10738)] | [[✓](https://drivingdojo.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Think2Drive** | ECCV 2024 | Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving | [[✓](https://arxiv.org/abs/2402.16720)] | ✗ | [[✓](https://github.com/trust-ai/Think2Drive)] | ✓ | ✓ | ✗ | 2.0 |
| **MARL-CCE** | ECCV 2024 | Modelling Competitive Behaviors in Autonomous Driving Under Generative World Model | [[✓](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05085.pdf)] | ✗ | [[✓](https://github.com/qiaoguanren/MARL-CCE)] | ✓ | ✗ | ✗ | 2.0 |
| **DriveDreamer** | ECCV 2024 | DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2309.09777)] | ✗ | [[✓](https://github.com/JeffWang987/DriveDreamer)] | ✓ | ✓ | ✓ | 2.0 |
| **GenAD** | ECCV 2024 | GenAD: Generative End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2402.11502)] | ✗ | [[✓](https://github.com/wzzheng/GenAD)] | ✓ | ✓ | ✓ | 2.0 |
| **OccWorld** | ECCV 2024 | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.16038)] | ✗ | [[✓](https://github.com/wzzheng/OccWorld)] | ✓ | ✓ | ✗ | 2.0 |
| **NeMo** | ECCV 2024 | Neural Volumetric World Models for Autonomous Driving | [[✓](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02571.pdf)] | ✗ | [[✓](https://github.com/MARS-Lab-CV/NeMo)] | ✓ | ✓ | ✓ | 2.0 |
| **CarFormer** | ECCV 2024 | CarFormer: Self-Driving with Learned Object-Centric Representations | [[✓](https://arxiv.org/abs/2407.15843)] | ✗ | [[✓](https://kuis-ai.github.io/CarFormer/)] | ✓ | ✓ | ✗ | 2.0 |
| **GUMP** | ECCV 2024 | GUMP: Solving Motion Planning Tasks with a Scalable Generative Model | [[✓](https://arxiv.org/abs/2407.02797)] | ✗ | [[✓](https://github.com/HorizonRobotics/GUMP/)] | ✓ | ✓ | ✗ | 2.0 |
| **DrivingDiffusion** | ECCV 2024 | DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model | [[✓](https://arxiv.org/abs/2310.07771)] | ✗ | [[✓](https://github.com/shalfun/DrivingDiffusion)] | ✓ | ✗ | ✓ | 2.0 |
| **3D-VLA** | ICML 2024 | 3D-VLA: A 3D Vision-Language-Action Generative World Model | [[✓](https://arxiv.org/abs/2403.09631)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **ViDAR** | CVPR 2024 | ViDAR: Visual Point Cloud Forecasting enables Scalable Autonomous Driving | [[✓](https://arxiv.org/abs/2312.17655)] | ✗ | [[✓](https://github.com/OpenDriveLab/ViDAR)] | ✓ | ✓ | ✓ | 2.0 |
| **GenAD** | CVPR 2024 | Generalized Predictive Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2403.09630)] | ✗ | [[Data](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file#genad-dataset-opendv-youtube)] | ✓ | ✓ | ✗ | 2.0 |
| **Cam4DOCC** | CVPR 2024 | Cam4DOCC: Benchmark for Camera-Only 4D Occupancy Forecasting in Autonomous Driving Applications | [[✓](https://arxiv.org/abs/2311.17663)] | ✗ | [[✓](https://github.com/haomo-ai/Cam4DOcc)] | ✓ | ✗ | ✗ | 2.0 |
| **Drive-WM** | CVPR 2024 | Drive-WM: Driving into the Future: Multiview Visual Forecasting and Planning with World Model | [[✓](https://arxiv.org/abs/2311.17918)] | ✗ | [[✓](https://github.com/BraveGroup/Drive-WM)] | ✓ | ✓ | ✗ | 2.0 |
| **DriveWorld** | CVPR 2024 | DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2405.04390)] | ✗ | [[✓](https://github.com/OpenDriveLab/DriveWorld)] | ✓ | ✓ | ✓ | 2.0 |
| **Panacea** | CVPR 2024 | Panacea: Panoramic and Controllable Video Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2311.16813)] | ✗ | [[✓](https://panacea-ad.github.io/)] | ✓ | ✗ | ✓ | 2.0 |
| **UnO** | CVPR 2024 | UnO: Unsupervised Occupancy Fields for Perception and Forecasting | [[✓](https://arxiv.org/abs/2406.08691)] | ✗ | [[✓](https://waabi.ai/research/uno)] | ✓ | ✗ | ✓ | 2.0 |
| **MagicDrive** | ICLR 2024 | MagicDrive: Street View Generation with Diverse 3D Geometry Control | [[✓](https://arxiv.org/abs/2310.02601)] | ✗ | [[✓](https://github.com/cure-lab/MagicDrive)] | ✓ | ✗ | ✓ | 2.0 |
| **Copilot4D** | ICLR 2024 | Copilot4D: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion | [[✓](https://arxiv.org/abs/2311.01017)] | ✗ | [[✓](https://github.com/edward19971023/Copilot4D)] | ✓ | ✗ | ✗ | 2.0 |
| **SafeDreamer** | ICLR 2024 | SafeDreamer: Safe Reinforcement Learning with World Models | [[✓](https://openreview.net/forum?id=tsE5HLYtYg)] | ✗ | [[✓](https://github.com/PKU-Alignment/SafeDreamer)] | ✓ | ✓ | ✗ | 2.0 |
| **DrivingWorld** | arXiv 2024.12 | DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT | [[✓](https://arxiv.org/abs/2412.19505)] | ✗ | [[✓](https://github.com/YvanYin/DrivingWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **DrivingGPT** | arXiv 2024.12 | DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers | [[✓](https://arxiv.org/abs/2412.18607)] | [[✓](https://rogerchern.github.io/DrivingGPT/)] | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DFIT-OccWorld** | arXiv 2024.12 | An Efficient Occupancy World Model via Decoupled Dynamic Flow and Image-assisted Training | [[✓](https://arxiv.org/abs/2412.13772)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Doe-1** | arXiv 2024.12 | Doe-1: Closed-Loop Autonomous Driving with Large World Model | [[✓](https://arxiv.org/abs/2412.09627)] | ✗ | [[✓](https://github.com/wzzheng/Doe)] | ✓ | ✓ | ✗ | 2.0 |
| **DrivePhysica** | arXiv 2024.12 | DrivePhysica: Physical Informed Driving World Model | [[✓](https://arxiv.org/abs/2412.08410)] | ✗ | [[✓](https://metadrivescape.github.io/papers_project/DrivePhysica/page.html)] | ✓ | ✗ | ✓ | 2.0 |
| **TERRA** | arXiv 2024.12 | TERRA ACT-Bench: Towards Action Controllable World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.05337)] | [[✓](https://turingmotors.github.io/actbench/)] | [[✓](https://github.com/turingmotors/ACT-Bench)] | ✓ | ✓ | ✗ | 2.0 |
| **UniMLVG** | arXiv 2024.12 | UniMLVG: Unified Framework for Multi-view Long Video Generation with Comprehensive Control Capabilities | [[✓](https://arxiv.org/abs/2412.04842)] | [[✓](https://sensetime-fvg.github.io/UniMLVG/)] | [[✓](https://github.com/SenseTime-FVG/OpenDWM)] | ✓ | ✗ | ✗ | 2.0 |
| **HoloDrive** | arXiv 2024.12 | HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for Autonomous Driving | [[✓](https://arxiv.org/abs/2412.01407)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **InfinityDrive** | arXiv 2024.12 | InfinityDrive: Breaking Time Limits in Driving World Models | [[✓](https://arxiv.org/abs/2412.01522)] | [[✓](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Imagine-2-Drive** | arXiv 2024.11 | Imagine-2-Drive: High-Fidelity World Modeling in CARLA for Autonomous Vehicles | [[✓](https://arxiv.org/abs/2411.10171)] | [[✓](https://anantagrg.github.io/Imagine-2-Drive.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **WorldSimBench** | arXiv 2024.10 | WorldSimBench: Towards Video Generation Models as World Simulator | [[✓](https://arxiv.org/abs/2410.18072)] | [[✓](https://iranqin.github.io/WorldSimBench.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DOME** | arXiv 2024.10 | DOME: Taming Diffusion Model into High-Fidelity Controllable Occupancy World Model | [[✓](https://arxiv.org/abs/2410.10429)] | [[✓](https://gusongen.github.io/DOME)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **OCCVAR** | OpenReview | OCCVAR: Scalable 4D Occupancy Prediction via Next-Scale Prediction | [[✓](https://openreview.net/forum?id=X2HnTFsFm8)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Popov et al.** | arXiv 2024.9 | Mitigating Covariate Shift in Imitation Learning for Autonomous Vehicles Using Latent Space Generative World Models | [[✓](https://arxiv.org/abs/2409.16663)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LatentDriver** | arXiv 2024.9 | LatentDriver: Learning Multiple Probabilistic Decisions from Latent World Model in Autonomous Driving | [[✓](https://arxiv.org/abs/2409.15730)] | ✗ | [[✓](https://github.com/Sephirex-X/LatentDriver)] | ✓ | ✓ | ✗ | 2.0 |
| **RenderWorld** | arXiv 2024.9 | RenderWorld: World Model with Self-Supervised 3D Label | [[✓](https://arxiv.org/abs/2409.11356)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **OccLLaMA** | arXiv 2024.9 | OccLLaMA: An Occupancy-Language-Action Generative World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2409.03272)] | ✗ | [[✓](https://github.com/sjtuycw/OccLLaMA)] | ✓ | ✓ | ✗ | 2.0 |
| **DriveGenVLM** | arXiv 2024.8 | DriveGenVLM: Real-world Video Generation for Vision Language Model based Autonomous Driving | [[✓](https://arxiv.org/abs/2408.16647)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Drive-OccWorld** | arXiv 2024.8 | Drive-OccWorld: Driving in the Occupancy World: Vision-Centric 4D Occupancy Forecasting and Planning | [[✓](https://arxiv.org/abs/2408.14197)] | ✗ | [[✓](https://github.com/HITSZ-Automated-Driving-Lab/Drive-OccWorld)] | ✓ | ✓ | ✗ | 2.0 |
| **BEVWorld** | arXiv 2024.7 | BEVWorld: A Multimodal World Model for Autonomous Driving via Unified BEV Latent Space | [[✓](https://arxiv.org/abs/2407.05679)] | ✗ | [[✓](https://github.com/zympsyche/BevWorld)] | ✓ | ✓ | ✓ | 2.0 |
| **TOKEN** | arXiv 2024.7 | Tokenize the World into Object-level Knowledge to Address Long-tail Events in Autonomous Driving | [[✓](https://arxiv.org/abs/2407.00959)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **UMAD** | arXiv 2024.6 | UMAD: Unsupervised Mask-Level Anomaly Detection for Autonomous Driving | [[✓](https://arxiv.org/abs/2406.06370)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **SimGen** | arXiv 2024.6 | SimGen: Simulator-conditioned Driving Scene Generation | [[✓](https://arxiv.org/abs/2406.09386)] | ✗ | [[✓](https://metadriverse.github.io/simgen/)] | ✓ | ✗ | ✗ | 2.0 |
| **AdaptiveDriver** | arXiv 2024.6 | AdaptiveDriver: Planning with Adaptive World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2406.10714)] | [[✓](https://arunbalajeev.github.io/world_models_planning/world_model_paper.html)] | [[✓](https://arunbalajeev.github.io/world_models_planning/world_model_paper.html)] | ✓ | ✓ | ✗ | 2.0 |
| **LAW** | arXiv 2024.6 | LAW: Enhancing End-to-End Autonomous Driving with Latent World Model | [[✓](https://arxiv.org/abs/2406.08481)] | ✗ | [[✓](https://github.com/BraveGroup/LAW)] | ✓ | ✓ | ✗ | 2.0 |
| **Delphi** | arXiv 2024.6 | Delphi: Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation | [[✓](https://arxiv.org/abs/2406.01349)] | ✗ | [[✓](https://github.com/westlake-autolab/Delphi)] | ✓ | ✗ | ✗ | 2.0 |
| **OccSora** | arXiv 2024.5 | OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving | [[✓](https://arxiv.org/abs/2405.20337)] | ✗ | [[✓](https://github.com/wzzheng/OccSora)] | ✓ | ✗ | ✗ | 2.0 |
| **MagicDrive3D** | arXiv 2024.5 | MagicDrive3D: Controllable 3D Generation for Any-View Rendering in Street Scenes | [[✓](https://arxiv.org/abs/2405.14475)] | ✗ | [[✓](https://gaoruiyuan.com/magicdrive3d/)] | ✓ | ✗ | ✗ | 2.0 |
| **CarDreamer** | arXiv 2024.5 | CarDreamer: Open-Source Learning Platform for World Model based Autonomous Driving | [[✓](https://arxiv.org/abs/2405.09111)] | ✗ | [[✓](https://github.com/ucd-dare/CarDreamer)] | ✓ | ✓ | ✗ | 2.0 |
| **DriveSim** | arXiv 2024.5 | DriveSim: Probing Multimodal LLMs as World Models for Driving | [[✓](https://arxiv.org/abs/2405.05956)] | ✗ | [[✓](https://github.com/sreeramsa/DriveSim)] | ✓ | ✗ | ✗ | 2.0 |
| **LidarDM** | arXiv 2024.4 | LidarDM: Generative LiDAR Simulation in a Generated World | [[✓](https://arxiv.org/abs/2404.02903)] | ✗ | [[✓](https://github.com/vzyrianov/lidardm)] | ✓ | ✗ | ✓ | 2.0 |
| **SubjectDrive** | arXiv 2024.3 | SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control | [[✓](https://arxiv.org/abs/2403.19438)] | [[✓](https://subjectdrive.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DriveDreamer-2** | arXiv 2024.3 | DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation | [[✓](https://arxiv.org/abs/2403.06845)] | ✗ | [[✓](https://drivedreamer2.github.io/)] | ✓ | ✗ | ✓ | 2.0 |

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
