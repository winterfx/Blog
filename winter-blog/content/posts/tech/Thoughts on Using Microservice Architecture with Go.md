---
title: "Thoughts on Using Microservice Architecture With Go"
date: 2024-01-08T17:37:12+08:00
lastmod: 2024-01-08T17:37:12+08:00
author: ["Winter"]
keywords: 
categories: # 没有分类界面可以不填写
tags: ["Microservice","Architecture"]
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
## Backgroud
平时工作只使用的是go作为后端语言，微服务作为系统架构，部署到azure aks，在写过几个工程之后，对架构有了一些体会，遂记录下来，也许有些错误或不足，以后发现再改正。首先有个区别就是，项目和工程。
项目可以是自己写的小工具或者具体功能的代码，用go写的话，其实项目结构没有那么重要，哪怕平铺下来问题也不大。但是如果是写一个工程，代码量大，逻辑多，分工协作，建议还是要有一定的结构规范。
## Architecture
我认为一个工程从high level上来看，其实就是分为三个有明确调用关系的大部分。
- entry-layer
- sevice-layer
- depency-layer
## Project Struct

## One Repo

## CI/CD





