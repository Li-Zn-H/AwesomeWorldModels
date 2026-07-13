<h1 align="center">A Comprehensive Survey on World Models for Embodied AI</h1>


<p align="center"> </p>

This repository accompanies our survey, [**A Comprehensive Survey on World Models for Embodied AI**](https://arxiv.org/abs/2510.16732). World models function as internal simulators of environmental dynamics, enabling forward and counterfactual rollouts that unify perception, prediction, and control across tasks and domains. For a brief overview of the survey, please refer to the two slides: :bookmark_tabs: [English (PDF)](slides/Slide_Eng.pdf) · :bookmark_tabs: [Chinese (PDF)](slides/Slide_CN.pdf)



# Papers :books:
**Icon legend** — :car: Autonomous Driving · :robot: Robotic Manipulation · :compass: Navigation · :clapper: Video Generation (Indicates the predominant domain. categories are non-exclusive, e.g., robotics and driving may involve generative modeling.)


## Decision-Coupled / Sequential / Global Latent Vector
### 2026

- :robot: **LeWorldModel**: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2603.19312)]
[[Project Page](https://le-wm.github.io/)]
[[Code](https://github.com/lucas-maes/le-wm)]

### 2025

- :robot: **DisWM**: Disentangled World Models: Learning to Transfer Semantic Knowledge from Distracting Videos for Reinforcement Learning.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2503.08751)]
[[Project Page](https://qiwang067.github.io/diswm)]
[[Code](https://github.com/qiwang067/DisWM)]
[[Dataset](https://huggingface.co/datasets/MrSC320/DisWM-Pretrain-Datasets/tree/main)]

- :robot: **FOUNDER**: Grounding Foundation Models in World Models for Open-Ended Embodied Decision Making.
**[ICML'25]**
[[Paper](https://openreview.net/forum?id=UTT5OTyIWm)]
[[Project Page](https://sites.google.com/view/founder-rl)]

- :robot: **SENSEI**: Semantic Exploration Guided by Foundation Models to Learn Versatile World Models.
**[ICML'25]**
[[Paper](https://arxiv.org/abs/2503.01584)]
[[Project Page](https://sites.google.com/view/sensei-paper)]
[[Code](https://github.com/martius-lab/sensei)]

- :robot: **SR-AIF**: Solving Sparse-Reward Robotic Tasks From Pixels with Active Inference and World Models.
**[ICRA'25]**
[[Paper](https://ieeexplore.ieee.org/abstract/document/11127713)]
[[Code](https://github.com/NACLab/self-revising-active-inference)]

- :robot: **LUMOS**: Language-Conditioned Imitation Learning with World Models.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2503.10370)]
[[Project Page](https://lumos.cs.uni-freiburg.de/)]
[[Code](https://github.com/nematoli/lumos)]

- :robot: **WMP**: World Model-Based Perception for Visual Legged Locomotion.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2409.16784)]
[[Project Page](https://wmp-loco.github.io/)]
[[Code](https://github.com/bytedance/WMP)]

- :compass: **X-MOBILITY**: End-to-end generalizable navigation via world modeling.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2410.17491)]
[[Project Page](https://nvlabs.github.io/X-MOBILITY/)]
[[Code](https://github.com/NVlabs/X-Mobility)]

- :car: **AdaWM**: Adaptive World Model based Planning for Autonomous Driving.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2501.13072)]

- :robot: **DreamerV3**: Mastering diverse control tasks through world models.
**[Nature'25]**
[[Paper](https://www.nature.com/articles/s41586-025-08744-2)]
[[Project Page](https://danijar.com/project/dreamerv3/)]
[[Code](https://github.com/danijar/dreamerv3)]

- :robot: **GLAM**: Global-Local Variation Awareness in Mamba-based World Model.
**[AAAI'25]**
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33880)]
[[Code](https://github.com/GLAM2025/glam)]


- :robot: **WMR**: Learning Humanoid Locomotion with World Model Reconstruction.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2502.16230)]



- :car: **VL-SAFE**: Vision-Language Guided Safety-Aware Reinforcement Learning with World Models for Autonomous Driving.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.16377)]
[[Project Page](https://ys-qu.github.io/vlsafe-website/)]
[[Code](https://github.com/ys-qu/vl-safe/tree/main)]
[[Poster](https://ys-qu.github.io/vlsafe-website/static/pdfs/poster%20-%20Yansong%20Qu%20-%20Apr%2024.pdf)]
[[Video](https://www.youtube.com/watch?v=cL4K3Fshjxk)]

- :car: **CALL**: Ego-centric Learning of Communicative World Models for Autonomous Driving.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.08149)]

- :robot: **Latent Policy Steering with Embodiment-Agnostic Pretrained World Models**.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.13340)]

- :robot: **ReDRAW**: Adapting World Models with Latent-State Dynamics Residuals.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2504.02252)]
[[Project Page](https://redraw.jblanier.net/)]

- :robot: **OSVI-WM**: One-Shot Visual Imitation for Unseen Tasks using World-Model-Guided Trajectory Generation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.20425)]

- :robot: **Robotic World Model**: A Neural Network Simulator for Robust Policy Optimization in Robotics.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2501.10100)]



### 2024
- :robot: **PreLAR**: World Model Pre-training with Learnable Action Representation.
**[ECCV'24]**
[[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03363.pdf)]
[[Code](https://github.com/zhanglixuan0720/PreLAR)]
[[Video](https://www.youtube.com/watch?v=5Ggon2fabH4)]

- :robot: **DWL**: Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning.
  **[RSS'24]**
  [[Paper](https://arxiv.org/abs/2408.14472)]

- :robot: **HRSSM**: Learning Latent Dynamic Robust Representations for World Models.
  **[ICML'24]**
  [[Paper](https://proceedings.mlr.press/v235/sun24n.html)]
  [[Project Page](https://icml.cc/virtual/2024/poster/34700)]
  [[Code](https://github.com/bit1029public/HRSSM)]
  [[Poster](https://icml.cc/media/PosterPDFs/ICML%202024/34700.png?t=1719905099.8906405)]

- :car: **SEM2**: Enhance Sample Efficiency and Robustness of End-to-End Urban Autonomous Driving via Semantic Masked World Model.
**[TITS'24]**
  [[Paper](https://arxiv.org/abs/2210.04017)]

- :car: **Mitigating Covariate Shift in Imitation Learning for Autonomous Vehicles Using Latent Space Generative World Models**.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2409.16663)]
[[Video](https://www.youtube.com/watch?v=7m3bXzlVQvU)]

### Earlier

- :robot: **DayDreamer**: World Models for Physical Robot Learning.
**[CoRL'22]**
[[Paper](https://proceedings.mlr.press/v205/wu23c)]
[[Project Page](https://danijar.com/project/daydreamer/)]
[[Code](https://github.com/danijar/daydreamer)]

- :robot: **TransDreamer**: Reinforcement Learning with Transformer World Models.
**[arXiv'22]**
[[Paper](https://arxiv.org/abs/2202.09481)]
[[Code](https://github.com/changchencc/TransDreamer)]

- :car: **MILE**: Model-Based Imitation Learning for Urban Driving.
**[NeurIPS'22]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/827cb489449ea216e4a257c47e407d18-Abstract-Conference.html)]
[[Code](https://github.com/wayveai/mile)]

- :robot: **Iso-Dream**: Isolating and Leveraging Noncontrollable Visual Dynamics in World Models.
**[NeurIPS'22]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9316769afaaeeaad42a9e3633b14e801-Abstract-Conference.html)]
[[Code](https://github.com/panmt/Iso-Dream)]

- :robot: **DreamerPro**: Reconstruction-Free Model-Based Reinforcement Learning with Prototypical Representations.
**[ICML'22]**
[[Paper](https://proceedings.mlr.press/v162/deng22a.html)]
[[Project Page](https://icml.cc/virtual/2022/spotlight/17996)]
[[Code](https://github.com/fdeng18/dreamer-pro)]

- :robot: **Dreaming**: Model-based Reinforcement Learning by Latent Imagination without Reconstruction.
**[ICRA'21]**
[[Paper](https://arxiv.org/abs/2007.14535)]

- :robot: **DreamerV2**: Mastering Atari with Discrete World Models.
**[ICLR'21]**
[[Paper](https://arxiv.org/abs/2010.02193)]
[[Project Page](https://danijar.com/project/dreamerv2/)]
[[Code](https://github.com/danijar/dreamerv2)]
[[Blog](https://ai.googleblog.com/2021/02/mastering-atari-with-discrete-world.html)]
[[Poster](https://danijar.com/asset/dreamerv2/poster.pdf)]

- :robot: **GLAMOR**: Planning from Pixels using Inverse Dynamics Models.
**[ICLR'21]**
[[Paper](https://arxiv.org/abs/2012.02419)]
[[Code](https://github.com/keirp/glamor)]


- :robot: **Dreamer**: Dream to Control: Learning Behaviors by Latent Imagination.
**[ICLR'20]**
[[Paper](https://arxiv.org/abs/1912.01603)]
[[Project Page](https://danijar.com/project/dreamer/)]
[[Code](https://github.com/danijar/dreamer)]
[[Blog](https://research.google/blog/introducing-dreamer-scalable-reinforcement-learning-using-world-models/)]
[[Poster](https://danijar.com/asset/dreamer/poster.pdf)]


- :robot: **PlaNet**: Learning Latent Dynamics for Planning from Pixels.
**[ICML'19]**
[[Paper](https://proceedings.mlr.press/v97/hafner19a.html)]
[[Project Page](https://danijar.com/project/planet/)]
[[Code](https://github.com/google-research/planet)]
[[Blog](https://research.google/blog/introducing-planet-a-deep-planning-network-for-reinforcement-learning/)]
[[Poster](https://danijar.com/asset/planet/poster.pdf)]


- :robot: **Recurrent World Models Facilitate Policy Evolution**.
**[NeurIPS'18]**
[[Paper](https://proceedings.neurips.cc/paper/2018/hash/2de5d16682c3c35007e4e92982f1a2ba-Abstract.html)]
[[Project Page](https://worldmodels.github.io/)]
[[Video](https://www.youtube.com/watch?v=HzA8LRqhujk)]



## Decision-Coupled / Sequential / Token Feature Sequence
### 2026

- :robot: **DreamDojo**: A Generalist Robot World Model from Large-Scale Human Videos.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.06949)]
[[Project Page](https://dreamdojo-world.github.io/)]
[[Code](https://github.com/nvidia/dreamdojo)]

- :robot: **$\tau_0$-WM**: A Unified Video-Action World Model for Robotic Manipulation.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2606.01027)]
[[Project Page](https://finch.agibot.com/research/tau0-wm)]
[[Code](https://github.com/sii-research/tau-0-wm)]

- :robot: **DreamZero**: World Action Models are Zero-shot Policies.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.15922)]
[[Project Page](https://dreamzero0.github.io/)]
[[Code](https://github.com/dreamzero0/dreamzero)]

- :robot: **WoVR**: World Models as Reliable Simulators for Post-Training VLA Policies with RL.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.13977)]
[[Code](https://github.com/RLinf/RLinf)]

- :robot: **World-VLA-Loop**: Closed-Loop Learning of Video World Model and VLA Policy.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.06508)]
[[Project Page](https://showlab.github.io/World-VLA-Loop/)]

- :robot: **RISE**: Self-Improving Robot Policy with Compositional World Model.
**[RSS'26]**
[[Paper](https://arxiv.org/abs/2602.11075)]
[[Project Page](https://opendrivelab.com/RISE/)]
[[Code](https://github.com/OpenDriveLab/RISE)]

### 2025

- :robot: **EgoAgent**: A Joint Predictive Agent Model in Egocentric Worlds.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2502.05857)]
[[Project Page](https://egoagent.github.io/)]
[[Code](https://github.com/zju3dv/EgoAgent)]
[[Video](https://www.youtube.com/watch?v=qhfHp_sfDvY)]


- :compass: **NavMorph**: A Self-Evolving World Model for Vision-and-Language Navigation in Continuous Environments.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2506.23468)]
[[Code](https://github.com/Feliciaxyao/NavMorph)]


- :robot: **DyWA**: Dynamics-adaptive World Action Model for Generalizable Non-prehensile Manipulation.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2503.16806)]
[[Project Page](https://pku-epic.github.io/DyWA/)]
[[Code](https://github.com/jiangranlv/DyWA/)]

- :car: **Epona**: Autoregressive Diffusion World Model for Autonomous Driving.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2506.24113)]
[[Project Page](https://kevin-thu.github.io/Epona/)]
[[Code](https://github.com/Kevin-thu/Epona)]

- :robot: **MineDreamer**: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2403.12037)]
[[Project Page](https://sites.google.com/view/minedreamer/main)]
[[Code](https://github.com/Zhoues/MineDreamer)]
[[Dataset](https://huggingface.co/datasets/Zhoues/Goal-Drift-Dataset)]

- :robot: **$\text{D}^2\text{PO}$**: World Modeling Makes a Better Planner: Dual Preference Optimization for Embodied Task Planning.
**[ACL'25]**
[[Paper](https://arxiv.org/abs/2503.10480)]
[[Code](https://github.com/sinwang20/D2PO)]
[[Dataset](https://huggingface.co/datasets/sinwang/D2PO)]

- :robot: **ReOI**: Reimagination with Test-time Observation Interventions: Distractor-Robust World Model Predictions for Visual Model Predictive Control.
**[RSSW'25]**
[[Paper](https://arxiv.org/abs/2506.16565)]

- :robot: **WoMAP**: World Models For Embodied Open-Vocabulary Object Localization.
**[RSSW'25]**
[[Paper](https://arxiv.org/abs/2506.01600)]

- :robot: **TWM**: Improving Transformer World Models for Data-Efficient RL.
**[ICML'25]**
[[Paper](https://arxiv.org/abs/2502.01591)]

- :robot: **TrajWorld**: Trajectory World Models for Heterogeneous Environments.
**[ICML'25]**
[[Paper](https://arxiv.org/abs/2502.01366)]
[[Code](https://github.com/thuml/TrajWorld)]
[[Dataset](https://huggingface.co/datasets/Joseph-Yin-2004/UniTraj)]

- :car: **SceneDiffuser++**: City-Scale Traffic Simulation via a Generative World Model.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Tan_SceneDiffuser_City-Scale_Traffic_Simulation_via_a_Generative_World_Model_CVPR_2025_paper.html)]

- :compass: **NWM**: Navigation World Models.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Bar_Navigation_World_Models_CVPR_2025_paper.html)]
[[Project Page](https://www.amirbar.net/nwm/)]
[[Code](https://github.com/facebookresearch/nwm/)]

- :car: **Learning to Drive from a World Model**.
**[CVPRW'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025W/DDADS/html/Goff_Learning_to_Drive_from_a_World_Model_CVPRW_2025_paper.html)]

- :car: **LatentDriver**: Learning Multiple Probabilistic Decisions from Latent World Model in Autonomous Driving.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2409.15730)]
[[Project Page](https://sephirex-x.github.io/LatentDriver/)]
[[Code](https://github.com/Sephirex-X/LatentDriver)]

- :car: **Planning with Adaptive World Models for Autonomous Driving**.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2406.10714)]


- :robot: **TWISTER**: Learning Transformer-based World Models with Contrastive Predictive Coding.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2503.04416)]
[[Code](https://github.com/burchim/TWISTER)]

- :robot: **DCWM**: Discrete Codebook World Models for Continuous Control.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2503.00653)]
[[Project Page](https://www.aidanscannell.com/dcmpc/)]
[[Code](https://github.com/aidanscannell/dcmpc)]
[[Video](https://recorder-v3.slideslive.com/#/share?share=98948&s=31e7f935-779c-446d-962d-be9ff1ddc366)]


- :robot: **Object-Centric World Model for Language-Guided Manipulation**.
**[ICLRW'25]**
[[Paper](https://arxiv.org/abs/2503.06170)]


- :compass: **NavCoT**: Boosting LLM-Based Vision-and-Language Navigation via Learning Disentangled Reasoning.
**[TPAMI'25]**
[[Paper](https://arxiv.org/abs/2403.07376)]
[[Code](https://github.com/expectorlin/NavCoT)]


- :robot: **Dyn-O**: Building Structured World Models with Object-Centric Representations.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.03298)]

- :robot: **MineWorld**: a Real-Time and Open-Source Interactive World Model on Minecraft.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2504.08388)]
[[Code](https://github.com/microsoft/MineWorld)]

- :robot: **EvoAgent**: Self-evolving Agent with Continual World Model for Long-Horizon Tasks.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2502.05907)]

- :robot: **RoboHorizon**: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2501.06605)]

- :robot: **WorldVLA**: Towards Autoregressive Action World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.21539)]
[[Code](https://github.com/alibaba-damo-academy/WorldVLA)]


- :car: **FutureSightDrive**: Thinking Visually with Spatio-Temporal CoT for Autonomous Driving.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.17685)]

- :robot: **Dyna-Think**: Synergizing Reasoning, Acting, and World Model Simulation in AI Agents.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.00320)]

- :robot: **RIG**: Synergizing Reasoning and Imagination in End-to-End Generalist Policy.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.24388)]

- :robot: **Language Agents Meet Causality -- Bridging LLMs and Causal World Models**.
**[ICLR'25]**
[[Paper](https://openreview.net/forum?id=y9A2TpaGsE)]
[[Project Page](https://j0hngou.github.io/LLMCWM/)]
[[Code](https://github.com/j0hngou/LLMCWM/)]

### 2024
- :robot: **ECoT**: Robotic Control via Embodied Chain-of-Thought Reasoning.
**[CoRL'24]**
[[Paper](https://proceedings.mlr.press/v270/zawalski25a.html)]
[[Project Page](https://embodied-cot.github.io/)]
[[Code](https://github.com/MichalZawalski/embodied-CoT/)]

- :robot: **PIVOT-R**: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation.
**[NeurIPS'24]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/6164b6e5352c139e9ddc1a98c09e4e4a-Abstract-Conference.html)]
[[Project Page](https://abliao.github.io/PIVOT-R/)]
[[Code](https://github.com/abliao/PIVOT-R)]

- :car: **CarFormer**: Self-driving with Learned Object-Centric Representations.
**[ECCV'24]**
[[Paper](https://arxiv.org/abs/2407.15843)]
[[Project Page](https://kuis-ai.github.io/CarFormer/)]
[[Code](https://github.com/Shamdan17/CarFormer)]



- :robot: **$\Delta$-IRIS**: Efficient World Models with Context-Aware Tokenization.
**[ICML'24]**
[[Paper](https://proceedings.mlr.press/v235/micheli24a.html)]
[[Code](https://github.com/vmicheli/delta-iris)]


- :robot: **Statler**: State-Maintaining Language Models for Embodied Reasoning.
**[ICRA'24]**
[[Paper](https://arxiv.org/abs/2306.17840)]
[[Project Page](https://statler-lm.github.io/)]
[[Code](https://github.com/ripl/statler/)]

- :car: **DrivingWorld**: Constructing World Model for Autonomous Driving via Video GPT.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.19505)]
[[Project Page](https://huxiaotaostasy.github.io/DrivingWorld/index.html)]
[[Code](https://github.com/YvanYin/DrivingWorld)]
[[Video](https://www.youtube.com/watch?v=5QJRAxnjX0k)]

- :car: **Doe-1**: Closed-Loop Autonomous Driving with Large World Model.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.09627)]
[[Project Page](https://wzzheng.net/Doe/)]
[[Code](https://github.com/wzzheng/Doe)]

- :car: **DrivingGPT**: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.18607)]
[[Project Page](https://rogerchern.github.io/DrivingGPT/)]
[[Code](https://github.com/RogerChern/DrivingGPT)]


### Earlier


- :robot: **TWM**: Transformer-based World Models Are Happy With 100k Interactions.
**[ICLR'23]**
[[Paper](https://arxiv.org/abs/2303.07109)]
[[Code](https://github.com/jrobine/twm)]

- :robot: **IRIS**: Transformers are Sample-Efficient World Models.
**[ICLR'23]**
[[Paper](https://arxiv.org/abs/2209.00588)]
[[Code](https://github.com/eloialonso/iris)]


- :robot: **Inner Monologue**: Embodied Reasoning through Planning with Language Models.
**[CoRL'22]**
[[Paper](https://proceedings.mlr.press/v205/huang23c.html)]
[[Project Page](https://innermonologue.github.io/)]
[[Video](https://www.youtube.com/watch?v=0sJjdxn5kcI)]


- :robot: **MWM**: Masked World Models for Visual Control.
**[CoRL'22]**
[[Paper](https://proceedings.mlr.press/v205/seo23a.html)]
[[Project Page](https://sites.google.com/view/mwm-rl)]
[[Code](https://github.com/younggyoseo/MWM)]


## Decision-Coupled / Sequential / Spatial Latent Grid
### 2026
- :robot: **PointWorld**: Scaling 3D World Models for In-The-Wild Robotic Manipulation.
**[CVPR'26]**
[[Paper](https://arxiv.org/abs/2601.03782)]
[[Project Page](https://point-world.github.io/)]
[[Code](https://github.com/NVlabs/PointWorld)]

### 2025
- :robot: **ParticleFormer**: A 3D Point Cloud World Model for Multi-Object, Multi-Material Robotic Manipulation.
**[CoRL'25]**
[[Paper](https://arxiv.org/abs/2506.23126)]
[[Project Page](https://suninghuang19.github.io/particleformer_page/)]

- :car: **WoTE**: End-to-End Driving with Online Trajectory Evaluation via BEV World Model.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2504.01941)]
[[Code](https://github.com/liyingyanUCAS/WoTE)]

- :compass: **WMNav**: Integrating Vision-Language Models into World Models for Object Goal Navigation.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2503.02247)]
[[Project Page](https://b0b8k1ng.github.io/WMNav/)]
[[Code](https://github.com/B0B8K1ng/WMNavigation)]
[[Video](https://www.youtube.com/watch?v=RnHtHueHGtg)]


- :robot: **DINO-WM**: World Models on Pre-trained Visual Features enable Zero-shot Planning.
**[ICML'25]**
[[Paper](https://arxiv.org/abs/2411.04983)]
[[Project Page](https://dino-wm.github.io/)]
[[Code](https://github.com/gaoyuezhou/dino_wm)]
[[Dataset](https://osf.io/bmw48/overview?view_only=a56a296ce3b24cceaf408383a175ce28)]

- :car: **RenderWorld**: World Model with Self-Supervised 3D Label.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2409.11356)]


- :car: **PreWorld**: Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2502.07309)]
[[Code](https://github.com/getterupper/PreWorld)]

- :car: **SSR**: Navigation-Guided Sparse Scene Representation for End-to-End Autonomous Driving.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2409.18341)]
[[Code](https://github.com/PeidongLi/SSR)]


- :car: **LAW**: Enhancing End-to-End Autonomous Driving with Latent World Model.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2406.08481)]
[[Code](https://github.com/BraveGroup/LAW)]

- :car: **Drive-OccWorld**: Driving in the Occupancy World: Vision-Centric 4D occupancy forecasting and planning via world models for autonomous driving.
**[AAAI'25]**
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33010)]
[[Project Page](https://drive-occworld.github.io/)]
[[Code](https://github.com/yuyang-cloud/Drive-OccWorld)]


- :car: **Raw2Drive**: Reinforcement Learning with Aligned World Models for End-to-End Autonomous Driving (in CARLA v2).
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.16394)]

- :car: **FASTopoWM**: Fast-Slow Lane Segment Topology Reasoning with Latent World Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.23325)]
[[Code](https://github.com/YimingYang23/FASTopoWM)]

- :robot: **RoboOccWorld**: Occupancy World Model for Robots.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.05512)]

- :robot: **EnerVerse**: Envisioning Embodied Future Space for Robotics Manipulation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2501.01895)]
[[Project Page](https://sites.google.com/view/enerverse?pli=1)]



### 2024
- :car: **DriveDreamer**: Towards Real-world-driven World Models for Autonomous Driving.
**[ECCV'24]**
[[Paper](https://arxiv.org/abs/2309.09777)]
[[Project Page](https://drivedreamer.github.io/)]
[[Code](https://github.com/JeffWang987/DriveDreamer)]

- :car: **GenAD**: Generative End-to-End Autonomous Driving.
**[ECCV'24]**
[[Paper](https://arxiv.org/abs/2402.11502)]
[[Code](https://github.com/wzzheng/GenAD)]
[[Dataset](https://drive.google.com/drive/folders/1gy7Ux-bk0sge77CsGgeEzPF9ImVn-WgJ)]

- :car: **OccWorld**: Learning a 3D Occupancy World Model for Autonomous Driving.
**[ECCV'24]**
[[Paper](https://arxiv.org/abs/2311.16038)]
[[Code](https://github.com/wzzheng/OccWorld)]

- :car: **NeMo**: Neural Volumetric World Models for Autonomous Driving.
 **[ECCV'24]**
 [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02571.pdf)]


- :car: **DriveWorld**: 4D pre-trained scene understanding via world models for autonomous driving.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Min_DriveWorld_4D_Pre-trained_Scene_Understanding_via_World_Models_for_Autonomous_CVPR_2024_paper.html)]

- :car: **OccLLaMA**: An Occupancy-Language-Action Generative World Model for Autonomous Driving.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2409.03272)]


## Decision-Coupled / Sequential / Decomposed Rendering Representation
### 2025
- :robot: **ManiGaussian++**: General Robotic Bimanual Manipulation with Hierarchical Gaussian World Model.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2506.19842)]
[[Code](https://github.com/April-Yz/ManiGaussian_Bimanual)]

- :robot: **PIN-WM**: Learning physics-informed world models for non-prehensile manipulation.
**[RSS'25]**
[[Paper](https://arxiv.org/abs/2504.16693)]
[[Project Page](https://pinwm.github.io/)]
[[Code](https://github.com/XuAdventurer/PIN-WM)]

- :robot: **PWTF**: Prompting with the Future: Open-World Model Predictive Control with Interactive Digital Twins.
**[RSS'25]**
[[Paper](https://arxiv.org/abs/2506.13761)]
[[Project Page](https://prompting-with-the-future.github.io/)]
[[Code](https://github.com/TritiumR/Prompting-with-the-Future)]

- :robot: **DreMa**: Dream to Manipulate: Compositional World Models Empowering Robot Imitation Learning with Imagination.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2412.14957)]
[[Project Page](https://dreamtomanipulate.github.io/)]
[[Code](https://github.com/leobarcellona/drema_code)]

- :robot: **GAF**: Gaussian Action Field as a 4D Representation for Dynamic World Modeling in Robotic Manipulation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.14135)]
[[Project Page](https://chaiying1.github.io/GAF.github.io/project_page/)]

- :car: **DTT**: Delta-Triplane Transformers as Occupancy World Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.07338)]

### 2024
- :robot: **Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**.
**[CoRL'24]**
[[Paper](https://arxiv.org/abs/2406.10788)]
[[Project Page](https://embodied-gaussians.github.io/)]
[[Code](https://github.com/bdaiinstitute/embodied_gaussians)]
[[Dataset](https://huggingface.co/datasets/anon211/embodied_gaussians/tree/main)]

- :robot: **ManiGaussian**: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation.
**[ECCV'24]**
[[Paper](https://arxiv.org/abs/2403.08321)]
[[Project Page](https://guanxinglu.github.io/ManiGaussian/)]
[[Code](https://github.com/GuanxingLu/ManiGaussian)]

- :robot: **$\text{DexSim2Real}^{2}$**: Building Explicit World Model for Precise Articulated Object Dexterous Manipulation.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2409.08750)]
[[Project Page](https://jiangtaoran.github.io/dexsim2real2web/)]
[[Code](https://github.com/jiangtaoran/DexSim2Real2)]
[[Video](https://www.youtube.com/watch?v=gW9AHF2zDFY)]

## Decision-Coupled / Global / Token Feature Sequence
### 2026

- :robot: **LDA-1B**: Scaling Latent Dynamics Action Model via Universal Embodied Data Ingestion.
**[RSS'26]**
[[Paper](https://arxiv.org/abs/2602.12215)]
[[Project Page](https://pku-epic.github.io/LDA/)]
[[Code](https://github.com/jiangranlv/LDA-1B)]

- :robot: **Cosmos Policy**: Fine-Tuning Video Models for Visuomotor Control and Planning.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2601.16163)]
[[Project Page](https://research.nvidia.com/labs/dir/cosmos-policy/)]
[[Code](https://github.com/NVlabs/cosmos-policy)]

### 2025

- :robot: **LaDi-WM**: A Latent Diffusion-based World Model for Predictive Manipulation.
**[CoRL'25]**
[[Paper](https://arxiv.org/abs/2505.11528)]
[[Project Page](https://guhuangai.github.io/LaDiWM.github.io/)]
[[Code](https://github.com/GuHuangAI/LaDiWM)]

- :robot: **FLARE**: Robot Learning with Implicit World Modeling.
**[RSSW'25]**
[[Paper](https://arxiv.org/abs/2505.15659)]
[[Project Page](https://research.nvidia.com/labs/gear/flare/)]
[[Code](https://github.com/nvidia/flare)]

- :car: **GeoDrive**: 3D Geometry-Informed Driving World Model with Precise Action Control.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.22421)]
[[Code](https://github.com/antonioo-c/GeoDrive)]

- :robot: **villa-X**: Enhancing Latent Action Modeling in Vision-Language-Action Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.23682)]
[[Project Page](https://microsoft.github.io/villa-x/)]
[[Code](https://github.com/microsoft/villa-x/)]



### 2024
- :robot: **VidMan**: Exploiting Implicit Dynamics from Video Diffusion Model for Effective Robot Manipulation.
**[NeurIPS'24]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/481c70828a4ff20d31a646cc6cc95f3d-Abstract-Conference.html)]


- :car: **TOKEN**: Tokenize the World into Object-level Knowledge to Address Long-tail Events in Autonomous Driving.
**[CoRL'24]**
[[Paper](https://proceedings.mlr.press/v270/tian25b.html)]
[[Project Page](https://thomasrantian.github.io/TOKEN_MM-LLM_for_AutoDriving/)]

## Decision-Coupled / Global / Spatial Latent Grid
### 2026

- :car: **DriveWorld-VLA**: Unified Latent-Space World Modeling with Vision-Language-Action for Autonomous Driving.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.06521)]
[[Code](https://github.com/liulin815/DriveWorld-VLA)]

### 2025

- :robot: **TesserAct**: Learning 4D Embodied World Models.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2504.20995)]
[[Project Page](https://tesseractworld.github.io/)]
[[Code](https://github.com/UMass-Embodied-AGI/TesserAct)]

- :car: **World4Drive**: End-to-End Autonomous Driving via Intention-aware Physical Latent World Model.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2507.00603)]
[[Code](https://github.com/ucaszyp/World4Drive)]


- :car: **Imagine-2-Drive**: Leveraging High-Fidelity World Models via Multi-Modal Diffusion Policies.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2411.10171)]
[[Project Page](https://imagine-2-drive.github.io/)]
[[Video](https://www.youtube.com/watch?v=fbwm_pdS-Ss)]

- :robot: **COMBO**: Compositional World Models for Embodied Multi-Agent Cooperation.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2404.10775)]
[[Project Page](https://umass-embodied-agi.github.io/COMBO/)]
[[Code](https://github.com/UMass-Embodied-AGI/COMBO)]

- :robot: **EmbodieDreamer**: Advancing Real2Sim2Real Transfer for Policy Training via Embodied World Modeling.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.05198)]
[[Project Page](https://embodiedreamer.github.io/)]
[[Code](https://github.com/GigaAI-research/EmbodieDreamer)]

- :robot: **ManipDreamer**: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2504.16464)]

- :robot: **3DFlowAction**: Learning Cross-Embodiment Manipulation from 3D Flow World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.06199)]
[[Code](https://github.com/Hoyyyaard/3DFlowAction/)]

### 2024
- :robot: **RoboDreamer**: Learning Compositional World Models for Robot Imagination.
**[ICML'24]**
[[Paper](https://proceedings.mlr.press/v235/zhou24f.html)]
[[Project Page](https://robovideo.github.io/)]
[[Code](https://github.com/rainbow979/robodreamer)]

- :car: **Drive-WM**: Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Driving_into_the_Future_Multiview_Visual_Forecasting_and_Planning_with_CVPR_2024_paper.html)]
[[Project Page](https://drive-wm.github.io/)]
[[Code](https://github.com/BraveGroup/Drive-WM)]


- :car: **DFIT-OccWorld**：An Efficient Occupancy World Model via Decoupled Dynamic Flow and Image-assisted Training.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.13772)]


## General-Purpose / Sequential / Token Feature Sequence
### 2026

- :robot: **Interactive World Simulator**: Robot Policy Training and Evaluation.
**[RSS'26]**
[[Paper](https://arxiv.org/abs/2603.08546)]
[[Project Page](https://www.yixuanwang.me/interactive_world_sim/)]
[[Code](https://github.com/WangYixuan12/interactive_world_sim)]

- :robot: **RoboWorld**: Fast and Reliable Neural Simulators for Generalist Robot Policy Evaluation.
**[ICMLW'26]**
[[Paper](https://arxiv.org/abs/2607.01060)]

- :car: **OmniDreams**: Real-Time Generative World Model for Closed-Loop Autonomous Vehicle Simulation.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2606.03159)]
[[Project Page](https://research.nvidia.com/labs/sil/projects/omnidreams-blog/)]
[[Code](https://github.com/nv-tlabs/omni-dreams)]

### 2025

- :car: **Orbis**: Overcoming Challenges of Long-Horizon Prediction in Driving World Models.
**[NeurIPS'25]**
[[Paper](https://arxiv.org/abs/2507.13162)]
[[Project Page](https://lmb-freiburg.github.io/orbis.github.io/)]
[[Code](https://github.com/lmb-freiburg/orbis)]

- :robot: **RLVR-World**: Training World Models with Reinforcement Learning.
**[NeurIPS'25]**
[[Paper](https://arxiv.org/abs/2505.13934)]
[[Project Page](https://thuml.github.io/RLVR-World/)]
[[Code](https://github.com/thuml/RLVR-World)]
[[Dataset](https://huggingface.co/collections/thuml/rlvr-world-682f331c75a904b8febc366a)]

- :car: **DriVerse**: Navigation World Model for Driving Simulation via Multimodal Trajectory Prompting and Motion Alignment.
**[ACMMM'25]**
[[Paper](https://arxiv.org/abs/2504.18576)]
[[Code](https://github.com/shalfun/DriVerse)]

- :robot: **Long-Context State-Space Video World Models**.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2505.20171)]
[[Project Page](https://ryanpo.com/ssm_wm/)]

- :car: **World model-based end-to-end scene generation for accident anticipation in autonomous driving**.
**[Nat. Commun. Eng.'25]**
[[Paper](https://www.nature.com/articles/s44172-025-00474-7)]
[[Code](https://github.com/humanlabmembers/Anticipation-of-Traffic-Accident)]
[[Dataset](https://github.com/humanlabmembers/Anticipation-of-Traffic-Accident)]

- :robot: **EVA**: Empowering World Models with Reflection for Embodied Video Prediction.
**[ICML'25]**
[[Paper](https://openreview.net/forum?id=onumui0nHi)]
[[Project Page](https://sites.google.com/view/icml-eva)]

- :robot: **AdaWorld**: Learning Adaptable World Models with Latent Actions.
**[ICML'25]**
[[Paper](https://arxiv.org/abs/2503.18938)]
[[Project Page](https://adaptable-world-model.github.io/)]
[[Code](https://github.com/Little-Podi/AdaWorld)]

- :clapper: **Hand2World**: Autoregressive Egocentric Interaction Generation via Free-Space Hand Gestures.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2602.09600)]
[[Project Page](https://hand2world.github.io/)]

- :clapper: **DINO-World**: Back to the Features: DINO as a Foundation for Video World Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.19468)]

- :robot: **RoboScape**: Physics-informed Embodied World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.23135)]
[[Code](https://github.com/tsinghua-fib-lab/RoboScape)]

- :clapper: **Yume**: An Interactive World Generation Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.17744)]
[[Project Page](https://stdstu12.github.io/YUME-Project/)]
[[Code](https://github.com/stdstu12/YUME)]
[[Video](https://www.youtube.com/watch?v=51VII_iJ1EM)]
[[Dataset](https://docs.google.com/forms/d/e/1FAIpQLSd5GiQLL1vZQSo0fMDDINd2i_N0rga0a5008Td3lMw9ZimcUQ/viewform?pli=1)]

- :robot: **World4Omni**: A Zero-Shot Framework from Image Generation World Model to Robotic Manipulation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.23919)]
[[Project Page](https://world4omni.github.io/)]

- :robot: **Vid2World**: Crafting Video Diffusion Models to Interactive World Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.14357)]
[[Project Page](https://knightnemo.github.io/vid2world/)]

- :clapper: **Geometry Forcing**: Marrying Video Diffusion and 3D Representation for Consistent World Modeling.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.07982)]
[[Project Page](https://geometryforcing.github.io/)]
[[Code](https://github.com/CIntellifusion/GeometryForcing)]

- :clapper: **DeepVerse**: 4D Autoregressive Video Generation as a World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.01103)]
[[Project Page](https://sotamak1r.github.io/deepverse/)]
[[Code](https://github.com/SOTAMak1r/DeepVerse)]

- :robot: **VRAG**: Learning World Models for Interactive Video Generation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.21996)]

- :robot: **StateSpaceDiffuser**: Bringing Long Context to Diffusion World Models.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.22246)]

- :car: **LongDWM**: Cross-Granularity Distillation for Building a Long-Term Driving World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.01546)]
[[Project Page](https://wang-xiaodong1899.github.io/longdwm/)]
[[Code](https://github.com/Wang-Xiaodong1899/Long-DWM)]

- :car: **MiLA**: Multi-view Intensive-fidelity Long-term Video Generation World Model for Autonomous Driving.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.15875)]
[[Code](https://github.com/xiaomi-mlab/mila.github.io)]

- :robot: **S2-SSM**: Learning Local Causal World Models with State Space Models and Attention.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.02074)]

- :robot: **WorldGym**: World Model as An Environment for Policy Evaluation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.00613)]
[[Project Page](https://world-model-eval.github.io/abstract.html)]
[[Code](https://github.com/world-model-eval/world-model-eval)]
[[Demo](https://world-model-eval.github.io/)]

- :robot: **WorldEval**: World Model as Real-World Robot Policies Evaluator.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.19017)]
[[Project Page](https://worldeval.github.io/)]
[[Code](https://github.com/liyaxuanliyaxuan/Worldeval)]

- :robot: **World-in-World**: World Models in a Closed-Loop World.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2510.18135)]
[[Project Page](https://world-in-world.github.io/)]
[[Code](https://github.com/World-In-World/world-in-world)]
[[Dataset](https://huggingface.co/datasets/zonszer/WIW_datasets/tree/main)]

### 2024

- :robot: **iVideoGPT**: Interactive VideoGPTs are Scalable World Models.
**[NeurIPS'24]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/7dbb5bfab324e3b86af9bd0df15498dd-Abstract-Conference.html)]
[[Project Page](https://thuml.github.io/iVideoGPT/)]
[[Code](https://github.com/thuml/iVideoGPT)]
[[Poster](https://manchery.github.io/assets/pub/nips2024_ivideogpt/poster.pdf)]

- :clapper: **Genie**: Generative Interactive Environments.
**[ICML'24]**
[[Paper](https://proceedings.mlr.press/v235/bruce24a.html)]
[[Code](https://github.com/myscience/open-genie)]

- :car: **GenAD**: Generalized Predictive Model for Autonomous Driving.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_Generalized_Predictive_Model_for_Autonomous_Driving_CVPR_2024_paper.html)]
[[Dataset](https://github.com/OpenDriveLab/DriveAGI)]
[[Poster](https://github.com/OpenDriveLab/DriveAGI/blob/main/assets/cvpr24_genad_poster.png)]
[[Video](https://www.youtube.com/watch?v=a4H6Jj-7IC0)]

- :clapper: **Owl-1**: Omni World Model for Consistent Long Video Generation.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.09600)]
[[Code](https://github.com/huang-yh/Owl)]

- :clapper: **Pandora**: Towards General World Model with Natural Language Actions and Video States.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2406.09455)]
[[Project Page](https://world-model.maitrix.org/)]
[[Code](https://github.com/maitrix-org/Pandora)]
[[Video](https://www.youtube.com/watch?v=nSKqr1Fl91g)]

- :car: **InfinityDrive**: Breaking Time Limits in Driving World Models.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.01522)]
[[Project Page](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html)]

### Earlier
- :compass: **PACT**: Perception-Action Causal Transformer for Autoregressive Robotics Pre-Training.
**[IROS'23]**
[[Paper](https://arxiv.org/abs/2209.11133)]


## General-Purpose / Sequential / Spatial Latent Grid
### 2026

- :robot: **EgoSim**: Egocentric World Simulator for Embodied Interaction Generation.
**[ECCV'26]**
[[Paper](https://arxiv.org/abs/2604.01001)]
[[Project Page](https://egosimulator.github.io/)]
[[Code](https://github.com/jinkun-hao/EgoSim)]

### 2025

- :car: **STAGE**: A Stream-Centric Generative World Model for Long-Horizon Driving-Scene Simulation.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2506.13138)]
[[Project Page](https://4dvlab.github.io/STAGE/)]

- :clapper: **GEM**: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Hassan_GEM_A_Generalizable_Ego-Vision_Multimodal_World_Model_for_Fine-Grained_Ego-Motion_CVPR_2025_paper.html)]
[[Project Page](https://vita-epfl.github.io/GEM.github.io/)]
[[Code](https://github.com/vita-epfl/GEM)]

- :car: **LidarDM**: Generative LiDAR Simulation in a Generated World.
**[ICRA'25]**
[[Paper](https://arxiv.org/abs/2404.02903)]
[[Project Page](https://zyrianov.org/lidardm/)]
[[Code](https://github.com/vzyrianov/LidarDM)]


- :clapper: **FOLIAGE**: Towards Physical Intelligence World Models Via Unbounded Surface Evolution.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.03173)]

- :compass: **MindJourney**: Test-Time Scaling with World Models for Spatial Reasoning.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.12508)]
[[Project Page](https://umass-embodied-agi.github.io/MindJourney/)]
[[Code](https://github.com/UMass-Embodied-AGI/MindJourney)]

- :compass: **Learning 3D Persistent Embodied World Models**.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.05495)]

### 2024

- :car: **Vista**: A Generalizable Driving World Model with High Fidelity and Versatile Controllability.
**[NeurIPS'24]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a6a066fb44f2fe0d36cf740c873b8890-Abstract-Conference.html)]
[[Project Page](https://opendrivelab.com/Vista/)]
[[Code](https://github.com/OpenDriveLab/Vista)]

- :car: **Copilot4D**: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion.
**[ICLR'24]**
[[Paper](https://arxiv.org/abs/2311.01017)]

- :car: **ViDAR**: Visual Point Cloud Forecasting enables Scalable Autonomous Driving.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_Visual_Point_Cloud_Forecasting_enables_Scalable_Autonomous_Driving_CVPR_2024_paper.html)]
[[Code](https://github.com/OpenDriveLab/ViDAR)]

- :car: **DOME**: Taming Diffusion Model into High-Fidelity Controllable Occupancy World Model.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2410.10429)]
[[Project Page](https://gusongen.github.io/DOME/)]
[[Code](https://github.com/gusongen/DOME)]

- :car: **Delphi**: Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2406.01349)]
[[Project Page](https://westlake-autolab.github.io/delphi.github.io/)]
[[Code](https://github.com/westlake-autolab/Delphi)]

### Earlier

- :clapper: **PhyDNet**: Disentangling Physical Dynamics From Unknown Factors for Unsupervised Video Prediction.
**[CVPR'20]**
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Le_Guen_Disentangling_Physical_Dynamics_From_Unknown_Factors_for_Unsupervised_Video_Prediction_CVPR_2020_paper.html)]
[[Code](https://github.com/vincent-leguen/PhyDNet)]




## General-Purpose / Sequential / Decomposed Rendering Representation
### 2025
- :car: **InfiniCube**: Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2412.03934)]
[[Project Page](https://research.nvidia.com/labs/toronto-ai/infinicube/)]
[[Code](https://github.com/nv-tlabs/InfiniCube)]

- :car: **GaussianWorld**: Gaussian World Model for Streaming 3D Occupancy Prediction.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zuo_GaussianWorld_Gaussian_World_Model_for_Streaming_3D_Occupancy_Prediction_CVPR_2025_paper.html)]
[[Code](https://github.com/zuosc19/GaussianWorld)]

- :clapper: **Video World Models with Long-term Spatial Memory**.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.05284)]
[[Project Page](https://spmem.github.io/)]


## General-Purpose / Global / Token Feature Sequence
### 2026
- :robot: **Cosmos 3**: Omnimodal World Models for Physical AI.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2606.02800)]
[[Project Page](https://research.nvidia.com/labs/cosmos-lab/cosmos3/)]
[[Code](https://github.com/nvidia/cosmos)]

- :robot: **Qwen-RobotWorld**: Unifying Embodied World Modeling through Language-Conditioned Video Generation.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2606.17030)]
[[Project Page](https://qwen.ai/blog?id=qwen-robotworld)]

- :clapper: **V-JEPA 2.1**: Unlocking Dense Features in Video Self-Supervised Learning.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2603.14482)]
[[Code](https://github.com/facebookresearch/vjepa2)]

### 2025
- :clapper: **MarsGen**: Martian World Models: Controllable Video Synthesis with Physically Accurate 3D Reconstructions.
**[NeurIPS'25]**
[[Paper](https://arxiv.org/abs/2507.07978)]
[[Project Page](https://marsgenai.github.io/)]
[[Code](https://github.com/loongfeili/Martian-World-Model)]
[[Dataset](https://huggingface.co/datasets/LongfeiLi/M3arsSynth)]

- :car: **MaskGWM**: A Generalizable Driving World Model with Video Mask Reconstruction.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_MaskGWM_A_Generalizable_Driving_World_Model_with_Video_Mask_Reconstruction_CVPR_2025_paper.html)]
[[Code](https://github.com/SenseTime-FVG/OpenDWM)]
[[Video](https://www.youtube.com/watch?v=j9RRj-xzOA4)]

- :clapper: **EchoWorld**: Learning Motion-Aware World Models for Echocardiography Probe Guidance.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Yue_EchoWorld_Learning_Motion-Aware_World_Models_for_Echocardiography_Probe_Guidance_CVPR_2025_paper.html)]
[[Code](https://github.com/LeapLabTHU/EchoWorld)]

- :clapper: **V-JEPA 2**: Self-Supervised Video Models Enable Understanding, Prediction and Planning.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.09985)]
[[Project Page](https://ai.meta.com/vjepa/)]
[[Code](https://github.com/facebookresearch/vjepa2)]
[[Blog](https://ai.meta.com/blog/v-jepa-2-world-model-benchmarks/)]

- :car: **DINO-Foresight**: Looking into the Future with DINO.
**[NeurIPS'25]**
[[Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/efaca9631eb6bd5df8f6761c5d9a9fe3-Abstract-Conference.html)]
[[Project Page](https://dino-foresight.github.io/)]
[[Code](https://github.com/Sta8is/DINO-Foresight)]

- :car: **AD-L-JEPA**: Self-Supervised Representation Learning with Joint Embedding Predictive Architecture for Automotive LiDAR Object Detection.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2501.04969)]

- :clapper: **AirScape**: An Aerial Generative World Model with Motion Controllability.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.08885)]
[[Project Page](https://embodiedcity.github.io/AirScape/)]

- :robot: **ForeDiff**: Consistent World Models via Foresight Diffusion.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2505.16474)]

### 2024
- :clapper: **V-JEPA**: Revisiting Feature Prediction for Learning Visual Representations from Video.
**[TMLR'24]**
[[Paper](https://openreview.net/forum?id=QaCCuDfBk2)]
[[Code](https://github.com/facebookresearch/jepa)]
[[Blog](https://ai.meta.com/blog/v-jepa-yann-lecun-ai-model-video-joint-embedding-predictive-architecture/)]
[[Video](https://www.youtube.com/watch?v=7UkJPwz_N_0)]

- :clapper: **WorldDreamer**: Towards General World Models for Video Generation via Predicting Masked Tokens.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2401.09985)]
[[Project Page](https://world-dreamer.github.io/)]
[[Code](https://github.com/JeffWang987/WorldDreamer)]

- :clapper: **Sora**: Video generation models as world simulators.
**[OpenAI'24]**
[[Paper](https://openai.com/index/video-generation-models-as-world-simulators/)]




## General-Purpose / Global / Spatial Latent Grid
### 2025
- :car: **GAIA-2**: A Controllable Multi-View Generative World Model for Autonomous Driving.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.20523)]
[[Project Page](https://wayve.ai/thinking/gaia-2/)]

- :car: **HERMES**: A Unified Self-Driving World Model for Simultaneous 3D Scene Understanding and Generation.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2501.14729)]
[[Project Page](https://lmd0311.github.io/HERMES/)]
[[Code](https://github.com/LMD0311/HERMES)]

- :clapper: **Aether**: Geometric-Aware Unified World Modeling.
**[ICCV'25]**
[[Paper](https://arxiv.org/abs/2503.18945)]
[[Project Page](https://aether-world.github.io/)]
[[Code](https://github.com/InternRobotics/Aether)]

- :car: **PosePilot**: Steering Camera Pose for Generative World Models with Self-supervised Depth.
**[IROS'25]**
[[Paper](https://arxiv.org/abs/2505.01729)]

- :car: **DynamicCity**: Large-Scale 4D Occupancy Generation from Dynamic Scenes.
**[ICLR'25]**
[[Paper](https://arxiv.org/abs/2410.18084)]
[[Project Page](https://dynamic-city.github.io/)]
[[Code](https://github.com/3DTopia/DynamicCity)]

- :car: **DriveDreamer-2**: LLM-Enhanced World Models for Diverse Driving Video Generation.
**[AAAI'25]**
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33130)]
[[Project Page](https://drivedreamer2.github.io/)]
[[Code](https://github.com/f1yfisher/DriveDreamer2)]

- :car: **UniFuture**: Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.13587)]
[[Project Page](https://dk-liang.github.io/UniFuture/)]
[[Code](https://github.com/dk-liang/UniFuture)]

- :car: **Towards foundational LiDAR world models with efficient latent flow matching**.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.23434)]
[[Project Page](https://orbis36.github.io/AdaFlowMatchingWM-Web/)]


- :car: **COME**: Adding Scene-Centric Forecasting Control to Occupancy World Model.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.13260)]
[[Code](https://github.com/synsin0/COME)]

- :robot: **Geometry-aware 4D Video Generation for Robot Manipulation**.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2507.01099)]
[[Project Page](https://robot4dgen.github.io/)]
[[Code](https://github.com/lzylucy/4dgen)]
[[Dataset](https://real.stanford.edu/4dgen/)]

- :car: **EOT-WM**: Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2503.09215)]

- :robot: **ORV**: 4D Occupancy-centric Robot Video Generation.
**[arXiv'25]**
[[Paper](https://arxiv.org/abs/2506.03079)]
[[Project Page](https://orangesodahub.github.io/ORV/)]
[[Code](https://github.com/OrangeSodahub/ORV)]

### 2024
- :car: **Cam4DOcc**: Benchmark for Camera-Only 4D Occupancy Forecasting in Autonomous Driving Applications.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ma_Cam4DOcc_Benchmark_for_Camera-Only_4D_Occupancy_Forecasting_in_Autonomous_Driving_CVPR_2024_paper.html)]
[[Code](https://github.com/haomo-ai/Cam4DOcc)]


- :car: **BEVWorld**: A Multimodal World Simulator for Autonomous Driving via Scene-Level BEV Latents.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2407.05679)]

- :car: **OccSora**: 4D Occupancy Generation Models as World Simulators for Autonomous Driving.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2405.20337)]
[[Code](https://github.com/wzzheng/OccSora)]

- :car: **DrivePhysica**: Physical Informed Driving World Model.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2412.08410)]
[[Code](https://github.com/DrivePhysica)]

### Earlier
- :car: **Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting**.
**[CVPR'23]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Khurana_Point_Cloud_Forecasting_as_a_Proxy_for_4D_Occupancy_Forecasting_CVPR_2023_paper.html)]
[[Project Page](https://www.cs.cmu.edu/~tkhurana/ff4d/index.html)]
[[Code](https://github.com/tarashakhurana/4d-occ-forecasting)]
[[Video](https://www.youtube.com/watch?v=v9rmkYEYmh8)]


- :car: **Differentiable Raycasting for Self-Supervised Occupancy Forecasting**.
**[ECCV'22]**
[[Paper](https://arxiv.org/abs/2210.01917)]
[[Project Page](https://github.com/tarashakhurana/emergent-occ-forecasting)]
[[Code](https://www.cs.cmu.edu/~tkhurana/ff3d.html)]
[[Video](https://www.youtube.com/watch?v=QqSCu0KJ2FM)]

- :car: **Self-supervised Point Cloud Prediction Using 3D Spatio-temporal Convolutional Networks**.
**[CoRL'21]**
[[Paper](https://proceedings.mlr.press/v164/mersch22a.html)]
[[Code](https://github.com/PRBonn/point-cloud-prediction)]








## General-Purpose / Global / Decomposed Rendering Representation
### 2026

- :clapper: **HY-World 2.0**: A Multi-Modal World Model for Reconstructing, Generating, and Simulating 3D Worlds.
**[arXiv'26]**
[[Paper](https://arxiv.org/abs/2604.14268)]
[[Project Page](https://3d-models.hunyuan.tencent.com/world/)]
[[Code](https://github.com/Tencent-Hunyuan/HY-World-2.0)]

### 2025

- :car: **DriveDreamer4D**: World Models Are Effective Data Machines for 4D Driving Scene Representation.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_DriveDreamer4D_World_Models_Are_Effective_Data_Machines_for_4D_Driving_CVPR_2025_paper.html)]
[[Project Page](https://drivedreamer4d.github.io/)]
[[Code](https://github.com/GigaAI-research/DriveDreamer4D)]

- :car: **ReconDreamer**: Crafting World Models for Driving Scene Reconstruction via Online Restoration.
**[CVPR'25]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ni_ReconDreamer_Crafting_World_Models_for_Driving_Scene_Reconstruction_via_Online_CVPR_2025_paper.html)]
[[Project Page](https://recondreamer.github.io/)]
[[Code](https://github.com/GigaAI-research/ReconDreamer)]



### 2024
- :car: **UnO**: Unsupervised Occupancy Fields for Perception and Forecasting.
**[CVPR'24]**
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Agro_UnO_Unsupervised_Occupancy_Fields_for_Perception_and_Forecasting_CVPR_2024_paper.html)]

- :car: **MagicDrive3D**: Controllable 3D Generation for Any-View Rendering in Street Scenes.
**[arXiv'24]**
[[Paper](https://arxiv.org/abs/2405.14475)]
[[Project Page](https://gaoruiyuan.com/magicdrive3d/)]
[[Code](https://github.com/flymin/MagicDrive3D)]
