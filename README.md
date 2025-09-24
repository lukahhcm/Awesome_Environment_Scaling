# 🌊 Awesome-Scaling-Environments

<!-- <div align="center">
  <img src="logo.png" alt="Logo" width="300">
  <h1 align="center">Thinking with Images: Next Frontier in Multimodal AI</h1>
  <p align="center">
    This repository accompanies our survey paper: <br>
    <a href="https://arxiv.org/pdf/2506.23918"><strong>Thinking with Images for Multimodal Reasoning: Foundations, Methods, and Future Frontiers</strong></a>
  </p>
  
  [![Awesome](https://awesome.re/badge.svg)](https://github.com/zhaochen0110/Awesome_Think_With_Images) 
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/zhaochen0110/Awesome_Think_With_Images?color=green) 

</div>

<div align="center">
  <a href="https://arxiv.org/pdf/2506.23918">
    <img src="https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white" alt="Paper">
  </a>
  <a href="https://github.com/zhaochen0110/Awesome_Think_With_Images">
    <img src="https://img.shields.io/badge/Think_With_Images-000000?style=for-the-badge&logo=github&logoColor=000&logoColor=white" alt="Github">
  </a>
  <a href="https://huggingface.co/papers/2506.23918">
    <img src="https://img.shields.io/badge/HuggingFace-fcd022?style=for-the-badge&logo=huggingface&logoColor=000" alt="Hugging Face Collection">
  </a>
  <a href="https://x.com/SuZhaochen0110/status/1940251163166986333">
    <img src="https://img.shields.io/badge/Twitter-%23000000.svg?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
</div> -->

## Introduction

<!-- Welcome to Awesome-Think-With-Images! The field of multimodal AI is undergoing a fundamental evolution, moving beyond static visual perception towards a new paradigm where vision becomes a **dynamic, manipulable cognitive workspace**. This repository is the first comprehensive resource that systematically curates the pivotal research enabling this shift.

We structure this collection along a trajectory of increasing cognitive autonomy, as detailed in our survey. This journey unfolds across three key stages:

1.  **Stage 1: Tool-Driven Visual Exploration** — Models as "Commanders" orchestrating external visual tools.
2.  **Stage 2: Programmatic Visual Manipulation** — Models as "Visual Programmers" creating bespoke analyses.
3.  **Stage 3: Intrinsic Visual Imagination** — Models as "Visual Thinkers" generating internal mental imagery.

<div align="center">
  <img src="paradigm_shift_figure.png" alt="The Paradigm Shift from Think about Images to Think with Images" width="800">
  <p><em>The paradigm shift from “Thinking about Images” to “Thinking with Images”, an evolution that transforms vision from a static input into a dynamic and manipulable cognitive workspace.</em></p>
</div>

As detailed in our survey, this paradigm shift unlocks three key capabilities: **Dynamic Perceptual Exploration**, **Structured Visual Reasoning**, and **Goal-Oriented Generative Planning**. This collection is for researchers, developers, and enthusiasts eager to explore the forefront of AI that can truly see, reason, and imagine.

<div align="center">
  <img src="paradigm_comparison.png" alt="Paradigm Comparison" width="800">
  <p><em>Conceptual comparison of “Thinking about Images” versus “Thinking with Images”.</em></p>
</div>

We structure this collection along a trajectory of increasing cognitive autonomy. This journey unfolds across three key stages, forming the taxonomy of our work:

<div align="center">
  <img src="taxonomy_tree.png" alt="Taxonomy of Thinking with Images" width="800">
  <p><em>The taxonomy of "Thinking with Images" organizing the field into core methodologies (across three stages), evaluation benchmarks, and key applications.</em></p>
</div>

This collection is for researchers, developers, and enthusiasts eager to explore the forefront of AI that can truly see, reason, and imagine. -->

Welcome to **Awesome-Scaling-Environments!** The field of LLM agents is entering a new era — moving beyond static datasets towards a paradigm where **environments become active data producers, continuously generating tasks and feedback to drive agent evolution**. This repository is the first comprehensive resource that systematically curates the research enabling this shift. We structure this collection along two fundamental axes, as detailed in our survey:

- **Scaling task generation** is the ability of environments to continually create challenging, diverse, and realistic tasks that foster generalization. It develops along two directions: task complexity, which captures the structural and dynamic nature of challenges, and data collection, which enriches the realism of interaction data from tools, humans, and other agents.

- **Scaling feedback** concerns how environments evaluate and guide agent behavior. It involves increasing the density and granularity of signals, improving automation and objectivity to reduce human supervision, and strengthening robustness against noise, exploitation, and failures. 

Together, these two axes define environment scaling as a first-class paradigm for advancing LLM agents toward greater autonomy and adaptability.

---


## 🔔 News
<!-- -   **[2025-07]** We have released ["Thinking with Images for Multimodal Reasoning: Foundations, Methods, and Future Frontiers"](https://arxiv.org/pdf/2506.23918), the **first comprehensive survey** dedicated to the emerging paradigm of "Think with Images". 
-   **[2025-06]** We created this repository to maintain a paper list on Awesome-Think-With-Images. Contributions are welcome!
-   **[2025-05]** We are excited to release **[OpenThinkIMG](https://github.com/OpenThinkIMG/OpenThinkIMG)**, the first dedicated end-to-end open-source framework designed to empower LVLMs to truly **think with images**! For ease of use, we've configured a Docker environment. We warmly invite the community to explore, use, and contribute. -->

---

## 📜 Table of Contents

<!-- - [🧠🤖 Awesome-Think-With-Images](#-awesome-think-with-images)
  - [Introduction](#introduction)
  - [🔔 News](#-news)
  - [📜 Table of Contents](#-table-of-contents)
  - [🧭 The Three-Stage Evolution of Thinking with Images](#-the-three-stage-evolution-of-thinking-with-images)
  - [🛠️ Stage 1: Tool-Driven Visual Exploration](#️-stage-1-tool-driven-visual-exploration)
    - [➤ Prompt-Based Approaches](#-prompt-based-approaches)
    - [➤ SFT-Based Approaches](#-sft-based-approaches)
    - [➤ RL-Based Approaches](#-rl-based-approaches)
  - [💻 Stage 2: Programmatic Visual Manipulation](#-stage-2-programmatic-visual-manipulation)
    - [➤ Prompt-Based Approaches](#-prompt-based-approaches-1)
    - [➤ SFT-Based Approaches](#-sft-based-approaches-1)
    - [➤ RL-Based Approaches](#-rl-based-approaches-1)
  - [🎨 Stage 3: Intrinsic Visual Imagination](#-stage-3-intrinsic-visual-imagination)
    - [➤ SFT-Based Approaches](#-sft-based-approaches-2)
    - [➤ RL-Based Approaches](#-rl-based-approaches-2)
  - [📊 Evaluation \& Benchmarks](#-evaluation--benchmarks)
    - [➤ Benchmarks for Thinking with Images](#-benchmarks-for-thinking-with-images)
  - [🙏 Contributing \& Citation](#-contributing--citation)
  - [Star History](#star-history) -->

---
## 🎯 Scaling Task Generation
*Scaling task generation requires producing complex challenges that build higher-order abilities and collecting rich, realistic datasets, organized along task complexity and data collection.*
### Scaling Task Complexity
#### ➤ Static Complexity
*Static complexity moves from single-step commands to hierarchical and dependency-rich tasks.*

#### ➤ Dynamic Complexity
*Dynamic environments provide signals beyond stationarity, thus preventing overfitting.*
- [ARE: Scaling Up Agent Environments and Evaluations](https://arxiv.org/abs/2509.17158) ![](https://img.shields.io/badge/abs-2025.09-red)
- [EvoCurr: Self-evolving Curriculum with Behavior Code Generation for Complex Decision-making](https://arxiv.org/abs/2508.09586) ![](https://img.shields.io/badge/abs-2025.08-red)
- [R-Zero: Self-Evolving Reasoning LLM from Zero Data](https://arxiv.org/abs/2508.05004) ![](https://img.shields.io/badge/abs-2025.08-red)
- [Eurekaverse: Environment Curriculum Generation via Large Language Models](https://arxiv.org/abs/2411.01775) ![](https://img.shields.io/badge/abs-2024.11-red)
- [WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning](https://arxiv.org/abs/2411.02337) ![](https://img.shields.io/badge/abs-2024.11-red)
- [AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation](https://arxiv.org/abs/2408.00764) ![](https://img.shields.io/badge/abs-2024.08-red) 
- [AgentGym: Evolving Large Language Model-based Agents across Diverse Environments](https://arxiv.org/abs/2406.04151) ![](https://img.shields.io/badge/abs-2024.06-red) 
- [EnvGen: Generating and Adapting Environments via LLMs for Training Embodied Agents](https://arxiv.org/abs/2403.12014) ![](https://img.shields.io/badge/abs-2024.03-red)

#### ➤ Task Diversity
*Robust and generalizable LLM agents emerge from diverse tasks, environments, and interactions.*
- [R-Zero: Self-Evolving Reasoning LLM from Zero Data](https://arxiv.org/abs/2508.05004) ![](https://img.shields.io/badge/abs-2025.08-red)
- [AgentSense: Virtual Sensor Data Generation Using LLM Agents in Simulated Home Environments](https://arxiv.org/abs/2506.11773) ![](https://img.shields.io/badge/abs-2025.06-red)
- [AgentBank: Towards Generalized LLM Agents via Fine-Tuning on 50000+ Interaction Trajectories](https://arxiv.org/abs/2410.07706) ![](https://img.shields.io/badge/abs-2024.10-red)
- [AgentGym: Evolving Large Language Model-based Agents across Diverse Environments](https://arxiv.org/abs/2406.04151) ![](https://img.shields.io/badge/abs-2024.06-red) 

### Scaling Data Collection
#### ➤ Interaction Scaling
*Expanding the richness of interaction data while reducing the difficulty of collection.*
- [Towards General Agentic Intelligence via Environment Scaling](https://arxiv.org/abs/2509.13311) ![](https://img.shields.io/badge/abs-2025.09-red)
- [MCP-Universe: Benchmarking Large Language Models with Real-World Model Context Protocol Servers](https://arxiv.org/abs/2508.14704) ![](https://img.shields.io/badge/abs-2025.08-red)
- [MCP-Bench: Benchmarking Tool-Using LLM Agents with Complex Real-World Tasks via MCP Servers](https://www.arxiv.org/abs/2508.20453) ![](https://img.shields.io/badge/abs-2025.08-red)
- [MCPToolBench++: A Large Scale AI Agent Model Context Protocol MCP Tool Use Benchmark](https://arxiv.org/abs/2508.07575) ![](https://img.shields.io/badge/abs-2025.08-red)
- [Procedural Environment Generation for Tool-Use Agents](https://arxiv.org/abs/2506.11045) ![](https://img.shields.io/badge/abs-2025.06-red)
- [AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents](https://arxiv.org/abs/2407.18901) ![](https://img.shields.io/badge/abs-2024.07-red)
- [WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://arxiv.org/abs/2207.01206) ![](https://img.shields.io/badge/abs-2022.07-red)

#### ➤ Realism Scaling
*Increasing the authenticity of the interaction data.*
- [Towards General Agentic Intelligence via Environment Scaling](https://arxiv.org/abs/2509.13311) ![](https://img.shields.io/badge/abs-2025.09-red)
- [Feedback-Driven Tool-Use Improvements in Large Language Models via Automated Build Environments](https://arxiv.org/abs/2508.08791) ![](https://img.shields.io/badge/abs-2025.08-red)
- [Making REST APIs Agent-Ready: From OpenAPI to Model Context Protocol Servers for Tool-Augmented LLMs](https://arxiv.org/abs/2507.16044v2) ![](https://img.shields.io/badge/abs-2025.07-red)
- [$\tau^2$-Bench: Evaluating Conversational Agents in a Dual-Control Environment](https://arxiv.org/abs/2506.07982) ![](https://img.shields.io/badge/abs-2025.06-red)
- [APIGen-MT: Agentic Pipeline for Multi-Turn Data Generation via Simulated Agent-Human Interplay](https://arxiv.org/abs/2504.03601) ![](https://img.shields.io/badge/abs-2025.04-red)
- [WebWalker: Benchmarking LLMs in Web Traversal](https://arxiv.org/abs/2501.07572) ![](https://img.shields.io/badge/abs-2025.02-red)
- [AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society](https://arxiv.org/abs/2502.08691) ![](https://img.shields.io/badge/abs-2025.02-red)
- [ToolHop: A Query-Driven Benchmark for Evaluating Large Language Models in Multi-Hop Tool Use](https://arxiv.org/abs/2501.02506) ![](https://img.shields.io/badge/abs-2025.01-red)
- [OASIS: Open Agent Social Interaction Simulations with One Million Agents](https://arxiv.org/abs/2411.11581) ![](https://img.shields.io/badge/abs-2024.11-red)
- [$\tau$-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains](https://arxiv.org/abs/2406.12045) ![](https://img.shields.io/badge/abs-2024.06-red)
- [RestGPT: Connecting Large Language Models with Real-World RESTful APIs](https://arxiv.org/abs/2306.06624) ![](https://img.shields.io/badge/abs-2023.06-red)
- [Tongyi DeepResearch: A New Era of Open-Source AI Researchers](https://tongyi-agent.github.io/blog/introducing-tongyi-deep-research/)

---
## ⚖️ Scaling Feedback
*The evolution of LLM agents hinges on scaling environmental feedback, along dimensions of density and granularity, automation and objectivity, and robustness.*
### ➤ Density & Granuality
*Dense, multifaceted feedback enables clearer attribution and stronger reasoning.*
- [Reinforcement Learning with Rubric Anchors](https://arxiv.org/abs/2508.12790) ![](https://img.shields.io/badge/abs-2025.08-red)
- [Rubrics as Rewards: Reinforcement Learning Beyond Verifiable Domains](https://arxiv.org/abs/2507.17746) ![](https://img.shields.io/badge/abs-2025.07-red)
- [What Are Step-Level Reward Models Rewarding? Counterintuitive Findings from MCTS-Boosted Mathematical Reasoning](https://arxiv.org/abs/2412.15904) ![](https://img.shields.io/badge/abs-2024.12-red)
- [On Designing Effective RL Reward at Training Time for LLM Reasoning](https://arxiv.org/abs/2410.15115) ![](https://img.shields.io/badge/abs-2024.10-red)

### ➤ Automation & Objectivity
*From RLHF to RLAIF:*
- [JudgeLRM: Large Reasoning Models as a Judge](https://arxiv.org/abs/2504.00050) ![](https://img.shields.io/badge/abs-2025.04-red)
- [Agentic reward modeling: Integrating human preferences with verifiable correctness signals for reliable reward systems](https://arxiv.org/abs/2502.19328) ![](https://img.shields.io/badge/abs-2025.02-red)
- [Scaling autonomous agents via automatic reward modeling and planning](https://arxiv.org/abs/2502.12130) ![](https://img.shields.io/badge/abs-2025.02-red)
- [Generative verifiers: Reward modeling as next-token prediction](https://arxiv.org/abs/2408.15240) ![](https://img.shields.io/badge/abs-2024.08-red)

*From Verifiable to Non-Verifiable Rewards:*
- [Omni-think: Scaling cross-domain generalization in llms via multi-task rl with hybrid rewards](https://arxiv.org/abs/2507.14783) ![](https://img.shields.io/badge/abs-2025.07-red)
- [Rlpr: Extrapolating rlvr to general domains without verifiers](https://arxiv.org/abs/2506.18254) ![](https://img.shields.io/badge/abs-2025.06-red)
- [Writing-zero: Bridge the gap between non-verifiable tasks and verifiable rewards](https://arxiv.org/abs/2506.00103) ![](https://img.shields.io/badge/abs-2025.06-red)
- [General-reasoner: Advancing llm reasoning across all domains](https://arxiv.org/abs/2505.14652) ![](https://img.shields.io/badge/abs-2025.05-red)
- [Nover: Incentive training for language models via verifier-free reinforcement learning](https://arxiv.org/abs/2505.16022) ![](https://img.shields.io/badge/abs-2025.05-red)
- [Nemotron-crossthink: Scaling self-learning beyond math reasoning](https://arxiv.org/abs/2504.13941) ![](https://img.shields.io/badge/abs-2025.04-red)
- [Crossing the reward bridge: Expanding rl with verifiable rewards across diverse domains](https://arxiv.org/abs/2503.23829) ![](https://img.shields.io/badge/abs-2025.03-red)


### ➤ Robustness
*Reward-Level:*
- [Mona: Myopic optimization with non-myopic approval can mitigate multi-step reward hacking](https://arxiv.org/abs/2501.13011) ![](https://img.shields.io/badge/abs-2025.01-red)
- [Navigating noisy feedback: Enhancing reinforcement learning with error-prone language models](https://arxiv.org/abs/2410.17389) ![](https://img.shields.io/badge/abs-2024.10-red)

*Interaction-Level:*
- [Trinity-rft: A general-purpose and unified framework for reinforcement fine-tuning of large language models](https://arxiv.org/abs/2505.17826) ![](https://img.shields.io/badge/abs-2025.05-red)
- [Tongyi DeepResearch: A New Era of Open-Source AI Researchers](https://tongyi-agent.github.io/blog/introducing-tongyi-deep-research/)


## 📊 Evaluation & Benchmarks


<!-- 
## 🙏 Contributing & Citation

We welcome contributions! If you have a paper that fits into this framework, please open a pull request. Let's build this resource together.

If you find our survey and this repository useful for your research, please consider citing our work:

```bibtex
@article{su2025thinking,
  title={Thinking with Images for Multimodal Reasoning: Foundations, Methods, and Future Frontiers},
  author={Su, Zhaochen and Xia, Peng and Guo, Hangyu and Liu, Zhenhua and Ma, Yan and Qu, Xiaoye and Liu, Jiaqi and Li, Yanshu and Zeng, Kaide and Yang, Zhengyuan and others},
  journal={arXiv preprint arXiv:2506.23918},
  year={2025}
}
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zhaochen0110/Awesome_Think_With_Images&type=Date)](https://www.star-history.com/#zhaochen0110/Awesome_Think_With_Images&Date) -->
