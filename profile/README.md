<!-- ─────────────  C R E A T O R S • A I • L A B  README (v3)  ───────────── -->
<!-- 100 % asset-free: one file, all inline SVG / HTML that GitHub allows.   -->
<!-- GitHub sanitiser **removes most CSS**, but inline SVG attributes stay.  -->

<!-- 1 ░░░  HERO BANNER  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->
<p align="center">
  <!-- 1200×180 SVG with gradient + fractal grain -->
  <svg viewBox="0 0 1200 180" width="100%" height="180" preserveAspectRatio="none">
    <defs>
      <linearGradient id="pgrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#ffd6e6"/>
        <stop offset="30%"  stop-color="#cfe8ff"/>
        <stop offset="55%"  stop-color="#ffe4c8"/>
        <stop offset="80%"  stop-color="#dfffe7"/>
        <stop offset="100%" stop-color="#ffd6e6"/>
      </linearGradient>
      <!-- grain filter -->
      <filter id="grain" x="-20%" y="-20%" width="140%" height="140%">
        <feTurbulence type="fractalNoise" baseFrequency="0.8" numOctaves="4" result="noise"/>
        <feComposite operator="in" in="noise" in2="SourceGraphic"/>
        <feBlend in="SourceGraphic" in2="noise" mode="multiply" />
      </filter>
    </defs>
    <rect width="1200" height="180" fill="url(#pgrad)" filter="url(#grain)" />
  </svg>
</p>

<!-- 2 ░░░  LOGOTYPE (SVG so gradient text survives sanitiser)  ░░░░░░░░░░ -->
<p align="center">
  <svg width="560" height="90" viewBox="0 0 560 90" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="textgrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"   stop-color="#fcb4ff"/>
        <stop offset="25%"  stop-color="#b2e2ff"/>
        <stop offset="50%"  stop-color="#ffd6c2"/>
        <stop offset="75%"  stop-color="#d8ffe8"/>
        <stop offset="100%" stop-color="#fcb4ff"/>
      </linearGradient>
    </defs>
    <text x="50%" y="66%" text-anchor="middle"
          font-family="Segoe UI, Helvetica, Arial, sans-serif"
          font-size="48" font-weight="700" fill="url(#textgrad)">
      Creators AI Lab
    </text>
  </svg>
</p>

<p align="center"><em>Open-sourcing the future of creator tooling.</em></p>

<!-- 3 ░░░  ANIMATED PULSE RINGS (pure SVG SMIL)  ░░░░░░░░░░░░░░░░░ -->
<p align="center">
  <svg width="180" height="120" viewBox="0 0 180 120" fill="none">
    <circle cx="90" cy="60" r="42" stroke="#ffe2f3" stroke-width="3">
      <animate attributeName="r" dur="6s" values="42;55;42" repeatCount="indefinite"/>
    </circle>
    <circle cx="90" cy="60" r="28" stroke="#d9f1ff" stroke-width="3">
      <animate attributeName="r" begin="0.3s" dur="6s" values="28;42;28" repeatCount="indefinite"/>
    </circle>
    <circle cx="90" cy="60" r="14" stroke="#fff0dd" stroke-width="3">
      <animate attributeName="r" begin="0.6s" dur="6s" values="14;28;14" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>

<p align="center">
  <img alt="stars"
       src="https://badgen.net/github/stars/Creatorsai-Lab?color=ffd6e6&icon=github">
  <img alt="style"
       src="https://badgen.net/badge/style/pastel/cfe8ff">
  <img alt="visitors"
       src="https://visitor-badge.laobi.icu/badge?page_id=Creatorsai-Lab.creatorsai-lab&left_color=dfffe7&right_color=ffe4c8">
</p>

---

## ✨ What we’re hacking on

| Domain | Projects |
|:------:| -------- |
| **LLMs&nbsp;🧠** | **Aura-LM**, **Content-Knowledge** |
| **Media&nbsp;Gen&nbsp;🎞️** | **luffy-create**, **content-claude-skills** |
| **Agents&nbsp;🤖** | **cupid**, **neel-voice** |

> Everything ships under permissive licenses—forks & PRs welcome.

---

## 📚 Repository Gallery

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/Aura-LM">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=Aura-LM&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/content-claude-skills">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=content-claude-skills&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/luffy-create">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=luffy-create&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/cupid">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=cupid&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/neel-voice">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=neel-voice&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Creatorsai-Lab/Content-Knowledge">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=Creatorsai-Lab&repo=Content-Knowledge&theme=calm&hide_border=true&border_radius=14">
      </a>
    </td>
  </tr>
</table>

---

## 🥁 Mission

> **Empower every storyteller** with open, ethical & composable AI that amplifies creativity.

---

## 🤝 Contributing

| 👉 | How |
|----|-----|
| **Start** | Pick a `good first issue` or `help wanted` |
| **Discuss** | [GitHub Discussions](https://github.com/Creatorsai-Lab/.github/discussions) |
| **Chat** | Discord link in each repo |
| **Standards** | Conventional commits · pre-commit · SemVer |

---

<p align="center" style="font-size:0.85rem;opacity:0.65">
  © 2026 Creators AI Lab · Built with pastel dreams & plenty of caffeine ☕
</p>

<!-- ─────────────────────────────────────────────────────────────────────── -->
