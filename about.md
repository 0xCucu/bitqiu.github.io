---
layout: page
title: 关于
menu: About
---
{% assign current_year = site.time | date: '%Y' %}

BitQiu
===
男 90后

## 概况

- 邮箱：i#bitqiu.cc
- 主页：[http://bitqiu.cc](http://bitqiu.cc)

{{ current_year | minus: 2012 }} 年在职工作经验，{{ current_year | minus: 2011 }} 年 web 开发经验。


## keywords
<div class="btn-inline">
{% for keyword in site.skill_keywords %} <button class="btn btn-outline" type="button">{{ keyword }}</button> {% endfor %}
</div>

### 综合技能

| 名称 | 熟悉程度
|--:|:--|
| PHP | ★★★★☆ |
| javascript | ★★★★☆ |
| Linux | ★★★★☆ |
| Nodejs | ★★☆☆☆ |
| Markdown | ★★★★☆ |
| Photoshop | ★★★★☆ |
