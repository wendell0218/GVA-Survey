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

- **[December 10, 2024]** We have developed an agent that automatically collects and analyzes the latest papers in the GVA field. It will update the [Related Papers](#-related-papers) daily at 0:30 AM UTC+8.

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

⚠️ **The paper analysis may not be accurate and is for reference only!**

<table style="width: 100%;">
  <tr>
    <td><strong>Date</strong></td>
    <td><strong>Paper</strong></td>
    <td><strong>Environment</strong></td>
    <td><strong>Contribution</strong></td>
    <td><strong>Available Link</strong></td>
  </tr>
  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>SciMaster: Towards General-Purpose Scientific AI Agents, Part I. X-Master as Foundation: Can We Lead on Humanity's Last Exam?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.05241"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sjtu-sai-agents/X-Master"><img src="https://img.shields.io/github/stars/sjtu-sai-agents/X-Master.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Artificial Intelligence, Shanghai Jiao Tong University<br>
      • Agent Name: X-Master, Base Model: DeepSeek-R1-0528, Strategy: Prompt<br>
      • Agent Name: X-Masters, Base Model: DeepSeek-R1-0528, Strategy: scattered-and-stacked agentic workflow<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>WebSynthesis: World-Model-Guided MCTS for Efficient WebUI-Trajectory Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.04370"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/LucusFigoGao/WebSynthesis"><img src="https://img.shields.io/github/stars/LucusFigoGao/WebSynthesis.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Agent Name: WebSynthesis, Base Model: Qwen2.5-7B-Instruct, Strategy: SFT, Curriculum Learning, MCTS<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Hijacking JARVIS: Benchmarking Mobile GUI Agents against Unprivileged Third Parties</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.04227"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute for AI Industry Research (AIR), Tsinghua University<br>
      • Benchmark Name: AgentHazard, Task Number: 898, Dataset Source: ['human demonstration', 'LLM synthesis']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>MalVol-25: A Diverse, Labelled and Detailed Volatile Memory Dataset for Malware Detection and Response Testing and Validation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.03993"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://dx.doi.org/10.21227/kg5b-nf37"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cyber Security Research Centre, London Metropolitan University<br>
      • Benchmark Name: MalVol-25, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Learning Dark Souls Combat Through Pixel Input With Neuroevolution</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.03793"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ConnAALL/darksoulsapi"><img src="https://img.shields.io/github/stars/ConnAALL/darksoulsapi.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Computer Science Department, Connecticut College<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Less is More: Empowering GUI Agent with Context-Aware Simplification</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.03730"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/JiuTian-VL/SimpAgent"><img src="https://img.shields.io/github/stars/JiuTian-VL/SimpAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen<br>
      • Agent Name: SimpAgent, Base Model: Qwen2VL-2B, Strategy: Fine-tuning with masking-based element pruning and consistency-guided history compression<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>CodeAgents: A Token-Efficient Framework for Codified Multi-Agent Reasoning in LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.03254"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/CodifyingAgent-5A86"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: CodeAgents, Base Model: Gemini-2.0-Flash, Gemini-2.5-Flash, Gemini-2.5-Pro, GPT-4.1, LLaMA-4-Maverick, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Reinforcement Learning for Automated Cybersecurity Penetration Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.02969"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Artificial Intelligence and Big Data, GMV<br>
      • Agent Name: , Base Model: , Strategy: Reinforcement Learning (PPO)<br>
      • Benchmark Name: Simulated Environment, Task Number: , Dataset Source: procedurally generated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Establishing Best Practices for Building Rigorous Agentic Benchmarks</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.02825"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/uiuc-kang-lab/agentic-benchmarks"><img src="https://img.shields.io/github/stars/uiuc-kang-lab/agentic-benchmarks.svg?style=social&label=Star"></a><br>
      <a href="https://uiuc-kang-lab.github.io/agentic-benchmarks/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UIUC<br>
      • Paper Number: 97<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Meta SecAlign: A Secure Foundation LLM Against Prompt Injection Attacks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.02735"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/facebookresearch/Meta_SecAlign"><img src="https://img.shields.io/github/stars/facebookresearch/Meta_SecAlign.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meta FAIR, UC Berkeley<br>
      • Agent Name: Meta-SecAlign-8B, Base Model: Llama-3.1-8B-Instruct, Strategy: SecAlign++ (DPO, LoRA)<br>
      • Agent Name: Meta-SecAlign-70B, Base Model: Llama-3.3-70B-Instruct, Strategy: SecAlign++ (DPO, LoRA)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Decoupled Planning and Execution: A Hierarchical Reasoning Framework for Deep Search</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.02652"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ignorejjj/HiRA"><img src="https://img.shields.io/github/stars/ignorejjj/HiRA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: HiRA, Base Model: QwQ-32B, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>WebSailor: Navigating Super-human Reasoning for Web Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.02592"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Alibaba-NLP/WebAgent"><img src="https://img.shields.io/github/stars/Alibaba-NLP/WebAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tongyi Lab, Alibaba Group<br>
      • Agent Name: WebSailor, Base Model: Qwen-2.5-3B, Qwen-2.5-7B, Qwen-2.5-32B, Qwen-2.5-72B, Strategy: RFT, RL (DUPO)<br>
      • Benchmark Name: SailorFog-QA, Task Number: None, Dataset Source: Graph-based synthesis from web data<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Towards a Playground to Democratize Experimentation and Benchmarking of AI Agents for Network Troubleshooting</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.01997"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UESTC<br>
      • Agent Name: ReAct Agent, Base Model: DeepSeek-R1-0528, Strategy: ReAct<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.01006"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/GLM-4.1V-Thinking"><img src="https://img.shields.io/github/stars/THUDM/GLM-4.1V-Thinking.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhipu AI & Tsinghua University<br>
      • Agent Name: GLM-4.1V-Thinking, Base Model: GLM, Strategy: ['Supervised Fine-Tuning', 'Reinforcement Learning with Curriculum Sampling (RLCS)']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>Enhancing LLM Agent Safety via Causal Influence Prompting</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.00979"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Agent Name: CIP, Base Model: ['GPT-4o', 'Gemini-1.5-Pro', 'Claude-3.5-Sonnet', 'Qwen2.5-72B-Instruct'], Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2025</td>
    <td style="width: 40%;"><strong>WebArXiv: Evaluating Multimodal Agents on Time-Invariant arXiv Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2507.00938"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/74E4423BVNW"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Australian Artificial Intelligence Institute, Sydney, Australia<br>
      • Agent Name: Dynamic Reflective Agent, Base Model: , Strategy: Dynamic Reflection<br>
      • Benchmark Name: WebArXiv, Task Number: 275, Dataset Source: LLM synthesis, expert-guided refinement<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>A Different Approach to AI Safety: Proceedings from the Columbia Convening on Openness in Artificial Intelligence and AI Safety</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.22183"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Paper Number: 112<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Universal Retrieval for Multimodal Trajectory Modeling</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.22056"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: iMean AI<br>
      • Benchmark Name: GAE-Bench, Task Number: 12, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Advancements and Challenges in Continual Reinforcement Learning: A Comprehensive Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.21899"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Monash University<br>
      • Paper Number: 360<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>A Survey of Continual Reinforcement Learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.21872"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Southwestern University of Finance and Economics<br>
      • Paper Number: 167<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>MemBench: Towards More Comprehensive Evaluation on the Memory of LLM-based Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.21605"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/import-myself/Membench"><img src="https://img.shields.io/github/stars/import-myself/Membench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Renmin University of China<br>
      • Paper Number: 48<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Bench to the Future: A Pastcasting Benchmark for Forecasting Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.21558"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FutureSearch<br>
      • Benchmark Name: Bench To the Future (BTF), Task Number: 299, Dataset Source: web pages<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Mobile-R1: Towards Interactive Reinforcement Learning for VLM-Based Mobile Agent via Task-Level Rewards</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.20332"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/mobile-r1/mobile-r1"><img src="https://img.shields.io/github/stars/mobile-r1/mobile-r1.svg?style=social&label=Star"></a><br>
      <a href="https://mobile-r1.github.io/Mobile-R1/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Taobao & Tmall Group of Alibaba<br>
      • Agent Name: Mobile-R1, Base Model: Qwen2.5-VL-3B, Strategy: GRPO<br>
      • Benchmark Name: Mobile Agent Benchmark, Task Number: 500, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Doc2Agent: Scalable Generation of Tool-Using Agents from API Documentation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.19998"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/coolkillercat/Doc2Agent"><img src="https://img.shields.io/github/stars/coolkillercat/Doc2Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Brandeis University<br>
      • Agent Name: Doc2Agent, Base Model: GPT-4, Strategy: Iterative refinement<br>
      • Benchmark Name: WebArena, Task Number: 174, Dataset Source: real-world API documentation and research APIs<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>From Reproduction to Replication: Evaluating Research Agents with Progressive Code Masking</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.19724"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/j1mk1m/AutoExperiment"><img src="https://img.shields.io/github/stars/j1mk1m/AutoExperiment.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: AUTOEXPERIMENT, Task Number: 85, Dataset Source: peer-reviewed research papers and their publicly released codebases<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Skywork-SWE: Unveiling Data Scaling Laws for Software Engineering in LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.19290"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://quixotic-sting-239.notion.site/eb17f379610040ceb54da5d5d24065bd"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Skywork AI, Kunlun Inc<br>
      • Agent Name: Skywork-SWE-32B, Base Model: Qwen-2.5-Coder-32B-Instruct, Strategy: SFT<br>
      • Benchmark Name: Skywork-SWE, Task Number: 10169, Dataset Source: GitHub repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>From Web Search towards Agentic Deep Research: Incentivizing Search with Reasoning Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.18959"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/DavidZWZ/Awesome-Deep-Research"><img src="https://img.shields.io/github/stars/DavidZWZ/Awesome-Deep-Research.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Chicago<br>
      • Paper Number: 91<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Deep Research Agents: A Systematic Examination And Roadmap</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.18096"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ai-agents-2030/awesome-deep-research-agent"><img src="https://img.shields.io/github/stars/ai-agents-2030/awesome-deep-research-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Liverpool<br>
      • Paper Number: 121<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Graphs Meet AI Agents: Taxonomy, Progress, and Future Opportunities</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.18019"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Paper Number: 239<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Learning, Reasoning, Refinement: A Framework for Kahneman's Dual-System Intelligence in GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17913"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: College of Intelligent Robotics and Advanced Manufacturing, Fudan University<br>
      • Agent Name: CogniGUI, Base Model: Qwen2.5VL-3B, Strategy: ['LoRA', 'GRPO']<br>
      • Benchmark Name: ScreenSeek, Task Number: >1000, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Towards Robust Fact-Checking: A Multi-Agent System with Advanced Evidence Retrieval</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17878"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HySonLab/FactAgent"><img src="https://img.shields.io/github/stars/HySonLab/FactAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Economics University, Vietnam<br>
      • Agent Name: FactAgent, Base Model: ['GPT-4o-mini', 'Llama-3.2-1B', 'Qwen-2.5-3B', 'Gemini-1.5-flash'], Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Toward Autonomous UI Exploration: The UIExplorer Benchmark</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17779"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UiPath<br>
      • Agent Name: UIExplore-AlGo, Base Model: gpt-4o, claude-3-5-sonnet, Strategy: Prompt<br>
      • Benchmark Name: UIEXPLORE-BENCH, Task Number: None, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Beyond Syntax: Action Semantics Learning for App Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17697"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Oxford<br>
      • Agent Name: Qwen2.5-7B-Instruct-ASL, Base Model: Qwen2.5-7B-Instruct, Strategy: ASL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17539"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Monash University<br>
      • Agent Name: MAdroid, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Context manipulation attacks : Web agents are susceptible to corrupted memory</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.17318"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University<br>
      • Benchmark Name: Plan Injection Benchmark, Task Number: 60, Dataset Source: LLM synthesis<br>
      • Benchmark Name: WebVoyager-Privacy Benchmark, Task Number: 45, Dataset Source: Based on WebVoyager<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AI-Driven Tools in Modern Software Quality Assurance: An Assessment of Benefits, Challenges, and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.16586"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/igor-pysmennyi-kpi/qa-ai-overview-paper-2025"><img src="https://img.shields.io/github/stars/igor-pysmennyi-kpi/qa-ai-overview-paper-2025.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Technical University of Ukraine "Igor Sikorsky Kyiv Polytechnic Institute"<br>
      • Paper Number: 33<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>OSWorld-Human: Benchmarking the Efficiency of Computer-Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.16042"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, San Diego<br>
      • Benchmark Name: OSWorld-Human, Task Number: 369, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15841"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Singapore-MIT Alliance for Research and Technology Centre<br>
      • Agent Name: MEM1, Base Model: Qwen2.5-7B Base, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>OAgents: An Empirical Study of Building Effective Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15741"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OPPO-PersonalAI/OAgents"><img src="https://img.shields.io/github/stars/OPPO-PersonalAI/OAgents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OPPO AI Agent Team<br>
      • Agent Name: OAgents, Base Model: ['Claude-3-7', 'GPT-4o', 'GPT-4.1', 'OpenAI-o1', 'DeepSeek-R1', 'Gemini-2.5'], Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Embodied Web Agents: Bridging Physical-Digital Realms for Integrated Agent Intelligence</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15677"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://embodied-web-agent.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Los Angeles<br>
      • Benchmark Name: EMBODIED WEBAGENTS Benchmark, Task Number: 1523, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Leaky Thoughts: Large Reasoning Models Are Not Private Thinkers</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15674"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/parameterlab/leaky_thoughts"><img src="https://img.shields.io/github/stars/parameterlab/leaky_thoughts.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Parameter Lab, Data and Web Science Group, University of Mannheim<br>
      • Benchmark Name: AirGapAgent-R, Task Number: None, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>RAS-Eval: A Comprehensive Benchmark for Security Evaluation of LLM Agents in Real-World Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15253"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lanzer-tree/RAS-Eval"><img src="https://img.shields.io/github/stars/lanzer-tree/RAS-Eval.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Benchmark Name: RAS-Eval, Task Number: 3802, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>From LLMs to MLLMs to Agents: A Survey of Emerging Paradigms in Jailbreak Attacks and Defenses within LLM Ecosystem</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.15170"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Software, Henan University<br>
      • Paper Number: 156<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>OS-Harm: A Benchmark for Measuring Safety of Computer Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14866"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tml-epfl/os-harm"><img src="https://img.shields.io/github/stars/tml-epfl/os-harm.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: EPFL<br>
      • Benchmark Name: OS-HARM, Task Number: 150, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Cost-Efficient Serving of LLM Agents via Test-Time Plan Caching</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14852"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: Agentic Plan Caching, Base Model: GPT-4o, LLaMa-3.2-8B, GPT-4o-mini, Strategy: plan caching<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Unified Software Engineering agent as AI Software Engineer</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14683"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: USEagent, Base Model: Claude 3.5 Sonnet v2, Strategy: Prompt<br>
      • Benchmark Name: USEbench, Task Number: 1271, Dataset Source: Existing benchmarks (SWE-bench, SWT-bench, REPOCOD)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>GUI-Robust: A Comprehensive Dataset for Testing GUI Agent Robustness in Real-World Anomalies</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14477"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/chessbean1/GUI-Robust"><img src="https://img.shields.io/github/stars/chessbean1/GUI-Robust.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Benchmark Name: GUI-Robust, Task Number: 5318, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AgentSynth: Scalable Task Generation for Generalist Computer-Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14205"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sunblaze-ucb/AgentSynth"><img src="https://img.shields.io/github/stars/sunblaze-ucb/AgentSynth.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Berkeley<br>
      • Benchmark Name: AgentSynth, Task Number: 6000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>FormGym: Doing Paperwork with Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14079"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Agent Name: FieldFinder, Base Model: Florence 2 Large, Strategy: Fine-tuning<br>
      • Benchmark Name: FormGym, Task Number: 3, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Discovering Temporal Structure: An Overview of Hierarchical Reinforcement Learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.14045"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Mila, McGill University<br>
      • Paper Number: 255<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>How Does LLM Reasoning Work for Code? A Survey and a Call to Action</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.13932"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Paper Number: 127<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Personalized Constitutionally-Aligned Agentic Superego: Secure AI Behavior Aligned to Diverse Human Values</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.13774"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="http://www.Creed.Space"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Gloucestershire<br>
      • Agent Name: Personalized Constitutionally-Aligned Agentic Superego, Base Model: GPT-3.5-Turbo, Gemini 2.5 Flash, GPT-4o, Claude Sonnet 4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>We Should Identify and Mitigate Third-Party Safety Risks in MCP-Powered Agent Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.13666"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/littlelittlenine/SafeMCP.git"><img src="https://img.shields.io/github/stars/littlelittlenine/SafeMCP.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Benchmark Name: SAFEMCP, Task Number: 10, Dataset Source: AgentGym<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>xbench: Tracking Agents Productivity Scaling with Profession-Aligned Real-World Evaluations</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.13651"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://xbench.org/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: nan<br>
      • Benchmark Name: xbench: Recruitment, Task Number: 50, Dataset Source: real-world headhunting business scenarios<br>
      • Benchmark Name: xbench: Marketing, Task Number: 50, Dataset Source: real client demands<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Towards Pervasive Distributed Agentic Generative AI -- A State of The Art</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.13324"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Turin, Italy<br>
      • Paper Number: 145<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Scaling Test-time Compute for LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.12928"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OPPO-PersonalAI/OAgents"><img src="https://img.shields.io/github/stars/OPPO-PersonalAI/OAgents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OPPO AI Agent Team<br>
      • Agent Name: ATTS, Base Model: GPT-4.1, Strategy: Test-time scaling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>SoK: The Privacy Paradox of Large Language Models: Advancements, Privacy Risks, and Mitigation</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.12699"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: CSIRO’s Data61<br>
      • Paper Number: 152<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AgentOrchestra: A Hierarchical Multi-Agent Framework for General-Purpose Task Solving</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.12508"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SkyworkAI/DeepResearchAgent"><img src="https://img.shields.io/github/stars/SkyworkAI/DeepResearchAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Skywork AI<br>
      • Agent Name: AgentOrchestra, Base Model: ['claude-3.7-sonnet', 'gpt-4.1', 'gemini-2.5-pro-preview-05-06', 'o3'], Strategy: ['Prompt', 'hierarchical multi-agent framework']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Cloud Infrastructure Management in the Age of AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.12270"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Michigan<br>
      • Agent Name: SDK agent, Base Model: Azure Copilot, Strategy: None<br>
      • Agent Name: CLI agent, Base Model: Azure Copilot, Strategy: None<br>
      • Agent Name: IaC agent, Base Model: Azure Copilot, Strategy: None<br>
      • Agent Name: ClickOps agent, Base Model: GPT-4o, Strategy: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>The Amazon Nova Family of Models: Technical Report and Model Card</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.12103"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/amazon-agi"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Amazon Artificial General Intelligence<br>
      • Agent Name: Amazon Nova Pro, Base Model: Transformer, Strategy: ['SFT', 'DPO', 'PPO', 'Prompt']<br>
      • Agent Name: Amazon Nova Lite, Base Model: Transformer, Strategy: ['SFT', 'DPO', 'PPO', 'Prompt']<br>
      • Agent Name: Amazon Nova Micro, Base Model: Transformer, Strategy: ['SFT', 'DPO', 'PPO', 'Prompt']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.11763"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Ayanami0730/deep_research_bench"><img src="https://img.shields.io/github/stars/Ayanami0730/deep_research_bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Benchmark Name: DeepResearch Bench, Task Number: 100, Dataset Source: real-world user queries, human/expert-crafted<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>LLM-as-a-Judge for Reference-less Automatic Code Validation and Refinement for Natural Language to Bash in IT Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.11237"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/IBM/nl2bash-eabench/tree/main"><img src="https://img.shields.io/github/stars/tree/main.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IBM Research<br>
      • Agent Name: Self-Reflection agent, Base Model: ['Llama-3.3-70B', 'Mistral-large', 'GPT-4o'], Strategy: ['Self-reflection', 'ReAct framework']<br>
      • Agent Name: Reflection agent with dedicated Evaluator, Base Model: ['Llama-3.3-70B', 'Mistral-large', 'GPT-4o'], Strategy: ['Reflection with dedicated evaluator', 'ReAct framework']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>GUIRoboTron-Speech: Towards Automated GUI Agents Based on Speech Instructions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.11127"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/GUIRoboTron/GUIRoboTron-Speech"><img src="https://img.shields.io/github/stars/GUIRoboTron/GUIRoboTron-Speech.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meituan, Zhejiang University<br>
      • Agent Name: GUIRoboTron-Speech, Base Model: Qwen-Omni-7B, Strategy: progressive grounding and planning training, mixed-instruction training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Evolutionary Perspectives on the Evaluation of LLM-Based AI Agents: A Comprehensive Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.11102"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Paper Number: 201<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Code Researcher: Deep Research Agent for Large Systems Code and Commit History</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.11060"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research<br>
      • Agent Name: Code Researcher, Base Model: ['GPT-4o', 'o1'], Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Build the web for agents, not agents for the web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.10953"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McGill University<br>
      • Benchmark Name: Agentic Web Interface (AWI), Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Specification and Evaluation of Multi-Agent LLM Systems -- Prototype and Cybersecurity Applications</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.10467"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/fhaer/multi-agent-llm-system"><img src="https://img.shields.io/github/stars/fhaer/multi-agent-llm-system.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Applied Sciences Northwestern Switzerland<br>
      • Agent Name: Security Q&A Agent, Base Model: OpenAI GPT-4o, OpenAI o1-preview, DeepSeek R1, DeepSeek R1 Distilled Llama 8B, Strategy: Prompting, Reasoning Chains<br>
      • Agent Name: Network Security Agent, Base Model: OpenAI GPT-4o, OpenAI o1-preview, DeepSeek R1, DeepSeek R1 Distilled Llama 8B, Strategy: Prompting, Augmentation, Constraints<br>
      • Agent Name: Server Security Agent, Base Model: OpenAI GPT-4o, OpenAI o1-preview, DeepSeek R1, DeepSeek R1 Distilled Llama 8B, Strategy: Prompting, Reasoning Chains<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Reasoning RAG via System 1 or System 2: A Survey on Reasoning Agentic Retrieval-Augmented Generation for Industry Challenges</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.10408"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications<br>
      • Paper Number: 59<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Mirage-1: Augmenting and Updating GUI Agent with Hierarchical Multimodal Skills</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.10387"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://cybertronagent.github.io/Mirage-1.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen<br>
      • Agent Name: Mirage-1, Base Model: GPT-4o, Strategy: Hierarchical Multimodal Skills (HMS) module and Skill-Augmented Monte Carlo Tree Search (SA-MCTS) algorithm<br>
      • Benchmark Name: AndroidLH, Task Number: 30, Dataset Source: GPT-4o generated tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>TaskCraft: Automated Generation of Agentic Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="http://arxiv.org/pdf/2506.10055"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OPPO-PersonalAI/TaskCraft"><img src="https://img.shields.io/github/stars/OPPO-PersonalAI/TaskCraft.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OPPO AI Agent Team<br>
      • Benchmark Name: TaskCraft, Task Number: 36000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Application-Driven Value Alignment in Agentic AI Systems: Survey and Perspectives</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.09656"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Business, Hunan University, Changsha, Hunan, China<br>
      • Paper Number: 372<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>LPO: Towards Accurate GUI Agent Interaction via Location Preference Optimization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.09373"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AIDC-AI/LPO"><img src="https://img.shields.io/github/stars/AIDC-AI/LPO.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong University of Science and Technology<br>
      • Agent Name: LPO, Base Model: Ovis2 8B, Strategy: Location Preference Optimization<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>ALE-Bench: A Benchmark for Long-Horizon Objective-Driven Algorithm Engineering</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.09050"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SakanaAI/ALE-Bench"><img src="https://img.shields.io/github/stars/SakanaAI/ALE-Bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sakana AI, Japan<br>
      • Agent Name: ALE-Agent, Base Model: Gemini 2.5 Pro, Strategy: Best-first search with domain knowledge and diversity-oriented solution search<br>
      • Benchmark Name: ALE-Bench, Task Number: 40, Dataset Source: AtCoder Heuristic Contest problems<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Atomic-to-Compositional Generalization for Mobile Agents with A New Benchmark and Scheduling System</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08972"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ui-nexus.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: AGENT-NEXUS, Base Model: GPT-4o, Strategy: Scheduling System<br>
      • Benchmark Name: UI-NEXUS, Task Number: 100, Dataset Source: human refinement<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>What Limits Virtual Agent Application? OmniBench: A Scalable Multi-Dimensional Benchmark for Essential Virtual Agent Capabilities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08933"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://omni-bench.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: Omni-OS-Atlas-Base-4B, Base Model: OS-Atlas-Base-4B, Strategy: SFT<br>
      • Agent Name: Omni-UGround-V1-7B, Base Model: UGround-V1-7B, Strategy: SFT<br>
      • Benchmark Name: OmniBench, Task Number: 36076, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Measuring Data Science Automation: A Survey of Evaluation Tools for AI Assistants and Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08800"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Leverhulme Centre for the Future of Intelligence, University of Cambridge, UK<br>
      • Paper Number: 62<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Your Agent Can Defend Itself against Backdoor Attacks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08336"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stony Brook University<br>
      • Agent Name: ReAgent, Base Model: , Strategy: Two-level consistency check<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>EconWebArena: Benchmarking Autonomous Agents on Economic Tasks in Realistic Web Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08136"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ServiceNow/BrowserGym"><img src="https://img.shields.io/github/stars/ServiceNow/BrowserGym.svg?style=social&label=Star"></a><br>
      <a href="https://econwebarena.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Institute of Technology<br>
      • Benchmark Name: EconWebArena, Task Number: 360, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>UAVs Meet Agentic AI: A Multidomain Survey of Autonomous Aerial Intelligence and Agentic UAVs</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08045"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University, Department of Biological and Environmental Engineering, Ithaca, NY 14853, USA<br>
      • Paper Number: 306<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>GUI-Reflection: Empowering Multimodal GUI Models with Self-Reflection Behavior</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.08012"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://penghao-wu.github.io/GUI_Reflection/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: S-Lab, Nanyang Technological University<br>
      • Agent Name: GUI-Reflection, Base Model: InternVL2.5-8B, Strategy: SFT, Reflection Tuning<br>
      • Benchmark Name: GUI-Reflection Task Suite, Task Number: 3, Dataset Source: constructed from existing datasets (e.g., AndroidControl, GUI-Odyssey)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>-Bench: Evaluating Conversational Agents in a Dual-Control Environment</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07982"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sierra-research/tau2-bench"><img src="https://img.shields.io/github/stars/sierra-research/tau2-bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sierra<br>
      • Benchmark Name: τ2-bench, Task Number: 2285, Dataset Source: programmatic generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Thinking vs. Doing: Agents that Reason by Scaling Test-Time Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07976"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/test-time-interaction/TTI"><img src="https://img.shields.io/github/stars/test-time-interaction/TTI.svg?style=social&label=Star"></a><br>
      <a href="https://test-time-interaction.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: TTI (Test-Time Interaction), Base Model: Gemma 3 12B, Strategy: Curriculum-Based Online RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>MCPWorld: A Unified Benchmarking Testbed for API, GUI, and Hybrid Computer Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07672"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SAAgent/MCPWorld"><img src="https://img.shields.io/github/stars/SAAgent/MCPWorld.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications<br>
      • Benchmark Name: MCPWorld, Task Number: 201, Dataset Source: realistic user scenarios<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Beyond the Sentence: A Survey on Context-Aware Machine Translation with Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07583"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Engineering, Indian Institute of Technology Patna, India<br>
      • Paper Number: 50<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>SAFEFLOW: A Principled Protocol for Trustworthy and Transactional Autonomous Agent Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07564"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Texas A&M University<br>
      • Agent Name: SAFEFLOW, Base Model: Not specified in the abstract, but mentioned as LLM/VLM-based, Strategy: Fine-grained information flow control, transactional logging, and secure coordination<br>
      • Benchmark Name: SAFEFLOW BENCH, Task Number: 332 (MTST) + 25 (CART), Dataset Source: Hybrid manual-automated generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Mind the Web: The Security of Web Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.07153"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ben-Gurion University of the Negev, Israel<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Contextual Experience Replay for Self-Improvement of Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06698"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University<br>
      • Agent Name: CER, Base Model: GPT-4o, Strategy: Contextual Experience Replay<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AI Simulation by Digital Twins: Systematic Survey, Reference Framework, and Mapping to a Standardized Architecture</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06580"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McMaster University, Hamilton, Canada<br>
      • Paper Number: 22<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>KramaBench: A Benchmark for AI Systems on Data-to-Insight Pipelines over Data Lakes</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06541"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/mitdbg/KramaBench"><img src="https://img.shields.io/github/stars/mitdbg/KramaBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MIT CSAIL<br>
      • Benchmark Name: KRAMA BENCH, Task Number: 104, Dataset Source: manually-curated real-world data science pipelines<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Deep Research Bench: Evaluating AI Web Research Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06287"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://drb.futuresearch.ai/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FutureSearch*<br>
      • Benchmark Name: Deep Research Bench, Task Number: 89, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Reinforcement Learning Optimization for Large-Scale Learning: An Efficient and User-Friendly Scaling Library</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06122"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/alibaba/ROLL"><img src="https://img.shields.io/github/stars/alibaba/ROLL.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Alibaba<br>
      • Agent Name: Qwen2.5-0.5B-Instruct, Base Model: Qwen2.5-0.5B-Instruct, Strategy: PPO with REINFORCE returns<br>
      • Benchmark Name: WebShop, Task Number: not specified, Dataset Source: not specified<br>
      • Benchmark Name: Sokoban, Task Number: not specified, Dataset Source: not specified<br>
      • Benchmark Name: FrozenLake, Task Number: not specified, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AgentSwift: Efficient LLM Agent Design via Value-guided Hierarchical Search</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.06017"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Ericccc02/AgentSwift"><img src="https://img.shields.io/github/stars/Ericccc02/AgentSwift.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: AgentSwift, Base Model: , Strategy: Value-guided Hierarchical Search<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.05364"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Visaze LLC<br>
      • Paper Number: 56<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>LLM-Guided Scenario-based GUI Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.05079"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://sites.google.com/view/scengen"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Technical University of Munich, Germany<br>
      • Agent Name: SCENGEN, Base Model: GPT-4V, Strategy: Multi-agent collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>From Standalone LLMs to Integrated Intelligence: A Survey of Compound Al Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.04565"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: New Jersey Institute of Technology, USA<br>
      • Agent Name: Voyager, Base Model: GPT-4, Strategy: Prompt<br>
      • Agent Name: OSAgent, Base Model: GPT-based, Strategy: API Calls<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>MedAgentGym: Training LLM Agents for Code-Based Medical Reasoning at Scale</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.04405"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/wshi83/MedAgentGym"><img src="https://img.shields.io/github/stars/wshi83/MedAgentGym.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/MedAgentGym"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Emory University<br>
      • Agent Name: Med-Copilot, Base Model: Qwen2.5-7B-Instruct, Qwen2.5-14B-Instruct, Strategy: SFT, DPO<br>
      • Benchmark Name: MedAgentGym, Task Number: 72413, Dataset Source: real-world biomedical scenarios<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.04287"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST AI<br>
      • Agent Name: EXIF, Base Model: GPT-4o, Qwen2.5-7B, Llama3.1-8B, Strategy: Exploration-first strategy with iterative feedback<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.04133"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Vector Institute, Toronto, Canada<br>
      • Paper Number: 180<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>PulseReddit: A Novel Reddit Dataset for Benchmarking MAS in High-Frequency Cryptocurrency Trading</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.03861"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/7huahua/RedditDataset"><img src="https://img.shields.io/github/stars/7huahua/RedditDataset.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute of Science Tokyo<br>
      • Benchmark Name: PulseReddit, Task Number: , Dataset Source: Reddit discussion data synchronized with high-frequency cryptocurrency market statistics<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Go-Browse: Training Web Agents with Structured Exploration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.03533"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ApGa/Go-Browse"><img src="https://img.shields.io/github/stars/ApGa/Go-Browse.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: Go-Browse, Base Model: Claude-3.7-Sonnet, GPT-4o, Qwen-2.5-7B-Instruct, Strategy: Supervised Fine-Tuning (SFT)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>GUI-Actor: Coordinate-Free Visual Grounding for GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.03143"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://aka.ms/GUI-Actor"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: GUI-Actor, Base Model: Qwen2-VL-7B-Instruct, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>DPO Learning with LLMs-Judge Signal for Computer Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.03095"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Intel<br>
      • Agent Name: UI-TARS-2B, Base Model: 2B-model, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Coding Agents with Multimodal Browsing are Generalist Problem Solvers</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.03011"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/adityasoni9998/OpenHands-Versa"><img src="https://img.shields.io/github/stars/adityasoni9998/OpenHands-Versa.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: OpenHands-Versa, Base Model: claude-3-7-sonnet-20250219, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>It's the Thought that Counts: Evaluating the Attempts of Frontier LLMs to Persuade on Harmful Topics</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02873"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AlignmentResearch/AttemptPersuadeEval"><img src="https://img.shields.io/github/stars/AlignmentResearch/AttemptPersuadeEval.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FAR.AI<br>
      • Benchmark Name: Attempt to Persuade Eval (APE), Task Number: 600, Dataset Source: automatically generated and manually validated topics<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Surfer-H Meets Holo1: Cost-Efficient Web Agent Powered by Open Weights</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02865"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://www.surferh.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: H Company<br>
      • Agent Name: Surfer-H, Base Model: Holo1, Strategy: Fine-tuning<br>
      • Benchmark Name: WebClick, Task Number: 1639, Dataset Source: human interactions with the Web, human interactions with calendar interfaces, and data collected by agents solving tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>DeepShop: A Benchmark for Deep Research Shopping Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02839"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/DeepShop-E4DF"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Amsterdam<br>
      • Benchmark Name: DeepShop, Task Number: 600, Dataset Source: seed queries evolved through GPT-4o<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>VerificAgent: Integrating Expert Knowledge and Fact-Checked Memory for Robust Domain-Specific Task Planning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02539"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: VERIFIC AGENT, Base Model: gpt-4o-2024-05-13, Strategy: Expert-curated seed of domain knowledge, iterative memory refinement, and post-hoc fact-checking<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>VPI-Bench: Visual Prompt Injection Attacks for Computer-Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02456"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/cua-framework/agents"><img src="https://img.shields.io/github/stars/cua-framework/agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: Sonnet-3.5, Base Model: Claude-3.7-Sonnet, Strategy: Fine-tuning<br>
      • Agent Name: Sonnet-3.7, Base Model: Claude-3.7-Sonnet, Strategy: <br>
      • Benchmark Name: VPI-Bench, Task Number: 306, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Reflection-Based Memory For Web navigation Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02158"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UIUC<br>
      • Agent Name: Reflection-Augmented Planning (ReAP), Base Model: gpt-4o-2024-08-06, Strategy: Reflection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>The Measurement Imbalance in Agentic AI Evaluation Undermines Industry Productivity Claims</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02064"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Paper Number: 84<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Will Agents Replace Us? Perceptions of Autonomous Multi-Agent AI</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02055"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/nkkko/agent-perceptions"><img src="https://img.shields.io/github/stars/nkkko/agent-perceptions.svg?style=social&label=Star"></a><br>
      <a href="https://v0-audience-mindset-probe.vercel.app/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Faculty of Science, University of Split, Croatia<br>
      • Paper Number: 40<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>EvoGit: Decentralized Code Evolution via Git-Based Multi-Agent Collaboration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.02049"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/BillHuang2001/evogit"><img src="https://img.shields.io/github/stars/BillHuang2001/evogit.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Data Science and Artificial Intelligence, The Hong Kong Polytechnic University<br>
      • Agent Name: EvoGit, Base Model: Large Language Model, Strategy: Mutation and Crossover<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>WebChoreArena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01952"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://webchorearena.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Tokyo<br>
      • Benchmark Name: WebChoreArena, Task Number: 532, Dataset Source: human-curated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Self-Challenging Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01716"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: Self-Challenging Agent (SCA), Base Model: Llama-3.1-8B-Instruct, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>MLA-Trust: Benchmarking Trustworthiness of Multimodal LLM Agents in GUI Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01616"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://mla-trust.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science & Technology, Institute for AI, BNRist Center, THBI Lab, Tsinghua-Bosch Joint Center for ML, Tsinghua University, Beijing, China<br>
      • Benchmark Name: MLA-Trust, Task Number: 34, Dataset Source: curated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>FormFactory: An Interactive Benchmarking Suite for Multimodal Form-Filling Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://formfactory-ai.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Benchmark Name: FormFactory, Task Number: 20, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>PGPO: Enhancing Agent Reasoning via Pseudocode-style Planning Guided Preference Optimization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01475"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zouyingcao/PGPO"><img src="https://img.shields.io/github/stars/zouyingcao/PGPO.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: PGPO, Base Model: , Strategy: Pseudocode-style Planning Guided Preference Optimization<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AgentCPM-GUI: Building Mobile-Use Agents with Reinforcement Fine-Tuning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.01391"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenBMB/AgentCPM-GUI"><img src="https://img.shields.io/github/stars/OpenBMB/AgentCPM-GUI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: AgentCPM-GUI, Base Model: MiniCPM-V, Strategy: ['SFT', 'RFT']<br>
      • Benchmark Name: CAGUI, Task Number: 600, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Browser Fingerprinting Using WebAssembly</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00719"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ben-Gurion University of the Negev<br>
      • Paper Number: 58<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>AgentAuditor: Human-Level Safety and Security Evaluation for LLM Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00641"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: New York University Abu Dhabi<br>
      • Benchmark Name: ASSEBench, Task Number: 2293, Dataset Source: human-computer collaborative classification<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>RiOSWorld: Benchmarking the Risk of Multimodal Computer-Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00618"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Artificial Intelligence Laboratory<br>
      • Benchmark Name: RiOSWorld, Task Number: 492, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Temac: Multi-Agent Collaboration for Automated Web GUI Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://drive.google.com/drive/folders/12vk2qz8EQa3P8kZ7IdPNY3hh9oBV-E?usp=sharing"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Key Lab of HCST (PKU), MOE; SCS; Peking University, Beijing, China<br>
      • Agent Name: Temac, Base Model: GPT-4o, Strategy: LLM-based multi-agent collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Dyna-Think: Synergizing Reasoning, Acting, and World Model Simulation in AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00320"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Agent Name: Dyna-Think, Base Model: Qwen2.5-32B-Instruct, Strategy: Dyna-Think Imitation Learning (DIT), Dyna-Think Dyna Training (DDT)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2025</td>
    <td style="width: 40%;"><strong>Literature Review Of Multi-Agent Debate For Problem-Solving</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2506.00066"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Göttingen<br>
      • Paper Number: 87<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Open CaptchaWorld: A Comprehensive Web-based Platform for Testing and Benchmarking Multimodal LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.24878"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/spaces/OpenCaptchaWorld/platform"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: VILA Lab, MBZUAI<br>
      • Benchmark Name: Open CaptchaWorld, Task Number: 20, Dataset Source: human designers or GPT-4o generated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>VideoCAD: A Large-Scale Video Dataset for Learning UI Interactions and 3D Reasoning from CAD Software</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.24838"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/BrandonMan123/VideoCAD"><img src="https://img.shields.io/github/stars/BrandonMan123/VideoCAD.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Mechanical Engineering, Massachusetts Institute of Technology<br>
      • Agent Name: VideoCADFormer, Base Model: , Strategy: Behavioral Cloning<br>
      • Benchmark Name: VideoCAD, Task Number: , Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>OWL: Optimized Workforce Learning for General Multi-Agent Assistance in Real-World Task Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23885"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/camel-ai/owl"><img src="https://img.shields.io/github/stars/camel-ai/owl.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Agent Name: WORKFORCE, Base Model: GPT-4o / Claude-3.7-Sonnet, Strategy: Supervised Fine-Tuning (SFT), Reinforcement Learning (DPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ZeroGUI: Automating Online GUI Learning at Zero Human Cost</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23762"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenGVLab/ZeroGUI"><img src="https://img.shields.io/github/stars/OpenGVLab/ZeroGUI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Artificial Intelligence Laboratory<br>
      • Agent Name: ZeroGUI, Base Model: UI-TARS-7B-DPO and Aguvis-7B, Strategy: Two-stage Online Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MCP Safety Training: Learning to Refuse Falsely Benign MCP Exploits using Improved Preference Alignment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23634"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Leidos<br>
      • Benchmark Name: MCP-FBAs, Task Number: 115 FBA testing samples, 171 TB testing samples, Dataset Source: derived from Common Vulnerabilities and Exposures (CVEs) catalog<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MAPLE: A Mobile Agent with Persistent Finite State Machines for Structured Task Reasoning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23596"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Software PErformance, Analysis, and Reliability (SPEAR) lab, Concordia University, Canada<br>
      • Agent Name: MAPLE, Base Model: GPT-4o-2024-11-20, Claude-3-5-sonnet-20241022, Gemini-1.5-Pro, Strategy: Finite State Machine (FSM) modeling, LLM-as-judges for plan selection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>TRAP: Targeted Redirecting of Agentic Preferences</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23518"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: TRAP, Base Model: CLIP, Stable Diffusion, Strategy: Semantic Injection via Diffusion Models<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Socratic-PRMBench: Benchmarking Process Reward Models with Systematic Reasoning Patterns</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.23474"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Xiang-Li-oss/Socratic-PRMBench"><img src="https://img.shields.io/github/stars/Xiang-Li-oss/Socratic-PRMBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute of Automation, Chinese Academy of Sciences<br>
      • Benchmark Name: SOCRATIC-PRMBENCH, Task Number: 2995, Dataset Source: synthetic + human<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>LLM Agents for Bargaining with Utility-based Feedback</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22998"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST AI<br>
      • Benchmark Name: BARGAIN ARENA, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>WorkForceAgent-R1: Incentivizing Reasoning Capability in LLM-based Web Agents via Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22942"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/night-chen/WorkForceAgent-R1"><img src="https://img.shields.io/github/stars/night-chen/WorkForceAgent-R1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Tech<br>
      • Agent Name: WorkForceAgent-R1, Base Model: Qwen2.5-Instruct (3B/7B/14B), Strategy: Supervised Fine-Tuning (SFT), Reinforcement Learning (RL), Rule-based R1-style RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>When Does Neuroevolution Outcompete Reinforcement Learning in Transfer Learning Tasks?</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22696"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/eleninisioti/ecorobot,https://github.com/eleninisioti/stepping_gates"><img src="https://img.shields.io/github/stars/eleninisioti/stepping_gates.svg?style=social&label=Star"></a><br>
      <a href="https://sites.google.com/view/neuroevo-transfer/home"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IT University of Copenhagen<br>
      • Benchmark Name: stepping gates, Task Number: 2, Dataset Source: <br>
      • Benchmark Name: ecorobot, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>WebDancer: Towards Autonomous Information Seeking Agency</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22648"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Alibaba-NLP/WebAgent"><img src="https://img.shields.io/github/stars/Alibaba-NLP/WebAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tongyi Lab, Alibaba Group<br>
      • Agent Name: WebDancer, Base Model: , Strategy: SFT, RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>EvolveSearch: An Iterative Self-Evolving Search Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22501"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tongyi Lab, Alibaba Group<br>
      • Agent Name: EvolveSearch, Base Model: Qwen2.5-7B-Instruct, Strategy: Hybrid Reward Reinforcement Learning and Rejection Sampling Fine-Tuning (RSFT)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>From Large AI Models to Agentic AI: A Tutorial on Future Intelligent Communications</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.22311"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/jiangfeibo/ComAgent"><img src="https://img.shields.io/github/stars/jiangfeibo/ComAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hunan Provincial Key Laboratory of Intelligent Computing and Language Information Processing, Hunan Normal University, Changsha, China<br>
      • Paper Number: 207<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>UI-Evol: Automatic Knowledge Evolving for Computer Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21964"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Software and Microelectronics, Peking University<br>
      • Agent Name: UI-Evol, Base Model: GPT-4o, OpenAI-o3, Strategy: Knowledge refinement and self-evolution through Retrace and Critique stages<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21936"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/RedTeamCUA"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/RedTeamCUA.svg?style=social&label=Star"></a><br>
      <a href="https://osu-nlp-group.github.io/RedTeamCUA"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Benchmark Name: RTC-BENCH, Task Number: 864, Dataset Source: not explicitly mentioned<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Deep Reinforcement Learning Agents are not even close to Human Intelligence</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21731"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/k4ntz/HackAtari"><img src="https://img.shields.io/github/stars/k4ntz/HackAtari.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Technical University Darmstadt, Germany<br>
      • Benchmark Name: HackAtari, Task Number: 224, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>UI-Genie: A Self-Improving Approach for Iteratively Boosting MLLM-based Mobile GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21496"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Euphoria16/UI-Genie"><img src="https://img.shields.io/github/stars/Euphoria16/UI-Genie.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: CUHK MMLab<br>
      • Agent Name: UI-Genie-Agent, Base Model: Qwen2.5-VL, Strategy: Reward-guided trajectory exploration, iterative fine-tuning<br>
      • Benchmark Name: UI-Genie-RM-517k, Task Number: 517000, Dataset Source: synthetic trajectory generation without manual annotation<br>
      • Benchmark Name: UI-Genie-Agent-16k, Task Number: 16000, Dataset Source: synthetic trajectory generation without manual annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>XBOUND: Exploring the Capability Boundaries of Device-Control Agents through Trajectory Tree Exploration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21279"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sqzhang-lazy/XBOUND"><img src="https://img.shields.io/github/stars/sqzhang-lazy/XBOUND.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen, China<br>
      • Benchmark Name: Android Control Tree Dataset, Task Number: 5, Dataset Source: derived from Android Control test data<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Creativity in LLM-based Multi-Agent Systems: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21116"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MiuLab/MultiAgent-Survey"><img src="https://img.shields.io/github/stars/MiuLab/MultiAgent-Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Taiwan University, Taipei, Taiwan<br>
      • Paper Number: 139<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21069"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Agent Name: CXXCrafter, Base Model: GPT-4o, Strategy: Dynamic Interaction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Agent-Environment Alignment via Automated Interface Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.21055"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUNLP-MT/ALIGN"><img src="https://img.shields.io/github/stars/THUNLP-MT/ALIGN.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Technology, Tsinghua University, Beijing, China<br>
      • Agent Name: ALIGN, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Can Agents Fix Agent Issues?</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20749"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://alfin06.github.io/AgentIssue-Bench-Leaderboard/#/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Benchmark Name: AGENT ISSUE -BENCH, Task Number: 50, Dataset Source: GitHub issues<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>RRO: LLM Agent Optimization Through Rising Reward Trajectories</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20737"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, San Diego<br>
      • Agent Name: Reward Rising Optimization (RRO), Base Model: Gemma-2 2B, Strategy: Dynamic Exploration Strategy and Reward Rising Criteria<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20732"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WangHanLinHenry/SPA-RL-Agent"><img src="https://img.shields.io/github/stars/WangHanLinHenry/SPA-RL-Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computing, The Hong Kong Polytechnic University<br>
      • Agent Name: SPA-RL Agent, Base Model: Llama-3.2-3B-Instruct, Strategy: Stepwise Progress Attribution<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>BacktrackAgent: Enhancing GUI Agent with Error Detection and Backtracking Mechanism</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20660"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MiLM Plus, Xiaomi Inc<br>
      • Agent Name: BacktrackAgent, Base Model: Qwen2-VL-7B, Strategy: SFT+RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20411"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://swe-rebench.com/leaderboard"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nebius<br>
      • Benchmark Name: SWE-rebench, Task Number: 21336, Dataset Source: GitHub repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20286"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/CharlesQ9/Alita"><img src="https://img.shields.io/github/stars/CharlesQ9/Alita.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AI Lab, Princeton University<br>
      • Agent Name: Alita, Base Model: Claude-3.7-Sonnet, GPT-4o, Strategy: Minimal Predefinition, Maximal Self-Evolution<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>On Path to Multimodal Historical Reasoning: HistBench and HistAgent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20246"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/CharlesQ9/HistAgent"><img src="https://img.shields.io/github/stars/CharlesQ9/HistAgent.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/jiahaoq/HistBench"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AI Lab, Princeton University<br>
      • Agent Name: HistAgent, Base Model: GPT-4o, Strategy: Modular tools integration<br>
      • Benchmark Name: HistBench, Task Number: 414, Dataset Source: human-authored questions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20023"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Agent Name: STeP, Base Model: LLaMA2-7B-chat, Strategy: Self-Reflected Trajectories and Partial Masking<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>WebCoT: Enhancing Web Agent Reasoning by Reconstructing Chain-of-Thought in Reflection, Branching, and Rollback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.20013"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Chinese University of Hong Kong<br>
      • Agent Name: WEBCOT, Base Model: LLAMA-3.3-70B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19897"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="Scienceboard Homepage"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Benchmark Name: SCIENCE BOARD, Task Number: 169, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Multi-Agent Reinforcement Learning in Cybersecurity: From Fundamentals to Applications</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19837"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cyber-Defence Campus & Eastern Switzerland University of Applied Sciences, Rapperswil, Switzerland<br>
      • Paper Number: 69<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>SecVulEval: Benchmarking LLMs for Real-World C/C++ Vulnerability Detection</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19828"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/basimbd/SecVulEval"><img src="https://img.shields.io/github/stars/basimbd/SecVulEval.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: York University<br>
      • Benchmark Name: SECVULEVAL, Task Number: 25440, Dataset Source: C/C++ vulnerabilities from NVD<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Large Language Models for Planning: A Comprehensive and Systematic Survey</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19683"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Quester-one/Awesome-LLM-Planning"><img src="https://img.shields.io/github/stars/Quester-one/Awesome-LLM-Planning.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Key Laboratory of Cognition and Decision Intelligence for Complex Systems, CASIA, and School of Artificial Intelligence, University of Chinese Academy of Sciences, China<br>
      • Agent Name: KnowAgent, Base Model: , Strategy: Knowledge Augmented Planning<br>
      • Agent Name: Agent-R, Base Model: , Strategy: Reflection via Iterative Self-Training<br>
      • Agent Name: Agentgen, Base Model: , Strategy: Environment and Task Generation<br>
      • Benchmark Name: Mind2Web, Task Number: , Dataset Source: <br>
      • Benchmark Name: WebArena, Task Number: , Dataset Source: <br>
      • Benchmark Name: AITW, Task Number: 30378, Dataset Source: human demonstration<br>
      • Paper Number: 350<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>FieldWorkArena: Agentic AI Benchmark for Real Field Work Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19662"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://en-documents.research.global.fujitsu.com/fieldworkarena/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fujitsu Limited, Japan<br>
      • Benchmark Name: FieldWorkArena, Task Number: 455, Dataset Source: data obtained from actual work sites<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Benchmarking and Enhancing LLM Agents in Localizing Linux Kernel Bugs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19489"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/FudanSELab/LinuxFLBench"><img src="https://img.shields.io/github/stars/FudanSELab/LinuxFLBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Agent Name: LINUX FL+, Base Model: GPT-4o, Strategy: Directory-Aware Expansion, Potential Cause Expansion<br>
      • Benchmark Name: LINUX FLBENCH, Task Number: 250, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19443"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University, Department of Biological and Environmental Engineering, USA<br>
      • Agent Name: Jules, Base Model: Gemini, Strategy: Autonomous execution through goal-driven agents capable of planning, executing, testing, and iterating tasks<br>
      • Agent Name: Codex, Base Model: OpenAI, Strategy: Execution within sandboxed environments, enabling autonomous actions across tools and APIs<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Can Compressed LLMs Truly Act? An Empirical Evaluation of Agentic Capabilities in LLM Compression</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19433"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/pprp/ACBench"><img src="https://img.shields.io/github/stars/pprp/ACBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong University of Science and Technology (GuangZhou)<br>
      • Benchmark Name: ACBench, Task Number: 12, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>What do Blind and Low-Vision People Really Want from Assistive Smart Devices? Comparison of the Literature with a Focus Study</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19325"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Monash University<br>
      • Paper Number: 646<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ALRPHFS: Adversarially Learned Risk Patterns with Hierarchical Fast \& Slow Reasoning for Robust Agent Defense</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19260"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sichuan University<br>
      • Agent Name: ALRPHFS, Base Model: , Strategy: Adversarially Learned Risk Patterns with Hierarchical Fast & Slow Reasoning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ScreenExplorer: Training a Vision-Language Model for Diverse Exploration in Open GUI World</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.19095"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/niuzaisheng/ScreenExplorer"><img src="https://img.shields.io/github/stars/niuzaisheng/ScreenExplorer.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Artificial Intelligence, Jilin University<br>
      • Agent Name: ScreenExplorer, Base Model: Qwen2.5-VL-3B, Strategy: Reinforcement Learning with GRPO, World Model Curiosity Reward, and Experience Stream Distillation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Security Concerns for Large Language Models: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18889"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Infinite Optimization AI Lab<br>
      • Paper Number: 49<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18878"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SalesforceAIResearch/CRMArena"><img src="https://img.shields.io/github/stars/SalesforceAIResearch/CRMArena.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/Salesforce/CRMArenaPro"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Salesforce AI Research<br>
      • Benchmark Name: CRMArena-Pro, Task Number: 19, Dataset Source: synthetic enterprise data<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>LiteCUA: Computer as MCP Server for Computer-Use Agent on AIOS</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18829"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agiresearch/LiteCUA"><img src="https://img.shields.io/github/stars/agiresearch/LiteCUA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Rutgers University<br>
      • Agent Name: LiteCUA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey of LLM $\times$ DATA</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18458"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/weAIDB/awesome-data-llm"><img src="https://img.shields.io/github/stars/weAIDB/awesome-data-llm.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Paper Number: 400<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Implementing Agents in JavaScript</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18228"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://js-son.readthedocs.io/en/latest/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computing Science, Umeå University, 901 87 Umeå, Sweden<br>
      • Agent Name: reasoning loop agent, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>IDA-Bench: Evaluating LLMs on Interactive Guided Data Analysis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18223"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lhydave/IDA-Bench"><img src="https://img.shields.io/github/stars/lhydave/IDA-Bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: CFCS, School of Computer Science, Peking University<br>
      • Benchmark Name: IDA-Bench, Task Number: 25, Dataset Source: Kaggle notebooks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ProgRM: Build Better GUI Agents with Progress Rewards</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18121"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: X-LANCE Lab, School of Computer Science, MoE Key Lab of Artificial Intelligence, SJTU AI Institute, Shanghai Jiao Tong University, Shanghai, China<br>
      • Agent Name: PROGRM, Base Model: Qwen2.5-7B, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ManuSearch: Democratizing Deep Search in Large Language Models with a Transparent and Open Multi-Agent Framework</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18105"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/RUCAIBox/ManuSearch"><img src="https://img.shields.io/github/stars/RUCAIBox/ManuSearch.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: ManuSearch, Base Model: QwQ-32B, DeepSeek-R1, Strategy: ReAct architecture, modular multi-agent design<br>
      • Benchmark Name: ORION, Task Number: 310, Dataset Source: LLM synthesis followed by human refinement<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Planning without Search: Refining Frontier LLMs with Offline Goal-Conditioned RL</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.18098"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://jxihong.github.io/pnlc_website/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: PNLC, Base Model: GPT-4, Strategy: Offline Goal-Conditioned RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Survival Games: Human-LLM Strategic Showdowns under Severe Resource Scarcity</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17937"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/hong123123/Survival-Games"><img src="https://img.shields.io/github/stars/hong123123/Survival-Games.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: South China University of Technology<br>
      • Benchmark Name: Survival Games, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Get Experience from Practice: LLM Agents with Record & Replay</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17716"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute of Parallel and Distributed Systems (IPADS), Shanghai Jiao Tong University<br>
      • Agent Name: AgentRR, Base Model: , Strategy: Record & Replay<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>TransBench: Breaking Barriers for Transferable Graphical User Interface Agents in Dynamic Digital Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17629"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beihang University<br>
      • Benchmark Name: TransBench, Task Number: not explicitly mentioned, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey of Safe Reinforcement Learning and Constrained MDPs: A Technical Survey on Single-Agent and Multi-Agent Safety</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17342"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: International Institute of Information Technology, Hyderabad<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>CRAKEN: Cybersecurity LLM Agent with Knowledge-Based Execution</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17107"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/NYU-LLM-CTF/nyuctf_agents_craken"><img src="https://img.shields.io/github/stars/NYU-LLM-CTF/nyuctf_agents_craken.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: New York University<br>
      • Agent Name: CRAKEN, Base Model: Claude 3.5 Sonnet, Strategy: Self-RAG + Graph-RAG<br>
      • Benchmark Name: NYU CTF Bench, Task Number: 200, Dataset Source: CTF writeups and challenges<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>P2P: Automated Paper-to-Poster Generation and Fine-Grained Benchmark</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17104"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Electronic Science and Technology of China<br>
      • Benchmark Name: Mobile-Bench, Task Number: 632, Dataset Source: human verification<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Decoding Rarity: Large Language Models in the Diagnosis of Rare Diseases</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.17065"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Catanzaro<br>
      • Paper Number: 66<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>AGENTIF: Benchmarking Instruction Following of Large Language Models in Agentic Scenarios</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16944"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THU-KEG/AgentIF"><img src="https://img.shields.io/github/stars/THU-KEG/AgentIF.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/THU-KEG/AgentIF"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: AGENT IF, Task Number: 50, Dataset Source: real-world agentic applications and open-source agentic workflows<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>From EduVisBench to EduVisAgent: A Benchmark and Multi-Agent Framework for Reasoning-Driven Pedagogical Visualization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16832"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aiming-lab/EduVisBench, https://github.com/aiming-lab/EduVisAgent"><img src="https://img.shields.io/github/stars/aiming-lab/EduVisAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UNC-Chapel Hill<br>
      • Agent Name: EduVisAgent, Base Model: , Strategy: Multi-agent collaborative framework<br>
      • Benchmark Name: EduVisBench, Task Number: 1154, Dataset Source: Carefully curated STEM questions from educational resources<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>GUI-explorer: Autonomous Exploration and Mining of Transition-aware Knowledge for GUI Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16827"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/JiuTian-VL/GUI-explorer"><img src="https://img.shields.io/github/stars/JiuTian-VL/GUI-explorer.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen<br>
      • Agent Name: GUI-explorer, Base Model: GPT-4o, Strategy: Autonomous Exploration and Mining of Transition-aware Knowledge<br>
      • Benchmark Name: GUI-KRB, Task Number: 500, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MCP-RADAR: A Multi-Dimensional Benchmark for Evaluating Tool Use Capabilities in Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16700"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/MCPRadar-B143/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Xi’an Jiaotong University<br>
      • Benchmark Name: MCP-R ADAR, Task Number: 300, Dataset Source: high-quality open-source datasets<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>EMULATE: A Multi-Agent Framework for Determining the Veracity of Atomic Claims by Emulating Human Actions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16576"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/qqqube/EMULATE"><img src="https://img.shields.io/github/stars/qqqube/EMULATE.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: EMULATE, Base Model: GPT-4.1, Strategy: Multi-Agent Framework<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Unlocking Smarter Device Control: Foresighted Planning with a World Model-Driven Code Execution Approach</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16422"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Electronic Science and Technology of China<br>
      • Agent Name: FPWC, Base Model: GPT-4V, Strategy: World Model-Driven Code Execution<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16421"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/weizhepei/WebAgent-R1"><img src="https://img.shields.io/github/stars/weizhepei/WebAgent-R1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Virginia<br>
      • Agent Name: WEBAGENT-R1, Base Model: Qwen2.5-3B, Llama3.1-8B, Strategy: Behavioral Cloning, Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ARPO:End-to-End Policy Optimization for GUI Agents with Experience Replay</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16282"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/dvlab-research/ARPO.git"><img src="https://img.shields.io/github/stars/dvlab-research/ARPO.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Chinese University of Hong Kong<br>
      • Agent Name: ARPO, Base Model: UI-Tars-1.5, Strategy: GRPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>LLM-Powered AI Agent Systems and Their Applications in Industry</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.16120"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Independent AI researcher<br>
      • Paper Number: 122<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Text-to-Pipeline: Bridging Natural Language and Data Preparation Pipelines</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15874"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/Text-to-Pipeline"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Benchmark Name: PARROT, Task Number: 17168, Dataset Source: real-world tables and production-inspired transformation patterns<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>InfoDeepSeek: Benchmarking Agentic Information Seeking for Retrieval-Augmented Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15872"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://infodeepseek.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: Agentic RAG framework, Base Model: , Strategy: <br>
      • Benchmark Name: InfoDeepSeek, Task Number: 245, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>AutoData: A Multi-Agent System for Open Web Data Collection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15859"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Notre Dame<br>
      • Agent Name: AutoData, Base Model: GPT-4o, Strategy: Multi-Agent Collaboration with Oriented Hypergraph Cache System<br>
      • Benchmark Name: Instruct2DS, Task Number: 234, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>GUI-G1: Understanding R1-Zero-Like Training for Visual Grounding in GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15810"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Yuqi-Zhou/GUI-G1"><img src="https://img.shields.io/github/stars/Yuqi-Zhou/GUI-G1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: GUI-G1-3B, Base Model: Qwen2.5-VL-3B-Instruct, Strategy: GRPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>X-WebAgentBench: A Multilingual Interactive Web Benchmark for Evaluating Global Agentic System</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15372"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WPENGxs/X-WebAgentBench"><img src="https://img.shields.io/github/stars/WPENGxs/X-WebAgentBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and Engineering, Central South University, China<br>
      • Benchmark Name: X-WebAgentBench, Task Number: 2,800, Dataset Source: WebShop<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Web-Shepherd: Advancing PRMs for Reinforcing Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15277"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Yonsei University<br>
      • Agent Name: WEB-SHEPHERD, Base Model: Qwen2.5-3B, Qwen3-8B, Qwen2.5-VL-3B, Strategy: Next-token prediction<br>
      • Benchmark Name: WEBREWARD BENCH, Task Number: 776, Dataset Source: human demonstration, LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ReGUIDE: Data Efficient GUI Grounding via Spatial Reasoning and Search</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15259"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Agent Name: ReGUIDE, Base Model: Qwen-2.5-VL, Strategy: Reinforcement Learning, Spatial Reasoning, Test-time Scaling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>BountyBench: Dollar Impact of AI Agent Attackers and Defenders on Real-World Cybersecurity Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.15216"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://bountybench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: Claude Code, Base Model: Claude 3.7 Sonnet, Strategy: Prompt<br>
      • Agent Name: OpenAI Codex CLI, Base Model: o4-mini, Strategy: Prompt<br>
      • Agent Name: C-Agent: GPT-4.1, Base Model: GPT-4.1, Strategy: Prompt<br>
      • Agent Name: C-Agent: Gemini 2.5, Base Model: Gemini 2.5 Pro Preview, Strategy: Prompt<br>
      • Agent Name: C-Agent: Claude 3.7, Base Model: Claude 3.7 Sonnet Thinking, Strategy: Prompt<br>
      • Benchmark Name: BountyBench, Task Number: 120, Dataset Source: bug bounty reports<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MedBrowseComp: Benchmarking Medical Deep Research and Computer Use</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14963"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/shan23chen/MedBrowseComp"><img src="https://img.shields.io/github/stars/shan23chen/MedBrowseComp.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/AIM-Harvard/MedBrowseComp"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harvard<br>
      • Benchmark Name: MedBrowseComp, Task Number: 1000+, Dataset Source: human-curated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>The Evolution of Alpha in Finance Harnessing Human Insight and LLM Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14727"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: George Mason University, Fairfax VA 22030, USA<br>
      • Paper Number: 72<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Agent Context Protocols Enhance Collective Inference</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14569"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agent-context-protocol"><img src="https://img.shields.io/github/stars/github.com/agent-context-protocol.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Indian Institute of Technology Roorkee<br>
      • Agent Name: Agent Context Protocols (ACPs), Base Model: GPT-4o, Strategy: Structured communication and error handling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14418"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Shanghai Jiao Tong University<br>
      • Agent Name: AgentGhost, Base Model: OS-Atlas-Base-7B, Strategy: Min-Max Optimization<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Safety Devolution in AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14215"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agno-agi/agno"><img src="https://img.shields.io/github/stars/agno-agi/agno.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Technical University of Munich<br>
      • Agent Name: WikiAgent, Base Model: Qwen2.5-3B, LLaMA3.2-3B, Gemma3-4B, Mistral0.3-7B, GPT-4o-mini, Strategy: Retrieval-Augmented Generation (RAG)<br>
      • Agent Name: WebAgent (Autogen), Base Model: Qwen2.5-3B, LLaMA3.2-3B, Gemma3-4B, Mistral0.3-7B, GPT-4o-mini, Strategy: Retrieval-Augmented Generation (RAG)<br>
      • Agent Name: WebAgent (Agno), Base Model: Qwen2.5-3B, LLaMA3.2-3B, Gemma3-4B, Mistral0.3-7B, GPT-4o-mini, Strategy: Retrieval-Augmented Generation (RAG)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Building a Stable Planner: An Extended Finite State Machine Based Planning Module for Mobile GUI Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.14141"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hong Kong University of Science and Technology (Guangzhou)<br>
      • Agent Name: SPlanner, Base Model: Qwen2.5-VL-72B, Strategy: EFSM-based planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Efficient Agent Training for Computer Use</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.13909"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/GAIR-NLP/PC-Agent-E"><img src="https://img.shields.io/github/stars/GAIR-NLP/PC-Agent-E.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: PC Agent-E, Base Model: Qwen2.5-VL-72B, Strategy: SFT<br>
      • Benchmark Name: WindowsAgentArena-V2, Task Number: 141, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Structured Agent Distillation for Large Language Model</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.13820"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: Structured Agent Distillation, Base Model: GPT-2-1.5B, Strategy: Behavioral Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.13652"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nebius<br>
      • Agent Name: SWE-agent, Base Model: Qwen-72B, Strategy: 1-step lookahead and trajectory selection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.13259"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery"><img src="https://img.shields.io/github/stars/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Engineering, HKUST, Hong Kong SAR, China<br>
      • Paper Number: 142<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Scaling Computer-Use Grounding via User Interface Decomposition and Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.13227"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://osworld-grounding.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Agent Name: JEDI, Base Model: Qwen2.5-VL, Strategy: Fine-tuning<br>
      • Benchmark Name: OSWORLD-G, Task Number: 564, Dataset Source: human annotation and synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>From Assistants to Adversaries: Exploring the Security Risks of Mobile LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12981"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huazhong University of Science and Technology<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>GEM: Gaussian Embedding Modeling for Out-of-Distribution Detection in GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12842"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Wuzheng02/GEM-OODforGUIagents"><img src="https://img.shields.io/github/stars/Wuzheng02/GEM-OODforGUIagents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Shanghai Jiao Tong University<br>
      • Agent Name: GEM, Base Model: Qwen2-VL-7B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Forewarned is Forearmed: A Survey on Large Language Model-based Agents in Autonomous Cyberattacks</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12786"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University, Singapore<br>
      • Paper Number: 221<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Scalable Video-to-Dataset Generation for Cross-Platform Mobile Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12632"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://monday-dataset.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Michigan<br>
      • Benchmark Name: MONDAY, Task Number: 313K annotated frames from 20K videos, Dataset Source: automated extraction from instructional videos<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey of Attacks on Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12567"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Minnesota<br>
      • Paper Number: 89<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>UIShift: Enhancing VLM-based GUI Agents through Self-supervised Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12493"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications<br>
      • Agent Name: UIShift, Base Model: Qwen2.5-VL-3B/7B, Strategy: GRPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Learning to Play Like Humans: A Framework for LLM Adaptation in Interactive Fiction Games</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12439"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Essex, UK<br>
      • Agent Name: LPLH, Base Model: Qwen2.5-7B-Instruct, Qwen2.5-14B-Instruct, GPT-4o-mini, GPT-o3-mini, Strategy: Dynamic knowledge-graphs map, Action Space Learning, Experience Lib<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12371"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://medagentboard.netlify.app/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Peking University<br>
      • Benchmark Name: MedAgentBoard, Task Number: 100, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Enhancing Visual Grounding for GUI Agents via Self-Evolutionary Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12370"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/YXB-NKU/SE-GUI"><img src="https://img.shields.io/github/stars/YXB-NKU/SE-GUI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: VCIP, School of Computer Science, NKU<br>
      • Agent Name: SE-GUI, Base Model: QwenVL2.5-3B/7B, Strategy: Reinforcement Learning with Self-Evolutionary Fine-Tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Enhance Mobile Agents Thinking Process Via Iterative Preference Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.12299"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: XiaoMi AI Lab<br>
      • Agent Name: MobileIPL, Base Model: Qwen2-VL-7B, Strategy: Iterative Preference Learning (IPL), including CoaT-tree sampling, rule-based reward, and Direct Preference Optimization (DPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>LifelongAgentBench: Evaluating LLM Agents as Lifelong Learners</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11942"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: South China University of Technology<br>
      • Benchmark Name: LifelongAgentBench, Task Number: 1396, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Benchmarking LLMs in an Embodied Environment for Blue Team Threat Hunting</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11901"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Southern University of Science and Technology<br>
      • Benchmark Name: CYBER TEAM, Task Number: 30, Dataset Source: threat intelligence data from 23 vulnerability databases and threat intelligence platforms<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Mobile-Bench-v2: A More Realistic and Comprehensive Benchmark for VLM-based Mobile Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11891"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/datasets/xwk123/MobileBench-v2"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University<br>
      • Benchmark Name: Mobile-Bench-v2, Task Number: 12856, Dataset Source: human demonstration and LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Credit Assignment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11821"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SiliangZeng/Multi-Turn-RL-Agent"><img src="https://img.shields.io/github/stars/SiliangZeng/Multi-Turn-RL-Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Minnesota<br>
      • Agent Name: Multi-Turn GRPO Agent, Base Model: Qwen2.5-7B, Strategy: Turn-Level Credit Assignment<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Retrospex: Language Agent Meets Offline Reinforcement Learning Critic</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11807"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Yufei-Xiang/Retrospex"><img src="https://img.shields.io/github/stars/Yufei-Xiang/Retrospex.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory for Novel Software Technology, Nanjing University<br>
      • Agent Name: Retrospex, Base Model: Flan-T5-large, LLaMA3-8B-Instruct, Strategy: Dynamic Action Rescoring, Offline RL Training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>EnvInjection: Environmental Prompt Injection Attack to Multi-modal Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11717"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Duke University<br>
      • Benchmark Name: EnvInjection, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Talk to Your Slides: Language-Driven Agents for Efficient Slide Editing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.11604"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="anonymous.4open.science/r/talk-to-your-slides"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Chung-ang University<br>
      • Agent Name: TALK-TO-YOUR-SLIDES, Base Model: Gemini-2.5-flash, Strategy: Prompt<br>
      • Benchmark Name: TSBench, Task Number: 379, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Group-in-Group Policy Optimization for LLM Agent Training</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10978"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/langfengQ/verl-agent"><img src="https://img.shields.io/github/stars/langfengQ/verl-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University, Singapore<br>
      • Agent Name: LLM Agent trained with GiGPO, Base Model: Qwen2.5-1.5B-Instruct, Qwen2.5-7B-Instruct, Strategy: Group-in-Group Policy Optimization (GiGPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey on the Safety and Security Threats of Computer-Using Agents: JARVIS or Ultron?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10924"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>InfantAgent-Next: A Multimodal Generalist Agent for Automated Computer Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10887"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bin123apple/InfantAgent"><img src="https://img.shields.io/github/stars/bin123apple/InfantAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Minnesota<br>
      • Agent Name: INFANT AGENT -NEXT, Base Model: Claude-3.7-Sonnet, Strategy: Modular architecture with unified dialogue context<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Creating General User Models from Computer Use</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10831"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://generalusermodels.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: Gumbo, Base Model: Llama 3.3 70B, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Automating Security Audit Using Large Language Model based Agent: An Exploration Experiment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10732"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University, Singapore<br>
      • Agent Name: Langchain agent, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>LLM-Explorer: Towards Efficient and Affordable LLM-based Exploration for Mobile Apps</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10593"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MobileLLM/LLM-Explorer"><img src="https://img.shields.io/github/stars/MobileLLM/LLM-Explorer.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute for AI Industry Research (AIR), Tsinghua University<br>
      • Agent Name: LLM-Explorer, Base Model: GPT-3.5, Strategy: LLM-assisted Knowledge Maintenance and Knowledge-guided Exploration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>AI Agents vs. Agentic AI: A Conceptual Taxonomy, Applications and Challenges</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10468"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University, Department of Biological and Environmental Engineering, USA<br>
      • Paper Number: 237<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.10321"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/JuliusHenke/autopentest"><img src="https://img.shields.io/github/stars/JuliusHenke/autopentest.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Amsterdam and SURF<br>
      • Agent Name: AutoPentest, Base Model: GPT-4o, Strategy: Prompt Engineering<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Security of Internet of Agents: Attacks and Countermeasures</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.08807"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Cyber Science and Engineering, Xi'an Jiaotong University, Xi'an, China<br>
      • Paper Number: 60<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>TRAIL: Trace Reasoning and Agentic Issue Localization</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.08638"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Patronus AI<br>
      • Benchmark Name: TRAIL, Task Number: 148, Dataset Source: human-annotated traces<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Benchmarking AI scientists in omics data-driven biological research</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.08341"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/EperLuo/BaisBench"><img src="https://img.shields.io/github/stars/EperLuo/BaisBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: BaisBench, Task Number: 2, Dataset Source: single-cell transcriptomic datasets<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Combining Bayesian Inference and Reinforcement Learning for Agent Decision Making: A Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07911"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Finnish Center for Artificial Intelligence (FCAI)<br>
      • Paper Number: 304<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ai.txt: A Domain-Specific Language for Guiding AI Interactions with the Internet</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07834"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://sites.google.com/view/ai-txt/home"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of New South Wales<br>
      • Agent Name: ai.txt, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>MLE-Dojo: Interactive Environments for Empowering LLM Agents in Machine Learning Engineering</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07782"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MLE-Dojo/MLE-Dojo"><img src="https://img.shields.io/github/stars/MLE-Dojo/MLE-Dojo.svg?style=social&label=Star"></a><br>
      <a href="https://mle-dojo.github.io/MLE-Dojo-page/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Institute of Technology<br>
      • Agent Name: MLE Agent, Base Model: , Strategy: <br>
      • Agent Name: AIDE, Base Model: , Strategy: Solution Space Tree Search<br>
      • Benchmark Name: MLE-Dojo, Task Number: 200+, Dataset Source: real-world Kaggle competitions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>VTutor for High-Impact Tutoring at Scale: Managing Engagement and Real-Time Multi-Screen Monitoring with P2P Connections</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07736"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ls2025.vtutor.ai"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: VTutor, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Neural Brain: A Neuroscience-inspired Framework for Embodied Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07634"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="Neural-Brain-for-Embodied-Agents"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Electrical and Electronic Engineering, Nanyang Technological University, Singapore<br>
      • Paper Number: 413<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Web-Bench: A LLM Code Benchmark Based on Web Standards and Frameworks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07473"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bytedance/web-bench"><img src="https://img.shields.io/github/stars/bytedance/web-bench.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/bytedance-research/Web-Bench"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ByteDance<br>
      • Benchmark Name: Web-Bench, Task Number: 50 projects, each consisting of 20 tasks, Dataset Source: designed by engineers with 5 to 10 years of experience<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Internet of Agents: Fundamentals, Applications, and Challenges</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07176"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Cyber Science and Engineering, Xi'an Jiaotong University, Xi'an, China<br>
      • Paper Number: 133<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Exploring Anthropomorphism in Conversational Agents for Environmental Sustainability</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07142"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Politecnico di Milano<br>
      • Agent Name: Washy, Base Model: GPT-4o, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Seed1.5-VL Technical Report</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.07062"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://www.volcengine.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ByteDance<br>
      • Agent Name: Seed1.5-VL, Base Model: Mixture-of-Experts (MoE) LLM with 20B active parameters, Strategy: Supervised Fine-tuning (SFT), Reinforcement Learning from Human Feedback (RLHF), and Reinforcement Learning with Verifiable Rewards (RLVR)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>RedTeamLLM: an Agentic AI framework for offensive security</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.06913"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lre-security-systems-team/redteamllm"><img src="https://img.shields.io/github/stars/lre-security-systems-team/redteamllm.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Laboratoire de Recherche de l’EPITA, 14-16 Rue Voltaire, 94270 Le Kremlin-Bicêtre, France<br>
      • Agent Name: RedTeamLLM, Base Model: GPT4-o, Strategy: Reasoning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>VTutor: An Animated Pedagogical Agent SDK that Provide Real Time Multi-Model Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.06676"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://vtutor-aied25.vercel.app"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: VTutor, Base Model: Various LLMs (e.g., GPT, Claude, Deepseek), Strategy: Generative AI-Driven Interaction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Would You Rely on an Eerie Agent? A Systematic Review of the Impact of the Uncanny Valley Effect on Trust in Human-Agent Interaction</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05543"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Communication Science, Vrije Universiteit Amsterdam<br>
      • Paper Number: 87<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Nature's Insight: A Novel Framework and Comprehensive Analysis of Agentic Reasoning Through the Lens of Neuroscience</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05515"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/BioRAILab/Awesome-Neuroscience-Agent-Reasoning"><img src="https://img.shields.io/github/stars/BioRAILab/Awesome-Neuroscience-Agent-Reasoning.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of EEE, Nanyang Technological University (NTU), Singapore<br>
      • Paper Number: 274<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>EcoAgent: An Efficient Edge-Cloud Collaborative Multi-Agent Framework for Mobile Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05440"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: EcoAgent, Base Model: GPT-4o, ShowUI (2B), Qwen2-VL-2B-Instruct, Strategy: Edge-Cloud Collaboration, Dual-ReACT Initial Planning, Memory and Reflection Empowered Replanning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Mapping User Trust in Vision Language Models: Research Landscape, Challenges, and Prospects</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05318"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Politecnico di Milano, Italy<br>
      • Paper Number: 71<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05283"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Xi’an Jiaotong University, China<br>
      • Paper Number: 461<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Multi-agent Embodied AI: Advances and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.05108"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Key Lab of Autonomous Intelligent Unmanned Systems, Beijing Institute of Technology, Beijing 100081, China<br>
      • Paper Number: 257<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Perception, Reason, Think, and Plan: A Survey on Large Multimodal Reasoning Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.04921"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models"><img src="https://img.shields.io/github/stars/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen<br>
      • Agent Name: Operater, Base Model: GPT-4o, Strategy: Reinforcement Learning<br>
      • Agent Name: Claude Computer Use, Base Model: Claude, Strategy: Dynamic Instruction Selection<br>
      • Agent Name: MME-Unify, Base Model: N/A, Strategy: Multi-modal Understanding and Generation<br>
      • Benchmark Name: AgentBench, Task Number: 8 different environments, Dataset Source: N/A<br>
      • Benchmark Name: WebArena, Task Number: N/A, Dataset Source: N/A<br>
      • Benchmark Name: Mind2Web, Task Number: N/A, Dataset Source: N/A<br>
      • Benchmark Name: OSWorld, Task Number: N/A, Dataset Source: Real computer environments<br>
      • Benchmark Name: AndroidWorld, Task Number: N/A, Dataset Source: Simulated Android environments<br>
      • Benchmark Name: Windows Agent Arena, Task Number: N/A, Dataset Source: Windows OS environments<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Vision-Language-Action Models: Concepts, Progress, Applications and Challenges</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.04769"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University, Biological & Environmental Engineering, Ithaca, New York, USA<br>
      • Paper Number: 224<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Scientific Hypothesis Generation and Validation: Methods, Datasets, and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.04651"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Virginia Tech, Blacksburg, VA, USA<br>
      • Paper Number: 60<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.04254"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Agent Name: CompileAgent, Base Model: , Strategy: flow-based agent strategy<br>
      • Benchmark Name: CompileAgentBench, Task Number: 100, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Towards Efficient Online Tuning of VLM Agents via Counterfactual Soft Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.03792"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/langfengQ/CoSo"><img src="https://img.shields.io/github/stars/langfengQ/CoSo.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University<br>
      • Agent Name: CoSo, Base Model: VLM (Vision-Language Model), Strategy: Counterfactual Soft Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>WebGen-Bench: Evaluating LLMs on Generating Interactive and Functional Websites from Scratch</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.03733"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/mnluzimu/WebGen-Bench"><img src="https://img.shields.io/github/stars/mnluzimu/WebGen-Bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Multimedia Laboratory (MMLab), The Chinese University of Hong Kong<br>
      • Agent Name: Bolt.diy, Base Model: DeepSeek-R1, Strategy: <br>
      • Agent Name: OpenHands, Base Model: DeepSeek-V3, Strategy: <br>
      • Agent Name: Aider, Base Model: DeepSeek-V3, Strategy: <br>
      • Benchmark Name: WebGen-Bench, Task Number: 647, Dataset Source: human annotators and GPT-4o<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>OSUniverse: Benchmark for Multimodal GUI-navigation AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.03570"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agentsea/osuniverse"><img src="https://img.shields.io/github/stars/agentsea/osuniverse.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Kentauros AI Inc.<br>
      • Benchmark Name: OSUniverse, Task Number: 160, Dataset Source: real use cases<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Comprehensive Survey of Large AI Models for Future Communications: Foundations, Applications and Challenges</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.03556"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/jiangfeibo/ComLAM"><img src="https://img.shields.io/github/stars/jiangfeibo/ComLAM.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hunan Provincial Key Laboratory of Intelligent Computing and Language Information Processing, Hunan Normal University, Changsha, China<br>
      • Paper Number: 194<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>VLM Q-Learning: Aligning Vision-Language Models for Interactive Decision-Making</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.03181"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Texas at Austin<br>
      • Agent Name: VLM-Q-Learning, Base Model: MoonDream2, PaliGemma, xGen-MM, Strategy: Advantage-Filtered Supervised Fine-Tuning (AFSFT), Q-Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>AutoLibra: Agent Metric Induction from Open-Ended Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.02820"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://autolibra.opensocial.world"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: AutoLibra, Base Model: GPT-4o, Strategy: Feedback-driven Metric Induction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey of Slow Thinking-based Reasoning LLMs using Reinforced Learning and Inference-time Scaling Law</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.02665"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and Technology, East China Normal University, China<br>
      • Paper Number: 160<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A survey of agent interoperability protocols: Model Context Protocol (MCP), Agent Communication Protocol (ACP), Agent-to-Agent Protocol (A2A), and Agent Network Protocol (ANP)</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.02279"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Kent State University<br>
      • Paper Number: 48<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>An overview of artificial intelligence in computer-assisted language learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.02032"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Helsinki, Finland. Department of Computer Science. Department of Digital Humanities.<br>
      • Paper Number: 189<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>From Mind to Machine: The Rise of Manus AI as a Fully Autonomous Digital Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.02024"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Electrical and Computer Engineering, Virginia Tech<br>
      • Agent Name: Manus AI, Base Model: transformer-based large language model (LLM), Strategy: Reinforcement Learning from Human Feedback (RLHF)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey on Inference Engines for Large Language Models: Perspectives on Optimization and Efficiency</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.01658"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sihyeong/Awesome-LLM-Inference-Engine"><img src="https://img.shields.io/github/stars/sihyeong/Awesome-LLM-Inference-Engine.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Korea Electronics Technology Institute, South Korea<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Grounding Task Assistance with Multimodal Cues from a Single Demonstration</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.01578"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research, USA<br>
      • Agent Name: MICA, Base Model: GPT-4o, Strategy: Multimodal Contextualized Assistance<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey of Robotic Navigation and Manipulation with Physics Simulators in the Era of Embodied AI</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.01458"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, City University of Hong Kong, China<br>
      • Paper Number: 210<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.01441"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research<br>
      • Agent Name: ARTIST, Base Model: Qwen2.5-7B-Instruct, Qwen2.5-14B-Instruct, Strategy: Reinforcement Learning (GRPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>A Survey on Large Language Model based Human-Agent Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00753"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Chicago<br>
      • Paper Number: 168<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Wireless Communication as an Information Sensor for Multi-agent Cooperative Perception: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00747"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: nan<br>
      • Paper Number: 61<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Visual Test-time Scaling for GUI Agent Grounding</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00684"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tiangeluo/RegionFocus"><img src="https://img.shields.io/github/stars/tiangeluo/RegionFocus.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Michigan<br>
      • Agent Name: RegionFocus, Base Model: UI-TARS, Qwen2.5-VL, Strategy: Visual Test-Time Scaling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Rethinking Memory in AI: Taxonomy, Operations, Topics, and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00675"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Elvin-Yiming-Du/Survey_Memory_in_AI"><img src="https://img.shields.io/github/stars/Elvin-Yiming-Du/Survey_Memory_in_AI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Edinburgh<br>
      • Paper Number: 3923<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>ScaleTrack: Scaling and back-tracking Automated GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00416"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meituan<br>
      • Agent Name: ScaleTrack, Base Model: Qwen2-VL-7B, Strategy: Data scaling, back-tracking training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2025</td>
    <td style="width: 40%;"><strong>Position Paper: Towards Open Complex Human-AI Agents Collaboration System for Problem-Solving and Knowledge Management</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2505.00018"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Paper Number: 107<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>SWE-smith: Scaling Data for Software Engineering Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21798"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://swesmith.com/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: SWE-agent-LM-32B, Base Model: Qwen 2.5 Coder Instruct 32B, Strategy: Rejection Sampling Fine-Tuning<br>
      • Benchmark Name: SWE-bench Multilingual, Task Number: 300, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>WebThinker: Empowering Large Reasoning Models with Deep Research Capability</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21776"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/RUC-NLPIR/WebThinker"><img src="https://img.shields.io/github/stars/RUC-NLPIR/WebThinker.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Renmin University of China<br>
      • Agent Name: WebThinker, Base Model: QwQ-32B, Strategy: RL-based training via iterative online DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>NGENT: Next-Generation AI Agents Must Integrate Multi-Domain Abilities to Achieve Artificial General Intelligence</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21433"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Renmin University, China<br>
      • Agent Name: NGENT, Base Model: , Strategy: Instruction Pre-Training (IPT), Supervised Fine-Tuning (SFT), Direct Preference Optimization (DPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>SecRepoBench: Benchmarking LLMs for Secure Code Generation in Real-World Repositories</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21205"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland<br>
      • Agent Name: Modified SWE-Agent EnIGMA, Base Model: GPT-4o-2024-11-20, Strategy: Adaptation of SWE-Agent EnIGMA<br>
      • Benchmark Name: SecRepoBench, Task Number: 318, Dataset Source: real-world C/C++ repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Multi-Agent Reinforcement Learning for Resources Allocation Optimization: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21048"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of South Australia<br>
      • Paper Number: 154<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.21024"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab<br>
      • Agent Name: WebEvolver, Base Model: Llama-3.3-70b, Strategy: Co-evolving World Model with SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey on GUI Agents with Foundation Models Enhanced by Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.20464"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Lenovo Research<br>
      • Paper Number: 40<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>CrashFixer: A crash resolution agent for the Linux kernel</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.20412"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Agent Name: CrashFixer, Base Model: Gemini Pro 1.5, Strategy: Hypothesis Generation and Patch Synthesis<br>
      • Benchmark Name: kGymSuite, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.20117"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: TCS Research<br>
      • Agent Name: ResearchCodeAgent, Base Model: Gemini 1.5 Flash, Strategy: Dynamic Planning and Execution<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Evolution of AI in Education: Agentic Workflows</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.20082"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AzizovDilshod/Multi-agent-System-for-Essay-Assessment/tree/main"><img src="https://img.shields.io/github/stars/tree/main.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Electrical Engineering, Canadian University Dubai, Dubai, United Arab Emirates<br>
      • Paper Number: 93<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.20073"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/RAGEN-AI/RAGEN"><img src="https://img.shields.io/github/stars/RAGEN-AI/RAGEN.svg?style=social&label=Star"></a><br>
      <a href="https://ragen-ai.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northwestern University<br>
      • Agent Name: RAGEN, Base Model: Qwen-2.5 Instruct 0.5B, Strategy: StarPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.19838"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/PhoneLLM/Awesome-LLM-Powered-Phone-GUI-Agents"><img src="https://img.shields.io/github/stars/PhoneLLM/Awesome-LLM-Powered-Phone-GUI-Agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: AutoDroid, Base Model: GPT-4, GPT-3.5, Strategy: UI Transition Graph (UTG) memory<br>
      • Agent Name: Mobile-Agent-v2, Base Model: GPT-4V, Strategy: Multi-agent architecture with planning, decision, and reflection agents<br>
      • Agent Name: AppAgent, Base Model: GPT-4, Strategy: Set-of-Mark (SoM) visual prompt method<br>
      • Agent Name: MobileGPT, Base Model: GPT-3.5, GPT-4, Strategy: Hierarchical decision-making process<br>
      • Agent Name: SeeClick, Base Model: Qwen-VL, Strategy: GUI grounding pre-training<br>
      • Benchmark Name: GUI Odyssey, Task Number: 7735, Dataset Source: human demonstration<br>
      • Benchmark Name: AndroidControl, Task Number: 15283, Dataset Source: LLM synthesis<br>
      • Paper Number: 159<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>From LLM Reasoning to Autonomous AI Agents: A Comprehensive Review</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.19678"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Guelma University, Algeria<br>
      • Agent Name: GUI Agent, Base Model: Claude 3.5, Strategy: Natural Language Instructions and Screenshots<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>BrowseComp-ZH: Benchmarking Web Browsing Ability of Large Language Models in Chinese</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.19314"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/PALIN2018/BrowseComp-ZH"><img src="https://img.shields.io/github/stars/PALIN2018/BrowseComp-ZH.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hong Kong University of Science and Technology (Guangzhou)<br>
      • Benchmark Name: BrowseComp-ZH, Task Number: 289, Dataset Source: reverse-designed tasks in native Chinese<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>AndroidGen: Building an Android Language Agent under Data Scarcity</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.19298"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/AndroidGen"><img src="https://img.shields.io/github/stars/THUDM/AndroidGen.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: ANDROID GEN, Base Model: GPT-4o, Strategy: ExpSearch, ReflectPlan, AutoCheck, StepCritic<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Generative to Agentic AI: Survey, Conceptualization, and Challenges</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.18875"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Liechtenstein, Vaduz, Liechtenstein<br>
      • Paper Number: 54<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Review of 3D Object Detection with Vision-Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.18738"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/r4hul77/Awesome-3D-Detection-Based-on-VLMs"><img src="https://img.shields.io/github/stars/r4hul77/Awesome-3D-Detection-Based-on-VLMs.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University<br>
      • Paper Number: 105<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.18575"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/facebookresearch/wasp"><img src="https://img.shields.io/github/stars/facebookresearch/wasp.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FAIR at Meta<br>
      • Benchmark Name: WASP, Task Number: 84, Dataset Source: manual prompt injection attack baselines<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>RepliBench: Evaluating the Autonomous Replication Capabilities of Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.18565"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UK AI Security Institute (AISI)<br>
      • Benchmark Name: RepliBench, Task Number: 86, Dataset Source: human-designed<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>LLMpatronous: Harnessing the Power of LLMs For Vulnerability Detection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.18423"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Rajesh9998/LLMPatronus"><img src="https://img.shields.io/github/stars/Rajesh9998/LLMPatronus.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Independent Researcher<br>
      • Agent Name: LLMpatronous, Base Model: , Strategy: RAG, MoA<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>From Bugs to Benchmarks: A Comprehensive Survey of Software Defect Datasets</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.17977"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://defect-datasets.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Davis, United States<br>
      • Paper Number: 226<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Cracking the Code of Action: a Generative Approach to Affordances for Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.17282"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McGill University<br>
      • Agent Name: CoGA (Code as Generative Affordances), Base Model: GPT-4, Strategy: Affordance-based action space pruning using pre-trained vision-language models<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Desideratum for Conversational Agents: Capabilities, Challenges, and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.16939"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/emrecanacikgoz/awesome-conversational-agents"><img src="https://img.shields.io/github/stars/emrecanacikgoz/awesome-conversational-agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Paper Number: 248<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey of AI Agent Protocols</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.16736"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Paper Number: 32<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Guiding VLM Agents with Process Rewards at Inference Time for GUI Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.16073"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: GuidNav, Base Model: GPT-4o, Gemini 2.0 Flash, Qwen-VL-Plus, Strategy: Process Reward Model<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Towards Test Generation from Task Description for Mobile Testing with Multi-modal Reasoning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.15917"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/visidroid/visidroid"><img src="https://img.shields.io/github/stars/visidroid/visidroid.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science, VNU-HCM<br>
      • Agent Name: VisiDroid, Base Model: GPT-4o, Strategy: Multi-modal reasoning with vision and memory mechanisms<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Multimodal Perception for Goal-oriented Navigation: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.15643"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and Technology, Tongji University, Shanghai 201804, China<br>
      • Paper Number: 199<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Agent for User: Testing Multi-User Interactive Features in TikTok</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.15474"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Monash University<br>
      • Agent Name: Multi-agent LLMs framework, Base Model: ChatGPT (gpt-4), Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Self-Improving Coding Agent</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.15228"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MaximeRobeyns/self_improving_coding_agent"><img src="https://img.shields.io/github/stars/MaximeRobeyns/self_improving_coding_agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Bristol<br>
      • Agent Name: SICA, Base Model: Sonnet 3.5 (v2), Strategy: Self-referential improvement via code edits and orchestration<br>
      • Benchmark Name: File editing benchmark, Task Number: Not explicitly mentioned, Dataset Source: Synthetically curated by cloning repositories<br>
      • Benchmark Name: Symbol navigation benchmark, Task Number: Not explicitly mentioned, Dataset Source: Synthetically curated by cloning Python repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>PLANET: A Collection of Benchmarks for Evaluating LLMs' Planning Capabilities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14773"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Computer Science Department, Emory University<br>
      • Benchmark Name: PLANET, Task Number: , Dataset Source: <br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>UFO2: The Desktop AgentOS</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14603"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/UFO/"><img src="https://img.shields.io/github/stars/UFO/.svg?style=social&label=Star"></a><br>
      <a href="https://microsoft.github.io/UFO/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: UFO2, Base Model: GPT-4o, Strategy: Deep OS Integration, Hybrid GUI-API Action Layer, Continuous Knowledge Integration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Meta-Thinking in LLMs via Multi-Agent Reinforcement Learning: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Oklahoma<br>
      • Paper Number: 122<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>VizTA: Enhancing Comprehension of Distributional Visualization with Visual-Lexical Fused Conversational Interface</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14507"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong University of Science and Technology (Guangzhou), Guangzhou, China<br>
      • Agent Name: VIZTA, Base Model: gpt-4o, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Toward Generation of Test Cases from Task Descriptions via History-aware Planning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14336"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/anonymoususer-26/HxAgent"><img src="https://img.shields.io/github/stars/anonymoususer-26/HxAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Faculty of Information Technology, University of Science, Ho Chi Minh city, Vietnam<br>
      • Agent Name: HxAgent, Base Model: GPT-4o, Strategy: Iterative LLM-based Agent Planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Diffusion-based Dynamic Contract for Federated AI Agent Construction in Mobile Metaverses</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14326"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: College of Computer Science and Technology, Nanjing University of Aeronautics and Astronautics, China<br>
      • Agent Name: Mobile AI Agent, Base Model: Qwen-VL-Plus, Qwen-VL-Max, Strategy: Diffusion-based Soft Actor-Critic (EDMSAC)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>InfiGUI-R1: Advancing Multimodal GUI Agents from Reactive Actors to Deliberative Reasoners</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14239"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Reallm-Labs/InfiGUI-R1"><img src="https://img.shields.io/github/stars/Reallm-Labs/InfiGUI-R1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: InfiGUI-R1-3B, Base Model: Qwen2.5-VL-3B-Instruct, Strategy: ['SFT', 'Reinforcement Learning']<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>DoomArena: A framework for Testing AI Agents Against Evolving Security Threats</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.14064"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ServiceNow/DoomArena"><img src="https://img.shields.io/github/stars/ServiceNow/DoomArena.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ServiceNow Research<br>
      • Benchmark Name: DoomArena, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>ViMo: A Generative Visual GUI World Model for App Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.13936"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ai-agents-2030.github.io/ViMo/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Queen Mary University of London<br>
      • Agent Name: ViMo, Base Model: GPT-4o, Strategy: Diffusion Model for GUI Prediction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey on (M)LLM-Based GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.13865"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zju-real/Awesome-GUI-Agents"><img src="https://img.shields.io/github/stars/zju-real/Awesome-GUI-Agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: Mobile-Agent, Base Model: GPT-4, Strategy: Prompt<br>
      • Agent Name: AppAgent, Base Model: GPT-4, Strategy: Prompt<br>
      • Agent Name: UFO, Base Model: GPT-Vision, Strategy: Prompt<br>
      • Agent Name: SeeClick, Base Model: Qwen2-VL, Strategy: Prompt<br>
      • Benchmark Name: ScreenSpot-Pro, Task Number: 30378, Dataset Source: human demonstration<br>
      • Benchmark Name: GUI Odyssey, Task Number: Not explicitly mentioned, Dataset Source: human demonstration<br>
      • Paper Number: 212<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Factors That Influence the Adoption of AI-enabled Conversational Agents (AICAs) as an Augmenting Therapeutic Tool by Frontline Healthcare Workers: From Technology Acceptance Model 3 (TAM3) Lens -- A Systematic Mapping Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.13183"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AI in Complex Systems Lab, University at Albany, SUNY<br>
      • Paper Number: 27<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Exploring Expert Failures Improves LLM Agent Tuning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.13145"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UCLA<br>
      • Agent Name: EEF, Base Model: LLama3 8B, Strategy: Exploring Expert Failures<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>InstructRAG: Leveraging Retrieval-Augmented Generation on Instruction Graphs for LLM-Based Task Planning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.13032"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Singapore Research Center<br>
      • Agent Name: InstructRAG, Base Model: , Strategy: Reinforcement Learning, Meta-Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>WebLists: Extracting Structured Information From Complex Interactive Websites Using Executable LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12682"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: College of Computing, Data Science, and Society, University of California Berkeley<br>
      • Agent Name: BardeenAgent, Base Model: GPT 4 Turbo, Strategy: Executable Agents<br>
      • Benchmark Name: WebLists, Task Number: 200, Dataset Source: live websites<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>TongUI: Building Generalized GUI Agents by Learning from Multimodal Web Tutorials</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12679"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://TongUI-agent.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory of General Artificial Intelligence, BIGAI<br>
      • Agent Name: TongUI, Base Model: Qwen2.5-VL-3B/7B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Framework for Information Disorder: Modeling Mechanisms and Implications Based on a Systematic Literature Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12537"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fundação Getulio Vargas / CNPq, São Paulo, Brazil<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12516"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/openai/simple-evals"><img src="https://img.shields.io/github/stars/openai/simple-evals.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OpenAI<br>
      • Benchmark Name: BrowseComp, Task Number: 1266, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Agentic AI Optimisation (AAIO): what it is, how it works, why it matters, and how to deal with it</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12482"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Digital Ethics Center, Yale University<br>
      • Agent Name: Agentic AI, Base Model: , Strategy: Structured data schemas, NLP optimisation, API integration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Towards LLM Agents for Earth Observation</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.12110"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://iandrover.github.io/UnivEarth/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University<br>
      • Benchmark Name: UnivEARTH, Task Number: 140, Dataset Source: NASA Earth Observatory articles<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Enhancing Web Agents with Explicit Rollback Mechanisms</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11788"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab<br>
      • Agent Name: Web Agent with Explicit Rollback Mechanism, Base Model: LLAMA-3.3-70B-Instruct, QWEN 2.5-72B-Instruct, Strategy: Rollback Mechanism<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Enhancing Web Agents with Explicit Rollback Mechanisms</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11788"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab<br>
      • Agent Name: Web Agent with Explicit Rollback Mechanism, Base Model: , Strategy: Explicit Rollback<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>GraphicBench: A Planning Benchmark for Graphic Design with Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11571"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/adobe-research"><img src="https://img.shields.io/github/stars/github.com/adobe-research.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland, College Park<br>
      • Agent Name: GRAPHIC TOWN, Base Model: , Strategy: <br>
      • Benchmark Name: GRAPHIC BENCH, Task Number: 1079, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>GraphicBench: A Planning Benchmark for Graphic Design with Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11571"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/adobe-research"><img src="https://img.shields.io/github/stars/github.com/adobe-research.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland, College Park<br>
      • Agent Name: GRAPHIC TOWN, Base Model: , Strategy: <br>
      • Benchmark Name: GRAPHIC BENCH, Task Number: 1079, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>REAL: Benchmarking Autonomous Agents on Deterministic Simulations of Real Websites</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11543"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agi-inc/agisdk"><img src="https://img.shields.io/github/stars/agi-inc/agisdk.svg?style=social&label=Star"></a><br>
      <a href="https://realevals.xyz"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The AGI Company<br>
      • Benchmark Name: REAL, Task Number: 112, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>REAL: Benchmarking Autonomous Agents on Deterministic Simulations of Real Websites</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11543"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/agi-inc/agisdk"><img src="https://img.shields.io/github/stars/agi-inc/agisdk.svg?style=social&label=Star"></a><br>
      <a href="https://realevals.xyz"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The AGI Company<br>
      • Benchmark Name: REAL, Task Number: 112, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>UI-E2I-Synth: Advancing GUI Grounding with Large-Scale Instruction Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11257"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research Asia<br>
      • Agent Name: UI-I2E-VLM, Base Model: InternVL2-4B, Qwen2-VL-7B, Strategy: Instruction Synthesis, Fine-tuning<br>
      • Benchmark Name: UI-I2E-Bench, Task Number: 1477, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>UI-E2I-Synth: Advancing GUI Grounding with Large-Scale Instruction Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.11257"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research Asia<br>
      • Agent Name: UI-I2E-VLM, Base Model: Qwen2-VL-7B, InternVL2-4B, Strategy: Fine-tuning using synthesized data<br>
      • Benchmark Name: UI-I2E-Bench, Task Number: 1477, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Deep Learning in Concealed Dense Prediction</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10979"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/PanchengZhao/Concealed-Dense-Prediction"><img src="https://img.shields.io/github/stars/PanchengZhao/Concealed-Dense-Prediction.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: College of Computer Science, Nankai University, Tianjin, China<br>
      • Paper Number: 222<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Adaptive Human-Agent Teaming: A Review of Empirical Studies from the Process Dynamics Perspective</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10918"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Paper Number: 191<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>GUI-R1 : A Generalist R1-Style Vision-Language Action Model For GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10458"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ritzz-ai/GUI-R1.git"><img src="https://img.shields.io/github/stars/ritzz-ai/GUI-R1.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences<br>
      • Agent Name: GUI-R1, Base Model: QwenVL2.5-3B/7B, Strategy: Reinforcement Fine-Tuning (RFT)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>RealWebAssist: A Benchmark for Long-Horizon Web Assistance with Real-World Users</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10445"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://scai.cs.jhu.edu/projects/RealWebAssist/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Johns Hopkins University<br>
      • Benchmark Name: RealWebAssist, Task Number: 107, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Ctrl-Z: Controlling AI Agents via Resampling</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10374"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Redwood Research<br>
      • Agent Name: Untrusted Model (U), Base Model: GPT-4o mini, Strategy: Scaffolded<br>
      • Benchmark Name: BashBench, Task Number: 257, Dataset Source: Unix StackExchange questions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey of Personalization: From RAG to Agent</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10147"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Applied-Machine-Learning-Lab/Awesome-Personalized-RAG-Agent"><img src="https://img.shields.io/github/stars/Applied-Machine-Learning-Lab/Awesome-Personalized-RAG-Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: City University of Hong Kong, Hong Kong<br>
      • Paper Number: 175<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Breaking the Data Barrier -- Building GUI Agents Through Task Generalization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.10127"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/hkust-nlp/GUIMid"><img src="https://img.shields.io/github/stars/hkust-nlp/GUIMid.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: GUI Agent, Base Model: Qwen2-VL-7B-Instruct, Strategy: Mid-training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey of Large Language Model-Powered Spatial Intelligence Across Scales: Advances in Embodied Agents, Smart Cities, and Earth Science</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.09848"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Electronic Engineering, BNRist, Tsinghua University, Beijing, China<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>AgentA/B: Automated and Scalable Web A/BTesting with Interactive LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.09723"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northeastern University<br>
      • Agent Name: AgentA/B, Base Model: Claude 3.5 Sonnet, Strategy: LLM-based autonomous agents with structured personas and embedded intentions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>UXAgent: A System for Simulating Usability Testing of Web Design with LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.09407"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northeastern University<br>
      • Agent Name: UXAgent, Base Model: Not explicitly mentioned, Strategy: Persona-based simulation, Dual Process Theory-inspired architecture<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey of Frontiers in LLM Reasoning: Inference Scaling, Learning to Reason, and Agentic Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.09037"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Salesforce AI Research<br>
      • Paper Number: 147<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>AgentRewardBench: Evaluating Automatic Evaluations of Web Agent Trajectories</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.08942"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://agent-reward-bench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McGill University<br>
      • Agent Name: Claude 3.7 Sonnet, Base Model: Anthropic Claude 3.7 Sonnet, Strategy: <br>
      • Agent Name: GPT-4o, Base Model: OpenAI GPT-4o, Strategy: <br>
      • Agent Name: Llama-3.3, Base Model: Llama 3.3, Strategy: <br>
      • Agent Name: Qwen2.5-VL, Base Model: Qwen2.5-VL, Strategy: <br>
      • Benchmark Name: AGENT REWARD BENCH, Task Number: 1302, Dataset Source: expert annotations<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>ScreenSpot-Pro: GUI Grounding for Professional High-Resolution Computer Use</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.07981"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gui-agent.github.io/grounding-leaderboard/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: ScreenSeekeR, Base Model: GPT-4o, Strategy: Visual Search<br>
      • Benchmark Name: ScreenSpot-Pro, Task Number: 1581, Dataset Source: expert annotations<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Agent That Debugs: Dynamic State-Guided Vulnerability Repair</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.07634"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beihang University<br>
      • Agent Name: VulDebugger, Base Model: GPT-4o, Strategy: Dynamic state-guided debugging using crash-free constraints<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Kimi-VL Technical Report</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.07491"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MoonshotAI/Kimi-VL"><img src="https://img.shields.io/github/stars/MoonshotAI/Kimi-VL.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Moonshot.ai<br>
      • Agent Name: Kimi-VL, Base Model: Moonlight, Strategy: Supervised Fine-Tuning (SFT), Reinforcement Learning (RL)<br>
      • Benchmark Name: ScreenSpot V2, Task Number: N/A, Dataset Source: human demonstration<br>
      • Benchmark Name: ScreenSpot Pro, Task Number: N/A, Dataset Source: expert-annotated tasks<br>
      • Benchmark Name: OSWorld, Task Number: N/A, Dataset Source: real computer environment<br>
      • Benchmark Name: WindowsAgentArena, Task Number: N/A, Dataset Source: realistic Windows environments<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.07079"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/SkillWeaver"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/SkillWeaver.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: SKILLWEAVER, Base Model: GPT-4o, Strategy: Self-Improvement through Exploration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Inducing Programmatic Skills for Agentic Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.06821"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zorazrw/agent-skill-induction"><img src="https://img.shields.io/github/stars/zorazrw/agent-skill-induction.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: ASI, Base Model: claude-3.5-sonnet, Strategy: Programmatic Skill Induction<br>
      • Benchmark Name: WebArena, Task Number: 812, Dataset Source: program-based evaluator<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>CAI: An Open, Bug Bounty-Ready Cybersecurity AI</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.06017"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aliasrobotics/cai"><img src="https://img.shields.io/github/stars/aliasrobotics/cai.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Alias Robotics<br>
      • Agent Name: CAI, Base Model: Claude-3.7-sonnet, Strategy: LLM-Assisted<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Playing Non-Embedded Card-Based Games with Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.04783"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/wty-yy/katacr"><img src="https://img.shields.io/github/stars/wty-yy/katacr.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Key Laboratory of Human-Machine Hybrid Augmented Intelligence, Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University<br>
      • Agent Name: Non-embedded offline reinforcement learning agent, Base Model: , Strategy: Offline Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Beyond Single-Turn: A Survey on Multi-Turn Interactions with Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.04717"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/yubol-cmu/Awesome-Multi-Turn-LLMs"><img src="https://img.shields.io/github/stars/yubol-cmu/Awesome-Multi-Turn-LLMs.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Paper Number: 272<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>MCP Safety Audit: LLMs with the Model Context Protocol Allow Major Security Exploits</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.03767"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/johnhalloran321/mcpSafetyScanner"><img src="https://img.shields.io/github/stars/johnhalloran321/mcpSafetyScanner.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Leidos<br>
      • Agent Name: McpSafetyScanner, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Agentic Knowledgeable Self-awareness</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.03553"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zjunlp/KnowSelf"><img src="https://img.shields.io/github/stars/zjunlp/KnowSelf.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: KnowSelf, Base Model: , Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Talk2X -- An Open-Source Toolkit Facilitating Deployment of LLM-Powered Chatbots on the Web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.03343"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aiondemand/aiod-chatbot"><img src="https://img.shields.io/github/stars/aiondemand/aiod-chatbot.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: German Research Center for Artificial Intelligence, RPTU Kaiserslautern-Landau<br>
      • Agent Name: Talk2X, Base Model: GPT4o-mini, Strategy: Function Calling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.03160"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/GAIR-NLP/DeepResearcher"><img src="https://img.shields.io/github/stars/GAIR-NLP/DeepResearcher.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: SJTU<br>
      • Agent Name: DeepResearcher, Base Model: Qwen2.5-7B-Instruct, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Affordable AI Assistants with Knowledge Graph of Thoughts</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.02670"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/spcl/knowledge-graph-of-thoughts"><img src="https://img.shields.io/github/stars/spcl/knowledge-graph-of-thoughts.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ETH Zurich, Zurich, Switzerland<br>
      • Agent Name: Knowledge Graph of Thoughts (KGoT), Base Model: GPT-4o mini, Strategy: Knowledge Graph Construction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>ReuseDroid: A VLM-empowered Android UI Test Migrator Boosted by Active Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.02357"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Engineering, The Hong Kong University of Science and Technology, China<br>
      • Agent Name: R EUSE DROID, Base Model: GPT-4o, Strategy: Multi-Agent Framework<br>
      • Benchmark Name: LinPro, Task Number: 578, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>A Survey of Scaling in Large Language Model Reasoning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.02181"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Virginia<br>
      • Paper Number: 245<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>LLMs Working in Harmony: A Survey on the Technological Aspects of Building Effective LLM-Based Multi Agent Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.01963"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Faculty of Computing, General Sir John Kotelawala Defence University, Ratmalana, Sri Lanka<br>
      • Paper Number: 27<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Review, Refine, Repeat: Understanding Iterative Decoding of AI Agents with Dynamic Evaluation and Selection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.01931"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google<br>
      • Agent Name: Iterative Agent Decoding (IAD), Base Model: Gemini-1.5, Strategy: Verifier-guided Feedback<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>PaperBench: Evaluating AI's Ability to Replicate AI Research</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.01848"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OpenAI<br>
      • Benchmark Name: PaperBench, Task Number: 20, Dataset Source: human-graded submissions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Are Autonomous Web Agents Good Testers?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.01495"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Smartesting, France<br>
      • Agent Name: SeeAct-ATA, Base Model: GPT-4o, Strategy: Prompt<br>
      • Agent Name: PinATA, Base Model: GPT-4o, Strategy: Planning with Feedback<br>
      • Benchmark Name: A Benchmark for Assessing ATA Effectiveness, Task Number: 113, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>An Illusion of Progress? Assessing the Current State of Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.01382"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/Online-Mind2Web"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/Online-Mind2Web.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Benchmark Name: Online-Mind2Web, Task Number: 300, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Agent S2: A Compositional Generalist-Specialist Framework for Computer Use Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.00906"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/simular-ai/Agent-S"><img src="https://img.shields.io/github/stars/simular-ai/Agent-S.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Simular Research<br>
      • Agent Name: Agent S2, Base Model: Claude-3.7-Sonnet, Strategy: Mixture of Grounding, Proactive Hierarchical Planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2025</td>
    <td style="width: 40%;"><strong>Command A: An Enterprise-Ready Large Language Model</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2504.00698"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cohere<br>
      • Agent Name: Command A, Base Model: Command A, Strategy: SFT, Preference Tuning, Reinforcement Learning<br>
      • Benchmark Name: Taubench, Task Number: Not specified, Dataset Source: human demonstration, synthetic generation<br>
      • Benchmark Name: BFCL, Task Number: Not specified, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Navi-plus: Managing Ambiguous GUI Navigation Tasks with Follow-up</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.24180"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications<br>
      • Agent Name: Navi-plus Agent, Base Model: Qwen2.5-VL-3B, SpiritSight-Agent-8B-base, Strategy: LoRA fine-tuning<br>
      • Benchmark Name: Navi-plus, Task Number: Not explicitly mentioned, Dataset Source: Constructed from existing trajectory datasets (AndroidControl, Mind2Web) using open-source LLMs<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Towards Trustworthy GUI Agents: A Survey</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23434"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Georgia<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey of WebAgents: Towards Next-Generation AI Agents for Web Automation with Large Foundation Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23350"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong Polytechnic University<br>
      • Paper Number: 190<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Conversational Agents for Older Adults' Health: A Systematic Literature Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23153"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Texas at Austin, USA<br>
      • Paper Number: 72<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>CodeARC: Benchmarking Reasoning Capabilities of LLM Agents for Inductive Program Synthesis</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23145"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Benchmark Name: CodeARC, Task Number: 1114, Dataset Source: curated synthesis traces<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Efficient Inference for Large Reasoning Models: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23077"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs"><img src="https://img.shields.io/github/stars/yueliu1999/Awesome-Efficient-Inference-for-LRMs.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Agentic Large Language Models, a survey</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.23037"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://askeplaat.github.io/agentic-llm-survey-site/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Leiden University, Netherlands<br>
      • Agent Name: AssistantGPT, Base Model: Not explicitly mentioned, Strategy: finetuning, planner, memory<br>
      • Agent Name: MUCA, Base Model: Not explicitly mentioned, Strategy: multi-user chat framework<br>
      • Agent Name: FinRobot, Base Model: finetuned LLM, Strategy: document analysis and generation<br>
      • Benchmark Name: WebArena, Task Number: Not explicitly mentioned, Dataset Source: Not explicitly mentioned<br>
      • Benchmark Name: BenchAgents, Task Number: Not explicitly mentioned, Dataset Source: agent interaction<br>
      • Benchmark Name: AgentBoard, Task Number: Not explicitly mentioned, Dataset Source: Not explicitly mentioned<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.22738"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://shieldagent-aiguard.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Chicago<br>
      • Agent Name: SHIELD AGENT, Base Model: GPT-4o, Strategy: Probabilistic Policy Reasoning<br>
      • Benchmark Name: SHIELD AGENT-BENCH, Task Number: 3110, Dataset Source: SOTA attacks across 6 web environments and 7 risk categories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Evaluating LLM-based Agents for Multi-Turn Conversations: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.22458"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft, China<br>
      • Paper Number: 250<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>UI-R1: Enhancing Efficient Action Prediction of GUI Agents by Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21620"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lll6gg/UI-R1"><img src="https://img.shields.io/github/stars/lll6gg/UI-R1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: vivo AI Lab<br>
      • Agent Name: UI-R1, Base Model: Qwen2.5-VL-3B, Strategy: Rule-Based Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Measure Based Generalizable Approach to Understandability</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21615"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Indian Institute of Technology Kanpur<br>
      • Paper Number: 58<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21614"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/XiaoYee/Awesome_Efficient_LRM_Reasoning"><img src="https://img.shields.io/github/stars/XiaoYee/Awesome_Efficient_LRM_Reasoning.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai AI Laboratory<br>
      • Paper Number: 128<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Large Language Model Agent: A Survey on Methodology, Applications and Challenges</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21460"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/luo-junyu/Awesome-Agent-Papers"><img src="https://img.shields.io/github/stars/luo-junyu/Awesome-Agent-Papers.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and PKU-Anker LLM Lab, Peking University, Beijing, China<br>
      • Agent Name: Voyager, Base Model: GPT-4, Strategy: Lifelong learning<br>
      • Agent Name: KnowAgent, Base Model: GPT-4, Strategy: Knowledge-augmented planning<br>
      • Agent Name: RecAgent, Base Model: , Strategy: Tool use decision<br>
      • Benchmark Name: AgentBench, Task Number: 8 interactive environments, Dataset Source: human demonstration<br>
      • Benchmark Name: OSWorld, Task Number: 369 multi-application tasks, Dataset Source: real computer ecosystem<br>
      • Paper Number: 270<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>From Deep Learning to LLMs: A survey of AI in Quantitative Investment</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21422"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong University of Science and Technology (Guangzhou), China and IDEA Research, International Digital Economy Academy, China<br>
      • Paper Number: 186<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Cultivating Game Sense for Yourself: Making VLMs Gaming Experts</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.21263"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute of Information Engineering, Chinese Academy of Sciences<br>
      • Agent Name: GameSense, Base Model: Qwen 2.5 VL, Strategy: Paradigm Shift<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Semantic Web and Software Agents -- A Forgotten Wave of Artificial Intelligence?</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20793"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Aalto University<br>
      • Paper Number: 28<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Prompting is Not All You Need! Evaluating LLM Agent Simulation Methodologies with Real-World Online Customer Behavior Data</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20749"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Amazon.com, Inc.<br>
      • Agent Name: Fine-tuned LLM Agent, Base Model: Qwen2.5-7B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Harmonia: A Multi-Agent Reinforcement Learning Approach to Data Placement and Migration in Hybrid Storage Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20507"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ETH Zürich<br>
      • Agent Name: Harmonia, Base Model: , Strategy: Multi-Agent Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>sudo rm -rf agentic_security</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20279"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AIM-Intelligence/SUDO"><img src="https://img.shields.io/github/stars/AIM-Intelligence/SUDO.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Aim Intelligence<br>
      • Agent Name: SUDO, Base Model: Claude 3.5, GPT-4o, Llama 3.2 Vision, Gemini 2.0, Claude 3.7, Strategy: DETOX 2TOX mechanism<br>
      • Benchmark Name: SUDO dataset, Task Number: 50, Dataset Source: manually crafted curated suite of malicious tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Open Deep Search: Democratizing Search with Open-source Reasoning Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20201"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sentient-agi/OpenDeepSearch"><img src="https://img.shields.io/github/stars/sentient-agi/OpenDeepSearch.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sentient<br>
      • Agent Name: Open Reasoning Agent, Base Model: DeepSeek-R1, Llama3.1-70B, Strategy: ReAct, CodeAct<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>BugCraft: End-to-End Crash Bug Reproduction Using LLM Agents in Minecraft</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20036"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://bugcraft2025.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Computer Engineering Department, Bilkent University<br>
      • Agent Name: BugCraft, Base Model: GPT-4o, Strategy: Prompt<br>
      • Benchmark Name: BugCraft-Bench, Task Number: 86, Dataset Source: Mojira bug reports<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>OmniNova:A General Multimodal Agent Framework</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.20028"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Omni-AI<br>
      • Agent Name: OmniNova, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Inducing Personality in LLM-Based Honeypot Agents: Measuring the Effect on Human-Like Agenda Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.19752"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computing and Communications, Lancaster University, UK<br>
      • Agent Name: SANDMAN, Base Model: GPT-3.5-Turbo, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Enabling Rapid Shared Human-AI Mental Model Alignment via the After-Action Review</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.19607"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MITLL-SMMAAL/pub_HMT_AAEtool_and_testbed"><img src="https://img.shields.io/github/stars/MITLL-SMMAAL/pub_HMT_AAEtool_and_testbed.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Lincoln Laboratory, Massachusetts Institute of Technology<br>
      • Agent Name: Decision Tree AI, Base Model: , Strategy: <br>
      • Agent Name: LLM-enabled AI, Base Model: ChatGPT, Strategy: <br>
      • Benchmark Name: Minecraft Human-Machine Teaming testbed, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Agent-Initiated Interaction in Phone UI Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.19537"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/android_interaction"><img src="https://img.shields.io/github/stars/master/android_interaction.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Benchmark Name: AndroidInteraction, Task Number: 772, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey of Large Language Model Agents for Question Answering</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.19213"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: George Mason University<br>
      • Paper Number: 94<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Boosting Virtual Agent Learning and Reasoning: A Step-wise, Multi-dimensional, and Generalist Reward Model with Benchmark</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.18665"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Similar-v1"><img src="https://img.shields.io/github/stars/github.com/Similar-v1.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: Similar, Base Model: pre-trained decoder-only MLLM, Strategy: Triple-M strategy (multi-step, multi-objective, and multi-modal)<br>
      • Benchmark Name: SRM, Task Number: 110k, Dataset Source: automatically annotated using MCTS-P algorithm<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Safeguarding Mobile GUI Agent via Logic-based Action Verification</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.18492"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computing, KAIST<br>
      • Agent Name: VeriSafe Agent (VSA), Base Model: GPT-4o, Strategy: Logic-based Action Verification<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Mind with Eyes: from Language Reasoning to Multimodal Reasoning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.18071"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning"><img src="https://img.shields.io/github/stars/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Paper Number: 77<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Building Resource-Constrained Language Agents: A Korean Case Study on Chemical Toxicity Information</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.17753"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST AI<br>
      • Agent Name: Tox-chat, Base Model: Llama-8B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.17709"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/921112343/GUI-Xplore"><img src="https://img.shields.io/github/stars/921112343/GUI-Xplore.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Information Science and Electronic Engineering, Shanghai Jiao Tong University<br>
      • Agent Name: Xplore-Agent, Base Model: QwenVL-7B, Strategy: Action-aware GUI Modeling and Graph-Guided Environment Reasoning<br>
      • Benchmark Name: GUI-Xplore, Task Number: 5, Dataset Source: pre-recorded exploration videos and human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Large language model-powered AI systems achieve self-replication with no human intervention</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.17378"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Fudan University<br>
      • Benchmark Name: Self-Replication Capability Evaluation, Task Number: Not explicitly mentioned, Dataset Source: Not explicitly mentioned<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Web Application Vulnerabilities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.17332"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/uiuc-kang-lab/cve-bench.git"><img src="https://img.shields.io/github/stars/uiuc-kang-lab/cve-bench.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Siebel School of Computing and Data Science, University of Illinois, Urbana-Champaign, USA<br>
      • Agent Name: Cy-Agent, Base Model: gpt-4o-2024-11-20, Strategy: ReAct-style agent framework<br>
      • Agent Name: T-Agent, Base Model: gpt-4o-2024-11-20, Strategy: Teams of specialized hacker agents with hierarchical planning<br>
      • Agent Name: AutoGPT, Base Model: gpt-4o-2024-11-20, Strategy: Self-criticism and self-correction mechanism<br>
      • Benchmark Name: CVE-Bench, Task Number: 40, Dataset Source: Common Vulnerabilities and Exposures (CVEs) from the National Vulnerability Database (NVD)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Big Help or Big Brother? Auditing Tracking, Profiling, and Personalization in Generative AI Assistants</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16586"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Davis<br>
      • Paper Number: 53<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Comprehensive Review of Reinforcement Learning for Medical Ultrasound Imaging</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16543"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Concordia Institute for Information Systems Engineering, Concordia University, Montreal, Canada<br>
      • Paper Number: 89<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16465"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Wuzheng02/OS-Kairos"><img src="https://img.shields.io/github/stars/Wuzheng02/OS-Kairos.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: OS-Kairos, Base Model: OS-Atlas-Pro-7B, Strategy: Confidence-driven Interaction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>The Application of MATEC (Multi-AI Agent Team Care) Framework in Sepsis Care</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16433"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University, Princeton, NJ<br>
      • Agent Name: MATEC (Multi-AI Agent Team Care), Base Model: Not explicitly mentioned, Strategy: Prompt engineering, Chain of Thought (CoT) Reasoning, ReAct, RAG (Retriever-Augmented Generation)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Survey on Evaluation of LLM-based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16416"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hebrew University of Jerusalem<br>
      • Paper Number: 200<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Real AI Agents with Fake Memories: Fatal Context Manipulation Attacks on Web3 Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16248"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University<br>
      • Agent Name: ElizaOS, Base Model: GPT-4o, Strategy: Prompt<br>
      • Benchmark Name: CrAIBench, Task Number: 135, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>The Lighthouse of Language: Enhancing LLM Agents via Critique-Guided Improvement</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.16024"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Agent Name: Critique-Guided Improvement (CGI), Base Model: Llama-3-8B-Instruct, Strategy: Supervised Fine-Tuning (SFT)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Unreal-MAP: Unreal-Engine-Based General Platform for Multi-Agent Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.15947"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/binary-husky/unreal-map"><img src="https://img.shields.io/github/stars/binary-husky/unreal-map.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Artificial Intelligence, University of Chinese Academy of Sciences, Beijing<br>
      • Benchmark Name: Unreal-MAP, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.15937"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University<br>
      • Agent Name: V-Droid, Base Model: Llama-3.1-8B, Strategy: Pairwise Process Preference (P3) training, Human-Agent Joint Annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>UI-Vision: A Desktop-centric GUI Benchmark for Visual Perception and Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.15661"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://uivision.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Mila - Quebec AI Institute<br>
      • Benchmark Name: UI-Vision, Task Number: 8227, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Towards Computer-Using Personal Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.15515"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Naples Federico II, Italy<br>
      • Agent Name: CUPA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>EnvBench: A Benchmark for Automated Environment Setup</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.14443"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/JetBrains-Research/EnvBench"><img src="https://img.shields.io/github/stars/JetBrains-Research/EnvBench.svg?style=social&label=Star"></a><br>
      <a href="https://jb.gg/envbench"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: JetBrains Research<br>
      • Agent Name: Bash Agent, Base Model: GPT-4o, Strategy: ReAct<br>
      • Agent Name: Installamatic Agent, Base Model: GPT-4o, Strategy: Documentation Gathering and Dockerfile Build stages<br>
      • Benchmark Name: ENVBENCH, Task Number: 994, Dataset Source: GitHub repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>DARS: Dynamic Action Re-Sampling to Enhance Coding Agent Performance by Adaptive Tree Traversal</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.14269"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/darsagent/DARS-Agent"><img src="https://img.shields.io/github/stars/darsagent/DARS-Agent.svg?style=social&label=Star"></a><br>
      <a href="https://darsagent.github.io/DARS-Agent/models"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sprinklr<br>
      • Agent Name: DARS, Base Model: Claude 3.5 Sonnet V2, Strategy: Dynamic Action Re-Sampling<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>WebNav: An Intelligent Agent for Voice-Controlled Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.13843"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cyrion Labs<br>
      • Agent Name: WebNav, Base Model: Google Generative AI model ('gemini-2.0-flash-thinking-exp-01-21'), Strategy: ReAct-inspired architecture<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>How Metacognitive Architectures Remember Their Own Thoughts: A Systematic Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.13467"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://dml.uni-bremen.de/ease/review"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Digital Media Lab, University of Bremen<br>
      • Paper Number: 101<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>MicroVQA: A Multimodal Reasoning Benchmark for Microscopy-Based Scientific Research</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.13399"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: MicroVQA-Agent, Base Model: GPT-4o, Strategy: Prompt Optimization<br>
      • Benchmark Name: MicroVQA, Task Number: 1042, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>AI Agents: Evolution, Architecture, and Real-World Applications</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.12687"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: nan<br>
      • Paper Number: 52<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>STEVE: A Step Verification Pipeline for Computer-use Agent Training</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.12532"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/FanbinLu/STEVE"><img src="https://img.shields.io/github/stars/FanbinLu/STEVE.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: CUHK<br>
      • Agent Name: STEVE, Base Model: Qwen2-VL 7B, Strategy: Kahneman & Tversky Optimization (KTO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey on the Optimization of Large Language Model-based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.12434"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/YoungDubbyDu/LLM-Agent-Optimization"><img src="https://img.shields.io/github/stars/YoungDubbyDu/LLM-Agent-Optimization.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Institute of Artificial Intelligence for Education, East China Normal University; School of Computer Science and Technology, East China Normal University, China<br>
      • Paper Number: 220<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>SPIN-Bench: How Well Do LLMs Plan Strategically and Reason Socially?</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.12349"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://spinbench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Electrical and Computer Engineering, Princeton University, New Jersey, US<br>
      • Benchmark Name: SPIN-Bench, Task Number: 1280, Dataset Source: PDDL competition benchmarks and additional domains<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.12163"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/AgentDroid/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Chongqing University, China<br>
      • Agent Name: AgentDroid, Base Model: GPT-4o, Strategy: Multi-Agent Collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>LLM Agents for Education: Advances and Applications</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.11733"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Squirrel Ai Learning, USA<br>
      • Paper Number: 258<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>DeskVision: Large Scale Desktop Region Captioning for Advanced GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.11170"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Moore Threads AI<br>
      • Agent Name: GUIExplorer, Base Model: Qwen-2, Strategy: Fine-tuning with DeskVision data<br>
      • Benchmark Name: DeskVision-Eval, Task Number: 5000, Dataset Source: human annotation and automated pipeline<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>API Agents vs. GUI Agents: Divergence and Convergence</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.11069"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Attacking Multimodal OS Agents with Malicious Image Patches</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.10809"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AIchberger/mip-os-agent-attacks"><img src="https://img.shields.io/github/stars/AIchberger/mip-os-agent-attacks.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Johannes Kepler University Linz, Austria<br>
      • Agent Name: OS Agent, Base Model: Llama 3.2 Vision model series, Strategy: Adversarial Image Patches<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Learning to Contextualize Web Pages for Enhanced Decision Making by LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.10689"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://lcowiclr2025.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST AI<br>
      • Agent Name: LCoW, Base Model: Various LLMs (e.g., GPT-4o, Gemini-1.5-flash, Claude-3.5-Sonnet), Strategy: Contextualization Module<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Inter-environmental world modeling for continuous and compositional dynamics</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09911"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Preferred Networks, Inc.<br>
      • Agent Name: WLA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09780"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FAIR at Meta<br>
      • Benchmark Name: AGENT DAM, Task Number: 246, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey on Trustworthy LLM Agents: Threats and Countermeasures</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09648"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Ymm-cll/TrustAgent"><img src="https://img.shields.io/github/stars/Ymm-cll/TrustAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Squirrel AI Learning<br>
      • Paper Number: 148<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09572"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: PLAN-AND-ACT, Base Model: LLaMA-3.3-70B-Instruct, Strategy: Synthetic Data Generation, Dynamic Replanning, Chain-of-Thought Reasoning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>COLA: A Scalable Multi-Agent Framework For Windows UI Task Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09263"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Alokia/COLA-demo"><img src="https://img.shields.io/github/stars/Alokia/COLA-demo.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Defense Technology<br>
      • Agent Name: COLA, Base Model: GPT-4o, Strategy: Hierarchical task resolution through specialized agent roles<br>
      • Benchmark Name: GAIA, Task Number: 466, Dataset Source: human-designed and annotated questions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>In-Context Defense in Computer Agents: An Empirical Study</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.09241"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Show Lab, National University of Singapore<br>
      • Agent Name: VisualWebArena agent, Base Model: GPT-4o, Strategy: In-Context Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Agentic AI for Scientific Discovery: A Survey of Progress, Challenges, and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.08979"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IQVIA<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>An Autonomous RL Agent Methodology for Dynamic Web UI Testing in a BDD Framework</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.08464"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Kansas State University<br>
      • Agent Name: Autonomous RL Agent, Base Model: , Strategy: Deep Q-Networks (DQN), Policy Gradient Methods, Epsilon-Greedy Exploration, Backtracking Mechanisms<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Guess What I am Thinking: A Benchmark for Inner Thought Reasoning of Role-Playing Language Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.08193"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/airaer1998/RPA_Thought"><img src="https://img.shields.io/github/stars/airaer1998/RPA_Thought.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Benchmark Name: ROLETHINK, Task Number: 616, Dataset Source: A Song of Ice and Fire series<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>BEARCUBS: A benchmark for computer-using web agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.07919"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://bear-cubs.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UMass Amherst<br>
      • Benchmark Name: BEARCUBS, Task Number: 111, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>OWLViz: An Open-World Benchmark for Visual Question Answering</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.07631"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Reason Foundation<br>
      • Benchmark Name: OWLViz, Task Number: 194, Dataset Source: human-designed and annotated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>ProjectEval: A Benchmark for Programming Agents Automated Evaluation on Project-Level Code Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.07010"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/RyanLoil/ProjectEval/"><img src="https://img.shields.io/github/stars/ProjectEval/.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, Shenzhen, China<br>
      • Benchmark Name: ProjectEval, Task Number: 20, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Agent models: Internalizing Chain-of-Action Generation into Reasoning models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.06580"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ADaM-BJTU/AutoCoA"><img src="https://img.shields.io/github/stars/ADaM-BJTU/AutoCoA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and Technology, Beijing Jiaotong University<br>
      • Agent Name: AutoCoA, Base Model: R1-Distill-Qwen-7B, Strategy: SFT, RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>MastermindEval: A Simple But Scalable Reasoning Benchmark</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.05891"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/flairNLP/mastermind"><img src="https://img.shields.io/github/stars/flairNLP/mastermind.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Humboldt-Universität zu Berlin<br>
      • Benchmark Name: MASTERMIND EVAL, Task Number: 30000+, Dataset Source: pre-played game states generated using Knuth’s algorithm<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A Survey of Large Language Model Empowered Agents for Recommendation and Search: Towards Next-Generation Information Retrieval</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.05659"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tsinghua-fib-lab/LLM-Agent-for-Recommendation-and-Search"><img src="https://img.shields.io/github/stars/tsinghua-fib-lab/LLM-Agent-for-Recommendation-and-Search.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: AutoConcierge, Base Model: , Strategy: <br>
      • Agent Name: RecAI, Base Model: , Strategy: <br>
      • Agent Name: AgentCF, Base Model: , Strategy: <br>
      • Agent Name: Laser, Base Model: , Strategy: <br>
      • Agent Name: CoSearchAgent, Base Model: , Strategy: <br>
      • Agent Name: AVATAR, Base Model: , Strategy: <br>
      • Agent Name: EASYTOOL, Base Model: , Strategy: <br>
      • Agent Name: CodeAct, Base Model: , Strategy: <br>
      • Agent Name: PersonaRAG, Base Model: , Strategy: <br>
      • Agent Name: ChatCite, Base Model: , Strategy: <br>
      • Paper Number: 191<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>FedMABench: Benchmarking Mobile Agents on Decentralized Heterogeneous User Data</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.05143"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/wwh0411/FedMABench"><img src="https://img.shields.io/github/stars/wwh0411/FedMABench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Benchmark Name: FedMABench, Task Number: 877 apps across 5 categories, Dataset Source: derived from Android Control and Android in the Wild datasets<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>SafeArena: Evaluating the Safety of Autonomous Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.04957"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://safearena.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McGill University<br>
      • Agent Name: Claude-3.5-Sonnet, Base Model: Claude-3.5-Sonnet, Strategy: Prompt<br>
      • Agent Name: GPT-4o, Base Model: GPT-4o, Strategy: Prompt<br>
      • Agent Name: GPT-4o-Mini, Base Model: GPT-4o-Mini, Strategy: Prompt<br>
      • Agent Name: Llama-3.2-90B, Base Model: Llama-3.2-90B, Strategy: Prompt<br>
      • Agent Name: Qwen-2-VL-72B, Base Model: Qwen-2-VL-72B, Strategy: Prompt<br>
      • Benchmark Name: SAFEARENA, Task Number: 500, Dataset Source: human demonstration and LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>DiMA: An LLM-Powered Ride-Hailing Assistant at DiDi</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.04768"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/usail-hkust/DiMA"><img src="https://img.shields.io/github/stars/usail-hkust/DiMA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong University of Science and Technology (Guangzhou)<br>
      • Agent Name: DiMA, Base Model: Qwen2-72B, Qwen2-7B, Qwen1.5-32B, Strategy: Continual Fine-tuning, Cost-aware LLM Configuration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>WinClick: GUI Grounding with Multimodal Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.04730"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zackhuiiiii/WinSpot"><img src="https://img.shields.io/github/stars/zackhuiiiii/WinSpot.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: WinClick, Base Model: Phi3-vision, Strategy: Fine-tuning<br>
      • Benchmark Name: WinSpot, Task Number: 5000+, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>SurveyForge: On the Outline Heuristics, Memory-Driven Generation, and Multi-dimensional Evaluation for Automated Survey Writing</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.04629"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Alpha-Innovator/SurveyForge"><img src="https://img.shields.io/github/stars/Alpha-Innovator/SurveyForge.svg?style=social&label=Star"></a><br>
      <a href="https://huggingface.co/datasets/U4R/SurveyBench"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Artificial Intelligence Laboratory<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>CHOP: Mobile Operating Assistant with Constrained High-frequency Optimized Subtask Planning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.03743"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Yuqi-Zhou/CHOP"><img src="https://img.shields.io/github/stars/Yuqi-Zhou/CHOP.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: CHOP, Base Model: GPT-4o, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>SpiritSight Agent: Advanced GUI Agent with One Look</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.03196"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/SenseLLM/SpiritSight-Agent-8B"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: SenseTime Research<br>
      • Agent Name: SpiritSight, Base Model: InternVL2, Strategy: Universal Block Parsing (UBP)<br>
      • Benchmark Name: GUI-Lasagne, Task Number: 5730496, Dataset Source: real-world and filtered through carefully designed rules<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>A2Perf: Real-World Autonomous Agents Benchmark</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.03056"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google_research/circuit_training"><img src="https://img.shields.io/github/stars/google_research/circuit_training.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
      • Benchmark Name: A2Perf, Task Number: 3, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>LiteWebAgent: The Open-Source Suite for VLM-Based Web-Agent Applications</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.02950"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/PathOnAI/LiteWebAgent"><img src="https://img.shields.io/github/stars/PathOnAI/LiteWebAgent.svg?style=social&label=Star"></a><br>
      <a href="https://lite-web-agent.vercel.app/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: PathOnAI.org<br>
      • Agent Name: LiteWebAgent, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>"Would You Want an AI Tutor?" Understanding Stakeholder Perceptions of LLM-based Chatbots in the Classroom</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.02885"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: New York University<br>
      • Paper Number: 89<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>AutoEval: A Practical Framework for Autonomous Evaluation of Mobile Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.02403"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Benchmark Name: AutoEval, Task Number: 93, Dataset Source: existing mobile agent benchmarks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>AppAgentX: Evolving GUI Agents as Proficient Smartphone Users</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.02268"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://appagentx.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Westlake University<br>
      • Agent Name: AppAgentX, Base Model: GPT-4o, Strategy: Evolutionary Mechanism<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Interactive Debugging and Steering of Multi-Agent AI Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.02068"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/agdebugger"><img src="https://img.shields.io/github/stars/microsoft/agdebugger.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Towards Enterprise-Ready Computer Using Generalist Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.01861"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://cuga.dev/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IBM Research<br>
      • Agent Name: IBM CUGA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Evaluation and Facilitation of Online Discussions in the LLM Era: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.01513"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Archimedes/Athena RC, Greece<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2025</td>
    <td style="width: 40%;"><strong>Smoothing Grounding and Reasoning for MLLM-Powered GUI Agents with Query-Oriented Pivot Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2503.00401"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ZrW00/GUIPivot"><img src="https://img.shields.io/github/stars/ZrW00/GUIPivot.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: query inference, Base Model: Qwen2-VL-7B-Instruct, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Why Are Web AI Agents More Vulnerable Than Standalone LLMs? A Security Analysis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.20383"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://vulnerable-ai-agents.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>VEM: Environment-Free Exploration for Training GUI Agent with Value Environment Model</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.18906"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/GUI-Agent-RL"><img src="https://img.shields.io/github/stars/microsoft/GUI-Agent-RL.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Peking University<br>
      • Agent Name: VEM, Base Model: Qwen2VL, Strategy: PPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>AgentSociety Challenge: Designing LLM Agents for User Modeling and Recommendation on Web Platforms</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.18754"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tsinghua-fib-lab/AgentSocietyChallenge/tree/main/GTsimulation"><img src="https://img.shields.io/github/stars/main/GTsimulation.svg?style=social&label=Star"></a><br>
      <a href="https://tsinghua-fib-lab.github.io/AgentSocietyChallenge"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: AgentSociety Challenge, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>ARACNE: An LLM-Based Autonomous Shell Pentesting Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.18528"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Colegio Nacional de Buenos Aires<br>
      • Agent Name: ARACNE, Base Model: GPT-O3-mini, Strategy: Jailbreak<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>WebGames: Challenging General-Purpose Web-Browsing AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.18356"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/convergence-ai/webgames"><img src="https://img.shields.io/github/stars/convergence-ai/webgames.svg?style=social&label=Star"></a><br>
      <a href="https://webgames.convergence.ai"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Convergence Labs Ltd.<br>
      • Benchmark Name: WebGames, Task Number: 50+, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Carbon and Silicon, Coexist or Compete? A Survey on Human-AI Interactions in Agent-based Modeling and Simulation</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.18145"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Paper Number: 97<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Survey on Strategic Mining in Blockchain: A Reinforcement Learning Approach</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.17307"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhongguancun Laboratory<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Mobile-Agent-V: Learning Mobile Device Operation Through Video-Guided Multi-Agent Collaboration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.17110"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/X-PLUG/MobileAgent"><img src="https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Agent Name: Mobile-Agent-V, Base Model: GPT-4o, Strategy: multi-agent collaboration<br>
      • Benchmark Name: Mobile-Agent-V Benchmark, Task Number: 3, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Generative Models in Decision Making: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.17100"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab, China<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Multi-Agent Autonomous Driving Systems with Large Language Models: A Survey of Recent Advances</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.16804"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/LLM-based_Multi-agent_ADS-3A5C/README.md"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Tokyo<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>MobileSteward: Integrating Multiple App-Oriented Agents with Self-Evolution to Automate Cross-App Instructions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.16796"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: MobileSteward, Base Model: GPT-4v, Strategy: Prompt<br>
      • Benchmark Name: CAPBench, Task Number: 500, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Contemporary Survey on Semantic Communications:Theory of Mind, Generative AI, and Deep Joint Source-Channel Coding</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.16468"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Kyung Hee University<br>
      • Paper Number: 201<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Statistical Inference in Reinforcement Learning: A Selective Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.16195"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Statistics, London School of Economics and Political Science, London WC2A 2AE, U.K.<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Digi-Q: Learning Q-Value Functions for Training Device-Control Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15760"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/DigiRL-agent/digiq"><img src="https://img.shields.io/github/stars/DigiRL-agent/digiq.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: Digi-Q, Base Model: VLM, Strategy: TD-learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Level-Navi Agent: A Framework and benchmark for Chinese Web Search Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15690"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/assistgui"><img src="https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: 360 AI Research<br>
      • Agent Name: Level-Navi Agent, Base Model: , Strategy: <br>
      • Benchmark Name: Web24, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>XPath Agent: An Efficient XPath Programming Agent Based on LLM for Web Crawler</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15688"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/eavae/feilian"><img src="https://img.shields.io/github/stars/eavae/feilian.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: lijingyu68@gmail.com<br>
      • Agent Name: XPath Agent, Base Model: LLM, Strategy: Two-stage pipeline<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Construction and Evaluation of LLM-based agents for Semi-Autonomous penetration testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15506"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meiji University<br>
      • Agent Name: LLM-based agent system, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Auto-Bench: An Automated Benchmark for Scientific Discovery in LLMs</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15224"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Benchmark Name: Auto-Bench, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>The Evolving Landscape of LLM- and VLM-Integrated Reinforcement Learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.15214"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Alberta<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Why do Experts Disagree on Existential Risk and P(doom)? A Survey of AI Experts</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.14870"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cambridge ERA:AI Fellowship, Cambridge, UK.<br>
      • Paper Number: 18<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Enhancing Language Multi-Agent Learning with Multi-Agent Credit Re-Assignment for Interactive Environment Generalization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.14496"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUNLP-MT/CollabUIAgents"><img src="https://img.shields.io/github/stars/THUNLP-MT/CollabUIAgents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hong Kong University of Science and Technology<br>
      • Agent Name: CollabUIAgents, Base Model: Qwen2 7B, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Beyond Self-Talk: A Communication-Centric Survey of LLM-Based Multi-Agent Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.14321"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beihang University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Qwen2.5-VL Technical Report</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.13923"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/QwenLM/Qwen2.5-VL"><img src="https://img.shields.io/github/stars/QwenLM/Qwen2.5-VL.svg?style=social&label=Star"></a><br>
      <a href="https://chat.qwenlm.ai"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Alibaba Group<br>
      • Agent Name: Qwen2.5-VL, Base Model: Qwen2.5 LLM, Strategy: SFT, DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Magma: A Foundation Model for Multimodal AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.13130"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://microsoft.github.io/Magma"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research<br>
      • Agent Name: Magma, Base Model: LLaMA-3-8B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Towards a Design Guideline for RPA Evaluation: A Survey of Large Language Model-Based Role-Playing Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.13012"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/CRChenND/LLM_roleplay_agent_eval_survey"><img src="https://img.shields.io/github/stars/CRChenND/LLM_roleplay_agent_eval_survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Notre Dame<br>
      • Paper Number: 1676<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey on DRL based UAV Communications and Networking: DRL Fundamentals, Applications and Implementations</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.12875"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Anhui University of Technology<br>
      • Paper Number: 124<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>UXAgent: An LLM Agent-Based Usability Testing Framework for Web Design</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.12561"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/neuhai/UXAgent"><img src="https://img.shields.io/github/stars/neuhai/UXAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northeastern University<br>
      • Agent Name: UXAgent, Base Model: LLM, Strategy: Simulated Interaction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey of Automatic Prompt Engineering: An Optimization Perspective</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11560"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tongji University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey of Personalized Large Language Models: Progress and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11528"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Chinese University of Hong Kong<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11448"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://eddyluo1232.github.io/AGrail/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: AGrail, Base Model: Claude-3.5-Sonnet, Strategy: Test-time adaptation<br>
      • Benchmark Name: Safe-OS, Task Number: 3, Dataset Source: carefully designed<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Explorer: Scaling Exploration-driven Web Trajectory Synthesis for Multimodal Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11357"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: Explorer, Base Model: GPT-4, Strategy: Exploration-driven synthesis<br>
      • Benchmark Name: Explorer, Task Number: 94K, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>PlanGenLLMs: A Modern Survey of LLM Planning Capabilities</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11221"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Merced<br>
      • Paper Number: 200<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey of LLM-based Agents in Medicine: How far are we from Baymax?</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.11211"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Chinese University of Hong Kong<br>
      • Paper Number: 60<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Reinforcement Learning in Strategy-Based and Atari Games: A Review of Google DeepMinds Innovations</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.10303"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Egypt Japan University of Science and Technology<br>
      • Paper Number: 25<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey on LLM-powered Agents for Recommender Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.10050"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tianjin University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Human-Centric Foundation Models: Perception, Generation and Agentic Modeling</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.08556"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Chinese University of Hong Kong<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>TRISHUL: Towards Region Identification and Screen Hierarchy Understanding for Large VLM based GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.08226"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fractal AI Research, India<br>
      • Agent Name: TRISHUL, Base Model: GPT-4V, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>WorldGUI: Dynamic Testing for Comprehensive Desktop GUI Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.08047"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: GUI-Thinker, Base Model: GPT-4o, Strategy: critical thinking philosophy<br>
      • Benchmark Name: WorldGUI, Task Number: 315, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>A Survey of In-Context Reinforcement Learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.07978"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Virginia<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>VSC-RL: Advancing Autonomous Vision-Language Agents with Variational Subgoal-Conditioned Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.07949"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ai-agents-2030.github.io/VSC-RL"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Liverpool<br>
      • Agent Name: VSC-RL, Base Model: Gemini-1.5-Pro, Strategy: Variational Subgoal-Conditioned Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Symbiotic Cooperation for Web Agents: Harnessing Complementary Strengths of Large and Small LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.07942"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of North Carolina at Chapel Hill<br>
      • Agent Name: AgentSymbiotic, Base Model: Claude-3.5, Strategy: Speculative Data Synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Fairness in Multi-Agent AI: A Unified Framework for Ethical and Equitable Autonomous Systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.07254"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Task Offloading in Vehicular Edge Computing using Deep Reinforcement Learning: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.06963"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Windsor<br>
      • Paper Number: 136<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Towards Internet-Scale Training For Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.06776"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://data-for-agents.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: InSTA, Task Number: 150000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>AppVLM: A Lightweight Vision Language Model for Online App Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.06395"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Agent Name: AppVLM, Base Model: Paligemma-3B-896, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>MetaChain: A Fully-Automated and Zero-Code Framework for LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.05957"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HKUDS/MetaChain"><img src="https://img.shields.io/github/stars/HKUDS/MetaChain.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Agent Name: MetaChain, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Amorphous Fortress Online: Collaboratively Designing Open-Ended Multi-Agent AI and Game Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.05632"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="http://amorphous-fortress.xyz/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Game Innovation Lab, New York University<br>
      • Benchmark Name: Amorphous Fortress Online, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Safety at Scale: A Comprehensive Survey of Large Model Safety</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.05206"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Paper Number: 390<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Every Software as an Agent: Blueprint and Case Study</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.04747"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beiing University of Posts and Telecommunications<br>
      • Agent Name: JiT-Codegen, Base Model: Claude-3.5, Strategy: Code Generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.04103"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/VTutorTools"><img src="https://img.shields.io/github/stars/github.com/VTutorTools.svg?style=social&label=Star"></a><br>
      <a href="https://vtutor.tools"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: VTutor, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Large Language Models for Multi-Robot Systems: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.03814"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Drexel University<br>
      • Paper Number: 98<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>FedMobileAgent: Training Mobile Agents Using Decentralized Self-Sourced Data from Diverse Users</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.02982"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/FedMobileAgent-2816"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: FedMobileAgent, Base Model: Qwen2-VL-7B, Strategy: Federated Learning<br>
      • Benchmark Name: FedMobileAgent Benchmark, Task Number: Not specified, Dataset Source: self-sourced data from diverse users<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>ReachAgent: Enhancing Mobile Agent via Page Reaching and Operation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.02955"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: XiaoMi AI Lab<br>
      • Agent Name: ReachAgent, Base Model: MobileVLM, Strategy: SFT, DPO<br>
      • Benchmark Name: MobileReach, Task Number: 3, Dataset Source: Mobile3M<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Doing More with Less -- Implementing Routing Strategies in Large Language Model-Based Systems: An Extended Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.00409"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Wikit, Lyon, France<br>
      • Paper Number: 127<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2025</td>
    <td style="width: 40%;"><strong>Embodied Intelligence for 3D Understanding: A Survey on 3D Scene Question Answering</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2502.00342"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hunan University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Context is Key for Agent Security</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.17070"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google, Inc.<br>
      • Agent Name: Conseca, Base Model: Gemini 1.5 Pro, Strategy: Deterministic Policy Enforcement<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.16609"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://oaishi.github.io/cowpilot.html"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Carnegie Mellon University<br>
      • Agent Name: COWPILOT, Base Model: LLM, Strategy: Human-Agent Collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>AI Agents for Computer Use: A Review of Instruction-based Computer Control, GUI Automation, and Operator Assistants</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.16150"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zurich University of Applied Sciences<br>
      • Paper Number: 86<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Audio-Language Models for Audio-Centric Tasks: A survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.15177"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Defense Technology<br>
      • Paper Number: 169<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>GUI-Bee: Align GUI Action Grounding to Novel Environments via Autonomous Exploration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.13896"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gui-bee.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Santa Cruz<br>
      • Agent Name: GUI-Bee, Base Model: GPT-4o, Strategy: Q-value-Incentive In-Context Reinforcement Learning (Q-ICRL)<br>
      • Benchmark Name: NovelScreenSpot, Task Number: 5, Dataset Source: human-collected queries<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Mutation-Guided LLM-based Test Generation at Meta</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.12862"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meta Platforms<br>
      • Agent Name: ACH, Base Model: Llama 3.1 70Bn, Strategy: Mutation-Guided Test Generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>R2D2: Remembering, Reflecting and Dynamic Decision Making for Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.12485"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Southern California<br>
      • Agent Name: R2D2, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>UI-TARS: Pioneering Automated GUI Interaction with Native Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.12326"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bytedance/UI-TARS"><img src="https://img.shields.io/github/stars/bytedance/UI-TARS.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ByteDance Seed<br>
      • Agent Name: UI-TARS, Base Model: Qwen-2-VL, Strategy: SFT, DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.11733"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://x-plug.github.io/MobileAgent"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: Mobile-Agent-E, Base Model: GPT-4o, Strategy: Hierarchical multi-agent framework<br>
      • Benchmark Name: Mobile-Eval-E, Task Number: 25, Dataset Source: manually crafted<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Towards Advancing Code Generation with Large Language Models: A Research Roadmap</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.11354"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Sydney<br>
      • Paper Number: 46<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>A Survey of World Models for Autonomous Driving</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.11260"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Technology Sydney<br>
      • Paper Number: 166<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Learn-by-interact: A Data-Centric Framework for Self-Adaptive Agents in Realistic Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.10893"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google<br>
      • Agent Name: Learn-by-interact, Base Model: Claude-3.5, Strategy: Backward Construction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>A Survey on LLM Test-Time Compute via Search: Tasks, LLM Profiling, Search Algorithms, and Relevant Frameworks</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.10069"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xinzhel/LLM-Agent-Survey/blob/main/search.md"><img src="https://img.shields.io/github/stars/main/search.md.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: nan<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>A Survey on Multi-Turn Interaction Capabilities of Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.09959"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Paper Number: 150<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.09136"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/asinghcsu/AgenticRAG-Survey"><img src="https://img.shields.io/github/stars/asinghcsu/AgenticRAG-Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cleveland State University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>WebWalker: Benchmarking LLMs in Web Traversal</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.07572"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Alibaba Group<br>
      • Agent Name: WebWalker, Base Model: various mainstream LLMs, Strategy: multi-agent framework<br>
      • Benchmark Name: WebWalkerQA, Task Number: 680, Dataset Source: LLM-based and human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Lifelong Learning of Large Language Model based Agents: A Roadmap</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.07278"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/qianlima-lab/awesome-lifelong-llm-agent"><img src="https://img.shields.io/github/stars/qianlima-lab/awesome-lifelong-llm-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: South China University of Technology<br>
      • Paper Number: 360<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Multi-Agent Collaboration Mechanisms: A Survey of LLMs</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.06322"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University College Cork<br>
      • Paper Number: 166<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Semantic Mapping in Indoor Embodied AI -- A Comprehensive Survey and Future Directions</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.05750"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Simon Fraser University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>How to Enable Effective Cooperation Between Humans and NLP Models: A Survey of Principles, Formalizations, and Beyond</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.05714"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Sichuan University<br>
      • Paper Number: 147<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>NSChat: A Chatbot System To Rule Them All</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.05541"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Strathclyde<br>
      • Agent Name: NSChat, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.04575"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Reallm-Labs/InfiGUIAgent"><img src="https://img.shields.io/github/stars/Reallm-Labs/InfiGUIAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: InfiGUIAgent, Base Model: Qwen2-VL-2B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Large language models for artificial general intelligence (AGI): A survey of foundational principles and approaches</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.03151"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cape Coast Technical University<br>
      • Paper Number: 570<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>Benchmark Evaluations, Applications, and Challenges of Large Vision Language Models: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.02189"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zli12321/Awesome-VLM-Papers-And-Models.git"><img src="https://img.shields.io/github/stars/zli12321/Awesome-VLM-Papers-And-Models.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland<br>
      • Paper Number: 308<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2025</td>
    <td style="width: 40%;"><strong>A3: Android Agent Arena for Mobile GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2501.01149"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://yuxiangchai.github.io/Android-Agent-Arena/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MMLab @ CUHK<br>
      • Benchmark Name: Android Agent Arena (A3), Task Number: 201, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey/blob/main/paper.pdf"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey"><img src="https://img.shields.io/github/stars/OS-Agent-Survey/OS-Agent-Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Paper Number: 255<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>OneKE: A Dockerized Schema-Guided LLM Agent-based Knowledge Extraction System</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.20005"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zjunlp/OneKE"><img src="https://img.shields.io/github/stars/zjunlp/OneKE.svg?style=social&label=Star"></a><br>
      <a href="http://oneke.openkg.cn/demo.mp4"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: OneKE, Base Model: LLaMA, Strategy: Schema-guided<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.19723"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai AI Laboratory<br>
      • Agent Name: OS-Genesis, Base Model: GPT-4o, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>GUI Testing Arena: A Unified Benchmark for Advancing Autonomous GUI Testing Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.18426"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ZJU-ACES-ISE/ChatUITest"><img src="https://img.shields.io/github/stars/ZJU-ACES-ISE/ChatUITest.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Benchmark Name: GTArena, Task Number: 3, Dataset Source: real mobile applications, mobile applications with artificially injected defects, and synthetic data<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>AutoDroid-V2: Boosting SLM-based GUI Agents via Code Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.18116"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute for AI Industry Research (AIR), Tsinghua University<br>
      • Agent Name: AutoDroid-V2, Base Model: Llama-3.1-8B, Strategy: Script-based<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Large Language Model Safety: A Holistic Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.17686"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tjunlp-lab/Awesome-LLM-Safety-Papers"><img src="https://img.shields.io/github/stars/tjunlp-lab/Awesome-LLM-Safety-Papers.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: TJUNLP Lab, Tianjin University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>PC Agent: While You Sleep, AI Works -- A Cognitive Journey into Digital World</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.17589"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gair-nlp.github.io/PC-Agent/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: PC Agent, Base Model: Qwen2-VL-72B-Instruct, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A Survey on Multi-Generative Agent System: Recent Advances and New Frontiers</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.17481"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bianhua-12/Multi-generative_Agent_System_survey"><img src="https://img.shields.io/github/stars/bianhua-12/Multi-generative_Agent_System_survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harbin Institute of Technology, China<br>
      • Paper Number: 125<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Aria-UI: Visual Grounding for GUI Instructions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.16256"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ariaui.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Hong Kong<br>
      • Agent Name: Aria-UI, Base Model: Aria, Strategy: Pure-vision approach<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>WebLLM: A High-Performance In-Browser LLM Inference Engine</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.15803"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/mlc-ai/web-llm"><img src="https://img.shields.io/github/stars/mlc-ai/web-llm.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: WebLLM, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A Survey on Large Language Model-based Agents for Statistics and Data Science</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.14222"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong Polytechnic University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.14161"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/TheAgentCompany/TheAgentCompany"><img src="https://img.shields.io/github/stars/TheAgentCompany/TheAgentCompany.svg?style=social&label=Star"></a><br>
      <a href="https://the-agent-company.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: TheAgentCompany, Task Number: 175, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A2H: A UI Converter from Android to HarmonyOS Platform</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.13693"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="http://124.70.54.129:37860/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanjing University of Aeronautics and Astronautics<br>
      • Agent Name: A2H Converter, Base Model: DeepSeek (V2.5), Strategy: multi-agent reflective collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>GUI Agents: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.13501"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Maryland<br>
      • Paper Number: 150<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Deploying Foundation Model Powered Agent Services: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.13437"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Hong Kong Polytechnic University<br>
      • Paper Number: 331<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Proposer-Agent-Evaluator(PAE): Autonomous Skill Discovery For Foundation Model Internet Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.13194"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://yanqval.github.io/PAE/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Berkeley<br>
      • Agent Name: Proposer-Agent-Evaluator (PAE), Base Model: LLaVa-1.6, Strategy: RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Virtual Agent-Based Communication Skills Training to Facilitate Health Persuasion Among Peers</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.12061"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northeastern University, USA<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>WEPO: Web Element Preference Optimization for LLM-based Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10742"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory of Networking and Switching Technology, Beijing University of Posts and Telecommunications, Beijing 100876, China<br>
      • Agent Name: WEPO, Base Model: LLM, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A systematic review of norm emergence in multi-agent systems</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10609"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Valencian Research Institute for Artificial Intelligence (VRAIN). Universitat Politècnica de València, Valencia, Spain<br>
      • Paper Number: 216<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Motion Generation Review: Exploring Deep Learning for Lifelike Animation with Manifold</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10458"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Institute of Technology<br>
      • Paper Number: 77<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Iris: Breaking GUI Complexity with Adaptive Focus and Self-Refining</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10342"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: Iris, Base Model: Qwen-VL, Strategy: Self-Refining Dual Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>You Name It, I Run It: An LLM Agent to Execute Tests of Arbitrary Projects</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10133"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Stuttgart, Germany<br>
      • Agent Name: ExecutionAgent, Base Model: GPT-4o-mini, Strategy: Meta-prompting<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Large Action Models: From Inception to Implementation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.10047"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/UFO/tree/main/dataflow"><img src="https://img.shields.io/github/stars/main/dataflow.svg?style=social&label=Star"></a><br>
      <a href="https://microsoft.github.io/UFO/dataflow/overview/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: UFO, Base Model: Mistral-7B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>ProxyLLM : LLM-Driven Framework for Customer Support Through Text-Style Transfer</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.09916"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sayjoupstack/Proxy-LLM"><img src="https://img.shields.io/github/stars/sayjoupstack/Proxy-LLM.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Colorado Boulder<br>
      • Agent Name: ProxyLLM, Base Model: Llama 3.1 8B, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.09605"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://agenttrek.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Hong Kong<br>
      • Agent Name: AgentTrek, Base Model: GPT-4, Strategy: Guided Replay<br>
      • Benchmark Name: AgentTrek Dataset, Task Number: 10398, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Falcon-UI: Understanding GUI Before Following User Instructions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.09362"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute of Information Engineering, Chinese Academy of Sciences<br>
      • Agent Name: Falcon-UI, Base Model: Qwen2-VL-7B, Strategy: Pretraining and fine-tuning<br>
      • Benchmark Name: Insight-UI Dataset, Task Number: 434K, Dataset Source: Common Crawl corpus<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A Systematic Review of Knowledge Tracing and Large Language Models in Education: Opportunities, Issues, and Future Research</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.09248"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Kalamazoo College<br>
      • Paper Number: 68<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Automated Soap Opera Testing Directed by LLMs and Scenario Knowledge: Feasibility, Challenges, and Road Ahead</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.08581"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Australian National University<br>
      • Agent Name: multi-agent system, Base Model: multi-modal LLMs, Strategy: not explicitly mentioned<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>PAFFA: Premeditated Actions For Fast Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.07958"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Massachusetts Amherst<br>
      • Agent Name: PAFFA, Base Model: Sonnet 3.5-v2, Strategy: Pre-computed Action APIs<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>In-Application Defense Against Evasive Web Scans through Behavioral Analysis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.07005"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/multimodalforensics/webguard"><img src="https://img.shields.io/github/stars/multimodalforensics/webguard.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Florida International University<br>
      • Agent Name: WebGuard, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>The BrowserGym Ecosystem for Web Agent Research</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.05467"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ServiceNow/BrowserGym"><img src="https://img.shields.io/github/stars/ServiceNow/BrowserGym.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ServiceNow Research<br>
      • Benchmark Name: BrowserGym, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>MageBench: Bridging Large Multimodal Models to Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.04531"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/MageBench"><img src="https://img.shields.io/github/stars/microsoft/MageBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Southeast University<br>
      • Benchmark Name: MageBench, Task Number: 483, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.04454"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://aguvis-project.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Hong Kong<br>
      • Agent Name: AGUVIS, Base Model: Qwen2-VL, Strategy: Two-stage training<br>
      • Benchmark Name: THE AGUVIS COLLECTION, Task Number: 35K, Dataset Source: VLM-augmented<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>A Survey on Large Language Model-Based Social Agents in Game-Theoretic Scenarios</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.03920"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Hacking CTFs with Plain Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.02776"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/palisaderesearch/intercode"><img src="https://img.shields.io/github/stars/palisaderesearch/intercode.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Palisade Research<br>
      • Agent Name: ReAct&Plan, Base Model: GPT-4o, Strategy: ReAct&Plan prompting strategy<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Large Multimodal Agents for Accurate Phishing Detection with Enhanced Token Optimization and Cost Reduction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.02301"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: American University of Beirut<br>
      • Agent Name: Agentic Approach, Base Model: Gemini 1.5 Flash and GPT-4o mini, Strategy: Two-tiered agentic approach<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>BOTracle: A framework for Discriminating Bots and Humans</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.02266"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Adobe Inc.<br>
      • Agent Name: BOTracle, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.01778"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aielte-research/HackSynth"><img src="https://img.shields.io/github/stars/aielte-research/HackSynth.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Eötvös Loránd University<br>
      • Agent Name: HackSynth, Base Model: GPT-4o, Strategy: Prompt<br>
      • Benchmark Name: PicoCTF Benchmark, Task Number: 120, Dataset Source: CTF challenges<br>
      • Benchmark Name: OverTheWire Benchmark, Task Number: 80, Dataset Source: CTF challenges<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>Ponder & Press: Advancing Visual GUI Agent towards General Computer Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.01268"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shenzhen International Graduate School, Tsinghua University<br>
      • Agent Name: Ponder & Press, Base Model: Qwen2-VL, Strategy: Divide-and-conquer<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2024</td>
    <td style="width: 40%;"><strong>DroidCall: A Dataset for LLM-powered Android Intent Invocation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2412.00402"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/UbiquitousLearning/DroidCall"><img src="https://img.shields.io/github/stars/UbiquitousLearning/DroidCall.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications (BUPT), China<br>
      • Benchmark Name: DroidCall, Task Number: 10000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Large Language Model-Brained GUI Agents: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.18279"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/vyokky/LLM-Brained-GUI-Agents-Survey"><img src="https://img.shields.io/github/stars/vyokky/LLM-Brained-GUI-Agents-Survey.svg?style=social&label=Star"></a><br>
      <a href="https://aka.ms/gui-agent"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Paper Number: 374<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>ShowUI: One Vision-Language-Action Model for GUI Visual Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.17465"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/ShowUI"><img src="https://img.shields.io/github/stars/showlab/ShowUI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Show Lab, National University of Singapore<br>
      • Agent Name: ShowUI, Base Model: Qwen2-VL-2B, Strategy: UI-Guided Visual Token Selection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Generative Context Distillation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.15927"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST AI<br>
      • Agent Name: Generative Context Distillation, Base Model: LLaMA-3-8B-Instruct, Strategy: Prompt Generation Loss<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>ScribeAgent: Towards Specialized Web Agents Using Production-Scale Workflow Data</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.15004"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/colonylabs/ScribeAgent"><img src="https://img.shields.io/github/stars/colonylabs/ScribeAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Machine Learning Department, CMU<br>
      • Agent Name: ScribeAgent, Base Model: Qwen2, Strategy: Fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>AdaptAgent: Adapting Multimodal Web Agents with Few-Shot Learning from Human Demonstrations</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.13451"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Institute of Technology<br>
      • Agent Name: AdaptAgent, Base Model: GPT-4o, Strategy: In-context Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>A Survey On Enhancing Reinforcement Learning in Complex Environments: Insights from Human and LLM Feedback</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.13410"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Tehran<br>
      • Paper Number: 83<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Generalist Virtual Agents: A Survey on Autonomous Agents Across Digital Platforms</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.10943"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Paper Number: 139<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>The Dawn of GUI Agent: A Preliminary Case Study with Claude 3.5 Computer Use</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.10323"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/computer_use_ootb"><img src="https://img.shields.io/github/stars/showlab/computer_use_ootb.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: Claude 3.5 Computer Use, Base Model: Claude-3.5, Strategy: API-based GUI automation<br>
      • Benchmark Name: Computer Use Out-of-the-Box, Task Number: 20, Dataset Source: human evaluation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>World Models: The Safety Perspective</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.07690"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Technologies Duesseldorf GmbH, RAMS Lab, Munich, Germany<br>
      • Paper Number: 79<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.06559"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/WebDreamer"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/WebDreamer.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: WEB-DREAMER, Base Model: LLMs, Strategy: Model-based planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Do you want to play a game? Learning to play Tic-Tac-Toe in Hypermedia Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.06398"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gitlab.com/mams-ucd/examples/HyperTicTacToe"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University College Dublin<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Alopex: A Computational Framework for Enabling On-Device Function Calls with LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.05209"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: TensorOpera Inc.<br>
      • Agent Name: Alopex, Base Model: Fox LLM, Strategy: fine-tuning with description-question-output format<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>GUI Agents with Foundation Models: A Comprehensive Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.04890"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>GUI Agents with Foundation Models: A Comprehensive Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.04890"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>CUIfy the XR: An Open-Source Package to Embed LLM-powered Conversational Agents in XR</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.04671"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gitlab.lrz.de/hctl/cuify"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Technical University of Munich (TUM), Munich, Germany<br>
      • Agent Name: CUIfy, Base Model: Various LLMs, Strategy: Integration of STT, LLM, and TTS models<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Magentic-One: A Generalist Multi-Agent System for Solving Complex Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.04468"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/autogen"><img src="https://img.shields.io/github/stars/microsoft/autogen.svg?style=social&label=Star"></a><br>
      <a href="https://aka.ms/magentic-one"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research AI Frontiers<br>
      • Agent Name: Magentic-One, Base Model: GPT-4o, Strategy: Multi-agent system<br>
      • Benchmark Name: AutoGenBench, Task Number: 3, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.02337"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/WebRL"><img src="https://img.shields.io/github/stars/THUDM/WebRL.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: WEBRL, Base Model: Llama-3.1, Strategy: Reinforcement Learning<br>
      • Benchmark Name: WebArena-Lite, Task Number: 165, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>Foundations and Recent Trends in Multimodal Mobile Agents: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.02006"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aialt/awesome-mobile-agents"><img src="https://img.shields.io/github/stars/aialt/awesome-mobile-agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Australian Artificial Intelligence Institute, Sydney, Australia<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.01236"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Dizzy-K/AutoPT"><img src="https://img.shields.io/github/stars/Dizzy-K/AutoPT.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Agent Name: AutoPT, Base Model: GPT-4o, Strategy: Finite State Machine (FSM)<br>
      • Benchmark Name: end-to-end penetration testing benchmark, Task Number: 20, Dataset Source: Vulhub<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>ReSpAct: Harmonizing Reasoning, Speaking, and Acting Towards Building Large Language Model-Based Conversational AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.00927"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: ReSpAct, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>AutoGLM: Autonomous Foundation Agents for GUIs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.00820"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/AutoGLM"><img src="https://img.shields.io/github/stars/THUDM/AutoGLM.svg?style=social&label=Star"></a><br>
      <a href="https://xiao9905.github.io/AutoGLM"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhipu AI<br>
      • Agent Name: AUTOGLM, Base Model: ChatGLM, Strategy: Self-evolving Online Curriculum RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2024</td>
    <td style="width: 40%;"><strong>AutoGLM: Autonomous Foundation Agents for GUIs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2411.00820"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/AutoGLM"><img src="https://img.shields.io/github/stars/THUDM/AutoGLM.svg?style=social&label=Star"></a><br>
      <a href="https://xiao9905.github.io/AutoGLM"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhipu AI<br>
      • Agent Name: AUTOGLM, Base Model: ChatGLM, Strategy: Self-Evolving Online Curriculum RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.24024"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/Android-Lab"><img src="https://img.shields.io/github/stars/THUDM/Android-Lab.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: ANDROID LAB, Task Number: 138, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>From Context to Action: Analysis of the Impact of State Representation and Context on the Generalization of Multi-Turn Web Navigation Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.23555"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, University of Illinois-Urbana Champaign<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Evaluating Cultural and Social Awareness of LLM Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.23252"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Los Angeles<br>
      • Benchmark Name: CASA, Task Number: 2, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>OS-ATLAS: A Foundation Action Model for Generalist GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.23218"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://osatlas.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai AI Laboratory<br>
      • Agent Name: OS-Atlas, Base Model: InternVL-2-4B, Strategy: SFT<br>
      • Agent Name: OS-Atlas, Base Model: Qwen2-VL-7B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Explainable Behavior Cloning: Teaching Large Language Model Agents through Learning by Demonstration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.22916"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ant Group<br>
      • Agent Name: EBC-LLMAgent, Base Model: LLM, Strategy: Behavior Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Auto-Intent: Automated Intent Discovery and Self-Exploration for Large Language Model Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.22552"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: LG AI Research<br>
      • Agent Name: Auto-Intent, Base Model: GPT-3.5, Strategy: Self-Exploration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Vision Search Assistant: Empower Vision-Language Models as Multimodal Search Engines</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.21220"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/cnzzx/VSA"><img src="https://img.shields.io/github/stars/cnzzx/VSA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MMLab, CUHK<br>
      • Agent Name: Vision Search Assistant, Base Model: LLaVA-1.6-7B, Strategy: Retrieval-Augmented Generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Vision Search Assistant: Empower Vision-Language Models as Multimodal Search Engines</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.21220"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/cnzzx/VSA"><img src="https://img.shields.io/github/stars/cnzzx/VSA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MMLab, CUHK<br>
      • Agent Name: Vision Search Assistant, Base Model: LLaVA-1.6-7B, Strategy: Retrieval-Augmented Generation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.19609"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MinorJerry/OpenWebVoyager"><img src="https://img.shields.io/github/stars/MinorJerry/OpenWebVoyager.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: OpenWebVoyager, Base Model: Idefics2-8b-instruct, Strategy: Imitation Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.19461"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/EDGE-1CDB"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Agent Name: EDGE, Base Model: Monkey, Strategy: Data Synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.19100"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ljang0/videowebarena"><img src="https://img.shields.io/github/stars/ljang0/videowebarena.svg?style=social&label=Star"></a><br>
      <a href="https://videowebarena.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: VideoWebArena, Task Number: 2021, Dataset Source: manually crafted video tutorials<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.19100"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ljang0/videowebarena"><img src="https://img.shields.io/github/stars/ljang0/videowebarena.svg?style=social&label=Star"></a><br>
      <a href="https://videowebarena.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: VideoWebArena, Task Number: 2021, Dataset Source: manually crafted video tutorials<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Infogent: An Agent-Based Framework for Web Information Aggregation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.19054"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/gangiswag/infogent"><img src="https://img.shields.io/github/stars/gangiswag/infogent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois at Urbana-Champaign<br>
      • Agent Name: INFOGENT, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.18963"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Universit é de Montr éal<br>
      • Agent Name: OSCAR, Base Model: GPT-4, Strategy: Task-driven Re-planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.18603"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://chengyou-jia.github.io/AgentStore-Home"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Xi’an Jiaotong University<br>
      • Agent Name: MetaAgent, Base Model: InternVL2-8B, Strategy: AgentToken<br>
      • Benchmark Name: OSWorld, Task Number: 369, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>PRACT: Optimizing Principled Reasoning and Acting of LLM Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.18528"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Salesforce AI Research, USA<br>
      • Agent Name: PRAct, Base Model: GPT-3.5-Turbo, Strategy: Reflective Principle Optimization (RPO)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Countering Autonomous Cyber Threats</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.18312"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/kmheckel/HeckelMLMIThesis"><img src="https://img.shields.io/github/stars/kmheckel/HeckelMLMIThesis.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Cambridge<br>
      • Agent Name: ReAct agent, Base Model: Llama3-405B, Strategy: ReAct<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Lightweight Neural App Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.17883"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Agent Name: LiMAC, Base Model: Florence2, Strategy: Fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.17520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://mobilesafetybench.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Benchmark Name: MobileSafetyBench, Task Number: 100, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.17520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://mobilesafetybench.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Benchmark Name: MobileSafetyBench, Task Number: 100, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AdvWeb: Controllable Black-box Attacks on VLM-powered Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.17401"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ai-secure.github.io/AdvWeb/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Large Language Models Empowered Personalized Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.17236"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/assistgui"><img src="https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: PUMA, Base Model: LLM, Strategy: SFT, DPO<br>
      • Benchmark Name: PersonalWAB, Task Number: 3, Dataset Source: Amazon review dataset<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>CoPS: Empowering LLM Agents with Provable Cross-Task Experience Sharing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.16670"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/uclaml/COPS"><img src="https://img.shields.io/github/stars/uclaml/COPS.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Indiana University Bloomington, IN 47408, USA<br>
      • Agent Name: CoPS, Base Model: Llama 3.1, Strategy: Pessimism-based strategy<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Beyond Browsing: API-Based Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.16464"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/yueqis/API-Based-Agent"><img src="https://img.shields.io/github/stars/yueqis/API-Based-Agent.svg?style=social&label=Star"></a><br>
      <a href="https://yueqis.github.io/API-Based-Agent/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: API-calling agent, Base Model: GPT-4o, Strategy: API calling<br>
      • Agent Name: Hybrid Agent, Base Model: GPT-4o, Strategy: API calling and web browsing<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Sketch2Code: Evaluating Vision-Language Models for Interactive Web Design Prototyping</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.16232"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://salt-nlp.github.io/Sketch2Code-Project-Page/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Benchmark Name: Sketch2Code, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Contextual Augmented Multi-Model Programming (CAMP): A Hybrid Local-Cloud Copilot Framework</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.15285"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: Copilot for Xcode, Base Model: OpenAI GPT series, Strategy: Retrieval-Augmented Generation (RAG)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AutoFLUKA: A Large Language Model Based Framework for Automating Monte Carlo Simulations in FLUKA</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.15222"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Nuclear Engineering, Texas A&M University, United States<br>
      • Agent Name: AutoFLUKA, Base Model: gpt-4o, Strategy: LangChain<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>SPA-Bench: A Comprehensive Benchmark for SmartPhone Agent Evaluation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.15164"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huawei Noah’s Ark Lab<br>
      • Benchmark Name: SPA-BENCH, Task Number: 340, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>DistRL: An Asynchronous Distributed Reinforcement Learning Framework for On-Device Control Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.14803"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Cambridge<br>
      • Agent Name: DISTRL, Base Model: T5-based multimodal generation architecture, Strategy: Reinforcement Learning<br>
      • Benchmark Name: AitW, Task Number: 128, Dataset Source: expert-curated task sets<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>When LLMs Go Online: The Emerging Threat of Web-Enabled LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.14569"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.13886"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: BrowserART, Task Number: 100, Dataset Source: HarmBench, AirBench 2024, and original behaviors<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.13825"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: AGENT OCCAM, Base Model: GPT-4-turbo, Strategy: Observation and Action Space Alignment<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Harnessing Webpage UIs for Text-Rich Visual Understanding</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.13824"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://neulab.github.io/MultiUI/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: MultiUI, Task Number: 9, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>MobA: A Two-Level Agent System for Efficient Mobile Task Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.13757"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: MobA, Base Model: multimodal large language models, Strategy: two-level agent architecture<br>
      • Benchmark Name: MobBench, Task Number: 50, Dataset Source: real-life tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Web Agents with World Models: Learning and Leveraging Environment Dynamics in Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.13232"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/kyle8581/WMA-Agents"><img src="https://img.shields.io/github/stars/kyle8581/WMA-Agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Yonsei University<br>
      • Agent Name: World-Model-Augmented (WMA) web agent, Base Model: Llama-3.1-8B-Instruct, Strategy: Policy optimization with world model<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>ClickAgent: Enhancing UI Location Capabilities of Autonomous Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.11872"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Samsung/ClickAgent"><img src="https://img.shields.io/github/stars/Samsung/ClickAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Warsaw University of Technology<br>
      • Agent Name: ClickAgent, Base Model: InternVL2.0, Strategy: Hybrid approach with UI location model<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>TinyClick: Single-Turn Agent for Empowering GUI Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.11871"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Samsung R&D Poland<br>
      • Agent Name: TinyClick, Base Model: Florence-2-Base, Strategy: Multitask Training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>From Interaction to Impact: Towards Safer AI Agents Through Understanding and Evaluating UI Operation Impacts</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.09006"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Washington<br>
      • Benchmark Name: Impact Actions Dataset, Task Number: 250, Dataset Source: crowdsourcing<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Agent S: An Open Agentic Framework that Uses Computers Like a Human</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.08164"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/simular-ai/Agent-S"><img src="https://img.shields.io/github/stars/simular-ai/Agent-S.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Simular Research<br>
      • Agent Name: Agent S, Base Model: GPT-4o, Strategy: Experience-Augmented Hierarchical Planning<br>
      • Benchmark Name: OSWorld, Task Number: 369, Dataset Source: not specified<br>
      • Benchmark Name: WindowsAgentArena, Task Number: 154, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>SoundScape: A Human-AI Co-Creation System Making Your Memories Heard</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.08136"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: SoundScape, Base Model: ChatGPT, Strategy: Conversational Agent<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.07331"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://da-code-bench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Key Laboratory of Cognition and Decision Intelligence for Complex Systems, Institute of Automation, Chinese Academy of Sciences<br>
      • Benchmark Name: DA-Code, Task Number: 500, Dataset Source: real, challenging data analysis tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.06703"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://sites.google.com/view/st-webagentbench/home"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IBM Research<br>
      • Benchmark Name: ST-WebAgentBench, Task Number: 234, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AgentSquare: Automatic LLM Agent Search in Modular Design Space</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.06153"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tsinghua-fib-lab/AgentSquare"><img src="https://img.shields.io/github/stars/tsinghua-fib-lab/AgentSquare.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Electronic Engineering, Tsinghua University<br>
      • Agent Name: AgentSquare, Base Model: LLM, Strategy: module evolution and recombination<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Better than Your Teacher: LLM Agents that learn from Privileged AI Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.05434"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://leap-llm.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Cornell University<br>
      • Agent Name: LEAP, Base Model: Llama3-8B, Strategy: SFT<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.05243"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://osu-nlp-group.github.io/UGround/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: UGround, Base Model: LLaV A, Strategy: Slight adaptation<br>
      • Benchmark Name: ScreenSpot, Task Number: 1272, Dataset Source: web-based synthetic data<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>AutoPenBench: Benchmarking Generative Agents for Penetration Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.03225"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lucagioacchini/auto-pen-bench"><img src="https://img.shields.io/github/stars/lucagioacchini/auto-pen-bench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Politecnico di Torino<br>
      • Benchmark Name: AUTOPENBENCH, Task Number: 33, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>NNetscape Navigator: Complex Demonstrations for Web Agents Without a Demonstrator</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.02907"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: NNetscape Navigator, Base Model: GPT-4o-mini, Strategy: Supervised Fine-Tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>ExACT: Teaching AI Agents to Explore with Reflective-MCTS and Exploratory Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.02052"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://aka.ms/ExACT"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Columbia University<br>
      • Agent Name: R-MCTS, Base Model: GPT-4o, Strategy: Reflective Monte Carlo Tree Search<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>CALF: Benchmarking Evaluation of LFQA Using Chinese Examinations</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.01945"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/assistgui"><img src="https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing University of Posts and Telecommunications<br>
      • Benchmark Name: CALF, Task Number: 1476, Dataset Source: Chinese examination questions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Multimodal Auto Validation For Self-Refinement in Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.00689"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://anonymous.4open.science/r/Agent-E-7E43"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois<br>
      • Agent Name: Agent-E, Base Model: GPT-4-Turbo, Strategy: Self-Refinement<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2024</td>
    <td style="width: 40%;"><strong>Dynamic Planning for LLM-based Graphical User Interface Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2410.00467"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/sqzhang-lazy/D-PoT"><img src="https://img.shields.io/github/stars/sqzhang-lazy/D-PoT.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science and Technology, Harbin Institute of Technology, China<br>
      • Agent Name: Dynamic Planning of Thoughts (D-PoT), Base Model: GPT-4V, Strategy: Dynamic Planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Turn Every Application into an Agent: Towards Efficient Human-Agent-Computer Interaction with API-First LLM-Based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.17140"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Peking University<br>
      • Agent Name: AXIS, Base Model: LLM, Strategy: API-first approach<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>EnIGMA: Enhanced Interactive Generative Model Agent for CTF Challenges</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.16165"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/princeton-nlp/SWE-agent"><img src="https://img.shields.io/github/stars/princeton-nlp/SWE-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tel-Aviv University<br>
      • Agent Name: EnIGMA, Base Model: GPT-4 Turbo, Strategy: Prompt<br>
      • Benchmark Name: NYU CTF Benchmark, Task Number: 200, Dataset Source: public and open source CTF challenges<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Synatra: Turning Indirect Knowledge into Direct Demonstrations for Digital Agents at Scale</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.15637"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://oootttyyy.github.io/synatra"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: Synatra-CodeLlama, Base Model: CodeLlama, Strategy: finetuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Towards a Realistic Long-Term Benchmark for Open-Web Research Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.14913"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FutureSearch AI<br>
      • Benchmark Name: Realistic Long-Term Benchmark for Open-Web Research Agents, Task Number: not specified, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>MobileVLM: A Vision-Language Model for Better Intra- and Inter-UI Understanding</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.14818"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/XiaoMi/mobilevlm"><img src="https://img.shields.io/github/stars/XiaoMi/mobilevlm.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: XiaoMi AI Lab<br>
      • Agent Name: MobileVLM, Base Model: Qwen-VL-Chat, Strategy: Pre-training and fine-tuning<br>
      • Benchmark Name: Mobile3M, Task Number: 4, Dataset Source: real-world interactions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Large Model Agents: State-of-the-Art, Cooperation Paradigms, Security and Privacy, and Future Trends</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.14457"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Xi’an Jiaotong University<br>
      • Paper Number: 231<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>WebQuest: A Benchmark for Multimodal QA on Web Page Sequences</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.13711"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind, USA<br>
      • Benchmark Name: WebQuest, Task Number: 3, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>The Impact of Element Ordering on LM Agent Performance</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.12089"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/waynchi/gui-agent"><img src="https://img.shields.io/github/stars/waynchi/gui-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.11295"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/EIA_against_webagent"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/EIA_against_webagent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Cognitive Kernel: An Open-source Agent System towards Generalist Autopilots</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.10277"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tencent-ailab/CogKernel"><img src="https://img.shields.io/github/stars/tencent-ailab/CogKernel.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab, Seattle<br>
      • Agent Name: Cognitive Kernel, Base Model: LLama3, Strategy: fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Cognitive Kernel: An Open-source Agent System towards Generalist Autopilots</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.10277"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tencent-ailab/CogKernel"><img src="https://img.shields.io/github/stars/tencent-ailab/CogKernel.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab, Seattle<br>
      • Agent Name: Cognitive Kernel, Base Model: LLama3, Strategy: fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>PeriGuru: A Peripheral Robotic Mobile App Operation Assistant based on GUI Image Understanding and Prompting with LLM</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.09354"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Z2sJ4t/PeriGuru"><img src="https://img.shields.io/github/stars/Z2sJ4t/PeriGuru.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Peking University, China<br>
      • Agent Name: PeriGuru, Base Model: LLM, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Enhancing Decision-Making for LLM Agents via Step-Level Q-Value Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.09345"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Defense Technology<br>
      • Agent Name: LLM Agent with Q-value Model, Base Model: Phi-3-mini-4k-instruct, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>ELMS: Elasticized Large Language Models On Mobile Devices</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.09071"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Key Lab of High Confidence Software Technologies (Peking University), Beijing, China<br>
      • Agent Name: ELMS, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.08264"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/WindowsAgentArena"><img src="https://img.shields.io/github/stars/microsoft/WindowsAgentArena.svg?style=social&label=Star"></a><br>
      <a href="https://microsoft.github.io/WindowsAgentArena"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: Navi, Base Model: GPT-4V-1106, Strategy: Set-of-Marks prompting<br>
      • Benchmark Name: WINDOWS AGENT ARENA, Task Number: 154, Dataset Source: automatic execution-based evaluation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Agent Workflow Memory</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.07429"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zorazrw/agent-workflow-memory"><img src="https://img.shields.io/github/stars/zorazrw/agent-workflow-memory.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: Agent Workflow Memory (AWM), Base Model: GPT-4, Strategy: Workflow Induction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Here's Charlie! Realising the Semantic Web vision of Agents in the age of LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.04465"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/jeswr/phd-language-dialogue-experiment"><img src="https://img.shields.io/github/stars/jeswr/phd-language-dialogue-experiment.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Oxford<br>
      • Agent Name: Charlie, Base Model: LLM, Strategy: Dialogue<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>MATWA: A Web Toolkit for Matching under Preferences</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.04402"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://matwa.optimalmatching.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Glasgow<br>
      • Benchmark Name: MATWA, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>BreachSeek: A Multi-Agent Automated Penetration Tester</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.03789"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/snow10100/pena/"><img src="https://img.shields.io/github/stars/pena/.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: King Fahd University of Petroleum and Minerals (KFUPM)<br>
      • Agent Name: BreachSeek, Base Model: Claude 3.5 Sonnet, Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>From Grounding to Planning: Benchmarking Bottlenecks in Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.01927"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IBM Research - Israel<br>
      • Agent Name: WebNaviX, Base Model: GPT-4o, Strategy: Prompt<br>
      • Benchmark Name: Mind2Web, Task Number: 777, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>TinyAgent: Function Calling at the Edge</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.00608"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/SqueezeAILab/TinyAgent"><img src="https://img.shields.io/github/stars/SqueezeAILab/TinyAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: TinyAgent, Base Model: TinyLlama-1.1B, Strategy: Fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2024</td>
    <td style="width: 40%;"><strong>Web Retrieval Agents for Evidence-Based Misinformation Detection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2409.00009"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ComplexData-MILA/webretrieval"><img src="https://img.shields.io/github/stars/ComplexData-MILA/webretrieval.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: McGill<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>An Extremely Data-efficient and Generative LLM-based Reinforcement Learning Agent for Recommenders</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.16032"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/fengshuang-coding/KDD2024"><img src="https://img.shields.io/github/stars/fengshuang-coding/KDD2024.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University SCPD<br>
      • Agent Name: DPO agent, Base Model: BERT, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>WebPilot: A Versatile and Autonomous Multi-Agent System for Web Task Execution with Strategic Exploration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.15978"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WebPilot"><img src="https://img.shields.io/github/stars/github.com/WebPilot.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: LMU Munich<br>
      • Agent Name: WebPilot, Base Model: GPT-4, Strategy: Monte Carlo Tree Search (MCTS)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>AppAgent v2: Advanced Agent for Flexible Mobile Interactions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.11824"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Technology Sydney<br>
      • Agent Name: AppAgent v2, Base Model: GPT-4, Strategy: RAG technology<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.10738"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Agent Name: PhishAgent, Base Model: MLLMs, Strategy: Multimodal information retrieval framework<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.08926"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://cybench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Benchmark Name: Cybench, Task Number: 40, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>WeKnow-RAG: An Adaptive Approach for Retrieval-Augmented Generation Integrating Web Search and Knowledge Graphs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.07611"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ping An Bank Co., Ltd.<br>
      • Agent Name: WeKnow-RAG, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.07199"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The AGI Company (MultiOn)<br>
      • Agent Name: Agent Q, Base Model: LLaMA-3 70B, Strategy: DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>Retrieval-Augmented Hierarchical in-Context Reinforcement Learning and Hindsight Modular Reflections for Task Planning with LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.06520"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Rutgers University–New Brunswick<br>
      • Agent Name: RAHL, Base Model: GPT-3.5-turbo, Strategy: Hierarchical Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>VisualAgentBench: Towards Large Multimodal Models as Visual Foundation Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.06327"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/VisualAgentBench"><img src="https://img.shields.io/github/stars/THUDM/VisualAgentBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: VisualAgentBench, Task Number: 5, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>Automated Code Fix Suggestions for Accessibility Issues in Mobile Apps</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.03827"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Apple<br>
      • Agent Name: FixAlly, Base Model: GPT-4o, Strategy: multi-agent LLM architecture<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>Reinforcement Learning for an Efficient and Effective Malware Investigation during Cyber Incident Response</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.01999"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: London Metropolitan University<br>
      • Agent Name: Reinforcement Learning Post-Incident Malware Investigation Model, Base Model: , Strategy: Q-learning<br>
      • Benchmark Name: Unified Markov Decision Process (MDP) Model, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2024</td>
    <td style="width: 40%;"><strong>OmniParser for Pure Vision Based GUI Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2408.00203"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research<br>
      • Agent Name: OMNIPARSER, Base Model: GPT-4V, Strategy: fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>MindSearch: Mimicking Human Minds Elicits Deep AI Searcher</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.20183"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/InternLM/MindSearch"><img src="https://img.shields.io/github/stars/InternLM/MindSearch.svg?style=social&label=Star"></a><br>
      <a href="https://mindsearch.netlify.app"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Agent Name: MindSearch, Base Model: GPT-4o, Strategy: multi-agent framework<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.19354"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Technology Sydney<br>
      • Paper Number: 135<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>AMEX: Android Multi-annotation Expo Dataset for Mobile GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.17490"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://yuxiangchai.github.io/AMEX/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MMLab, CUHK<br>
      • Benchmark Name: AMEX, Task Number: 2946, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>OpenHands: An Open Platform for AI Software Developers as Generalist Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.16741"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/All-Hands-AI/OpenHands"><img src="https://img.shields.io/github/stars/All-Hands-AI/OpenHands.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UIUC<br>
      • Agent Name: OpenHands, Base Model: CodeAct, Strategy: Prompt<br>
      • Benchmark Name: OpenHands Evaluation, Task Number: 15, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>TaskGen: A Task-Based, Memory-Infused Agentic Framework using StrictJSON</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.15734"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/simbianai/taskgen"><img src="https://img.shields.io/github/stars/simbianai/taskgen.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Simbian AI<br>
      • Agent Name: TaskGen, Base Model: LLM, Strategy: StrictJSON<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.15711"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://assistantbench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tel Aviv University<br>
      • Agent Name: SEEPLANACT (SPA), Base Model: GPT-4-Turbo, Strategy: Prompt<br>
      • Benchmark Name: ASSISTANT BENCH, Task Number: 214, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Using LLMs to Automate Threat Intelligence Analysis Workflows in Security Operation Centers</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.13093"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Penn State University<br>
      • Agent Name: AI agent for CTI analysis, Base Model: GPT-4, Strategy: Not explicitly mentioned<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Agent-E: From Autonomous Web Navigation to Foundational Design Principles in Agentic Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.13032"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/EmergenceAI/Agent-E"><img src="https://img.shields.io/github/stars/EmergenceAI/Agent-E.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Emergence AI<br>
      • Agent Name: Agent-E, Base Model: GPT-4-Turbo, Strategy: Hierarchical Architecture<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>InferAct: Inferring Safe Actions for LLM-Based Agents Through Preemptive Evaluation and Human Feedback</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.11843"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ubiquitous Knowledge Processing Lab (UKP Lab), Department of Computer Science and Hessian Center for AI (hessian.AI), Technical University of Darmstadt, Germany<br>
      • Agent Name: InferAct, Base Model: GPT-4, Strategy: Belief Reasoning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.10956"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xlang-ai/Spider2-V"><img src="https://img.shields.io/github/stars/xlang-ai/Spider2-V.svg?style=social&label=Star"></a><br>
      <a href="https://spider2-v.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Benchmark Name: Spider2-V, Task Number: 494, Dataset Source: real-world tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Sibyl: Simple yet Effective Agent Framework for Complex Real-world Reasoning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.10718"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Ag2S1/Sibyl-System"><img src="https://img.shields.io/github/stars/Ag2S1/Sibyl-System.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Baichuan Inc.<br>
      • Agent Name: Sibyl, Base Model: GPT-4, Strategy: multi-agent debate-based jury<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Security Matrix for Multimodal Agents on Mobile Devices: A Systematic and Proof of Concept Study</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.09295"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Cyber Science and Engineering, Xi’an Jiaotong University<br>
      • Benchmark Name: mobile agent security matrix, Task Number: 8, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>AUITestAgent: Automatic Requirements Oriented GUI Function Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.09018"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bz-lab/AUITestAgent"><img src="https://img.shields.io/github/stars/bz-lab/AUITestAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Fudan University<br>
      • Agent Name: AUITestAgent, Base Model: GPT-4o, Strategy: multi-dimensional data extraction<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.05291"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ServiceNow/WorkArena/tree/workarena-plus-plus"><img src="https://img.shields.io/github/stars/tree/workarena-plus-plus.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ServiceNow Research<br>
      • Benchmark Name: WorkArena++, Task Number: 682, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>MobileFlow: A Multimodal LLM For Mobile GUI Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.04346"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ant Group<br>
      • Agent Name: MobileFlow, Base Model: Qwen-VL-Chat, Strategy: Mixture of Experts (MoE)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>MobileExperts: A Dynamic Tool-Enabled Agent Team in Mobile Devices</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.03913"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AI Lab at Lenovo Research<br>
      • Agent Name: MobileExperts, Base Model: LLM/VLM, Strategy: Code Combination Based Tool Formulation<br>
      • Benchmark Name: Expert-Eval, Task Number: 28, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Seeing is Believing: Vision-driven Non-crash Functional Bug Detection for Mobile Apps</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.03037"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/testtest2024-art/Trident"><img src="https://img.shields.io/github/stars/testtest2024-art/Trident.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory of Intelligent Game, Institute of Software Chinese Academy of Sciences, University of Chinese Academy of Sciences, Beijing, China<br>
      • Agent Name: Trident, Base Model: GPT-4 Vision, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>CRAB: Cross-environment Agent Benchmark for Multimodal Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.01511"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAUST<br>
      • Benchmark Name: Crab Benchmark-v0, Task Number: 120, Dataset Source: sub-task composition<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>AI Agents That Matter</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.01502"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University<br>
      • Benchmark Name: WebArena, Task Number: 812, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Tree Search for Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.01476"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://jykoh.com/search-agents"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2024</td>
    <td style="width: 40%;"><strong>Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2407.00993"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/XiaoMi/MobileBench"><img src="https://img.shields.io/github/stars/XiaoMi/MobileBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Electronic Science and Technology of China<br>
      • Benchmark Name: Mobile-Bench, Task Number: 832, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Read Anywhere Pointed: Layout-aware GUI Screen Reading with Tree-of-Lens Grounding</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.19263"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://screen-point-and-read.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Santa Cruz<br>
      • Agent Name: Tree-of-Lens (ToL) agent, Base Model: GPT-4o, Strategy: Multi-lens Prompting<br>
      • Benchmark Name: Screen Point-and-Read (ScreenPR) benchmark, Task Number: 1500, Dataset Source: manually annotated<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>VLM Agents Generate Their Own Memories: Distilling Experience into Embodied Programs of Thought</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.14596"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ical-learning.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: ICAL, Base Model: GPT-4V, Strategy: In-Context Abstraction Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Identifying User Goals from UI Trajectories</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.14314"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Benchmark Name: Goal Identification from UI Trajectories, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>GUI Action Narrator: Where and When Did That Action Take Place?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.13719"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://showlab.github.io/GUI-Narrator"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Show Lab, National University of Singapore<br>
      • Benchmark Name: Act2Cap, Task Number: 4189, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>CoAct: A Global-Local Hierarchy for Autonomous Agent Collaboration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.13381"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xmhou2002/CoAct"><img src="https://img.shields.io/github/stars/xmhou2002/CoAct.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: CoAct, Base Model: gpt-3.5-turbo-16K-0613, Strategy: Hierarchical Planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>WONDERBREAD: A Benchmark for Evaluating Multimodal Foundation Models on Business Process Management Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.13264"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HazyResearch/wonderbread"><img src="https://img.shields.io/github/stars/HazyResearch/wonderbread.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Benchmark Name: WONDERBREAD, Task Number: 6, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Adversarial Attacks on Multimodal Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.12814"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ChenWu98/agent-attack"><img src="https://img.shields.io/github/stars/ChenWu98/agent-attack.svg?style=social&label=Star"></a><br>
      <a href="https://chenwu.io/attack-agent"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: VisualWebArena-Adv, Task Number: 200, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>WebCanvas: Benchmarking Web Agents in Online Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.12373"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://www.imean.ai/web-canvas"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: iMean AI<br>
      • Benchmark Name: WebCanvas, Task Number: 542, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Socially Interactive Agents for Robotic Neurorehabilitation Training: Conceptualization and Proof-of-concept Study</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.12035"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: German Research Center for Artificial Intelligence, Saarbrücken, Germany<br>
      • Agent Name: Lydia, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.11896"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/DigiRL-agent/digirl"><img src="https://img.shields.io/github/stars/DigiRL-agent/digirl.svg?style=social&label=Star"></a><br>
      <a href="https://digirl-agent.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
      • Agent Name: DigiRL, Base Model: VLM, Strategy: Advantage-Weighted Regression<br>
      • Benchmark Name: Android-in-the-Wild (AitW), Task Number: not specified, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>GUICourse: From General Vision Language Models to Versatile GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.11317"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/yiye3/GUICourse"><img src="https://img.shields.io/github/stars/yiye3/GUICourse.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Renmin University of China<br>
      • Agent Name: Qwen-GUI, Base Model: Qwen-VL, Strategy: SFT<br>
      • Agent Name: Fuyu-GUI, Base Model: Fuyu-8B, Strategy: SFT<br>
      • Agent Name: MiniCPM-GUI, Base Model: MiniCPM-V, Strategy: SFT<br>
      • Benchmark Name: GUICourse, Task Number: 3, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.11176"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WeiminXiong/IPR"><img src="https://img.shields.io/github/stars/WeiminXiong/IPR.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory of Multimedia Information Processing School of Computer Science, Peking University<br>
      • Agent Name: IPR, Base Model: Llama-2-7B, Strategy: SFT, DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.10819"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://gui-world.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Huazhong University of Science and Technology<br>
      • Benchmark Name: GUI-WORLD, Task Number: 7, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.09187"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UIUC<br>
      • Agent Name: GuardAgent, Base Model: GPT-4, Strategy: in-context learning<br>
      • Benchmark Name: EICU-AC, Task Number: 316, Dataset Source: EICU dataset<br>
      • Benchmark Name: Mind2Web-SC, Task Number: 200, Dataset Source: Mind2Web dataset<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.08451"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenGVLab/GUI-Odyssey"><img src="https://img.shields.io/github/stars/OpenGVLab/GUI-Odyssey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: OpenGVLab, Shanghai AI Laboratory<br>
      • Agent Name: OdysseyAgent, Base Model: Qwen-VL, Strategy: fine-tuning with a history resampling module<br>
      • Benchmark Name: GUI Odyssey, Task Number: 7735, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.08184"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://MobileAgentBench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: MobileAgentBench, Task Number: 100, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Tell Me What's Next: Textual Foresight for Generic UI Representations</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.07822"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aburns4/textualforesight"><img src="https://img.shields.io/github/stars/aburns4/textualforesight.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Boston University<br>
      • Benchmark Name: OpenApp, Task Number: 4, Dataset Source: newly constructed mobile app dataset<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>CAAP: Context-Aware Action Planning Prompting to Solve Computer Tasks with Front-End UI Only</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.06947"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/caap-agent/caap-agent"><img src="https://img.shields.io/github/stars/caap-agent/caap-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Samsung SDS<br>
      • Agent Name: CAAP, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.05804"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xinzhel/LLM-Agent-Survey"><img src="https://img.shields.io/github/stars/xinzhel/LLM-Agent-Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Independent Researcher<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>AgentGym: Evolving Large Language Model-based Agents across Diverse Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.04151"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WooooDyy/AgentGym"><img src="https://img.shields.io/github/stars/WooooDyy/AgentGym.svg?style=social&label=Star"></a><br>
      <a href="https://agentgym.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan NLP Lab & Fudan Vision and Learning Lab<br>
      • Agent Name: AGENT EVOL, Base Model: Llama-2-Chat-7B, Strategy: Behavioral Cloning<br>
      • Benchmark Name: AGENT EVAL, Task Number: 89, Dataset Source: crowdsourcing and AI-based methods<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Mini Honor of Kings: A Lightweight Environment for Multi-Agent Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.03978"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/tencent-ailab/mini-hok"><img src="https://img.shields.io/github/stars/tencent-ailab/mini-hok.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent Timi Studio<br>
      • Benchmark Name: Mini Honor of Kings, Task Number: 7, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>On the Effects of Data Scale on UI Control Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.03679"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/android_control"><img src="https://img.shields.io/github/stars/master/android_control.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
      • Benchmark Name: ANDROID CONTROL, Task Number: 15283, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.03007"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/DPamK/BadAgent"><img src="https://img.shields.io/github/stars/DPamK/BadAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhengzhou University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>AI Agents Under Threat: A Survey of Key Security Challenges and Future Pathways</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.02630"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Swinburne University of Technology<br>
      • Paper Number: 215<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Teams of LLM Agents can Exploit Zero-Day Vulnerabilities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.01637"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: HPTSA, Base Model: GPT-4, Strategy: Hierarchical Planning and Task-Specific Agents<br>
      • Benchmark Name: Benchmark of Zero-Day Vulnerabilities, Task Number: 15, Dataset Source: open-source software vulnerabilities<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>WebSuite: Systematically Evaluating Why Web Agents Fail</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.01623"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/erichli1/websuite"><img src="https://img.shields.io/github/stars/erichli1/websuite.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Harvard University<br>
      • Benchmark Name: WebSuite, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.01014"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/X-PLUG/MobileAgent"><img src="https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Agent Name: Mobile-Agent-v2, Base Model: GPT-4V, Strategy: Multi-agent collaboration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2024</td>
    <td style="width: 40%;"><strong>Towards Rationality in Language and Multimodal Agents: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2406.00252"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bowen-upenn/Agent_Rationality"><img src="https://img.shields.io/github/stars/bowen-upenn/Agent_Rationality.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Pennsylvania<br>
      • Paper Number: 200<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>DepsRAG: Towards Agentic Reasoning and Planning for Software Dependency Management</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.20455"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Mohannadcse/DepsRAG"><img src="https://img.shields.io/github/stars/Mohannadcse/DepsRAG.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Wisconsin-Madison<br>
      • Agent Name: DEPSRAG, Base Model: GPT-4-Turbo, Strategy: Retrieval-Augmented Generation (RAG)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Large Language Models Can Self-Improve At Web Agent Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.20309"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Pennsylvania<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Reverse Image Retrieval Cues Parametric Memory in Multimodal LLMs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.18740"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/mi92/reverse-image-rag"><img src="https://img.shields.io/github/stars/mi92/reverse-image-rag.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Stanford University<br>
      • Agent Name: RIR-augmented MLLM, Base Model: GPT-4, Strategy: Reverse Image Retrieval<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Devil's Advocate: Anticipatory Reflection for LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.16334"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UPenn<br>
      • Agent Name: DEVIL'S ADVOCATE, Base Model: GPT-4, Strategy: Introspective Reflection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Knowledge-Informed Auto-Penetration Testing Based on Reinforcement Learning with Reward Machine</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.15908"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Concordia University<br>
      • Agent Name: DRLRM-PT, Base Model: , Strategy: Deep Q-learning with Reward Machine<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.15793"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/princeton-nlp/SWE-bench"><img src="https://img.shields.io/github/stars/princeton-nlp/SWE-bench.svg?style=social&label=Star"></a><br>
      <a href="https://swe-agent.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Princeton University<br>
      • Agent Name: SWE-agent, Base Model: GPT-4 Turbo, Strategy: ReAct<br>
      • Benchmark Name: SWE-bench, Task Number: 2294, Dataset Source: GitHub issues<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.14573"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/android_world"><img src="https://img.shields.io/github/stars/google-research/android_world.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
      • Benchmark Name: ANDROID WORLD, Task Number: 116, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Latent State Estimation Helps UI Agents to Reason</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.11120"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Agent Design Pattern Catalogue: A Collection of Architectural Patterns for Foundation Model based Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.10467"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Data61, CSIRO, Australia<br>
      • Paper Number: 79<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>CRATOR: a Dark Web Crawler</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.06356"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tilburg University - JADS<br>
      • Agent Name: CRATOR, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Unveiling Disparities in Web Task Handling Between Human and Web Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.04497"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computing, KAIST<br>
      • Paper Number: 17<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Automating the Enterprise with Foundation Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.03710"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HazyResearch/eclair-agents"><img src="https://img.shields.io/github/stars/HazyResearch/eclair-agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: ECLAIR, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Prioritizing Software Requirements Using Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.01564"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tampere University, Tampere, Finland.<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2024</td>
    <td style="width: 40%;"><strong>Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2405.00516"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Maastricht University<br>
      • Agent Name: WebAI, Base Model: T5, Strategy: Behavioral Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Benchmarking Mobile Device Control Agents across Diverse Configurations</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.16660"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://b-moca.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Benchmark Name: B-MoCA, Task Number: 131, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>LlamaTouch: A Faithful and Scalable Testbed for Mobile UI Task Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.16054"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/LlamaTouch/LlamaTouch"><img src="https://img.shields.io/github/stars/LlamaTouch/LlamaTouch.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: State Key Laboratory of Networking and Switching Technology, Beijing University of Posts and Telecommunications<br>
      • Benchmark Name: LlamaTouch, Task Number: 496, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>GeoLLM-Engine: A Realistic Environment for Building Geospatial Copilots</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.15500"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Corporation, USA<br>
      • Benchmark Name: GeoLLM-Engine, Task Number: 500000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>A Survey on the Memory Mechanism of Large Language Model based Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.13501"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/nuster1128/LLM_Agent_Memory_Survey"><img src="https://img.shields.io/github/stars/nuster1128/LLM_Agent_Memory_Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Renmin University of China<br>
      • Paper Number: 174<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>AutoScraper: A Progressive Understanding Web Agent for Web Scraper Generation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.12753"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/EZ-hwh/AutoScraper"><img src="https://img.shields.io/github/stars/EZ-hwh/AutoScraper.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Key Laboratory of Data Science, School of Computer Science, Fudan University<br>
      • Agent Name: AUTOSCRAPER, Base Model: LLMs, Strategy: Progressive Understanding<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>From Language Models to Practical Self-Improving Computer Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.11964"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: New York University<br>
      • Agent Name: LLM-powered general computer agent, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>The Landscape of Emerging AI Agent Architectures for Reasoning, Planning, and Tool Calling: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.11584"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Neudesic, an IBM Company<br>
      • Paper Number: 38<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>AgentKit: Structured LLM Reasoning with Dynamic Graphs</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.11483"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: AgentKit, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Search Beyond Queries: Training Smaller Language Models for Web Interactions via Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.10887"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Kentucky<br>
      • Agent Name: GLAINTEL, Base Model: Flan-T5, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>MMInA: Benchmarking Multihop Multimodal Internet Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.09992"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://mmina.cliangyu.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University<br>
      • Benchmark Name: MMInA, Task Number: 1050, Dataset Source: human-written tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>ChatShop: Interactive Information Seeking with Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.09911"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Duke University<br>
      • Benchmark Name: ChatShop, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Enhancing Mobile "How-to" Queries with Automated Search Results Verification and Reranking</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.08860"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Santa Cruz<br>
      • Agent Name: Action Prediction Model, Base Model: GPT4-V, Strategy: Prompt<br>
      • Benchmark Name: MagicWand, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Training a Vision Language Model as Smartphone Assistant</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.08755"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Agile Loop<br>
      • Agent Name: UI-VLM, Base Model: Qwen-VL, Strategy: next-token prediction and masked self-attention<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>LLM Agents can Autonomously Exploit One-day Vulnerabilities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.08144"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: LLM CVE agent, Base Model: GPT-4, Strategy: ReAct agent framework<br>
      • Benchmark Name: Real-world one-day vulnerabilities, Task Number: 15, Dataset Source: CVE database and academic papers<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.07972"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/os-world"><img src="https://img.shields.io/github/stars/github.com/os-world.svg?style=social&label=Star"></a><br>
      <a href="https://os-world.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Benchmark Name: OSWORLD, Task Number: 369, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Autonomous Evaluation and Refinement of Digital Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.06474"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Berkeley-NLP/Agent-Eval-Refine"><img src="https://img.shields.io/github/stars/Berkeley-NLP/Agent-Eval-Refine.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC Berkeley<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>VisualWebBench: How Far Have Multimodal LLMs Evolved in Web Page Understanding and Grounding?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.05955"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://visualwebbench.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Chinese University of Hong Kong<br>
      • Benchmark Name: VisualWebBench, Task Number: 7, Dataset Source: human-curated instances<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>WILBUR: Adaptive In-Context Learning for Robust and Accurate Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.05902"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California Berkeley<br>
      • Agent Name: WILBUR, Base Model: LLM, Strategy: Adaptive In-Context Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>AI2Apps: A Visual IDE for Building LLM-based AI Agent Applications</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.04902"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Avdpro/ai2apps"><img src="https://img.shields.io/github/stars/Avdpro/ai2apps.svg?style=social&label=Star"></a><br>
      <a href="https://www.ai2apps.com"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Exploring Autonomous Agents through the Lens of Large Language Models: A Review</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.04442"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: North South University<br>
      • Paper Number: 117<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>AutoWebGLM: A Large Language Model-based Web Navigating Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.03648"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/AutoWebGLM"><img src="https://img.shields.io/github/stars/THUDM/AutoWebGLM.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: AutoWebGLM, Base Model: ChatGLM3-6B, Strategy: SFT, Reinforcement Learning, Rejection Sampling Finetuning<br>
      • Benchmark Name: AutoWebBench, Task Number: 50, Dataset Source: model-assisted and manual methods<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Measuring Social Norms of Large Language Models</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.02491"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/datasets/socialnormdataset/social"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Peking University<br>
      • Benchmark Name: Social, Task Number: 12383, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>PromptRPA: Generating Robotic Process Automation on Smartphones from Textual Prompts</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.02475"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Technology, Tsinghua University, China<br>
      • Agent Name: PromptRPA, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2024</td>
    <td style="width: 40%;"><strong>Octopus v2: On-device language model for super agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2404.01744"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Agent Name: Octopus v2, Base Model: Gemma 2B, Strategy: Fine-tuning with functional tokens<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>AgentStudio: A Toolkit for Building General Virtual Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.17918"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://computer-agents.github.io/agent-studio"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: NTU, Singapore<br>
      • Benchmark Name: AgentStudio, Task Number: 205, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>AgentStudio: A Toolkit for Building General Virtual Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.17918"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://computer-agents.github.io/agent-studio"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: NTU, Singapore<br>
      • Benchmark Name: AgentStudio overall benchmark tasks, Task Number: 205, Dataset Source: human demonstration<br>
      • Benchmark Name: GroundUI, Task Number: 18026, Dataset Source: existing datasets and AgentStudio-collected data<br>
      • Benchmark Name: IDMBench, Task Number: 345, Dataset Source: Mind2Web, Android in the Wild, VisualWebArena, and AgentStudio<br>
      • Benchmark Name: CriticBench, Task Number: 350, Dataset Source: Mind2Web, Android in the Wild, VisualWebArena, and AgentStudio<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>ReAct Meets ActRe: When Language Agents Enjoy Training Data Autonomy</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.14589"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: A3T, Base Model: Mistral-7B-Instruct-v0.2, Strategy: Policy Gradient<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>Tur[k]ingBench: A Challenge Benchmark for Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.11905"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://turkingbench.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Johns Hopkins University<br>
      • Benchmark Name: TURKING BENCH, Task Number: 158, Dataset Source: crowdsourcing tasks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>AUTONODE: A Neuro-Graphic Self-Learnable Engine for Cognitive GUI Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.10171"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: SuperAGI Research<br>
      • Agent Name: AUTONODE, Base Model: GPT-4V, Strategy: Neuro-graphic Operations<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>AutoGuide: Automated Generation and Selection of Context-Aware Guidelines for Large Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.08978"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Michigan<br>
      • Agent Name: AUTOGUIDE, Base Model: GPT-4-turbo, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>CleanAgent: Automating Data Standardization with LLM-based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.08291"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Simon Fraser University<br>
      • Agent Name: CleanAgent, Base Model: LLM-based Agents, Strategy: Declarative API Calls<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>BAGEL: Bootstrapping Agents by Guiding Exploration with Language</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.08140"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Stanford University<br>
      • Agent Name: BAGEL, Base Model: PaLM-2, Strategy: Iterative relabeling with LM components<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.07718"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ServiceNow/WorkArena"><img src="https://img.shields.io/github/stars/ServiceNow/WorkArena.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: ServiceNow Research<br>
      • Benchmark Name: WorkArena, Task Number: 33, Dataset Source: <br>
      • Benchmark Name: BrowserGym, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>TRAD: Enhancing LLM Agents with Step-Wise Thought Retrieval and Aligned Decision</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.06221"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/skyriver-2000/TRAD-Official"><img src="https://img.shields.io/github/stars/skyriver-2000/TRAD-Official.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: TRAD, Base Model: GPT-4, Strategy: Thought Retrieval and Aligned Decision<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>Cradle: Empowering Foundation Agents Towards General Computer Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.03186"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://baai-agents.github.io/Cradle/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanyang Technological University, Singapore<br>
      • Agent Name: CRADLE, Base Model: GPT-4o, Strategy: Modular Framework<br>
      • Benchmark Name: OSWorld, Task Number: 369, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>Android in the Zoo: Chain-of-Action-Thought for GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.02713"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/IMNearth/CoAT"><img src="https://img.shields.io/github/stars/IMNearth/CoAT.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Agent Name: CoAT, Base Model: GPT-4V, Strategy: Prompt<br>
      • Benchmark Name: AITZ, Task Number: 18643, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2024</td>
    <td style="width: 40%;"><strong>Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2403.02502"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Yifan-Song793/ETO"><img src="https://img.shields.io/github/stars/Yifan-Song793/ETO.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Computer Science, Peking University<br>
      • Agent Name: ETO, Base Model: Llama-2-7B-Chat, Strategy: Behavioral Cloning, DPO<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.19446"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/YifeiZhou02/ArCHer"><img src="https://img.shields.io/github/stars/YifeiZhou02/ArCHer.svg?style=social&label=Star"></a><br>
      <a href="https://yifeizhou02.github.io/archer.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Berkeley<br>
      • Agent Name: ArCHer, Base Model: , Strategy: Hierarchical Multi-Turn RL<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Are LLMs Capable of Data-based Statistical and Causal Reasoning? Benchmarking Advanced Quantitative Reasoning with Data</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.17644"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xxxiaol/QRData"><img src="https://img.shields.io/github/stars/xxxiaol/QRData.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Wangxuan Institute of Computer Technology, Peking University<br>
      • Benchmark Name: QRDATA, Task Number: 411, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.17553"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://huggingface.co/datasets/Writer/omniact"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: OmniACT, Task Number: 9802, Dataset Source: human annotation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>BASES: Large-scale Web Search User Simulation with Large Language Model based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.17505"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Agent Name: BASES, Base Model: GPT-4, Strategy: Prompt<br>
      • Benchmark Name: WARRIORS, Task Number: 100000, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>WIPI: A New Web Threat for LLM-Driven Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.16965"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Wisconsin-Madison<br>
      • Benchmark Name: WIPI, Task Number: 18, Dataset Source: real-world webpages<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Large Multimodal Agents: A Survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.15116"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/jun0wanan/awesome-large-multimodal-agents"><img src="https://img.shields.io/github/stars/jun0wanan/awesome-large-multimodal-agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shenzhen Research Institute of Big Data<br>
      • Paper Number: 81<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>On the Multi-turn Instruction Following for Conversational Web Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.15057"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/magicgh/self-map"><img src="https://img.shields.io/github/stars/magicgh/self-map.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National University of Singapore<br>
      • Benchmark Name: MT-Mind2Web, Task Number: 720, Dataset Source: expert-annotated web navigation dataset<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Soft Self-Consistency Improves Language Model Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.13212"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/HanNight/soft_self_consistency"><img src="https://img.shields.io/github/stars/HanNight/soft_self_consistency.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UNC Chapel Hill<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.11941"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xbmxb/CoCo-Agent"><img src="https://img.shields.io/github/stars/xbmxb/CoCo-Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: CoCo-Agent, Base Model: LLaV A, Strategy: Comprehensive Environment Perception (CEP) and Conditional Action Prediction (CAP)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.11208"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lancopku/agent-backdoor-attacks"><img src="https://img.shields.io/github/stars/lancopku/agent-backdoor-attacks.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China<br>
      • Benchmark Name: Agent Backdoor Attacks, Task Number: 2, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>PRompt Optimization in Multi-Step Tasks (PROMST): Integrating Human Feedback and Heuristic-based Sampling</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.08702"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/yongchao98/PROMST"><img src="https://img.shields.io/github/stars/yongchao98/PROMST.svg?style=social&label=Star"></a><br>
      <a href="https://yongchao98.github.io/MIT-REALM-PROMST/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: MIT / Harvard University<br>
      • Benchmark Name: PROMST, Task Number: 11, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>ScreenAgent: A Vision Language Model-driven Computer Control Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.07945"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/niuzaisheng/ScreenAgent"><img src="https://img.shields.io/github/stars/niuzaisheng/ScreenAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: School of Artificial Intelligence, Jilin University<br>
      • Agent Name: ScreenAgent, Base Model: GPT-4V, Strategy: Reinforcement Learning<br>
      • Benchmark Name: ScreenAgent Dataset, Task Number: 273, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>UFO: A UI-Focused Agent for Windows OS Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.07939"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/microsoft/UFO"><img src="https://img.shields.io/github/stars/microsoft/UFO.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
      • Agent Name: UFO, Base Model: GPT-Vision, Strategy: Prompt<br>
      • Benchmark Name: WindowsBench, Task Number: 50, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Towards Unified Alignment Between Agents, Humans, and Environment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.07744"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://agent-force.github.io/unified-alignment-for-agents.html"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Technology, Tsinghua University, Beijing, China<br>
      • Agent Name: UA2 Agent, Base Model: GPT-3.5, Strategy: Structured Memory<br>
      • Benchmark Name: Retrofitted WebShop, Task Number: 500, Dataset Source: artificially constructed instructions<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>OS-Copilot: Towards Generalist Computer Agents with Self-Improvement</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.07456"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://os-copilot.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai AI Laboratory<br>
      • Agent Name: FRIDAY, Base Model: GPT-4, Strategy: self-directed learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>LLM Agents can Autonomously Hack Websites</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.06664"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UIUC<br>
      • Agent Name: LLM Agent, Base Model: GPT-4, Strategy: Function calling, document reading, and planning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Understanding the Weakness of Large Language Model Agents within a Complex Android Environment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.06596"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/AndroidArenaAgent/AndroidArena"><img src="https://img.shields.io/github/stars/AndroidArenaAgent/AndroidArena.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Peking University<br>
      • Benchmark Name: AndroidArena, Task Number: 221, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>CoSearchAgent: A Lightweight Collaborative Search Agent with Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.06360"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/pygongnlp/CoSearchAgent"><img src="https://img.shields.io/github/stars/pygongnlp/CoSearchAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: GSAI, Renmin University of China<br>
      • Agent Name: CoSearchAgent, Base Model: ChatGPT, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>WebLINX: Real-World Website Navigation with Multi-Turn Dialogue</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.05930"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://mcgill-nlp.github.io/weblinx"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Mila Quebec AI Institute<br>
      • Benchmark Name: WEBLINX, Task Number: 2337, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Dual-View Visual Contextualization for Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.04476"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: DUAL-VCR, Base Model: , Strategy: <br>
      • Benchmark Name: Mind2Web, Task Number: 2000, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Understanding the planning of LLM agents: A survey</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.02716"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Science and Technology of China<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2024</td>
    <td style="width: 40%;"><strong>Computational Experiments Meet Large Language Model Based Agents: A Survey and Perspective</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2402.00262"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tianjin University<br>
      • Paper Number: 292<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.16158"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/X-PLUG/MobileAgent"><img src="https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Agent Name: Mobile-Agent, Base Model: GPT-4V, Strategy: Prompt<br>
      • Benchmark Name: Mobile-Eval, Task Number: 10, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.13919"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MinorJerry/WebVoyager"><img src="https://img.shields.io/github/stars/MinorJerry/WebVoyager.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Zhejiang University<br>
      • Agent Name: WebVoyager, Base Model: GPT-4V, Strategy: Prompt<br>
      • Benchmark Name: WebVoyager Benchmark, Task Number: 643, Dataset Source: self-instruct<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.13649"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: VisualWebArena, Task Number: 910, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>Stream-based perception for cognitive agents in mobile ecosystems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.13604"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hannover University of Applied Sciences and Arts<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.13178"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/hkust-nlp/AgentBoard"><img src="https://img.shields.io/github/stars/hkust-nlp/AgentBoard.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Benchmark Name: AGENT BOARD, Task Number: 9, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.10935"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/njucckevin/SeeClick"><img src="https://img.shields.io/github/stars/njucckevin/SeeClick.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science and Technology, Nanjing University<br>
      • Agent Name: SeeClick, Base Model: Qwen-VL, Strategy: GUI grounding pre-training<br>
      • Benchmark Name: ScreenSpot, Task Number: 1200, Dataset Source: automated curation from web and mobile<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.05459"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MobileLLM/Personal_LLM_Agents_Survey"><img src="https://img.shields.io/github/stars/MobileLLM/Personal_LLM_Agents_Survey.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Institute for AI Industry Research (AIR), Tsinghua University<br>
      • Paper Number: 445<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>MobileAgent: enhancing mobile control via human-machine interaction and SOP integration</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.04124"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/alipay/mobile-agent"><img src="https://img.shields.io/github/stars/alipay/mobile-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Ant Group<br>
      • Agent Name: Ant Intelligent Assistant (AIA), Base Model: QWen-7B, Strategy: Supervised Fine-Tuning (SFT) with LoRA<br>
      • Benchmark Name: AitW, Task Number: 30000, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>Agent AI: Surveying the Horizons of Multimodal Interaction</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.03568"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Stanford University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>Overview of Dialogue Robot Competition 2023</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.03547"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Hiroshi Ishiguro Laboratories, ATR, Kyoto, Japan<br>
      • Benchmark Name: DRC2023, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>XUAT-Copilot: Multi-Agent Collaborative System for Automated User Acceptance Testing with Large Language Model</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.02705"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: WeChat Pay, Tencent<br>
      • Agent Name: XUAT-Copilot, Base Model: LLM, Strategy: Multi-Agent Collaborative Framework<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2024</td>
    <td style="width: 40%;"><strong>GPT-4V(ision) is a Generalist Web Agent, if Grounded</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2401.01614"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/SeeAct"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct.svg?style=social&label=Star"></a><br>
      <a href="https://osu-nlp-group.github.io/SeeAct"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Agent Name: SEEACT, Base Model: GPT-4V, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>WebVLN: Vision-and-Language Navigation on Websites</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.15820"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/WebVLN/WebVLN"><img src="https://img.shields.io/github/stars/WebVLN/WebVLN.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Australian Institute for Machine Learning, The University of Adelaide<br>
      • Agent Name: Website-aware VLN Network (WebVLN-Net), Base Model: , Strategy: <br>
      • Benchmark Name: WebVLN-v1, Task Number: 14925, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>AppAgent: Multimodal Agents as Smartphone Users</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.13771"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://appagent-official.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent<br>
      • Agent Name: AppAgent, Base Model: GPT-4, Strategy: Exploration and Observation<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.13108"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/assistgui"><img src="https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star"></a><br>
      <a href="https://showlab.github.io/assistgui/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Show Lab, National University of Singapore<br>
      • Benchmark Name: ASSIST GUI, Task Number: 100, Dataset Source: not specified<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.11970"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Paper Number: 245<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.10763"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenM3D/M3DBench"><img src="https://img.shields.io/github/stars/OpenM3D/M3DBench.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Fudan University<br>
      • Benchmark Name: M3DBench, Task Number: 15, Dataset Source: LLM synthesis<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>UINav: A Practical Approach to Train On-Device Automation Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.10170"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Agent Name: UINav, Base Model: SmallBERT, Strategy: Demonstration-based training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>Vision-Language Models as a Source of Rewards</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.09187"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>CogAgent: A Visual Language Model for GUI Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.08914"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/CogVLM"><img src="https://img.shields.io/github/stars/THUDM/CogVLM.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Agent Name: CogAgent, Base Model: CogVLM, Strategy: cross-attention module<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2023</td>
    <td style="width: 40%;"><strong>The Generalization Gap in Offline Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2312.05742"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/facebookresearch/gen_dgrl"><img src="https://img.shields.io/github/stars/facebookresearch/gen_dgrl.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: FAIR at Meta<br>
      • Benchmark Name: Procgen and WebShop Datasets, Task Number: , Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>Exposing Limitations of Language Model Agents in Sequential-Task Compositions on the Web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.18751"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/compositional_rl/compwob"><img src="https://img.shields.io/github/stars/compositional_rl/compwob.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind, USA<br>
      • Benchmark Name: CompWoB, Task Number: 50, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.11797"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Zoeyyao27/CoT-Igniting-Agent"><img src="https://img.shields.io/github/stars/Zoeyyao27/CoT-Igniting-Agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>Testing Language Model Agents Safely in the Wild</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.10538"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Significant-Gravitas/Auto-GPT-Benchmarks/tree/master/paper"><img src="https://img.shields.io/github/stars/master/paper.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AutoGPT/Independent<br>
      • Benchmark Name: AgentMonitor, Task Number: 29, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>ML-Bench: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.09835"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/gersteinlab/ML-bench"><img src="https://img.shields.io/github/stars/gersteinlab/ML-bench.svg?style=social&label=Star"></a><br>
      <a href="https://ml-bench.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Yale University<br>
      • Benchmark Name: ML-BENCH, Task Number: 9641, Dataset Source: GitHub repositories<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>Autonomous Large Language Model Agents Enabling Intent-Driven Mobile GUI Testing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.08649"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/testing-agent/droidagent"><img src="https://img.shields.io/github/stars/testing-agent/droidagent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: KAIST<br>
      • Agent Name: DROID AGENT, Base Model: Large Language Models, Strategy: Autonomous GUI testing<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.07562"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/zzxslp/MM-Navigator"><img src="https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UC San Diego<br>
      • Agent Name: MM-Navigator, Base Model: GPT-4V, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2023</td>
    <td style="width: 40%;"><strong>Agent Lumos: Unified and Modular Training for Open-Source Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2311.05657"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/allenai/lumos"><img src="https://img.shields.io/github/stars/allenai/lumos.svg?style=social&label=Star"></a><br>
      <a href="https://allenai.github.io/lumos/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: UCLA<br>
      • Agent Name: LUMOS, Base Model: LLAMA-2-7B/13B, Strategy: Unified and Modular Training<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>Hybrid Minimax-MCTS and Difficulty Adjustment for General Game Playing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.16581"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/marcoantonioaav/Hybrid-Minimax-MCTS"><img src="https://img.shields.io/github/stars/marcoantonioaav/Hybrid-Minimax-MCTS.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Universidade Federal do Rio Grande do Sul<br>
      • Agent Name: Hybrid Minimax-MCTS, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>O3D: Offline Data-driven Discovery and Distillation for Sequential Decision-Making with Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.14403"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: JPMorgan AI Research<br>
      • Agent Name: O3D, Base Model: LLM, Strategy: Offline Data-driven Discovery and Distillation<br>
      • Benchmark Name: ALFWorld, Task Number: 134, Dataset Source: human demonstration<br>
      • Benchmark Name: WebShop, Task Number: 500, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>OpenAgents: An Open Platform for Language Agents in the Wild</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.10634"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/xlang-ai/OpenAgents"><img src="https://img.shields.io/github/stars/xlang-ai/OpenAgents.svg?style=social&label=Star"></a><br>
      <a href="https://chat.xlang.ai"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Hong Kong<br>
      • Agent Name: OpenAgents, Base Model: GPT-4, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>A Zero-Shot Language Agent for Computer Control with Structured Reflection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.08740"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/zero_shot_structured_reflection"><img src="https://img.shields.io/github/stars/master/zero_shot_structured_reflection.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research, Mountain View, U.S.A.<br>
      • Agent Name: Zero-Shot Language Agent, Base Model: PaLM2, Strategy: Structured Reflection<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>Lemur: Harmonizing Natural Language and Code for Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.06830"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenLemur/Lemur"><img src="https://img.shields.io/github/stars/OpenLemur/Lemur.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Hong Kong<br>
      • Agent Name: Lemur, Base Model: Llama-2-70B, Strategy: Pre-training and instruction fine-tuning<br>
      • Agent Name: Lemur-Chat, Base Model: Llama-2-70B, Strategy: Instruction fine-tuning<br>
      • Benchmark Name: MINT, Task Number: 13, Dataset Source: Repurposed existing datasets<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2023</td>
    <td style="width: 40%;"><strong>Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2310.04406"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/lapisrocks/LanguageAgentTreeSearch"><img src="https://img.shields.io/github/stars/lapisrocks/LanguageAgentTreeSearch.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Illinois Urbana-Champaign<br>
      • Agent Name: LATS, Base Model: GPT-3.5, Strategy: Monte Carlo Tree Search<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>Raijū: Reinforcement Learning-Guided Post-Exploitation for Automating Security Assessment of Network Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.15518"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Information Technology, Ho Chi Minh City, Vietnam<br>
      • Agent Name: Raijū, Base Model: , Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>An In-depth Survey of Large Language Model-based Artificial Intelligence Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.14365"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Beijing Jiaotong University<br>
      • Paper Number: 150<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>You Only Look at Screens: Multimodal Chain-of-Action Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.11436"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/cooelf/Auto-GUI"><img src="https://img.shields.io/github/stars/cooelf/Auto-GUI.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: Auto-GUI, Base Model: , Strategy: chain-of-action technique<br>
      • Benchmark Name: AITW, Task Number: 30000, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>LASER: LLM Agent with State-Space Exploration for Web Navigation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.08172"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tencent AI Lab, Bellevue, WA<br>
      • Agent Name: LASER, Base Model: GPT-4, Strategy: State-Space Exploration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>Agents: An Open-source Framework for Autonomous Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.07870"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aiwaves-cn/agents"><img src="https://img.shields.io/github/stars/aiwaves-cn/agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: AIWaves Inc.<br>
      • Agent Name: AGENTS, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>Spoken Humanoid Embodied Conversational Agents in Mobile Serious Games: A Usability Assessment</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.07773"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Edinburgh<br>
      • Agent Name: Spoken Humanoid Embodied Conversational Agents (HECAs), Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2023</td>
    <td style="width: 40%;"><strong>Towards Autonomous Cyber Operation Agents: Exploring the Red Case</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2309.02247"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Defence Research & Development Canada<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>MONDEO: Multistage Botnet Detection</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.16570"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/prodaft/malware-ioc/blob/master/FluBot/FluBot.pdf"><img src="https://img.shields.io/github/stars/FluBot/FluBot.pdf.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Coimbra<br>
      • Agent Name: MONDEO, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>A Multi-Perspective Learning to Rank Approach to Support Children's Information Seeking in the Classroom</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.15265"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/Neelik/REdORank"><img src="https://img.shields.io/github/stars/Neelik/REdORank.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Delft University of Technology<br>
      • Agent Name: REdORank, Base Model: , Strategy: multi-perspective learning to rank<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>Towards an On-device Agent for Text Rewriting</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.11807"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Agent Name: On-device Agent for Text Rewriting, Base Model: PaLM 2-XXS, Strategy: SFT + heuristic RL<br>
      • Benchmark Name: MESSAGE REWRITE EVAL, Task Number: 5, Dataset Source: human-donated message texts<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>A Survey on Large Language Model based Autonomous Agents</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Survey-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.11432"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Gaoling School of Artificial Intelligence, Renmin University of China, Beijing, 100872, China<br>
      • Paper Number: 100<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>BOLAA: Benchmarking and Orchestrating LLM-augmented Autonomous Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.05960"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/salesforce/BOLAA"><img src="https://img.shields.io/github/stars/salesforce/BOLAA.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Salesforce Research, USA<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>AgentBench: Evaluating LLMs as Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.03688"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/THUDM/AgentBench"><img src="https://img.shields.io/github/stars/THUDM/AgentBench.svg?style=social&label=Star"></a><br>
      <a href="https://llmbench.ai/agent"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Tsinghua University<br>
      • Benchmark Name: AGENT BENCH, Task Number: 8, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>Mamba: Bringing Multi-Dimensional ABR to WebRTC</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.03643"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nanjing University<br>
      • Agent Name: Mamba, Base Model: , Strategy: multi-agent reinforcement learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2023</td>
    <td style="width: 40%;"><strong>Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2308.02151"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/weirayao/Retroformer"><img src="https://img.shields.io/github/stars/weirayao/Retroformer.svg?style=social&label=Star"></a><br>
      <a href="https://Retroformer.github.io/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Salesforce AI Research<br>
      • Agent Name: Retroformer, Base Model: GPT-3, Strategy: Policy Gradient Optimization<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2023</td>
    <td style="width: 40%;"><strong>WebArena: A Realistic Web Environment for Building Autonomous Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2307.13854"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://webarena.dev/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Benchmark Name: WebArena, Task Number: 812, Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2023</td>
    <td style="width: 40%;"><strong>A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2307.12856"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
      • Agent Name: WebAgent, Base Model: Flan-U-PaLM, Strategy: self-experience supervision<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2023</td>
    <td style="width: 40%;"><strong>Towards an architectural framework for intelligent virtual agents using probabilistic programming</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2307.10693"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Université Grenoble Alpes, CNRS, Grenoble INP, GIPSA-lab, 38000 Grenoble, France<br>
      • Agent Name: KorraAI, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2023</td>
    <td style="width: 40%;"><strong>Android in the Wild: A Large-Scale Dataset for Android Device Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2307.10088"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/android_in_the_wild"><img src="https://img.shields.io/github/stars/master/android_in_the_wild.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Benchmark Name: AITW, Task Number: 30378, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>AR2-D2:Training a Robot Without a Robot</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.13818"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="www.ar2d2.site"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Washington<br>
      • Agent Name: AR2-D2, Base Model: , Strategy: Behavior Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>Creating Valid Adversarial Examples of Malware</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.13587"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Faculty of Information Technology, Czech Technical University in Prague<br>
      • Agent Name: Adversarial Malware Generator (AMG), Base Model: , Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>Large Language Models Are Semi-Parametric Reinforcement Learning Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.07929"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OpenDFM/Rememberer"><img src="https://img.shields.io/github/stars/OpenDFM/Rememberer.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Agent Name: REMEMBERER, Base Model: GPT-3.5, Strategy: Reinforcement Learning with Experience Memory (RLEM)<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>Synapse: Trajectory-as-Exemplar Prompting with Memory for Computer Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.07863"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ltzheng.github.io/Synapse"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: NTU, Singapore<br>
      • Agent Name: SYNAPSE, Base Model: GPT-3.5, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>Mind2Web: Towards a Generalist Agent for the Web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.06070"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/OSU-NLP-Group/Mind2Web"><img src="https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web.svg?style=social&label=Star"></a><br>
      <a href="https://osu-nlp-group.github.io/Mind2Web"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The Ohio State University<br>
      • Benchmark Name: MIND2WEB, Task Number: 2000, Dataset Source: crowdsourced action sequences<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>A Novel Approach To User Agent String Parsing For Vulnerability Analysis Using Mutli-Headed Attention</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.03733"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Deloitte & Touche LLP<br>
      • Benchmark Name: UAS Parsing Methodology, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>Auto-GPT for Online Decision Making: Benchmarks and Additional Opinions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.02224"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/younghuman/LLMAgent"><img src="https://img.shields.io/github/stars/younghuman/LLMAgent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Amazon<br>
      • Agent Name: Auto-GPT, Base Model: GPT-4, Strategy: Additional Opinions algorithm<br>
      • Benchmark Name: WebShop, Task Number: 50, Dataset Source: simulated environment<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2023</td>
    <td style="width: 40%;"><strong>From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2306.00245"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-deepmind/pix2act"><img src="https://img.shields.io/github/stars/google-deepmind/pix2act.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google DeepMind<br>
      • Agent Name: PIX2ACT, Base Model: PIX2STRUCT, Strategy: Behavioral Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2023</td>
    <td style="width: 40%;"><strong>NASimEmu: Network Attack Simulator & Emulator for Training Agents Generalizing to Novel Scenarios</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2305.17246"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/jaromiru/NASimEmu"><img src="https://img.shields.io/github/stars/jaromiru/NASimEmu.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Czech Technical University in Prague<br>
      • Benchmark Name: NASimEmu, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2023</td>
    <td style="width: 40%;"><strong>BertRLFuzzer: A BERT and Reinforcement Learning Based Fuzzer</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2305.12534"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bert-rl-fuzzer/fuzzer.git"><img src="https://img.shields.io/github/stars/bert-rl-fuzzer/fuzzer.git.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Institute of Technology<br>
      • Agent Name: BERT RLFuzzer, Base Model: BERT, Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2023</td>
    <td style="width: 40%;"><strong>Multimodal Web Navigation with Instruction-Finetuned Foundation Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2305.11854"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: The University of Tokyo<br>
      • Agent Name: WebGUM, Base Model: Flan-T5, Strategy: Finetuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2023</td>
    <td style="width: 40%;"><strong>Mobile-Env: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2305.08144"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/X-LANCE/Mobile-Env"><img src="https://img.shields.io/github/stars/X-LANCE/Mobile-Env.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Benchmark Name: Mobile-Env, Task Number: 74, Dataset Source: real-world apps<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2023</td>
    <td style="width: 40%;"><strong>Evolving Reinforcement Learning Environment to Minimize Learner's Achievable Reward: An Application on Hardening Active Directory Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2304.03998"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Adelaide<br>
      • Agent Name: Critic network assisted Evolutionary Diversity Optimization (C-EDO), Base Model: , Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2023</td>
    <td style="width: 40%;"><strong>Enabling A Network AI Gym for Autonomous Cyber Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2304.01366"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Defence Research & Development Canada<br>
      • Benchmark Name: CyGIL, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2023</td>
    <td style="width: 40%;"><strong>Unified Emulation-Simulation Training Environment for Autonomous Cyber Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2304.01244"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Defence Research and Development Canada<br>
      • Benchmark Name: CyGIL, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2023</td>
    <td style="width: 40%;"><strong>Language Models can Solve Computer Tasks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2303.17491"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/posgnu/rci-agent"><img src="https://img.shields.io/github/stars/posgnu/rci-agent.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of California, Irvine<br>
      • Agent Name: RCI Agent, Base Model: InstructGPT-3+RLHF, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2023</td>
    <td style="width: 40%;"><strong>Hey Dona! Can you help me with student course registration?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2303.13548"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Montclair State University<br>
      • Agent Name: Dona, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2023</td>
    <td style="width: 40%;"><strong>Signifiers as a First-class Abstraction in Hypermedia Multi-Agent Systems</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2302.06970"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of St. Gallen<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2023</td>
    <td style="width: 40%;"><strong>Arena-Web -- A Web-based Development and Benchmarking Platform for Autonomous Navigation Approaches</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2302.02898"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Berlin Institute of Technology<br>
      • Benchmark Name: Arena-Web, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2023</td>
    <td style="width: 40%;"><strong>A System for Human-AI collaboration for Online Customer Support</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2301.12158"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Universität Hamburg<br>
      • Agent Name: Human-AI collaboration system, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2023</td>
    <td style="width: 40%;"><strong>Chatbots in a Honeypot World</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2301.03771"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: PeopleTec<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2022</td>
    <td style="width: 40%;"><strong>Can Current Task-oriented Dialogue Models Automate Real-world Scenarios in the Wild?</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2212.10504"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: NA VER Cloud<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2022</td>
    <td style="width: 40%;"><strong>A Bayesian Model Combination-based approach to Active Malware Analysis</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2212.04781"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Jacobs University<br>
      • Agent Name: Bayesian Model Combination based analyzer, Base Model: , Strategy: Bayesian Model Combination<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2022</td>
    <td style="width: 40%;"><strong>Learning to Navigate Wikipedia by Taking Random Walks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2211.00177"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: DeepMind New York<br>
      • Agent Name: Wikipedia Navigation Agent, Base Model: Transformer, Strategy: Behavioral Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2022</td>
    <td style="width: 40%;"><strong>A Game Benchmark for Real-Time Human-Swarm Control</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2210.15852"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/showlab/assistgui"><img src="https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star"></a><br>
      <a href="https://sites.google.com/view/swarm-game-benchmark"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Northwestern University<br>
      • Benchmark Name: Swarm vs. Swarm Game, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2022</td>
    <td style="width: 40%;"><strong>DinoDroid: Testing Android Apps Using Deep Q-Networks</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2210.06307"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Central Missouri<br>
      • Agent Name: DinoDroid, Base Model: , Strategy: Deep Q-Networks<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2022</td>
    <td style="width: 40%;"><strong>iMedBot: A Web-based Intelligent Agent for Healthcare Related Prediction and Deep Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2210.05671"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="http://iMedBot.odpac.net/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Pittsburgh<br>
      • Agent Name: iMedBot, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2022</td>
    <td style="width: 40%;"><strong>WebCrowds: An Authoring Tool for Crowd Simulation</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2210.04624"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://vhlab.com.br/projects/webcrowds/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: PUCRS<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2022</td>
    <td style="width: 40%;"><strong>Emotion Twenty Questions Dialog System for Lexical Emotional Intelligence</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2210.02400"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="http://emo20q.org"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of St. Thomas<br>
      • Agent Name: EMO20Q Dialog Agent, Base Model: BERT, Strategy: Classification<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2022</td>
    <td style="width: 40%;"><strong>MUG: Interactive Multimodal Grounding on User Interfaces</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2209.15099"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research, Mountain View, U.S.A.<br>
      • Benchmark Name: MUG, Task Number: 77820, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2022</td>
    <td style="width: 40%;"><strong>Enabling Conversational Interaction with Mobile UI using Large Language Models</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2209.08655"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/llm4mobile"><img src="https://img.shields.io/github/stars/master/llm4mobile.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Toronto<br>
      • Agent Name: Conversational Interaction Agent, Base Model: PaLM, Strategy: Prompt<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2022</td>
    <td style="width: 40%;"><strong>Synthetic End-User Testing: Modeling Realistic Agents Based on Behavioral Examples</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2208.12261"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/MEPalma/SyntheticEndUserTesting-Prototype"><img src="https://img.shields.io/github/stars/MEPalma/SyntheticEndUserTesting-Prototype.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Zurich<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2022</td>
    <td style="width: 40%;"><strong>BlenderBot 3: a deployed conversational agent that continually learns to responsibly engage</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2208.03188"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://parl.ai/projects/bb3"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Meta AI<br>
      • Agent Name: BlenderBot 3, Base Model: OPT-175B, Strategy: fine-tuning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2022</td>
    <td style="width: 40%;"><strong>JAM: The JavaScript Agent Machine for Distributed Computing and Simulation with reactive and mobile Multi-agent Systems -- A Technical Report</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2207.11300"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/bsLab/jam"><img src="https://img.shields.io/github/stars/bsLab/jam.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Univ. of Bremen, Dept. of Mathematics & Computer Science, and Institute for Digitization, Bremen, Germany<br>
      • Agent Name: JavaScript Agent Machine (JAM), Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2022</td>
    <td style="width: 40%;"><strong>On Decentralizing Federated Reinforcement Learning in Multi-Robot Scenarios</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2207.09372"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Federal Institute of Science and Technology<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2022</td>
    <td style="width: 40%;"><strong>GriddlyJS: A Web IDE for Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2207.06105"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://griddly.ai"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Queen Mary University<br>
      • Benchmark Name: GriddlyJS, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2022</td>
    <td style="width: 40%;"><strong>CausalAgents: A Robustness Benchmark for Motion Forecasting using Causal Relationships</strong></td>
    <td style="width: 15%;">
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2207.03586"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/causal-agents"><img src="https://img.shields.io/github/stars/google-research/causal-agents.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research, Brain Team<br>
      • Benchmark Name: CausalAgents, Task Number: , Dataset Source: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2022</td>
    <td style="width: 40%;"><strong>WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2207.01206"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://webshop-pnlp.github.io"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Department of Computer Science, Princeton University<br>
      • Benchmark Name: WebShop, Task Number: not specified, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2022</td>
    <td style="width: 40%;"><strong>Fast Inference and Transfer of Compositional Task Structures for Few-shot Task Generalization</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2205.12648"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of Michigan<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2022</td>
    <td style="width: 40%;"><strong>META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2205.11029"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://x-lance.github.io/META-GUI-Leaderboard/"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Shanghai Jiao Tong University<br>
      • Benchmark Name: META-GUI, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2022</td>
    <td style="width: 40%;"><strong>Learning how to Interact with a Complex Interface using Hierarchical Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2204.10374"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/deepmind/acme/tree/master/acme/agents/tf/dqn"><img src="https://img.shields.io/github/stars/tf/dqn.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: DeepMind<br>
      • Agent Name: Hierarchical Distributed Deep Reinforcement Learning architecture, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Apr 2022</td>
    <td style="width: 40%;"><strong>Habitat-Web: Learning Embodied Object-Search Strategies from Human Demonstrations at Scale</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2204.03514"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://ram81.github.io/projects/habitat-web"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Georgia Institute of Technology<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2022</td>
    <td style="width: 40%;"><strong>Multi-agent Searching System for Medical Information</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2203.12465"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Technical University of Sofia<br>
      • Agent Name: multi-agent security system, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2022</td>
    <td style="width: 40%;"><strong>Natural Language Communication with a Teachable Agent</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2203.09016"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Monash University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2022</td>
    <td style="width: 40%;"><strong>A data-driven approach for learning to control computers</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2202.08137"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: DeepMind, London, United Kingdom<br>
      • Agent Name: CC-Net, Base Model: , Strategy: Behavioral Cloning<br>
      • Benchmark Name: MiniWob++, Task Number: 104, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2022</td>
    <td style="width: 40%;"><strong>Governance of Autonomous Agents on the Web: Challenges and Opportunities</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2202.02574"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Umeå University<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2022</td>
    <td style="width: 40%;"><strong>A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2202.02312"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/aburns4/MoTIF"><img src="https://img.shields.io/github/stars/aburns4/MoTIF.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Boston University<br>
      • Benchmark Name: MoTIF, Task Number: 6100, Dataset Source: human demonstration<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Feb 2022</td>
    <td style="width: 40%;"><strong>Feasibility of Interactive 3D Map for Remote Sighted Assistance</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2202.01365"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: College of Information Sciences and Technology, Pennsylvania State University<br>
      • Agent Name: RSA prototype, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2022</td>
    <td style="width: 40%;"><strong>Environment Generation for Zero-Shot Compositional Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2201.08896"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/google-research/google-research/tree/master/compositional_rl"><img src="https://img.shields.io/github/stars/master/compositional_rl.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research, Brain Team<br>
      • Benchmark Name: compositional MiniGrid, Task Number: None, Dataset Source: None<br>
      • Benchmark Name: gMiniWoB, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2021</td>
    <td style="width: 40%;"><strong>Tree-based Focused Web Crawling with Reinforcement Learning</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2112.07620"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: National Technical University of Athens<br>
      • Agent Name: TRES, Base Model: , Strategy: Reinforcement Learning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2021</td>
    <td style="width: 40%;"><strong>Contextual Bandit Applications in Customer Support Bot</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2112.03210"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2021</td>
    <td style="width: 40%;"><strong>LOA: Logical Optimal Actions for Text-based Interaction Games</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2110.10973"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/ibm/loa"><img src="https://img.shields.io/github/stars/ibm/loa.svg?style=social&label=Star"></a><br>
      <a href="https://ibm.biz/acl21-loa"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: IBM Research<br>
      • Agent Name: Logical Optimal Actions (LOA), Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2021</td>
    <td style="width: 40%;"><strong>Sim-to-Real Transfer in Multi-agent Reinforcement Networking for Federated Edge Computing</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Benchmark-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2110.08952"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: University of North Carolina Charlotte<br>
      • Benchmark Name: FedEdge simulator, Task Number: None, Dataset Source: None<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2021</td>
    <td style="width: 40%;"><strong>Learning UI Navigation through Demonstrations composed of Macro Actions</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2110.08653"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Google Research<br>
      • Agent Name: UI navigation agent, Base Model: , Strategy: Behavioral Cloning<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Oct 2021</td>
    <td style="width: 40%;"><strong>Developing a Lecture Video Recording System Using Augmented Reality</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/iOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2110.05955"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Nagoya Institute of Technology<br>
      • Agent Name: Lecture Video Recording System, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2021</td>
    <td style="width: 40%;"><strong>ERICA: An Empathetic Android Companion for Covid-19 Quarantine</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2106.02325"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://youtu.be/PLPEBXLeKJI"><img src="https://img.shields.io/badge/Website-9cf"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Center for Artificial Intelligence Research (CAiRE), HKUST<br>
      • Agent Name: ERICA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Aug 2020</td>
    <td style="width: 40%;"><strong>ICE-Talk: an Interface for a Controllable Expressive Talking Machine</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2008.11045"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/noetits/ICE-Talk"><img src="https://img.shields.io/github/stars/noetits/ICE-Talk.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Numediart Institute, University of Mons<br>
      • Agent Name: ICE-Talk, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Mar 2020</td>
    <td style="width: 40%;"><strong>Towards Effective Human-AI Collaboration in GUI-Based Interactive Task Learning Agents</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/2003.02622"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: SUGILITE, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Dec 2019</td>
    <td style="width: 40%;"><strong>SensAI+Expanse Adaptation on Human Behaviour Towards Emotional Valence Prediction</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1912.10084"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: BioISI, Faculdade de Ciências, Universidade de Lisboa, Portugal<br>
      • Agent Name: SensAI+Expanse, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Sep 2019</td>
    <td style="width: 40%;"><strong>Interactive Task and Concept Learning from Natural Language Instructions and GUI Demonstrations</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Android-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1909.00031"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Carnegie Mellon University<br>
      • Agent Name: PUMICE, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2019</td>
    <td style="width: 40%;"><strong>scenery: Flexible Virtual Reality Visualization on the Java VM</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Linux-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/macOS-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1906.06726"><img src="https://img.shields.io/badge/Paper-red"></a><br>
      <a href="https://github.com/scenerygraphics/scenery"><img src="https://img.shields.io/github/stars/scenerygraphics/scenery.svg?style=social&label=Star"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: CASUS, Görlitz<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">May 2019</td>
    <td style="width: 40%;"><strong>Lessons from Contextual Bandit Learning in a Customer Support Bot</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
      <a><img src="https://img.shields.io/badge/Windows-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1905.02219"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Dynamics 365 AI<br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Nov 2018</td>
    <td style="width: 40%;"><strong>Say Hi to Eliza. An Embodied Conversational Agent on the Web</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1811.05902"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Interactive Technologies Group, Universitat Pompeu Fabra, Barcelona, Spain<br>
      • Agent Name: 3D ECA, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jul 2016</td>
    <td style="width: 40%;"><strong>Towards A Virtual Assistant That Can Be Taught New Tasks In Any Domain By Its End-Users</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1607.00061"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Microsoft Research, New York, NY, U.S.A.<br>
      • Agent Name: Helpa, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jan 2016</td>
    <td style="width: 40%;"><strong>BUbiNG: Massive Crawling for the Masses</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1601.06919"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Dipartimento di Informatica, Università degli Studi di Milano, Italy<br>
      • Agent Name: BUbiNG, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2012</td>
    <td style="width: 40%;"><strong>MAINWAVE: Multi Agents and Issues Negotiation for Web using Alliance Virtual Engine</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1206.5884"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: Maharashtra Institute of Technology, Pune 411038<br>
      • Agent Name: MAINWAVE, Base Model: , Strategy: <br>
    </td>
  </tr>

  <tr>
    <td rowspan="2" style="width: 15%;">Jun 2010</td>
    <td style="width: 40%;"><strong>Design specifications of the Human Robotic interface for the biomimetic underwater robot "yellow submarine project"</strong></td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Web-yellow"></a><br>
    </td>
    <td style="width: 15%;">
      <a><img src="https://img.shields.io/badge/Agent-blue"></a><br>
    </td>
    <td style="width: 15%;">
      <a href="https://arxiv.org/pdf/1006.5263"><img src="https://img.shields.io/badge/Paper-red"></a><br>
    </td>
  </tr>
  <tr>
    <td colspan="4">
      • Affiliation: 341/42 17 cross Ideal Homes Township, Rajarajeshwarinagar Bangalore 560098, India<br>
    </td>
  </tr>
</table>

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
