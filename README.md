<!-- BATMAN THEME PROFILE V2 -->
<div align="center">

<svg width="100%" height="450" viewBox="0 0 800 450" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Dark Gotham Gradient -->
    <linearGradient id="gothamNight" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#050505;stop-opacity:1" />
      <stop offset="80%" style="stop-color:#111111;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0b0d12;stop-opacity:1" />
    </linearGradient>
    
    <!-- Glitch Filter for text -->
    <filter id="glitch">
       <feTurbulence type="fractalNoise" baseFrequency="0.01 0.001" numOctaves="1" result="warp" />
       <feDisplacementMap xChannelSelector="R" yChannelSelector="G" scale="10" in="SourceGraphic" in2="warp" />
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#gothamNight)"/>

  <!-- ANIMATED RAIN EFFECT (Multiple layers for depth) -->
  <g stroke="#404040" stroke-width="1" opacity="0.4">
    <line x1="50" y1="-50" x2="50" y2="0"><animate attributeName="y1" from="-50" to="500" dur="0.8s" repeatCount="indefinite"/><animate attributeName="y2" from="0" to="550" dur="0.8s" repeatCount="indefinite"/></line>
    <line x1="250" y1="-80" x2="250" y2="-20"><animate attributeName="y1" from="-80" to="500" dur="1.2s" repeatCount="indefinite"/><animate attributeName="y2" from="-20" to="560" dur="1.2s" repeatCount="indefinite"/></line>
    <line x1="450" y1="-30" x2="450" y2="20"><animate attributeName="y1" from="-30" to="500" dur="0.9s" repeatCount="indefinite"/><animate attributeName="y2" from="20" to="550" dur="0.9s" repeatCount="indefinite"/></line>
    <line x1="650" y1="-60" x2="650" y2="-10"><animate attributeName="y1" from="-60" to="500" dur="1.1s" repeatCount="indefinite"/><animate attributeName="y2" from="-10" to="550" dur="1.1s" repeatCount="indefinite"/></line>
    <line x1="150" y1="-90" x2="150" y2="-40"><animate attributeName="y1" from="-90" to="500" dur="1.5s" repeatCount="indefinite"/><animate attributeName="y2" from="-40" to="550" dur="1.5s" repeatCount="indefinite"/></line>
    <line x1="550" y1="-20" x2="550" y2="40"><animate attributeName="y1" from="-20" to="500" dur="0.7s" repeatCount="indefinite"/><animate attributeName="y2" from="40" to="560" dur="0.7s" repeatCount="indefinite"/></line>
  </g>

  <!-- THE BAT SIGNAL (Moving Beam) -->
  <g opacity="0.6">
    <!-- Beam -->
    <path d="M400 400 L320 50 L480 50 Z" fill="#ffd700" opacity="0.15">
      <animate attributeName="d" values="M400 400 L320 50 L480 50 Z; M400 400 L300 80 L460 80 Z; M400 400 L340 40 L500 40 Z; M400 400 L320 50 L480 50 Z" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.1;0.2;0.1" dur="3s" repeatCount="indefinite"/>
    </path>
    <!-- Cloud Haze -->
    <ellipse cx="400" cy="50" rx="100" ry="30" fill="#fff" opacity="0.1" filter="url(#glitch)"/>
    <!-- Bat Logo in Sky -->
    <path fill="#000" d="M355 50 Q380 15 400 50 Q420 15 445 50 L425 40 L400 70 L375 40 Z" transform="translate(0, 0)">
       <animateTransform attributeName="transform" type="translate" values="-10 0; 10 0; -10 0" dur="6s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- BATCOMPUTER INTERFACE (Typing Text) -->
  <g font-family="Consolas, monospace" font-size="14" fill="#0f0">
    <text x="20" y="380" opacity="0.7">root@batcomputer:~$ initiate_protocol --user chahel1817</text>
    <text x="20" y="400" fill="#ffd700" font-weight="bold">
       > USER IDENTIFIED: CHAHEL TANNA
       <animate attributeName="opacity" values="0;1;1" keyTimes="0;0.1;1" dur="2s" fill="freeze"/>
    </text>
    <text x="20" y="420" fill="#fff">
       > STATUS: CODING IN THE SHADOWS...
       <animate attributeName="opacity" values="0;0;1" keyTimes="0;0.5;1" dur="3s" fill="freeze"/>
    </text>
  </g>

  <!-- Main Title -->
  <text x="50%" y="220" fill="#ffd700" font-size="40" font-family="Arial, sans-serif" font-weight="900" text-anchor="middle" stroke="#000" stroke-width="2" filter="url(#glitch)">
    CHAHEL TANNA
  </text>
  <text x="50%" y="260" fill="#ffffff" font-size="16" font-family="monospace" letter-spacing="4" text-anchor="middle" opacity="0.8">
    FULL STACK VIGILANTE
  </text>
  
  <!-- Animated Pulse Circles behind title -->
  <circle cx="400" cy="230" r="160" stroke="#ffd700" stroke-width="1" fill="none" opacity="0.3">
    <animate attributeName="r" values="160;170;160" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>

</svg>
</div>

<h1 align="center" style="color:#ffd700;">🦇 THE DARK KNIGHT OF CODE 🦇</h1>

<p align="center">
  <a href="https://github.com/chahel1817">
    <img src="https://img.shields.io/badge/MISSION-ACTIVE-000000?style=for-the-badge&logo=github&logoColor=white&color=black&border=ffd700" alt="Mission Active"/>
  </a>
  <a href="https://linkedin.com/in/chahel-tanna-87300a269/">
    <img src="https://img.shields.io/badge/COMMS-ESTABLISHED-0077b5?style=for-the-badge&logo=linkedin&logoColor=white&color=05070d&labelColor=0077B5" alt="LinkedIn"/>
  </a>
  <a href="mailto:chahel1817@gmail.com">
    <img src="https://img.shields.io/badge/SIGNAL-SEND_EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=black" alt="Email"/>
  </a>
</p>

---

## 🖥️ THE UTILITY BELT (Tech Stack)

<div align="center">

<!-- SCRIPTING & CORE -->
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=F7DF1E"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=3776AB&color=1a1a1a"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=00599C&color=1a1a1a"/>

<!-- FRONTEND -->
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=61DAFB"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=E34F26&color=1a1a1a"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=1572B6&color=1a1a1a"/>

<!-- BACKEND & DB -->
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=339933&color=1a1a1a"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white&labelColor=000000&color=333"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=47A248&color=1a1a1a"/>

<!-- TOOLS -->
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=F05032&color=1a1a1a"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white&labelColor=FF6C37&color=1a1a1a"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>

</div>

---

## 🗂️ CLASSIFIED CASE FILES

### 🔦 [PROJECT: VIVAMATE](https://github.com/chahel1817/VivaMate)
> **Clearance Level: TOP SECRET**  
> An AI-powered interrogation unit (Interview Simulator) designed to test the resolve of recruits.  
> **Tech:** MERN Stack, OpenRouter Neural Net, Real-time AV Analysis.

### 🎯 [PROJECT: EDUTRACK](https://github.com/chahel1817/EduTrack)
> **Clearance Level: RESTRICTED**  
> A tactical performance monitoring system for tracking skill acquisition and field readiness.  
> **Tech:** Node.js, REST Analytics, MongoDB Archives.

---

## 🦇 GOTHAM ANALYTICS

<div align="center">

<!-- Custom Colored Stats Card to match Batman Theme (Gold/Black) -->
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api?username=chahel1817&show_icons=true&bg_color=050505&title_color=ffd700&text_color=ffffff&icon_color=ffd700&border_color=333333&hide_border=false" height="180" alt="stats" />
</a>

<!-- Custom Colored Top Langs Card -->
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chahel1817&layout=compact&bg_color=050505&title_color=ffd700&text_color=ffffff&icon_color=ffd700&border_color=333333&hide_border=false" height="180" alt="languages" />
</a>

</div>

<br/>

<div align="center">
  <!-- Streak Stats (Gold Theme) -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chahel1817&background=050505&ring=ffd700&fire=ffd700&currStreakNum=ffffff&currStreakLabel=ffd700&sideNums=ffffff&sideLabels=ffffff&border=333333" alt="streak" />
</div>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=050505&height=100&section=footer&text=GOTHAM%20NEEDS%20CODE&fontSize=20&fontColor=ffd700&fontAlignY=40" width="100%"/>
</p>
