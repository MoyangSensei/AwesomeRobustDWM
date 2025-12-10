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
|:-------:|:------:|:-----------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:--------:|
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
| Abbr. | Pub. | Full Title | Paper | Page | Code | Gene. | Plan. | Enh. | Lv. |
| :---: | :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **HERMES** | ICCV 2025 | HERMES: A Unified Self-Driving World Model for Simultaneous 3D Scene Understanding and Generation | [[✓](https://arxiv.org/abs/2505.16394)] | [[✓](https://lmd0311.github.io/HERMES/)] | [[✓](https://github.com/LMD0311/HERMES)] | ✓ | ✓ | ✗ | 2.0 |
| **InfiniCube** | ICCV 2025 | InfiniCube: Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models | [[✓](https://arxiv.org/abs/2412.03934)] | [[✓](https://research.nvidia.com/labs/toronto-ai/infinicube/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **DiST-4D** | ICCV 2025 | DiST-4D: Disentangled Spatiotemporal Diffusion with Metric Depth for 4D Driving Scene Generation | [[✓](https://arxiv.org/abs/2503.15208)] | [[✓](https://royalmelon0505.github.io/DiST-4D/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Epona** | ICCV 2025 | Epona: Autoregressive Diffusion World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.24113)] | ✗ | [[✓](https://github.com/Kevin-thu/Epona/)] | ✓ | ✓ | ✗ | 2.0 |
| **UniOcc** | ICCV 2025 | UniOcc: A Unified Benchmark for Occupancy Forecasting and Prediction in Autonomous Driving | [[✓](https://arxiv.org/abs/2503.24381)] | ✗ | [[✓](https://uniocc.github.io/)] | ✓ | ✗ | ✗ | 2.0 |
| **World4Drive** | ICCV 2025 | World4Drive: End-to-End Autonomous Driving via Intention-aware Physical Latent World Model | [[✓](https://arxiv.org/abs/2507.00603)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DINO-Foresight** | NeurIPS 2025 | DINO-Foresight: Looking into the Future with DINO | [[✓](https://arxiv.org/abs/2412.11673)] | ✗ | [[✓](https://github.com/Sta8is/DINO-Foresight)] | ✓ | ✗ | ✗ | 2.0 |
| **PolicyWM** | NeurIPS 2025 | From Forecasting to Planning: Policy World Model for Collaborative State-Action Prediction | [[✓](https://arxiv.org/abs/2510.19654)] | ✗ | [[✓](https://github.com/6550Zhao/Policy-World-Model)] | ✓ | ✓ | ✗ | 2.0 |
| **DriVerse** | ACM MM 2025 | DriVerse: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment | [[✓](https://arxiv.org/abs/2504.19614)] | ✗ | [[✓](https://github.com/shalfun/DriVerse)] | ✓ | ✗ | ✗ | 2.0 |
| **PIWM** | TIV 2025 | PIWM: Dream to Drive with Predictive Individual World Model | [[✓](https://arxiv.org/abs/2501.16733)] | ✗ | [[✓](https://github.com/gaoyinfeng/PIWM)] | ✓ | ✗ | ✗ | 2.0 |
| **DriveDreamer4D** | CVPR 2025 | DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene Representation | [[✓](https://arxiv.org/abs/2410.13571)] | [[✓](https://drivedreamer4d.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GaussianWorld** | CVPR 2025 | GaussianWorld: Gaussian World Model for Streaming 3D Occupancy Prediction | [[✓](https://arxiv.org/abs/2412.10373)] | ✗ | [[✓](https://github.com/zuosc19/GaussianWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **ReconDreamer** | CVPR 2025 | ReconDreamer: Crafting World Models for Driving Scene Reconstruction via Online Restoration | [[✓](https://arxiv.org/abs/2411.19548)] | ✗ | [[✓](https://github.com/GigaAI-research/ReconDreamer)] | ✓ | ✗ | ✓ | 2.0 |
| **FUTURIST** | CVPR 2025 | FUTURIST: Advancing Semantic Future Prediction through Multimodal Visual Sequence Transformers | [[✓](https://arxiv.org/abs/2501.08303)] | ✗ | [[✓](https://github.com/Sta8is/FUTURIST)] | ✓ | ✗ | ✗ | 2.0 |
| **MaskGWM** | CVPR 2025 | MaskGWM: A Generalizable Driving World Model with Video Mask Reconstruction | [[✓](https://arxiv.org/abs/2502.11663)] | ✗ | [[✓](https://github.com/SenseTime-FVG/OpenDWM)] | ✓ | ✗ | ✗ | 2.0 |
| **UniScene** | CVPR 2025 | UniScene: Unified Occupancy-centric Driving Scene Generation | [[✓](https://arxiv.org/abs/2412.05435)] | [[✓](https://arlo0o.github.io/uniscene/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GEM** | CVPR 2025 | GEM: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control | [[✓](https://arxiv.org/abs/2412.11198)] | [[✓](https://vita-epfl.github.io/GEM.github.io/)] | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **UMGen** | CVPR 2025 | UMGen: Generating Multimodal Driving Scenes via Next-Scene Prediction | [[✓](https://arxiv.org/abs/2503.14945)] | [[✓](https://yanhaowu.github.io/UMGen/)] | [[✓](https://github.com/YanhaoWu/UMGen/)] | ✓ | ✗ | ✗ | 2.0 |
| **DIO** | CVPR 2025 | DIO: Decomposable Implicit 4D Occupancy-Flow World Model | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Diehl_DIO_Decomposable_Implicit_4D_Occupancy-Flow_World_Model_CVPR_2025_paper.html)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **SceneDiffuser++** | CVPR 2025 | SceneDiffuser++: City-Scale Traffic Simulation via a Generative World Model | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Tan_SceneDiffuser_City-Scale_Traffic_Simulation_via_a_Generative_World_Model_CVPR_2025_paper.html)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **DynamicCity** | ICLR 2025 | DynamicCity: Large-Scale LiDAR Generation from Dynamic Scenes | [[✓](https://arxiv.org/abs/2410.18084)] | ✗ | [[✓](https://github.com/3DTopia/DynamicCity)] | ✓ | ✗ | ✗ | 2.0 |
| **AdaWM** | ICLR 2025 | AdaWM: Adaptive World Model based Planning for Autonomous Driving | [[✓](https://arxiv.org/abs/2501.13072)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **OccProphet** | ICLR 2025 | OccProphet: Pushing Efficiency Frontier of Camera-Only 4D Occupancy Forecasting with Observer-Forecaster-Refiner Framework | [[✓](https://arxiv.org/abs/2502.15180)] | ✗ | [[✓](https://github.com/JLChen-C/OccProphet)] | ✓ | ✗ | ✗ | 2.0 |
| **PreWorld** | ICLR 2025 | PreWorld: Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2502.07309)] | ✗ | [[✓](https://github.com/getterupper/PreWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **SSR** | ICLR 2025 | SSR: Does End-to-End Autonomous Driving Really Need Perception Tasks? | [[✓](https://arxiv.org/abs/2409.18341)] | ✗ | [[✓](https://github.com/PeidongLi/SSR)] | ✗ | ✓ | ✗ | 2.0 |
| **Occ-LLM** | ICRA 2025 | Occ-LLM: Enhancing Autonomous Driving with Occupancy-Based Large Language Models | [[✓](https://arxiv.org/abs/2502.06419)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **STAGE** | IROS 2025 | STAGE: A Stream-Centric Generative World Model for Long-Horizon Driving-Scene Simulation | [[✓](https://arxiv.org/abs/2506.13138)] | [[✓](https://4dvlab.github.io/STAGE/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Drive&Gen** | IROS 2025 | Drive&Gen: Co-Evaluating End-to-End Driving and Video Generation Models | [[✓](https://arxiv.org/abs/2510.06209)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LiDAR-Seq** | ICCVW 2025 | Learning to Generate 4D LiDAR Sequences | [[✓](https://arxiv.org/abs/2509.11959)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Accident-WM** | Comms Eng 2025 | World model-based end-to-end scene generation for accident anticipation in autonomous driving | [[✓](https://www.nature.com/articles/s44172-025-00474-7)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **LiDAR-Nav** | JIFS 2025 | World Models for Autonomous Navigation of Terrestrial Robots from LIDAR Observations | [[✓](https://arxiv.org/abs/2512.03429)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **MindDrive** | arXiv 2025.12 | MindDrive: An All-in-One Framework Bridging World Models and Vision-Language Model for End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2512.04441)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **U4D** | arXiv 2025.12 | U4D: Uncertainty-Aware 4D World Modeling from LiDAR Sequences | [[✓](https://arxiv.org/abs/2512.02982)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **ThinkByDrive** | arXiv 2025.12 | Think Before You Drive: World Model-Inspired Multimodal Grounding for Autonomous Vehicles | [[✓](https://arxiv.org/abs/2512.03454)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **VD-WM** | arXiv 2025.12 | Vehicle Dynamics Embedded World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2512.02417)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **LiSTAR** | arXiv 2025.11 | LiSTAR: Ray-Centric World Models for 4D LiDAR Sequences in Autonomous Driving | [[✓](https://arxiv.org/abs/2511.16049)] | [[✓](https://ocean-luna.github.io/LiSTAR.gitub.io)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **OpenTwinMap** | arXiv 2025.11 | OpenTwinMap: An Open-Source Digital Twin Generator for Urban Autonomous Driving | [[✓](https://arxiv.org/abs/2511.21925)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **SparseWorld-TC** | arXiv 2025.11 | SparseWorld-TC: Trajectory-Conditioned Sparse Occupancy World Model | [[✓](https://arxiv.org/abs/2511.22039)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **LaGen** | arXiv 2025.11 | LaGen: Towards Autoregressive LiDAR Scene Generation | [[✓](https://arxiv.org/abs/2511.21256)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **AD-R1** | arXiv 2025.11 | AD-R1: Closed-Loop Reinforcement Learning for End-to-End Autonomous Driving with Impartial World Models | [[✓](https://arxiv.org/abs/2511.20325)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **CorrectAD** | arXiv 2025.11 | CorrectAD: A Self-Correcting Agentic System to Improve End-to-end Planning in Autonomous Driving | [[✓](https://arxiv.org/abs/2511.13297)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **UniScenev2** | arXiv 2025.10 | UniScenev2: Scaling Up Occupancy-centric Driving Scene Generation: Dataset and Method | [[✓](https://arxiv.org/abs/2510.22973)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Implicit-RWM** | arXiv 2025.10 | Vision-Centric 4D Occupancy Forecasting and Planning via Implicit Residual World Models | [[✓](https://arxiv.org/abs/2510.16729)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **SparseWorld** | arXiv 2025.10 | SparseWorld: A Flexible, Adaptive, and Efficient 4D Occupancy World Model Powered by Sparse and Dynamic Queries | [[✓](https://arxiv.org/abs/2510.17482)] | ✗ | [[✓](https://github.com/MSunDYY/SparseWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **OmniNWM** | arXiv 2025.10 | OmniNWM: Omniscient Driving Navigation World Models | [[✓](https://arxiv.org/abs/2510.18313)] | [[✓](https://arlo0o.github.io/OmniNWM/)] | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **ORAD-3D** | arXiv 2025.10 | ORAD-3D: Advancing Off-Road Autonomous Driving: The Large-Scale ORAD-3D Dataset and Comprehensive Benchmarks | [[✓](https://arxiv.org/abs/2510.16500)] | ✗ | [[✓](https://github.com/chaytonmin/ORAD-3D)] | ✓ | ✗ | ✓ | 2.0 |
| **Dream4Drive** | arXiv 2025.10 | Dream4Drive: Rethinking Driving World Model as Synthetic Data Generator for Perception Tasks | [[✓](https://arxiv.org/abs/2510.19195)] | [[✓](https://wm-research.github.io/Dream4Drive/)] | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **DriveVLA-W0** | arXiv 2025.10 | DriveVLA-W0: World Models Amplify Data Scaling Law in Autonomous Driving | [[✓](https://arxiv.org/abs/2510.12796)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **CoIRL-AD** | arXiv 2025.10 | CoIRL-AD: Collaborative-Competitive Imitation-Reinforcement Learning in Latent World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2510.12560)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **CVD-STORM** | arXiv 2025.10 | CVD-STORM: Cross-View Video Diffusion with Spatial-Temporal Reconstruction Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2510.07944)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **PhiGensis** | arXiv 2025.9 | PhiGensis: 4D Driving Scene Generation With Stereo Forcing | [[✓](https://arxiv.org/abs/2509.20251)] | [[✓](https://jiangxb98.github.io/PhiGensis/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **TeraSim-World** | arXiv 2025.9 | TeraSim-World: Worldwide Safety-Critical Data Synthesis for End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2509.13164)] | ✗ | ✗ | ✓ | ✗ | ✓ | 2.0 |
| **OccTENS** | arXiv 2025.9 | OccTENS: 3D Occupancy World Model via Temporal Next-Scale Prediction | [[✓](https://arxiv.org/abs/2509.03887)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **G^2Editor** | arXiv 2025.8 | G^2Editor: Realistic and Controllable 3D Gaussian-Guided Object Editing for Driving Video Generation | [[✓](https://arxiv.org/abs/2508.20471)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **LSD-3D** | arXiv 2025.8 | LSD-3D: Large-Scale 3D Driving Scene Generation with Geometry Grounding | [[✓](https://arxiv.org/abs/2508.19204)] | [[✓](https://princeton-computational-imaging.github.io/LSD-3D/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **VideoGen-FT** | arXiv 2025.8 | Seeing Clearly, Forgetting Deeply: Revisiting Fine-Tuned Video Generators for Driving Simulation | [[✓](https://arxiv.org/abs/2508.16512)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **MoVieDrive** | arXiv 2025.8 | MoVieDrive: Multi-Modal Multi-View Urban Scene Video Generation | [[✓](https://arxiv.org/abs/2508.14327)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **ImagiDrive** | arXiv 2025.8 | ImagiDrive: A Unified Imagination-and-Planning Framework for Autonomous Driving | [[✓](https://arxiv.org/abs/2508.11428)] | ✗ | [[✓](https://github.com/fudan-zvg/ImagiDrive)] | ✓ | ✓ | ✗ | 2.0 |
| **LiDARCrafter** | arXiv 2025.8 | LiDARCrafter: Dynamic 4D World Modeling from LiDAR Sequences | [[✓](https://arxiv.org/abs/2508.03692)] | [[✓](https://lidarcrafter.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **FASTopoWM** | arXiv 2025.7 | FASTopoWM: Fast-Slow Lane Segment Topology Reasoning with Latent World Models | [[✓](https://arxiv.org/abs/2507.23325)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Accident-WM** | arXiv 2025.7 | World Model-Based End-to-End Scene Generation for Accident Anticipation in Autonomous Driving | [[✓](https://arxiv.org/abs/2507.12762)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Orbis** | arXiv 2025.7 | Orbis: Overcoming Challenges of Long-Horizon Prediction in Driving World Models | [[✓](https://arxiv.org/abs/2507.13162)] | ✗ | [[✓](https://lmb-freiburg.github.io/orbis.github.io/)] | ✓ | ✗ | ✗ | 2.0 |
| **I2-World** | arXiv 2025.7 | I²-World: Intra-Inter Tokenization for Efficient Dynamic 4D Scene Forecasting | [[✓](https://arxiv.org/abs/2507.09144)] | ✗ | [[✓](https://github.com/lzzzzzm/II-World)] | ✓ | ✗ | ✗ | 2.0 |
| **NRSeg** | arXiv 2025.7 | NRSeg: Noise-Resilient Learning for BEV Semantic Segmentation via Driving World Models | [[✓](https://arxiv.org/abs/2507.04002)] | ✗ | [[✓](https://github.com/lynn-yu/NRSeg)] | ✓ | ✗ | ✓ | 2.0 |
| **LiDAR-FM** | arXiv 2025.6 | Towards foundational LiDAR world models with efficient latent flow matching | [[✓](https://arxiv.org/abs/2506.23434)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **ReSim** | arXiv 2025.6 | ReSim: Reliable World Simulation for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.09981)] | [[✓](https://opendrivelab.com/ReSim)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Cosmos-Drive** | arXiv 2025.6 | Cosmos-Drive-Dreams: Scalable Synthetic Driving Data Generation with World Foundation Models | [[✓](https://arxiv.org/abs/2506.09042)] | [[✓](https://research.nvidia.com/labs/toronto-ai/cosmos_drive_dreams/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Dreamland** | arXiv 2025.6 | Dreamland: Controllable World Creation with Simulator and Generative Models | [[✓](https://arxiv.org/abs/2506.08006)] | [[✓](https://metadriverse.github.io/dreamland/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **LongDWM** | arXiv 2025.6 | LongDWM: Cross-Granularity Distillation for Building a Long-Term Driving World Model | [[✓](https://arxiv.org/abs/2506.01546)] | ✗ | [[✓](https://wang-xiaodong1899.github.io/longdwm/)] | ✓ | ✓ | ✗ | 2.0 |
| **FSDrive** | arXiv 2025.5 | FutureSightDrive: Thinking Visually with Spatio-Temporal CoT for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.17685)] | ✗ | [[✓](https://github.com/MIV-XJTU/FSDrive)] | ✓ | ✓ | ✗ | 2.0 |
| **ProphetDWM** | arXiv 2025.5 | ProphetDWM: A Driving World Model for Rolling Out Future Actions and Videos | [[✓](https://arxiv.org/abs/2505.18650)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **GeoDrive** | arXiv 2025.5 | GeoDrive: 3D Geometry-Informed Driving World Model with Precise Action Control | [[✓](https://arxiv.org/abs/2505.22421)] | ✗ | [[✓](https://github.com/antonioo-c/GeoDrive)] | ✓ | ✓ | ✗ | 2.0 |
| **DriveX** | arXiv 2025.5 | DriveX: Omni Scene Modeling for Learning Generalizable World Knowledge in Autonomous Driving | [[✓](https://arxiv.org/abs/2505.19239)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **VL-SAFE** | arXiv 2025.5 | VL-SAFE: Vision-Language Guided Safety-Aware Reinforcement Learning with World Models | [[✓](https://arxiv.org/abs/2505.16377)] | [[✓](https://ys-qu.github.io/vlsafe-website/)] | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **Raw2Drive** | arXiv 2025.5 | Raw2Drive: Reinforcement Learning with Aligned World Models for End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2505.16394)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **RAMBLE** | arXiv 2025.4 | RAMBLE: From Imitation to Exploration: End-to-end Autonomous Driving based on World Model | [[✓](https://arxiv.org/abs/2410.02253)] | ✗ | [[✓](https://github.com/SCP-CN-001/ramble)] | ✓ | ✓ | ✗ | 2.0 |
| **DiVE** | arXiv 2025.4 | DiVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer | [[✓](https://arxiv.org/abs/2504.18576)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **WoTE** | arXiv 2025.4 | WoTE: End-to-End Driving with Online Trajectory Evaluation via BEV World Model | [[✓](https://arxiv.org/abs/2503.22231)] | ✗ | [[✓](https://github.com/liyingyanUCAS/WoTE)] | ✓ | ✓ | ✗ | 2.0 |
| **UniFuture** | arXiv 2025.3 | UniFuture: Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception | [[✓](https://arxiv.org/abs/2503.13587)] | [[✓](https://dk-liang.github.io/UniFuture/)] | [[✓](https://github.com/dk-liang/UniFuture)] | ✓ | ✗ | ✓ | 2.0 |
| **MagicDrive-V2** | arXiv 2025.3 | MagicDrive-V2: High-Resolution Long Video Generation for Autonomous Driving with Adaptive Control | [[✓](https://arxiv.org/abs/2411.13807)] | [[✓](https://gaoruiyuan.com/magicdrive-v2/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **CoGen** | arXiv 2025.3 | CoGen: 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.22231)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **GAIA-2** | arXiv 2025.3 | GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.20523)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **Semi-SD** | arXiv 2025.3 | Semi-SD: Semi-Supervised Metric Depth Estimation via Surrounding Cameras for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.19713)] | ✗ | [[✓](https://github.com/xieyuser/Semi-SD)] | ✓ | ✗ | ✓ | 2.0 |
| **MiLA** | arXiv 2025.3 | MiLA: Multi-view Intensive-fidelity Long-term Video Generation World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.15875)] | [[✓](https://xiaomi-mlab.github.io/mila.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **SimWorld** | arXiv 2025.3 | SimWorld: A Unified Benchmark for Simulator-Conditioned Scene Generation via World Model | [[✓](https://arxiv.org/abs/2503.13952)] | ✗ | [[✓](https://github.com/Li-Zn-H/SimWorld)] | ✓ | ✗ | ✗ | 2.0 |
| **EOT-WM** | arXiv 2025.3 | EOT-WM: Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories | [[✓](https://arxiv.org/abs/2503.09215)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **T³Former** | arXiv 2025.3 | T³Former: Temporal Triplane Transformers as Occupancy World Models | [[✓](https://arxiv.org/abs/2503.07338)] | ✗ | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **AVD2** | arXiv 2025.3 | AVD2: Accident Video Diffusion for Accident Video Description | [[✓](https://arxiv.org/abs/2502.14801)] | [[✓](https://an-answer-tree.github.io/)] | ✗ | ✓ | ✗ | ✗ | 2.0 |
| **VaViM** | arXiv 2025.2 | VaViM and VaVAM: Autonomous Driving through Video Generative Modeling | [[✓](https://arxiv.org/abs/2502.15672)] | ✗ | [[✓](https://github.com/valeoai/VideoActionModel)] | ✓ | ✗ | ✗ | 2.0 |
| **Dream to Drive** | arXiv 2025.2 | Dream to Drive: Model-Based Vehicle Control Using Analytic World Models | [[✓](https://arxiv.org/abs/2502.10012)] | ✗ | ✗ | ✓ | ✓ | ✗ | 2.0 |
| **AD-L-JEPA** | arXiv 2025.1 | AD-L-JEPA: Self-Supervised Spatial World Models with Joint Embedding Predictive Architecture | [[✓](https://arxiv.org/abs/2501.04969)] | ✗ | [[✓](https://github.com/HaoranZhuExplorer/AD-L-JEPA-Release)] | ✓ | ✗ | ✓ | 2.0 |
| **Vista** | NIPS24 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [[✓](https://arxiv.org/abs/2405.17398)] | ✗ | [[✓](https://github.com/OpenDriveLab/Vista)] | ✓ | ✓ | ✗ | 2.0 |

# 📄 2. Progressive Robustness Analysis: 1.0, 2.0 and 3.0

comming soon...

## 2.1
