---
title: "会议论文展示示例"
collection: publications
category: conferences
permalink: /publication/2024-10-15-conference-paper-example
excerpt: '这是一个专门用于展示会议论文的paper-box样式示例。'
date: 2024-10-15
venue: 'CVPR 2024'
paperurl: '#'
citation: 'Your Name, You. (2024). &quot;Vision Transformer with Dynamic Attention.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>. pp. 1234-1242.'
---

# 会议论文展示示例

以下是如何使用paper-box样式来展示您的会议论文。这种布局特别适合展示会议论文，因为它可以突出显示论文的关键信息和视觉内容。

## CVPR 2024 论文

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="Vision Transformer架构图">
  </div>
  <div class="paper-box-text">
    <h3>Vision Transformer with Dynamic Attention</h3>
    <p><strong>作者：</strong> Zhang Wei, Li Ming, Wang Hua</p>
    <p><strong>会议：</strong> CVPR 2024</p>
    <p><strong>接收状态：</strong> Oral Presentation (接受率 4.2%)</p>
    <p>本文提出了一种新型的动态注意力机制，显著提高了Vision Transformer在计算机视觉任务中的性能。我们的方法在ImageNet分类、COCO目标检测和ADE20K语义分割等多个基准测试中均取得了最先进的结果。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--success">Slides</a>
      <a href="#" class="btn btn--danger">Video</a>
    </p>
  </div>
</div>

## ICLR 2024 论文

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/image-alignment-300x200.jpg" alt="神经网络架构图">
  </div>
  <div class="paper-box-text">
    <h3>Self-Supervised Learning with Contrastive Knowledge Distillation</h3>
    <p><strong>作者：</strong> Liu Yang, Chen Jia, Zhang Wei</p>
    <p><strong>会议：</strong> ICLR 2024</p>
    <p><strong>接收状态：</strong> Spotlight (接受率 8.7%)</p>
    <p>我们提出了一种新的自监督学习方法，结合对比学习和知识蒸馏，在有限的标注数据条件下显著提高了模型性能。该方法在多个下游任务中展现出强大的迁移学习能力。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--warning">Demo</a>
      <a href="#" class="btn btn--success">Poster</a>
    </p>
  </div>
</div>

## NeurIPS 2023 论文

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/profile.png" alt="算法示意图">
  </div>
  <div class="paper-box-text">
    <h3>Efficient Reinforcement Learning with Hierarchical Planning</h3>
    <p><strong>作者：</strong> Wang Lei, Zhang Yu, Li Xin</p>
    <p><strong>会议：</strong> NeurIPS 2023</p>
    <p><strong>接收状态：</strong> Poster</p>
    <p>本文提出了一种层次化规划框架，显著提高了强化学习算法在复杂环境中的探索效率和性能。我们的方法在Atari游戏和MuJoCo机器人控制任务中均表现出色。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--danger">Video</a>
      <a href="#" class="btn btn--success">Supplementary</a>
    </p>
  </div>
</div>

## 会议论文展示技巧

在展示会议论文时，以下信息通常很重要：

1. **会议名称和年份**：如CVPR 2024、ICLR 2024等
2. **接收类型**：Oral、Spotlight、Poster等
3. **接受率**：展示论文的竞争程度
4. **视觉材料**：可以是论文中的关键图表、架构图或实验结果
5. **相关资源**：论文PDF、代码、演示视频、幻灯片、海报等

使用paper-box样式可以清晰地组织这些信息，使您的会议论文展示更加专业和吸引人。

## HTML结构参考

```html
<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/your-conference-image.jpg" alt="描述">
  </div>
  <div class="paper-box-text">
    <h3>论文标题</h3>
    <p><strong>作者：</strong> 作者列表</p>
    <p><strong>会议：</strong> 会议名称和年份</p>
    <p><strong>接收状态：</strong> Oral/Spotlight/Poster (可选：接受率)</p>
    <p>论文摘要或简短描述...</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <!-- 其他资源按钮 -->
    </p>
  </div>
</div>
``` 