<!-- 
=======================================================================
  PREMIUM CYBERPUNK DEVELOPER DASHBOARD README
  Theme: Neon Cyan Glassmorphism 
  Colors: #00F5FF (Cyan), #22D3EE (Sec. Cyan), #7C3AED (Purple), #050816 (Dark BG)
=======================================================================
  INSTRUCTIONS:
  1. Search and replace "YOUR_GITHUB_USERNAME" with your GitHub username.
  2. Search and replace "YOUR_WAKATIME_USERNAME" with your WakaTime username.
  3. Replace "#" in the Connect with Me section with your actual URLs.
=======================================================================
-->

<div align="center">

<!-- 1. & 2. HERO BANNER & ANIMATED NAME (SVG) -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 300" width="100%" height="300">
  <defs>
    <radialGradient id="glowGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00F5FF" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#050816" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F5FF"/>
      <stop offset="50%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#00F5FF"/>
      <animate attributeName="x1" values="0%;-100%;0%" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="100%;0%;100%" dur="6s" repeatCount="indefinite"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#22D3EE" stroke-width="0.3" opacity="0.15"/>
    </pattern>
    <filter id="neon" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background Layer -->
  <rect width="100%" height="100%" fill="#050816"/>
  <rect width="100%" height="100%" fill="url(#grid)"/>
  <rect width="100%" height="100%" fill="url(#glowGrad)"/>
  
  <!-- Animated Background Particles -->
  <g fill="#00F5FF" opacity="0.6">
    <circle cx="150" cy="280" r="1.5"><animate attributeName="cy" values="280;20" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="850" cy="290" r="2.5"><animate attributeName="cy" values="290;10" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="250" cy="260" r="1.5"><animate attributeName="cy" values="260;50" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="750" cy="270" r="2"><animate attributeName="cy" values="270;30" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="50" cy="200" r="1"><animate attributeName="cy" values="200;10" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="950" cy="220" r="3"><animate attributeName="cy" values="220;40" dur="5.5s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Animated Cloud Nodes -->
  <path d="M 120,150 L 220,100 L 300,160 L 420,120" fill="none" stroke="#7C3AED" stroke-width="1.5" stroke-dasharray="4" opacity="0.4">
    <animate attributeName="stroke-dashoffset" values="20;0" dur="2s" repeatCount="indefinite"/>
  </path>
  <path d="M 880,150 L 780,100 L 700,160 L 580,120" fill="none" stroke="#00F5FF" stroke-width="1.5" stroke-dasharray="4" opacity="0.4">
     <animate attributeName="stroke-dashoffset" values="0;20" dur="2s" repeatCount="indefinite"/>
  </path>
  <circle cx="120" cy="150" r="3" fill="#00F5FF" filter="url(#neon)"/>
  <circle cx="220" cy="100" r="4" fill="#7C3AED"/>
  <circle cx="300" cy="160" r="3" fill="#00F5FF"/>
  <circle cx="880" cy="150" r="3" fill="#00F5FF" filter="url(#neon)"/>
  <circle cx="780" cy="100" r="4" fill="#7C3AED"/>
  <circle cx="700" cy="160" r="3" fill="#00F5FF"/>

  <!-- Profile Avatar Placeholder -->
  <circle cx="500" cy="80" r="42" fill="#0B1120" stroke="#00F5FF" stroke-width="3" filter="url(#neon)"/>
  <circle cx="500" cy="80" r="38" fill="#050816"/>
  <circle cx="500" cy="80" r="38" fill="#00F5FF" opacity="0.1"/>
  <text x="500" y="88" font-family="'Courier New', monospace" font-size="20" fill="#00F5FF" text-anchor="middle" filter="url(#neon)">&lt;/&gt;</text>

  <!-- ARX Title (Animated Name) -->
  <text x="500" y="190" font-family="'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="72" font-weight="900" fill="url(#textGrad)" text-anchor="middle" letter-spacing="10" filter="url(#neon)">
    ARX
  </text>
  
  <!-- Subtitle -->
  <text x="500" y="230" font-family="'Segoe UI', Roboto, sans-serif" font-size="14" font-weight="600" fill="#B6C2CF" text-anchor="middle" letter-spacing="3">
    CLOUD ENGINEER • SOFTWARE ENGINEER • DEVOPS • AI BUILDER
  </text>

  <!-- Animated Glowing Underline -->
  <rect x="350" y="250" width="300" height="2" fill="#00F5FF" filter="url(#neon)" rx="1">
    <animate attributeName="width" values="0;300;0" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x" values="500;350;500" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- 3. TYPING ANIMATION -->
<a href="https://github.com/YOUR_GITHUB_USERNAME">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00F5FF&center=true&vCenter=true&width=600&lines=Building+Cloud+Native+Systems...;Engineering+Full+Stack+Applications...;Deploying+with+Docker+%26+Kubernetes...;Learning+AWS+%26+Terraform...;Building+AI-Powered+Solutions...;Automating+Infrastructure..." alt="Typing SVG" />
</a>

<br><br>

<!-- 18. CONNECT WITH ME -->
<a href="#"><img src="https://img.shields.io/badge/GitHub-0B1120?style=for-the-badge&logo=github&logoColor=00F5FF&labelColor=050816" alt="GitHub"/></a>
<a href="#"><img src="https://img.shields.io/badge/LinkedIn-0B1120?style=for-the-badge&logo=linkedin&logoColor=00F5FF&labelColor=050816" alt="LinkedIn"/></a>
<a href="#"><img src="https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=vercel&logoColor=00F5FF&labelColor=050816" alt="Portfolio"/></a>
<a href="mailto:#"><img src="https://img.shields.io/badge/Email-0B1120?style=for-the-badge&logo=gmail&logoColor=00F5FF&labelColor=050816" alt="Email"/></a>
<a href="#"><img src="https://img.shields.io/badge/X_Twitter-0B1120?style=for-the-badge&logo=x&logoColor=00F5FF&labelColor=050816" alt="X"/></a>
<a href="#"><img src="https://img.shields.io/badge/Discord-0B1120?style=for-the-badge&logo=discord&logoColor=00F5FF&labelColor=050816" alt="Discord"/></a>

<br><br>
</div>

---

<!-- 4. ABOUT ME DASHBOARD -->
### 💠 SYSTEM_INFO: ABOUT_ME_DASHBOARD
<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <blockquote>
        <h3 align="center">👨‍💻 About Me</h3>
        <p align="center">Designing scalable cloud-native applications, robust backend systems, automation tools, and AI-powered software solutions from the Philippines. Passionate about building elegant, high-performance infrastructure.</p>
      </blockquote>
    </td>
    <td width="50%" valign="top">
      <blockquote>
        <h3 align="center">⚡ Current Focus</h3>
        <p align="center">
          <img src="https://img.shields.io/badge/-Cloud_Engineering-0B1120?style=flat-square&logo=cloud&logoColor=00F5FF&labelColor=050816" />
          <img src="https://img.shields.io/badge/-DevOps-0B1120?style=flat-square&logo=linux&logoColor=00F5FF&labelColor=050816" />
          <img src="https://img.shields.io/badge/-Backend_APIs-0B1120?style=flat-square&logo=databricks&logoColor=00F5FF&labelColor=050816" />
          <img src="https://img.shields.io/badge/-AI_Systems-0B1120?style=flat-square&logo=openai&logoColor=00F5FF&labelColor=050816" />
        </p>
      </blockquote>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <blockquote>
        <h3 align="center">🚀 Currently Learning</h3>
        <p align="center">
          <code>AWS</code> <code>Kubernetes</code> <code>Terraform</code> <code>CI/CD</code> <code>Microservices</code>
        </p>
      </blockquote>
    </td>
    <td width="50%" valign="top">
      <blockquote>
        <h3 align="center">🧠 Interests</h3>
        <p align="center">
          Distributed Systems • Cloud Architecture • Automation • Machine Learning • Human-Centered Software
        </p>
      </blockquote>
    </td>
  </tr>
</table>

---

<!-- 5. GITHUB OVERVIEW DASHBOARD & 6. DEVELOPER METRICS CENTER -->
### 📊 MODULE: GITHUB_OVERVIEW

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=radical&bg_color=050816&title_color=00F5FF&text_color=FFFFFF&icon_color=7C3AED&hide_border=true&border_radius=10" height="195" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=radical&bg_color=050816&title_color=00F5FF&text_color=FFFFFF&icon_color=7C3AED&hide_border=true&fire=00F5FF&ring=7C3AED&border_radius=10" height="195" alt="GitHub Streak" />
</div>
<br>
<div align="center">
  <img src="https://img.shields.io/github/followers/YOUR_GITHUB_USERNAME?style=for-the-badge&color=0B1120&logoColor=00F5FF&labelColor=050816&logo=github" alt="Followers" />
  <img src="https://img.shields.io/github/stars/YOUR_GITHUB_USERNAME?style=for-the-badge&color=0B1120&logoColor=00F5FF&labelColor=050816&logo=github" alt="Stars" />
  <img src="https://img.shields.io/github/issues/YOUR_GITHUB_USERNAME?style=for-the-badge&color=0B1120&logoColor=00F5FF&labelColor=050816&logo=github" alt="Issues" />
  <img src="https://img.shields.io/github/issues-pr/YOUR_GITHUB_USERNAME?style=for-the-badge&color=0B1120&logoColor=00F5FF&labelColor=050816&logo=github" alt="Pull Requests" />
</div>

---

<!-- 7. CODING ACTIVITY DASHBOARD -->
### ⏱️ MODULE: CODING_ACTIVITY

<div align="center">
  <a href="https://wakatime.com/@YOUR_WAKATIME_USERNAME">
    <img src="https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME_USERNAME&theme=radical&bg_color=050816&title_color=00F5FF&text_color=FFFFFF&hide_border=true&border_radius=10&layout=compact" height="195" alt="Wakatime Activity" />
  </a>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&theme=radical&bg_color=050816&title_color=00F5FF&text_color=FFFFFF&hide_border=true&border_radius=10&layout=compact" height="195" alt="Top Languages" />
</div>

---

<!-- 8. TECH STACK SHOWCASE -->
### ⚙️ MODULE: TECHNOLOGY_STACK

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>☁️ Cloud Platforms</b><br><br>
      <img src="https://img.shields.io/badge/AWS-0B1120?style=for-the-badge&logo=amazon-aws&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Azure-0B1120?style=for-the-badge&logo=microsoft-azure&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/GCP-0B1120?style=for-the-badge&logo=google-cloud&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Firebase-0B1120?style=for-the-badge&logo=firebase&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Cloudflare-0B1120?style=for-the-badge&logo=cloudflare&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Vercel-0B1120?style=for-the-badge&logo=vercel&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Railway-0B1120?style=for-the-badge&logo=railway&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Render-0B1120?style=for-the-badge&logo=render&logoColor=00F5FF&labelColor=050816" />
    </td>
    <td width="50%" align="center">
      <b>🏗️ DevOps & Infra</b><br><br>
      <img src="https://img.shields.io/badge/Docker-0B1120?style=for-the-badge&logo=docker&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Kubernetes-0B1120?style=for-the-badge&logo=kubernetes&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Terraform-0B1120?style=for-the-badge&logo=terraform&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/GitHub_Actions-0B1120?style=for-the-badge&logo=githubactions&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Linux-0B1120?style=for-the-badge&logo=linux&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/NGINX-0B1120?style=for-the-badge&logo=nginx&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Bash-0B1120?style=for-the-badge&logo=gnu-bash&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/YAML-0B1120?style=for-the-badge&logo=yaml&logoColor=00F5FF&labelColor=050816" />
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <br><b>🔌 Backend & DBs</b><br><br>
      <img src="https://img.shields.io/badge/Node.js-0B1120?style=for-the-badge&logo=nodedotjs&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Python-0B1120?style=for-the-badge&logo=python&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Java-0B1120?style=for-the-badge&logo=java&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/FastAPI-0B1120?style=for-the-badge&logo=fastapi&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Express-0B1120?style=for-the-badge&logo=express&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/GraphQL-0B1120?style=for-the-badge&logo=graphql&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/PostgreSQL-0B1120?style=for-the-badge&logo=postgresql&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Prisma-0B1120?style=for-the-badge&logo=prisma&logoColor=00F5FF&labelColor=050816" />
    </td>
    <td width="50%" align="center">
      <br><b>🤖 Frontend & AI</b><br><br>
      <img src="https://img.shields.io/badge/React-0B1120?style=for-the-badge&logo=react&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Next.js-0B1120?style=for-the-badge&logo=nextdotjs&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/Flutter-0B1120?style=for-the-badge&logo=flutter&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/TypeScript-0B1120?style=for-the-badge&logo=typescript&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/TensorFlow-0B1120?style=for-the-badge&logo=tensorflow&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/PyTorch-0B1120?style=for-the-badge&logo=pytorch&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/OpenCV-0B1120?style=for-the-badge&logo=opencv&logoColor=00F5FF&labelColor=050816" />
      <img src="https://img.shields.io/badge/HuggingFace-0B1120?style=for-the-badge&logo=huggingface&logoColor=00F5FF&labelColor=050816" />
    </td>
  </tr>
</table>

---

<!-- 9. SKILLS VISUALIZATION (SVG) -->
### 📈 MODULE: SKILLS_VISUALIZATION

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 420" width="100%" height="420">
  <defs>
    <linearGradient id="barGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F5FF"/>
      <stop offset="100%" stop-color="#7C3AED"/>
    </linearGradient>
    <filter id="glowBar" x="-5%" y="-20%" width="110%" height="140%">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="100%" height="100%" fill="#050816" rx="10"/>
  
  <g font-family="'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-weight="600" font-size="14" fill="#FFFFFF">
    
    <!-- Row 1 -->
    <text x="30" y="42">Cloud Engineering</text>
    <rect x="220" y="30" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="30" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="456" dur="2s" fill="freeze"/>
    </rect>
    <text x="720" y="42" fill="#00F5FF">95%</text>

    <!-- Row 2 -->
    <text x="30" y="82">Backend Development</text>
    <rect x="220" y="70" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="70" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="432" dur="2.2s" fill="freeze"/>
    </rect>
    <text x="720" y="82" fill="#00F5FF">90%</text>

    <!-- Row 3 -->
    <text x="30" y="122">DevOps & CI/CD</text>
    <rect x="220" y="110" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="110" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="408" dur="2.4s" fill="freeze"/>
    </rect>
    <text x="720" y="122" fill="#00F5FF">85%</text>

    <!-- Row 4 -->
    <text x="30" y="162">Frontend Development</text>
    <rect x="220" y="150" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="150" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="408" dur="2.6s" fill="freeze"/>
    </rect>
    <text x="720" y="162" fill="#00F5FF">85%</text>

    <!-- Row 5 -->
    <text x="30" y="202">Databases</text>
    <rect x="220" y="190" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="190" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="432" dur="2.8s" fill="freeze"/>
    </rect>
    <text x="720" y="202" fill="#00F5FF">90%</text>

    <!-- Row 6 -->
    <text x="30" y="242">Linux / System Admin</text>
    <rect x="220" y="230" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="230" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="384" dur="3s" fill="freeze"/>
    </rect>
    <text x="720" y="242" fill="#00F5FF">80%</text>

    <!-- Row 7 -->
    <text x="30" y="282">Python</text>
    <rect x="220" y="270" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="270" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="456" dur="3.2s" fill="freeze"/>
    </rect>
    <text x="720" y="282" fill="#00F5FF">95%</text>

    <!-- Row 8 -->
    <text x="30" y="322">Java</text>
    <rect x="220" y="310" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="310" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="384" dur="3.4s" fill="freeze"/>
    </rect>
    <text x="720" y="322" fill="#00F5FF">80%</text>

    <!-- Row 9 -->
    <text x="30" y="362">AI / Machine Learning</text>
    <rect x="220" y="350" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="350" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="360" dur="3.6s" fill="freeze"/>
    </rect>
    <text x="720" y="362" fill="#00F5FF">75%</text>

    <!-- Row 10 -->
    <text x="30" y="402">Git & Source Control</text>
    <rect x="220" y="390" width="480" height="14" fill="#0B1120" rx="7"/>
    <rect x="220" y="390" width="0" height="14" fill="url(#barGrad)" rx="7" filter="url(#glowBar)">
      <animate attributeName="width" from="0" to="456" dur="3.8s" fill="freeze"/>
    </rect>
    <text x="720" y="402" fill="#00F5FF">95%</text>
  </g>
</svg>
</div>

---

<!-- 10. TECHNOLOGY ORBIT (SVG) -->
### 🌀 MODULE: SYSTEM_CORE_ORBIT

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 350" width="100%" height="350">
  <defs>
    <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00F5FF" stop-opacity="1"/>
      <stop offset="100%" stop-color="#00F5FF" stop-opacity="0"/>
    </radialGradient>
    <filter id="neonBlur" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="100%" height="100%" fill="#050816"/>
  
  <g transform="translate(300, 175)">
    <!-- Orbits -->
    <circle r="70" fill="none" stroke="#22D3EE" stroke-width="0.5" stroke-dasharray="4 4"/>
    <circle r="110" fill="none" stroke="#7C3AED" stroke-width="0.5" stroke-dasharray="4 4"/>
    <circle r="150" fill="none" stroke="#38BDF8" stroke-width="0.5" stroke-dasharray="4 4"/>

    <!-- Central Core -->
    <circle r="35" fill="url(#coreGlow)"/>
    <circle r="18" fill="#050816" stroke="#00F5FF" stroke-width="2" filter="url(#neonBlur)"/>
    <text x="0" y="4" font-family="'Courier New', monospace" font-size="12" fill="#FFF" text-anchor="middle" font-weight="900">ARX</text>

    <!-- Inner Orbit Nodes -->
    <g>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="8s" repeatCount="indefinite"/>
      <circle cx="70" cy="0" r="6" fill="#00F5FF" filter="url(#neonBlur)"/>
      <circle cx="-70" cy="0" r="4" fill="#7C3AED"/>
    </g>
    
    <!-- Middle Orbit Nodes -->
    <g>
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="12s" repeatCount="indefinite"/>
      <circle cx="110" cy="0" r="8" fill="#7C3AED" filter="url(#neonBlur)"/>
      <circle cx="-110" cy="0" r="5" fill="#00F5FF"/>
      <circle cx="0" cy="110" r="4" fill="#38BDF8"/>
    </g>
    
    <!-- Outer Orbit Nodes -->
    <g>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="16s" repeatCount="indefinite"/>
      <circle cx="150" cy="0" r="6" fill="#00F5FF" filter="url(#neonBlur)"/>
      <circle cx="-106" cy="-106" r="7" fill="#38BDF8" filter="url(#neonBlur)"/>
      <circle cx="106" cy="106" r="5" fill="#7C3AED"/>
    </g>
  </g>
</svg>
</div>

---

<!-- 11 & 12. EXPERTISE DASHBOARD -->
### 🛠️ MODULE: EXPERTISE_VECTORS

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <blockquote>
        <h4 align="center">☁️ CLOUD ENGINEERING</h4>
        <ul>
          <li><b>Cloud Computing:</b> Scalable architecture on AWS & GCP.</li>
          <li><b>Containers & K8s:</b> Orchestrating resilient microservices.</li>
          <li><b>Infrastructure as Code:</b> Automation via Terraform.</li>
          <li><b>Serverless Architecture:</b> Event-driven processing.</li>
          <li><b>Cloud Security:</b> IAM, VPC, and robust network isolation.</li>
        </ul>
      </blockquote>
    </td>
    <td width="50%" valign="top">
      <blockquote>
        <h4 align="center">💻 SOFTWARE ENGINEERING</h4>
        <ul>
          <li><b>System Design:</b> High-availability, low-latency architectures.</li>
          <li><b>REST & GraphQL:</b> Designing efficient API contracts.</li>
          <li><b>Microservices:</b> Decoupling monolithic structures.</li>
          <li><b>Database Design:</b> SQL & NoSQL optimization.</li>
          <li><b>Clean Code:</b> Strict adherence to SOLID & DRY principles.</li>
        </ul>
      </blockquote>
    </td>
  </tr>
</table>

---

<!-- 13. FEATURED PROJECTS -->
### 📂 MODULE: PROJECT_REGISTRY

<table width="100%">
  <thead>
    <tr>
      <th width="35%">Project Matrix</th>
      <th width="45%">Tech Stack & Architecture</th>
      <th width="20%">Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>🐕 Stray Animal Rescue Platform</b><br>
        <sub>Cloud-native rescue and adoption management ecosystem.</sub>
      </td>
      <td>
        <img src="https://img.shields.io/badge/Next.js-0B1120?style=flat&logo=next.js&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/Node.js-0B1120?style=flat&logo=node.js&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/AWS-0B1120?style=flat&logo=amazon-aws&logoColor=00F5FF" />
      </td>
      <td align="center"><img src="https://img.shields.io/badge/DEPLOYED-00F5FF?style=for-the-badge&color=0B1120" /></td>
    </tr>
    <tr>
      <td>
        <b>🚨 DRRH Disaster Response</b><br>
        <sub>Emergency response coordination and mapping platform.</sub>
      </td>
      <td>
        <img src="https://img.shields.io/badge/React-0B1120?style=flat&logo=react&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/Python-0B1120?style=flat&logo=python&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/PostgreSQL-0B1120?style=flat&logo=postgresql&logoColor=00F5FF" />
      </td>
      <td align="center"><img src="https://img.shields.io/badge/ACTIVE-00F5FF?style=for-the-badge&color=0B1120" /></td>
    </tr>
    <tr>
      <td>
        <b>☁️ Cloud Backup CLI</b><br>
        <sub>Python-based automation for enterprise cloud synchronization.</sub>
      </td>
      <td>
        <img src="https://img.shields.io/badge/Python-0B1120?style=flat&logo=python&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/Bash-0B1120?style=flat&logo=gnu-bash&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/Docker-0B1120?style=flat&logo=docker&logoColor=00F5FF" />
      </td>
      <td align="center"><img src="https://img.shields.io/badge/STABLE-00F5FF?style=for-the-badge&color=0B1120" /></td>
    </tr>
    <tr>
      <td>
        <b>🧠 AI Career Engine</b><br>
        <sub>Machine learning recommendation platform for tech careers.</sub>
      </td>
      <td>
        <img src="https://img.shields.io/badge/TensorFlow-0B1120?style=flat&logo=tensorflow&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/FastAPI-0B1120?style=flat&logo=fastapi&logoColor=00F5FF" />
        <img src="https://img.shields.io/badge/AWS-0B1120?style=flat&logo=amazon-aws&logoColor=00F5FF" />
      </td>
      <td align="center"><img src="https://img.shields.io/badge/BETA-7C3AED?style=for-the-badge&color=0B1120" /></td>
    </tr>
  </tbody>
</table>

---

<!-- 14. CLOUD ARCHITECTURE ILLUSTRATION -->
### 🏗️ MODULE: CLOUD_ARCHITECTURE_FLOW

```mermaid
graph TD
  classDef border fill:#0B1120,stroke:#00F5FF,stroke-width:2px,color:#FFFFFF,rx:5px,ry:5px;
  classDef db fill:#050816,stroke:#7C3AED,stroke-width:2px,color:#FFFFFF,rx:5px,ry:5px;
  classDef special fill:#050816,stroke:#38BDF8,stroke-width:2px,color:#FFFFFF,rx:5px,ry:5px;

  User([User Client]):::special --> CDN[Cloudflare CDN / Edge]:::border
  CDN --> Frontend[Frontend React / Next.js]:::border
  Frontend --> API[API Gateway / Load Balancer]:::border
  API --> Backend[Backend Microservices]:::border
  Backend --> DB[(PostgreSQL)]:::db
  Backend --> Storage[(Cloud Storage)]:::db
  Backend --> AI[AI Recommendation Engine]:::special
  Backend --> Monitor[Monitoring Dashboard / Logs]:::special
