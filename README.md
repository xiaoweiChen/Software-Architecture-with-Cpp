# Software Architecture with C++

Design modern systems using effective architecture concepts, design patterns, and techniques with C++20

(*使用有效的架构计模式和C++20进行系统设计*)

* 作者：Adrian Ostrowski，Piotr Gaczkowski

* 译者：陈晓伟

* 首次发布时间：2021年4月23日([来源](https://www.amazon.com/Software-Architecture-effective-architecture-techniques/dp/1838554599))

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

***通过理解诸如微服务、DevOps和使用现代C++标准和特性的本地云等架构，将业务需求应用到IT基础设施，并交付高质量的产品***

软件架构是指复杂应用的高级设计。就像语言一样，它也在不断发展，但在不牺牲可读性和可维护性的情况下，可以了解一些架构概念和模式，以及用高级语言编写高性能的应用。

如果正在使用现代C++，本书会把相应的知识运用到实际工作中，设计分布式的、大规模的应用。首先，快速了解架构概念，包括已建立的模式和正在兴起的趋势，然后继续理解什么是软件架构，并开始研究其组件。

接下来，在学习如何构建、打包、集成和部署组件之前，再了解应用程序架构中涉及的设计概念和软件开发中的模式。在最后一章中，将探讨不同的架构质量，例如：可维护性、可重用性、可测试性、性能、可扩展性和安全性。最后，将概述分布式系统，如面向服务的架构、微服务和本地云，并了解如何在应用开发中应用。

本书的最后，将使用现代C++和相关工具构建分布式服务，从而根据客户的需求交付解决方案。

#### 关键特性

- 用C++设计可扩展的大规模应用程序
- 基于云的持续集成和持续交付(CI/CD)中的软件架构解决方案
- 通过设计模式、语言特性和工具来实现架构的目标

#### 内容纲要

- 理解如何应用软件架构的原则
- 应用设计模式和最佳实践来满足架构的目标
- 使用最新的C++特性编写优雅、安全、高效的代码
- 构建易于维护和部署的应用
- 探索不同架构的方法，并根据需求进行应用
- 使用容器简化开发和操作
- 了解在软件设计和开发中常见问题的解决方法

## 适读人群

这本软件架构C++编程书是为有经验的C++开发者准备的，并且这些开发者希望成为软件架构师，或想要开发企业级应用。

为了帮助使用现代C++的开发者将能够将知识运用到软件架构的实践指南中，本书采取了实践的方法来实现相关方案，一定会让读者们感觉干货满满。

## 作者简介

**[Adrian Ostrowski](https://www.amazon.com/Adrian-Ostrowski/e/B08ZQTDGHR/ref=aufs_dp_mata_dsk)**是一个现代C++爱好者，对C++的开发和编写的高质量代码都很感兴趣。他在IT行业有超过十年的经验，特别是在C++方面有超过8年的经验，总是会与他人分享知识。其操刀的项目包括通过光纤网络进行并行计算，以及在商品交易所的交易系统上工作。目前，他是英特尔和Habana机器学习框架的设计师之一。

在业余时间里，他曾与Piotr一起推广乐队，并学会了如何驾驶滑翔机。目前，他喜欢骑自行车、参加音乐活动和浏览一些网络梗。

> 敬Agnieszka，感谢她的爱和支持
> 敬Mateusz，我的良师益友
> 敬我的父母，是你们激发了我的好奇心
> 敬我的朋友们，感谢你们所做的一切
>
> <p align="right"> — Adrian Ostrowski</p>

**[Piotr Gaczkowski](https://www.amazon.com/Piotr-Gaczkowski/e/B08Y7V74KM/ref=aufs_dp_mata_dsk)**在编程和实践DevOps方面有超过10年的经验。他喜欢为问题构建简单的解决方案，组织文化活动，教授专业人士。Piotr热衷于将无聊的活动自动化，并利用自己的经验，通过开设课程、撰写有关个人成长和远程工作的文章来分享知识。

他曾在IT行业从事全职工作和自由职业，但他真正热爱的是音乐。当他的技能不能在工作中发挥作用时，他就会去在建立社区。

> 致Emilia，她在我写这本书的时候容非常包容我；我的父母鼓励我编程；为我加油鼓劲的智囊团成员；Hackerspace Trójmiasto，气氛组重要成员；IOD，提醒我要保持对写作的热爱；255，检验工作；以及所有和我一起走过这段旅程的朋友们。爱你们！
> 
> <p align="right"> — Piotr Gaczkowski</p>

## 审评者介绍

**Andrey Gavrilin**是一名高级软件工程师，就职于提供财务管理云解决方案的国际公司。他拥有工程(工业自动化)硕士学位，曾在会计和人力资源、道路数据库、Web和Linux发行开发以及金融科技等不同领域工作。他的兴趣包括数学、电子、嵌入式系统、全栈网页开发、复古游戏和复古编程。

## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/XXXX
* 本书源码：https://github.com/PacktPublishing/Software-Architecture-with-Cpp
* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html 
* vscode中配置latex：https://blog.csdn.net/Ruins_LEE/article/details/123555016

