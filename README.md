# Awesome LLM-Based Human-Agent Systems
[![Code](https://img.shields.io/badge/Code-GithubRepo-c8a4bf.svg)](https://github.com/HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers) 
[![Paper](https://img.shields.io/badge/Paper-Human_Agent_Systems-white.svg)](https://arxiv.org/pdf/2505.00753)
[![arXiv](https://img.shields.io/badge/arXiv-Human_Agent_Systems-b31b1b.svg)](https://arxiv.org/abs/2505.00753)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-blue)]()



<p align="center">
    <img src="https://i.imgur.com/waxVImv.png" alt="Oryx Video-ChatGPT">
</p>


![image](./images/overview_llm_has.jpg)

Feel free to ⭐ and fork [this repository](https://github.com/HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers) to follow the latest updates. Let us know if you have any suggestions, recommended papers and resources! We’ll keep adding new papers and resources here.




## 🌟 Introduction

LLM-based Human-Agent Systems (LLM-HAS) are interactive frameworks where humans actively provide additional information, feedback, or control during interaction with LLM-powered agents to enhance system performance, reliability, and safety. For a detailed introduction, please refer to [our survey paper](https://arxiv.org/abs/2505.00753). Our goal with this project is to build an exhaustive collection of awesome resources relevant to LLM-HAS encompassing papers, repositories, and more

<div id="contents"></div>

<!-- omit in toc -->
## 📄 Contents

- [Awesome LLM-Based Human-Agent Systems](#awesome-llm-based-human-agent-systems)
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

| Title | Date & Code | Feedback Type | Feedback Subtype | Feedback Granularity | Feedback Phase |
| --- | :---: | :---: | :---: | :---: | :---: |
[MineWorld: a Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) | [2025/04](https://github.com/microsoft/MineWorld) [![GitHub stars](https://img.shields.io/github/stars/microsoft/MineWorld?style=social)](https://github.com/microsoft/MineWorld) | Evaluative | Scaler Rating | Holistic | Post Task |
[Experimental Exploration: Investigating Cooperative Interaction Behavior Between Humans and Large Language Model Agents](https://arxiv.org/abs/2503.07320) | [2025/03](https://arxiv.org/abs/2503.07320) | Implicit | User Action | Segment | During Task |
[SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | [2025/03](https://github.com/facebookresearch/sweet_rl) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social)](https://github.com/facebookresearch/sweet_rl) | Corrective, Implicit | Refinement, User Action | Segment | During Task |
[FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | [2025/03](https://huggingface.co/datasets/Illogicaler/FinArena-low-cost-dataset) | Guidance | Demonstration | Segment | During Task |
| [Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration](https://arxiv.org/abs/2502.11882) | [2025/02](https://github.com/sjtu-marl/DPT-Agent) [![GitHub stars](https://img.shields.io/github/stars/sjtu-marl/DPT-Agent?style=social)](https://github.com/sjtu-marl/DPT-Agent) | Guidance | Critique | Holistic | During Task
| [ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments](https://arxiv.org/abs/2502.19852) | [2025/02](https://github.com/stovecat/convcodeworld) [![GitHub stars](https://img.shields.io/github/stars/stovecat/convcodeworld?style=social)](https://github.com/stovecat/convcodeworld) | Guidance  | Demonstration, Critique | Segment | During Task
[CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation](https://arxiv.org/abs/2501.16609) | [2025/01](https://oaishi.github.io/cowpilot.html) | Corrective, Implicit | User Action, Refinement | Segment | During Task |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration (Co-Gym)](https://arxiv.org/abs/2412.15701) | [2024/12](https://github.com/SALT-NLP/collaborative-gym) [![GitHub stars](https://img.shields.io/github/stars/SALT-NLP/collaborative-gym?style=social)](https://github.com/SALT-NLP/collaborative-gym) | Corrective | Refinement | Segment | During Task |
[Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension](https://arxiv.org/abs/2412.05958) | [2024/12](https://github.com/BESSER-PEARL/agentic-bpmn) [![GitHub stars](https://img.shields.io/github/stars/BESSER-PEARL/agentic-bpmn?style=social)](https://github.com/BESSER-PEARL/agentic-bpmn) | Guidance | Demonstration | Holistic | Initial Setup, During Task, Post Task |
| [To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions](https://ieeexplore.ieee.org/abstract/document/10801517) | [2024/10](https://github.com/HRI-EU/AttentiveSupport) [![GitHub stars](https://img.shields.io/github/stars/HRI-EU/AttentiveSupport?style=social)](https://github.com/HRI-EU/AttentiveSupport) | Implicit, Guidance | Demonstration, User Action | Holistic | Initial Setup, During Task
[PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks](https://openreview.net/forum?id=T5QLRRHyL1) | [2024/10](https://github.com/facebookresearch/partnr-planner/tree/main/) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/partnr-planner?style=social)](https://github.com/facebookresearch/partnr-planner/tree/main/) | Corrective, Guidance | Refinement, Critique | Holistic, Segment | During Task, Post Task |
[AssistantX: An LLM-Powered Proactive Assistant in Collaborative Human-Populated Environment](https://arxiv.org/abs/2409.17655) | [2024/09](https://github.com/AssistantX-Agent/AssistantX) [![GitHub stars](https://img.shields.io/github/stars/AssistantX-Agent/AssistantX?style=social)](https://github.com/AssistantX-Agent/AssistantX) | Implicit | Human Control | Holistic | Initial Setup |
[Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811) | [2024/09](https://arxiv.org/abs/2409.08811) | Corrective | Refinement | Segment | During Task |
[Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations](https://arxiv.org/abs/2408.15232) | [2024/08](https://github.com/stanford-oval/storm) [![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)](https://github.com/stanford-oval/storm) | Guidance | Demonstration | Segment | During Task |
[Human-LLM collaboration in generative design for customization](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | [2024/07](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | Guidance, Evaluative | Demonstration, Binary Assessment, Preference Ranking | Holistic, Segment | Initial Setup, Post Task |
[WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/pdf/2406.12373) | [2024/06](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live) | Evaluative | Scaler Rating | Holistic | Post Task |
[Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://arxiv.org/abs/2406.01915) | [2024/06](https://arxiv.org/abs/2406.01915) | Corrective, Guidance | Demonstration, Refinement, Critique | Segment | Initial Setup, During Task |
| [Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration](https://ieeexplore.ieee.org/abstract/document/10561501) | [2024/06](https://ieeexplore.ieee.org/abstract/document/10561501) | Corrective | Refinement | Holistic | During Task
[DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896) | [2024/06](https://github.com/DigiRL-agent/digirl) [![GitHub stars](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social)](https://github.com/DigiRL-agent/digirl) | Evaluative | Binary Assessment | Holistic | During Task, Post Task |
[REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents using Information Relevance and Relative Proximity](https://arxiv.org/abs/2405.16751) | [2024/05](https://arxiv.org/abs/2405.16751) | Implicit | Human Control | Segment | During Task |
[Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) | [2024/04](https://github.com/Berkeley-NLP/Agent-Eval-Refine) [![GitHub stars](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine?style=social)](https://github.com/Berkeley-NLP/Agent-Eval-Refine) | Evaluative | Binary Assessment | Holistic | Post Task |
[A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples](https://arxiv.org/abs/2404.15974) | [2024/04](https://arxiv.org/abs/2404.15974) | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
| [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943) | [2024/04](https://github.com/AgentCoord/AgentCoord) [![GitHub stars](https://img.shields.io/github/stars/AgentCoord/AgentCoord?style=social)](https://github.com/AgentCoord/AgentCoord) | Guidance, Corrective | Demonstration, Refinement | Segment | Initial Setup |
[PDFChatAnnotator: A Human-LLM Collaborative Multi-Modal Data Annotation Tool for PDF-Format Catalogs](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | [2024/04](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
| [Embodied LLM Agents Learn to Cooperate in Organized Teams](https://arxiv.org/abs/2403.12482) | [2024/03](https://github.com/tobeatraceur/Organized-LLM-Agents) [![GitHub stars](https://img.shields.io/github/stars/tobeatraceur/Organized-LLM-Agents?style=social)](https://github.com/tobeatraceur/Organized-LLM-Agents) | Guidance  | Critique | Holistic | 
| [Large Language Model-based Human-Agent Collaboration for Complex Task Solving](https://arxiv.org/abs/2402.12914) | [2024/02](https://github.com/XueyangFeng/ReHAC) [![GitHub stars](https://img.shields.io/github/stars/XueyangFeng/ReHAC?style=social)](https://github.com/XueyangFeng/ReHAC) | Implicit  | Human Control  | Segment | During Task
| [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) | [2024/02](https://github.com/McGill-NLP/WebLINX) [![GitHub stars](https://img.shields.io/github/stars/McGill-NLP/WebLINX?style=social)](https://github.com/McGill-NLP/WebLINX) | Guidance  | Demonstration | Holistic, Segment | During Task
[Ask-before-Plan: Proactive Language Agents for Real-World Planning](https://arxiv.org/abs/2401.14432) | [2024/01](https://github.com/magicgh/Ask-before-Plan) [![GitHub stars](https://img.shields.io/github/stars/magicgh/Ask-before-Plan?style=social)](https://github.com/magicgh/Ask-before-Plan) | Guidance | Demonstration, Critique | Segment | During Task | During Task
[A2C: A Modular Multi-stage Collaborative Decision Framework for Human-AI Teams](https://arxiv.org/abs/2401.14432) | [2024/01](https://anonymous.4open.science/r/A2C/README.md) | Guidance, Implicit, Corrective, Evaluative | Refinement, Binary Assessment, Critique, Human Control | Holistic, Segment | During Task |
| [LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination](https://arxiv.org/abs/2312.15224) | [2023/12](https://github.com/HosnLS/Hierarchical-Language-Agent) [![GitHub stars](https://img.shields.io/github/stars/HosnLS/Hierarchical-Language-Agent?style=social)](https://github.com/HosnLS/Hierarchical-Language-Agent) | Guidance, Corrective | Demonstration, Refinement | Segment | During Task |
[SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667) | [2023/10](https://arxiv.org/abs/2310.11667) | Evaluative, Implicit | Scaler Rating, User Action | Holistic, Segment | During Task, Post Task |
[MindAgent: Emergent Gaming Interaction](https://arxiv.org/abs/2309.09971) | [2023/09](https://github.com/mindagent/mindagent) [![GitHub stars](https://img.shields.io/github/stars/mindagent/mindagent?style=social)](https://github.com/mindagent/mindagent) | Corrective | Refinement | Segment | During Task |
[Drive As You Speak: Enabling Human-Like Interaction With Large Language Models in Autonomous Vehicles](https://arxiv.org/abs/2309.10228) | [2023/09](https://arxiv.org/abs/2309.10228) | Guidance | Demonstration | Segment | During Task |
| [MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback](https://arxiv.org/pdf/2309.10691) | [2023/09](https://xwang.dev/mint-bench/) | Evaluative | Binary Assessment | Holistic ｜ During Task ｜
[MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) | [2023/08](https://github.com/geekan/MetaGPT) [![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)](https://github.com/geekan/MetaGPT) | Evaluative, Guidance | Binary Assessment | Holistic | Initial Setup, Post Task |
[LLM-Based Human-Robot Collaboration Framework for Manipulation Tasks](https://arxiv.org/abs/2308.14972) | [2023/08](https://arxiv.org/abs/2308.14972) | Corrective, Guidance | Demonstration, Refinement | Segment | During Task |
[Embodied Task Planning with Large Language Models](https://arxiv.org/abs/2307.01848) | [2023/07](https://github.com/Gary3410/TaPA) [![GitHub stars](https://img.shields.io/github/stars/Gary3410/TaPA?style=social)](https://github.com/Gary3410/TaPA) | Guidance, Evaluative | Demonstration, Binary Assessment | Holistic, Segment | Initial Setup, Post Task |
[Building cooperative embodied agents modularly with large language models](https://arxiv.org/abs/2307.02485) | [2023/07](https://arxiv.org/abs/2307.02485) | Evaluative | Scaler Rating | Holistic | Post Task |
[Improved Trust in Human-Robot Collaboration With ChatGPT](https://ieeexplore.ieee.org/abstract/document/10141597) | [2023/06](https://ieeexplore.ieee.org/abstract/document/10141597) | Guidance | Demonstration, Critique | Segment | During Task |
[Investigating Agency of LLMs in Human-AI Collaboration Tasks](https://arxiv.org/abs/2305.12815) | [2023/05](https://arxiv.org/abs/2305.12815) | Guidance | Demonstration, Critique | Segment | During Task |
[Improving grounded language understanding in a collaborative environment by interacting with agents through help feedback](https://arxiv.org/abs/2304.10750) | [2023/04](https://arxiv.org/abs/2304.10750) | Corrective, Guidance | Demonstration, Refinement | Holistic | During Task |
[PaLM-E: An Embodied Multimodal Language Model](https://openreview.net/forum?id=VTpHpqM3Cf&utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=284568789&_hsenc=p2ANqtz-9lsSL4nXMrOGBQqGoqktY5Yno_r9-nTOARZinDcgihFNqcOFEQb_MVtHKdpgI2AC3N8SrNW5PxcD0uxl4WeKcPJgUOgw) | [2023/03](https://palm-e.github.io) | Guidance, Implicit | Demonstration, User Action | Segment | During Task |
[Ai chains: Transparent and controllable human-ai interaction by chaining large language model prompts](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | [2021/10](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | Corrective | Refinement | Segment | During Task |



## 🔄 Interaction
 ([©️click here back to table of contents👆🏻](#contents))


| Title | Date & Code | Interaction Types | Interaction Variant |
| --- | :---: | :---: | :---: |
| [MineWorld: A Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) | [2025/04](https://github.com/microsoft/MineWorld) [![GitHub stars](https://img.shields.io/github/stars/microsoft/MineWorld?style=social)](https://github.com/microsoft/MineWorld) | Collaboration | Delegation |
| [Experimental Exploration: Investigating Cooperative Interaction Behavior Between Humans and Large Language Model Agents](https://arxiv.org/abs/2503.07320) | [2025/03](https://arxiv.org/abs/2503.07320) | Coopetition | - |
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | [2025/03](https://huggingface.co/datasets/Illogicaler/FinArena-low-cost-dataset) | Collaboration | Delegation |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | [2025/03](https://github.com/facebookresearch/sweet_rl) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social)](https://github.com/facebookresearch/sweet_rl) | Collaboration | Delegation |
| [ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments](https://arxiv.org/abs/2502.19852) | [2025/02](https://github.com/stovecat/convcodeworld) [![GitHub stars](https://img.shields.io/github/stars/stovecat/convcodeworld?style=social)](https://github.com/stovecat/convcodeworld) | Collaboration | Supervision, Delegation |
| [Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration](https://arxiv.org/abs/2502.11882) | [2025/02](https://github.com/sjtu-marl/DPT-Agent) [![GitHub stars](https://img.shields.io/github/stars/sjtu-marl/DPT-Agent?style=social)](https://github.com/sjtu-marl/DPT-Agent) | Collaboration | - |
| [CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation](https://arxiv.org/abs/2501.16609) | [2025/01](https://oaishi.github.io/cowpilot.html) | Collaboration | Supervision, Delegation, Coordination |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration (Co-Gym)](https://arxiv.org/abs/2412.15701) | [2024/12](https://github.com/SALT-NLP/collaborative-gym) [![GitHub stars](https://img.shields.io/github/stars/SALT-NLP/collaborative-gym?style=social)](https://github.com/SALT-NLP/collaborative-gym) | Collaboration | Supervision, Delegation |
| [Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension](https://arxiv.org/abs/2412.05958) | [2024/12](https://github.com/BESSER-PEARL/agentic-bpmn) [![GitHub stars](https://img.shields.io/github/stars/BESSER-PEARL/agentic-bpmn?style=social)](https://github.com/BESSER-PEARL/agentic-bpmn) | Collaboration | Coordination |
| [To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions](https://ieeexplore.ieee.org/abstract/document/10801517) | [2024/10](https://github.com/HRI-EU/AttentiveSupport) [![GitHub stars](https://img.shields.io/github/stars/HRI-EU/AttentiveSupport?style=social)](https://github.com/HRI-EU/AttentiveSupport) | Collaboration | Coordination |
| [PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-Agent Tasks](https://openreview.net/forum?id=T5QLRRHyL1) | [2024/10](https://github.com/facebookresearch/partnr-planner/tree/main/) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/partnr-planner?style=social)](https://github.com/facebookresearch/partnr-planner/tree/main/) | Collaboration | Coordination, Cooperation |
| [AssistantX: An  Proactive Assistant in Collaborative Human-Populated Environment](https://arxiv.org/abs/2409.17655) | [2024/09](https://github.com/AssistantX-Agent/AssistantX) [![GitHub stars](https://img.shields.io/github/stars/AssistantX-Agent/AssistantX?style=social)](https://github.com/AssistantX-Agent/AssistantX) | Collaboration | Delegation |
| [Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811) | [2024/09](https://arxiv.org/abs/2409.08811) | Collaboration | Coordination |
| [Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations](https://arxiv.org/abs/2408.15232) | [2024/08](https://github.com/stanford-oval/storm) [![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)](https://github.com/stanford-oval/storm) | Collaboration | Delegation |
| [Human-LLM Collaboration in Generative Design for Customization](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | [2024/07](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | Collaboration | Delegation |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896) | [2024/06](https://github.com/DigiRL-agent/digirl) [![GitHub stars](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social)](https://github.com/DigiRL-agent/digirl) | Collaboration | Delegation |
| [Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://arxiv.org/abs/2406.01915) | [2024/06](https://arxiv.org/abs/2406.01915) | Collaboration | Delegation |
| [Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration](https://ieeexplore.ieee.org/abstract/document/10561501) | [2024/06](https://ieeexplore.ieee.org/abstract/document/10561501) | Collaboration | Delegation |
| [WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/pdf/2406.12373) | [2024/06](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live) | Collaboration | Delegation |
| [REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents Using Information Relevance and Relative Proximity](https://arxiv.org/abs/2405.16751) | [2024/05](https://arxiv.org/abs/2405.16751) | Collaboration | Delegation |
| [A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples](https://arxiv.org/abs/2404.15974) | [2024/04](https://arxiv.org/abs/2404.15974) | Collaboration | Delegation, Supervision |
| [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943) | [2024/04](https://github.com/AgentCoord/AgentCoord) [![GitHub stars](https://img.shields.io/github/stars/AgentCoord/AgentCoord?style=social)](https://github.com/AgentCoord/AgentCoord) | Collaboration | Coordination |
| [An LLM-based approach for Enabling Seamless Human-Robot Collaboration in Assembly](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | [2024/04](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | Collaboration | Delegation |
| [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) | [2024/04](https://github.com/Berkeley-NLP/Agent-Eval-Refine) [![GitHub stars](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine?style=social)](https://github.com/Berkeley-NLP/Agent-Eval-Refine) | Collaboration | Delegation |
| [PDFChatAnnotator: A Human-LLM Collaborative Multi-Modal Data Annotation Tool for PDF-Format Catalogs](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | [2024/04](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | Collaboration | Delegation |
| [Embodied LLM Agents Learn to Cooperate in Organized Teams](https://arxiv.org/abs/2403.12482) | [2024/03](https://github.com/tobeatraceur/Organized-LLM-Agents) [![GitHub stars](https://img.shields.io/github/stars/tobeatraceur/Organized-LLM-Agents?style=social)](https://github.com/tobeatraceur/Organized-LLM-Agents) | Collaboration | Delegation |
| [Large Language Model-based Human-Agent Collaboration for Complex Task Solving](https://arxiv.org/abs/2402.12914) | [2024/02](https://github.com/XueyangFeng/ReHAC) [![GitHub stars](https://img.shields.io/github/stars/XueyangFeng/ReHAC?style=social)](https://github.com/XueyangFeng/ReHAC) | Collaboration | Delegation |
| [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) | [2024/02](https://github.com/McGill-NLP/WebLINX) [![GitHub stars](https://img.shields.io/github/stars/McGill-NLP/WebLINX?style=social)](https://github.com/McGill-NLP/WebLINX) | Collaboration | Delegation |
| [A2C: A Modular Multi-stage Collaborative Decision Framework for Human-AI Teams](https://arxiv.org/abs/2401.14432) | [2024/01](https://anonymous.4open.science/r/A2C/README.md) | Collaboration | Coordination |
| [Ask-before-Plan: Proactive Language Agents for Real-World Planning](https://arxiv.org/abs/2401.14432) | [2024/01](https://github.com/magicgh/Ask-before-Plan) [![GitHub stars](https://img.shields.io/github/stars/magicgh/Ask-before-Plan?style=social)](https://github.com/magicgh/Ask-before-Plan) | Collaboration | Coordination |
| [LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination](https://arxiv.org/abs/2312.15224) | [2023/12](https://github.com/HosnLS/Hierarchical-Language-Agent) [![GitHub stars](https://img.shields.io/github/stars/HosnLS/Hierarchical-Language-Agent?style=social)](https://github.com/HosnLS/Hierarchical-Language-Agent) | Collaboration | Supervision, Delegation |
| [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667) | [2023/10](https://arxiv.org/abs/2310.11667) | Collaboration, Competition, Coopetition | Coordination |
| [Drive As You Speak: Enabling Human-Like Interaction With Large Language Models in Autonomous Vehicles](https://arxiv.org/abs/2309.10228) | [2023/09](https://arxiv.org/abs/2309.10228) | Collaboration | Delegation |
| [MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback](https://arxiv.org/pdf/2309.10691) | [2023/09](https://xwang.dev/mint-bench/) | Collaboration | Delegation |
| [MindAgent: Emergent Gaming Interaction](https://arxiv.org/abs/2309.09971) | [2023/09](https://github.com/mindagent/mindagent) [![GitHub stars](https://img.shields.io/github/stars/mindagent/mindagent?style=social)](https://github.com/mindagent/mindagent) | Collaboration | Coordination |
| [LLM-Based Human-Robot Collaboration Framework for Manipulation Tasks](https://arxiv.org/abs/2308.14972) | [2023/08](https://arxiv.org/abs/2308.14972) | Collaboration | Supervision, Delegation |
| [MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) | [2023/08](https://github.com/geekan/MetaGPT) [![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)](https://github.com/geekan/MetaGPT) | Collaboration | Coordination |
| [Building Cooperative Embodied Agents Modularly with Large Language Models](https://arxiv.org/abs/2307.02485) | [2023/07](https://arxiv.org/abs/2307.02485) | Collaboration | Cooperation |
| [Embodied Task Planning with Large Language Models](https://arxiv.org/abs/2307.01848) | [2023/07](https://github.com/Gary3410/TaPA) [![GitHub stars](https://img.shields.io/github/stars/Gary3410/TaPA?style=social)](https://github.com/Gary3410/TaPA) | Collaboration | Delegation |
| [Improved Trust in Human-Robot Collaboration With ChatGPT](https://ieeexplore.ieee.org/abstract/document/10141597) | [2023/06](https://ieeexplore.ieee.org/abstract/document/10141597) | Collaboration | Delegation |
| [Investigating Agency of LLMs in Human-AI Collaboration Tasks](https://arxiv.org/abs/2305.12815) | [2023/05](https://arxiv.org/abs/2305.12815) | Collaboration | Cooperation, Delegation |
| [Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents through Help Feedback](https://arxiv.org/abs/2304.10750) | [2023/04](https://arxiv.org/abs/2304.10750) | Collaboration | Delegation |
| [PaLM-E: An Embodied Multimodal Language Model](https://openreview.net/forum?id=VTpHpqM3Cf&utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=284568789&_hsenc=p2ANqtz-9lsSL4nXMrOGBQqGoqktY5Yno_r9-nTOARZinDcgihFNqcOFEQb_MVtHKdpgI2AC3N8SrNW5PxcD0uxl4WeKcPJgUOgw) | [2023/03](https://palm-e.github.io) | Collaboration | Delegation |
| [AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | [2021/10](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | Collaboration | Delegation |



## 🎛️ Orchestration
 ([©️click here back to table of contents👆🏻](#contents))


| Title | Date & Code | Orchestration Strategy | Orchestration Synchronization |
| --- | :---: | :---: | :---: |
| [MineWorld: A Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) | [2025/04](https://github.com/microsoft/MineWorld) [![GitHub stars](https://img.shields.io/github/stars/microsoft/MineWorld?style=social)](https://github.com/microsoft/MineWorld) | One-by-One | Synchronous |
| [Experimental Exploration: Investigating Cooperative Interaction Behavior Between Humans and Large Language Model Agents](https://arxiv.org/abs/2503.07320) | [2025/03](https://arxiv.org/abs/2503.07320) | One-by-One | Synchronous |
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://arxiv.org/abs/2503.02692) | [2025/03](https://huggingface.co/datasets/Illogicaler/FinArena-low-cost-dataset) | One-by-One | Synchronous |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | [2025/03](https://github.com/facebookresearch/sweet_rl) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social)](https://github.com/facebookresearch/sweet_rl) | One-by-One | Synchronous |
| [ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments](https://arxiv.org/abs/2502.19852) | [2025/02](https://github.com/stovecat/convcodeworld) [![GitHub stars](https://img.shields.io/github/stars/stovecat/convcodeworld?style=social)](https://github.com/stovecat/convcodeworld) | One-by-One | Asynchronous |
| [Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration](https://arxiv.org/abs/2502.11882) | [2025/02](https://github.com/sjtu-marl/DPT-Agent) [![GitHub stars](https://img.shields.io/github/stars/sjtu-marl/DPT-Agent?style=social)](https://github.com/sjtu-marl/DPT-Agent) | Simultaneous | Asynchronous |
| [CoWPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation](https://arxiv.org/abs/2501.16609) | [2025/01](https://oaishi.github.io/cowpilot.html) | One-by-One | Synchronous |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration (Co-Gym)](https://arxiv.org/abs/2412.15701) | [2024/12](https://github.com/SALT-NLP/collaborative-gym) [![GitHub stars](https://img.shields.io/github/stars/SALT-NLP/collaborative-gym?style=social)](https://github.com/SALT-NLP/collaborative-gym) | One-by-One | Asynchronous |
| [Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension](https://arxiv.org/abs/2412.05958) | [2024/12](https://github.com/BESSER-PEARL/agentic-bpmn) [![GitHub stars](https://img.shields.io/github/stars/BESSER-PEARL/agentic-bpmn?style=social)](https://github.com/BESSER-PEARL/agentic-bpmn) | One-by-One | Asynchronous |
| [To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions](https://ieeexplore.ieee.org/abstract/document/10801517) | [2024/10](https://github.com/HRI-EU/AttentiveSupport) [![GitHub stars](https://img.shields.io/github/stars/HRI-EU/AttentiveSupport?style=social)](https://github.com/HRI-EU/AttentiveSupport) | One-by-One | Synchronous |
| [PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-Agent Tasks](https://openreview.net/forum?id=T5QLRRHyL1) | [2024/10](https://github.com/facebookresearch/partnr-planner/tree/main/) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/partnr-planner?style=social)](https://github.com/facebookresearch/partnr-planner/tree/main/) | One-by-One | Asynchronous |
| [AssistantX: An LLM-Powered Proactive Assistant in Collaborative Human-Populated Environment](https://arxiv.org/abs/2409.17655) | [2024/09](https://github.com/AssistantX-Agent/AssistantX) [![GitHub stars](https://img.shields.io/github/stars/AssistantX-Agent/AssistantX?style=social)](https://github.com/AssistantX-Agent/AssistantX) | One-by-One | Asynchronous |
| [Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811) | [2024/09](https://arxiv.org/abs/2409.08811) | Simultaneous | Synchronous |
| [Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations](https://arxiv.org/abs/2408.15232) | [2024/08](https://github.com/stanford-oval/storm) [![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)](https://github.com/stanford-oval/storm) | One-by-One | Synchronous |
| [Human-LLM Collaboration in Generative Design for Customization](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | [2024/07](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | One-by-One | Synchronous |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896) | [2024/06](https://github.com/DigiRL-agent/digirl) [![GitHub stars](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social)](https://github.com/DigiRL-agent/digirl) | One-by-One | Asynchronous |
| [Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://arxiv.org/abs/2406.01915) | [2024/06](https://arxiv.org/abs/2406.01915) | One-by-One | Synchronous |
| [Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration](https://ieeexplore.ieee.org/abstract/document/10561501) | [2024/06](https://ieeexplore.ieee.org/abstract/document/10561501) | One-by-One | Synchronous |
| [WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/pdf/2406.12373) | [2024/06](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live) | One-by-One | Synchronous |
| [REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents Using Information Relevance and Relative Proximity](https://arxiv.org/abs/2405.16751) | [2024/05](https://arxiv.org/abs/2405.16751) | One-by-One | Asynchronous |
| [A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples](https://arxiv.org/abs/2404.15974) | [2024/04](https://arxiv.org/abs/2404.15974) | One-by-One | Synchronous |
| [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943) | [2024/04](https://github.com/AgentCoord/AgentCoord) [![GitHub stars](https://img.shields.io/github/stars/AgentCoord/AgentCoord?style=social)](https://github.com/AgentCoord/AgentCoord) | One-by-One | Synchronous |
| [An LLM-based approach for Enabling Seamless Human-Robot Collaboration in Assembly](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | [2024/04](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | One-by-One | Synchronous |
| [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) | [2024/04](https://github.com/Berkeley-NLP/Agent-Eval-Refine) [![GitHub stars](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine?style=social)](https://github.com/Berkeley-NLP/Agent-Eval-Refine) | One-by-One | Asynchronous |
| [PDFChatAnnotator: A Human-LLM Collaborative Multi-Modal Data Annotation Tool for PDF-Format Catalogs](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | [2024/04](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | One-by-One | Synchronous |
| [Embodied LLM Agents Learn to Cooperate in Organized Teams](https://arxiv.org/abs/2403.12482) | [2024/03](https://github.com/tobeatraceur/Organized-LLM-Agents) [![GitHub stars](https://img.shields.io/github/stars/tobeatraceur/Organized-LLM-Agents?style=social)](https://github.com/tobeatraceur/Organized-LLM-Agents) | One-by-One | Synchronous |
| [Large Language Model-based Human-Agent Collaboration for Complex Task Solving](https://arxiv.org/abs/2402.12914) | [2024/02](https://github.com/XueyangFeng/ReHAC) [![GitHub stars](https://img.shields.io/github/stars/XueyangFeng/ReHAC?style=social)](https://github.com/XueyangFeng/ReHAC) | One-by-One | Synchronous |
| [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) | [2024/02](https://github.com/McGill-NLP/WebLINX) [![GitHub stars](https://img.shields.io/github/stars/McGill-NLP/WebLINX?style=social)](https://github.com/McGill-NLP/WebLINX) | One-by-One | Synchronous |
| [A2C: A Modular Multi-stage Collaborative Decision Framework for Human-AI Teams](https://arxiv.org/abs/2401.14432) | [2024/01](https://anonymous.4open.science/r/A2C/README.md) | One-by-One | Asynchronous |
| [Ask-before-Plan: Proactive Language Agents for Real-World Planning](https://arxiv.org/abs/2401.14432) | [2024/01](https://github.com/magicgh/Ask-before-Plan) [![GitHub stars](https://img.shields.io/github/stars/magicgh/Ask-before-Plan?style=social)](https://github.com/magicgh/Ask-before-Plan) | One-by-One | Synchronous |
| [LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination](https://arxiv.org/abs/2312.15224) | [2023/12](https://github.com/HosnLS/Hierarchical-Language-Agent) [![GitHub stars](https://img.shields.io/github/stars/HosnLS/Hierarchical-Language-Agent?style=social)](https://github.com/HosnLS/Hierarchical-Language-Agent) | Simultaneous | Synchronous |
| [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667) | [2023/10](https://arxiv.org/abs/2310.11667) | One-by-One | Synchronous |
| [Drive As You Speak: Enabling Human-Like Interaction With Large Language Models in Autonomous Vehicles](https://arxiv.org/abs/2309.10228) | [2023/09](https://arxiv.org/abs/2309.10228) | One-by-One | Synchronous |
| [MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback](https://arxiv.org/pdf/2309.10691) | [2023/09](https://xwang.dev/mint-bench/) | One-by-One | Synchronous |
| [MindAgent: Emergent Gaming Interaction](https://arxiv.org/abs/2309.09971) | [2023/09](https://github.com/mindagent/mindagent) [![GitHub stars](https://img.shields.io/github/stars/mindagent/mindagent?style=social)](https://github.com/mindagent/mindagent) | One-by-One | Synchronous |
| [LLM-Based Human-Robot Collaboration Framework for Manipulation Tasks](https://arxiv.org/abs/2308.14972) | [2023/08](https://arxiv.org/abs/2308.14972) | One-by-One | Synchronous |
| [MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) | [2023/08](https://github.com/geekan/MetaGPT) [![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)](https://github.com/geekan/MetaGPT) | One-by-One | Asynchronous |
| [Building Cooperative Embodied Agents Modularly with Large Language Models](https://arxiv.org/abs/2307.02485) | [2023/07](https://arxiv.org/abs/2307.02485) | Simultaneous | Synchronous |
| [Embodied Task Planning with Large Language Models](https://arxiv.org/abs/2307.01848) | [2023/07](https://github.com/Gary3410/TaPA) [![GitHub stars](https://img.shields.io/github/stars/Gary3410/TaPA?style=social)](https://github.com/Gary3410/TaPA) | One-by-One | Asynchronous |
| [Improved Trust in Human-Robot Collaboration With ChatGPT](https://ieeexplore.ieee.org/abstract/document/10141597) | [2023/06](https://ieeexplore.ieee.org/abstract/document/10141597) | One-by-One | Synchronous |
| [Investigating Agency of LLMs in Human-AI Collaboration Tasks](https://arxiv.org/abs/2305.12815) | [2023/05](https://arxiv.org/abs/2305.12815) | One-by-One | Synchronous |
| [Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents through Help Feedback](https://arxiv.org/abs/2304.10750) | [2023/04](https://arxiv.org/abs/2304.10750) | One-by-One | Synchronous |
| [PaLM-E: An Embodied Multimodal Language Model](https://openreview.net/forum?id=VTpHpqM3Cf&utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=284568789&_hsenc=p2ANqtz-9lsSL4nXMrOGBQqGoqktY5Yno_r9-nTOARZinDcgihFNqcOFEQb_MVtHKdpgI2AC3N8SrNW5PxcD0uxl4WeKcPJgUOgw) | [2023/03](https://palm-e.github.io) | One-by-One | Synchronous |
| [AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | [2021/10](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | One-by-One | Synchronous |






## 💬 Communication
 ([©️click here back to table of contents👆🏻](#contents))


| Title | Date & Code | Communication Structure | Communication Mode |
| --- | :---: | :---: | :---: |
| [MineWorld: A Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) | [2025/04](https://github.com/microsoft/MineWorld) [![GitHub stars](https://img.shields.io/github/stars/microsoft/MineWorld?style=social)](https://github.com/microsoft/MineWorld) | Decentralized | Conversation |
| [Experimental Exploration: Investigating Cooperative Interaction Behavior Between Humans and Large Language Model Agents](https://arxiv.org/abs/2503.07320) | [2025/03](https://arxiv.org/abs/2503.07320) | Decentralized | Conversation |
| [FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting](https://huggingface.co/datasets/Illogicaler/FinArena-low-cost-dataset) | [2025/03](https://arxiv.org/abs/2503.02692) | Hierarchical | Conversation |
| [SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks](https://arxiv.org/abs/2503.15478) | [2025/03](https://github.com/facebookresearch/sweet_rl) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/sweet_rl?style=social)](https://github.com/facebookresearch/sweet_rl) | Decentralized | Conversation |
| [ConvCodeWorld: Benchmarking Conversational Code Generation in Reproducible Feedback Environments](https://arxiv.org/abs/2502.19852) | [2025/02](https://github.com/stovecat/convcodeworld) [![GitHub stars](https://img.shields.io/github/stars/stovecat/convcodeworld?style=social)](https://github.com/stovecat/convcodeworld) | Decentralized | Conversation |
| [Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration](https://arxiv.org/abs/2502.11882) | [2025/02](https://github.com/sjtu-marl/DPT-Agent) [![GitHub stars](https://img.shields.io/github/stars/sjtu-marl/DPT-Agent?style=social)](https://github.com/sjtu-marl/DPT-Agent) | Decentralized | Observation |
| [CoWPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation](https://arxiv.org/abs/2501.16609) | [2025/01](https://oaishi.github.io/cowpilot.html) | Decentralized | Conversation |
| [Towards Modeling Human-Agentic Collaborative Workflows: A BPMN Extension](https://arxiv.org/abs/2412.05958) | [2024/12](https://github.com/BESSER-PEARL/agentic-bpmn) [![GitHub stars](https://img.shields.io/github/stars/BESSER-PEARL/agentic-bpmn?style=social)](https://github.com/BESSER-PEARL/agentic-bpmn) | Decentralized | Conversation |
| [Collaborative Gym: A Framework for Enabling and Evaluating Human-Agent Collaboration (Co-Gym)](https://arxiv.org/abs/2412.15701) | [2024/12](https://github.com/SALT-NLP/collaborative-gym) [![GitHub stars](https://img.shields.io/github/stars/SALT-NLP/collaborative-gym?style=social)](https://github.com/SALT-NLP/collaborative-gym) | Decentralized | Conversation |
| [To Help or Not to Help: LLM-based Attentive Support for Human-Robot Group Interactions](https://ieeexplore.ieee.org/abstract/document/10801517) | [2024/10](https://github.com/HRI-EU/AttentiveSupport) [![GitHub stars](https://img.shields.io/github/stars/HRI-EU/AttentiveSupport?style=social)](https://github.com/HRI-EU/AttentiveSupport) | Decentralized | Observation |
| [PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-Agent Tasks](https://openreview.net/forum?id=T5QLRRHyL1) | [2024/10](https://github.com/facebookresearch/partnr-planner/tree/main/) [![GitHub stars](https://img.shields.io/github/stars/facebookresearch/partnr-planner?style=social)](https://github.com/facebookresearch/partnr-planner/tree/main/) | Decentralized | Conversation |
| [AssistantX: An LLM-Powered Proactive Assistant in Collaborative Human-Populated Environment](https://arxiv.org/abs/2409.17655) | [2024/09](https://github.com/AssistantX-Agent/AssistantX) [![GitHub stars](https://img.shields.io/github/stars/AssistantX-Agent/AssistantX?style=social)](https://github.com/AssistantX-Agent/AssistantX) | Decentralized | Message Pool |
| [Mutual Theory of Mind in Human-AI Collaboration: An Empirical Study with LLM-driven AI Agents in a Real-time Shared Workspace Task](https://arxiv.org/abs/2409.08811) | [2024/09](https://arxiv.org/abs/2409.08811) | Decentralized | Conversation |
| [Into the Unknown Unknowns: Engaged Human Learning through Participation in Language Model Agent Conversations](https://arxiv.org/abs/2408.15232) | [2024/08](https://github.com/stanford-oval/storm) [![GitHub stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)](https://github.com/stanford-oval/storm) | Decentralized | Conversation |
| [Human-LLM Collaboration in Generative Design for Customization](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | [2024/07](https://www.sciencedirect.com/science/article/abs/pii/S0278612525000731) | Decentralized | Conversation |
| [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896) | [2024/06](https://github.com/DigiRL-agent/digirl) [![GitHub stars](https://img.shields.io/github/stars/DigiRL-agent/digirl?style=social)](https://github.com/DigiRL-agent/digirl) | Decentralized | Conversation |
| [Enhancing Human-Robot Collaborative Assembly in Manufacturing Systems Using Large Language Models](https://arxiv.org/abs/2406.01915) | [2024/06](https://arxiv.org/abs/2406.01915) | Decentralized | Conversation |
| [Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration](https://ieeexplore.ieee.org/abstract/document/10561501) | [2024/06](https://ieeexplore.ieee.org/abstract/document/10561501) | Decentralized | Conversation |
| [WebCanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/pdf/2406.12373) | [2024/06](https://huggingface.co/datasets/iMeanAI/Mind2Web-Live) | Decentralized | Conversation |
| [REVECA: Adaptive Planning and Trajectory-based Validation in Cooperative Language Agents Using Information Relevance and Relative Proximity](https://arxiv.org/abs/2405.16751) | [2024/05](https://arxiv.org/abs/2405.16751) | Hierarchical | Observation |
| [A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples](https://arxiv.org/abs/2404.15974) | [2024/04](https://arxiv.org/abs/2404.15974) | Decentralized | Conversation |
| [AgentCoord: Visually Exploring Coordination Strategy for LLM-based Multi-Agent Collaboration](https://arxiv.org/abs/2404.11943) | [2024/04](https://github.com/AgentCoord/AgentCoord) [![GitHub stars](https://img.shields.io/github/stars/AgentCoord/AgentCoord?style=social)](https://github.com/AgentCoord/AgentCoord) | Decentralized | Conversation |
| [An LLM-based approach for Enabling Seamless Human-Robot Collaboration in Assembly](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | [2024/05](https://www.sciencedirect.com/science/article/pii/S000785062400012X) | Centralized | Conversation |
| [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) | [2024/04](https://github.com/Berkeley-NLP/Agent-Eval-Refine) [![GitHub stars](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine?style=social)](https://github.com/Berkeley-NLP/Agent-Eval-Refine) | Decentralized | Conversation |
| [PDFChatAnnotator: A Human-LLM Collaborative Multi-Modal Data Annotation Tool for PDF-Format Catalogs](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | [2024/04](https://dl.acm.org/doi/abs/10.1145/3640543.3645174) | Decentralized | Conversation |
| [Embodied LLM Agents Learn to Cooperate in Organized Teams](https://arxiv.org/abs/2403.12482) | [2024/03](https://github.com/tobeatraceur/Organized-LLM-Agents) [![GitHub stars](https://img.shields.io/github/stars/tobeatraceur/Organized-LLM-Agents?style=social)](https://github.com/tobeatraceur/Organized-LLM-Agents) | Decentralized | Conversation |
| [Large Language Model-based Human-Agent Collaboration for Complex Task Solving](https://arxiv.org/abs/2402.12914) | [2024/02](https://github.com/XueyangFeng/ReHAC) [![GitHub stars](https://img.shields.io/github/stars/XueyangFeng/ReHAC?style=social)](https://github.com/XueyangFeng/ReHAC) | Decentralized | Conversation |
| [WebLINX: Real-World Website Navigation with Multi-Turn Dialogue](https://arxiv.org/abs/2402.05930) | [2024/02](https://github.com/McGill-NLP/WebLINX) [![GitHub stars](https://img.shields.io/github/stars/McGill-NLP/WebLINX?style=social)](https://github.com/McGill-NLP/WebLINX) | Decentralized | Conversation |
| [A2C: A Modular Multi-stage Collaborative Decision Framework for Human-AI Teams](https://arxiv.org/abs/2401.14432) | [2024/01](https://anonymous.4open.science/r/A2C/README.md) | Decentralized | Conversation |
| [Ask-before-Plan: Proactive Language Agents for Real-World Planning](https://arxiv.org/abs/2401.14432) | [2024/01](https://github.com/magicgh/Ask-before-Plan) [![GitHub stars](https://img.shields.io/github/stars/magicgh/Ask-before-Plan?style=social)](https://github.com/magicgh/Ask-before-Plan) | Centralized | Conversation |
| [LLM-Powered Hierarchical Language Agent for Real-time Human-AI Coordination](https://arxiv.org/abs/2312.15224) | [2023/12](https://github.com/HosnLS/Hierarchical-Language-Agent) [![GitHub stars](https://img.shields.io/github/stars/HosnLS/Hierarchical-Language-Agent?style=social)](https://github.com/HosnLS/Hierarchical-Language-Agent) | Hierarchical | Conversation |
| [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667) | [2023/10](https://arxiv.org/abs/2310.11667) | Centralized | Conversation |
| [Drive As You Speak: Enabling Human-Like Interaction With Large Language Models in Autonomous Vehicles](https://arxiv.org/abs/2309.10228) | [2023/09](https://arxiv.org/abs/2309.10228) | Centralized | Conversation |
| [MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback](https://arxiv.org/pdf/2309.10691) | [2023/09](https://xwang.dev/mint-bench/) | Decentralized | Conversation |
| [MindAgent: Emergent Gaming Interaction](https://arxiv.org/abs/2309.09971) | [2023/09](https://github.com/mindagent/mindagent) [![GitHub stars](https://img.shields.io/github/stars/mindagent/mindagent?style=social)](https://github.com/mindagent/mindagent) | Centralized | Conversation |
| [LLM-Based Human-Robot Collaboration Framework for Manipulation Tasks](https://arxiv.org/abs/2308.14972) | [2023/08](https://arxiv.org/abs/2308.14972) | Decentralized | Conversation |
| [MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352) | [2023/08](https://github.com/geekan/MetaGPT) [![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)](https://github.com/geekan/MetaGPT) | Decentralized | Message Pool |
| [Building Cooperative Embodied Agents Modularly with Large Language Models](https://arxiv.org/abs/2307.02485) | [2023/07](https://arxiv.org/abs/2307.02485) | Decentralized | Conversation |
| [Embodied Task Planning with Large Language Models](https://arxiv.org/abs/2307.01848) | [2023/07](https://github.com/Gary3410/TaPA) [![GitHub stars](https://img.shields.io/github/stars/Gary3410/TaPA?style=social)](https://github.com/Gary3410/TaPA) | Decentralized | Conversation |
| [Improved Trust in Human-Robot Collaboration With ChatGPT](https://ieeexplore.ieee.org/abstract/document/10141597) | [2023/06](https://ieeexplore.ieee.org/abstract/document/10141597) | Decentralized | Conversation |
| [Investigating Agency of LLMs in Human-AI Collaboration Tasks](https://arxiv.org/abs/2305.12815) | [2023/05](https://arxiv.org/abs/2305.12815) | Decentralized | Conversation |
| [Improving Grounded Language Understanding in a Collaborative Environment by Interacting with Agents through Help Feedback](https://arxiv.org/abs/2304.10750) | [2023/04](https://arxiv.org/abs/2304.10750) | Decentralized | Conversation |
| [PaLM-E: An Embodied Multimodal Language Model](https://openreview.net/forum?id=VTpHpqM3Cf&utm_campaign=The%20Batch&utm_source=hs_email&utm_medium=email&utm_content=284568789&_hsenc=p2ANqtz-9lsSL4nXMrOGBQqGoqktY5Yno_r9-nTOARZinDcgihFNqcOFEQb_MVtHKdpgI2AC3N8SrNW5PxcD0uxl4WeKcPJgUOgw) | [2023/03](https://palm-e.github.io) | Decentralized | Conversation |
| [AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | [2021/10](https://dl.acm.org/doi/abs/10.1145/3491102.3517582) | Hierarchical | Conversation |



## 📚 Applications, Datasets & Benchmarks
 ([©️click here back to table of contents👆🏻](#contents))

 
| Domain | Datasets & Benchmarks | Proposed or Used by | Data Link |
|---|:---:|:---:|:---:|
| Embodied AI | TaPA | [Wu et al., 2023](https://arxiv.org/abs/2307.01848) | [Link](https://github.com/Gary3410/TaPA) |
| Embodied AI | EmboInteract | [Sun et al., 2024b](https://openreview.net/forum?id=WDdiCIkpxC) | – |
| Embodied AI | AssistantX | [Sun et al., 2024](https://arxiv.org/abs/2409.17655) | – |
| Embodied AI | IGLU Multi-Turn | [Mehta et al., 2024](https://arxiv.org/abs/2304.10750) | [Link](https://github.com/microsoft/iglu-datasets) |
| Embodied AI | PARTNR | [Chang et al., 2024](https://arxiv.org/abs/2411.00081) | [Link](https://github.com/facebookresearch/partnr-planner/tree/main/) |
| Embodied AI | MINT | [Wang et al., 2024](https://arxiv.org/abs/2309.10691) | [Link](https://github.com/xingyaoww/mint-bench) |
| Embodied AI | C-WAH | [Seo et al., 2025](https://arxiv.org/abs/2405.16751) | [Link](https://github.com/UMass-Embodied-AGI/CoELA) |
| Conversational Systems | WEBLINX | [Lu et al., 2024](https://arxiv.org/abs/2402.05930) | – |
| Conversational Systems | Ask-before-Plan | [Zhang et al., 2024](https://arxiv.org/abs/2401.14432) | [Link](https://github.com/magicgh/Ask-before-Plan) |
| Conversational Systems | Agency Dialogue | [Sharma et al., 2024](https://arxiv.org/abs/2305.12815) | – |
| Conversational Systems | WildSeek | [Jiang et al., 2024](https://aclanthology.org/2024.emnlp-main.554/) | [Link](https://github.com/stanford-oval/storm?tab=readme-ov-file) |
| Conversational Systems | MINT | [Wang et al., 2024](https://arxiv.org/abs/2309.10691) | [Link](https://github.com/xingyaoww/mint-bench) |
| Conversational Systems | HOTPOTQA | [Feng et al., 2024](https://hotpotqa.github.io/) | [Link](https://hotpotqa.github.io/) |
| Conversational Systems | StrategyQA | [Feng et al., 2024](https://github.com/eladsegal/strategyqa) | [Link](https://github.com/eladsegal/strategyqa) |
| Software Development | MINT | [Wang et al., 2024](https://arxiv.org/abs/2309.10691) | [Link](https://github.com/xingyaoww/mint-bench) |
| Software Development | InterCode | [Feng et al., 2024](https://github.com/princeton-nlp/intercode) | [Link](https://github.com/princeton-nlp/intercode) |
| Software Development | ColBench | [Zhou et al., 2025](https://arxiv.org/abs/2503.15478) | [Link](https://huggingface.co/datasets/facebook/collaborative_agent_bench) |
| Software Development | ConvCodeWorld | [Han et al., 2025](https://arxiv.org/abs/2502.19852) | [Link](https://github.com/stovecat/convcodeworld) |
| Software Development | ConvCodeBench | [Han et al., 2025](https://arxiv.org/abs/2502.19852) | [Link](https://github.com/stovecat/convcodeworld) |
| Gaming | CuisineWorld | [Gong et al., 2023](https://arxiv.org/abs/2309.09971) | [Link](https://github.com/mindagent/mindagent) |
| Gaming | MineWorld | [Guo et al., 2025](https://arxiv.org/abs/2504.08388) | [Link](https://github.com/microsoft/MineWorld) |
| Finance | FinArena-Low-Cost | [Xu et al., 2025](https://arxiv.org/abs/2503.02692) | [Link](https://huggingface.co/datasets/Illogicaler/FinArena-low-cost-dataset) |





<!-- ## 🔗 Other Resources   -->


## 📌 Contributing
 ([©️click here back to table of contents👆🏻](#contents))

Contributions are welcome! If you have relevant papers, code, or insights, feel free to submit a request 🤗.  



## 📝 Citation
 ([©️click here back to table of contents👆🏻](#contents))

If you find our survey helpful, please consider citing our work 💕:

```
@misc{zou2025surveylargelanguagemodel,
      title={A Survey on Large Language Model based Human-Agent Systems}, 
      author={Henry Peng Zou and Wei-Chieh Huang and Yaozu Wu and Yankai Chen and Chunyu Miao and Hoang Nguyen and Yue Zhou and Weizhi Zhang and Liancheng Fang and Langzhou He and Yangning Li and Yuwei Cao and Dongyuan Li and Renhe Jiang and Philip S. Yu},
      year={2025},
      eprint={2505.00753},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2505.00753}, 
}
```



<!-- omit in toc -->
## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&type=Date)](https://www.star-history.com/#HenryPengZou/Awesome-LLM-Based-Human-Agent-System-Papers&Date)
