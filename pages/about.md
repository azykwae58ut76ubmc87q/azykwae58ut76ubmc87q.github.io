---
layout: page
title: プロフィール
permalink: /about/
weight: 1
---

<h3 class="page-title">プロフィール</h3>
<br>
<br>
<div class="row justify-content-center align-items-center mx-5">
       <img src="https://source.unsplash.com/LhWr3yGGC6k" alt="aboutme_dummy">
</div>
<br>
<br>
<p class = "page-content">
樋口一葉　

日本の小説家。<br>東京生まれ。戸籍名は「奈津」だが、本人は「夏子」と名乗ることが多かった。

</p>
<br>
<br>
<div class="row" style="margin-top:20px;margin-bottom:50px;">{% include about/timeline.html %}</div>
<br>
<br>
<div class="row" style="margin-bottom:50px;">{% include about/skills.html title="About me" source=site.data.about-me %} {% include about/skills.html title="Other thigs to list..." source=site.data.others %}</div>
