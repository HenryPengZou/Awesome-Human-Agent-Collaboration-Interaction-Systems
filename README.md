# 🚀 Awesome-LLM-Based-Human-Agent-Systems
[![Paper](https://img.shields.io/badge/Paper-Human_Agent_Systems-white.svg)](https://openreview.net/pdf?id=OUsZtCgYxy) 
[![arXiv](https://img.shields.io/badge/arXiv-Human_Agent_Systems-b31b1b.svg)](https://openreview.net/forum?id=OUsZtCgYxy) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)]()

<p align="center">
    <img src="https://i.imgur.com/waxVImv.png" alt="Oryx Video-ChatGPT">
</p>


![image](./images/overview_llm_has.jpg)


A Survey on Large Language Model based Human-Agent Systems

⭐ Star and stay tuned! :> Our survey paper will be publicly available on ArXiv within the next three days, and comprehensive paper lists and resources will be added here very soon.

😊 Feel free to let us know if you want all paper lists and resources even earlier~ 



<!-- omit in toc -->
## 🔥 News
- **2025.04**: 🎉🎉🎉 We have published a survey paper titled "[A Survey on Large Language Model based Human-Agent Systems](https://openreview.net/forum?id=OUsZtCgYxy)". Please feel free to cite or open requests for your awesome studies.



## 🌟 Introduction

Welcome to the repository associated with our survey paper, "A Survey on Large Language Model based Human-Agent Systems". This repository contains **resources and updates** related to our ongoing Human-Agent-System research. For a detailed introduction, please refer to [our survey paper](https://openreview.net/pdf?id=OUsZtCgYxy).


<div id="contents"></div>

<!-- omit in toc -->
## 📄 Contents

- [🚀 Awesome-LLM-Based-Human-Agent-Systems](#-awesome-llm-based-human-agent-systems)
  - [🌟 Introduction](#-introduction)
  - [🤝 Human Feedback](#-human-feedback)
  - [🔄 Interaction](#-interaction)
  - [🎛️ Orchestration](#️-orchestration)
  - [💬 Communication](#-communication)
  - [📚 Applications, Datasets \& Benchmarks](#-applications-datasets--benchmarks)
  - [📌 Contributing](#-contributing)
  - [📝 Citation](#-citation)



![image](./images/taxonomy.png)


## 🤝 Human Feedback
 ([©️click here back to table of contents👆🏻](#contents))
| Title | Date | Code | Feedback Type | Feedback Subtype | Feedback Granularity | Feedback Phase |
| ---  | :---: | :---: | :---: | :---: | :---: | :---: |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration (Co-Gym)](https://arxiv.org/abs/2412.15701) | 2025/01 | [Link](https://github.com/SALT-NLP/collaborative-gym) | Corrective | Refinement | Segment | During Task |
| [Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811) | 2024/09 | -- | Corrective | Refinement | Segment | During Task |
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | 2025/03 | -- | Guidance | Demonstration | Segment | During Task |
| [Experimental Exploration: Investigating Cooperative Interaction Behavior Between Humans and Large Language Model Agents](https://arxiv.org/abs/2503.07320) | 2025/03 | -- | Implicit | User Action | Segment | During Task |
| [InteractGen: Enhancing Human-Involved Embodied Task Reasoning through LLM-Based Multi-Agent Collaboration](https://openreview.net/forum?id=WDdiCIkpxC) | 2024/12 | -- | Guidance | Demonstration | Segment | During Task |
| [Ai chains: Transparent and controllable human-ai interaction by chaining large language model prompts](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | 2022/04 | -- | Corrective | Refinement | Segment | During Task |
| [Drive As You Speak: Enabling Human-Like Interaction With Large Language Models in Autonomous Vehicles](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/html/Cui_Drive_As_You_Speak_Enabling_Human-Like_Interaction_With_Large_Language_WACVW_2024_paper.html) | 2024 | -- | Guidance | Demonstration | Segment | During Task |
| [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943) | 2024/04 | [Link](https://github.com/AgentCoord/AgentCoord) | Guidance, Corrective | Demonstration, Refinement | Segment | Initial Setup |
| [CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation](https://arxiv.org/abs/2501.16609) | 2025/04 | [Link](https://oaishi.github.io/cowpilot.html) | Corrective, Implicit | User Action, Refinement | Segment | During Task |
| [A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples](https://arxiv.org/abs/2404.15974) | 2024/04 | -- | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
| [LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination](https://arxiv.org/abs/2312.15224) | 2024/01 | -- | Guidance, Corrective | Demonstration, Refinement | Segment | During Task |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | 2025/03 | [Link](https://github.com/facebookresearch/sweet_rl) | Corrective, Implicit | Refinement, User Action | Segment | During Task |
| [An LLM-based approach for enabling seamless Human-Robot collaboration in assembly](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | 2024/04 | -- | Guidance | Demonstration | Segment | During Task |
| [REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents using Information Relevance and Relative Proximity](https://arxiv.org/abs/2405.16751) | 2024/05 | -- | Implicit | Human Control | Segment | During Task |
| [AssistantX: An LLM-Powered Proactive Assistant in Collaborative Human-Populated Environment](https://arxiv.org/abs/2409.17655) | 2024/09 | [Link](https://github.com/AssistantX-Agent/AssistantX) | Implicit | Human Control | Holistic | Initial Setup |
| [MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback](https://arxiv.org/pdf/2309.10691) | 2023/09 | [Link](https://xwang.dev/mint-bench/) | Evaluative | Binary Assessment | Holistic | During Task |
| [Improving grounded language understanding in a collaborative environment by interacting with agents through help feedback](https://arxiv.org/abs/2304.10750) | 2023/04 | -- | Corrective, Guidance | Demonstration, Refinement | Holistic | During Task |
| [ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments](https://arxiv.org/abs/2502.19852) | 2025/02 | [Link](https://github.com/stovecat/convcodeworld) | Guidance | Demonstration, Critique | Segment | During Task |
| [Large Language Model-based Human-Agent Collaboration for Complex Task Solving](https://arxiv.org/abs/2402.12914) | 2024/02 | [Link](https://github.com/XueyangFeng/ReHAC) | Implicit | Human Control | Segment | During Task |
| [Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration](https://arxiv.org/abs/2502.11882) | 2025/02 | [Link](https://github.com/sjtu-marl/DPT-Agent) | Guidance | Critique | Holistic | During Task |
| [LLM-Based Human-Robot Collaboration Framework for Manipulation Tasks](https://arxiv.org/abs/2308.14972) | 2023/08 | -- | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
| [Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration](https://ieeexplore.ieee.org/abstract/document/10561501?casa_token=3M-aX2BcpxEAAAAA:htR-WI2hy2l-xS53-YUHqxQEOb_4g27UEkdPG_lzwzMyON275DFryPfW_ttPhMyQqbFrRziTyg) | 2024 | -- | Corrective | Refinement | Holistic | During Task |
| [PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks](https://openreview.net/forum?id=T5QLRRHyL1) | 2025/01 | [Link](https://github.com/facebookresearch/partnr-planner/tree/main/) | Corrective, Guidance | Refinement, Critique | Holistic, Segment | During Task, Post Task |
| [Embodied LLM Agents Learn to Cooperate in Organized Teams](https://arxiv.org/abs/2403.12482) | 2024/03 | [Link](https://github.com/tobeatraceur/Organized-LLM-Agents) | Guidance | Critique | Holistic | During Task |
| [Building cooperative embodied agents modularly with large language models](https://arxiv.org/abs/2307.02485)) | 2023/07 | -- | Evaluative | Scaler Rating | Holistic | Post Task |
| [Investigating Agency of LLMs in Human-AI Collaboration Tasks](https://arxiv.org/abs/2305.12815) | 2023/05 | [Link](https://github.com/microsoft/agency-dialogue) | Guidance | Demonstration, Critique | Segment | During Task |
| [Human-LLM collaboration in generative design for customization](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | 2025 | -- | Guidance, Evaluative | Demonstration, Binary Assessment, Preference Ranking | Holistic, Segment | Initial Setup, Post Task |
| [PDFChatAnnotator: A Human-LLM Collaborative Multi-Modal Data Annotation Tool for PDF-Format Catalogs](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | 2024 | -- | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
| [To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions](https://ieeexplore.ieee.org/abstract/document/10801517) | 2024 | [Link](https://github.com/HRI-EU/AttentiveSupport) | Implicit, Guidance | Demonstration, User Action | Holistic | Initial Setup, During Task |
| [Improved Trust in Human-Robot Collaboration With ChatGPT](https://ieeexplore.ieee.org/abstract/document/10141597) | 2023 | -- | Guidance | Demonstration, Critique | Segment | During Task |
| [Challenges in Human-Agent Communication](https://arxiv.org/abs/2412.10380) | 2024 | -- | Guidance | Demonstration, Critique | Holistic, Segment | Initial Setup, During Task, Post Task |
| [Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension](https://arxiv.org/abs/2412.05958) | 2024/12 | [Link](https://github.com/BESSER-PEARL/agentic-bpmn) | Guidance | Demonstration | Holistic | Initial Setup, During Task, Post Task |
| [Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations](https://arxiv.org/abs/2408.15232) | 2024/08 | [Link](https://github.com/stanford-oval/storm) | Guidance | Demonstration | Segment | During Task |
| [Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://arxiv.org/abs/2406.01915) | 2024/06 | -- | Corrective, Guidance | Demonstration, Refinement, Critique | Segment | Initial Setup, During Task |
| [A2C: A Modular Multi-stage Collaborative Decision Framework for Human-AI Teams](https://arxiv.org/abs/2401.14432) | 24/01 | [Link](https://anonymous.4open.science/r/A2C/README.md) | Guidance, Implicit, Corrective, Evaluative | Refinement, Binary Assessment, Critique, Human Control | Holistic, Segment | During Task |
| [MindAgent: Emergent Gaming Interaction](https://arxiv.org/abs/2309.09971) | 23/09 | [Link](https://github.com/mindagent/mindagent) | Corrective | Refinement | Segment | During Task |
| [Ask-before-Plan: Proactive Language Agents for Real-World Planning](https://arxiv.org/abs/2401.14432) | 24/01 | [Link](https://github.com/magicgh/Ask-before-Plan) | Guidance | Demonstration, Critique | Segment | During Task |
| [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667) | 23/10 | -- | Evaluative, Implicit | Scaler Rating, User Action | Holistic, Segment | During Task, Post Task |
| [PaLM-E: An Embodied Multimodal Language Model](https://openreview.net/forum?id=VTpHpqM3Cf&utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=284568789&_hsenc=p2ANqtz-9lsSL4nXMrOGBQqGoqktY5Yno_r9-nTOARZinDcgihFNqcOFEQb_MVtHKdpgI2AC3N8SrNW5PxcD0uxl4WeKcPJgUOgw) | 2023/04 | [Link](https://palm-e.github.io) | Guidance, Implicit | Demonstration, User Action | Segment | During Task |
| [Embodied Task Planning with Large Language Models](https://arxiv.org/abs/2307.01848) | 2023/07 | [Link](https://github.com/Gary3410/TaPA) | Guidance, Evaluative | Demonstration, Binary Assessment | Holistic, Segment | Initial Setup, Post Task |
| [MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) | 2023/08 | [Link](https://github.com/geekan/MetaGPT) | Evaluative, Guidance | Binary Assessment | Holistic | Initial Setup, Post Task |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://proceedings.neurips.cc/paper_files/paper/2024/hash/1704ddd0bb89f159dfe609b32c889995-Abstract-Conference.html) | 2024 | [Link](https://github.com/DigiRL-agent/digirl) | Evaluative | Binary Assessment | Holistic | During Task, Post Task |
| [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) | 2024/02 | [Link](https://github.com/McGill-NLP/WebLINX) | Guidance | Demonstration | Holistic, Segment | During Task |
| [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) | 2024/04 | [Link](https://github.com/Berkeley-NLP/Agent-Eval-Refine) | Evaluative | Binary Assessment | Holistic | Post Task |
| [WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/pdf/2406.12373) | 2024/06 | [Link](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live) | Evaluative | Scaler Rating | Holistic | Post Task |
| [MineWorld: a Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) | 2025/04| [Link](https://github.com/microsoft/MineWorld) | Evaluative | Scaler Rating | Holistic | Post Task |




## 🔄 Interaction
 ([©️click here back to table of contents👆🏻](#contents))
| Title | Date | Code | Interaction Types | Interaction Variant
| ---   | :---: | :---: | :---: | :---: |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration](https://arxiv.org/abs/2309.13007) | 2024/12 | [Link](https://github.com/SALT-NLP/collaborative-gym) | Collaboration | Supervision, Delegation
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | 2025/03 | - | Collaboration | Delegation


## 🎛️ Orchestration
 ([©️click here back to table of contents👆🏻](#contents))
| Title | Date | Code | Orchestration Strategy | Orchestration Synchronization 
| ---  | :---: | :---: | :---: | :---: |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration](https://arxiv.org/abs/2309.13007) | 2024/12 | [Link](https://github.com/SALT-NLP/collaborative-gym) | One-by-One | Asynchronous
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | 2025/03 | - | One-by-One | Asynchronous



## 💬 Communication
 ([©️click here back to table of contents👆🏻](#contents))
| Title | Date | Code | Communication Structure | Communication Mode 
| ---  | :---: | :---: | :---: | :---: |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration](https://arxiv.org/abs/2309.13007) | 2024/12 | [Link](https://github.com/SALT-NLP/collaborative-gym) | Decentralized | Conversation
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | 2025/03 | - | Hierarchical | Conversation


## 📚 Applications, Datasets & Benchmarks
 ([©️click here back to table of contents👆🏻](#contents))
| Domain | Datasets & Benchmarks | Proposed or Used by | Data Link |
| ---  | :---: | :---: | :---: |
Embodied AI | TaPA | TaPA ([Wu et al., 2023](https://arxiv.org/abs/2307.01848)) | [Link](https://github.com/Gary3410/TaPA) |
Embodied AI | EmboInteract|  InteractGen ([Sun et al., 2024b](https://openreview.net/forum?id=WDdiCIkpxC)) | -



<!-- ## 🔗 Other Resources   -->


## 📌 Contributing  

Contributions are welcome! If you have relevant papers, code, or insights, feel free to submit a request.  



## 📝 Citation

If you find our survey helpful, please consider citing our work:

```

@article{hassurvey2025,
  title={A Survey on Large Language Model based Human-Agent Systems},
  author={Henry Peng Zou, Wei-Chieh Huang, Yaozu Wu, Yankai Chen, Chunyu Miao, Hoang H Nguyen, Yue Zhou, Weizhi Zhang, Renhe Jiang Liancheng Fang, Langzhou He, Yangning Li, Yuwei Cao, Dongyuan Li, Philip S. Yu},
  year={2025}
}

```



<!-- omit in toc -->
## ⭐ Star History

<a href="https://www.star-history.com/#HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&type=Date" />
 </picture>
</a>
