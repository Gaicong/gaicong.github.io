---
title: "Model Variational Consumer Preferences Based on Online Reviews Using Sentiment Analysis and PSO-based DENFIS Approaches"
collection: publications
category: 'manuscripts'
permalink: /publication/2022-07-01-consumer-preferences
excerpt: '企业面临消费者偏好快速变化的挑战：传统市场调研周期长、成本高，无法及时捕捉消费者的真实需求变化。海量的在线评论数据蕴含着宝贵的信息，但缺乏有效的方法来提取和分析这些动态变化的偏好。本研究利用在线评论的实时性，开发基于情感分析和动态学习的预测模型，实时捕捉和分析消费者偏好的变化趋势。'
date: 2022-07-01
venue: 'Journal of Intelligent & Fuzzy Systems'
paperurl: 'https://doi.org/10.3233/JIFS-213057'
citation: 'Jiang, H.*, <strong>Guo, G.</strong>, Sabetzadeh, F., & Chan, K. Y. (2022). Model variational consumer preferences based on online reviews using sentiment analysis and PSO-based DENFIS approaches. <i>Journal of Intelligent & Fuzzy Systems</i>, 43(3), 2407-2418.'
authors: 'Jiang, H.*, <strong>Guo, G.</strong>, Sabetzadeh, F., & Chan, K. Y.'
---

## 研究背景

### 核心痛点
企业面临**消费者偏好快速变化**的挑战：传统市场调研周期长、成本高，无法及时捕捉消费者的真实需求变化。海量的在线评论数据蕴含着宝贵的信息，但缺乏有效的方法来提取和分析这些动态变化的偏好。

### 解决思路
利用**在线评论的实时性**，开发基于情感分析和动态学习的预测模型，实时捕捉和分析消费者偏好的变化趋势。

## 技术方案

### 核心创新
- **情感分析+DENFIS融合**：将文本情感特征输入动态神经模糊推理系统
- **PSO参数优化**：自动调整DENFIS的学习参数，提高预测精度
- **实时适应机制**：模型能够随着新评论的加入不断更新和进化

### 技术架构
- **数据预处理**：爬取在线评论→文本清洗→情感特征提取
- **动态建模**：DENFIS系统实时学习新的偏好模式
- **参数调优**：PSO算法优化DENFIS的网络结构和学习率

## 实际应用

该系统为企业提供了**实时市场洞察**工具，能够：
- 及时发现产品或服务的问题
- 预测市场趋势变化
- 指导产品改进和营销策略调整

- 相比传统调研方法，反应速度提升90%以上
