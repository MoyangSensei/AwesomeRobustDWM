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
|   **DrivingWorld**   | arXiv 2024.12 | DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT                                         | [[✓](https://arxiv.org/abs/2412.19505)] |                                      ✗                                      |                          [[✓](https://github.com/YvanYin/DrivingWorld)]                          |  ✓  |  ✗  |  ✗  | 2.0 |
|  **InfinityDrive**  | arXiv 2024.12 | InfinityDrive: Breaking Time Limits in Driving World Models                                                         | [[✓](https://arxiv.org/abs/2412.01522)] | [[✓](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html)] |                                               ✗                                               |  ✓  |  ✗  |  ✗  | 2.0 |
|      **GenAD**      |   CVPR 2024   | Generalized Predictive Model for Autonomous Driving                                                                 | [[✓](https://arxiv.org/abs/2403.09630)] |                                      ✗                                      | [[Data](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file#genad-dataset-opendv-youtube)] |  ✓  |  ✓  |  ✗  | 2.0 |
|      **TERRA**      | arXiv 2024.12 | Towards Action Controllable World Models for Autonomous Driving                                                     | [[✓](https://arxiv.org/abs/2412.05337)] |                [[✓](https://turingmotors.github.io/actbench/)]                |                         [[✓](https://github.com/turingmotors/ACT-Bench)]                         |  ✓  |  ✓  |  ✗  | 2.0 |
|      **Vista**      | NeurIPS 2024 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability                         | [[✓](https://arxiv.org/abs/2405.17398)] |                                      ✗                                      |                           [[✓](https://github.com/OpenDriveLab/Vista)]                           |  ✓  |  ✓  |  ✗  | 2.0 |
|  **DINO-Foresight**  | arXiv 2024.12 | DINO-Foresight: Self-Supervised Semantic Foresight for Autonomous Driving                                           | [[✓](https://arxiv.org/abs/2412.11673)] |                                      ✗                                      |                          [[✓](https://github.com/Sta8is/DINO-Foresight)]                          |  ✓  |  ✗  |  ✗  | 2.0 |
|   **DriveGenVLM**   |  IAVVC 2024  | DriveGenVLM: Real-world Video Generation for Autonomous Driving with Vision Language Models                         | [[✓](https://arxiv.org/abs/2408.16647)] |                                      ✗                                      |                                               ✗                                               |  ✓  |  ✗  |  ✗  | 2.0 |
|      **Doe-1**      | arXiv 2024.12 | Doe-1: Driving on Earth with One Transformer                                                                        | [[✓](https://arxiv.org/abs/2412.09627)] |                                      ✗                                      |                               [[✓](https://github.com/wzzheng/Doe)]                               |  ✓  |  ✓  |  ✗  | 2.0 |
|     **UniMLVG**     | arXiv 2024.12 | UniMLVG: Unified Multi-View LiDAR-Video Generation for Autonomous Driving                                           | [[✓](https://arxiv.org/abs/2412.09628)] |                [[✓](https://sensetime-fvg.github.io/UniMLVG/)]                |                          [[✓](https://github.com/SenseTime-FVG/OpenDWM)]                          |  ✓  |  ✗  |  ✗  | 2.0 |
|     **Drive-WM**     |   CVPR 2024   | Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving          | [[✓](https://arxiv.org/abs/2311.17918)] |                       [[✓](https://drive-wm.github.io/)]                       |                           [[✓](https://github.com/BraveGroup/Drive-WM)]                           |  ✓  |  ✓  |  ✗  | 2.0 |
|   **DriveDreamer**   |   ECCV 2024   | DriveDreamer: Towards Real-world-driven Generative World Models for Autonomous Driving                              | [[✓](https://arxiv.org/abs/2309.09777)] |                     [[✓](https://drivedreamer.github.io/)]                     |                        [[✓](https://github.com/JeffWang987/DriveDreamer)]                        |  ✓  |  ✓  |  ✓  | 2.0 |
| **DrivingDiffusion** |   ECCV 2024   | Layout-Guided multi-view driving scene video generation with latent diffusion model                                 | [[✓](https://arxiv.org/abs/2310.07771)] |                   [[✓](https://drivingdiffusion.github.io/)]                   |                        [[✓](https://github.com/shalfun/DrivingDiffusion)]                        |  ✓  |  ✗  |  ✓  | 2.0 |
|   **DrivePhysica**   | arXiv 2024.12 | DrivePhysica: Physical-Consistent Video Generation for Autonomous Driving                                           | [[✓](https://arxiv.org/abs/2412.09621)] |                                      ✗                                      |           [[✓](https://metadrivescape.github.io/papers_project/DrivePhysica/page.html)]           |  ✓  |  ✗  |  ✓  | 2.0 |
|     **Panacea**     |   CVPR 2024   | Panoramic and Controllable Video Generation for Autonomous Driving                                                  | [[✓](https://arxiv.org/abs/2311.16813)] |                      [[✓](https://panacea-ad.github.io/)]                      |                            [[✓](https://github.com/wenyuqing/panacea)]                            |  ✓  |  ✗  |  ✓  | 2.0 |
|    **DriveScape**    | arXiv 2024.09 | DriveScape: Towards High-Resolution Controllable Multi-View Driving Video Generation                                | [[✓](https://arxiv.org/abs/2409.05463)] |                                      ✗                                      |                                               ✗                                               |  ✓  |  ✗  |  ✓  | 2.0 |
|    **HoloDrive**    | arXiv 2024.12 | Holistic 2D-3D Multi-Modal Street Scene Generation for Autonomous Driving                                                      | [[✓](https://arxiv.org/abs/2412.01407)] |                                      ✗                                      |                                               ✗                                               |  ✓  |  ✗  |  ✗  | 2.0 |
|     **WoVoGen**     |   ECCV 2024   | World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation                                                   | [[✓](https://arxiv.org/abs/2312.02934)] |                      ✗                       |             [[✓](https://github.com/fudan-zvg/WoVoGen)]                                                                                  |  ✓  |  ✗  |  ✗  | 2.0 |
|    **Copilot4D**    |   ICLR 2024   | Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion                                                  | [[✓](https://arxiv.org/abs/2311.01017)] |                                      ✗                                      |                     ✗                          |  ✓  |  ✗  |  ✗  | 2.0 |
|  **DFIT-OccWorld**  | arXiv 2024.12 | An Efficient Occupancy World Model via Decoupled Dynamic Flow and Image-assisted Training                                                             | [[✓](https://arxiv.org/abs/2412.13772)] |                                      ✗                                      |                                               ✗                                               |  ✓  |  ✓  |  ✗  | 2.0 |
|      **ViDAR**      |   CVPR 2024   | Visual Point Cloud Forecasting enables Scalable Autonomous Driving                                                                  | [[✓](https://arxiv.org/abs/2312.17655)] |                                      ✗                                      |                           [[✓](https://github.com/OpenDriveLab/ViDAR)]                           |  ✓  |  ✓  |  ✓  | 2.0 |
|       **UnO**       |   CVPR 2024   | Unsupervised Occupancy Fields for Perception and Forecasting                                                  | [[✓](https://arxiv.org/abs/2406.08691)] |                                       [[✓](https://waabi.ai/research/uno)]                                      |                             [[✓](https://waabi.ai/research/uno)]                              |  ✓  |  ✗  |  ✓  | 2.0 |
|     **OccWorld**     |   ECCV 2024   | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving                                                | [[✓](https://arxiv.org/abs/2311.16038)] |                      [[✓](https://wzzheng.net/OccWorld)]                      |                            [[✓](https://github.com/wzzheng/OccWorld)]                            |  ✓  |  ✓  |  ✗  | 2.0 |
|       **DOME**       | arXiv 2024.10 | Taming Diffusion Model into High-Fidelity Controllable Occupancy World Model                                              | [[✓](https://arxiv.org/abs/2410.10429)] |                     [[✓](https://gusongen.github.io/DOME)]                     |                 [[✓](https://github.com/gusongen/DOME)]                                                                                |  ✓  |  ✗  |  ✗  | 2.0 |
|    **DriveWorld**    |   CVPR 2024   | 4D Pre-trained Scene Understanding via World Models for Autonomous Driving                                                                  | [[✓](https://arxiv.org/abs/2405.04390)] |                                      ✗                                      |                       ✗                            |  ✓  |  ✓  |  ✓  | 2.0 |
|     **Cam4DOCC**     |   CVPR 2024   | Cam4DOcc: Benchmark for Camera-Only 4D Occupancy Forecasting in Autonomous Driving Applications                     | [[✓](https://arxiv.org/abs/2311.17663)] |                            ✗            |                            [[✓](https://github.com/haomo-ai/Cam4DOcc)]                            |  ✓  |  ✗  |  ✗  | 2.0 |
|     **OccSora**     | arXiv 2024.05 | OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving                                  | [[✓](https://arxiv.org/abs/2405.17833)] |                                      ✗                                      |                             [[✓](https://github.com/haomo-ai/Cam4DOcc)]                             |  ✓  |  ✗  |  ✗  | 2.0 |
|       **NeMo**       |   ECCV 2024   | Neural Volumetric World Models for Autonomous Driving                                                                                 | [[✓](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02571.pdf)] |                                      ✗                                      |                            ✗                            |  ✓  |  ✓  |  ✓  | 2.0 |
|     **OccLLaMA**     | arXiv 2024.09 | An Occupancy-Language-Action Generative World Model for Autonomous Driving                                                       | [[✓](https://arxiv.org/abs/2409.03272)] |                                      ✗                                      |                            ✗                            |  ✓  |  ✓  |  ✗  | 2.0 |
|       **LAW**       | arXiv 2024.06 | Enhancing End-to-end Autonomous Driving with Latent World Model                                                     | [[✓](https://arxiv.org/abs/2406.08481)] |                                      ✗                                      |                             [[✓](https://github.com/BraveGroup/LAW)]                             |  ✓  |  ✓  |  ✗  | 2.0 |
|    **CarFormer**    |   ECCV 2024   | CarFormer: Self-Driving with Learned Object-Centric Representations                                                 | [[✓](https://arxiv.org/abs/2407.15843)] |                  [[✓](https://kuis-ai.github.io/CarFormer/)]                  |                            [[✓](https://github.com/Shamdan17/CarFormer)]                            |  ✓  |  ✓  |  ✗  | 2.0 |
|      **GenAD**      |   ECCV 2024   | Generative End-to-End Autonomous Driving                                                                     | [[✓](https://arxiv.org/abs/2402.11502)] |                     ✗                      |                              [[✓](https://github.com/wzzheng/GenAD)]                              |  ✓  |  ✓  |  ✓  | 2.0 |
|  **SceneDiffuser**  | NeurIPS 2024 | Efficient and Controllable Driving Simulation Initialization and Rollout                                                   | [[✓](https://arxiv.org/abs/2412.12129)] |                                      ✗                                      |                         ✗                     |  ✓  |  ✓  |  ✗  | 2.0 |
|     **MARL-CCE**     |   ECCV 2024   | Modelling Competitive Behaviors in Autonomous Driving Under Generative World Model      | [[✓](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05085.pdf)] |                                      ✗                                      |                          [[✓](https://github.com/qiaoguanren/MARL-CCE)]                          |  ✓  |  ✗  |  ✗  | 2.0 |
|      **RAMBLE**      | arXiv 2024.10 | From Imitation to Exploration: End-to-end Autonomous Driving based on World Model                                                               | [[✓](https://arxiv.org/abs/2410.02253)] |           ✗           |                              ✗                              |  ✓  |  ✓  |  ✗  | 2.0 |
| **Imagine-2-Drive** | arXiv 2024.11 | High-Fidelity World Modeling in CARLA for Autonomous Vehicles                                                       | [[✓](https://arxiv.org/abs/2411.10171)] |                                   [[✓](https://anantagrg.github.io/Imagine-2-Drive.github.io/)]                                         |                                               ✗                                               |  ✓  |  ✗  |  ✗  | 2.0 |
|   **Popov et al.**   | arXiv 2024.09 | Mitigating Covariate Shift in Imitation Learning for Autonomous Vehicles Using Latent Space Generative World Models | [[✓](https://arxiv.org/abs/2409.16663)] |                                      ✗                                      |                                               ✗                                               |  ✓  |  ✓  |  ✗  | 2.0 |
|   **Think2Drive**   |   ECCV 2024   | Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving      | [[✓](https://arxiv.org/abs/2402.16720)] |                 ✗                 |                          ✗                        |  ✓  |  ✓  |  ✗  | 2.0 |
|       **GUMP**       |   ECCV 2024   | Solving Motion Planning Tasks with a Scalable Generative Model                                                                    | [[✓](https://arxiv.org/abs/2407.02797)] |                  ✗                  |                               [[✓](https://github.com/HorizonRobotics/GUMP/)]                               |  ✓  |  ✓  |  ✗  | 2.0 |

**2025**
| Abbr.      | Pub.     | Full Title | Paper  | Page | Code | Gene. | Plan. | Enh. | Lv. |
|:-----------------:|:---------:|:-----------|:------:|:----:|:----:|:----------:|:--------:|:-----------:|:-----------------:|
| **HERMES** | A Unified Self-Driving World Model for Simultaneous 3D Scene Understanding and Generation | [[✓](https://arxiv.org/abs/2505.16394)] | [[✓](https://lmd0311.github.io/HERMES/)] | [[✓](https://github.com/LMD0311/HERMES)] |
| **DINO-Foresight** | Looking into the Future with DINO | [[✓](https://arxiv.org/abs/2412.11673)] | ✗ | [[✓](https://github.com/Sta8is/DINO-Foresight)] |
| **From Forecasting to Planning** | Policy World Model for Collaborative State-Action Prediction | [[✓](https://arxiv.org/abs/2510.19654)] | ✗ | [[✓](https://github.com/6550Zhao/Policy-World-Model)] |
| **InfiniCube** | Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models | [[✓](https://arxiv.org/abs/2412.03934)] | [[✓](https://research.nvidia.com/labs/toronto-ai/infinicube/)] | ✗ |
| **DiST-4D** | Disentangled Spatiotemporal Diffusion with Metric Depth for 4D Driving Scene Generation | [[✓](https://arxiv.org/abs/2503.15208)] | [[✓](https://royalmelon0505.github.io/DiST-4D/)] | ✗ |
| **Epona** | Autoregressive Diffusion World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.24113)] | ✗ | [[✓](https://github.com/Kevin-thu/Epona/)] |
| **UniOcc** | A Unified Benchmark for Occupancy Forecasting and Prediction in Autonomous Driving | [[✓](https://arxiv.org/abs/2503.24381)] | [[✓](https://uniocc.github.io/)] | ✗ |
| **DriVerse** | Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment | [[✓](https://arxiv.org/abs/2504.19614)] | ✗ | [[✓](https://github.com/shalfun/DriVerse)] |
| **World4Drive** | End-to-End Autonomous Driving via Intention-aware Physical Latent World Model | [[✓](https://arxiv.org/abs/2507.00603)] | ✗ | ✗ |
| **PIWM** | Dream to Drive with Predictive Individual World Model | [[✓](https://arxiv.org/abs/2501.16733)] | ✗ | [[✓](https://github.com/gaoyinfeng/PIWM)] |
| **DriveDreamer4D** | World Models Are Effective Data Machines for 4D Driving Scene Representation | [[✓](https://arxiv.org/abs/2410.13571)] | [[✓](https://drivedreamer4d.github.io/)] | ✗ |
| **GaussianWorld** | Gaussian World Model for Streaming 3D Occupancy Prediction | [[✓](https://arxiv.org/abs/2412.10373)] | ✗ | [[✓](https://github.com/zuosc19/GaussianWorld)] |
| **ReconDreamer** | Crafting World Models for Driving Scene Reconstruction via Online Restoration | [[✓](https://arxiv.org/abs/2411.19548)] | ✗ | [[✓](https://github.com/GigaAI-research/ReconDreamer)] |
| **FUTURIST** | Advancing Semantic Future Prediction through Multimodal Visual Sequence Transformers | [[✓](https://arxiv.org/abs/2501.08303)] | ✗ | [[✓](https://github.com/Sta8is/FUTURIST)] |
| **MaskGWM** | A Generalizable Driving World Model with Video Mask Reconstruction | [[✓](https://arxiv.org/abs/2502.11663)] | ✗ | [[✓](https://github.com/SenseTime-FVG/OpenDWM)] |
| **UniScene** | Unified Occupancy-centric Driving Scene Generation | [[✓](https://arxiv.org/abs/2412.05435)] | [[✓](https://arlo0o.github.io/uniscene/)] | ✗ |
| **GEM** | A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control | [[✓](https://arxiv.org/abs/2412.11198)] | [[✓](https://vita-epfl.github.io/GEM.github.io/)] | ✗ |
| **UMGen** | Generating Multimodal Driving Scenes via Next-Scene Prediction | [[✓](https://arxiv.org/abs/2503.14945)] | [[✓](https://yanhaowu.github.io/UMGen/)] | [[✓](https://github.com/YanhaoWu/UMGen/)] |
| **DIO** | Decomposable Implicit 4D Occupancy-Flow World Model | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Diehl_DIO_Decomposable_Implicit_4D_Occupancy-Flow_World_Model_CVPR_2025_paper.html)] | ✗ | ✗ |
| **SceneDiffuser++** | City-Scale Traffic Simulation via a Generative World Model | [[✓](https://openaccess.thecvf.com/content/CVPR2025/html/Tan_SceneDiffuser_City-Scale_Traffic_Simulation_via_a_Generative_World_Model_CVPR_2025_paper.html)] | ✗ | ✗ |
| **DynamicCity** | Large-Scale LiDAR Generation from Dynamic Scenes | [[✓](https://arxiv.org/abs/2410.18084)] | ✗ | [[✓](https://github.com/3DTopia/DynamicCity)] |
| **AdaWM** | Adaptive World Model based Planning for Autonomous Driving | [[✓](https://arxiv.org/abs/2501.13072)] | ✗ | ✗ |
| **OccProphet** | Pushing Efficiency Frontier of Camera-Only 4D Occupancy Forecasting with Observer-Forecaster-Refiner Framework | [[✓](https://arxiv.org/abs/2502.15180)] | ✗ | [[✓](https://github.com/JLChen-C/OccProphet)] |
| **PreWorld** | Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2502.07309)] | ✗ | [[✓](https://github.com/getterupper/PreWorld)] |
| **SSR** | Does End-to-End Autonomous Driving Really Need Perception Tasks? | [[✓](https://arxiv.org/abs/2409.18341)] | ✗ | [[✓](https://github.com/PeidongLi/SSR)] |
| **Occ-LLM** | Enhancing Autonomous Driving with Occupancy-Based Large Language Models | [[✓](https://arxiv.org/abs/2502.06419)] | ✗ | ✗ |
| **STAGE** | A Stream-Centric Generative World Model for Long-Horizon Driving-Scene Simulation | [[✓](https://arxiv.org/abs/2506.13138)] | [[✓](https://4dvlab.github.io/STAGE/)] | ✗ |
| **Drive&Gen** | Co-Evaluating End-to-End Driving and Video Generation Models | [[✓](https://arxiv.org/abs/2510.06209)] | ✗ | ✗ |
| **Learning to Generate 4D LiDAR Sequences** | Learning to Generate 4D LiDAR Sequences | [[✓](https://arxiv.org/abs/2509.11959)] | ✗ | ✗ |
| **Accident Anticipation WM** | World model-based end-to-end scene generation for accident anticipation in autonomous driving | [[✓](https://www.nature.com/articles/s44172-025-00474-7)] | ✗ | ✗ |
| **LIDAR Navigation WM** | World Models for Autonomous Navigation of Terrestrial Robots from LIDAR Observations | [[✓](https://arxiv.org/abs/2512.03429)] | ✗ | ✗ |
| **UniFuture** | Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception | [[✓](https://arxiv.org/abs/2503.13587)] | [[✓](https://dk-liang.github.io/UniFuture/)] | [[✓](https://github.com/dk-liang/UniFuture)] |
| **MindDrive** | An All-in-One Framework Bridging World Models and Vision-Language Model for End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2512.04441)] | ✗ | ✗ |
| **U4D** | Uncertainty-Aware 4D World Modeling from LiDAR Sequences | [[✓](https://arxiv.org/abs/2512.02982)] | ✗ | ✗ |
| **Think Before You Drive** | World Model-Inspired Multimodal Grounding for Autonomous Vehicles | [[✓](https://arxiv.org/abs/2512.03454)] | ✗ | ✗ |
| **Vehicle Dynamics WM** | Vehicle Dynamics Embedded World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2512.02417)] | ✗ | ✗ |
| **LiSTAR** | Ray-Centric World Models for 4D LiDAR Sequences in Autonomous Driving | [[✓](https://arxiv.org/abs/2511.16049)] | [[✓](https://ocean-luna.github.io/LiSTAR.gitub.io)] | ✗ |
| **OpenTwinMap** | An Open-Source Digital Twin Generator for Urban Autonomous Driving | [[✓](https://arxiv.org/abs/2511.21925)] | ✗ | ✗ |
| **SparseWorld-TC** | Trajectory-Conditioned Sparse Occupancy World Model | [[✓](https://arxiv.org/abs/2511.22039)] | ✗ | ✗ |
| **LaGen** | Towards Autoregressive LiDAR Scene Generation | [[✓](https://arxiv.org/abs/2511.21256)] | ✗ | ✗ |
| **AD-R1** | Closed-Loop Reinforcement Learning for End-to-End Autonomous Driving with Impartial World Models | [[✓](https://arxiv.org/abs/2511.20325)] | ✗ | ✗ |
| **CorrectAD** | A Self-Correcting Agentic System to Improve End-to-end Planning in Autonomous Driving | [[✓](https://arxiv.org/abs/2511.13297)] | ✗ | ✗ |
| **UniScenev2** | Scaling Up Occupancy-centric Driving Scene Generation: Dataset and Method | [[✓](https://arxiv.org/abs/2510.22973)] | ✗ | ✗ |
| **Vision-Centric 4D Occ** | Vision-Centric 4D Occupancy Forecasting and Planning via Implicit Residual World Models | [[✓](https://arxiv.org/abs/2510.16729)] | ✗ | ✗ |
| **SparseWorld** | A Flexible, Adaptive, and Efficient 4D Occupancy World Model Powered by Sparse and Dynamic Queries | [[✓](https://arxiv.org/abs/2510.17482)] | ✗ | [[✓](https://github.com/MSunDYY/SparseWorld)] |
| **OmniNWM** | Omniscient Driving Navigation World Models | [[✓](https://arxiv.org/abs/2510.18313)] | [[✓](https://arlo0o.github.io/OmniNWM/)] | ✗ |
| **ORAD-3D** | Advancing Off-Road Autonomous Driving: The Large-Scale ORAD-3D Dataset and Comprehensive Benchmarks | [[✓](https://arxiv.org/abs/2510.16500)] | ✗ | [[✓](https://github.com/chaytonmin/ORAD-3D)] |
| **Dream4Drive** | Rethinking Driving World Model as Synthetic Data Generator for Perception Tasks | [[✓](https://arxiv.org/abs/2510.19195)] | [[✓](https://wm-research.github.io/Dream4Drive/)] | ✗ |
| **DriveVLA-W0** | World Models Amplify Data Scaling Law in Autonomous Driving | [[✓](https://arxiv.org/abs/2510.12796)] | ✗ | ✗ |
| **CoIRL-AD** | Collaborative-Competitive Imitation-Reinforcement Learning in Latent World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2510.12560)] | ✗ | ✗ |
| **CVD-STORM** | Cross-View Video Diffusion with Spatial-Temporal Reconstruction Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2510.07944)] | ✗ | ✗ |
| **PhiGensis** | 4D Driving Scene Generation With Stereo Forcing | [[✓](https://arxiv.org/abs/2509.20251)] | [[✓](https://jiangxb98.github.io/PhiGensis/)] | ✗ |
| **TeraSim-World** | Worldwide Safety-Critical Data Synthesis for End-to-End Autonomous Driving | [[✓](https://arxiv.org/abs/2509.13164)] | ✗ | ✗ |
| **OccTENS** | 3D Occupancy World Model via Temporal Next-Scale Prediction | [[✓](https://arxiv.org/abs/2509.03887)] | ✗ | ✗ |
| **G^2Editor** | Realistic and Controllable 3D Gaussian-Guided Object Editing for Driving Video Generation | [[✓](https://arxiv.org/abs/2508.20471)] | ✗ | ✗ |
| **LSD-3D** | Large-Scale 3D Driving Scene Generation with Geometry Grounding | [[✓](https://arxiv.org/abs/2508.19204)] | [[✓](https://princeton-computational-imaging.github.io/LSD-3D/)] | ✗ |
| **Fine-Tuned Video Gen** | Seeing Clearly, Forgetting Deeply: Revisiting Fine-Tuned Video Generators for Driving Simulation | [[✓](https://arxiv.org/abs/2508.16512)] | ✗ | ✗ |
| **MoVieDrive** | Multi-Modal Multi-View Urban Scene Video Generation | [[✓](https://arxiv.org/abs/2508.14327)] | ✗ | ✗ |
| **ImagiDrive** | A Unified Imagination-and-Planning Framework for Autonomous Driving | [[✓](https://arxiv.org/abs/2508.11428)] | ✗ | [[✓](https://github.com/fudan-zvg/ImagiDrive)] |
| **LiDARCrafter** | Dynamic 4D World Modeling from LiDAR Sequences | [[✓](https://arxiv.org/abs/2508.03692)] | [[✓](https://lidarcrafter.github.io/)] | ✗ |
| **FASTopoWM** | Fast-Slow Lane Segment Topology Reasoning with Latent World Models | [[✓](https://arxiv.org/abs/2507.23325)] | ✗ | ✗ |
| **Accident Anticipation II** | World Model-Based End-to-End Scene Generation for Accident Anticipation in Autonomous Driving | [[✓](https://arxiv.org/abs/2507.12762)] | ✗ | ✗ |
| **Orbis** | Overcoming Challenges of Long-Horizon Prediction in Driving World Models | [[✓](https://arxiv.org/abs/2507.13162)] | [[✓](https://lmb-freiburg.github.io/orbis.github.io/)] | ✗ |
| **I2-World** | Intra-Inter Tokenization for Efficient Dynamic 4D Scene Forecasting | [[✓](https://arxiv.org/abs/2507.09144)] | ✗ | [[✓](https://github.com/lzzzzzm/II-World)] |
| **NRSeg** | Noise-Resilient Learning for BEV Semantic Segmentation via Driving World Models | [[✓](https://arxiv.org/abs/2507.04002)] | ✗ | [[✓](https://github.com/lynn-yu/NRSeg)] |
| **LiDAR Foundational** | Towards foundational LiDAR world models with efficient latent flow matching | [[✓](https://arxiv.org/abs/2506.23434)] | ✗ | ✗ |
| **ReSim** | Reliable World Simulation for Autonomous Driving | [[✓](https://arxiv.org/abs/2506.09981)] | [[✓](https://opendrivelab.com/ReSim)] | ✗ |
| **Cosmos-Drive-Dreams** | Scalable Synthetic Driving Data Generation with World Foundation Models | [[✓](https://arxiv.org/abs/2506.09042)] | [[✓](https://research.nvidia.com/labs/toronto-ai/cosmos_drive_dreams/)] | ✗ |
| **Dreamland** | Controllable World Creation with Simulator and Generative Models | [[✓](https://arxiv.org/abs/2506.08006)] | [[✓](https://metadriverse.github.io/dreamland/)] | ✗ |
| **LongDWM** | Cross-Granularity Distillation for Building a Long-Term Driving World Model | [[✓](https://arxiv.org/abs/2506.01546)] | [[✓](https://wang-xiaodong1899.github.io/longdwm/)] | ✗ |
| **FutureSightDrive** | Thinking Visually with Spatio-Temporal CoT for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.17685)] | ✗ | [[✓](https://github.com/MIV-XJTU/FSDrive)] |
| **ProphetDWM** | ProphetDWM: A Driving World Model for Rolling Out Future Actions and Videos | [[✓](https://arxiv.org/abs/2505.18650)] | ✗ | ✗ |
| **GeoDrive** | 3D Geometry-Informed Driving World Model with Precise Action Control | [[✓](https://arxiv.org/abs/2505.22421)] | ✗ | [[✓](https://github.com/antonioo-c/GeoDrive)] |
| **DriveX** | Omni Scene Modeling for Learning Generalizable World Knowledge in Autonomous Driving | [[✓](https://arxiv.org/abs/2505.19239)] | ✗ | ✗ |
| **VL-SAFE** | Vision-Language Guided Safety-Aware Reinforcement Learning with World Models for Autonomous Driving | [[✓](https://arxiv.org/abs/2505.16377)] | [[✓](https://ys-qu.github.io/vlsafe-website/)] | ✗ |
| **Raw2Drive** | Reinforcement Learning with Aligned World Models for End-to-End Autonomous Driving (in CARLA v2) | [[✓](https://arxiv.org/abs/2505.16394)] | ✗ | ✗ |
| **RAMBLE** | From Imitation to Exploration: End-to-end Autonomous Driving based on World Model | [[✓](https://arxiv.org/abs/2410.02253)] | ✗ | [[✓](https://github.com/SCP-CN-001/ramble)] |
| **DiVE** | Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer | [[✓](https://arxiv.org/abs/2504.18576)] | ✗ | ✗ |
| **WoTE** | End-to-End Driving with Online Trajectory Evaluation via BEV World Model | [[✓](https://arxiv.org/abs/2503.22231)] | ✗ | [[✓](https://github.com/liyingyanUCAS/WoTE)] |
| **MagicDrive-V2** | High-Resolution Long Video Generation for Autonomous Driving with Adaptive Control | [[✓](https://arxiv.org/abs/2411.13807)] | [[✓](https://gaoruiyuan.com/magicdrive-v2/)] | ✗ |
| **CoGen** | 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.22231)] | ✗ | ✗ |
| **GAIA-2** | A Controllable Multi-View Generative World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.20523)] | ✗ | ✗ |
| **Semi-SD** | Semi-Supervised Metric Depth Estimation via Surrounding Cameras for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.19713)] | ✗ | [[✓](https://github.com/xieyuser/Semi-SD)] |
| **MiLA** | Multi-view Intensive-fidelity Long-term Video Generation World Model for Autonomous Driving | [[✓](https://arxiv.org/abs/2503.15875)] | [[✓](https://xiaomi-mlab.github.io/mila.github.io/)] | ✗ |
| **SimWorld** | A Unified Benchmark for Simulator-Conditioned Scene Generation via World Model | [[✓](https://arxiv.org/abs/2503.13952)] | ✗ | [[✓](https://github.com/Li-Zn-H/SimWorld)] |
| **EOT-WM** | Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latant Space | [[✓](https://arxiv.org/abs/2503.09215)] | ✗ | ✗ |
| **T³Former** | Temporal Triplane Transformers as Occupancy World Models | [[✓](https://arxiv.org/abs/2503.07338)] | ✗ | ✗ |
| **AVD2** | Accident Video Diffusion for Accident Video Description | [[✓](https://arxiv.org/abs/2502.14801)] | [[✓](https://an-answer-tree.github.io/)] | ✗ |
| **VaViM and VaVAM** | Autonomous Driving through Video Generative Modeling | [[✓](https://arxiv.org/abs/2502.15672)] | ✗ | [[✓](https://github.com/valeoai/VideoActionModel)] |
| **Dream to Drive** | Model-Based Vehicle Control Using Analytic World Models | [[✓](https://arxiv.org/abs/2502.10012)] | ✗ | ✗ |
| **AD-L-JEPA** | Self-Supervised Spatial World Models with Joint Embedding Predictive Architecture for Autonomous Driving with LiDAR Data | [[✓](https://arxiv.org/abs/2501.04969)] | ✗ | [[✓](https://github.com/HaoranZhuExplorer/AD-L-JEPA-Release)] |

# 📄 2. Progressive Robustness Analysis: 1.0, 2.0 and 3.0

comming soon...

## 2.1
