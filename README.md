<!-- ============================================================
     STARRY NIGHT — deveshdevfauzdar/README.md
     palette: cobalt #1a3a6b · midnight #0a0e27 · gold #f0c040
              sky-blue #7ec8e3 · cream #e8d5a3 · swirl #2255a4
     ============================================================ -->

<div align="center">

<!-- ── ANIMATED HEADER ─────────────────────────────────────── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=280&color=0:0a0e27,20:0d1540,45:1a3a6b,70:2255a4,100:0a0e27&text=Devesh%20Dev%20Fauzdar&fontSize=46&fontColor=f0c040&fontAlignY=52&desc=∿%20frontend%20engineer%20%C2%B7%20ml%20practitioner%20%C2%B7%20ai%20systems%20builder%20∿&descSize=15&descColor=7ec8e3&descAlignY=70&animation=fadeIn&stroke=f0c040&strokeWidth=1"/>

<!-- ── TYPING TAGLINE ────────────────────────────────────────── -->
<br/>

<img src="https://readme-typing-svg.demolab.com?font=Cormorant+Garamond&weight=600&size=24&pause=1400&color=F0C040&background=00000000&center=true&vCenter=true&width=680&height=55&lines=I+build+things+at+the+edge+of+math+%26+design;LLM+agents+that+actually+work;Next.js+%C2%B7+TypeScript+%C2%B7+Tailwind+%C2%B7+Three.js;data+tells+a+story+%E2%80%94+I+help+it+speak;turning+prompts+into+reliable+systems" />

<br/><br/>

<!-- ── SWIRLING DIVIDER SVG ─────────────────────────────────── -->
<svg width="700" height="30" viewBox="0 0 700 30" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,15 Q87.5,0 175,15 Q262.5,30 350,15 Q437.5,0 525,15 Q612.5,30 700,15"
        stroke="#2255a4" stroke-width="2" fill="none" opacity="0.8"/>
  <path d="M0,15 Q87.5,5 175,15 Q262.5,25 350,15 Q437.5,5 525,15 Q612.5,25 700,15"
        stroke="#f0c040" stroke-width="1" fill="none" opacity="0.5"/>
  <circle cx="175" cy="15" r="3" fill="#f0c040" opacity="0.9"/>
  <circle cx="350" cy="15" r="3" fill="#7ec8e3" opacity="0.9"/>
  <circle cx="525" cy="15" r="3" fill="#f0c040" opacity="0.9"/>
</svg>

</div>

<br/>

<!-- ══════════════════════════════════════════════════════════
     ABOUT
═══════════════════════════════════════════════════════════ -->

<table border="0" align="center" width="90%">
<tr>
<td width="58%" valign="top">

### `~$ whoami`

Dual-degree student at **IIT Madras** (Data Science) and **University of Delhi** (Mathematics). I live at the intersection of systems that *think* and interfaces that *feel*.

I build frontend products people enjoy using, train models on data that matters, and engineer LLM agents that don't hallucinate nonsense. Strong opinions on clean architecture and honest design.

When I'm not doing any of that — astronomy, robotics, or something that has nothing to do with a screen.

<br/>

```python
devesh = {
  "currently_building": "things I can't shut up about",
  "obsessing_over":     ["LLM agent reliability", "WebGL shaders"],
  "open_to":            "collabs, ideas, interesting problems",
  "fun_fact":           "Van Gogh painted Starry Night in an asylum"
}
```

</td>
<td width="42%" align="center" valign="middle">

<!-- Starry night SVG constellation -->
<svg width="280" height="260" viewBox="0 0 280 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="sky" cx="50%" cy="40%" r="60%">
      <stop offset="0%" stop-color="#2255a4" stop-opacity="1"/>
      <stop offset="100%" stop-color="#0a0e27" stop-opacity="1"/>
    </radialGradient>
    <radialGradient id="moon" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#fffde0"/>
      <stop offset="60%" stop-color="#f0c040"/>
      <stop offset="100%" stop-color="#c8960a"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .swirl { animation: rotate 12s linear infinite; transform-origin: 140px 100px; }
      .star  { animation: twinkle 2s ease-in-out infinite alternate; }
      .s2    { animation-delay: 0.5s; }
      .s3    { animation-delay: 1.1s; }
      .s4    { animation-delay: 0.3s; }
      .s5    { animation-delay: 1.7s; }
      @keyframes twinkle {
        from { opacity: 0.4; r: 2px; }
        to   { opacity: 1;   r: 3.5px; }
      }
      @keyframes rotate {
        from { transform: rotate(0deg); }
        to   { transform: rotate(360deg); }
      }
    </style>
  </defs>

  <!-- sky bg -->
  <rect width="280" height="260" rx="16" fill="url(#sky)"/>

  <!-- swirl strokes (Van Gogh brushwork) -->
  <g opacity="0.35">
    <path d="M20,80 Q60,50 100,80 Q140,110 180,80 Q220,50 260,80" stroke="#7ec8e3" stroke-width="8" fill="none" stroke-linecap="round"/>
    <path d="M10,110 Q70,85 130,110 Q190,135 250,110" stroke="#2255a4" stroke-width="10" fill="none" stroke-linecap="round"/>
    <path d="M0,140 Q80,115 140,140 Q200,165 280,140" stroke="#7ec8e3" stroke-width="7" fill="none" stroke-linecap="round"/>
    <path d="M15,60 Q55,35 95,60 Q135,85 175,60" stroke="#a8c5da" stroke-width="6" fill="none" stroke-linecap="round"/>
  </g>

  <!-- moon -->
  <circle cx="210" cy="55" r="32" fill="url(#moon)" filter="url(#glow)" opacity="0.95"/>
  <circle cx="210" cy="55" r="38" fill="none" stroke="#f0c040" stroke-width="1.5" opacity="0.4"/>

  <!-- stars -->
  <circle class="star"    cx="50"  cy="45"  r="3"   fill="#fffde0" filter="url(#glow)"/>
  <circle class="star s2" cx="90"  cy="30"  r="2.5" fill="#f0c040" filter="url(#glow)"/>
  <circle class="star s3" cx="155" cy="40"  r="2"   fill="#fffde0" filter="url(#glow)"/>
  <circle class="star s4" cx="30"  cy="120" r="2"   fill="#7ec8e3" filter="url(#glow)"/>
  <circle class="star s5" cx="130" cy="25"  r="2.5" fill="#fffde0" filter="url(#glow)"/>
  <circle class="star"    cx="70"  cy="95"  r="1.5" fill="#f0c040" filter="url(#glow)"/>
  <circle class="star s2" cx="240" cy="100" r="1.5" fill="#fffde0" filter="url(#glow)"/>

  <!-- cypress tree (Van Gogh signature element) -->
  <ellipse cx="55" cy="200" rx="18" ry="60" fill="#1a2a0a" opacity="0.9"/>
  <ellipse cx="55" cy="175" rx="12" ry="40" fill="#243810" opacity="0.7"/>

  <!-- village silhouette -->
  <rect x="100" y="220" width="180" height="40" fill="#0a0e27" opacity="0.8"/>
  <polygon points="155,200 170,220 140,220" fill="#1a2a40" opacity="0.9"/>
  <rect x="195" y="210" width="20" height="30" fill="#1a2a40" opacity="0.9"/>
  <rect x="225" y="215" width="15" height="25" fill="#1a2a40" opacity="0.9"/>

  <!-- name tag -->
  <text x="140" y="252" text-anchor="middle" font-family="Georgia, serif" font-size="10" fill="#7ec8e3" opacity="0.7">∿ the night is alive ∿</text>
</svg>

</td>
</tr>
</table>

<br/>

<!-- ══════════════════════════════════════════════════════════
     WHAT I DO — 3 PILLARS
═══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="700" height="30" viewBox="0 0 700 30" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,15 Q175,3 350,15 Q525,27 700,15" stroke="#2255a4" stroke-width="1.5" fill="none"/>
  <path d="M100,15 Q250,8 350,15 Q450,22 600,15" stroke="#f0c040" stroke-width="0.8" fill="none" opacity="0.6"/>
</svg>

### what i actually do

<br/>

<table border="0" width="88%">
<tr>
<td width="33%" align="center" valign="top">

<!-- Frontend icon -->
<svg width="48" height="48" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
  <rect width="48" height="48" rx="12" fill="#0d1540"/>
  <rect x="8" y="10" width="32" height="22" rx="3" fill="none" stroke="#7ec8e3" stroke-width="1.5"/>
  <rect x="11" y="13" width="26" height="16" rx="2" fill="#1a3a6b" opacity="0.6"/>
  <line x1="24" y1="32" x2="24" y2="38" stroke="#7ec8e3" stroke-width="1.5"/>
  <line x1="17" y1="38" x2="31" y2="38" stroke="#7ec8e3" stroke-width="1.5"/>
  <polyline points="14,21 18,24 14,27" stroke="#f0c040" stroke-width="1.5" fill="none" stroke-linecap="round"/>
  <line x1="20" y1="27" x2="26" y2="27" stroke="#7ec8e3" stroke-width="1.5" stroke-linecap="round"/>
</svg>

**Frontend Engineer**

Building web experiences that feel fast and look intentional. Next.js, React, TypeScript, Three.js — from landing pages to 3D in the browser.

</td>
<td width="33%" align="center" valign="top">

<!-- ML/Data Science icon -->
<svg width="48" height="48" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
  <rect width="48" height="48" rx="12" fill="#0d1540"/>
  <circle cx="24" cy="24" r="4" fill="#f0c040"/>
  <circle cx="12" cy="16" r="3" fill="#7ec8e3" opacity="0.8"/>
  <circle cx="36" cy="16" r="3" fill="#7ec8e3" opacity="0.8"/>
  <circle cx="12" cy="32" r="3" fill="#7ec8e3" opacity="0.8"/>
  <circle cx="36" cy="32" r="3" fill="#7ec8e3" opacity="0.8"/>
  <line x1="15" y1="17" x2="21" y2="21" stroke="#2255a4" stroke-width="1.2"/>
  <line x1="33" y1="17" x2="27" y2="21" stroke="#2255a4" stroke-width="1.2"/>
  <line x1="15" y1="31" x2="21" y2="27" stroke="#2255a4" stroke-width="1.2"/>
  <line x1="33" y1="31" x2="27" y2="27" stroke="#2255a4" stroke-width="1.2"/>
  <circle cx="24" cy="24" r="8" fill="none" stroke="#f0c040" stroke-width="0.8" stroke-dasharray="3 2"/>
</svg>

**ML & Data Science**

Dual-degree in Data Science (IIT Madras) + Mathematics (DU). I work with real datasets — statistical analysis, pattern detection, Python-first.

</td>
<td width="33%" align="center" valign="top">

<!-- AI Systems icon -->
<svg width="48" height="48" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
  <rect width="48" height="48" rx="12" fill="#0d1540"/>
  <rect x="14" y="14" width="20" height="20" rx="4" fill="none" stroke="#f0c040" stroke-width="1.5"/>
  <rect x="18" y="18" width="12" height="12" rx="2" fill="#1a3a6b"/>
  <circle cx="24" cy="24" r="3" fill="#f0c040"/>
  <line x1="24" y1="8"  x2="24" y2="14" stroke="#7ec8e3" stroke-width="1.5"/>
  <line x1="24" y1="34" x2="24" y2="40" stroke="#7ec8e3" stroke-width="1.5"/>
  <line x1="8"  y1="24" x2="14" y2="24" stroke="#7ec8e3" stroke-width="1.5"/>
  <line x1="34" y1="24" x2="40" y2="24" stroke="#7ec8e3" stroke-width="1.5"/>
</svg>

**AI Systems & Automation**

Engineering LLM-based agent workflows — structured tool use, retry logic, prompt design. Making AI that doesn't break in production.

</td>
</tr>
</table>

</div>

<br/>

<!-- ══════════════════════════════════════════════════════════
     TECH STACK
═══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="700" height="30" viewBox="0 0 700 30" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,15 Q175,27 350,15 Q525,3 700,15" stroke="#2255a4" stroke-width="1.5" fill="none"/>
</svg>

### the stack

<br/>

**— languages —**

![Python](https://img.shields.io/badge/Python-0a0e27?style=for-the-badge&logo=python&logoColor=f0c040)
![TypeScript](https://img.shields.io/badge/TypeScript-0a0e27?style=for-the-badge&logo=typescript&logoColor=7ec8e3)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0e27?style=for-the-badge&logo=javascript&logoColor=f0c040)
![SQL](https://img.shields.io/badge/SQL-0a0e27?style=for-the-badge&logo=postgresql&logoColor=a8c5da)
![Java](https://img.shields.io/badge/Java-0a0e27?style=for-the-badge&logo=openjdk&logoColor=e8795a)

<br/>

**— frontend —**

![Next.js](https://img.shields.io/badge/Next.js-0a0e27?style=for-the-badge&logo=next.js&logoColor=ffffff)
![React](https://img.shields.io/badge/React-0a0e27?style=for-the-badge&logo=react&logoColor=61dafb)
![Three.js](https://img.shields.io/badge/Three.js-0a0e27?style=for-the-badge&logo=three.js&logoColor=ffffff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-0a0e27?style=for-the-badge&logo=tailwind-css&logoColor=7ec8e3)
![HTML5](https://img.shields.io/badge/HTML5-0a0e27?style=for-the-badge&logo=html5&logoColor=e8795a)
![CSS3](https://img.shields.io/badge/CSS3-0a0e27?style=for-the-badge&logo=css3&logoColor=7ec8e3)

<br/>

**— backend & data —**

![Node.js](https://img.shields.io/badge/Node.js-0a0e27?style=for-the-badge&logo=node.js&logoColor=68a063)
![FastAPI](https://img.shields.io/badge/FastAPI-0a0e27?style=for-the-badge&logo=fastapi&logoColor=00d2a0)
![LangChain](https://img.shields.io/badge/LangChain-0a0e27?style=for-the-badge&logo=chainlink&logoColor=f0c040)
![Pandas](https://img.shields.io/badge/Pandas-0a0e27?style=for-the-badge&logo=pandas&logoColor=7ec8e3)
![Jupyter](https://img.shields.io/badge/Jupyter-0a0e27?style=for-the-badge&logo=jupyter&logoColor=f0c040)

<br/>

**— tools —**

![Git](https://img.shields.io/badge/Git-0a0e27?style=for-the-badge&logo=git&logoColor=e8795a)
![Vercel](https://img.shields.io/badge/Vercel-0a0e27?style=for-the-badge&logo=vercel&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/VS_Code-0a0e27?style=for-the-badge&logo=visual-studio-code&logoColor=007acc)
![Canva](https://img.shields.io/badge/Canva-0a0e27?style=for-the-badge&logo=canva&logoColor=7ec8e3)

</div>

<br/>

<!-- ══════════════════════════════════════════════════════════
     PROJECTS
═══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="700" height="30" viewBox="0 0 700 30" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,15 Q87.5,0 175,15 Q262.5,30 350,15 Q437.5,0 525,15 Q612.5,30 700,15" stroke="#2255a4" stroke-width="1.5" fill="none"/>
  <circle cx="350" cy="15" r="3" fill="#f0c040"/>
</svg>

### things i've built

</div>

<br/>

<table border="0" align="center" width="90%">
<tr>
<td width="50%" valign="top">

**[Finwise — Fintech Landing Page](https://github.com/deveshdevfauzdar)**

Next.js · TypeScript · Tailwind CSS · Vercel

A fintech product landing page — custom UI components, fluid animations, fully responsive. Built to look like a real product, not a template.

---

**[Trader Behavior & Sentiment Analysis](https://github.com/deveshdevfauzdar)**

Python · Pandas · Matplotlib · Jupyter

Analyzed trader performance patterns against Bitcoin market sentiment across bull/bear cycles. Statistical correlation, behavioral clustering, clean visualizations.

</td>
<td width="50%" valign="top">

**[Kaprekar Constant — Convergence Study](https://github.com/deveshdevfauzdar)**

Python · Mathematics · Data Analysis

Computational study of the Kaprekar routine — convergence behavior, statistical properties, edge cases. Published as a research article.

---

**[Leaf Plate Revival — Sustainability Initiative](https://github.com/deveshdevfauzdar)**

Research · Leadership · Outreach

Led a biodegradable tableware initiative across 250+ local eateries. Submitted under UNESCO × Nestlé Global Youth Grant Scheme.

</td>
</tr>
</table>

<br/>

<!-- ══════════════════════════════════════════════════════════
     CONNECT
═══════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="700" height="30" viewBox="0 0 700 30" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,15 Q175,3 350,15 Q525,27 700,15" stroke="#2255a4" stroke-width="1.5" fill="none"/>
  <circle cx="175" cy="9" r="2.5" fill="#7ec8e3"/>
  <circle cx="525" cy="21" r="2.5" fill="#7ec8e3"/>
</svg>

### reach out

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a0e27?style=for-the-badge&logo=linkedin&logoColor=7ec8e3&label=devesh-dev-fauzdar)](https://linkedin.com/in/devesh-dev-fauzdar-3ab06b395)
[![GitHub](https://img.shields.io/badge/GitHub-0a0e27?style=for-the-badge&logo=github&logoColor=ffffff&label=deveshdevfauzdar)](https://github.com/deveshdevfauzdar)
[![Email](https://img.shields.io/badge/Gmail-0a0e27?style=for-the-badge&logo=gmail&logoColor=e8795a&label=devesh.d.fauzdar)](mailto:devesh.d.fauzdar@gmail.com)

<br/><br/>

<!-- ── FOOTER WAVE ────────────────────────────────────────── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0a0e27,40:1a3a6b,70:2255a4,100:0a0e27&section=footer"/>

<br/>

<!-- swirling footer text -->
<img src="https://readme-typing-svg.demolab.com?font=Cormorant+Garamond&weight=400&size=14&pause=3000&color=2255A4&background=00000000&center=true&vCenter=true&width=500&height=30&lines=%E2%80%9CI+dream+of+painting+and+then+I+paint+my+dream.%E2%80%9D+%E2%80%94+Van+Gogh" />

</div>

<!--
  built with brushstrokes, not a template.
  feel free to reach out — always happy to collab.
-->
