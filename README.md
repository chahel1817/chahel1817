<!-- BATMAN THEME README START -->
<div align="center">

<svg width="800" height="400" viewBox="0 0 800 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="skyGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#020205;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1a1c29;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Gotham Sky -->
  <rect width="100%" height="100%" fill="url(#skyGradient)"/>

  <!-- Stars -->
  <g fill="#ffffff" opacity="0.8">
    <circle cx="50" cy="50" r="1"><animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="80" r="1.5"><animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="300" cy="30" r="1"><animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="500" cy="150" r="1"><animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/></circle>
  </g>

  <!-- The Moon / Signal Source -->
  <circle cx="100" cy="80" r="40" fill="#eee" opacity="0.1" filter="url(#glow)"/>

  <!-- Bat Signal Beam -->
  <path d="M400 350 L300 50 L500 50 Z" fill="#ffd700" opacity="0.1">
    <animate attributeName="opacity" values="0.1;0.25;0.1" dur="4s" repeatCount="indefinite"/>
  </path>
  
  <!-- Cloud Projection -->
  <ellipse cx="400" cy="50" rx="80" ry="30" fill="#fff" opacity="0.05" filter="url(#glow)">
     <animate attributeName="opacity" values="0.05;0.1;0.05" dur="4s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Bat Symbol Silhouette -->
  <g transform="translate(350, 25) scale(0.2)">
     <path fill="#05070d" d="M259.5,41.4c-6.8-5.8-19.5-6.5-19.5-6.5S229.2,27,219,25.9c-8.7-0.9-19.2,1.3-19.2,1.3s-10.2,18.8-10.2,18.8
	s-15.5-2.2-27.2,3.1c-11.7,5.3-26.4,17.4-26.4,17.4s-5.3-28.7-18.8-37c-13.6-8.3-33.6-4.9-33.6-4.9s-9.8,20.4-8.7,35.5
	c0.9,13.2,9.4,32.4,9.4,32.4S60,86.1,49.5,103.1c-9.1,14.7-6.4,35.1-6.4,35.1s27.9-9.1,50.2-6.8c18.5,1.9,38.1,12.8,38.1,12.8
	s9.8-19.6,35.1-23c21.9-3,46.8,4.2,46.8,4.2s8.3-26.8,39.6-26.4c31.3,0.4,49.8,22.3,49.8,22.3s30.2-11.3,46.8-6
	c20.4,6.4,30.6,27.2,30.6,27.2s2.6-23-9.8-39.6c-13.6-18.1-41.9-24.5-41.9-24.5s9.4-19.6,9.1-32.1c-0.4-15.1-10.6-35.1-10.6-35.1
	s-20-3.4-33.6,4.9c-13.6,8.3-18.8,37-18.8,37s-14.7-12.1-26.4-17.4C267.8,42.7,259.5,41.4,259.5,41.4z"/>
  </g>

  <!-- Gotham City Skyline (Simplistic) -->
  <path d="M0 400 L0 320 L50 320 L50 280 L100 280 L100 340 L150 340 L150 300 L200 300 L200 360 L250 360 L250 250 L300 250 L300 380 L350 380 L350 300 L400 300 L400 350 L450 350 L450 220 L500 220 L500 370 L550 370 L550 290 L600 290 L600 350 L650 350 L650 270 L700 270 L700 330 L750 330 L750 380 L800 380 L800 400 Z" fill="#0d1117"/>
  
  <!-- Windows in buildings (Yellow) -->
  <g fill="#ffd700" opacity="0.6">
    <rect x="60" y="290" width="5" height="5"><animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite" begin="0.5s"/></rect>
    <rect x="260" y="260" width="5" height="5"><animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite" begin="1s"/></rect>
    <rect x="460" y="230" width="5" height="5"><animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite" begin="2s"/></rect>
    <rect x="560" y="300" width="5" height="5"><animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite" begin="0.2s"/></rect>
  </g>

  <!-- Text Overlay -->
  <text x="50%" y="30%" fill="#ffd700" font-size="28" font-family="'Segoe UI', Arial, sans-serif" font-weight="bold" text-anchor="middle" filter="url(#glow)">
    CHAHEL TANNA
  </text>
  <text x="50%" y="40%" fill="#ffffff" font-size="16" font-family="monospace" letter-spacing="2" text-anchor="middle">
    PROTECTOR OF THE SOURCE CODE
  </text>
</svg>

<br/>

<h1 align="center">🦇 Welcome to the Batcave 🦇</h1>
<p align="center">
  <em>"It's not who I am underneath, but what I <strong>code</strong> that defines me."</em>
</p>

<p align="center">
  <a href="https://github.com/chahel1817">
    <img src="https://img.shields.io/badge/Status-Operating_in_Shadows-000000?style=for-the-badge&logo=batman&logoColor=ffd700&color=05070d&labelColor=ffd700" alt="Status"/>
  </a>
  <a href="https://linkedin.com/in/chahel-tanna-87300a269/">
    <img src="https://img.shields.io/badge/Network-Encrypted_Comms-000000?style=for-the-badge&logo=linkedin&logoColor=000&color=ffd700&labelColor=05070d" alt="LinkedIn"/>
  </a>
</p>

</div>

---

### 🕵️‍♂️ Identity Profile
> **Designation:** Full Stack Developer & Computer Science Engineer  
> **Base of Operations:** Ahmedabad, Gujarat, India  
> **Mission:** Building scalable architectures, mastering the MERN stack, and securing backend systems.  

I operate in the shadows of the web, constructing robust applications and efficient algorithms. My expertise lies in weaving logic into reality using **JavaScript, Node.js, and Python**.

---

### 🛠️ The Utility Belt (Tech Stack)

<table>
  <tr>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="45" height="45" />
      <br>JavaScript
    </td>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="45" height="45" />
      <br>React
    </td>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/bg/nodedotjs-icon.svg" alt="icon" width="45" height="45" />
      <br>Node.js
    </td>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/g-icon.svg" alt="icon" width="45" height="45" />
      <br>Google Cloud
    </td>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/mongodb-icon.svg" alt="icon" width="45" height="45" />
      <br>MongoDB
    </td>
    <td align="center" width="120">
      <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="45" height="45" />
      <br>Python
    </td>
  </tr>
</table>

**Gadgets & Tools:** `Git` `Postman` `Vercel` `Netlify` `Express.js` `JWT`

---

### 📂 Case Files (Featured Projects)

#### 🔹 [Project: VIVAMATE](https://github.com/chahel1817/VivaMate)
> *The AI-Powered Interrogation Simulator*
- **Objective:** Train recruits effectively using AI.
- **Tech:** MERN Stack, OpenRouter API.
- **Intel:** Features real-time camera & microphone analysis for mock interviews.

#### 🔹 [Project: EDUTRACK](https://github.com/chahel1817/EduTrack)
> *Tactical Learning & Assessment System*
- **Objective:** Track performance metrics and execute quiz assessments.
- **Tech:** MERN Stack, REST Analytics.
- **Intel:** Comprehensive performance tracking for field operatives.

---

### 🦇 Patrol Activity (GitHub Stats)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chahel1817&show_icons=true&theme=tokyonight&title_color=FFD700&icon_color=FFD700&text_color=ffffff&bg_color=0d1117&hide_border=true" height="180" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chahel1817&layout=compact&theme=tokyonight&title_color=FFD700&text_color=ffffff&bg_color=0d1117&hide_border=true" height="180" alt="languages" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chahel1817&theme=tokyonight&background=0d1117&ring=FFD700&fire=FFD700&currStreakNum=ffffff&currStreakLabel=FFD700&sideNums=ffffff&sideLabels=ffffff&hide_border=true" alt="streak" />
</div>

---

<div align="center">

### 📡 Signal The Bat
<a href="https://linkedin.com/in/chahel-tanna-87300a269/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:chahel1817@gmail.com">
  <img src="https://img.shields.io/badge/Email-Send_Intel-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>
