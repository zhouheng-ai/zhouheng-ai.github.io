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

  /* WeChat 弹窗 */
.wechat-modal {
  position: fixed;
  inset: 0;
  z-index: 1000;

  display: flex;
  align-items: center;
  justify-content: center;

  padding: 24px;

  opacity: 0;
  visibility: hidden;
  pointer-events: none;

  transition:
    opacity 0.2s ease,
    visibility 0.2s ease;
}

/* 访问 #wechat-modal 时显示 */
.wechat-modal:target {
  opacity: 1;
  visibility: visible;
  pointer-events: auto;
}

/* 灰色遮罩 */
.wechat-modal-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.68);
  cursor: default;
}

/* 白色弹窗主体 */
.wechat-modal-content {
  position: relative;
  z-index: 1;

  width: min(470px, 100%);
  padding: 48px 48px 36px;

  background: #fff;
  border-radius: 18px;
  box-shadow: 0 18px 60px rgba(0, 0, 0, 0.28);

  text-align: center;
  transform: translateY(14px) scale(0.97);
  transition: transform 0.2s ease;
}

.wechat-modal:target .wechat-modal-content {
  transform: translateY(0) scale(1);
}

/* 右上角关闭按钮 */
.wechat-modal-close {
  position: absolute;
  top: 14px;
  right: 22px;

  color: #12324a;
  font-size: 34px;
  font-weight: 300;
  line-height: 1;
  text-decoration: none;
}

.wechat-modal-close:hover {
  color: #1769aa;
  text-decoration: none;
}

/* 二维码 */
.wechat-qr {
  display: block;
  width: 100%;
  max-width: 350px;
  height: auto;
  margin: 0 auto;

  border-radius: 10px;
}

/* 底部文字 */
.wechat-modal-title {
  margin: 28px 0 0;
  color: #17344c;
  font-size: 21px;
}

/* 手机端 */
@media (max-width: 600px) {
  .wechat-modal {
    padding: 18px;
  }

  .wechat-modal-content {
    padding: 44px 24px 28px;
    border-radius: 14px;
  }

  .wechat-modal-title {
    margin-top: 20px;
    font-size: 18px;
  }
}

  .email-modal {
  position: fixed;
  inset: 0;
  z-index: 1000;

  display: flex;
  align-items: center;
  justify-content: center;

  padding: 24px;

  opacity: 0;
  visibility: hidden;
  pointer-events: none;

  transition:
    opacity 0.2s ease,
    visibility 0.2s ease;
}

.email-modal:target {
  opacity: 1;
  visibility: visible;
  pointer-events: auto;
}

.email-modal-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.68);
}

.email-modal-content {
  position: relative;
  z-index: 1;

  width: min(550px, 100%);
  padding: 48px 46px 36px;

  background: #fff;
  border-radius: 18px;
  box-shadow: 0 18px 60px rgba(0, 0, 0, 0.28);

  text-align: center;
  transform: translateY(12px) scale(0.98);
  transition: transform 0.2s ease;
}

.email-modal:target .email-modal-content {
  transform: translateY(0) scale(1);
}

.email-modal-close {
  position: absolute;
  top: 13px;
  right: 22px;

  color: #12324a;
  font-size: 34px;
  font-weight: 300;
  line-height: 1;
  text-decoration: none;
}

.email-modal-close:hover {
  color: #1769aa;
  text-decoration: none;
}

.email-address {
  display: block;
  width: 100%;
  padding: 25px 16px;

  color: #17344c;
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 9px;

  font-family: inherit;
  font-size: 24px;
  cursor: pointer;
}

.email-address:hover {
  background: #f7f7f7;
  border-color: #aaa;
}

.email-modal-title {
  margin: 27px 0 0;
  color: #17344c;
  font-size: 20px;
}

@media (max-width: 600px) {
  .email-modal-content {
    padding: 45px 24px 30px;
  }

  .email-address {
    padding: 20px 10px;
    font-size: 18px;
    overflow-wrap: anywhere;
  }

  .email-modal-title {
    font-size: 17px;
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
  Jiangnan University (江南大学), Wuxi (无锡), China
</p>

<p>
周恒，讲师，硕士生导师，江苏省卓越博士后，西安电子科技大学优博。
</p>
<p>
He is currently a Lecturer at the School of Artificial Intelligence and Computer Science, Jiangnan University, Wuxi, China. 
He received the Ph.D. degree in Electronic Science and Technology from Xidian University in 2024. His research interests include multimodal learning, remote sensing image processing.

</p>


<p class="profile-links">
   <a href="#wechat-modal">💬 WeChat</a>
   &nbsp;·&nbsp;
  <a href='#email-modal'>📧 Email</a>
  &nbsp;·&nbsp;
  <a href="https://scholar.google.com.hk/citations?hl=en&user=WFFSbNQAAAAJ&view_op=list_works&sortby=pubdate"
    target="_blank"
  rel="noopener noreferrer"
    >📖 Google Scholar</a>
  &nbsp;·&nbsp;
  <a href="https://www.researchgate.net/profile/Heng-Zhou-6"
    target="_blank"
  rel="noopener noreferrer"
    >🏫 ResearchGate</a>
</p>

</div>





{% include interests.html %}

{% include publications.html %}

{% include awards.html %}












<p class="updated">
  Last updated: {{ site.time | date: "%B %Y" }}
</p>

</div>


<div
  id="wechat-modal"
  class="wechat-modal"
  role="dialog"
  aria-modal="true"
  aria-labelledby="wechat-modal-title"
>
  <!-- 点击灰色背景关闭 -->
  <a
    href="#"
    class="wechat-modal-overlay"
    aria-label="Close WeChat dialog"
  ></a>

  <div class="wechat-modal-content">
    <a
      href="#"
      class="wechat-modal-close"
      aria-label="Close WeChat dialog"
    >
      &times;
    </a>

    <img
      class="wechat-qr"
      src="/imgs/HengZhou-WeChat.jpg"
      alt="Heng Zhou WeChat QR code"
    >

    <p id="wechat-modal-title" class="wechat-modal-title">
      💬 Scan to add WeChat
    </p>
  </div>
</div>


<div
  id='email-modal'
  class='email-modal'
  role='dialog'
  aria-modal='true'
  aria-labelledby='email-modal-title'
>
  <a
    href='#'
    class='email-modal-overlay'
    aria-label='Close email dialog'
  ></a>

  <div class='email-modal-content'>
    <a
      href='#'
      class='email-modal-close'
      aria-label='Close email dialog'
    >
      &times;
    </a>

    <button
      class='email-address'
      type='button'
      onclick='copyEmail()'
    >
      hengzhou@jiangnan.edu.cn
    </button>

    <p id='email-copy-status' class='email-modal-title'>
      ✉️ Click to copy / Contact me via email
    </p>
  </div>
</div>


<script>
  function copyEmail() {
    const email = 'hengzhou@jiangnan.edu.cn';
    const status = document.getElementById('email-copy-status');

    navigator.clipboard.writeText(email).then(function () {
      status.textContent = '✓ Email copied to clipboard';

      window.setTimeout(function () {
        status.textContent = '✉️ Click to copy / Contact me via email';
      }, 1800);
    }).catch(function () {
      window.location.href = 'mailto:' + email;
    });
  }
</script>
