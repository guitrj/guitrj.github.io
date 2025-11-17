---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## 教育
* 上海交通大学, 李政道研究所: 天文学博士 (预计 2031 年毕业).
* 上海交通大学, 物理与天文学院: 物理学学士 (预计 2026 年毕业).

## 科研
* 2023 秋—2025 春: 粒子物理理论
  * 导师: 王伟, 何红建
  * 研究方向: 圈图计算与费曼积分, 量子色动力学有效理论, 非微扰量子场论.
* 2025 春—至今: 天体物理理论
  * 导师: 赖东 (Dong Lai)
  * 研究方向: 致密天体 (磁星辐射, 黑洞双星合并, 潮汐瓦解事件等), 系外行星 (行星轨道动力学, 行星刚体动力学等) 与天体物理动力学 (非线性力学, 混沌现象等) 

## 出版物 / 学术论文

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

学术报告
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
