---
weight: 1
title: "我的博客又双叒叕上线啦！"
date: 2025-04-28T09:37:00+08:00
lastmod: 2025-04-28T12:57:00+08:00
draft: false
author: "宗山"
authorLink: "https://blog.kebensun.com"
description: "十年程序人生之瞎折腾的博客"
images: []
resources:
- name: ""
  src: ""


tags: ["Hugo","Vercel","GitHub","静态博客"]
categories: ["博客搭建"]

lightgallery: true

toc:
  auto: false
---

十年程序人生 之 瞎折腾的博客。

<!--more-->

> 15年开始实习，到今年，算下来已经在程序猿这条路上走了整整10年。对博客的执念也一直未曾放下，这篇文章就来记录一下我一路折腾的历程。

---

### 自开发 + 云服务器
**关键词：开端**  
**花费：域名 + 学生优惠服务器 + 备案**

刚入行时，为了提升编程水平，我自己找了一些课程学习。偶然看到一个Python系列课程，内容是手把手教你实现一个简单的博客系统。  
跟着视频一行行敲代码，最终买了台云服务器部署上线，又入手了域名并完成备案。  
**退坑原因：** 用着用着发现问题不断，毕竟只是个教学demo，功能简单且不稳定，最终弃坑。

---

### WordPress + 云服务器
**关键词：入门**  
**花费：无**

提到博客，WordPress几乎是无法绕开的选择：开源、自部署、对新手友好。虽然很多人后来因为各种原因放弃了它，但入门阶段，基本都试过。  
我在原有服务器上部署了WordPress，体验还算不错。  
**退坑原因：** 学生优惠服务器到期了，当时又没别的需求，便直接停掉了。

---

### Hexo + GitHub Pages
**关键词：白嫖**  
**花费：无**

GitHub Pages大概也是每个技术人必经的白嫖之路——创建一个公共仓库，就能免费拥有一个7×24小时在线的静态站点，香得一塌糊涂。  
搭配Hexo快速生成静态博客，体验感满满。  
**退坑原因：** GitHub Pages在国内访问实在不稳定，公司能打开，回家却打不开。再加上Hexo的配置流程偏繁琐，每换一台设备都得重配一遍，强迫症发作，遂弃坑。

---

### Notion + GitHub + NotionNext + Vercel
**关键词：瞎折腾**  
**花费：无**

不想继续用GitHub Pages后，我开始寻找替代方案。那时正频繁使用Notion笔记，便萌生了直接用Notion生成博客的想法。  
一番搜索后找到了 [NotionNext](https://github.com/tangly1024/NotionNext)。跟着文档clone模板，结合GitHub和Vercel，快速搭建了新站点。Notion写作体验极佳，Vercel绑定国内DNS后访问速度也不错，整体体验很顺滑。  
**退坑原因：** NotionNext仍在快速迭代中，经常会出现小bug，需要频繁更新，而每次更新都容易遇到文件冲突，处理起来很麻烦，不够优雅，于是弃坑。

---

### Hugo + GitHub + Vercel
**关键词：暂时性的终点**  
**花费：无**

Hugo是另一个流行的静态博客生成器。相比Hexo，它构建速度更快（虽然对我这博客量来说也没差多少😅），安装配置也更简单，几乎一键起飞。  
加上Vercel对Hugo的良好支持，部署体验非常顺手，目前就是我在用的方案。  
**退坑原因：** 暂无。

---

### 后记
一路折腾，博客搭了一版又一版，但真正输出的内容少得可怜。每次更换方案，总要重新整理一遍旧内容，结果一删再删，留下来的文章寥寥无几 😂。  
于是给自己立个小目标：

**在输出100篇高质量内容之前，不得再切换博客方案！**  

舍弃无意义的折腾，回归内容本身，把事情做扎实。