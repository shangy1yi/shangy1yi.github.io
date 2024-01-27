---
abbrlink: ''
banner: null
categories:
- - 科技&产品
cover: https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.3kleey4o3yg0.webp
date: '2024-01-27T17:33:33.906053+08:00'
description: null
poster:
  caption: null
  color: null
  headline: null
  topic: null
tags:
- openai
- gpt
- chatgpt
- ai
title: OpenAI 一口气宣布了 5 个新模型
updated: 2024-1-27T17:38:30.449+8:0
---
**OpenAI 今天一口气宣布了 5 个新模型，包括两个文本嵌入模型、升级的 GPT-4 Turbo 预览版和 GPT-3.5 Turbo、一个审核模型。**

![](https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.3kleey4o3yg0.webp)

## 更新 GPT-4 Turbo 预览模型

OpenAI 根据开发者对早期预览版的反馈，发布了 gpt-4-0125-preview 预览模型，重点修复了模型的“变懒”情况，能更彻底地完成代码生成等任务。

新预览版还改善了对非英语生成问题的支持，引入“gpt-4-turbo-preview”模型别名，可自动指向最新的预览版。

OpenAI 还计划在未来几个月内全面推出带有视觉功能的 GPT-4 Turbo。

## 定价更低的新嵌入模型

OpenAI 还引入了两种新的嵌入模式，一种是体积更小、效率更高的 text-embedding-3-small 模型，另一种是体积更大、功能更强的 text-embedding-3-large 模型。

嵌入（embedding）是表示自然语言或代码等内容中概念的数字序列。机器学习模型和其他算法通过嵌入，可以更容易理解内容之间的关联，也更容易执行聚类或检索等任务。

![](https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.2fv2oikwngcg.webp)

ChatGPT 和 Assistants API 中的知识检索等应用，以及许多检索增强生成（RAG）开发工具都使用到了嵌入这个概念。

### text-embedding-3-small

相比较 2022 年 12 月发布的 text-embedding-ada-002 模型，text-embedding-3-small 性能和效率大幅提升。

性能方面，text-embedding-3-small 在多语言检索常用基准（MIRACL）的平均得分从 31.4% 提高到 44.0%，而英语任务常用基准（MTEB）的平均得分从 61.0% 提高到 62.3%。

![](https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.7jant594meo0.webp)

![](https://cdn.jsdelivr.net/gh/shangy1yi/picx-images-hosting@master/image.3uq7jl5pkva0.webp)

定价方面，text-embedding-3-small 的定价是 text-embedding-ada-002 的五分之一，从每 1k token 0.0001 美元降至 0.00002 美元。

### text-embedding-3-large

text-embedding-3-large 是 OpenAI 新推出的性能最佳的模型。将 text-embedding-ada-002 与 text-embedding-3-large 进行比较：在 MIRACL 上，平均得分从 31.4% 提高到 54.9%，而在 MTEB 上，平均得分从 61.0% 提高到 64.6%。

text-embedding-3-large 的价格为每 1k token 售价 0.00013 美元。

## 原生支持 shortening

允许开发人员以降低存储和计算需求来换取一定的准确性。简单地说，保持主旨不变的情况下，shortening 就像从一个复杂的标签中去掉一些不那么重要的细节。

## GPT-3.5 Turbo

在 API 领域，GPT-3.5 Turbo 同样表现不俗。在执行各类任务时，它不仅能够提供比 GPT-4 更低的成本，还能保证更快的执行速度。

因此，对于那些付费用户来说，此次输入价格下调 50%、输出价格下调 25% 无疑是一大利好。

具体来说，新的输入价格定格在每 1k token 价格为 0.0005 美元，而输出价格则为每 1k token 价格为 0.0015 美元。


[原文地址](https://openai.com/blog/new-embedding-models-and-api-updates)，感兴趣可以深入阅读
