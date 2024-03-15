---
title: "Moonshot"
date: 2024-03-15T10:55:53+08:00
lastmod: 2024-03-15T10:55:53+08:00
author: ["Winter"]
keywords: 
categories: # 没有分类界面可以不填写
tags: ["AI"]# 标签
description: ""
weight:
slug: ""
draft: false # 是否为草稿
comments: true # 本页面是否显示评论
reward: true # 打赏
mermaid: true #是否开启mermaid
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示路径
cover:
    image: "" #图片路径例如：posts/tech/123/123.png
    zoom: # 图片大小，例如填写 50% 表示原图像的一半大小
    caption: "" #图片底部描述
    alt: ""
    relative: false
---
## 月之暗面（Moonshot AI）
看到许多地方有人在讨论这家国内的AI公司，起初被公司的名字吸引，然后看大家对其产品的使用评价都很不错，自己试用下来在确实在一些场景下可以胜过chatgpt。最近刚融资10亿美金，看了对创始人-杨植麟（90后）的专访，以及强大的技术团队，浅薄的觉得是国内未来可期的一家公司。废话不多说，上干货。

### 产品&技术
1. kimi chat：

    面向c端的智能助手 https://www.moonshot.cn/
    - 免费，不需特定网络环境
    - web/app/微信小程序
    - 20万汉字的长文本输入，主打无损记忆功能
    - 可联网搜索，减少幻觉
    - 支持最多上传50个文件，每个100M以内（支持pdf/doc/xlsx/ppt/txt/image）
  

    特色：因为支持长文本，所以它的文件总结能力确实很强。这一特性使得Kimi智能助手在处理复杂对话和长篇幅内容时表现出色，为用户提供了更加流畅和连贯的交互体验。这也应了杨植麟反复强调的-lossless long context is everythis.

2. 多模态模型研发

    月之暗面正在秘密研发通用多模态模型，预计将在不久的将来推出。这种模型将能够处理包括文本、图像和视频在内的多种数据类型，进一步提升AI的理解和生成能力。

### 摘自专访
> 如果你有 10 亿的 context length，今天看到的问题都不是问题。


> 做“长”是因为杨植麟判断 AI-Native 产品的终极价值是提供个性化的交互，而 lossless long-context 是实现这一点的基础 —— 模型的微调长期不应该存在，用户跟模型的交互历史就是最好的个性化过程，历史上每一代技术都是在提升 context length。

> 像 ChatGPT 这样的产品，还没有完全建立起基于用户数据的持续进化。我觉得这很大程度上是 base model 还在进化，进化了一代，之前的用户数据就没什么用了。这跟发展阶段有关系 —— 现在“吃”的是 base model 的 scaling law，未来可能会去“吃”用户这个数据源的 scaling law。

        










