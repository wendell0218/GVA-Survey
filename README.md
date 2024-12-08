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

- **[November 17, 2024]** Our survey paper is available on the arXiv platform: https://arxiv.org/abs/2411.10943

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

### Section 2: What is GVA?
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

### Section 3: Why we need GVA?
![alt text](./assets/necessity.png)

### Section 4: How to implement GVA?
![alt text](./assets/implementation.png)

### Section 5: How to evaluate GVA?
![alt text](./assets/evaluation.png)

### Section 6: Limitations
![alt text](./assets/limitations.png)

### Section 7: Future
![alt text](./assets/future.png)

## 🔍 Related Papers

We are committed to offering researchers the latest advancements in the field. By regularly reviewing and evaluating recent research studies, we ensure that the list of papers stays up-to-date.

<table style="width: 100%;">
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
