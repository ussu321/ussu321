<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    👻  GHOST HEADER BANNER  👻                 -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="ghostGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1">
        <animate attributeName="stop-color" values="#667eea;#764ba2;#f093fb;#667eea" dur="5s" repeatCount="indefinite" />
      </stop>
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1">
        <animate attributeName="stop-color" values="#764ba2;#f093fb;#667eea;#764ba2" dur="5s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1">
        <animate attributeName="stop-color" values="#f093fb;#667eea;#764ba2;#f093fb" dur="5s" repeatCount="indefinite" />
      </stop>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="strongGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background with animated gradient -->
  <rect width="800" height="220" fill="#0d1117" rx="20"/>

  <!-- Animated background particles -->
  <circle cx="100" cy="50" r="2" fill="#667eea" opacity="0.6">
    <animate attributeName="cy" values="50;180;50" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0;0.6" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="180" r="2" fill="#764ba2" opacity="0.6">
    <animate attributeName="cy" values="180;40;180" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0;0.6" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="300" cy="30" r="1.5" fill="#f093fb" opacity="0.5">
    <animate attributeName="cy" values="30;190;30" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="300;500;300" dur="8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="100" r="1" fill="#667eea" opacity="0.4">
    <animate attributeName="cy" values="100;20;100" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="600;200;600" dur="9s" repeatCount="indefinite"/>
  </circle>

  <!-- Floating Ghosts -->
  <g filter="url(#glow)">
    <text x="120" y="130" font-size="55" fill="url(#ghostGrad)">👻
      <animate attributeName="y" values="130;100;130" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="x" values="120;140;120" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
    </text>
    <text x="620" y="110" font-size="45" fill="url(#ghostGrad)">👻
      <animate attributeName="y" values="110;80;110" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="x" values="620;600;620" dur="3.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.9;0.5" dur="2.5s" repeatCount="indefinite"/>
    </text>
    <text x="50" y="80" font-size="30" fill="url(#ghostGrad)">👻
      <animate attributeName="y" values="80;60;80" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0.7;0.3" dur="2s" repeatCount="indefinite"/>
    </text>
    <text x="720" y="160" font-size="35" fill="url(#ghostGrad)">👻
      <animate attributeName="y" values="160;130;160" dur="3.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.5s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Main Title -->
  <text x="400" y="100" font-family="monospace" font-size="44" font-weight="bold" fill="#e6edf3" text-anchor="middle" filter="url(#strongGlow)">
    U S S U  3 2 1
  </text>

  <!-- Glitch effect subtitle -->
  <text x="400" y="145" font-family="monospace" font-size="16" fill="#8b949e" text-anchor="middle">
    <tspan>👻 Ghost in the Machine | Full Stack Developer | Cyber Security Enthusiast 👻</tspan>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- Animated status line -->
  <line x1="180" y1="175" x2="620" y2="175" stroke="url(#ghostGrad)" stroke-width="2" stroke-linecap="round">
    <animate attributeName="x1" values="180;220;180" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="620;580;620" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="stroke-width" values="2;4;2" dur="2s" repeatCount="indefinite"/>
  </line>

  <!-- Terminal-style status -->
  <text x="400" y="200" font-family="monospace" font-size="12" fill="#667eea" text-anchor="middle">
    <tspan>[</tspan><tspan fill="#764ba2">root@ussu321</tspan><tspan>]</tspan><tspan fill="#e6edf3"> ~ $ ./haunt_the_internet.sh</tspan>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
  </text>
</svg>

<br>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    ANIMATED WAVE DIVIDER                        -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<svg width="100%" height="60" viewBox="0 0 1200 60" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,30 Q150,5 300,30 T600,30 T900,30 T1200,30" fill="none" stroke="#667eea" stroke-width="2.5" opacity="0.8">
    <animate attributeName="d" 
      values="M0,30 Q150,5 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,55 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,5 300,30 T600,30 T900,30 T1200,30" 
      dur="3s" repeatCount="indefinite"/>
  </path>
  <path d="M0,30 Q150,55 300,30 T600,30 T900,30 T1200,30" fill="none" stroke="#764ba2" stroke-width="2" opacity="0.5">
    <animate attributeName="d" 
      values="M0,30 Q150,55 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,5 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,55 300,30 T600,30 T900,30 T1200,30" 
      dur="3s" repeatCount="indefinite"/>
  </path>
  <path d="M0,30 Q150,20 300,30 T600,30 T900,30 T1200,30" fill="none" stroke="#f093fb" stroke-width="1.5" opacity="0.3">
    <animate attributeName="d" 
      values="M0,30 Q150,20 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,40 300,30 T600,30 T900,30 T1200,30;
              M0,30 Q150,20 300,30 T600,30 T900,30 T1200,30" 
      dur="2.5s" repeatCount="indefinite"/>
  </path>
</svg>

</div>

---

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    TYPING ANIMATION BANNER                      -->
<!-- ═══════════════════════════════════════════════════════════════ -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=667EEA&center=true&vCenter=true&width=800&lines=Welcome+to+my+Haunted+Repository!;I+am+Ussu321+%F0%9F%91%BB;Full+Stack+Developer+%F0%9F%92%BB;Cyber+Security+Expert+%F0%9F%94%90;Open+Source+Contributor+%E2%9C%A8;Always+Learning+New+Spells+%F0%9F%93%9A)](https://git.io/typing-svg)

</div>

---

## 👻 About Me

> *"I am the ghost that haunts the code, leaving behind elegant solutions and mysterious bugs..."* 👻✨

Hello there, wanderer of the digital realm! I am **Ussu** ( **`ussu321`** ), a phantom developer who materializes between the shadows of **frontend** and **backend** architectures. By day, I craft spellbinding applications; by night, I hunt vulnerabilities in the cyber wilderness.

<div align="center">

<!-- Terminal-style info box -->
<svg width="90%" height="280" viewBox="0 0 700 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e"/>
      <stop offset="100%" style="stop-color:#16213e"/>
    </linearGradient>
  </defs>

  <!-- Terminal window -->
  <rect width="700" height="280" fill="url(#termGrad)" rx="12" stroke="#667eea" stroke-width="2"/>

  <!-- Window controls -->
  <circle cx="25" cy="20" r="6" fill="#ff5f56"/>
  <circle cx="45" cy="20" r="6" fill="#ffbd2e"/>
  <circle cx="65" cy="20" r="6" fill="#27c93f"/>

  <!-- Terminal title -->
  <text x="350" y="24" font-family="monospace" font-size="12" fill="#8b949e" text-anchor="middle">ussu321@kali-linux: ~/ghost-profile</text>

  <!-- Terminal content -->
  <text x="20" y="55" font-family="monospace" font-size="13" fill="#667eea">
    <tspan x="20" dy="0">$ neofetch</tspan>
  </text>

  <text x="20" y="80" font-family="monospace" font-size="13" fill="#e6edf3">
    <tspan x="20" dy="0">👤 Name:        Ussu (ussu321)</tspan>
    <tspan x="20" dy="22">💻 Role:        Full Stack Developer & Security Researcher</tspan>
    <tspan x="20" dy="22">🐧 OS:          Kali Linux / Windows 11 Dual Boot</tspan>
    <tspan x="20" dy="22">🐍 Languages:   Python, JavaScript, Go, Rust, Bash</tspan>
    <tspan x="20" dy="22">🔮 Focus:       AI, Cyber Security, Open Source</tspan>
    <tspan x="20" dy="22">⚡ Fun Fact:     I debug code faster than coffee brews ☕</tspan>
  </text>

  <text x="20" y="245" font-family="monospace" font-size="13" fill="#667eea">
    <tspan x="20" dy="0">$ <tspan fill="#764ba2" font-weight="bold">_</tspan></tspan>
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </text>
</svg>

</div>

<br>

🌙 **Current Haunting Grounds:**
- 🔭 I’m currently working on **next-generation security tools** and **AI-powered applications**
- 🌱 I’m currently learning **Rust, Blockchain Security, and Advanced ML**
- 👯 I’m looking to collaborate on **open-source security projects**
- 🤔 I’m looking for help with **distributed systems architecture**
- 💬 Ask me about **Python, JavaScript, Ethical Hacking, or Linux**
- ⚡ Fun fact: *I can debug code faster than most people can brew coffee* ☕👻

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    GHOST DIVIDER                               -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<svg width="400" height="50" viewBox="0 0 400 50" xmlns="http://www.w3.org/2000/svg">
  <text x="80" y="35" font-size="30" fill="#667eea">👻
    <animate attributeName="y" values="35;20;35" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
  </text>
  <text x="150" y="35" font-size="25" fill="#764ba2">⭐
    <animate attributeName="y" values="35;25;35" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="200" y="35" font-size="30" fill="#667eea">👻
    <animate attributeName="y" values="35;20;35" dur="2.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2.2s" repeatCount="indefinite"/>
  </text>
  <text x="270" y="35" font-size="25" fill="#764ba2">⭐
    <animate attributeName="y" values="35;25;35" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.8s" repeatCount="indefinite"/>
  </text>
  <text x="320" y="35" font-size="30" fill="#667eea">👻
    <animate attributeName="y" values="35;20;35" dur="1.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="1.8s" repeatCount="indefinite"/>
  </text>
</svg>

</div>

---

## 🔮 Tech Stack & Phantom Powers

<div align="center">

### 👻 Languages & Frameworks 👻

<p>
  <img src="https://skillicons.dev/icons?i=python,javascript,typescript,go,rust,bash,c,cpp,java,html,css,react,nextjs,nodejs,express,django,flask,fastapi,tailwind,scss&theme=dark&perline=10" />
</p>

### 🔮 Databases & Cloud 🔮

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,postgresql,mysql,redis,sqlite,aws,gcp,azure,docker,kubernetes,nginx,linux,kali,git,github,gitlab,vscode,vim,neovim&theme=dark&perline=10" />
</p>

</div>

---

## 🔥 GitHub Stats & Spectral Activity

<div align="center">

<!-- GitHub Stats with Ghost Theme -->
<img src="https://github-readme-stats.vercel.app/api?username=ussu321&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=667eea&icon_color=764ba2&text_color=e6edf3&ring_color=667eea&fire_color=764ba2" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ussu321&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=667eea&icon_color=764ba2&text_color=e6edf3" width="49%" />

<br><br>

<!-- Streak Stats -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ussu321&theme=midnight-purple&hide_border=true&background=0d1117&stroke=667eea&ring=764ba2&fire=667eea&currStreakNum=e6edf3&sideNums=e6edf3&currStreakLabel=667eea&sideLabels=667eea&dates=8b949e" width="80%" />

<br><br>

<!-- Trophy Case -->
<img src="https://github-profile-trophy.vercel.app/?username=ussu321&theme=discord&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7" width="100%" />

</div>

---

## ✨ Featured Haunted Projects

<div align="center">

<!-- Project Cards with Ghost Theme -->
<a href="https://github.com/ussu321">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ussu321&repo=AI-Code-Reviewer&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=667eea&icon_color=764ba2&text_color=e6edf3" />
</a>
<a href="https://github.com/ussu321">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ussu321&repo=Jarvis-AI-Assistant&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=667eea&icon_color=764ba2&text_color=e6edf3" />
</a>

</div>

---

## 🔮 Activity Graph & Contribution Map

<div align="center">

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ussu321&theme=midnight-purple&hide_border=true&bg_color=0d1117&color=667eea&line=764ba2&point=e6edf3&area=true&area_color=667eea" width="100%" />

<br><br>

<!-- Snake Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ussu321/ussu321/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ussu321/ussu321/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/ussu321/ussu321/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

## 🌌 Connect With The Spirit Realm

<div align="center">

<!-- Social Links with Ghost Theme -->
<a href="https://github.com/ussu321" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-ussu321-667eea?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://github.com/ussu321" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-Coming%20Soon-764ba2?style=for-the-badge&logo=firefox&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://github.com/ussu321" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-667eea?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://github.com/ussu321" target="_blank">
  <img src="https://img.shields.io/badge/Twitter-Follow-764ba2?style=for-the-badge&logo=twitter&logoColor=white&labelColor=0d1117" />
</a>
<a href="https://github.com/ussu321" target="_blank">
  <img src="https://img.shields.io/badge/Discord-Join%20Server-667eea?style=for-the-badge&logo=discord&logoColor=white&labelColor=0d1117" />
</a>

<br><br>

<!-- Profile Views Counter -->
<img src="https://komarev.com/ghpvc/?username=ussu321&color=667eea&style=for-the-badge&label=SPECTRAL+VISITORS" />

</div>

---

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    ANIMATED FOOTER                             -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea"/>
      <stop offset="50%" style="stop-color:#764ba2"/>
      <stop offset="100%" style="stop-color:#f093fb"/>
    </linearGradient>
    <filter id="footerGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="800" height="180" fill="#0d1117" rx="20" stroke="#667eea" stroke-width="2"/>

  <!-- Floating ghost emojis -->
  <text x="180" y="85" font-size="40" fill="#667eea" filter="url(#footerGlow)">👻
    <animate attributeName="y" values="85;65;85" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="x" values="180;200;180" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
  </text>

  <text x="580" y="95" font-size="35" fill="#764ba2" filter="url(#footerGlow)">👻
    <animate attributeName="y" values="95;75;95" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="x" values="580;560;580" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.9;0.5" dur="2.5s" repeatCount="indefinite"/>
  </text>

  <!-- Footer Text -->
  <text x="400" y="85" font-family="monospace" font-size="24" fill="url(#footerGrad)" text-anchor="middle" font-weight="bold" filter="url(#footerGlow)">
    Thanks for visiting my haunted profile!
  </text>

  <text x="400" y="115" font-family="monospace" font-size="14" fill="#8b949e" text-anchor="middle">
    May your code be bug-free and your deployments always green 🟢
  </text>

  <text x="400" y="140" font-family="monospace" font-size="13" fill="#667eea" text-anchor="middle">
    ⭐ Star my repos if they spooked you in a good way! ⭐
  </text>

  <!-- Animated dots -->
  <circle cx="350" cy="155" r="3" fill="#667eea">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="155" r="3" fill="#764ba2">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="155" r="3" fill="#f093fb">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>

<br>

<!-- Waving goodbye -->
<svg width="200" height="60" viewBox="0 0 200 60" xmlns="http://www.w3.org/2000/svg">
  <text x="50" y="40" font-size="35">👋
    <animate attributeName="y" values="40;30;40" dur="1s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="-10 50 40; 10 50 40; -10 50 40" dur="1s" repeatCount="indefinite"/>
  </text>
  <text x="100" y="40" font-size="35">👻
    <animate attributeName="y" values="40;25;40" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;1;0.7" dur="1.5s" repeatCount="indefinite"/>
  </text>
  <text x="150" y="40" font-size="35">👋
    <animate attributeName="y" values="40;30;40" dur="1s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="rotate" values="10 150 40; -10 150 40; 10 150 40" dur="1s" repeatCount="indefinite"/>
  </text>
</svg>

<br>

**Made with 👻, 💜, and lots of caffeine by [Ussu321](https://github.com/ussu321)**

</div>
