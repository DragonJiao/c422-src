+++
title = "[分享] CPU简析与软件设计总结"
summary = "硬件简析之CPU篇与自己前段时间软件设计经验的总结"

date = "2019-05-30T00:00:00+00:00"
tags = []
authors = ["yangjin"]

[header]
image = ""
caption = ""
+++

点击[PDF](https://cdn.coden.hk/c422/weekly-keynote/2019-5-31-yangjin/5.30工作室分享会.pdf)查看详情

## 指出一个错误

针对PDF中提出的 **“为什么‘4核8线程’中用的是线程而非进程？”** 问题

首先明确一个点，**‘4核8线程’中的线程与我们设计软件时遇到的线程并不是同一个概念！**前者指的是CPU中的**物理单元**，后者指的是操作系统中的**逻辑单元**，所以这个问题本身并不成立！

