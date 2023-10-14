---
layout: cv
title: Fangkai Jiao
email:
  url: mailto:jiaofangkai@hotmail.com
  text: jiaofangkai [AT] hotmail.com
homepage:
  url: http://sparkjiao.github.io
  text: jiaofangkai.com
phone: +86 178 6415 4896
---

# Fangkai JIAO

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## **Education**

### Nanyang Technological University & Infocomm Research (I2R), A*STAR `2022.8 - 2026.6 (expected)`

- Ph.D. in Computer Science and Engineering
- Supervisor: Assoc Prof. Aixin Sun, Assoc Prof. Shafiq Joty, Dr. Nancy F. Chen 

### Shandong University `2019.9 - 2022.6`

```
GPA: 90.12/100
```

- M.E. in Computer Science and Technology
- Supervisor: Prof. [Liqiang Nie](https://liqiangnie.github.io/)

### Shandong University `2015.9 - 2019.6`

```
GPA: 85.03/100
```

- B.E. in Software Engineering

## **Research Interests**

- Machine reasoning
- Large langauge models
- Self/weak-supervised pre-training

## **Publications**
<!-- <font size=2>* means equal contribution.</font> -->
##### \* means equal contribution.

### **SeaEval for Multilingual Foundation Models: From Cross-Lingual Alignment to Cultural Reasoning**
Bin Wang*, Zhengyuan Liu*, Xin Huang, **Fangkai Jiao**, Yang Ding, Ai Ti Aw, Nancy F. Chen. _Preprint._
[[pdf](https://arxiv.org/abs/2309.04766)]

### **LogicLLM: Exploring Self-supervised Logic-enhanced Training for Large Language Models**
**Fangkai Jiao**, Zhiyang Teng, Shafiq Joty, Bosheng Ding, Aixin Sun, Zhengyuan Liu, Nancy F. Chen. _Preprint._
[[pdf](https://arxiv.org/abs/2305.13718)]
[[code](https://github.com/SparkJiao/MERIt-v2)]


### **Retrieving Multimodal Information for Augmented Generation: A Survey**  
Ruochen Zhao, Hailin Chen, Weishi Wang, **Fangkai Jiao**, Xuan Long Do, Chengwei Qin, Bosheng Ding, Xiaobao Guo, Minzhi Li, Xingxuan Li, Shafiq Joty. _Findings of EMNLP 2023._
[[pdf](https://arxiv.org/abs/2303.10868)]


### **Enhanced Multi-domain Dialogue State Tracker with Second-order Slot Interactions**  
**Fangkai Jiao**, Yangyang Guo, Minlie Huang, and Liqiang Nie. _TASLP 2022._
[[pdf]()]
[[code]()]


### **MERIt: Meta-Path Guided Contrastive Learning for Logical Reasoning**
**Fangkai Jiao**, Yangyang Guo, Xuemeng Song, Liqiang Nie. _Findings of ACL 2022._
[[pdf](https://arxiv.org/abs/2203.00357)]
[[code](https://github.com/SparkJiao/MERIt)]  
<!-- * The motivation of this work is to improve the generalization of neural logical reasoning models by devising task-oriented pre-training.   -->
<!-- * I complete almost all parts of this work. The other co-authors help me polish the paper writing.   -->
<!-- * Our system achieves new state-of-art performance on both [ReClor](https://eval.ai/web/challenges/challenge-page/503/leaderboard/1347) and LogiQA.   -->

### **Personalized Fashion Compatibility Modeling via Metapath-guided Heterogeneous Graph Learning**  
Weili Guan, **Fangkai Jiao**, Xuemeng Song, Haokun Wen, Chung-Hsing Yeh and Xiaojun Chang. _SIGIR 2022._
[[pdf](http://jiaofangkai.com/files/sigir2022-camera-ready.pdf)]
[[code](https://github.com/SparkJiao/MG-PFCM_outfit_rec)]


### **REPT: Bridging Language Models and Machine Reading Comprehension via Retrieval-Based Pre-training**
**Fangkai Jiao**, Yangyang Guo, Yilin Niu, Feng Ji, Feng-Lin Li, Liqiang Nie. _Findings of ACL 2021._
[[pdf](https://arxiv.org/pdf/2105.04201.pdf)]
[[code](https://github.com/SparkJiao/Retrieval-based-Pre-training-for-Machine-Reading-Comprehension)]  
<!-- * The motivation of this work is to alleviate the data hungry problem of machinea reading comprehension system.    -->
<!-- * We propose a retrieval-based pre-training method, including two pretext tasks, namely surrounding sentences prediction and retrieval-based masked language modeling, to augment the pre-trained language models with the ability of evidence extraction.    -->
<!-- - Our pre-training method has achieved substantial improvements over strong baselines on five reading comprehension benchmarks.   -->
<!-- * I am reponsible for almost all of the work and the other co-authors give me valuable suggestions about the paper writing.    -->


### **Conversational Image Search**
Liqiang Nie, **Fangkai Jiao**, Wenjie Wang, Yinglong Wang, and Qi Tian. _Transactions on Image Processing (TIP) 2021_.
[[pdf](https://ieeexplore.ieee.org/document/9528996)]
[[code](https://github.com/SparkJiao/LARCH)]  
<!-- * Existing works have overlooked the (1) the session structure in the conversational query, and (2) the multiform knowledge.   -->
<!-- * We devise a novel contextual image search scheme, LARCH, to facilitate conversational image search.  -->
<!-- * Besides, we construct a augmented dataset based on MMD to facilitate future research.   -->
<!-- * The main idea comes from Prof. Nie and Wenjie Wang. I have proposed several improvements to it, including: (1) increasing the edges of the constructed graph, (2) considering the session-related knowledge, and (3) introducing the gate mechanism.   -->
<!-- * In addition to the above suggestions, my main contributions to this work include system implemetation, experiments, the paper writing of methodology, dataset and experiments.    -->

### **A Self-Training Method for Machine Reading Comprehension with Soft Evidence Extraction**

Yilin Niu\*, **Fangkai Jiao**\*, Mantong Zhou, Ting Yao, Jingfang Xu and Minlie Huang. _ACL 2020._
[[pdf](https://arxiv.org/pdf/2005.05189.pdf)]
[[code](https://github.com/SparkJiao/Self-Training-MRC)]  
<!-- * The motivation of this study is that manually annotating the evidence in a paragraph for reading comprehension is expensive.     -->
<!-- * In this work, we propose a self-training method to supervise the evidence extractor with auto-generated evidence labels.     -->
<!-- * Our method achieves significant improvements on seven datasets over three MRC tasks.   -->
<!-- * My contributions in this work include the discussion of the idea, system implementation, all the experiments except those conducted on Quasar-T, and the paper writing of methodology.   -->


## **Projects**


### PandaLLM

*Chinese Large Language Model (LLM) series based on LLaMA.*  [[code](https://github.com/dandelionsllm/pandallm)][[technical report](https://arxiv.org/pdf/2305.03025.pdf)] (900+ stars)

### SLQA

*An Pytorch Implementation of Multi-Granularity Hierarchical Attention Fusion Networks (ACL 2018).* [[code](https://github.com/SparkJiao/SLQA)] (75 stars)

## **Experience**

### **Lanboat** `2022.4 - 2022.7`
_Intern._   Mentored by [Yulong Wang](https://github.com/Ag2S1) and advised by Dr. [Ming Zhou](https://scholar.google.co.jp/citations?user=a0w5c0gAAAAJ&hl=en)  
Working on semantic parsing (NL2SQL) and machine reasoning.

### **ByteCamp, Bytedance** `2021.8.1 - 2021.8.7`
Working on self-supervised pre-training for dialogue response selection.

### **Damo Academy, Alibaba Group** `2020.7 - 2021.2`
_Research Intern._   Advised by Dr. [Feng Ji](http://scholar.google.com/citations?user=BxWZ-ZgAAAAJ&hl=zh-CN) and Dr. [Feng-Lin Li](http://scholar.google.it/citations?user=xo_dfnMAAAAJ&hl=en)  
Working on Pre-training for question answering.

### **CoAI Group, Tsinghua University** `2018.10 - 2019.8`

_Research Intern._   Advised by Prof. [Minlie Huang](http://coai.cs.tsinghua.edu.cn/hml)  
Working on reading comprehension and dialogue state tracking.

## **Honors & Awards**

Dean's Scholarship `School of Computer Science and Technology, Shandong University, 2021` <br>
Dean Scholarship `School of Software, 2018` <br>
Bronze Medal in the ACM-ICPC Asia Regional Contest Urumqi Site `ICPC, 2017` <br>
Silver Medal in the ACM-ICPC Asia Regional Contest Qingdao Site `ICPC, 2017` <br>
Bronze Medal in the ACM-ICPC Asia Regional Contest China-Final `ICPC, 2016` <br>
Silver Medal in the ACM-ICPC Asia Regional Contest Qingdao Site `ICPC, 2016` <br>
National Scholarship `Ministry of Education, 2016` <br>

---

<!-- ### Footer

Last updated: Oct. 2023 -->
