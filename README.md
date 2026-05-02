<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 300" width="860" height="300">
  <defs>
    <style>
      @keyframes scanline { 0%{transform:translateY(-300px)} 100%{transform:translateY(300px)} }
      @keyframes flicker { 0%,100%{opacity:1} 92%{opacity:1} 93%{opacity:0.7} 95%{opacity:1} 97%{opacity:0.85} }
      @keyframes blink { 0%,49%{opacity:1} 50%,100%{opacity:0} }
      @keyframes spin { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }
      @keyframes spin-rev { from{transform:rotate(360deg)} to{transform:rotate(0deg)} }
      @keyframes dash-move { to{stroke-dashoffset:-40} }
      @keyframes glitch1 { 0%,90%,100%{transform:translate(0,0)} 92%{transform:translate(-3px,1px)} 94%{transform:translate(3px,-1px)} 96%{transform:translate(-1px,2px)} }
      @keyframes glitch2 { 0%,85%,100%{clip-path:inset(0 0 100% 0)} 86%{clip-path:inset(30% 0 55% 0)} 88%{clip-path:inset(60% 0 20% 0)} 90%{clip-path:inset(10% 0 75% 0)} 91%{clip-path:inset(0 0 100% 0)} }
      @keyframes orbit { from{transform:rotate(0deg) translateX(58px) rotate(0deg)} to{transform:rotate(360deg) translateX(58px) rotate(-360deg)} }
      @keyframes orbit2 { from{transform:rotate(180deg) translateX(40px) rotate(-180deg)} to{transform:rotate(540deg) translateX(40px) rotate(-540deg)} }
    </style>
    <filter id="redglow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feFlood flood-color="#ff1a1a" flood-opacity="0.8" result="color"/>
      <feComposite in="color" in2="blur" operator="in" result="glow"/>
      <feMerge><feMergeNode in="glow"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="whiteglow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="clip"><rect width="860" height="300" rx="10"/></clipPath>
  </defs>
  <g clip-path="url(#clip)">
    <rect width="860" height="300" fill="#080808"/>
    <ellipse cx="120" cy="80" rx="180" ry="120" fill="#cc0000" opacity="0.07"/>
    <ellipse cx="740" cy="240" rx="200" ry="130" fill="#cc0000" opacity="0.05"/>
    <g stroke="#1a1a1a" stroke-width="0.5">
      <line x1="86" y1="0" x2="86" y2="300"/><line x1="172" y1="0" x2="172" y2="300"/>
      <line x1="258" y1="0" x2="258" y2="300"/><line x1="344" y1="0" x2="344" y2="300"/>
      <line x1="430" y1="0" x2="430" y2="300"/><line x1="516" y1="0" x2="516" y2="300"/>
      <line x1="602" y1="0" x2="602" y2="300"/><line x1="688" y1="0" x2="688" y2="300"/>
      <line x1="774" y1="0" x2="774" y2="300"/>
      <line x1="0" y1="50" x2="860" y2="50"/><line x1="0" y1="100" x2="860" y2="100"/>
      <line x1="0" y1="150" x2="860" y2="150"/><line x1="0" y1="200" x2="860" y2="200"/>
      <line x1="0" y1="250" x2="860" y2="250"/>
    </g>
    <path d="M20,20 L20,45 M20,20 L50,20" stroke="#cc0000" stroke-width="2" fill="none" filter="url(#redglow)"/>
    <path d="M840,20 L840,45 M840,20 L810,20" stroke="#cc0000" stroke-width="2" fill="none" filter="url(#redglow)"/>
    <path d="M20,280 L20,255 M20,280 L50,280" stroke="#cc0000" stroke-width="2" fill="none" filter="url(#redglow)"/>
    <path d="M840,280 L840,255 M840,280 L810,280" stroke="#cc0000" stroke-width="2" fill="none" filter="url(#redglow)"/>
    <rect x="0" y="0" width="860" height="2" fill="white" opacity="0.04" style="animation:scanline 4s linear infinite"/>
    <rect x="28" y="55" width="220" height="190" rx="6" fill="#0d0d0d" stroke="#222" stroke-width="0.8"/>
    <rect x="28" y="55" width="220" height="22" rx="6" fill="#161616"/>
    <rect x="28" y="65" width="220" height="12" fill="#161616"/>
    <circle cx="44" cy="66" r="4" fill="#ff5f57"/>
    <circle cx="57" cy="66" r="4" fill="#febc2e"/>
    <circle cx="70" cy="66" r="4" fill="#28c840"/>
    <text x="130" y="70" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#555">terminal</text>
    <text x="40" y="96" font-family="'Courier New',monospace" font-size="9.5" fill="#cc0000">$ whoami</text>
    <text x="40" y="112" font-family="'Courier New',monospace" font-size="9.5" fill="#e0e0e0">kundan_kumar_yadav</text>
    <text x="40" y="130" font-family="'Courier New',monospace" font-size="9.5" fill="#cc0000">$ cat skills.json</text>
    <text x="40" y="146" font-family="'Courier New',monospace" font-size="9.5" fill="#666">{</text>
    <text x="48" y="160" font-family="'Courier New',monospace" font-size="9" fill="#888">"stack": <tspan fill="#e0e0e0">"MERN",</tspan></text>
    <text x="48" y="173" font-family="'Courier New',monospace" font-size="9" fill="#888">"ai": <tspan fill="#cc0000">true,</tspan></text>
    <text x="48" y="186" font-family="'Courier New',monospace" font-size="9" fill="#888">"open": <tspan fill="#cc0000">true</tspan></text>
    <text x="40" y="199" font-family="'Courier New',monospace" font-size="9.5" fill="#666">}</text>
    <rect x="40" y="212" width="7" height="11" fill="#cc0000" style="animation:blink 1s step-end infinite"/>
    <rect x="28" y="77" width="2" height="168" fill="#cc0000" opacity="0.6"/>
    <text x="433" y="138" text-anchor="middle" font-family="Georgia,serif" font-size="44" font-weight="700" fill="#cc0000" opacity="0.5" style="animation:glitch1 6s infinite" letter-spacing="2">KUNDAN YADAV</text>
    <text x="433" y="138" text-anchor="middle" font-family="Georgia,serif" font-size="44" font-weight="700" fill="#ff3333" opacity="0.7" style="animation:glitch2 6s infinite;animation-delay:0.1s" letter-spacing="2">KUNDAN YADAV</text>
    <text x="430" y="135" text-anchor="middle" font-family="Georgia,serif" font-size="44" font-weight="700" fill="white" letter-spacing="2" filter="url(#whiteglow)" style="animation:flicker 8s infinite">KUNDAN YADAV</text>
    <rect x="260" y="147" width="30" height="1.5" fill="#cc0000" filter="url(#redglow)"/>
    <text x="430" y="162" text-anchor="middle" font-family="'Courier New',monospace" font-size="11" fill="#aaa" letter-spacing="3">FULL-STACK DEVELOPER  ·  MERN  ·  AI/ML</text>
    <rect x="570" y="147" width="30" height="1.5" fill="#cc0000" filter="url(#redglow)"/>
    <text x="430" y="183" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" fill="#555" letter-spacing="2">{ building scalable web apps · one commit at a time }</text>
    <g transform="translate(292,196)">
      <rect width="54" height="19" rx="3" fill="none" stroke="#333" stroke-width="0.8"/>
      <text x="27" y="13" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#888">React</text>
      <rect x="60" width="58" height="19" rx="3" fill="none" stroke="#333" stroke-width="0.8"/>
      <text x="89" y="13" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#888">Node.js</text>
      <rect x="124" width="68" height="19" rx="3" fill="none" stroke="#333" stroke-width="0.8"/>
      <text x="158" y="13" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#888">MongoDB</text>
      <rect x="198" width="60" height="19" rx="3" fill="none" stroke="#cc0000" stroke-width="0.8"/>
      <text x="228" y="13" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#cc0000">Python</text>
    </g>
    <line x1="28" y1="242" x2="832" y2="242" stroke="#1e1e1e" stroke-width="0.8"/>
    <circle cx="430" cy="242" r="3" fill="#cc0000" filter="url(#redglow)"/>
    <text x="100" y="265" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#444">MERN STACK</text>
    <text x="100" y="278" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" font-weight="700" fill="#e0e0e0">3+ YRS</text>
    <text x="240" y="265" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#444">PROJECTS</text>
    <text x="240" y="278" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" font-weight="700" fill="#e0e0e0">10+</text>
    <text x="430" y="265" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#444">LOCATION</text>
    <text x="430" y="278" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" font-weight="700" fill="#e0e0e0">BENGALURU, IN</text>
    <text x="620" y="265" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#444">STATUS</text>
    <text x="620" y="278" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" font-weight="700" fill="#cc0000">OPEN TO WORK</text>
    <text x="760" y="265" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#444">INTERNSHIP</text>
    <text x="760" y="278" text-anchor="middle" font-family="'Courier New',monospace" font-size="10" font-weight="700" fill="#e0e0e0">YUGAYATRA</text>
    <line x1="168" y1="248" x2="168" y2="288" stroke="#1e1e1e" stroke-width="0.8"/>
    <line x1="332" y1="248" x2="332" y2="288" stroke="#1e1e1e" stroke-width="0.8"/>
    <line x1="528" y1="248" x2="528" y2="288" stroke="#1e1e1e" stroke-width="0.8"/>
    <line x1="694" y1="248" x2="694" y2="288" stroke="#1e1e1e" stroke-width="0.8"/>
    <g transform="translate(754,148)">
      <circle r="72" fill="none" stroke="#1a1a1a" stroke-width="1"/>
      <circle r="72" fill="none" stroke="#cc0000" stroke-width="0.8" stroke-dasharray="6 4" opacity="0.5" style="transform-origin:center;animation:spin 16s linear infinite"/>
      <circle r="50" fill="none" stroke="#222" stroke-width="0.8"/>
      <circle r="50" fill="none" stroke="#fff" stroke-width="0.5" stroke-dasharray="3 8" opacity="0.2" style="transform-origin:center;animation:spin-rev 10s linear infinite"/>
      <polygon points="0,-38 33,-19 33,19 0,38 -33,19 -33,-19" fill="none" stroke="#cc0000" stroke-width="1.2" filter="url(#redglow)" style="transform-origin:center;animation:spin 20s linear infinite"/>
      <polygon points="0,-22 19,-11 19,11 0,22 -19,11 -19,-11" fill="#0d0d0d" stroke="#333" stroke-width="0.8" style="transform-origin:center;animation:spin-rev 12s linear infinite"/>
      <text y="-6" text-anchor="middle" font-family="'Courier New',monospace" font-size="9" fill="#666">KKY</text>
      <text y="8" text-anchor="middle" font-family="'Courier New',monospace" font-size="7" fill="#cc0000">DEV</text>
      <circle r="3.5" fill="#cc0000" filter="url(#redglow)" style="transform-origin:center;animation:orbit 4s linear infinite"/>
      <circle r="2" fill="white" style="transform-origin:center;animation:orbit2 6s linear infinite"/>
      <line x1="0" y1="-72" x2="0" y2="-62" stroke="#cc0000" stroke-width="1.5" filter="url(#redglow)"/>
      <line x1="72" y1="0" x2="62" y2="0" stroke="#cc0000" stroke-width="1.5" filter="url(#redglow)"/>
      <line x1="0" y1="72" x2="0" y2="62" stroke="#cc0000" stroke-width="1.5" filter="url(#redglow)"/>
      <line x1="-72" y1="0" x2="-62" y2="0" stroke="#cc0000" stroke-width="1.5" filter="url(#redglow)"/>
    </g>
    <circle cx="280" cy="108" r="1.5" fill="#cc0000" filter="url(#redglow)"><animate attributeName="opacity" values="0;1;0" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="575" cy="115" r="1" fill="white"><animate attributeName="opacity" values="0;0.8;0" dur="1.8s" begin="0.4s" repeatCount="indefinite"/></circle>
    <circle cx="310" cy="175" r="1" fill="#cc0000"><animate attributeName="opacity" values="0;1;0" dur="2.7s" begin="0.8s" repeatCount="indefinite"/></circle>
    <circle cx="550" cy="170" r="1.5" fill="white"><animate attributeName="opacity" values="0;0.6;0" dur="2s" begin="1.2s" repeatCount="indefinite"/></circle>
    <circle cx="420" cy="60" r="1" fill="#cc0000"><animate attributeName="opacity" values="0;1;0" dur="3s" begin="0.3s" repeatCount="indefinite"/></circle>
    <circle cx="670" cy="75" r="1.5" fill="#cc0000" filter="url(#redglow)"><animate attributeName="opacity" values="0;1;0" dur="2.1s" begin="1s" repeatCount="indefinite"/></circle>
    <circle cx="190" cy="230" r="1" fill="white"><animate attributeName="opacity" values="0;0.5;0" dur="2.5s" begin="0.6s" repeatCount="indefinite"/></circle>
    <line x1="260" y1="30" x2="600" y2="30" stroke="#cc0000" stroke-width="0.5" stroke-dasharray="4 6" opacity="0.4" style="animation:dash-move 2s linear infinite"/>
    <line x1="260" y1="34" x2="600" y2="34" stroke="white" stroke-width="0.3" stroke-dasharray="2 10" opacity="0.15" style="animation:dash-move 3s linear infinite reverse"/>
    <rect width="860" height="300" fill="none" stroke="#cc0000" stroke-width="0.6" rx="10" opacity="0.4" filter="url(#redglow)"/>
    <rect x="28" y="18" width="60" height="1" fill="#cc0000" opacity="0.8"/>
    <rect x="772" y="18" width="60" height="1" fill="#cc0000" opacity="0.8"/>
  </g>
</svg>

<!-- STEP 1: After uploading banner.svg to your repo root, replace the line below with:  -->
<!-- <img src="https://raw.githubusercontent.com/KUNDANIOS/KUNDANIOS/main/banner.svg" width="100%" alt="Banner"/> -->
<!-- For now the typing SVG works as the header -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=cc0000&height=200&section=header&text=Kundan%20Kumar%20Yadav&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20MERN%20%7C%20AI%2FML&descAlignY=60&descColor=aaaaaa&animation=fadeIn" width="100%" alt="Header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=CC0000&center=true&vCenter=true&width=600&lines=Full-Stack+Developer+(MERN);React+%7C+Node.js+%7C+MongoDB+%7C+Express;AI+%26+ML+Enthusiast;Open+Source+Contributor;Building+Scalable+Web+Apps+🚀" alt="Typing SVG" />

</div>

---

## 💡 About Me

- 🎓 B.E. Electronics & Communication Engineering — **JSS Academy of Technical Education, Bengaluru**
- 💼 Software Developer Intern @ **YugaYatra Retail**
- 🔭 Currently building **modern web applications and backend systems**
- 🌱 Exploring **Next.js, Generative AI, and scalable backend architectures**
- 🧠 Strong fundamentals in **DSA, OOPs, DBMS, and Operating Systems**
- ⚡ Fun fact: I love designing smooth UIs and writing clean backend APIs
- 🤝 Open to **collaboration on web development and open-source projects**

---

## 🛠 Tech Stack

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nextjs,tailwind" />
</p>

### ⚙️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,fastapi,flask" />
</p>

### 🗄️ Databases
<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql" />
</p>

### ☁️ Cloud & DevTools
<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,vercel,git,github,postman,vscode" />
</p>

---

## 🚀 Featured Projects

| 🚀 Project | 📄 Description | 🛠 Tech Stack |
|---|---|---|
| ☁️ **CloudDrive** | Full-stack cloud storage with secure file upload, auth & dashboard | React, Node.js, Express, MongoDB |
| 🌐 **Developer Portfolio** | Interactive portfolio with 3D animations and modern UI | React, Three.js, GSAP, TailwindCSS |
| 🤖 **Emotion Detection App** | Detects human emotions from facial images using ML & API | Python, Flask, Transformers, OpenCV |

🔗 [**View All Projects →**](https://github.com/KUNDANIOS)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KUNDANIOS&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KUNDANIOS&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top Languages" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=KUNDANIOS&theme=tokyonight&hide_border=true" alt="GitHub Streak" />

</div>

---

## 🏆 Certifications & Achievements

- 🏅 **Oracle Certified Foundations Associate** — AI & Machine Learning
- 💼 **JP Morgan Chase & Co. Software Engineering Job Simulation** — Forage
- ☁️ **Google Cloud Skill Badge** — Image Classification with TensorFlow

---

## 🌐 Currently Exploring

- 🏗️ **System Design** & Scalable Architectures
- ☁️ **Cloud Deployments** (Vercel, AWS, Google Cloud)
- 🤖 **Generative AI** & LLM integrations
- ⚡ **Next.js** & Edge Computing

---

## 🤝 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kundanyadv/)
[![Portfolio](https://img.shields.io/badge/Portfolio-CC0000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://kundan-portfolio-pi.vercel.app)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kundan4169re@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KUNDANIOS)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=cc0000&height=100&section=footer" width="100%"/>

![Profile Views](https://komarev.com/ghpvc/?username=KUNDANIOS&color=cc0000&style=flat-square&label=Profile+Views)

</div>
