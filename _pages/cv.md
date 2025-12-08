---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## 基本信息

**齐炜祯** (Weizhen Qi)  
**邮箱：** qiweizhen AT outlook.com  
**电话：** 16599999899  
**出生：** 1997年8月，男  
**Google Scholar：** [https://scholar.google.com/citations?user=rme-IWIAAAAJ](https://scholar.google.com/citations?user=rme-IWIAAAAJ)

## 工作经历

### 云玦科技 | 联合创始人 & CTO (2025.07 - 至今)

- 定义公司的AGI技术路线图，开创性地提出了"自主蝶变体"(AMI)的"四大公理"（无损进化、物理闭环、自举演化、个性化状态）。
- 取得通用智能体核心榜单GAIA的世界第一，科研成果将于12月底或者1月初发布。
- 主导设计了"云玦One OS"，一个以"用户意图"为内核的"关系型智能体原生操作系统"。
- 设计了"软件先行"（iOS App验证）与"硬件V1"（端云协同）相结合的研发交付路线图。

### 中关村学院 | （兼职）科研共建导师 (2025.07-至今)

- 指导多名博士生的科研工作，原计划担任AGI学部副主任及智谱智能体联合实验室主任，离职后转为兼职科研共建导师。
- ACL、EMNLP ARR 2025领域主席（Area Chair）

### 中关村学院、中关村人工智能研究院 | 博士生科研导师、研究员 (2025.03-2025.07)

- 指导多名博士生的科研工作，原计划担任AGI学部副主任及智谱智能体联合实验室主任。

### 微软亚洲研究院 | 联合培养博士 (2019.09-2024.11)

- 以微软内部各工业落地为导向，积累大量工程落地和以落地为导向的科研经验。
- **第一作者提出ProphetNet：** 科研上，提出的MTP被广泛验证和采用，并逐渐成为替换掉逐词预测的预训练范式，被DeepSeek V3、Qwen-3-Next等世界一线模型使用。工业上，大幅度提升必应的营收（是预训练策略替换掉传统NLP策略的基座模型）。
- **独立开展500卡A100、5TB语料的预训练工作ProphetNet-X：** 科研上，是首个同架构多任务的预训练模型簇。工业落地上，支持必应的跨语言生成能力，也是微软小冰等模型的基座模型。
- **第一作者提出BANG：** 科研上，是首个非自回归预训练大模型，支持在效率和质量之间的权衡。工业落地上，支撑必应<50ms的实时响应。
- **参与工程院与OpenAI合作的GPT-3的源代码落地、优化：** 在输出效果完全不变的情况下，为GPT-3带来5-10倍输出速度提升。发表EL-Attention，集成入主流Huggingface Transformers代码库，是业界首批提出KV Cache优化的学者之一，其核心思想与后期DeepSeek的MLA等高效部署的推理算法一致，为大模型的实战落地扫清了障碍。
- **Visual ChatGPT的核心作者之一：** 开源一周获3万Star，该工作开创性地定义了以LLM为中心的、调用多模态工具以完成复杂视觉任务的智能体范式。
- 在读期间，独立开发项目，包含服务于中小B商家的自媒体自动生成Agent、书籍新闻的动态知识图谱构建和一致性审核、量化套利等。

## 教育经历

### 中国科学技术大学 | 本科生 (2015.09-2019.06)

- 高中生全国物理竞赛山东省一等奖、中国科大物理冬令营金奖，物理专业满绩点转计算机。
- 微软联培、推免保送排名学院第一，毕业绩点排名学院第三。

### 台湾大学 | 资讯工程 交换生 (2017.02-2017.07)

### 滑铁卢大学 | 软件工程+深度学习 访问学者 (2018.07-2018.10)

## 主要研究成果

### 奠定预训练基石
- **ProphetNet (MTP架构)：** 第一作者，多词元预测的原创性工作，被DeepSeek V3、Qwen-3-Next等主流LLM模型采纳为核心预训练方法。
- **ProphetNet-X：** 独立开展500显卡、数TB语料的预训练工作，首个同架构多任务的预训练模型簇。

### 模型部署加速
- **EL-Attention：** 业界首批提出KV Cache优化的学者之一，核心思想与DeepSeek的MLA等高效部署推理算法一致。
- **BANG：** 第一作者，业界首个非自回归预训练工作，支撑必应<50ms的实时响应。

### 开创智能体先河
- **Visual ChatGPT：** 核心作者之一，开源一周获3万Star，开创性地定义了以LLM为中心的、调用多模态工具以完成复杂视觉任务的智能体范式。

## 学术服务

- ACL、EMNLP ARR 2025领域主席（Area Chair）

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
