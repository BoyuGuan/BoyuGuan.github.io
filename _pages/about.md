---
permalink: /
title: "关于我"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 个人简介

你好！我是管博宇，中科院自动化所自然语言处理专业的三年级博士研究生。我的研究兴趣主要集中在自然语言处理领域。

欢迎访问我的学术主页。在这里你可以了解我的研究工作、发表的论文以及学术活动。

---

<div id="publications"></div>
## 📚 发表论文

{% if site.author.googlescholar %}
  <div class="wordwrap" style="margin-bottom: 20px;">
    你也可以在 <a href="{{site.author.googlescholar}}">Google Scholar</a> 上查看我的文章。
  </div>
{% endif %}

{% include base_path %}

<!-- 显示发表论文 -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3>
        {% assign title_shown = true %}
      {% endunless %}
      <div class="publication-item" style="margin-bottom: 15px; padding: 10px; border-left: 3px solid #3498db; background-color: #f8f9fa;">
        <h4 style="margin-bottom: 5px;">
          {% if post.paperurl %}
            <a href="{{ post.paperurl }}" target="_blank">{{ post.title }}</a>
          {% else %}
            {{ post.title }}
          {% endif %}
        </h4>
        <p style="margin-bottom: 5px; color: #666;"><strong>{{ post.venue }}</strong> | {{ post.date | date: "%Y年%m月" }}</p>
        {% if post.excerpt %}
          <p style="margin-bottom: 10px; font-size: 14px;">{{ post.excerpt }}</p>
        {% endif %}
        {% if post.citation %}
          <p style="font-size: 12px; color: #888; margin-bottom: 0;">{{ post.citation }}</p>
        {% endif %}
      </div>
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    <div class="publication-item" style="margin-bottom: 15px; padding: 10px; border-left: 3px solid #3498db; background-color: #f8f9fa;">
      <h4 style="margin-bottom: 5px;">
        {% if post.paperurl %}
          <a href="{{ post.paperurl }}" target="_blank">{{ post.title }}</a>
        {% else %}
          {{ post.title }}
        {% endif %}
      </h4>
      <p style="margin-bottom: 5px; color: #666;"><strong>{{ post.venue }}</strong> | {{ post.date | date: "%Y年%m月" }}</p>
      {% if post.excerpt %}
        <p style="margin-bottom: 10px; font-size: 14px;">{{ post.excerpt }}</p>
      {% endif %}
      {% if post.citation %}
        <p style="font-size: 12px; color: #888; margin-bottom: 0;">{{ post.citation }}</p>
      {% endif %}
    </div>
  {% endfor %}
{% endif %}

---

<div id="talks"></div>
## 🎤 学术报告与演讲

{% if site.talkmap_link == true %}
<p style="margin-bottom: 20px;">
  <a href="/talkmap.html" target="_blank">📍 查看我演讲地点的地图</a>
</p>
{% endif %}

{% for post in site.talks reversed %}
  <div class="talk-item" style="margin-bottom: 15px; padding: 10px; border-left: 3px solid #e74c3c; background-color: #fef9f9;">
    <h4 style="margin-bottom: 5px;">{{ post.title }}</h4>
    <p style="margin-bottom: 5px; color: #666;">
      <strong>{{ post.venue }}</strong> | {{ post.date | date: "%Y年%m月%d日" }}
      {% if post.location %} | 📍 {{ post.location }}{% endif %}
    </p>
    {% if post.type %}
      <p style="margin-bottom: 5px; font-size: 14px;"><em>类型：{{ post.type }}</em></p>
    {% endif %}
    {% if post.content %}
      <div style="font-size: 14px; margin-top: 10px;">
        {{ post.content }}
      </div>
    {% endif %}
  </div>
{% endfor %}

---

<div id="contact"></div>
## 📧 联系方式

如果你对我的研究感兴趣或有合作意向，欢迎通过邮件联系我：[{{ site.author.email }}](mailto:{{ site.author.email }})

你也可以在以下平台找到我：
- [GitHub](https://github.com/{{ site.author.github }})
- [Google Scholar]({{ site.author.googlescholar }})
