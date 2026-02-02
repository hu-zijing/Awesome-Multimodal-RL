# Reinforcement Learning in Generative Multimodal AI

## Introduction

Generative multimodal artificial intelligence (AI) has achieved remarkable progress in recent years, driven by large-scale pre-training and the emergence of powerful foundation models. While these models have demonstrated strong capabilities in perception, reasoning, and content synthesis, their training is predominantly based on supervised objectives, which are often insufficient to capture task-specific goals and user intent. Reinforcement learning (RL) has therefore emerged as a critical training framework for improving generative multimodal models. 

This repository collects research papers on **reinforcement learning in generative multimodal AI**. We primarily focus on three categories of models: 
* **Multimodal understanding models**, which focus on perceiving and reasoning over visual inputs and produce corresponding natural language responses. 
* **Visual generation models**, which synthesize visual content conditioned on textual prompts or inputs from other modalities. 
* **Unified models**, which adopt a single framework to jointly support visual understanding and visual generation, allowing multimodal inputs and flexibly producing outputs in the visual or textual form. 

## Papers

### Autoregression-based RL

* [2512] [EMA-GRPO] [OneThinker: All-in-one Reasoning Model for Image and Video](https://arxiv.org/abs/2512.03043)

* [2510] [PIVOT] [RL makes MLLMs see better than SFT](https://arxiv.org/abs/2510.16333)

* [2510] [RewardMap] [RewardMap: Tackling Sparse Rewards in Fine-grained Visual Reasoning via Multi-Stage Reinforcement Learning](https://arxiv.org/abs/2510.02240)

* [2509] [STAGE] [STAGE: Stable and Generalizable GRPO for Autoregressive Image Generation](https://arxiv.org/abs/2509.25027)

* [2509] [GCPO] [Group Critical-token Policy Optimization for Autoregressive Image Generation](https://arxiv.org/abs/2509.22485)

* [2508] [DGRPO] [Thinking With Videos: Multimodal Tool-Augmented Reinforcement Learning for Long Video Reasoning](https://arxiv.org/abs/2508.04416)

* [2508] [AR-GRPO] [AR-GRPO: Training Autoregressive Image Generation Models via Reinforcement Learning](https://arxiv.org/abs/2508.06924)

* [2507] [X-Omni] [X-Omni: Reinforcement Learning Makes Discrete Autoregressive Image Generative Models Great Again](https://arxiv.org/abs/2507.22058)

* [2507] [3D-R1] [3D-R1: Enhancing Reasoning in 3D VLMs for Unified Scene Understanding](https://arxiv.org/abs/2507.23478)

* [2507] [Multi-Image] [Improving the Reasoning of Multi-Image Grounding in MLLMs via Reinforcement Learning](https://arxiv.org/abs/2507.00748)

* [2506] [VL-GenRM] [VL-GenRM: Enhancing Vision-Language Verification via Vision Experts and Iterative Training](https://arxiv.org/abs/2506.13888)

* [2506] [Temporal-RLT] [Reinforcement Learning Tuning for VideoLLMs: Reward Design and Data Efficiency](https://arxiv.org/abs/2506.01908)

* [2506] [SRPO] [SRPO: Enhancing Multimodal LLM Reasoning via Reflection-Aware Reinforcement Learning](https://arxiv.org/abs/2506.01713)

* [2506] [RAPID] [Reasoning-Aligned Perception Decoupling for Scalable Multi-modal Reasoning](https://arxiv.org/abs/2506.04559)

* [2506] [GThinker] [GThinker: Towards General Multimodal Reasoning via Cue-Guided Rethinking](https://arxiv.org/abs/2506.01078)

* [2506] [DeepVideo-R1] [DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO](https://arxiv.org/abs/2506.07464)

* [2506] [SVQA-R1] [SVQA-R1: Reinforcing Spatial Reasoning in MLLMs via View-Consistent Reward Optimization](https://arxiv.org/abs/2506.01371)

* [2506] [ViLaSR] [Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing](https://arxiv.org/abs/2506.09965)

* [2506] [GRPO-CARE] [GRPO-CARE: Consistency-Aware Reinforcement Learning for Multimodal Reasoning](https://arxiv.org/abs/2506.16141)

* [2506] [WeThink] [WeThink: Toward General-purpose Vision-Language Reasoning via Reinforcement Learning](https://arxiv.org/abs/2506.07905)

* [2506] [FocusDiff] [FocusDiff: Advancing Fine-Grained Text-Image Alignment for Autoregressive Visual Generation through RL](https://arxiv.org/abs/2506.05501)

* [2506] [ViCrit] [ViCrit: A Verifiable Reinforcement Learning Proxy Task for Visual Perception in VLMs](https://arxiv.org/abs/2506.10128)

* [2506] [MiMo-VL] [MiMo-VL Technical Report](https://arxiv.org/abs/2506.03569)

* [2506] [Scene-R1] [Scene-R1: Video-Grounded Large Language Models for 3D Scene Reasoning without 3D Annotations](https://arxiv.org/abs/2506.17545)

* [2506] [AV-Reasoner] [AV-Reasoner: Improving and Benchmarking Clue-Grounded Audio-Visual Counting for MLLMs](https://arxiv.org/abs/2506.05328)

* [2506] [Q-Ponder] [Q-Ponder: A Unified Training Pipeline for Reasoning-based Visual Quality Assessment](https://arxiv.org/abs/2506.05384)

* [2506] [VQ-Insight] [VQ-Insight: Teaching VLMs for AI-Generated Video Quality Understanding via Progressive Visual Reinforcement Learning](https://arxiv.org/abs/2506.18564)

* [2506] [TimeMaster] [TimeMaster: Training Time-Series Multimodal LLMs to Reason via Reinforcement Learning](https://arxiv.org/abs/2506.13705)

* [2506] [EgoVLM] [EgoVLM: Policy Optimization for Egocentric Video Understanding](https://arxiv.org/abs/2506.03097)

* [2506] [RePIC] [RePIC: Reinforced Post-Training for Personalizing Multi-Modal Language Models](http://arxiv.org/abs/2506.18369)

* [2505] [R1-Reward] [R1-Reward: Training Multimodal Reward Model Through Stable Reinforcement Learning](https://arxiv.org/abs/2505.02835)

* [2505] [TW-GRPO] [Reinforcing Video Reasoning with Focused Thinking](https://arxiv.org/abs/2505.24718)

* [2505] [ViGoRL] [Grounded Reinforcement Learning for Visual Reasoning](https://arxiv.org/abs/2505.23678)

* [2505] [GRIT] [GRIT: Teaching MLLMs to Think with Images](https://arxiv.org/abs/2505.15879)

* [2505] [Ground-R1] [Ground-R1: Incentivizing Grounded Visual Reasoning via Reinforcement Learning](https://arxiv.org/abs/2505.20272)

* [2505] [Pixel Reasoner] [Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966)

* [2505] [DeepEyes] [DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning](https://arxiv.org/abs/2505.14362)

* [2505] [CoF] [Chain-of-Focus: Adaptive Visual Search and Zooming for Multimodal Reasoning via RL](https://arxiv.org/abs/2505.15436)

* [2505] [OpenThinkIMG] [OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning](https://arxiv.org/abs/2505.08617)

* [2505] [Active-O3] [Active-O3: Empowering Multimodal Large Language Models with Active Perception via GRPO](https://arxiv.org/abs/2505.21457)

* [2505] [Qwen-LA] [Qwen Look Again: Guiding Vision-Language Reasoning](https://arxiv.org/abs/2505.23558)

* [2505] [VRAG-RL] [VRAG-RL: Empower Vision-Perception-Based RAG for Visually Rich Information Understanding via Iterative Reasoning with Reinforcement Learning](https://arxiv.org/abs/2505.22019)

* [2505] [VAR-GRPO] [Fine-Tuning Next-Scale Visual Autoregressive Models with Group Relative Policy Optimization](https://arxiv.org/abs/2505.23331)

* [2505] [ReasonGen-R1] [ReasonGen-R1: CoT for Autoregressive Image generation models through SFT and RL](https://arxiv.org/abs/2505.24875)

* [2505] [BiCoT-GRPO] [T2I-R1: Reinforcing Image Generation with Collaborative Semantic-level and Token-level CoT](https://arxiv.org/abs/2505.00703)

* [2505] [SelfTok] [Selftok: Discrete Visual Tokens of Autoregression, by Diffusion, and for Reasoning](https://arxiv.org/abs/2505.07538)

* [2505] [CoRL] [Co-Reinforcement Learning for Unified Multimodal Understanding and Generation](https://arxiv.org/abs/2505.17534)

* [2505] [UniRL] [UniRL: Self-Improving Unified Multimodal Models via Supervised and Reinforcement Learning](https://arxiv.org/abs/2505.23380)

* [2505] [TACO] [TACO: Think-Answer Consistency for Optimized Long-Chain Reasoning and Efficient Data Learning via Reinforcement Learning in LVLMs](https://arxiv.org/abs/2505.20777)

* [2505] [Observe-R1] [Observe-R1: Unlocking Reasoning Abilities of MLLMs with Dynamic Progressive Reinforcement Learning](https://arxiv.org/abs/2505.12432)

* [2505] [Visionary-R1] [Visionary-R1: Mitigating Shortcuts in Visual Reasoning with Reinforcement Learning](https://arxiv.org/abs/2505.14677)

* [2505] [SATORI-R1] [SATORI-R1: Incentivizing Multimodal Reasoning with Spatial Grounding and Verifiable Rewards](https://arxiv.org/abs/2505.19094)

* [2505] [DIP-R1] [DIP-R1: Deep Inspection and Perception with RL Looking Through and Understanding Complex Scenes](https://arxiv.org/abs/2505.23179)

* [2505] [V-Triune] [One RL to See Them All: Visual Triple Unified Reinforcement Learning](https://arxiv.org/abs/2505.18129)

* [2505] [Omni-R1] [Omni-R1: Reinforcement Learning for Omnimodal Reasoning via Two-System Collaboration](https://arxiv.org/abs/2505.20256)

* [2505] [Skywork-VL] [Skywork-VL Reward: An Effective Reward Model for Multimodal Understanding and Reasoning](https://arxiv.org/abs/2505.07263)

* [2505] [UnifiedReward-Think] [Unified Multimodal Chain-of-Thought Reward Model through Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.03318)

* [2505] [GoT-R1] [GoT-R1: Unleashing Reasoning Capability of MLLM for Visual Generation with Reinforcement Learning](https://arxiv.org/abs/2505.17022)

* [2505] [MoDoMoDo] [MoDoMoDo: Multi-Domain Data Mixtures for Multimodal LLM Reinforcement Learning](https://arxiv.org/abs/2505.24871)

* [2505] [VisionReasoner] [VisionReasoner: Unified Reasoning-Integrated Visual Perception via Reinforcement Learning](https://arxiv.org/abs/2505.12081)

* [2505] [VisualQuality-R1] [VisualQuality-R1: Reasoning-Induced Image Quality Assessment via Reinforcement Learning to Rank](https://arxiv.org/abs/2505.14460)

* [2505] [EchoInk-R1] [EchoInk-R1: Exploring Audio-Visual Reasoning in Multimodal LLMs via Reinforcement Learning](https://arxiv.org/abs/2505.04623)

* [2505] [VAU-R1] [VAU-R1: Advancing Video Anomaly Understanding via Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.23504)

* [2505] [Jigsaw-R1] [Jigsaw-R1: A Study of Rule-based Visual Reinforcement Learning with Jigsaw Puzzles](http://arxiv.org/abs/2505.23590)

* [2505] [G1] [G1: Bootstrapping Perception and Reasoning Abilities of Vision-Language Model via Reinforcement Learning](http://arxiv.org/abs/2505.13426)

* [2505] [VisTA] [VisualToolAgent (VisTA): A Reinforcement Learning Framework for Visual Tool Selection](https://arxiv.org/abs/2505.20289)

* [2505] [STAR-R1] [STAR-R1: Spatial TrAnsformation Reasoning by Reinforcing Multimodal LLMs](http://arxiv.org/abs/2505.15804)

* [2505] [UniVG-R1] [UniVG-R1: Reasoning Guided Universal Visual Grounding with Reinforcement Learning](https://arxiv.org/abs/2505.14231)

* [2505] [ProxyThinker] [ProxyThinker: Test-Time Guidance through Small Visual Reasoners](https://arxiv.org/abs/2505.24872)

* [2505] [Visual Planning] [Visual Planning: Let's Think Only with Images](https://arxiv.org/abs/2505.11409)

* [2505] [RLRF] [Rendering-Aware Reinforcement Learning for Vector Graphics Generation](https://arxiv.org/abs/2505.20793)

* [2505] [Omni-R1] [Omni-R1: Do You Really Need Audio to Fine-Tune Your Audio LLM?](https://arxiv.org/abs/2505.09439)

* [2504] [VARGPT-v1.1] [VARGPT-v1.1: Improve Visual Autoregressive Large Unified Model via Iterative Instruction Tuning and Reinforcement Learning](https://arxiv.org/abs/2504.02949)

* [2504] [VLM-R1] [VLM-R1: A Stable and Generalizable R1-style Large Vision-Language Model](https://arxiv.org/abs/2504.07615)

* [2504] [Skywork R1V2] [Skywork R1V2: Multimodal Hybrid Reinforcement Learning for Reasoning](https://arxiv.org/abs/2504.16656)

* [2504] [Perception-R1] [Perception-R1: Pioneering Perception Policy with Reinforcement Learning](https://arxiv.org/abs/2504.07954)

* [2504] [TinyLLaVA-Video-R1] [TinyLLaVA-Video-R1: Towards Smaller LMMs for Video Reasoning](https://arxiv.org/abs/2504.09641)

* [2504] [SimpleAR] [SimpleAR: Pushing the Frontier of Autoregressive Visual Generation through Pretraining, SFT, and RL](https://arxiv.org/abs/2504.11455)

* [2504] [SpaceR] [SpaceR: Reinforcing MLLMs in Video Spatial Reasoning](https://arxiv.org/abs/2504.01805)

* [2504] [VideoChat-R1] [VideoChat-R1: Enhancing Spatio-Temporal Perception via Reinforcement Fine-Tuning](https://arxiv.org/abs/2504.06958)

* [2504] [vsGRPO] [Improved Visual-Spatial Reasoning via R1-Zero-Like Training](https://arxiv.org/abs/2504.00883)

* [2504] [Phys-AR] [Reasoning Physical Video Generation with Diffusion Timestep Tokens via Reinforcement Learning](https://arxiv.org/abs/2504.15932)

* [2503] [VisRL] [VisRL: Intention-Driven Visual Perception via Reinforced Reasoning](https://arxiv.org/abs/2503.07523)

* [2503] [Reason-RFT] [Reason-RFT: Reinforcement Fine-Tuning for Visual Reasoning of Vision Language Models](https://arxiv.org/abs/2503.20752)

* [2503] [MetaSpatial] [MetaSpatial: Reinforcing 3D Spatial Reasoning in VLMs for the Metaverse](https://arxiv.org/abs/2503.18470)

* [2503] [R1-Onevision] [R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization](https://arxiv.org/abs/2503.10615)

* [2503] [T-GRPO] [Video-R1: Reinforcing Video Reasoning in MLLMs](https://arxiv.org/abs/2503.21776)

* [2503] [Vision-R1] [Vision-R1: Evolving Human-Free Alignment in Large Vision-Language Models via Vision-Guided Reinforcement Learning](https://arxiv.org/abs/2503.18013)

* [2503] [Visual-RFT] [Visual-RFT: Visual Reinforcement Fine-Tuning](https://arxiv.org/abs/2503.01785)

* [2503] [Time-R1] [Time-R1: Post-Training Large Vision Language Model for Temporal Video Grounding](https://arxiv.org/abs/2503.13377)

* [2503] [UnifiedReward] [Unified Reward Model for Multimodal Understanding and Generation](https://arxiv.org/abs/2503.05236)

* [2503] [SEED-Bench-R1] [Exploring the Effect of Reinforcement Learning on Video Understanding: Insights from SEED-Bench-R1](https://arxiv.org/abs/2503.24376)

* [2503] [MM-Eureka] [MM-Eureka: Exploring the Frontiers of Multimodal Reasoning with Rule-based Reinforcement Learning](https://arxiv.org/abs/2503.07365)

* [2503] [R1-Omni] [R1-Omni: Explainable Omni-Multimodal Emotion Recognition with Reinforcement Learning](https://arxiv.org/abs/2503.05379)

* [2502] [HermesFlow] [HermesFlow: Seamlessly Closing the Gap in Multimodal Understanding and Generation](https://arxiv.org/abs/2502.12148)

* [2501] [PARM] [Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step](https://arxiv.org/abs/2501.13926)

* [2411] [MPO] [Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization](https://arxiv.org/abs/2411.10442)

* [2312] [RLHF-V] [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849)

### Diffusion-based RL

* [2512] [GARDO] [GARDO: Reinforcing Diffusion Models without Reward Hacking](https://arxiv.org/abs/2510.24138)

* [2510] [Identity-GRPO] [Identity-GRPO: Optimizing Multi-Human Identity-preserving Video Generation via Reinforcement Learning](https://arxiv.org/abs/2510.14256)

* [2510] [DGPO] [Reinforcing Diffusion Models by Direct Group Preference Optimization](https://arxiv.org/abs/2510.08425)

* [2510] [Smart-GRPO] [Smart-GRPO: Smartly Sampling Noise for Efficient RL of Flow-Matching Models](https://arxiv.org/abs/2510.02654)

* [2510] [G<sup>2</sup>RPO] [Fine-Grained GRPO for Precise Preference Alignment in Flow Models](https://arxiv.org/abs/2510.01982)

* [2509] [Dynamic-TreeRPO] [Dynamic-TreeRPO: Breaking the Independent Trajectory Bottleneck with Structured Sampling](https://arxiv.org/abs/2509.23352)

* [2509] [BruPA/FluPA] [Follow-Your-Preference: Towards Preference-Aligned Image Inpainting](https://arxiv.org/abs/2509.23082)

* [2509] [DiffusionNFT] [DiffusionNFT: Online Diffusion Reinforcement with Forward Process](https://arxiv.org/abs/2509.16117)

* [2509] [PCPO] [PCPO: Proportionate Credit Policy Optimization for Aligning Image Generation Models](https://arxiv.org/abs/2509.25774)

* [2509] [CPS] [Coefficients-Preserving Sampling for Reinforcement Learning with Flow Matching
](https://arxiv.org/abs/2509.05952)

* [2509] [BranchGRPO] [BranchGRPO: Stable and Efficient GRPO with Structured Branching in Diffusion Models](https://arxiv.org/abs/2509.06040)

* [2508] [Pref-GRPO] [Pref-GRPO: Pairwise Preference Reward-based GRPO for Stable Text-to-Image Reinforcement Learning](https://arxiv.org/abs/2508.20751)

* [2508] [TempFlow-GRPO] [TempFlow-GRPO: When Timing Matters for GRPO in Flow Models](https://arxiv.org/abs/2508.04324)

* [2507] [MixGRPO] [MixGRPO: Unlocking Flow-based GRPO Efficiency with Mixed ODE-SDE](http://arxiv.org/abs/2507.21802)

* [2507] [LLaVA-Reward] [Multimodal LLMs as Customized Reward Models for Text-to-Image Generation](https://arxiv.org/abs/2507.21391)

* [2506] [DreamCS] [DreamCS: Geometry-Aware Text-to-3D Generation with Unpaired 3D Reward Supervision](http://arxiv.org/abs/2506.09814)

* [2506] [RDPO] [RDPO: Real Data Preference Optimization for Physics Consistency Video Generation](https://arxiv.org/abs/2506.18655)

* [2505] [Flow-GRPO] [Flow-GRPO: Training Flow Matching Models via Online RL](https://arxiv.org/abs/2505.05470)

* [2505] [SmPO-Diffusion] [Smoothed Preference Optimization via ReNoise Inversion for Aligning Diffusion Models with Varied Human Preferences](https://arxiv.org/abs/2506.02698)

* [2505] [Diffusion-NPO] [Diffusion-NPO: Negative Preference Optimization for Better Preference Aligned Generation of Diffusion Models](https://arxiv.org/abs/2505.11245)

* [2505] [DanceGRPO] [DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818)

* [2505] [InfLVG] [InfLVG: Reinforce Inference-Time Consistent Long Video Generation with GRPO](https://arxiv.org/abs/2505.17574)

* [2505] [D-Fusion] [D-Fusion: Direct Preference Optimization for Aligning Diffusion Models with Visually Consistent Samples](http://arxiv.org/abs/2505.22002)

* [2505] [RePrompt] [RePrompt: Reasoning-Augmented Reprompting for Text-to-Image Generation via Reinforcement Learning](http://arxiv.org/abs/2505.17540)

* [2505] [Self-Reward] [Self-Rewarding Large Vision-Language Models for Optimizing Prompts in Text-to-Image Generation](http://arxiv.org/abs/2505.16763)

* [2504] [GAPO] [Aligning Anime Video Generation with Human Feedback](https://arxiv.org/abs/2504.10044)

* [2503] [B<sup>2</sup>-DiffuRL] [Towards Better Alignment: Training Diffusion Models with Reinforcement Learning Against Sparse Rewards](http://arxiv.org/abs/2503.11240)

* [2503] [LOOP] [A Simple and Effective Reinforcement Learning Method for Text-to-Image Diffusion Fine-tuning](https://arxiv.org/abs/2503.00897)

* [2503] [InPO] [InPO: Inversion Preference Optimization with Reparametrized DDIM for Efficient Diffusion Model Alignment](http://arxiv.org/abs/2503.18454)

* [2503] [GRADEO] [GRADEO: Towards Human-Like Evaluation for Text-to-Video Generation via Multi-Step Reasoning](http://arxiv.org/abs/2503.02341)

* [2502] [Continuous Time RL] [Score as Action: Fine-Tuning Diffusion Generative Models by Continuous-time Reinforcement Learning](https://arxiv.org/abs/2502.01819)

* [2502] [DreamDPO] [DreamDPO: Aligning Text-to-3D Generation with Human Preferences via Direct Preference Optimization](http://arxiv.org/abs/2502.04370)

* [2502] [CaPO] [Calibrated Multi-Preference Optimization for Aligning Diffusion Models](http://arxiv.org/abs/2502.02588)

* [2501] [Flow-DPO] [Improving Video Generation with Human Feedback](https://arxiv.org/abs/2501.13918)

* [2501] [PPD] [Personalized Preference Fine-tuning of Diffusion Models](http://arxiv.org/abs/2501.06655)

* [2412] [DiffPPO] [DiffPPO: Reinforcement Learning Fine-Tuning of Diffusion Models for Text-to-Image Generation](https://ieeexplore.ieee.org/document/10987802)

* [2412] [VideoDPO] [VideoDPO: Omni-Preference Alignment for Video Diffusion Generation](http://arxiv.org/abs/2412.14167)

* [2412] [MVReward] [MVReward: Better Aligning and Evaluating Multi-View Diffusion Models with Human Preferences](https://arxiv.org/abs/2412.06614)

* [2412] [TPDM] [Schedule On the Fly: Diffusion Time Prediction for Faster and Better Image Generation](http://arxiv.org/abs/2412.01243)

* [2410] [SSPO] [Bridging SFT and DPO for Diffusion Model Alignment with Self-Sampling Preference Optimization](https://arxiv.org/abs/2410.05255)

* [2410] [PrefPaint] [PrefPaint: Aligning Image Inpainting Diffusion Model with Human Preference](http://arxiv.org/abs/2410.21966)

* [2409] [VideoRM] [Boosting Text-to-Video Generative Model with MLLMs Feedback](https://openreview.net/forum?id=3ivnixHy16)

* [2407] [RPO] [Subject-driven Text-to-Image Generation via Preference-based Reinforcement Learning](https://arxiv.org/abs/2407.12164)

* [2407] [DPG] [Powerful and Flexible: Personalized Text-to-Image Generation via Reinforcement Learning](https://arxiv.org/abs/2407.06642)

* [2406] [Diversity Reward] [Training Diffusion Models Towards Diverse Image Generation with Reinforcement Learning](https://ieeexplore.ieee.org/document/10656815)

* [2406] [VideoScore] [VideoScore: Building Automatic Metrics to Simulate Fine-grained Human Feedback for Video Generation](http://arxiv.org/abs/2406.15252)

* [2406] [Diffusion-RPO] [Diffusion-RPO: Aligning Diffusion Models through Relative Preference Optimization](http://arxiv.org/abs/2406.06382)

* [2406] [SPO] [Aesthetic Post-Training Diffusion Models from Generic Preferences with Step-by-step Preference Optimization](http://arxiv.org/abs/2406.04314)

* [2405] [Curriculum DPO] [Curriculum Direct Preference Optimization for Diffusion and Consistency Models](http://arxiv.org/abs/2405.13637)

* [2405] [DNO] [Inference-Time Alignment of Diffusion Models with Direct Noise Optimization](https://arxiv.org/abs/2405.18881)

* [2404] [RLCM] [RL for Consistency Models: Faster Reward Guided Text-to-Image Generation](https://arxiv.org/abs/2404.03673)

* [2404] [Diffusion-KTO] [Aligning Diffusion Models by Optimizing Human Utility](http://arxiv.org/abs/2404.04465)

* [2404] [PAE] [Dynamic Prompt Optimizing for Text-to-Image Generation](http://arxiv.org/abs/2404.04095)

* [2403] [DreamReward] [DreamReward: Text-to-3D Generation with Human Preference](http://arxiv.org/abs/2403.14613)

* [2402] [TDPO-R] [Confronting Reward Overoptimization for Diffusion Models: A Perspective of Inductive and Primacy Biases](http://arxiv.org/abs/2402.08552)

* [2402] [DenseReward] [A Dense Reward View on Aligning Text-to-Image Diffusion with Preference](http://arxiv.org/abs/2402.08265)

* [2401] [Parrot] [Parrot: Pareto-optimal Multi-Reward Reinforcement Learning Framework for Text-to-Image Generation](http://arxiv.org/abs/2401.05675)

* [2312] [InstructVideo] [InstructVideo: Instructing Video Diffusion Models with Human Feedback](http://arxiv.org/abs/2312.12490)

* [2311] [D3PO] [Using Human Feedback to Fine-tune Diffusion Models without Any Reward Model](https://arxiv.org/abs/2311.13231)

* [2311] [Diffusion-DPO] [Diffusion Model Alignment Using Direct Preference Optimization](http://arxiv.org/abs/2311.12908)

* [2311] [TextForce] [Enhancing Diffusion Models with Text-Encoder Reinforcement Learning](http://arxiv.org/abs/2311.15657)

* [2309] [DRaFT] [Directly Fine-Tuning Diffusion Models on Differentiable Rewards](http://arxiv.org/abs/2309.17400)

* [2305] [DDPO] [Training Diffusion Models with Reinforcement Learning](https://arxiv.org/abs/2305.13301)

* [2305] [DPOK] [DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models](https://arxiv.org/abs/2305.16381)

* [2304] [ImageReward] [ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation](http://arxiv.org/abs/2304.05977)

* [2304] [RAFT] [RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment](http://arxiv.org/abs/2304.06767)

* [2302] [Reward-weighted Method] [Aligning Text-to-Image Models using Human Feedback](https://arxiv.org/abs/2302.12192)

* [2212] [Promptist] [Optimizing Prompts for Text-to-Image Generation](http://arxiv.org/abs/2212.09611)
