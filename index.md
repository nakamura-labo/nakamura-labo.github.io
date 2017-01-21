---
layout: page
title: 研究室概要 | 中村研究室
description: 日本大学 理工学部 土木工学科 都市・交通研究室（中村研究室）のホームページ
section_id: labo
---

# 研究室概要

中村研究室は、日本大学理工学部土木工学科の都市・交通研究室として2016年4月に新たに開設されました。

都市計画、都市交通、都市開発などを主な研究分野として活動しています。

## 最近の更新

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

## 主なコンテンツ

* [メンバー](member)
* [論文・学会発表](papers)
* [出来事](posts)
* [研究室内Tips](tips)
* [アクセス](access)
* [リンク](link)
* [サイトマップ](sitemap)
{: .list-unstyled}

<!--
<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
-->
