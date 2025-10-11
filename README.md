![](./files/RoboScholar-logo.png)
<h1 align="center">
	RoboScholar: A Comprehensive Paper List of Embodied AI and Robotics Research
</h1>

> It's RoboScholar Project Here, started by [Tianxing Chen](http://tianxingchen.github.io/).<br>
> Related Information:
<div style="">
  <div>
    <img src="./files/RoboScholar-logo.png">
    <p>Lumina Embodied AI Community</p>
  </div>
  <div>
    <img src="./files/RoboScholar-logo.png">
    <p>Embodied-AI-Guide</p>
  </div>
</div>

## Sections
- Manipulation
  - Imitation Learning (IL)
  - Reinforcement Learning (RL)
  - Humanoid Whole-Body Control
  - Dexterous Manipulation
  - World Model
  - Tectile Manipulation
- Simulations
  - Platform
  - [Dataset & Benchmark](./topics/simulations/dataset_and_benchmark.md)
- [Robot Hardware]()
  - [Data Collection](./)
- [Real World Dataset]()
- [Robot Nevigation]()
- [Locomotion]()
- [LLM Agent for Robotics]()
- Computer Vision
  - [Foundation Models & Tools]()
  - [2DV]()
  - [3DV]()
- Embodied AI for X
  - [Medical]()



# Recent Random Papers
Open-Vocabulary 3D Articulated Objects Modeling
https://arxiv.org/pdf/2507.02747






- [] **[arXiv 25]** LEMON: Learning 3D Human-Object Interaction Relation from 2D Images, [arXiv](https://arxiv.org/pdf/2312.08963)

- [] **[arXiv 25]** Merging and Disentangling Views in Visual Reinforcement Learning for Robotic Manipulation, [arXiv](https://arxiv.org/abs/2505.04619)


- [] **[RSS 25]** Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation, [arXiv](https://reactive-diffusion-policy.github.io/)
- [] **[arXiv 24]** GRAPE: Generalizing Robot Policy via Preference Alignment, [arXiv](https://arxiv.org/abs/2411.19309)
- [] **[arXiv 25]** GROVE: A Generalized Reward for Learning Open-Vocabulary Physical Skill, [arXiv](https://arxiv.org/abs/2504.04191)
- [] **[arXiv 24]** Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers, [arXiv](https://arxiv.org/abs/2409.20537)





## 1. Diffusion Model for Planning, Policy, and RL

- [] **[arXiv 24]** Surgical Robot Transformer: Imitation Learning for Surgical Tasks, [website](https://surgical-robot-transformer.github.io/)

## 6. Generative Model for Embodied
- [] **[arXiv 24]** Generative Image as Action Models, [website](https://genima-robot.github.io/)

- [] **[arXiv 24]** Genie: Generative Interactive Environments, [website](https://sites.google.com/view/genie-24/home)



## 9. Pose Estimation and Tracking
- [] **[CVPR 24 (Highlight)]** FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects, [website](https://nvlabs.github.io/FoundationPose/)

- [] **[CVPR 23 (Highlight)]** GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts, [website](https://pku-epic.github.io/GAPartNet/)

- [] **[arXiv 23]** GAMMA: Generalizable Articulation Modeling and Manipulation for Articulated Objects, [website](https://sites.google.com/view/gamma-articulation)

- [] **[arXiv 24]** ManiPose: A Comprehensive Benchmark for Pose-aware Object Manipulation in Robotics, [website](https://sites.google.com/view/manipose)

- [] **[ICCV 23]** AffordPose: A Large-scale Dataset of Hand-Object Interactions with Affordance-driven Hand Pose, [website](https://affordpose.github.io/)

- [] **[CVPR 23]** BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects, [website](https://bundlesdf.github.io/)

- [] **[arXiv 24]** WiLoR: End-to-end 3D hand localization and reconstruction in-the-wild, [website](https://rolpotamias.github.io/WiLoR/)





## TO READ

* Where2Act: From Pixels to Actions for Articulated 3D Objects

* PreAfford: Universal Affordance-Based Pre-Grasping for Diverse Objects and Environments

* Decision Transformer: Reinforcement Learning via Sequence Modeling

* Toward General-Purpose Robots via Foundation Models: A Survey and Meta-Analysis

* AO-Grasp: Articulated Object Grasp Generation

* Human-to-Robot Imitation in the Wild

* RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots

* SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation https://sam-embodied.github.io/, ICML24

* https://progprompt.github.io/

* PerAct, Act3D

* https://groups.csail.mit.edu/vision/datasets/ADE20K/

* Probing the 3D Awareness of Visual Foundation Model: https://arxiv.org/pdf/2404.08636

* ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models

* CLIP: Zero-shot Jack of All Trades, [website](https://blog.kzakka.com/posts/clip/), [CLIP GradCAM CLIP_GradCAM_Visualization](https://colab.research.google.com/github/kevinzakka/clip_playground/blob/main/CLIP_GradCAM_Visualization.ipynb)

* Articulated Object Manipulation with Coarse-to-fine Affordance for Mitigating the Effect of Point Cloud Noise: https://arxiv.org/pdf/2402.18699

* 3D-VLA: A 3D Vision-Language-Action Generative World Model
* PDDLGym: Gym Environments from PDDL Problems: https://arxiv.org/abs/2002.06432
* https://github.com/zjunlp/LLMAgentPapers?tab=readme-ov-file
* https://github.com/zjunlp/Prompt4ReasoningPapers
* TravelPlanner: A Benchmark for Real-World Planning with Language Agents
* VisionLLM: https://arxiv.org/abs/2305.11175
* Ferret: Refer and Ground Anything Anywhere at Any Granularity: https://github.com/apple/ml-ferret
* LangSplat
* Embodied AI with Two Arms: Zero-shot Learning, Safety and Modularity
* SparseDFF
* ManiPose: A Comprehensive Benchmark for Pose-aware Object Manipulation in Robotics

1. **Stabilizing Transformers for Reinforcement Learning**
   - **Summary**: 本文提出了Gated Transformer-XL (GTrXL)，一种改进的Transformer架构，用于解决标准Transformer在强化学习中的优化难题。通过引入层归一化和门控机制，GTrXL在部分可观察性环境中取得了优于LSTM的性能。
   - [链接](https://arxiv.org/abs/1910.06764)

2. **CoBERL: Contrastive BERT for Reinforcement Learning**
   - **Summary**: 文章介绍了CoBERL，它结合了对比损失和Transformer架构，通过双向掩码预测和对比学习方法提高强化学习中的数据效率和性能。
   - [链接](https://arxiv.org/abs/2107.05431)

3. **Adaptive Transformers in RL**
   - **Summary**: 该研究探索了在强化学习中使用具有自适应注意力跨度的Transformer模型，发现这种方法能够提高模型在需要长期依赖的环境中的性能。
   - [链接](https://arxiv.org/abs/2004.03761)

4. **Efficient Transformers in Reinforcement Learning using Actor-Learner Distillation**
   - **Summary**: 本文提出了Actor-Learner Distillation (ALD)方法，通过从大型学习者模型向小型执行者模型进行知识蒸馏，以提高Transformer在强化学习中的样本效率。
   - [链接](https://arxiv.org/abs/2104.01655)

5. **Deep Transformer Q-Networks for Partially Observable Reinforcement Learning**
   - **Summary**: 介绍了Deep Transformer Q-Networks (DTQN)，这是一种新型的强化学习架构，使用Transformer的自注意力机制来处理部分可观察性任务，并在多个挑战性环境中展示了有效性。
   - [链接](https://arxiv.org/abs/2206.01078)

6. **CtrlFormer: Learning Transferable State Representation for Visual Control via Transformer**
   - **Summary**: CtrlFormer是一种新型的Transformer架构，专注于通过学习可迁移的状态表示来提高视觉控制任务的样本效率，特别强调了在跨任务迁移学习方面的优势。
   - [链接](https://arxiv.org/abs/2206.08883)
  
Sapiens: Foundation for Human Vision Models: https://about.meta.com/realitylabs/codecavatars/sapiens
General Flow as Foundation Affordance for Scalable Robot Learning https://general-flow.github.io/
