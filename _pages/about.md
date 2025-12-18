---
layout: about
title: about
permalink: /
subtitle: "<a href='#'> 团队目标 </a>: AI for public policy"

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>团队负责人：张友浪</p>
    <p>首席工程师：王培杰</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
建设自主化、系统化的政策数据体系，是推动自主知识体系发展、实现决策科学化与国家治理体系和治理能力现代化的基础工程。

公共政策可分解为“政策工具—工具设定—适用条件—作用对象”的结构化单元，但受制于高成本数据标注与低可扩展性，政策工具及其参数设定的结构化数据长期稀缺，相关研究多停留在政策或工具类型层面，难以开展机制导向的细颗粒度比较。

本文提出一种融合通用大语言模型与专用自然语言处理模型的混合协同框架，旨在实现政策工具及其参数设定的要素挖掘与知识库构建。该框架遵循包括三项标准化操作流程：

1. 基于轻量化多模型组合的高效率数据采集与文本预处理；
2. 利用高性能通用大模型开展文本语义解析并抽取工具要素；
3. 通过专用模型完成工具数据库构建与知识图谱生成。

混合协同的多模型架构在工具要素识别精度与覆盖广度上均显著优于现有方法，同时兼具“成本—性能”均衡、可动态迭代更新、可解释性以及可迁移性。

本文为公共政策研究从“政策层面”推进至“工具—参数”层面提供可复制的方法基础，并为构建更具解释力的理论模型与实践导向的政策设计提供数据与工具支撑。
