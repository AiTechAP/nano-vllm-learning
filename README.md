# 《Nano-vLLM 源码解读：从零构建高性能 LLM 推理引擎》

> 本课程以 [Nano-vLLM](https://github.com/GeeeekExplorer/nano-vllm) v0.2.0 源代码为基础，通过`原理阐释 + 源码解读`双线并行的方式，从零开始、系统讲解 LLM 推理引擎核心技术的实现细节。

## 一、课程信息

| 课程信息 | 内容 |
|------|------|
| 课程名称 | 《Nano-vLLM 源码解读：从零构建高性能 LLM 推理引擎》 |
| 课程地址 | https://github.com/AiTechAP/nano-vllm-learning |
| 在线阅读 | https://aitechap.github.io/nano-vllm-learning |
| 课程视频 | https://space.bilibili.com/509304290 |

## 二、课程简介

[vLLM](https://github.com/vllm-project/vllm) 是目前工业界极具代表性的一款 LLM 推理引擎，但是其源码体量庞大、内部实现复杂度高，对初学者而言存在不小的入门门槛，容易让人望而却步。

`Nano-vLLM` 是由 Xingkai Yu 开发的一个轻量级、高性能 LLM 推理引擎实现。Nano-vLLM 剥离了 vLLM 大量冗余的工程代码，以极简的代码还原大模型推理引擎的核心原理与关键机制，具备极强的可读性，是学习 LLM 推理引擎原理与实践的极佳切入点。

## 三、课程目标

完成本课程后，你将能够：

1. 理解 KV Cache、PagedAttention、连续批处理等大模型推理核心机制。
2. 读懂 Nano-vLLM 各核心模块，掌握大模型推理的完整执行链路。
3. 具备研读工业级推理引擎 vLLM 源码的基础能力。

## 四、前置要求

- 零基础友好：课程从零开始讲解 LLM 推理的基本概念和核心技术。
- 前置知识：Python 编程基础、PyTorch 基础操作、Transformer 基本结构等等。

## 参考资料

- Nano-vLLM 源码：https://github.com/GeeeekExplorer/nano-vllm

## 关注我们
<div align=center>
    <p>欢迎关注公众号：AI技术应用实践</p>
    <img src="https://raw.githubusercontent.com/AiTechAP/AiTechAP.github.io/refs/heads/main/images/AiTechAP-qrcode.png" height="300">
</div>

---
*本课程基于 Nano-vLLM v0.2.0 源码编写，课程配套课件、教学视频持续更新中。*