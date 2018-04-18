---
layout: page
title: 研究室概要 | 中村研究室
description: 日本大学 理工学部 土木工学科 都市・交通研究室（中村研究室）のホームページ
section_id: labo
---
# ＨＰ移転のお知らせ

使用しているドメイン（civilold.civil.cst.nihon-u.ac.jp）とWebサーバが３月中に利用できなくなります。
このため、このドメインでの公開は３月上旬より一時停止します。

新しいWebサーバ・新しいURLであらためてＨＰを公開する予定ですが、時期は未定です。
ご不便をお掛けしますことお詫びします。

なお、[Github](https://nakamura-labo.github.io/)上でも同一ページを見ることが出来ますので、こちらもご利用ください。また、新しいＨＰは[学科の研究室紹介](http://www.civil.cst.nihon-u.ac.jp/laboratory/)から辿れるようにします。

# 研究室概要

中村研究室は、日本大学理工学部土木工学科の都市・交通研究室として2016年4月に新たに開設され、３年目になります。

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
