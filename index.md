<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
  >

  <title>Heng Zhou | Academic Homepage</title>

  <meta
    name="description"
    content="Academic homepage of Heng Zhou. Research interests include artificial intelligence and machine learning."
  >

  <style>
    :root {
      --text-color: #222;
      --secondary-color: #666;
      --link-color: #1769aa;
      --line-color: #dedede;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: #fff;
      color: var(--text-color);
      font-family:
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        Arial,
        "Noto Sans SC",
        sans-serif;
      font-size: 17px;
      line-height: 1.7;
    }

    main {
      width: min(920px, calc(100% - 48px));
      margin: 50px auto 80px;
    }

    header::after {
      display: block;
      clear: both;
      content: "";
    }

    .portrait {
      float: right;
      width: 220px;
      height: auto;
      margin: 4px 0 24px 42px;
      border-radius: 4px;
      box-shadow: 0 2px 10px rgb(0 0 0 / 12%);
    }

    h1 {
      margin: 0 0 8px;
      font-size: 38px;
      font-weight: 500;
      line-height: 1.25;
    }

    .chinese-name {
      font-size: 26px;
      font-weight: 400;
    }

    .position {
      margin: 0 0 4px;
      font-size: 18px;
    }

    .affiliation {
      margin: 0 0 14px;
      color: var(--secondary-color);
    }

    .links {
      margin: 14px 0 22px;
    }

    a {
      color: var(--link-color);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    section {
      margin-top: 38px;
    }

    h2 {
      margin: 0 0 18px;
      padding-bottom: 5px;
      border-bottom: 1px solid var(--line-color);
      font-size: 25px;
      font-weight: 500;
    }

    ul,
    ol {
      padding-left: 24px;
    }

    li {
      margin-bottom: 9px;
    }

    .news {
      padding-left: 0;
      list-style: none;
    }

    .news li {
      display: flex;
      gap: 24px;
      margin-bottom: 10px;
    }

    .news time {
      min-width: 95px;
      font-weight: 600;
    }

    .publications li {
      margin-bottom: 17px;
    }

    .paper-title {
      font-weight: 600;
    }

    .venue {
      font-style: italic;
    }

    footer {
      margin-top: 60px;
      padding-top: 16px;
      border-top: 1px solid var(--line-color);
      color: var(--secondary-color);
      font-size: 14px;
      text-align: center;
    }

    @media (max-width: 700px) {
      main {
        width: min(100% - 32px, 920px);
        margin-top: 28px;
      }

      .portrait {
        float: none;
        display: block;
        width: 180px;
        margin: 0 auto 26px;
      }

      h1 {
        font-size: 32px;
        text-align: center;
      }

      .position,
      .affiliation,
      .links {
        text-align: center;
      }

      .news li {
        display: block;
      }

      .news time {
        display: block;
        margin-bottom: 2px;
      }
    }
  </style>
</head>

<body>
  <main>
    <header>
      <img
        class="portrait"
        src="imgs/HengZhou.jpg"
        alt="Portrait of Heng Zhou"
      >

      <h1>
        Heng Zhou
        <span class="chinese-name">周恒</span>
      </h1>

      <p class="position">
        Researcher in Artificial Intelligence
      </p>

      <p class="affiliation">
        Your Department<br>
        Your University, City, China
      </p>

      <p class="links">
        <a href="mailto:your-email@example.com">Email</a>
        &nbsp;·&nbsp;
        <a href="YOUR_GOOGLE_SCHOLAR_URL">Google Scholar</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/zhouheng-ai">GitHub</a>
      </p>

      <p>
        I am Heng Zhou, a researcher interested in artificial intelligence
        and machine learning. My research focuses on developing effective,
        reliable, and practical intelligent systems.
      </p>
    </header>

    <section>
      <h2>Research Interests</h2>

      <ul>
        <li>Machine Learning</li>
        <li>Deep Learning</li>
        <li>Computer Vision</li>
        <li>Trustworthy Artificial Intelligence</li>
      </ul>
    </section>

    <section>
      <h2>News</h2>

      <ul class="news">
        <li>
          <time datetime="2026-07">Jul. 2026</time>
          <span>My academic homepage is now online.</span>
        </li>
      </ul>
    </section>

    <section>
      <h2>Publications</h2>

      <ol class="publications">
        <li>
          <span class="paper-title">Title of Your Paper.</span><br>
          <strong>Heng Zhou</strong>, Second Author, Third Author.<br>
          <span class="venue">Conference or Journal Name</span>, 2026.
          [<a href="#">Paper</a>]
          [<a href="#">Code</a>]
        </li>

        <!-- 复制上面的 li 添加更多论文 -->
      </ol>
    </section>

    <section>
      <h2>Education</h2>

      <ul>
        <li>
          <strong>Ph.D. in Your Major</strong>,
          Your University, 20XX–20XX
        </li>

        <li>
          <strong>B.Eng. in Your Major</strong>,
          Your University, 20XX–20XX
        </li>
      </ul>
    </section>

    <footer>
      Last updated: July 2026
    </footer>
  </main>
</body>
</html>
