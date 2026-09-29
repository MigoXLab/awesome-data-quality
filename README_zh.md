# 数据质量资源大全 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

一个精心策划的数据质量相关资源、工具、论文和项目列表，涵盖各种数据类型。本仓库旨在为研究人员和从业者提供不同领域数据质量的全面参考。

## 目录

- [简介](#简介)
- [传统数据](#传统数据)
  - [论文](#传统数据论文)
  - [工具与项目](#传统数据工具)
  - [数据准备度评估](#数据准备度评估)
- [大语言模型数据](#大语言模型数据)
  - [预训练数据](#预训练数据)
  - [微调数据](#微调数据)
  - [LLM数据管理](#llm数据管理)
  - [认知工程与测试时扩展](#认知工程)
- [多模态数据](#多模态数据)
  - [论文](#多模态数据论文)
  - [工具与项目](#多模态数据工具)
- [表格数据](#表格数据)
  - [论文](#表格数据论文)
  - [工具与项目](#表格数据工具)
- [时间序列数据](#时间序列数据)
  - [论文](#时间序列数据论文)
  - [工具与项目](#时间序列数据工具)
- [图数据](#图数据)
  - [论文](#图数据论文)
  - [工具与项目](#图数据工具)
- [以数据为中心的AI](#以数据为中心的ai)
  - [综述](#数据中心ai综述)
  - [数据估值](#数据估值)
  - [数据选择](#数据选择)
  - [基准测试](#数据中心ai基准)
- [贡献指南](#贡献指南)

## 简介

数据质量是任何数据驱动应用或研究的关键方面。本仓库收集了与不同数据类型的数据质量相关的资源，包括传统数据、大语言模型数据（预训练和微调）、多模态数据等。

## 传统数据

本节涵盖传统结构化和非结构化数据的数据质量。

### 论文

- [数据清洗：问题与当前方法](https://www.researchgate.net/publication/220423285_Data_Cleaning_Problems_and_Current_Approaches) - 数据清洗方法的全面概述。(2000)
- [数据质量调查：劣质数据分类](https://ieeexplore.ieee.org/document/7423672) - 数据质量问题和分类的调查。(2016)

### 工具与项目

- [Great Expectations](https://github.com/great-expectations/great_expectations) - 用于验证、记录和分析数据的Python框架。(2018)
- [Deequ](https://github.com/awslabs/deequ) - 基于Apache Spark构建的库，用于定义"数据单元测试"。(2018)
- [OpenRefine](https://openrefine.org/) - 处理混乱数据、清洗和转换数据的强大工具。(2010)
- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - 从pandas DataFrame生成概要报告。(2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - 用于自动化数据分析的Python库。(2021)
- [PyDeequ](https://github.com/awslabs/python-deequ) - Deequ的Python API，支持"数据单元测试"。(2020)
- [Evidently](https://github.com/evidentlyai/evidently) - 用于数据漂移检测的开源ML监控框架。(2021)
- [TensorFlow Data Validation (TFDV)](https://www.tensorflow.org/tfx/data_validation/get_started) - 大规模探索和验证ML数据的库。(2018)
- [Deepchecks](https://github.com/deepchecks/deepchecks) - 用于验证ML模型和数据的Python包。(2021)

### 数据准备度评估

本小节涵盖评估AI应用数据准备度的方法和工具。

#### 论文

- [AI数据准备度：360度调查](https://arxiv.org/abs/2404.05779) - 全面调查评估结构化和非结构化数据集AI训练数据准备度的指标。(2024)
- [评估工程教育中学生对生成式人工智能的采用](https://arxiv.org/abs/2503.04696) - 教育AI应用中数据质量考虑的实证研究。(2025)

#### 工具与项目

- [数据准备度评估框架](https://github.com/data-readiness/framework) - 评估AI应用数据质量和准备度的框架。(2024)
- [AI数据质量指标](https://github.com/ai-data-quality/metrics) - AI环境中评估数据质量的标准化指标。(2024)

## 大语言模型数据

### 预训练数据

本节涵盖大语言模型预训练数据的数据质量。

#### 论文

- [The Pile：用于语言建模的800GB多样化文本数据集](https://arxiv.org/abs/2101.00027) - 用于语言模型预训练的大规模精选数据集。(2021)
- [一目了然的质量：网络爬取多语言数据集的审计](https://arxiv.org/abs/2103.12028) - 网络爬取多语言数据集质量的审计。(2021)
- [记录大型网络文本语料库：巨大清洁爬取语料库案例研究](https://arxiv.org/abs/2104.08758) - C4数据集的文档。(2021)
- [回收网络：增强语言模型预训练数据质量和数量的方法](https://arxiv.org/abs/2506.04689) - REWire方法，通过引导重写回收和改善低质量网络文档，解决LLM预训练中的"数据墙"问题。(2025)
- [评估双语言模型训练中数据质量的作用](https://arxiv.org/abs/2506.12966) - 研究揭示不平等的数据质量是双语环境中性能下降的主要驱动因素，并提出实用的多语言模型数据过滤策略。(2025)

#### 工具与项目

- [Dolma](https://github.com/allenai/dolma) - 用于策划和记录大语言模型预训练数据的框架。(2023)
- [文本数据清洗器](https://github.com/ChenghaoMou/text-data-cleaner) - 用于清洗语言模型预训练文本数据的工具。(2022)
- [CCNet](https://github.com/facebookresearch/cc_net) - 下载和过滤CommonCrawl数据的工具。(2020)
- [Dingo](https://github.com/MigoXLab/dingo) - 支持多种数据源、类型和模态的综合数据质量评估工具。(2024)

### 微调数据

本节涵盖大语言模型微调数据的数据质量。

#### 论文

- [通过人类反馈训练语言模型遵循指令](https://arxiv.org/abs/2203.02155) - Anthropic的RLHF论文。(2022)
- [质量而非数量：数据集设计与CLIP鲁棒性的相互作用](https://arxiv.org/abs/2112.07295) - 关于数据质量重要性超过数量的研究。(2021)
- [机器学习任务的数据质量](https://arxiv.org/abs/2108.02711) - 机器学习数据质量的调查。(2021)

#### 工具与项目

- [LMSYS聊天机器人竞技场](https://github.com/lm-sys/FastChat) - 评估LLM响应的平台。(2023)
- [OpenAssistant](https://github.com/LAION-AI/Open-Assistant) - 创建高质量指令跟随数据的项目。(2022)
- [Argilla](https://github.com/argilla-io/argilla) - 用于LLM的开源数据策划平台。(2021)

### LLM数据管理

本节涵盖LLM的综合数据管理方法，包括数据处理、存储和服务。

#### 论文

- [LLM × 数据调查](https://arxiv.org/abs/2505.18458) - 关于大语言模型数据中心方法的综合调查，涵盖数据处理、存储和服务。(2025)
- [修复损害性能的数据：级联LLM重新标记硬负样本以实现鲁棒信息检索](https://arxiv.org/abs/2505.16967) - 识别和重新标记训练数据中假负样本以提高模型性能的方法。(2025)

#### 工具与项目

- [awesome-data-llm](https://github.com/weAIDB/awesome-data-llm) - "LLM × 数据"调查论文的官方仓库，包含精选资源。(2025)
- [CommonCrawl](https://commoncrawl.org/) - 涵盖多种语言和领域的大规模网络爬取数据集。(2008)
- [RedPajama](https://github.com/togethercomputer/RedPajama-Data) - LLaMA训练数据集的开源复现。(2023)
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - 用于语言模型训练的大规模高质量网络数据集。(2024)

### 认知工程与测试时扩展

本节专注于通过增强推理和思维过程来改善数据质量的认知工程和测试时扩展方法。

#### 综述

- [生成式AI第二幕：测试时扩展驱动认知工程](https://arxiv.org/abs/2504.13828) - 通过测试时扩展和强化学习进行认知工程的综合调查。(2025)
- [解锁语言模型的深度思维：通过推理时扩展和强化学习的认知工程](https://gair-nlp.github.io/cognition-engineering/) - 通过测试时扩展范式开发AI思维能力的框架。(2025)

#### 数据工程2.0

- [O1之旅--第一部分](https://github.com/GAIR-NLP/O1-Journey) - 具有长链式思维的数学推理数据集。(2024)
- [Marco-o1](https://github.com/AIDC-AI/Marco-o1) - 从Qwen2-7B-Instruct合成的推理数据集。(2024)
- [STILL-2](https://github.com/RUCAIBox/Slow_Thinking_with_LLMs) - 数学、代码、科学和谜题领域的长形式思维数据。(2024)
- [OpenThoughts-114k](https://github.com/open-thoughts/open-thoughts) - 从DeepSeek R1提取的大规模推理轨迹数据集。(2024)

#### 训练数据质量

- [高影响样本选择](https://arxiv.org/abs/2502.11886) - 基于学习影响测量优先选择训练样本的方法。(2025)
- [噪声减少过滤](https://arxiv.org/abs/2502.03373) - 去除噪声网络提取数据以改善泛化的技术。(2025)
- [长度自适应训练](https://arxiv.org/abs/2504.05118) - 处理训练数据中可变长度序列的方法。(2024)

## 多模态数据

本节涵盖多模态数据的数据质量，包括图像-文本对、视频和音频。

### 论文

- [LAION-5B：训练下一代图像-文本模型的开放大规模数据集](https://arxiv.org/abs/2210.08402) - 大规模图像-文本对数据集。(2022)
- [DataComp：寻找下一代多模态数据集](https://arxiv.org/abs/2304.14108) - 评估数据策划策略的基准。(2023)

### 工具与项目

- [CLIP-Benchmark](https://github.com/LAION-AI/CLIP-Benchmark) - 评估CLIP模型的基准。(2021)
- [img2dataset](https://github.com/rom1504/img2dataset) - 高效下载和处理图像-文本数据集的工具。(2021)

## 表格数据

本节涵盖表格数据的数据质量。

### 论文

- [动态数据摄取的自动化数据质量验证](https://ieeexplore.ieee.org/document/8731379) - 自动化数据质量验证的框架。(2019)
- [实践中机器学习的数据质量调查](https://arxiv.org/abs/2103.05251) - 机器学习中数据质量问题的调查。(2021)

### 工具与项目

- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - 从pandas DataFrame生成概要报告的工具。(2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - 用于数据分析和数据质量验证的Python库。(2021)
- [Spreadsheet Data Quality Audit - Fictional Sample](https://github.com/ja9740913/spreadsheet-data-quality-audit-sample) - 一个固定的虚构 XLSX 输入，附有脱敏的 Excel、Markdown 和 JSON 审计输出；仅为样本，不含审计引擎。(2026)

## 时间序列数据

本节涵盖时间序列数据的数据质量。

### 论文

- [清洗时间序列数据：现状、挑战和机遇](https://arxiv.org/abs/2201.05562) - 清洗时间序列数据的调查。(2022)
- [深度学习的时间序列数据增强：调查](https://arxiv.org/abs/2002.12478) - 时间序列数据增强的调查。(2020)

### 工具与项目

- [Darts](https://github.com/unit8co/darts) - 用于时间序列预测和异常检测的Python库。(2020)
- [tslearn](https://github.com/tslearn-team/tslearn) - 专门用于时间序列数据的机器学习工具包。(2017)

## 图数据

本节涵盖图数据的数据质量。

### 论文

- [图数据噪声和错误的图清洗方法调查](https://arxiv.org/abs/2201.00443) - 图清洗方法的调查。(2022)
- [图数据质量：数据库视角的调查](https://arxiv.org/abs/2201.05236) - 从数据库角度对图数据质量的调查。(2022)

### 工具与项目

- [DGL](https://github.com/dmlc/dgl) - 用于图深度学习的Python包。(2018)
- [NetworkX](https://github.com/networkx/networkx) - 用于创建、操作和研究复杂网络的Python包。(2008)

## 以数据为中心的AI

本节专注于机器学习模型的数据质量管理，遵循以数据为中心的AI范式。包括与数据估值、数据选择和评估ML管道中数据质量的基准相关的论文和资源。

### 综述

- [机器学习数据质量维度和工具调查](https://arxiv.org/pdf/2406.19614) - 全面调查ML应用中的17种数据质量工具。[GitHub资源](https://github.com/haihua0913/awesome-dq4ml)。(2024)
- [数据质量意识：从传统数据管理到数据科学系统的旅程](https://arxiv.org/pdf/2411.03007) - 跨传统数据管理和现代数据科学系统的数据质量意识综合调查。(2024)
- [语言模型数据选择调查](https://arxiv.org/pdf/2402.16827.pdf) - 专注于语言模型数据选择技术的调查。(2024)
- [创建可信AI数据的进展、挑战和机遇](https://www.nature.com/articles/s42256-022-00516-1) - Nature Machine Intelligence论文，讨论为AI创建高质量数据的挑战和机遇。(2022)
- [以数据为中心的人工智能：调查](https://arxiv.org/pdf/2303.10158.pdf) - 以数据为中心的AI方法的综合调查。(2023)
- [大语言模型的数据管理：调查](https://arxiv.org/pdf/2312.01700.pdf) - 大语言模型数据管理技术的调查。(2023)
- [训练数据影响分析和估计：调查](https://arxiv.org/pdf/2212.04612.pdf) - 分析和估计训练数据对模型性能影响的方法调查。(2022)
- [机器学习的数据管理：调查](https://luoyuyu.vip/files/DM4ML%5FSurvey.pdf) - TKDE关于机器学习数据管理技术的调查。(2022)
- [机器学习中的数据估值："成分"、策略和开放挑战](https://www.ijcai.org/proceedings/2022/0782.pdf) - IJCAI关于机器学习中数据估值方法的论文。(2022)
- [基于解释的NLP模型人工调试：调查](https://aclanthology.org/2021.tacl-1.90.pdf) - TACL关于基于解释的NLP模型调试的调查。(2021)

### 数据估值

- [数据Shapley：机器学习数据的公平估值](https://proceedings.mlr.press/v97/ghorbani19c/ghorbani19c.pdf) - ICML论文，介绍用于评估训练数据的数据Shapley方法。(2019)
- [最近邻算法的高效任务特定数据估值](https://vldb.org/pvldb/vol12/p1610-jia.pdf) - VLDB关于最近邻算法高效数据估值的论文。(2019)
- [基于Shapley值的高效数据估值](https://proceedings.mlr.press/v89/jia19a/jia19a.pdf) - AISTATS关于使用Shapley值进行高效数据估值的论文。(2019)
- [通过影响函数理解黑盒预测](https://arxiv.org/pdf/1703.04730.pdf) - ICML论文，介绍用于理解模型预测的影响函数。(2017)
- [SGD训练模型的数据清洗](https://proceedings.neurips.cc/paper%5Ffiles/paper/2019/file/5f14615696649541a025d3d0f8e0447f-Paper.pdf) - NeurIPS关于SGD训练模型数据清洗的论文。(2019)

### 数据选择

- [MIRA: Mid-training Rubric Anchoring for Source-Aware Data Selection](https://arxiv.org/abs/2605.30288) - 为不同数据来源发现评估准则，并将判断蒸馏为可扩展的评分器，用于代码导向的大语言模型中期训练数据筛选。(2026)
- [Modyn：以数据为中心的机器学习管道编排](https://arxiv.org/pdf/2312.06254) - SIGMOD关于以数据为中心的机器学习管道编排的论文。(2023)
- [通过最优控制进行语言模型数据选择](https://openreview.net/pdf?id=dhAL5fy8wS) - ICLR关于语言模型数据选择最优控制方法的论文。(2024)
- [具有自适应批次选择的ADAM优化](https://openreview.net/pdf?id=BZrSCv2SBq) - ICLR关于ADAM优化自适应批次选择的论文。(2024)
- [自适应数据优化：使用缩放定律的动态样本选择](https://openreview.net/pdf?id=aqok1UX7Z1) - ICLR关于使用缩放定律进行动态样本选择的论文。(2024)
- [通过代理选择：深度学习的高效数据选择](https://openreview.net/pdf?id=HJg2b0VYDr) - ICLR关于使用代理模型进行高效数据选择的论文。(2020)

### 基准测试

- [DataPerf：以数据为中心的AI开发基准](https://openreview.net/pdf?id=LaFKTgrZMG) - NeurIPS论文，介绍以数据为中心的AI开发基准。(2023)
- [OpenDataVal：统一的数据估值基准](https://openreview.net/pdf?id=eEK99egXeB) - NeurIPS关于统一数据估值基准的论文。(2023)
- [通过图像字幕改善多模态数据集](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/45e604a3e33d10fba508e755faa72345-Paper-Datasets%5Fand%5FBenchmarks.pdf) - NeurIPS关于通过图像字幕改善多模态数据集的论文。(2023)
- [大语言模型作为归因训练数据生成器：多样性和偏见的故事](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/ae9500c4f5607caf2eff033c67daa9d7-Paper-Datasets%5Fand%5FBenchmarks.pdf) - NeurIPS关于使用LLM作为训练数据生成器的论文。(2023)
- [dcbench：以数据为中心的AI系统基准](https://dl.acm.org/doi/pdf/10.1145/3533028.3533310) - DEEM论文，介绍以数据为中心的AI系统基准。(2022)

## 贡献指南

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。 
