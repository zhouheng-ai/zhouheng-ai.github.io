---
layout: default
title: Heng Zhou
---

<style>
  /* 隐藏 Minima 主题自带的顶部导航和底部信息 */
  .site-header,
  .site-footer {
    display: none;
  }

  .page-content {
    padding: 0;
  }

  .wrapper {
    max-width: 920px;
  }

  body {
    color: #222;
    font-size: 17px;
    line-height: 1.7;
  }

  a {
    color: #1769aa;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .homepage {
    margin: 48px auto 80px;
  }

  .profile::after {
    display: block;
    clear: both;
    content: "";
  }

  .portrait {
    float: right;
    width: 220px;
    height: auto;
    margin: 5px 0 25px 42px;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.12);
  }

  .name {
    margin: 0 0 8px;
    font-size: 38px;
    font-weight: 500;
    line-height: 1.25;
  }

  .chinese-name {
    margin-left: 8px;
    font-size: 25px;
    font-weight: 400;
  }

  .position {
    margin: 0 0 3px;
    font-size: 18px;
  }

  .affiliation {
    margin: 0 0 15px;
    color: #666;
  }

  .profile-links {
    margin: 14px 0 24px;
  }

  section {
    margin-top: 38px;
  }

  h2 {
    margin-bottom: 17px;
    padding-bottom: 5px;
    border-bottom: 1px solid #ddd;
    font-size: 25px;
    font-weight: 500;
  }

  li {
    margin-bottom: 9px;
  }

  .news-list {
    padding-left: 0;
    list-style: none;
  }

  .news-item {
    display: flex;
    gap: 22px;
    margin-bottom: 10px;
  }

  .news-date {
    min-width: 100px;
    font-weight: 600;
  }

  .publication {
    margin-bottom: 19px;
  }

  .paper-title {
    font-weight: 600;
  }

  .venue {
    font-style: italic;
  }

  .updated {
    margin-top: 55px;
    padding-top: 15px;
    border-top: 1px solid #ddd;
    color: #777;
    font-size: 14px;
    text-align: center;
  }

  @media (max-width: 700px) {
    .homepage {
      margin-top: 28px;
    }

    .portrait {
      float: none;
      display: block;
      width: 180px;
      margin: 0 auto 25px;
    }

    .name,
    .position,
    .affiliation,
    .profile-links {
      text-align: center;
    }

    .name {
      font-size: 32px;
    }

    .news-item {
      display: block;
    }

    .news-date {
      display: block;
      margin-bottom: 2px;
    }
  }
</style>

<div class="homepage">

<div class="profile">

<img
  class="portrait"
  src="/imgs/HengZhou.jpg"
  alt="Portrait of Heng Zhou"
>

<h1 class="name">
  Heng Zhou <span class="chinese-name">周恒</span>
</h1>

<p class="position">
  Lecturer
</p>

<p class="affiliation">
  School of Artificial Intelligence and Computer Science<br>
  Jiangnan University, Wuxi, China
</p>

<p>
  I am Heng Zhou, a researcher interested in artificial intelligence
  and machine learning. My research focuses on developing effective,
  reliable, and practical intelligent systems.
</p>


<p class="profile-links">
  <a href="mailto:hengzhou@jiangnan.edu.cn">Email</a>
  &nbsp;·&nbsp;
  <a href="https://scholar.google.com.hk/citations?hl=en&user=WFFSbNQAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/zhouheng-ai">GitHub</a>
</p>


</div>

<section markdown="1">

## Research Interests

- Machine Learning
- Deep Learning
- Computer Vision
- Trustworthy Artificial Intelligence

</section>

<section markdown="1">

## News

<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Jul. 2026</span>
    <span>My academic homepage is now online.</span>
  </li>
</ul>

</section>

<section markdown="1">

## Publications

<div class="publication">
  <span class="paper-title">Title of Your Paper.</span><br>
  <strong>Heng Zhou</strong>, Second Author, Third Author.<br>
  <span class="venue">Conference or Journal Name</span>, 2026.<br>
  [<a href="#">Paper</a>]
  [<a href="#">Code</a>]
</div>

</section>

<p class="updated">
  Last updated: {{ site.time | date: "%B %Y" }}
</p>

</div>
