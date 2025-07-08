---
title: "TriFine: A Large-Scale Dataset of Vision-Audio-Subtitle for Tri-Modal Machine Translation and Benchmark with Fine-Grained Annotated Tags"
collection: publications
category: conferences
permalink: /publication/2024-12-TriFine
excerpt: '本文提出了一种新型的动态注意力机制，显著提高了Vision Transformer在计算机视觉任务中的性能。'
date: 2024-05-15
venue: '<span style="background-color:rgb(32, 98, 168); color: white; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-style: normal;">CCF B</span> COLING 2025'
paperurl: 'https://aclanthology.org/2025.coling-main.547.pdf'
codeurl: 'https://github.com/BoyuGuan/TriFine'
slidesurl: '/files/paper-TriFine/oral-TriFine.pdf'
videourl: # '#'
posterurl: #'#'
demourl: # '#'
authors: '**Boyu Guan**, Yining Zhang, Yang Zhao<sup>#</sup>, Chengqing Zong'
acceptance_status: 'Oral (rate 4.2%)'
header:
  teaser: 'https://boyuguan.github.io/files/paper-TriFine/TriFine.png'
citation: # 'Zhang, W., Li, M., & Wang, H. (2024). &quot;Vision Transformer with Dynamic Attention.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>. pp. 1234-1242.'
---

本文提出了一种新型的动态注意力机制，显著提高了Vision Transformer在计算机视觉任务中的性能。我们的方法在ImageNet分类、COCO目标检测和ADE20K语义分割等多个基准测试中均取得了最先进的结果。

## 摘要

Transformer模型已经在计算机视觉领域取得了巨大的成功。然而，标准的自注意力机制对所有输入令牌使用固定的注意力模式，这限制了模型对不同视觉内容的适应能力。本文提出了一种动态注意力机制，根据输入内容自适应地调整注意力分布。我们的方法不仅提高了模型性能，还减少了计算复杂度，使模型更加高效。

## 方法

我们的动态注意力机制包括以下关键组件：
1. 内容感知的注意力生成器
2. 自适应稀疏化策略
3. 层次化的注意力分配

## 实验结果

在ImageNet-1K分类任务上，我们的方法达到了85.6%的Top-1准确率，比基线ViT-B/16模型高出2.3个百分点。在COCO目标检测和ADE20K语义分割任务中，我们的方法也取得了显著的性能提升。

## 结论

本文提出的动态注意力机制为Vision Transformer模型提供了一种更加灵活和高效的注意力分配方式，显著提高了模型在各种计算机视觉任务中的性能。 