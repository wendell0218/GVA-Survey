<div align="center"><h2>Generalist Virtual Agents: A Survey on Autonomous Agents Across Digital Platforms</h2></div>

<p align="center">
  <!-- arxiv badges -->
  <a href="https://arxiv.org/abs/2411.10943">
    <img src="https://img.shields.io/badge/Paper-red?style=flat&logo=arxiv">
  </a>
  <!-- Chinese Version -->
  <a href="./CN_survey.md">
    <img src="https://img.shields.io/badge/Chinese--Version-white?style=flat&logo=google-docs">
  </a>
  <!-- Github -->
  <a href="https://github.com/wendell0218/GVA-Survey">
    <img src="https://img.shields.io/badge/Code-black?style=flat&logo=github">
  </a>
  <!-- HuggingFace -->
  <!-- <a href="https://huggingface.co/papers/2411.10943">
    <img src="https://img.shields.io/badge/-%F0%9F%A4%97%20Hugging_Face-orange?style=flat"/>
  </a> -->
  <!-- Last commit -->
  <img src="https://img.shields.io/github/last-commit/wendell0218/GVA-Survey?color=green">
</p>

<div align="center">
  <p>
    <a href="https://scholar.google.com/citations?user=xMORwU8AAAAJ">Minghe Gao</a><sup>1</sup>, 
    <a>Wendong Bu</a><sup>1</sup>, 
    <a>Bingchen Miao</a><sup>1</sup>,
    <a>Yang Wu</a><sup>2</sup>, 
    <a>Yunfei Li</a><sup>2</sup>, <br>
    <a href="https://scholar.google.com/citations?user=lm9s-QgAAAAJ">Juncheng Li</a><sup>1†</sup>,
    <a href="https://scholar.google.com/citations?user=8e7H3PcAAAAJ">Siliang Tang</a><sup>1</sup>,
    <a href="https://scholar.google.com/citations?user=aKXe1FEAAAAJ">Qi Wu</a><sup>3</sup>,
    <a href="https://scholar.google.com/citations?user=1RD7UJAAAAAJ">Yueting Zhuang</a><sup>1</sup>,
    <a href="https://scholar.google.com/citations?user=rHagaaIAAAAJ">Meng Wang</a><sup>4</sup>
  </p>
  <p>
    <sup>1</sup><a href="https://www.zju.edu.cn">Zhejiang University, Hangzhou, China</a> <br>
    <sup>2</sup><a href="https://www.antgroup.com">Antgroup, China</a> <br>
    <sup>3</sup><a href="https://www.adelaide.edu.au">The University of Adelaide, Adelaide, Australia</a> <br>
    <sup>4</sup><a href="https://www.hfut.edu.cn">Hefei University of Technology, Hefei, China</a>
  </p>
</div>

<div align="center"><small><sup>†</sup>Corresponding author: Juncheng Li (<a href="mailto:junchengli@zju.edu.cn">junchengli@zju.edu.cn</a>)</small></div>

## 🔥 News

- **[December 7, 2024]** We have released a Chinese version of the survey, please click [中文版综述](./CN_survey.md) to access!

- **[November 17, 2024]** Our survey is available on the arXiv platform: https://arxiv.org/abs/2411.10943

## 📖 Table of Content
- [Introduction](#-introduction)

- [Cited Papers](#-cited-papers)

- [Related Papers](#-related-papers)

- [How to Contribute](#-how-to-contribute)

- [Citation](#-citation)

## 🤖 Introduction

Welcome to the GitHub repository for our survey paper titled *"Generalist Virtual Agents: A Survey on Autonomous Agents Across Digital Platforms"*. This repository includes all the resources, code, and references related to the paper. Our objective is to provide a comprehensive overview of **Generalist Virtual Agents (GVAs)**, covering their definition, necessity, implementation approaches, evaluation methods, limitations and future directions. We aim to bridge the gap between theory and practice in GVA research, providing a systematic framework for future development in this field.

<div align="center">
  <img src="./assets/overview.png"/> <br>
  <img src="./assets/overview_caption.jpeg"/>
</div>

## 📚 Cited Papers

Here we list the most important references cited in our survey, organized by different sections. We particularly focus on works that have made substantial impact or proposed innovative methodologies.

Additionally, we note that some papers may be cited across multiple sections. For the convenience of researchers, we provide complete citation information under each section. 

### Section II: What is GVA?
![alt text](./assets/definition.png)

#### Environment - Web

- **World of bits: an open-domain platform for web-based agents**
  
  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **Reinforcement Learning on Web Interfaces using Workflow-Guided Exploration**
  
  Stanford University, ICLR, 2018
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/1802.08802)
  [![Star](https://img.shields.io/github/stars/stanfordnlp/wge.svg?style=social&label=Star)](https://github.com/stanfordnlp/wge)

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**
  
  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

- **WebArena: A Realistic Web Environment for Building Autonomous Agents**
  
  Carnegie Mellon University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.13854)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webarena.dev/)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**
  
  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**
  
  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

- **Mind2Web: Towards a Generalist Agent for the Web**
  
  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **WebVLN: Vision-and-Language Navigation on Websites**
  
  Australian Institute for Machine Learning, The University of Adelaide, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.15820)
  [![Star](https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star)](https://github.com/WebVLN/WebVLN)

#### Environment - Application
- **AppAgent: Multimodal Agents as Smartphone Users**
  
  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**
  
  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

- **A Dataset for Interactive Vision Language Navigation with Unknown Command Feasibility**
  
  Boston University, ECCV, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2202.02312)

- **AndroidInTheWild: A Large-Scale Dataset For Android Device Control**
  
  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning**
  
  University of California, Santa Barbara, EMNLP, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.12295)
  [![Star](https://img.shields.io/github/stars/teacherpeterpan/Logic-LLM.svg?style=social&label=Star)](https://github.com/teacherpeterpan/Logic-LLM)

- **Neural-Symbolic VQA: Disentangling Reasoning from Vision and Language Understanding**
  
  Harvard University, NeurIPS, 2018
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/1810.02338)

- **Visual Programming: Compositional visual reasoning without training**
  
  PRIOR @ Allen Institute for AI, CVPR, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2211.11559)

- **Toolformer: Language Models Can Teach Themselves to Use Tools**
  
  Meta AI Research, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2302.04761)

- **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production**
  
  DAMO Academy, Alibaba Group, arXiv preprint arXiv:2403.07952, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07952)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aesopai.github.io/)

#### Environment - Operating System
- **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**

  The University of Hong Kong, arXiv preprint arXiv:2404.07972, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.07972)
  [![Star](https://img.shields.io/github/stars/xlang-ai/OSWorld.svg?style=social&label=Star)](https://github.com/xlang-ai/OSWorld)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://os-world.github.io)

- **AgentStudio: A Toolkit for Building General Virtual Agents**

  NTU, Singapore, arXiv preprint arXiv:2403.17918, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.17918)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://computer-agents.github.io/agent-studio)

- **MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot**

  University of Technology Sydney, arXiv preprint arXiv:2404.18074, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.18074)

- **UFO: A UI-Focused Agent for Windows OS Interaction**

  Microsoft, arXiv preprint arXiv:2402.07939, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.07939)
  [![Star](https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star)](https://github.com/microsoft/UFO)

#### Task - Command Task
- **AppAgent: Multimodal Agents as Smartphone Users**

  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

- **Android In The Wild: A Large-Scale Dataset For Android Device Control**

  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **UFO: A UI-Focused Agent for Windows OS Interaction**

  Microsoft, arXiv preprint arXiv:2402.07939, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.07939)
  [![Star](https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star)](https://github.com/microsoft/UFO)

- **From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces**

  Google DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.00245)
  [![Star](https://img.shields.io/github/stars/google-deepmind/pix2act.svg?style=social&label=Star)](https://github.com/google-deepmind/pix2act)

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**

  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

#### Task - Query Task
- **ViperGPT: Visual Inference via Python Execution for Reasoning**

  Columbia University, ICCV, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.08128)

- **Visual Programming: Compositional visual reasoning without training**

  PRIOR @ Allen Institute for AI, CVPR, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2211.11559)

- **Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning**

  University of California, Santa Barbara, EMNLP, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.12295)
  [![Star](https://img.shields.io/github/stars/teacherpeterpan/Logic-LLM.svg?style=social&label=Star)](https://github.com/teacherpeterpan/Logic-LLM)

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**

  Zhejiang University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.17580)
  [![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)

- **Mm-react: Prompting chatgpt for multimodal reasoning and action**

  Microsoft Azure AI, arXiv preprint arXiv:2303.11381, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.11381)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://multimodal-react.github.io/)

- **WebVLN: Vision-and-Language Navigation on Websites**

  Australian Institute for Machine Learning, The University of Adelaide, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.15820)
  [![Star](https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star)](https://github.com/WebVLN/WebVLN)

#### Task - Dialogue Task
- **Windows Copilot Plus for PCs**

  Microsoft, 2024
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.microsoft.com/en-us/windows/copilot-plus-pcs)

- **Apple Intelligence Overview**

  Apple, 2024
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.apple.com/apple-intelligence)

- **NICE: Neural Image Commenting with Empathy**

  Microsoft, EMNLP, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://aclanthology.org/2021.findings-emnlp.380.pdf)

- **Is ChatGPT Equipped with Emotional Dialogue Capabilities?**

  Harbin Institute of Technology, China, arXiv preprint arXiv:2304.09582, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2304.09582)

#### Observation Space - Command Line Interface
- **AutoGPT**

  OpenAI, 2024
  [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/Significant-Gravitas/AutoGPT)

- **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**

  The University of Hong Kong, arXiv preprint arXiv:2404.07972, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.07972)
  [![Star](https://img.shields.io/github/stars/xlang-ai/OSWorld.svg?style=social&label=Star)](https://github.com/xlang-ai/OSWorld)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://os-world.github.io)

- **AgentBench: Evaluating LLMs as Agents**

  Tsinghua University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2308.03688)
  [![Star](https://img.shields.io/github/stars/THUDM/AgentBench.svg?style=social&label=Star)](https://github.com/THUDM/AgentBench)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://llmbench.ai/agent)

- **AgentStudio: A Toolkit for Building General Virtual Agents**

  NTU, Singapore, arXiv preprint arXiv:2403.17918, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.17918)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://computer-agents.github.io/agent-studio)

- **InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback**

  Department of Computer Science, Princeton University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.14898)
  [![Star](https://img.shields.io/github/stars/princeton-nlp/intercode.svg?style=social&label=Star)](https://github.com/princeton-nlp/intercode)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://intercode-benchmark.github.io/)

#### Observation Space - Document Object Model
- **World of bits: an open-domain platform for web-based agents**

  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **Reinforcement Learning on Web Interfaces using Workflow-Guided Exploration**

  Stanford University, ICLR, 2018
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/1802.08802)
  [![Star](https://img.shields.io/github/stars/stanfordnlp/wge.svg?style=social&label=Star)](https://github.com/stanfordnlp/wge)

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**

  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **AppAgent: Multimodal Agents as Smartphone Users**

  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

- **A data-driven approach for learning to control computers**

  DeepMind, London, United Kingdom, ICML, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2202.08137)

#### Observation Space - Screen
- **You Only Look at Screens: Multimodal Chain-of-Action Agents**

  School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, arXiv preprint arXiv:2309.11436, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2309.11436)
  [![Star](https://img.shields.io/github/stars/cooelf/Auto-GUI.svg?style=social&label=Star)](https://github.com/cooelf/Auto-GUI)

- **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents**

  Department of Computer Science and Technology, Nanjing University, arXiv preprint arXiv:2401.10935, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.10935)
  [![Star](https://img.shields.io/github/stars/njucckevin/SeeClick.svg?style=social&label=Star)](https://github.com/njucckevin/SeeClick)

- **WebVLN: Vision-and-Language Navigation on Websites**

  Australian Institute for Machine Learning, The University of Adelaide, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.15820)
  [![Star](https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star)](https://github.com/WebVLN/WebVLN)

- **From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces**

  Google DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.00245)
  [![Star](https://img.shields.io/github/stars/google-deepmind/pix2act.svg?style=social&label=Star)](https://github.com/google-deepmind/pix2act)

- **GPT-4V(ision) is a Generalist Web Agent, if Grounded**

  The Ohio State University, arXiv preprint arXiv:2401.01614, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.01614)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/SeeAct)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/SeeAct)

- **UFO: A UI-Focused Agent for Windows OS Interaction**

  Microsoft, arXiv preprint arXiv:2402.07939, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.07939)
  [![Star](https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star)](https://github.com/microsoft/UFO)

- **GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation**

  UC San Diego, arXiv preprint arXiv:2311.07562, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2311.07562)
  [![Star](https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star)](https://github.com/zzxslp/MM-Navigator)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

#### Action Space - Keyboard
- **World of bits: an open-domain platform for web-based agents**

  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **WebArena: A Realistic Web Environment for Building Autonomous Agents**

  Carnegie Mellon University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.13854)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webarena.dev/)

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**

  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

#### Action Space - Mouse
- **World of bits: an open-domain platform for web-based agents**

  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces**

  Google DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.00245)
  [![Star](https://img.shields.io/github/stars/google-deepmind/pix2act.svg?style=social&label=Star)](https://github.com/google-deepmind/pix2act)

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **WebArena: A Realistic Web Environment for Building Autonomous Agents**

  Carnegie Mellon University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.13854)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webarena.dev/)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**

  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

#### Action Space - Touchscreen
- **AppAgent: Multimodal Agents as Smartphone Users**

  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

- **AndroidInTheWild: A Large-Scale Dataset For Android Device Control**

  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **You Only Look at Screens: Multimodal Chain-of-Action Agents**

  School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, arXiv preprint arXiv:2309.11436, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2309.11436)
  [![Star](https://img.shields.io/github/stars/cooelf/Auto-GUI.svg?style=social&label=Star)](https://github.com/cooelf/Auto-GUI)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

#### Action Space - Others
- **HyperPalm: DNN-based hand gesture recognition interface for intelligent communication with quadruped robot in 3D space**

  Intelligent Space Robotics Laboratory, Skoltech, SMC, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2209.09937)


### Section III: Why we need GVA?
![alt text](./assets/necessity.png)

#### Perspective of AI and Machine Learning
- **CogAgent: A Visual Language Model for GUI Agents**

  Tsinghua University, arXiv preprint arXiv:2312.08914, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.08914)
  [![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star)](https://github.com/THUDM/CogVLM)

- **You Only Look at Screens: Multimodal Chain-of-Action Agents**

  School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, arXiv preprint arXiv:2309.11436, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2309.11436)
  [![Star](https://img.shields.io/github/stars/cooelf/Auto-GUI.svg?style=social&label=Star)](https://github.com/cooelf/Auto-GUI)

- **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents**

  Department of Computer Science and Technology, Nanjing University, arXiv preprint arXiv:2401.10935, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.10935)
  [![Star](https://img.shields.io/github/stars/njucckevin/SeeClick.svg?style=social&label=Star)](https://github.com/njucckevin/SeeClick)

- **From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces**

  Google DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.00245)
  [![Star](https://img.shields.io/github/stars/google-deepmind/pix2act.svg?style=social&label=Star)](https://github.com/google-deepmind/pix2act)

- **GPT-4V(ision) is a Generalist Web Agent, if Grounded**

  The Ohio State University, arXiv preprint arXiv:2401.01614, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.01614)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/SeeAct)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/SeeAct)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)


#### Perspective of Interaction
- **Inferring Rewards from Language in Context**

  University of California, Berkeley, ACL, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2204.02515)

- **Deep Reinforcement Learning from Human Preferences**

  OpenAI, NeurIPS, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/1706.03741)

- **Apple Intelligence Overview**

  Apple, 2024
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.apple.com/apple-intelligence)

#### Perspective of Agent Applications
- **Distributed and reactive query planning in R-MAGIC: an agent-based multimedia retrieval system**

  IEEE Transactions on Knowledge and Data Engineering, 2004
  [![Paper](https://img.shields.io/badge/Paper-red)](https://ieeexplore.ieee.org/abstract/document/1316836)

- **Rap: Retrieval-augmented planning with contextual memory for multimodal llm agents**

  Panasonic Connect Co., Ltd., Japan, arXiv preprint arXiv:2402.03610, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.03610)

- **Plan4mc: Skill reinforcement learning and planning for open-world minecraft tasks**

  School of Computer Science, Peking University, arXiv preprint arXiv:2303.16563, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.16563)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/plan4mc)

- **Autoact: Automatic agent learning from scratch via self-planning**

  Zhejiang University, arXiv preprint arXiv:2401.05268, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.05268)
  [![Star](https://img.shields.io/github/stars/zjunlp/AutoAct.svg?style=social&label=Star)](https://github.com/zjunlp/AutoAct)

- **Self-Refine: Iterative Refinement with Self-Feedback**

  Language Technologies Institute, Carnegie Mellon University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.17651)
  [![Star](https://img.shields.io/github/stars/selfrefine.info/.svg?style=social&label=Star)](https://selfrefine.info/)

- **Reflexion: language agents with verbal reinforcement learning**

  Northeastern University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.11366)
  [![Star](https://img.shields.io/github/stars/noahshinn024/reflexion.svg?style=social&label=Star)](https://github.com/noahshinn024/reflexion)

- **Eureka: Human-Level Reward Design via Coding Large Language Models**

  NVIDIA, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2310.12931)
  [![Star](https://img.shields.io/github/stars//eureka-research.github.io.svg?style=social&label=Star)](https://eureka-research.github.io)

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**

  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

- **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production**

  DAMO Academy, Alibaba Group, arXiv preprint arXiv:2403.07952, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07952)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://aesopai.github.io/)

### Section IV: How to implement GVA?
![alt text](./assets/implementation.png)

#### Environment - Off-line

- **World of bits: an open-domain platform for web-based agents**

  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **Reinforcement Learning on Web Interfaces using Workflow-Guided Exploration**

  Stanford University, ICLR, 2018
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/1802.08802)
  [![Star](https://img.shields.io/github/stars/stanfordnlp/wge.svg?style=social&label=Star)](https://github.com/stanfordnlp/wge)

- **SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents**

  Department of Computer Science and Technology, Nanjing University, arXiv preprint arXiv:2401.10935, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.10935)
  [![Star](https://img.shields.io/github/stars/njucckevin/SeeClick.svg?style=social&label=Star)](https://github.com/njucckevin/SeeClick)

- **AndroidInTheWild: A Large-Scale Dataset For Android Device Control**

  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **A Dataset for Interactive Vision Language Navigation with Unknown Command Feasibility**

  Boston University, ECCV, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2202.02312)

- **META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI**

  Shanghai Jiao Tong University, EMNLP, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2205.11029)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://x-lance.github.io/META-GUI-Leaderboard/)

#### Environment - On-line

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**

  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

- **WebArena: A Realistic Web Environment for Building Autonomous Agents**

  Carnegie Mellon University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.13854)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webarena.dev/)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**

  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

#### Environment - Updated

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**

  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **AppAgent: Multimodal Agents as Smartphone Users**

  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

- **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**

  The University of Hong Kong, arXiv preprint arXiv:2404.07972, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.07972)
  [![Star](https://img.shields.io/github/stars/xlang-ai/OSWorld.svg?style=social&label=Star)](https://github.com/xlang-ai/OSWorld)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://os-world.github.io)

- **AgentStudio: A Toolkit for Building General Virtual Agents**

  NTU, Singapore, arXiv preprint arXiv:2403.17918, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.17918)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://computer-agents.github.io/agent-studio)

- **UFO: A UI-Focused Agent for Windows OS Interaction**

  Microsoft, arXiv preprint arXiv:2402.07939, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.07939)
  [![Star](https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star)](https://github.com/microsoft/UFO)

#### Model - Retriever-based Agent

- **Distributed and reactive query planning in R-MAGIC: an agent-based multimedia retrieval system**

  nan, IEEE Transactions on Knowledge and Data Engineering, 2004
  [![Paper](https://img.shields.io/badge/Paper-red)](https://ieeexplore.ieee.org/abstract/document/1316836)

- **Mobile agents and their use for information retrieval: a brief overview and an elaborate case study**

  nan, IEEE Network, 2002
  [![Paper](https://img.shields.io/badge/Paper-red)](https://ieeexplore.ieee.org/abstract/document/980543)

- **SAIRE—a scalable agent-based information retrieval engine**

  nan, Proceedings of the first international conference on Autonomous agents, 1997
  [![Paper](https://img.shields.io/badge/Paper-red)](https://dl.acm.org/doi/pdf/10.1145/267658.267731)

- **ACQUIRE: agent-based complex query and information retrieval engine**

  nan, Proceedings of the first international joint conference on Autonomous agents and multiagent systems: part 2, 2002
  [![Paper](https://img.shields.io/badge/Paper-red)](https://dl.acm.org/doi/abs/10.1145/544862.544891)

- **Thought-retriever: Don’t just retrieve raw data, retrieve thoughts**

  University of Illinois at Urbana-Champaign, ICLR Workshop, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://openreview.net/pdf?id=sOSAu0XQcI)

#### Model - LLM-based Agent

- **Agent-pro: Learning to evolve via policy-level reflection and optimization**

  Zhejiang University, arXiv preprint arXiv:2402.17574, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.17574)
  [![Star](https://img.shields.io/github/stars/zwq2018/Agent-Pro.svg?style=social&label=Star)](https://github.com/zwq2018/Agent-Pro)

- **Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning**

  University of California, Santa Barbara, EMNLP, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.12295)
  [![Star](https://img.shields.io/github/stars/teacherpeterpan/Logic-LLM.svg?style=social&label=Star)](https://github.com/teacherpeterpan/Logic-LLM)

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**

  Zhejiang University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.17580)
  [![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)](https://github.com/microsoft/JARVIS)

- **Mm-react: Prompting chatgpt for multimodal reasoning and action**

  Microsoft Azure AI, arXiv preprint arXiv:2303.11381, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.11381)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://multimodal-react.github.io/)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **AllTogether: Investigating the Efficacy of Spliced Prompt for Web Navigation using Large Language Models**

  nan, arXiv preprint arXiv:2310.18331, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2310.18331)

- **Building Cooperative Embodied Agents Modularly with Large Language Models**

  University of Massachusetts Amherst, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.02485)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vis-www.cs.umass.edu/Co-LLM-Agents/)

- **RoboGPT: an intelligent agent of making embodied long-term decisions for daily instruction tasks**

  State Key Laboratory of Multimodal Artificial Intelligence Systems, Institute of Automation, Chinese Academy of Sciences, Beijing, China, arXiv preprint arXiv:2311.15649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2311.15649)

- **AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation**

  University of Hong Kong, arXiv preprint arXiv:2312.13010, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13010)

- **Pyramid Coder: Hierarchical Code Generator for Compositional Visual Question Answering**

  Tokyo Institute of Technology, arXiv preprint arXiv:2407.20563, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2407.20563)

- **Modular Visual Question Answering via Code Generation**

  UC Berkeley, ACL, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.05392)
  [![Star](https://img.shields.io/github/stars/sanjayss34/codevqa.svg?style=social&label=Star)](https://github.com/sanjayss34/codevqa)

- **ViperGPT: Visual Inference via Python Execution for Reasoning**

  Columbia University, ICCV, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.08128)

#### Model - MLLM-based Agent

- **GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation**

  UC San Diego, arXiv preprint arXiv:2311.07562, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2311.07562)
  [![Star](https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star)](https://github.com/zzxslp/MM-Navigator)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

- **Autonomous Evaluation and Refinement of Digital Agents**

  UC Berkeley, arXiv preprint arXiv:2404.06474, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.06474)
  [![Star](https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine.svg?style=social&label=Star)](https://github.com/Berkeley-NLP/Agent-Eval-Refine)

- **Clova: A closed-loop visual assistant with tool usage and update**

  Peking University, CVPR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.10908)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://clova-tool.github.io)

- **Agent smith: A single image can jailbreak one million multimodal llm agents exponentially fast**

  Sea AI Lab, arXiv preprint arXiv:2402.08567, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.08567)
  [![Star](https://img.shields.io/github/stars/sail-sg/Agent-Smith.svg?style=social&label=Star)](https://github.com/sail-sg/Agent-Smith)

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **You Only Look at Screens: Multimodal Chain-of-Action Agents**

  School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University, arXiv preprint arXiv:2309.11436, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2309.11436)
  [![Star](https://img.shields.io/github/stars/cooelf/Auto-GUI.svg?style=social&label=Star)](https://github.com/cooelf/Auto-GUI)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**

  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

- **CogAgent: A Visual Language Model for GUI Agents**

  Tsinghua University, arXiv preprint arXiv:2312.08914, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.08914)
  [![Star](https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star)](https://github.com/THUDM/CogVLM)

#### Model - VLA-based Agent

- **Rt-2: Vision-language-action models transfer web knowledge to robotic control**

  Google DeepMind, arXiv preprint arXiv:2307.15818, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.15818)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://robotics-transformer2.github.io)

- **Lm-nav: Robotic navigation with large pre-trained models of language, vision, and action**

  UC Berkeley, Conference on robot learning, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.04429)

- **Octo: An open-source generalist robot policy**

  UC Berkeley, arXiv preprint arXiv:2405.12213, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2405.12213)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://octo-models.github.io)

- **OpenVLA: An Open-Source Vision-Language-Action Model**

  Stanford University, arXiv preprint arXiv:2406.09246, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.09246)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://openvla.github.io)

- **3d-vla: A 3d vision-language-action generative world model**

  University of Massachusetts Amherst, arXiv preprint arXiv:2403.09631, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.09631)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://vis-www.cs.umass.edu/3dvla)

- **Palm-e: An embodied multimodal language model**

  Robotics at Google, arXiv preprint arXiv:2303.03378, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.03378)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://palm-e.github.io)

- **Actra: Optimized Transformer Architecture for Vision-Language-Action Models in Robot Learning**

  The Chinese University of Hong Kong, arXiv preprint arXiv:2408.01147, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2408.01147)

#### Strategy - Adaption Strategy

- **Mm-react: Prompting chatgpt for multimodal reasoning and action**

  Microsoft Azure AI, arXiv preprint arXiv:2303.11381, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.11381)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://multimodal-react.github.io/)

- **Plan-and-solve prompting: Improving zero-shot chain-of-thought reasoning by large language models**

  Singapore Management University, arXiv preprint arXiv:2305.04091, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.04091)
  [![Star](https://img.shields.io/github/stars/AGI-Edgerunners/Plan-and-Solve-Prompting.svg?style=social&label=Star)](https://github.com/AGI-Edgerunners/Plan-and-Solve-Prompting)

- **Expertprompting: Instructing large language models to be distinguished experts**

  University of Science and Technology of China, arXiv preprint arXiv:2305.14688, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.14688)
  [![Star](https://img.shields.io/github/stars/OFA-Sys/ExpertLLaMA.svg?style=social&label=Star)](https://github.com/OFA-Sys/ExpertLLaMA)

- **Self-refine: Iterative refinement with self-feedback**

  Language Technologies Institute, Carnegie Mellon University, NeurIPS, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.17651)
  [![Star](https://img.shields.io/github/stars/selfrefine.info/.svg?style=social&label=Star)](https://selfrefine.info/)

- **Pangu-coder2: Boosting large language models for code with ranking feedback**

  Huawei Cloud Co., Ltd., arXiv preprint arXiv:2307.14936, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.14936)

- **De-fine: Decomposing and refining visual programs with auto-feedback**

  Zhejiang University, arXiv preprint arXiv:2311.12890, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2311.12890)

- **A survey on the memory mechanism of large language model based agents**

  Gaoling School of Artificial Intelligence, Renmin University of China, arXiv preprint arXiv:2404.13501, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.13501)
  [![Star](https://img.shields.io/github/stars/nuster1128/LLM_Agent_Memory_Survey.svg?style=social&label=Star)](https://github.com/nuster1128/LLM_Agent_Memory_Survey)

- **Rap: Retrieval-augmented planning with contextual memory for multimodal llm agents**

  Panasonic Connect Co., Ltd., Japan, arXiv preprint arXiv:2402.03610, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.03610)

- **Chatdb: Augmenting llms with databases as their symbolic memory**

  Tsinghua University, arXiv preprint arXiv:2306.03901, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.03901)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chatdatabase.github.io/)

- **Memorybank: Enhancing large language models with long-term memory**

  Sun Yat-Sen University, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.10250)
  [![Star](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend.svg?style=social&label=Star)](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

#### Strategy - Fine-tuning Strategy

- **CoEvol: Constructing Better Responses for Instruction Finetuning through Multi-Agent Cooperation**

  University of Macau, arXiv preprint arXiv:2406.07054, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.07054)
  [![Star](https://img.shields.io/github/stars/lirenhao1997/CoEvol.svg?style=social&label=Star)](https://github.com/lirenhao1997/CoEvol)

- **Reflection-Reinforced Self-Training for Language Agents**

  University of California, Los Angeles, arXiv preprint arXiv:2406.01495, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.01495)
  [![Star](https://img.shields.io/github/stars/PlusLabNLP/Re-ReST.svg?style=social&label=Star)](https://github.com/PlusLabNLP/Re-ReST)

- **Learning to Clarify: Multi-turn Conversations with Action-Based Contrastive Self-Training**

  Columbia University, arXiv preprint arXiv:2406.00222, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.00222)

- **Enhancing the General Agent Capabilities of Low-Parameter LLMs through Tuning and Multi-Branch Reasoning**

  Huazhong University of Science and Technology, arXiv preprint arXiv:2403.19962, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.19962)

- **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models**

  Department of Automation, University of Science and Technology of China, arXiv preprint arXiv:2403.12881, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.12881)
  [![Star](https://img.shields.io/github/stars/InternLM/Agent-FLAN.svg?style=social&label=Star)](https://github.com/InternLM/Agent-FLAN)

#### Strategy - Reinforcement Learning Strategy

- **Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning**

  UC Berkeley, arXiv preprint arXiv:2405.10292, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2405.10292)
  [![Star](https://img.shields.io/github/stars/rl4vlm.github.io/.svg?style=social&label=Star)](https://rl4vlm.github.io/)

- **Search Beyond Queries: Training Smaller Language Models for Web Interactions via Reinforcement Learning**

  University of Kentucky, arXiv preprint arXiv:2404.10887, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.10887)

- **Juewu-mc: Playing minecraft with sample-efficient hierarchical reinforcement learning**

  Tencent AI Lab, Shenzhen, China, arXiv preprint arXiv:2112.04907, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2112.04907)

- **Towards robust and domain agnostic reinforcement learning competitions: MineRL 2020**

  CMU, NeurIPS, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v133/guss21a/guss21a.pdf)

- **Plan4mc: Skill reinforcement learning and planning for open-world minecraft tasks**

  School of Computer Science, Peking University, arXiv preprint arXiv:2303.16563, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.16563)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/plan4mc)

- **Pok\'eLLMon: A Human-Parity Agent for Pok\'emon Battles with Large Language Models**

  Georgia Institute of Technology, arXiv preprint arXiv:2402.01118, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.01118)
  [![Star](https://img.shields.io/github/stars/git-disl/PokeLLMon.svg?style=social&label=Star)](https://github.com/git-disl/PokeLLMon)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://poke-llm-on.github.io/)

- **Scaling instructable agents across many simulated worlds**

  Google DeepMind, arXiv preprint arXiv:2404.10179, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.10179)

- **Mental Modeling of Reinforcement Learning Agents by Language Models**

  University of Hamburg, arXiv preprint arXiv:2406.18505, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.18505)
  [![Star](https://img.shields.io/github/stars/LukasWill/LLM-X.svg?style=social&label=Star)](https://github.com/LukasWill/LLM-X)

- **LLMSat: A Large Language Model-Based Goal-Oriented Agent for Autonomous Space Exploration**

  University of Toronto, arXiv preprint arXiv:2405.01392, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2405.01392)


#### Strategy - Cooperation or Competition Strategy

- **CMAT: A Multi-Agent Collaboration Tuning Framework for Enhancing Small Language Models**

  East China Jiaotong University, arXiv preprint arXiv:2404.01663, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.01663)
  [![Star](https://img.shields.io/github/stars/tree/master.svg?style=social&label=Star)](https://github.com/heimy2000/CMAT/tree/master)

- **Autoact: Automatic agent learning from scratch via self-planning**

  Zhejiang University, arXiv preprint arXiv:2401.05268, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.05268)
  [![Star](https://img.shields.io/github/stars/zjunlp/AutoAct.svg?style=social&label=Star)](https://github.com/zjunlp/AutoAct)

- **ProAgent: building proactive cooperative agents with large language models**

  The Chinese University of Hong Kong, Shenzhen, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2308.11339)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-proagent.github.io)

- **Chatllm network: More brains, more intelligence**

  Beijing University of Posts and Telecommunications, arXiv preprint arXiv:2304.12998, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2304.12998)

- **Encouraging divergent thinking in large language models through multi-agent debate**

  Tsinghua University, arXiv preprint arXiv:2305.19118, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.19118)
  [![Star](https://img.shields.io/github/stars/Skytliang/Multi-Agents-Debate.svg?style=social&label=Star)](https://github.com/Skytliang/Multi-Agents-Debate)

- **Improving factuality and reasoning in language models through multiagent debate**

  MIT CSAIL, arXiv preprint arXiv:2305.14325, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.14325)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://composable-models.github.io/llm_debate/)

- **Chateval: Towards better llm-based evaluators through multi-agent debate**

  Tsinghua University, arXiv preprint arXiv:2308.07201, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2308.07201)
  [![Star](https://img.shields.io/github/stars/chanchimin/ChatEval.svg?style=social&label=Star)](https://github.com/chanchimin/ChatEval)

- **How susceptible are llms to logical fallacies?**

  Department of Computer Science, George Mason University, arXiv preprint arXiv:2308.09853, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2308.09853)
  [![Star](https://img.shields.io/github/stars/Amir-pyh/LOGICOM.svg?style=social&label=Star)](https://github.com/Amir-pyh/LOGICOM)

### Section V: How to evaluate GVA?
![alt text](./assets/evaluation.png)

#### Overall Evaluation

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**

  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?**

  ServiceNow Research, arXiv preprint arXiv:2403.07718, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.07718)
  [![Star](https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star)](https://github.com/ServiceNow/WorkArena)

- **GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices**

  OpenGVLab, Shanghai AI Laboratory, arXiv preprint arXiv:2406.08451, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.08451)
  [![Star](https://img.shields.io/github/stars/OpenGVLab/GUI-Odyssey.svg?style=social&label=Star)](https://github.com/OpenGVLab/GUI-Odyssey)

- **WebSRC: A Dataset for Web-Based Structural Reading Comprehension**

  Shanghai Jiao Tong University, EMNLP, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2101.09465)
  [![Star](https://img.shields.io/github/stars/WebSRC/.svg?style=social&label=Star)](https://x-lance.github.io/WebSRC/)

- **WebArena: A Realistic Web Environment for Building Autonomous Agents**

  Carnegie Mellon University, ICLR, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.13854)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webarena.dev/)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**

  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

- **Mapping Natural Language Instructions to Mobile UI Action Sequences**

  Google Research, Mountain View, CA, 94043, ACL, 2020
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2005.03776)
  [![Star](https://img.shields.io/github/stars/master/seq2act.svg?style=social&label=Star)](https://github.com/google-research/google-research/tree/master/seq2act)

- **Grounding Open-Domain Instructions to Automate Web Support Tasks**

  Stanford University, NAACL, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2103.16057)
  [![Star](https://img.shields.io/github/stars/xnancy/russ.svg?style=social&label=Star)](https://github.com/xnancy/russ)

#### Detail Evaluation - Step-wise Evaluation

- **World of bits: an open-domain platform for web-based agents**

  OpenAI, ICML, 2017
  [![Paper](https://img.shields.io/badge/Paper-red)](http://proceedings.mlr.press/v70/shi17a)

- **Mind2Web: Towards a Generalist Agent for the Web**

  The Ohio State University, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.06070)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/Mind2Web)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/Mind2Web)

- **Mapping Natural Language Instructions to Mobile UI Action Sequences**

  Google Research, Mountain View, CA, 94043, ACL, 2020
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2005.03776)
  [![Star](https://img.shields.io/github/stars/master/seq2act.svg?style=social&label=Star)](https://github.com/google-research/google-research/tree/master/seq2act)

- **META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI**

  Shanghai Jiao Tong University, EMNLP, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2205.11029)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://x-lance.github.io/META-GUI-Leaderboard/)

- **AndroidInTheWild: A Large-Scale Dataset For Android Device Control**

  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

- **WebSRC: A Dataset for Web-Based Structural Reading Comprehension**

  Shanghai Jiao Tong University, EMNLP, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2101.09465)
  [![Star](https://img.shields.io/github/stars/WebSRC/.svg?style=social&label=Star)](https://x-lance.github.io/WebSRC/)

- **WebVLN: Vision-and-Language Navigation on Websites**

  Australian Institute for Machine Learning, The University of Adelaide, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.15820)
  [![Star](https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star)](https://github.com/WebVLN/WebVLN)

- **Room2Room: Enabling Life-Size Telepresence in a Projected Augmented Reality Environment**

  Microsoft, CSCW, 2016
  [![Paper](https://img.shields.io/badge/Paper-red)](https://dl.acm.org/doi/abs/10.1145/2818048.2819965)

- **OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web**

  Carnegie Mellon University, arXiv preprint arXiv:2402.17553, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.17553)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://huggingface.co/datasets/Writer/omniact)

#### Detail Evaluation - Set Inclusion Evaluation

- **Grounding Open-Domain Instructions to Automate Web Support Tasks**

  Stanford University, NAACL, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2103.16057)
  [![Star](https://img.shields.io/github/stars/xnancy/russ.svg?style=social&label=Star)](https://github.com/xnancy/russ)

- **META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI**

  Shanghai Jiao Tong University, EMNLP, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2205.11029)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://x-lance.github.io/META-GUI-Leaderboard/)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**

  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

- **WebQA: Multihop and Multimodal QA**

  Carnegie Mellon University, CVPR, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2109.00590)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webqna.github.io)

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents**

  Department of Computer Science, Princeton University, NeurIPS, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2207.01206)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://webshop-pnlp.github.io)

- **Sequence to sequence learning with neural networks**

  Google, NeurIPS, 2014
  [![Paper](https://img.shields.io/badge/Paper-red)](https://jeremy-su1.github.io/images/2024-07-08-Seq2Seq-Learning/1409.3215v3.pdf)

- **A Dataset for Interactive Vision Language Navigation with Unknown Command Feasibility**

  Boston University, ECCV, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2202.02312)

#### Detail Evaluation - Multi-dimensional Evaluation

- **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**

  The University of Hong Kong, arXiv preprint arXiv:2404.07972, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.07972)
  [![Star](https://img.shields.io/github/stars/xlang-ai/OSWorld.svg?style=social&label=Star)](https://github.com/xlang-ai/OSWorld)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://os-world.github.io)

- **WebVLN: Vision-and-Language Navigation on Websites**

  Australian Institute for Machine Learning, The University of Adelaide, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.15820)
  [![Star](https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star)](https://github.com/WebVLN/WebVLN)

- **ChatDev: Communicative Agents for Software Development**

  Tsinghua University, arXiv preprint arXiv:2307.07924, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.07924)
  [![Star](https://img.shields.io/github/stars/OpenBMB/ChatDev.svg?style=social&label=Star)](https://github.com/OpenBMB/ChatDev)

- **Online Adaptation of Language Models with a Memory of Amortized Contexts**

  KAIST, arXiv preprint arXiv:2403.04317, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2403.04317)
  [![Star](https://img.shields.io/github/stars/jihoontack/MAC.svg?style=social&label=Star)](https://github.com/jihoontack/MAC)

- **Voyager: An Open-Ended Embodied Agent with Large Language Models**

  NVIDIA, arXiv preprint arXiv:2305.16291, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.16291)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://voyager.minedojo.org)

- **GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices**

  OpenGVLab, Shanghai AI Laboratory, arXiv preprint arXiv:2406.08451, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.08451)
  [![Star](https://img.shields.io/github/stars/OpenGVLab/GUI-Odyssey.svg?style=social&label=Star)](https://github.com/OpenGVLab/GUI-Odyssey)

- **Using Large Language Models to Simulate Multiple Humans and Replicate Human Subject Studies**

  Olin College of Engineering, ICML, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2208.10264)

- **MemoChat: Tuning LLMs to Use Memos for Consistent Long-Range Open-Domain Conversation**

  University of Warwick, arXiv preprint arXiv:2308.08239, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2308.08239)
  [![Star](https://img.shields.io/github/stars/LuJunru/MemoChat.svg?style=social&label=Star)](https://github.com/LuJunru/MemoChat)

- **Secrets of RLHF in Large Language Models Part I: PPO**

  Fudan NLP Group, arXiv preprint arXiv:2307.04964, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.04964)
  [![Star](https://img.shields.io/github/stars/OpenLMLab/MOSS-RLHF.svg?style=social&label=Star)](https://github.com/OpenLMLab/MOSS-RLHF)

- **WebSRC: A Dataset for Web-Based Structural Reading Comprehension**

  Shanghai Jiao Tong University, EMNLP, 2021
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2101.09465)
  [![Star](https://img.shields.io/github/stars/WebSRC/.svg?style=social&label=Star)](https://x-lance.github.io/WebSRC/)

- **A Dataset for Interactive Vision Language Navigation with Unknown Command Feasibility**

  Boston University, ECCV, 2022
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2202.02312)

#### Human Evaluation

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **AndroidInTheWild: A Large-Scale Dataset For Android Device Control**

  DeepMind, NeurIPS, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2307.10088)

- **Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**

  Beijing Jiaotong University, arXiv preprint arXiv:2401.16158, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.16158)
  [![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)](https://github.com/X-PLUG/MobileAgent)

#### MLLM-based Evaluation

- **Gpt-4 technical report**

  OpenAI, arXiv preprint arXiv:2303.08774, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2303.08774)

- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks**

  Carnegie Mellon University, arXiv preprint arXiv:2401.13649, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13649)

- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models**

  Zhejiang University, arXiv preprint arXiv:2401.13919, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.13919)
  [![Star](https://img.shields.io/github/stars/MinorJerry/WebVoyager2023.svg?style=social&label=Star)](https://github.com/MinorJerry/WebVoyager2023)

- **GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents**

  Huazhong University of Science and Technology, arXiv preprint arXiv:2406.10819, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.10819)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://gui-world.github.io/)

### Section VI: Limitations
![alt text](./assets/limitations.png)

#### Unrealistic Environment and Dataset

- **OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments**

  The University of Hong Kong, arXiv preprint arXiv:2404.07972, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.07972)
  [![Star](https://img.shields.io/github/stars/xlang-ai/OSWorld.svg?style=social&label=Star)](https://github.com/xlang-ai/OSWorld)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://os-world.github.io)

- **Mapping Natural Language Instructions to Mobile UI Action Sequences**

  Google Research, Mountain View, CA, 94043, ACL, 2020
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2005.03776)
  [![Star](https://img.shields.io/github/stars/master/seq2act.svg?style=social&label=Star)](https://github.com/google-research/google-research/tree/master/seq2act)

- **AppAgent: Multimodal Agents as Smartphone Users**

  Tencent, arXiv preprint arXiv:2312.13771, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.13771)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://appagent-official.github.io/)

#### Insufficient Transferability

- **GPT-4V(ision) is a Generalist Web Agent, if Grounded**

  The Ohio State University, arXiv preprint arXiv:2401.01614, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.01614)
  [![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct.svg?style=social&label=Star)](https://github.com/OSU-NLP-Group/SeeAct)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://osu-nlp-group.github.io/SeeAct)

- **Visually Grounded Language Learning: a review of language games, datasets, tasks, and models**

  Heriot-Watt University, Journal of Artificial Intelligence Research, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2312.02431)

#### Limited Long-Sequence Decision-Making

- **Memorybank: Enhancing large language models with long-term memory**

  Sun Yat-Sen University, AAAI, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.10250)
  [![Star](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend.svg?style=social&label=Star)](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

- <b>Q*: Improving Multi-step Reasoning for LLMs with Deliberative Planning</b>

  Skywork AI, arXiv preprint arXiv:2406.14283, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2406.14283)

- **Reasoning with language model is planning with world model**

  UC San Diego, arXiv preprint arXiv:2305.14992, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2305.14992)
  [![Star](https://img.shields.io/github/stars/Ber666/llm-reasoners.svg?style=social&label=Star)](https://github.com/Ber666/llm-reasoners)

#### Heightened Security Concerns

- **LLaVA-phi: Efficient Multi-Modal Assistant with Small Language Model**

  Midea Group, arXiv preprint arXiv:2401.02330, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2401.02330)
  [![Star](https://img.shields.io/github/stars/zhuyiche/llava-phi.svg?style=social&label=Star)](https://github.com/zhuyiche/llava-phi)

- **Smoothquant: Accurate and efficient post-training quantization for large language models**

  Massachusetts Institute of Technology, ICML, 2023
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2211.10438)
  [![Star](https://img.shields.io/github/stars/mit-han-lab/smoothquant.svg?style=social&label=Star)](https://github.com/mit-han-lab/smoothquant)

- **AWQ: Activation-aware Weight Quantization for On-Device LLM Compression and Acceleration**

  MIT, Proceedings of Machine Learning and Systems, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2306.00978)

### Section VII: Future
![alt text](./assets/future.png)

#### From Individual to Systematic

- **LLM multi-agent systems: Challenges and open problems**

  University of California, Irvine, arXiv preprint arXiv:2402.03578, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.03578)

- **Combining multi-agent systems and Artificial Intelligence of Things: Technical challenges and gains**

  Belfort Montbeliard University of Technology, Internet of Things, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://www.sciencedirect.com/science/article/abs/pii/S2542660524003056)

- **Multi-agent systems in Peer-to-Peer energy trading: A comprehensive survey**

  University of Galway, Engineering Applications of Artificial Intelligence, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://www.sciencedirect.com/science/article/abs/pii/S0952197624000058)

#### From Virtual to Physical

- **A survey on robotics with foundation models: toward embodied ai**

  Midea Group, arXiv preprint arXiv:2402.02385, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2402.02385)

- **Embodied AI with Two Arms: Zero-shot Learning, Safety and Modularity**

  Google Deep Mind Robotics, arXiv preprint arXiv:2404.03570, 2024
  [![Paper](https://img.shields.io/badge/Paper-red)](https://arxiv.org/pdf/2404.03570)

## 🔍 Related Papers

We are committed to offering researchers the latest advancements in the field. By regularly reviewing and evaluating recent research studies, we ensure that the list of papers stays up-to-date.

<!-- <table style="width: 100%;">
  <tr>
    <td><strong>Date</strong></td>
    <td><strong>Paper</strong></td>
    <td><strong>Contribution</strong></td>
    <td><strong>Links</strong></td>
  </tr>
  <tr>
    <td rowspan="2" style="width: 15%;">2024-12</td>
    <td style="width: 55%;"><strong>Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction</strong></td>
    <td style="width: 15%;"><img src="https://img.shields.io/badge/Knowledge_Retention_Head-gold"></td>
    <td style="width: 15%;">
      <a href="https://aclanthology.org/2024.emnlp-main.190/"><img src="https://img.shields.io/badge/EMNLP-Paper-%23D2691E" alt="Paper Badge"></a>
      <a href="https://github.com/jinghan1he/SEEKR"><img src="https://img.shields.io/badge/GitHub-Code-brightgreen?logo=github" alt="Code Badge"></a>
    </td>
  </tr>
  <tr>
    <td colspan="3">
      • agent<br>
      • benchmark<br>
      • survey
    </td>
  </tr>
</table> -->

## 💪 How to Contribute

If you have a paper or are aware of relevant research that should be incorporated, please contribute via pull requests, issues, email, or other suitable methods.


## 📝 Citation

If you find this survey useful, please cite our paper:

```
@article{gao2024generalist,
  title={Generalist virtual agents: A survey on autonomous agents across digital platforms},
  author={Gao, Minghe and Bu, Wendong and Miao, Bingchen and Wu, Yang and Li, Yunfei and Li, Juncheng and Tang, Siliang and Wu, Qi and Zhuang, Yueting and Wang, Meng},
  journal={arXiv preprint arXiv:2411.10943},
  year={2024}
}
```
