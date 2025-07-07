---
title: "Vision Transformer with Dynamic Attention"
collection: publications
category: conferences
permalink: /publication/2024-05-15-paper-box-style
excerpt: '本文提出了一种新型的动态注意力机制，显著提高了Vision Transformer在计算机视觉任务中的性能。'
date: 2024-05-15
venue: 'CVPR 2024'
paperurl: '#'
codeurl: 'https://github.com/yourusername/dynamic-vit'
slidesurl: '#'
videourl: '#'
posterurl: '#'
demourl: '#'
authors: 'Zhang Wei, Li Ming, Wang Hua'
acceptance_status: 'Oral Presentation (接受率 4.2%)'
header:
  teaser: '500x300.png'
citation: 'Zhang, W., Li, M., & Wang, H. (2024). &quot;Vision Transformer with Dynamic Attention.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>. pp. 1234-1242.'
---

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="Vision Transformer with Dynamic Attention">
  </div>
  <div class="paper-box-text">
    <h3>Vision Transformer with Dynamic Attention</h3>
    <p><strong>作者：</strong> Zhang Wei, Li Ming, Wang Hua</p>
    <p><strong>会议：</strong> CVPR 2024</p>
    <p><strong>状态：</strong> Oral Presentation (接受率 4.2%)</p>
    <p>本文提出了一种新型的动态注意力机制，显著提高了Vision Transformer在计算机视觉任务中的性能。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="https://github.com/yourusername/dynamic-vit" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--warning">Slides</a>
      <a href="#" class="btn btn--danger">Video</a>
    </p>
  </div>
</div>

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