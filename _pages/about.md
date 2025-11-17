---
permalink: /
title: "Kun Zhou (周昆)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Kun Zhou is a postdoctoral researcher at UC San Diego, working with [Zhiting Hu](http://zhiting.ucsd.edu/) and [Biwei Huang](https://biweihuang.com/). His research interests are **Representation Learning for Foundation Models**, with focuses on Multimodal Foundation Models and Unified Representation Learning, and their applications in complex planning and reasoning tasks. He obtained Ph.D at School of Information, Renmin University of China, under the supervision of [Wayne Xin Zhao](https://scholar.google.com/citations?user=JNhNacoAAAAJ&hl=zh-CN) and [Ji-Rong Wen](https://scholar.google.com/citations?user=tbxCHJgAAAAJ&hl=zh-CN), master degree from Peking University, and bachelor from Hohai University.

#### <font color="red"> Research Opportunities: </font> I am consistently seeking highly motivated students, to work with me in various research projects. If you are interested in my current research topics about improving the advanced capabilities of LLMs and World Models (Complex Reasoning, Multimodal Understanding and Generation), feel free to email me.

News
======
We release [PAN](https://ifm.mbzuai.ac.ae/pan/), A World Model for General, Interactable, and Long-Horizon World Simulation!

Our Vision-G1 is accepted by AAAI 2026! See you in Singapore!

Our three papers are accepted by NeurIPS 2025, with one Spotlight! Thanks for my comrades!

Research Interests
======
Currently, my primary research lies in building Large-scale Multimodal Foundation Models (World Model and Vision-language Models). Concretely, I focus on training World Model and Unified Agent, building their Universal Memory and 
I am devoting to answer the following research problems:

* **How to Build a Strong World Model?**
  * ***Background:*** A Comprehensive Survey about LLMs [Arxiv](https://arxiv.org/abs/2303.18223)
  * ***Training:*** Curriculum Pre-training [YuLan-Chat](https://github.com/RUC-GSAI/YuLan-Chat)
  * ***What is strong?*** Studying Benchmark Leakage for Fair Evaluation [Arxiv](https://arxiv.org/pdf/2311.01964), Decentralized Arena with Collective Intelligence [Blog](https://de-arena.maitrix.org/)
* **How to Enhance the Reasoning Capability?** (Knowledge/Mathematical Reasoning)
  * ***Data Refinement and Synthesis:*** Distilling Data Synthesis Ability [NeurIPS 2024](https://arxiv.org/pdf/2405.14365)
  * ***Training Algorithm:*** RL with Fine-grained Rewards [ACL 2024-Findings](https://arxiv.org/pdf/2401.06081), Low-Redundant Optimization [EMNLP 2024](https://arxiv.org/pdf/2406.12606)
  * ***Tool-Augmented Agent:*** Tool-Augmented Reasoning Agent [EMNLP 2023](https://arxiv.org/pdf/2305.14323), Iterative Deliberation for Error Check [NeurIPS 2023](https://arxiv.org/pdf/2306.02408)
  * ***Reasoning Agent over Structured Data:*** Toolization with Prompting Method [EMNLP 2023](https://arxiv.org/pdf/2305.09645), Autonomous Agent for Reasoning over KG [KG-Agent](https://arxiv.org/pdf/2402.11163)
* **How to Enhance the Multimodal Abilities?** (Image/Video Understanding/Generation )
  * ***Training Data Management:*** Complex Visual Instruction Synthesis [ComVint](https://arxiv.org/pdf/2311.01487), Visual Instruction Value Estimation [TIVE](https://arxiv.org/pdf/2403.09559)
  * ***Multimodal Alignment:*** Object Hallucination Evaluation [EMNLP 2023](https://arxiv.org/pdf/2305.10355), Visual Vulnerabilities for Jailbreaking [ECCV 2024](https://arxiv.org/pdf/2403.09792), Event-oriented Long Video Understanding [VIM](https://arxiv.org/pdf/2406.14129)

Before the era of large language models, I have investigated pre-trained language models (PLMs), and their application on sentence representation learning and complex reasoning.

* **Effective Fine-tuning PLMs**
  * ***General Fine-tuning Strategy:*** Visual-Augmentation [ACL 2023](https://arxiv.org/pdf/2212.07937), Over-Parameterization [ACL 2023](https://aclanthology.org/2023.acl-long.212.pdf)
  * ***PLM as Diffusion Model*** Masked Language Model likes Diffusion Model [EACL 2024 Evaluation and Model Insight Award](https://aclanthology.org/2024.eacl-long.86/)
* **PLM-based Sentence Representations**
  * ***Unsupervised Sentence Representations:*** Debiased Contrastive Learning [ACL 2022](https://arxiv.org/pdf/2205.00656)
  * ***Dense Text Retrieval:*** Ambiguous Negatives Sampling [EMNLP 2022](https://arxiv.org/pdf/2210.11773), Multi-task Bottlenecked MAE [ECML-PKDD 2023](https://arxiv.org/pdf/2212.07841)
* **PLM-based Complex Reasoning**
  * ***Math-specific PLMs:*** Curriculum Pre-training [KDD 2022](https://arxiv.org/pdf/2206.06315), Unified MoE Pre-training [KDD 2023](https://arxiv.org/pdf/2306.11027)
  * ***PLM+KG for Knowledge Reasoning:*** Simple Rule-based KG Encoder [NAACL 2022](https://arxiv.org/pdf/2205.01841), Unified Relation Learning [ICLR 2023](https://arxiv.org/pdf/2212.00959)


I also have done interesting research works about conversational recommender systems, sequential recommendation and dialog system. My whole publication list is in [Publication](https://lancelot39.github.io/publications/)

Open-Source Projects
======
Most of my research work are open-source. Here are some my preferable projects!
* [**JiuZhang3.0**](https://arxiv.org/pdf/2405.14365)
  * We publish JiuZhang3.0-7B/8B/8X7B, a series of LLMs with new SOTA performance on mathematical reasoning tasks, with only 1/4 cost for training and data synthesis!
* [**YuLan-Chat**](https://github.com/RUC-GSAI/YuLan-Chat)
  * YuLan-Chat-3-12B is a LLM trained from scratch. It is pre-trained on over 1.6TB tokens of English, Chinese, and multilingual data, and then supervised fine-tuned via curriculum learning with high-quality English and Chinese instructions and human preference data.
  * YuLan-Chat-2 is developed by continually-pretraining and instruction-tuning LLaMA-2 with high-quality English and Chinese data. It can support 8k maximum length now, and outperforms other llama-2-based bilingual LLM on MMLU, C-Eval and AGIEval-Gaokao.
  * YuLan-Chat is a chat-based large language model developed based on fine-tuning LLaMA. YuLan-Chat can chat with users to well follow English or Chinese instructions, and can be deployed on an GPU (A800-80G or RTX3090) after quantization. YuLan (Simplified Chinese 玉兰), is the campus flower of Renmin University of China.
* [**LLMBook**](https://llmbook-zh.github.io/LLMBook.pdf)
  * A Chinese book for everyone to master the knowledge about large language models.
* [**LLMSurvey**](https://github.com/RUCAIBox/LLMSurvey)
  * A collection of papers and resources related to Large Language Models. The organization of papers refers to our survey "A Survey of Large Language Models". 

Experiences
------
### 2022.4 - 2023.6, Research Intern, NLC Group, MSRA.
#### Mentor: Yeyun Gong, Nan Duan

### 2021.9 - 2022.4, Research Intern, iFLYTEK Research.
#### Mentor: Jing Sha, Shijin Wang

### 2019.12 - 2021.5, Research Intern, NLP center, Meituan Dianping.
#### Mentor: Sirui Wang, Fuzheng Zhang

### 2018.8 - 2019.6, Research Intern, XiaoIce, Microsoft Asia.
#### Mentor: Kai Zhang, Yu Wu

Rewards and Honors
------
* EACL 2024 [Evaluation and Model Insight Award](https://2024.eacl.org/program/best-paper/#evaluation-and-model-insight-award)
* Five Highly-cited Papers are selected as the most influential KDD/WWW/CIKM papers by PaperDigest:
  * [KDD](https://www.paperdigest.org/2023/09/most-influential-kdd-papers-2023-09/): [KGSF](https://www.paperdigest.org/paper/?paper_id=kdd-3394486.3403143-2020-08-21), [UniCRS](https://www.paperdigest.org/paper/?paper_id=kdd-3534678.3539382-2022-08-12)
  * [WWW](https://www.paperdigest.org/2023/09/most-influential-www-papers-2023-09/): [FMLP-Rec](https://www.paperdigest.org/paper/?paper_id=www-3485447.3512111-2022-04-29)
  * [CIKM](https://www.paperdigest.org/2023/09/most-influential-cikm-papers-2023-09/): [S3-Rec](https://www.paperdigest.org/paper/?paper_id=cikm-3340531.3411954-2020-10-19), [MultimodalKG](https://www.paperdigest.org/paper/?paper_id=cikm-3340531.3411947-2020-10-19)
* 2022 Baidu Scholarship (10 PhD Students) [Link](http://scholarship.baidu.com/)
* 2022 Bytedance Scholarship (10 PhD Students in China Mainland) [Link](https://ur.bytedance.com/scholarship)
* 2022 MSRA Fellowship (12 PhD Students in Asia-Pacific-region) [Link](https://www.msra.cn/zh-cn/news/features/2022-fellows)
* 2022 Baosteel Scholarship (12 Students in RUC). 
* 2022 National Scholarship.
* LIC2021 Multi-Skill Dialog Challenge [Link](https://aistudio.baidu.com/aistudio/competition/detail/29?isFromCcf=true)
  * Ranked **1st** in Automatic Metrics Track, **3rd** in Human Evaluation Track
* LIC2020 Conversational Recommendation Challenge [Link](https://aistudio.baidu.com/aistudio/competition/detail/67)
  * Ranked **2st** in Automatic Metrics Track, **4rd** in Human Evaluation Track
* 2018 Jane Street Electronic Trading Challenges 
  * Ranked **1st**
* 2018 The Data Open Challenges Citadel Datathen 
  * Ranked **2nd**
* 2016 American Mathematical Contest in Modeling 
  * **Honorable Mention**
* 2015 China Undergraduate Mathematical Contest in Modeling 
  * **National Second Prize**
* 2015 National Zhou Peiyuan college student mechanics competition 
  * **National Third Prize**
* 2015 Jiangsu Province Undergraduate Mechanical Competition 
  * **The First Prize**

Service
======
* IJCAI 2021
  * **Senior PC Reviewer**
* AAAI, IJCAI, KDD, SIGIR, WWW, WSDM, ACL, EMNLP, COLING, TOIS, TORS
  * **PC Reviewer**

Zhihu Posts
------
I love writing blogs in my free time. Here are some my favorite posts!

[BERT meet Knowledge Graph：预训练模型与知识图谱相结合的研究进展](https://zhuanlan.zhihu.com/p/270009212)

[BERT meet KG第二弹：新训练方式，新问题视角](https://zhuanlan.zhihu.com/p/356415715)
