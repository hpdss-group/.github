<div align="center">

# CAS-ICT HPDSS Group

**High-Performance Data Systems and Software**  
**高性能数据系统与基础软件课题组**

[English](#english) · [中文](#中文) · [OpenSDC](https://github.com/opensdc-org)

</div>

---

## English

We are the High-Performance Data Systems and Software (HPDSS) Group at the Institute of Computing Technology, Chinese Academy of Sciences (CAS-ICT). We build software to reduce the cost of moving data in large-scale machine learning systems. Our current projects focus on compressing collective communication in distributed training and moving KV caches more efficiently in LLM serving.

### Communication Compression for Distributed Training

| Project | Role | Description |
| --- | --- | --- |
| [**COCCL**](https://github.com/hpdss-group/COCCL) | Communication library | A collective communication library that combines compression and precision control to reduce data movement during distributed training. |
| [**CC-Bench**](https://github.com/hpdss-group/CC-Bench) | Benchmark | A benchmark suite for evaluating compression in collective communication across HPC and AI workloads. |

### KV Cache Compression for LLM Serving

| Project | Role | Description |
| --- | --- | --- |
| [**KVServe**](https://github.com/hpdss-group/KVServe) | Serving framework | A service-aware KV cache compression framework that reduces transfer bandwidth requirements between prefill and decode workers in disaggregated LLM serving. |
| [**KVCompBench**](https://github.com/hpdss-group/KVCompBench) | Benchmark | A benchmark suite for evaluating and comparing KV cache compression methods. |

### Scientific Data Compression

Our scientific data compression software is available through [**OpenSDC**](https://github.com/opensdc-org), an open community for scientific data compression.

[**OpenSDC website**](https://opensdc-org.github.io/) · [Benchmark and leaderboard](https://opensdc-org.github.io/benchmark/) · [Research survey](https://opensdc-org.github.io/survey/)

---

## 中文

我们是中国科学院计算技术研究所高性能数据系统与基础软件课题组（HPDSS），主要研发降低大规模机器学习系统数据传输开销的基础软件。目前聚焦两个方向：分布式训练中的集合通信压缩，以及大模型推理服务中的 KV 缓存压缩。

### 分布式训练通信压缩

| 项目 | 类型 | 简介 |
| --- | --- | --- |
| [**COCCL**](https://github.com/hpdss-group/COCCL) | 通信库 | 将压缩与精度控制融入集合通信，减少分布式训练中的数据传输量。 |
| [**CC-Bench**](https://github.com/hpdss-group/CC-Bench) | 基准评测 | 面向高性能计算和 AI 工作负载，评估在集合通信中使用压缩的效果。 |

### 大模型推理 KV 缓存压缩

| 项目 | 类型 | 简介 |
| --- | --- | --- |
| [**KVServe**](https://github.com/hpdss-group/KVServe) | 推理系统框架 | 面向预填充与解码分离的大模型推理服务，按服务需求压缩 KV 缓存，降低两阶段之间的数据传输带宽需求。 |
| [**KVCompBench**](https://github.com/hpdss-group/KVCompBench) | 基准评测 | 用于评测和比较 KV 缓存压缩方法。 |

### 科学数据压缩

课题组的科学数据压缩软件可在 [**OpenSDC 开放科学数据压缩社区**](https://github.com/opensdc-org) 获取。

[**OpenSDC 官网**](https://opensdc-org.github.io/) · [评测与榜单](https://opensdc-org.github.io/benchmark/) · [研究综述](https://opensdc-org.github.io/survey/)
