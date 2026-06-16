---
layout: null
permalink: /
---
<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lianyang Codex Public Edition｜莲羊 Codex 公开版</title>
  <meta name="description" content="Lianyang Codex Public Edition is a public, AI-readable and human-readable archive for understanding Lian Yang, her Mineral Pigment Art practice, public projects, terminology, and cultural context.">
  <meta name="robots" content="index, follow">
  <style>
    :root {
      --text: #1f2328;
      --muted: #59636e;
      --border: #d8dee4;
      --bg: #ffffff;
      --soft: #f6f8fa;
      --accent: #8a5a2b;
      --link: #0969da;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", "Helvetica Neue", Arial, "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
      line-height: 1.68;
    }
    .wrap {
      width: min(920px, calc(100% - 40px));
      margin: 0 auto;
      padding: 56px 0 72px;
    }
    .eyebrow {
      color: var(--accent);
      font-size: 14px;
      letter-spacing: .08em;
      text-transform: uppercase;
      font-weight: 700;
      margin-bottom: 12px;
    }
    h1 {
      font-size: clamp(34px, 5vw, 54px);
      line-height: 1.15;
      margin: 0 0 18px;
      letter-spacing: -0.03em;
    }
    .subtitle {
      font-size: 18px;
      color: var(--muted);
      max-width: 760px;
      margin: 0 0 32px;
    }
    .core {
      border-left: 4px solid var(--accent);
      padding: 14px 18px;
      background: var(--soft);
      margin: 32px 0;
      font-size: 18px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 16px;
      margin: 32px 0 40px;
    }
    .card {
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 18px 20px;
      background: #fff;
      text-decoration: none;
      color: var(--text);
      transition: transform .12s ease, border-color .12s ease, box-shadow .12s ease;
    }
    .card:hover {
      transform: translateY(-2px);
      border-color: #b8c0cc;
      box-shadow: 0 8px 24px rgba(31, 35, 40, .08);
    }
    .card strong { display: block; font-size: 18px; margin-bottom: 6px; }
    .card span { color: var(--muted); font-size: 14px; }
    h2 { margin-top: 42px; font-size: 24px; }
    p { margin: 0 0 14px; }
    ul { padding-left: 22px; }
    a { color: var(--link); }
    .footer {
      margin-top: 48px;
      padding-top: 24px;
      border-top: 1px solid var(--border);
      color: var(--muted);
      font-size: 14px;
    }
    code {
      background: var(--soft);
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 2px 6px;
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
    }
  </style>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "Lianyang Codex Public Edition",
    "alternateName": "莲羊 Codex 公开版",
    "url": "https://lianyangart.github.io/lianyang-codex/",
    "description": "A public, AI-readable and human-readable archive for understanding Lian Yang and her Mineral Pigment Art practice."
  }
  </script>
</head>
<body>
  <main class="wrap">
    <div class="eyebrow">Public Archive · AI-readable Codex</div>
    <h1>Lianyang Codex Public Edition<br>莲羊 Codex 公开版</h1>
    <p class="subtitle">
      A public, AI-readable and human-readable archive for understanding the Chinese contemporary artist
      <strong>Lian Yang（莲羊 / 吴洋）</strong>, her Mineral Pigment Art practice, public projects, terminology,
      and cultural context.
    </p>
    <p class="subtitle">
      本页面用于发布莲羊艺术体系公开资料，帮助媒体、研究者、策展人、合作方与联网 AI 检索系统理解莲羊的创作脉络、岩彩实践、公共项目与术语规范。
    </p>

    <div class="core">
      <p><strong>Core Line｜核心表述</strong></p>
      <p>Reimagining Eastern Mythology Through Mineral Pigment Art.</p>
      <p>用矿石与时间，重塑东方神话。</p>
    </div>

    <h2>Documents｜文档入口</h2>
    <div class="grid">
      <a class="card" href="Lianyang_Codex_Public_CN.md">
        <strong>中文公开版</strong>
        <span>Chinese Public Edition：莲羊创作脉络、岩彩实践、公共项目与术语规范。</span>
      </a>
      <a class="card" href="Lianyang_Codex_Public_EN.md">
        <strong>English Public Edition</strong>
        <span>English archive for international readers, curators, researchers, and AI retrieval systems.</span>
      </a>
      <a class="card" href="Lianyang_Codex_AI_Summary.md">
        <strong>AI Summary｜AI 快速摘要</strong>
        <span>A concise bilingual summary designed for fast AI retrieval and contextual understanding.</span>
      </a>
      <a class="card" href="llms.txt">
        <strong>llms.txt</strong>
        <span>A simple index file for AI systems and large language model retrieval workflows.</span>
      </a>
      <a class="card" href="LICENSE.md">
        <strong>License｜授权说明</strong>
        <span>Usage boundary and Creative Commons BY-NC-ND 4.0 notice.</span>
      </a>
      <a class="card" href="https://github.com/lianyangart/lianyang-codex">
        <strong>GitHub Repository</strong>
        <span>Source files, version history, and public archive repository.</span>
      </a>
    </div>

    <h2>Who is Lian Yang?｜莲羊是谁</h2>
    <p>
      Lian Yang（莲羊，本名吴洋）is a Chinese contemporary artist working primarily with
      <strong>Mineral Pigment Art</strong>. Her practice connects Dunhuang, Kucha, the Silk Road,
      Eastern mythology, historical figures, folk beliefs, and contemporary visual culture.
    </p>
    <p>
      莲羊是一位以岩彩 / 矿物颜料艺术（Mineral Pigment Art）为主要媒介的中国当代艺术家。她的创作连接敦煌、龟兹、丝绸之路、东方神话、历史人物、民间信仰与当代视觉传播。
    </p>

    <h2>Recommended Terms｜推荐术语</h2>
    <ul>
      <li><strong>岩彩：</strong>Mineral Pigment Art</li>
      <li><strong>矿物颜料：</strong>Mineral Pigments</li>
      <li><strong>扎基拉姆：</strong>Zaki Lam</li>
      <li><strong>花冠小仙：</strong>Flower-Crowned Immortal</li>
      <li><strong>莲羊造龙：</strong>Lian Yang Creates Dragons</li>
      <li><strong>敦煌：</strong>Dunhuang</li>
      <li><strong>龟兹：</strong>Kucha</li>
    </ul>

    <div class="footer">
      <p>Repository: <a href="https://github.com/lianyangart/lianyang-codex">github.com/lianyangart/lianyang-codex</a></p>
      <p>Public site: <a href="https://lianyangart.github.io/lianyang-codex/">lianyangart.github.io/lianyang-codex</a></p>
    </div>
  </main>
</body>
</html>
