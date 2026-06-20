<!-- ─────────  C R E A T O R S • A I • L A B  README (no assets)  ───────── -->

<!-- 1 ░░░   HERO BANNER (gradient + grain)   ░░░░░░░░░░░░░░░░░░░░░░░░ -->

<p align="center">
  <svg viewBox="0 0 1200 140" width="100%" height="140" preserveAspectRatio="none">
    <defs>
      <!-- Pastel rainbow -->
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#ffc8da"/>
        <stop offset="25%"  stop-color="#b2e2ff"/>
        <stop offset="50%"  stop-color="#ffd6c2"/>
        <stop offset="75%"  stop-color="#d8ffe8"/>
        <stop offset="100%" stop-color="#ffc8da"/>
      </linearGradient>

      <!-- Grain made with fractal noise -->
      <filter id="grain">
        <feTurbulence type="fractalNoise" baseFrequency="0.75" numOctaves="5" result="noise"/>
        <feComposite operator="in" in="noise" in2="SourceGraphic"/>
        <feBlend in="SourceGraphic" in2="noise" mode="multiply"/>
      </filter>
    </defs>

    <rect width="1200" height="140" fill="url(#grad)" filter="url(#grain)"/>
  </svg>
</p>

<!-- 2 ░░░   TITLE & TAGLINE   ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<h1 align="center" style="
  font-size:3.4rem;
  font-weight:800;
  margin:-84px 0 0;
  background:linear-gradient(90deg,#fcb4ff,#b2e2ff,#ffd6c2,#d8ffe8,#fcb4ff);
  -webkit-background-clip:text;
  color:transparent;">
Creators AI Lab
</h1>

<p align="center" style="font-size:1.15rem;margin-top:6px;">
  <em>Open-sourcing the future of creator tooling.</em>
</p>

<!-- 3 ░░░   ANIMATED PULSE RING (SVG SMIL)   ░░░░░░░░░░░░░░░░░░░░░░ -->

<p align="center">
  <svg width="180" height="180" viewBox="0 0 180 180" fill="none">
    <circle cx="90" cy="90" r="70" stroke="#ffe2f3" stroke-width="4">
      <animate attributeName="r" dur="5s" values="50;70;50" repeatCount="indefinite"/>
    </circle>
    <circle cx="90" cy="90" r="50" stroke="#d9f1ff" stroke-width="4">
      <animate attributeName="r" begin="0.3s" dur="5s" values="30;50;30" repeatCount="indefinite"/>
    </circle>
    <circle cx="90" cy="90" r="30" stroke="#fff0dd" stroke-width="4">
      <animate attributeName="r" begin="0.6s" dur="5s" values="12;30;12" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>

<p align="center">
  <img src="https://badgen.net/github/stars/Creatorsai-Lab?color=ffe2f3&icon=github" alt="stars">
  <img src="https://badgen.net/badge/style/pastel/b2e2ff" alt="style">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Creatorsai-Lab.creatorsai-lab&left_color=d8ffe8&right_color=ffd6c2" alt="visitors">
</p>

---

## ✨ What we’re hacking on

| Domain | Projects |
| :---: | --- |
| **LLMs&nbsp;🧠** | **Aura-LM**, **Content-Knowledge** |
| **Media&nbsp;Gen&nbsp;🎞️** | **luffy-create**, **content-claude-skills** |
| **Agents&nbsp;🤖** | **cupid**, **neel-voice** |

> Everything ships under permissive licenses—forks & PRs welcome!

---

## 📚 Repository Gallery

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/Aura-LM">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=Aura-LM&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/content-claude-skills">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=content-claude-skills&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/luffy-create">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=luffy-create&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/cupid">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=cupid&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/neel-voice">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=neel-voice&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/Content-Knowledge">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=Content-Knowledge&theme=calm&hide_border=true&border_radius=15">
      </a>
    </td>
  </tr>
</table>

---

## 🥁 Mission

> **Empower every storyteller** with open, ethical, composable AI that amplifies creativity.

---

## 🤝 Contributing

| 👉 | How |
|---|---|
| **Start** | Pick a `good first issue` or `help wanted` |
| **Discuss** | [GitHub Discussions](https://github.com/Creatorsai-Lab/.github/discussions) |
| **Chat** | Discord link in each repo |
| **Standards** | Conventional commits • pre-commit • semver |

---

<p align="center" style="font-size:0.9rem;opacity:0.6">
  © 2026 Creators AI Lab – built with pastel dreams & plenty of caffeine ☕
</p>

<!-- ───────────────────────────────────────────────────────────────────────── -->
