# Awesome Data Quality [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Resources, tools, papers, and projects for ensuring data reliability and effectiveness across traditional data, LLM pretraining/fine-tuning data, multimodal data, and more.

## Contents

- [Introduction](#introduction)
- [Traditional Data](#traditional-data)
  - [Papers](#papers)
  - [Tools & Projects](#tools--projects)
  - [Data Readiness Assessment](#data-readiness-assessment)
- [Large Language Model Data](#large-language-model-data)
  - [Pretraining Data](#pretraining-data)
  - [Fine-tuning Data](#fine-tuning-data)
  - [LLM Data Management](#llm-data-management)
  - [Cognition Engineering & Test-Time Scaling](#cognition-engineering--test-time-scaling)
- [Multimodal Data](#multimodal-data)
  - [Papers](#papers-1)
  - [Tools & Projects](#tools--projects-1)
- [Tabular Data](#tabular-data)
  - [Papers](#papers-2)
  - [Tools & Projects](#tools--projects-2)
- [Time Series Data](#time-series-data)
  - [Papers](#papers-3)
  - [Tools & Projects](#tools--projects-3)
- [Graph Data](#graph-data)
  - [Papers](#papers-4)
  - [Tools & Projects](#tools--projects-4)
- [Data-Centric AI](#data-centric-ai)
  - [Surveys](#surveys)
  - [Data Valuation](#data-valuation)
  - [Data Selection](#data-selection)
  - [Benchmarks](#benchmarks)

## Introduction

Data quality is a critical aspect of any data-driven application or research. This repository collects resources related to data quality across different data types, including traditional data, large language model data (both pretraining and fine-tuning), multimodal data, and more.

## Traditional Data

This section covers data quality for traditional structured and unstructured data.

### Papers

- [Data Cleaning: Problems and Current Approaches](https://www.researchgate.net/publication/220423285_Data_Cleaning_Problems_and_Current_Approaches) - A comprehensive overview of data cleaning approaches. (2000)
- [A Survey on Data Quality: Classifying Poor Data](https://ieeexplore.ieee.org/document/7423672) - A survey on data quality issues and classification. (2016)

### Tools & Projects

- [Great Expectations](https://github.com/great-expectations/great_expectations) - A Python framework for validating, documenting, and profiling data. (2018)
- [Deequ](https://github.com/awslabs/deequ) - A library built on top of Apache Spark for defining "unit tests for data". (2018)
- [OpenRefine](https://openrefine.org/) - A powerful tool for working with messy data, cleaning it, and transforming it. (2010)
- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - Generates profile reports from pandas DataFrames. (2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - A Python library for automated data profiling. (2021)
- [PyDeequ](https://github.com/awslabs/python-deequ) - Python API for Deequ, enabling "unit tests for data". (2020)
- [Evidently](https://github.com/evidentlyai/evidently) - An open-source ML monitoring framework for data drift detection. (2021)
- [TensorFlow Data Validation (TFDV)](https://www.tensorflow.org/tfx/data_validation/get_started) - A library for exploring and validating ML data at scale. (2018)
- [Deepchecks](https://github.com/deepchecks/deepchecks) - A Python package for validating ML models and data. (2021)
- [Provero](https://github.com/provero-org/provero) - A vendor-neutral, declarative data quality engine. Define checks in YAML and run anywhere. (2026)
- [DataScreenIQ](https://datascreeniq.com) - A hosted real-time data quality screening API that returns PASS / WARN / BLOCK verdicts at the ingest boundary before data enters pipelines or warehouses. Detects schema drift, null spikes, and type mismatches in milliseconds. (2026)

### Data Readiness Assessment

This subsection covers methods and tools for assessing data readiness for AI applications.

#### Papers

- [Data Readiness for AI: A 360-Degree Survey](https://arxiv.org/abs/2404.05779) - A comprehensive survey examining metrics for evaluating data readiness for AI training across structured and unstructured datasets. (2024)
- [Assessing Student Adoption of Generative Artificial Intelligence across Engineering Education](https://arxiv.org/abs/2503.04696) - An empirical study on data quality considerations in educational AI applications. (2025)

#### Tools & Projects

- [Data Readiness Assessment Framework](https://github.com/data-readiness/framework) - A framework for evaluating data quality and readiness for AI applications. (2024)
- [AI Data Quality Metrics](https://github.com/ai-data-quality/metrics) - Standardized metrics for assessing data quality in AI contexts. (2024)

## Large Language Model Data

### Pretraining Data

This section covers data quality for large language model pretraining data.

#### Papers

- [The Pile: An 800GB Dataset of Diverse Text for Language Modeling](https://arxiv.org/abs/2101.00027) - A large-scale curated dataset for language model pretraining. (2021)
- [Quality at a Glance: An Audit of Web-Crawled Multilingual Datasets](https://arxiv.org/abs/2103.12028) - An audit of the quality of web-crawled multilingual datasets. (2021)
- [Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus](https://arxiv.org/abs/2104.08758) - Documentation of the C4 dataset. (2021)
- [Recycling the Web: A Method to Enhance Pre-training Data Quality and Quantity for Language Models](https://arxiv.org/abs/2506.04689) - REWire method for recycling and improving low-quality web documents through guided rewriting, addressing the "data wall" problem in LLM pretraining. (2025)
- [Assessing the Role of Data Quality in Training Bilingual Language Models](https://arxiv.org/abs/2506.12966) - A study revealing that unequal data quality is a major driver of performance degradation in bilingual settings, with a practical data filtering strategy for multilingual models. (2025)

#### Tools & Projects

- [Dolma](https://github.com/allenai/dolma) - A framework for curating and documenting large language model pretraining data. (2023)
- [Text Data Cleaner](https://github.com/ChenghaoMou/text-data-cleaner) - A tool for cleaning text data for language model pretraining. (2022)
- [CCNet](https://github.com/facebookresearch/cc_net) - Tools for downloading and filtering CommonCrawl data. (2020)
- [Dingo](https://github.com/MigoXLab/dingo) - A comprehensive AI data quality evaluation tool supporting multiple data sources, types, and modalities. (2024)

### Fine-tuning Data

This section covers data quality for large language model fine-tuning data.

#### Papers

- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) - The RLHF paper from Anthropic. (2022)
- [Quality Not Quantity: On the Interaction between Dataset Design and Robustness of CLIP](https://arxiv.org/abs/2112.07295) - A study on the importance of data quality over quantity. (2021)
- [Data Quality for Machine Learning Tasks](https://arxiv.org/abs/2108.02711) - A survey on data quality for machine learning. (2021)

#### Tools & Projects

- [LMSYS Chatbot Arena](https://github.com/lm-sys/FastChat) - A platform for evaluating LLM responses. (2023)
- [OpenAssistant](https://github.com/LAION-AI/Open-Assistant) - A project to create high-quality instruction-following data. (2022)
- [Argilla](https://github.com/argilla-io/argilla) - An open-source data curation platform for LLMs. (2021)

### LLM Data Management

This section covers comprehensive data management approaches for LLMs, including data processing, storage, and serving.

#### Papers

- [A Survey of LLM × DATA](https://arxiv.org/abs/2505.18458) - A comprehensive survey on data-centric methods for large language models covering data processing, storage, and serving. (2025)
- [Fixing Data That Hurts Performance: Cascading LLMs to Relabel Hard Negatives for Robust Information Retrieval](https://arxiv.org/abs/2505.16967) - A method for identifying and relabeling false negatives in training data to improve model performance. (2025)

#### Tools & Projects

- [awesome-data-llm](https://github.com/weAIDB/awesome-data-llm) - Official repository of "LLM × DATA" survey paper with curated resources. (2025)
- [CommonCrawl](https://commoncrawl.org/) - A massive web crawl dataset covering diverse languages and domains. (2008)
- [RedPajama](https://github.com/togethercomputer/RedPajama-Data) - An open-source reproduction of the LLaMA training dataset. (2023)
- [FineWeb](https://huggingface.co/datasets/HuggingFaceFW/fineweb) - A large-scale, high-quality web dataset for language model training. (2024)
- [Dokime](https://github.com/dokime-ai/dokime) - An open-source CLI toolkit for scoring, filtering, deduplicating, and diagnosing ML training data quality. (2026)

### Cognition Engineering & Test-Time Scaling

This section focuses on cognition engineering and test-time scaling methods that improve data quality through enhanced reasoning and thinking processes.

#### Surveys

- [Generative AI Act II: Test Time Scaling Drives Cognition Engineering](https://arxiv.org/abs/2504.13828) - A comprehensive survey on cognition engineering through test-time scaling and reinforcement learning. (2025)
- [Unlocking Deep Thinking in Language Models: Cognition Engineering through Inference Time Scaling and Reinforcement Learning](https://gair-nlp.github.io/cognition-engineering/) - A framework for developing AI thinking capabilities through test-time scaling paradigms. (2025)

#### Data Engineering 2.0

- [O1 Journey--Part 1](https://github.com/GAIR-NLP/O1-Journey) - A dataset for math reasoning with long chain-of-thought. (2024)
- [Marco-o1](https://github.com/AIDC-AI/Marco-o1) - Reasoning dataset synthesized from Qwen2-7B-Instruct. (2024)
- [STILL-2](https://github.com/RUCAIBox/Slow_Thinking_with_LLMs) - Long-form thought data for math, code, science, and puzzle domains. (2024)
- [OpenThoughts-114k](https://github.com/open-thoughts/open-thoughts) - Large-scale dataset of reasoning trajectories distilled from DeepSeek R1. (2024)

#### Training Data Quality

- [High-impact Sample Selection](https://arxiv.org/abs/2502.11886) - Methods for prioritizing training samples based on learning impact measurement. (2025)
- [Noise Reduction Filtering](https://arxiv.org/abs/2502.03373) - Techniques for removing noisy web-extracted data to improve generalization. (2025)
- [Length-Adaptive Training](https://arxiv.org/abs/2504.05118) - Approaches for handling variable-length sequences in training data. (2024)

## Multimodal Data

This section covers data quality for multimodal data, including image-text pairs, video, and audio.

### Papers

- [LAION-5B: An open large-scale dataset for training next generation image-text models](https://arxiv.org/abs/2210.08402) - A large-scale dataset of image-text pairs. (2022)
- [DataComp: In search of the next generation of multimodal datasets](https://arxiv.org/abs/2304.14108) - A benchmark for evaluating data curation strategies. (2023)

### Tools & Projects

- [CLIP-Benchmark](https://github.com/LAION-AI/CLIP-Benchmark) - A benchmark for evaluating CLIP models. (2021)
- [img2dataset](https://github.com/rom1504/img2dataset) - A tool for efficiently downloading and processing image-text datasets. (2021)

## Tabular Data

This section covers data quality for tabular data.

### Papers

- [Automating Data Quality Validation for Dynamic Data Ingestion](https://ieeexplore.ieee.org/document/8731379) - A framework for automating data quality validation. (2019)
- [A Survey on Data Quality for Machine Learning in Practice](https://arxiv.org/abs/2103.05251) - A survey on data quality issues in machine learning. (2021)

### Tools & Projects

- [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling) - A tool for generating profile reports from pandas DataFrames. (2016)
- [DataProfiler](https://github.com/capitalone/DataProfiler) - A Python library for data profiling and data quality validation. (2021)

## Time Series Data

This section covers data quality for time series data.

### Papers

- [Cleaning Time Series Data: Current Status, Challenges, and Opportunities](https://arxiv.org/abs/2201.05562) - A survey on cleaning time series data. (2022)
- [Time Series Data Augmentation for Deep Learning: A Survey](https://arxiv.org/abs/2002.12478) - A survey on time series data augmentation. (2020)

### Tools & Projects

- [Darts](https://github.com/unit8co/darts) - A Python library for time series forecasting and anomaly detection. (2020)
- [tslearn](https://github.com/tslearn-team/tslearn) - A machine learning toolkit dedicated to time series data. (2017)

## Graph Data

This section covers data quality for graph data.

### Papers

- [A Survey on Graph Cleaning Methods for Noise and Errors in Graph Data](https://arxiv.org/abs/2201.00443) - A survey on graph cleaning methods. (2022)
- [Graph Data Quality: A Survey from the Database Perspective](https://arxiv.org/abs/2201.05236) - A survey on graph data quality from a database perspective. (2022)

### Tools & Projects

- [DGL](https://github.com/dmlc/dgl) - A Python package for deep learning on graphs. (2018)
- [NetworkX](https://github.com/networkx/networkx) - A Python package for the creation, manipulation, and study of complex networks. (2008)

## Data-Centric AI

This section focuses on data quality management for machine learning models, following the Data-Centric AI paradigm. It includes papers and resources related to data valuation, data selection, and benchmarks for evaluating data quality in ML pipelines.

### Surveys

- [A Survey on Data Quality Dimensions and Tools for Machine Learning](https://arxiv.org/pdf/2406.19614) - A comprehensive survey reviewing 17 data quality tools for ML applications. [GitHub resource](https://github.com/haihua0913/awesome-dq4ml). (2024)
- [Data Quality Awareness: A Journey from Traditional Data Management to Data Science Systems](https://arxiv.org/pdf/2411.03007) - A comprehensive survey on data quality awareness across traditional data management and modern data science systems. (2024)
- [A Survey on Data Selection for Language Models](https://arxiv.org/pdf/2402.16827.pdf) - A survey focusing on data selection techniques for language models. (2024)
- [Advances, challenges and opportunities in creating data for trustworthy AI](https://www.nature.com/articles/s42256-022-00516-1) - A Nature Machine Intelligence paper discussing the challenges and opportunities in creating high-quality data for AI. (2022)
- [Data-centric Artificial Intelligence: A Survey](https://arxiv.org/pdf/2303.10158.pdf) - A comprehensive survey on data-centric AI approaches. (2023)
- [Data Management For Large Language Models: A Survey](https://arxiv.org/pdf/2312.01700.pdf) - A survey on data management techniques for large language models. (2023)
- [Training Data Influence Analysis and Estimation: A Survey](https://arxiv.org/pdf/2212.04612.pdf) - A survey on methods for analyzing and estimating the influence of training data on model performance. (2022)
- [Data Management for Machine Learning: A Survey](https://luoyuyu.vip/files/DM4ML%5FSurvey.pdf) - A TKDE survey on data management techniques for machine learning. (2022)
- [Data Valuation in Machine Learning: "Ingredients", Strategies, and Open Challenges](https://www.ijcai.org/proceedings/2022/0782.pdf) - An IJCAI paper on data valuation methods in machine learning. (2022)
- [Explanation-Based Human Debugging of NLP Models: A Survey](https://aclanthology.org/2021.tacl-1.90.pdf) - A TACL survey on explanation-based debugging of NLP models. (2021)

### Data Valuation

- [Data Shapley: Equitable Valuation of Data for Machine Learning](https://proceedings.mlr.press/v97/ghorbani19c/ghorbani19c.pdf) - An ICML paper introducing the Data Shapley method for valuing training data. (2019)
- [Efficient task-specific data valuation for nearest neighbor algorithms](https://vldb.org/pvldb/vol12/p1610-jia.pdf) - A VLDB paper on efficient data valuation for nearest neighbor algorithms. (2019)
- [Towards Efficient Data Valuation Based on the Shapley Value](https://proceedings.mlr.press/v89/jia19a/jia19a.pdf) - An AISTATS paper on efficient data valuation using Shapley values. (2019)
- [Understanding Black-box Predictions via Influence Functions](https://arxiv.org/pdf/1703.04730.pdf) - An ICML paper introducing influence functions for understanding model predictions. (2017)
- [Data Cleansing for Models Trained with SGD](https://proceedings.neurips.cc/paper%5Ffiles/paper/2019/file/5f14615696649541a025d3d0f8e0447f-Paper.pdf) - A NeurIPS paper on data cleansing for SGD-trained models. (2019)

### Data Selection

- [Modyn: Data-Centric Machine Learning Pipeline Orchestration](https://arxiv.org/pdf/2312.06254) - A SIGMOD paper on pipeline orchestration for data-centric machine learning. (2023)
- [Data Selection via Optimal Control for Language Models](https://openreview.net/pdf?id=dhAL5fy8wS) - An ICLR paper on optimal control methods for data selection in language models. (2024)
- [ADAM Optimization with Adaptive Batch Selection](https://openreview.net/pdf?id=BZrSCv2SBq) - An ICLR paper on adaptive batch selection for ADAM optimization. (2024)
- [Adaptive Data Optimization: Dynamic Sample Selection with Scaling Laws](https://openreview.net/pdf?id=aqok1UX7Z1) - An ICLR paper on dynamic sample selection using scaling laws. (2024)
- [Selection via proxy: Efficient data selection for deep learning](https://openreview.net/pdf?id=HJg2b0VYDr) - An ICLR paper on efficient data selection using proxy models. (2020)

### Benchmarks

- [DataPerf: Benchmarks for Data-Centric AI Development](https://openreview.net/pdf?id=LaFKTgrZMG) - A NeurIPS paper introducing benchmarks for data-centric AI development. (2023)
- [OpenDataVal: a Unified Benchmark for Data Valuation](https://openreview.net/pdf?id=eEK99egXeB) - A NeurIPS paper on a unified benchmark for data valuation. (2023)
- [Improving multimodal datasets with image captioning](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/45e604a3e33d10fba508e755faa72345-Paper-Datasets%5Fand%5FBenchmarks.pdf) - A NeurIPS paper on improving multimodal datasets with image captioning. (2023)
- [Large Language Model as Attributed Training Data Generator: A Tale of Diversity and Bias](https://proceedings.neurips.cc/paper%5Ffiles/paper/2023/file/ae9500c4f5607caf2eff033c67daa9d7-Paper-Datasets%5Fand%5FBenchmarks.pdf) - A NeurIPS paper on using LLMs as training data generators. (2023)
- [dcbench: A Benchmark for Data-Centric AI Systems](https://dl.acm.org/doi/pdf/10.1145/3533028.3533310) - A DEEM paper introducing a benchmark for data-centric AI systems. (2022)


