---
title: "Paper-Box 样式演示"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-paper-box-demo
excerpt: '这是一个演示如何使用paper-box样式来展示论文的示例页面。'
date: 2024-12-01
venue: 'Demo Journal'
paperurl: '#'
citation: 'Your Name, You. (2024). &quot;Paper-Box 样式演示.&quot; <i>Demo Journal</i>. 1(1).'
---

这个页面演示了如何使用新添加的 paper-box 样式来美观地展示您的论文。以下是几个不同的使用示例：

## 基本用法示例

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/profile.png" alt="论文图片示例">
  </div>
  <div class="paper-box-text">
    <h3>Deep Learning for Computer Vision</h3>
    <p><strong>作者：</strong> Zhang Wei, Li Ming, Wang Hua</p>
    <p><strong>期刊：</strong> IEEE Transactions on Pattern Analysis and Machine Intelligence</p>
    <p><strong>年份：</strong> 2024</p>
    <p>这是一篇关于计算机视觉中深度学习应用的重要论文。我们提出了一种新的卷积神经网络架构，在多个基准数据集上取得了显著的性能提升。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--success">Dataset</a>
    </p>
  </div>
</div>

## 第二个论文示例

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/image-alignment-300x200.jpg" alt="论文图片示例2">
  </div>
  <div class="paper-box-text">
    <h3>Natural Language Processing with Transformers</h3>
    <p><strong>作者：</strong> Chen Liu, Yang Zhang, Li Wang</p>
    <p><strong>会议：</strong> ACL 2024</p>
    <p><strong>年份：</strong> 2024</p>
    <p>本文提出了一种改进的Transformer架构，专门用于处理中文自然语言任务。我们的方法在多个中文NLP基准测试中都取得了最先进的结果。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--warning">Demo</a>
    </p>
  </div>
</div>

## 第三个论文示例

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="论文图片示例3">
  </div>
  <div class="paper-box-text">
    <h3>Reinforcement Learning for Robotics</h3>
    <p><strong>作者：</strong> Liu Ming, Wang Lei, Zhang Yu</p>
    <p><strong>期刊：</strong> Nature Machine Intelligence</p>
    <p><strong>年份：</strong> 2023</p>
    <p>我们开发了一个新的强化学习框架，使机器人能够在复杂的真实世界环境中学习和适应。该方法显著提高了机器人任务的成功率和效率。</p>
    <p>
      <a href="#" class="btn btn--primary">PDF</a>
      <a href="#" class="btn btn--info">Code</a>
      <a href="#" class="btn btn--danger">Video</a>
    </p>
  </div>
</div>

## 使用说明

paper-box 样式具有以下特点：

- **响应式设计**：在移动设备上，图片会显示在文本下方；在桌面设备上，图片显示在左侧
- **灵活布局**：图片容器最大宽度为400px，在桌面端占40%宽度
- **美观阴影**：图片自带阴影效果，增强视觉效果
- **清晰分隔**：每个论文条目之间有清晰的底部边框分隔

### HTML 结构

```html
<div class="paper-box">
  <div class="paper-box-image">
    <img src="你的图片路径" alt="描述">
  </div>
  <div class="paper-box-text">
    <!-- 你的论文信息 -->
  </div>
</div>
```

这样您就可以在任何支持Markdown和HTML的页面中使用这些样式来展示您的论文了！ 