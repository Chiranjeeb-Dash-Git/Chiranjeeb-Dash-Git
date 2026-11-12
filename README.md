<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Headline Preview</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@800;900&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #0d1117;
      color: #c9d1d9;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      padding: 20px;
      box-sizing: border-box;
    }
    .container {
      width: 100%;
      max-width: 900px;
      text-align: center;
    }
    .portfolio-btn {
      display: inline-block;
      margin-top: 15px;
      transition: transform 0.2s ease, filter 0.2s ease;
    }
    .portfolio-btn:hover {
      transform: translateY(-2px);
      filter: drop-shadow(0 0 10px rgba(255, 30, 86, 0.7));
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- Red Animated SVG Header Card -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 220" width="100%" height="220">
      <defs>
        <!-- Dark Obsidian / Crimson Gradient -->
        <linearGradient id="darkBg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#0a0508"/>
          <stop offset="50%" stop-color="#19070f"/>
          <stop offset="100%" stop-color="#070305"/>
        </linearGradient>

        <!-- Pulsing Red Glow Filter -->
        <filter id="neonPulse" x="-50%" y="-50%" width="200%" height="200%">
          <feDropShadow dx="0" dy="0" stdDeviation="8" flood-color="#FF1E56" flood-opacity="0.9">
            <animate attributeName="stdDeviation" values="4;14;4" dur="2.4s" repeatCount="indefinite"/>
            <animate attributeName="flood-color" values="#FF1E56;#FF4B4B;#FF0055;#FF1E56" dur="2.4s" repeatCount="indefinite"/>
          </feDropShadow>
        </filter>

        <!-- Shimmering Red-to-White Text Gradient -->
        <linearGradient id="textRedShimmer" x1="-100%" y1="0%" x2="200%" y2="0%">
          <stop offset="0%" stop-color="#FF1E56"/>
          <stop offset="45%" stop-color="#FF4B4B"/>
          <stop offset="50%" stop-color="#FFFFFF"/>
          <stop offset="55%" stop-color="#FF4B4B"/>
          <stop offset="100%" stop-color="#FF1E56"/>
          <animate attributeName="x1" values="-100%;100%" dur="3s" repeatCount="indefinite"/>
          <animate attributeName="x2" values="0%;200%" dur="3s" repeatCount="indefinite"/>
        </linearGradient>

        <!-- Circular Avatar Mask -->
        <clipPath id="circleAvatar">
          <circle cx="130" cy="110" r="65" />
        </clipPath>
      </defs>

      <!-- Background Box -->
      <rect width="900" height="220" rx="20" fill="url(#darkBg)" stroke="#FF1E56" stroke-width="1.5" stroke-opacity="0.5"/>

      <!-- Glowing Red Ring -->
      <circle cx="130" cy="110" r="70" fill="none" stroke="#FF1E56" stroke-width="3.5" filter="url(#neonPulse)"/>

      <!-- Avatar Photo -->
      <image href="https://avatars.githubusercontent.com/u/180313099?v=4" x="65" y="45" width="130" height="130" clip-path="url(#circleAvatar)" />

      <!-- Big Animated Text -->
      <text x="240" y="125" font-family="'Orbitron', sans-serif" font-size="46" font-weight="900" letter-spacing="4" fill="url(#textRedShimmer)" filter="url(#neonPulse)">
        CHIRANJEEB DASH
      </text>
    </svg>

    <!-- Animated Typing SVG -->
    <p style="margin-top: 15px; margin-bottom: 5px;">
      <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=800&size=23&duration=2800&pause=1100&color=FF1E56&center=true&vCenter=true&width=650&height=50&lines=%E2%9A%A1+NEXT-GEN+FULLStack+DEVELOPER+%E2%9A%A1;%F0%9F%A7%A0+AI-INTEGRATED+MERN+ARCHITECT+%F0%9F%A7%A0;%F0%9F%9A%80+SCALABLE+SOFTWARE+ENGINEER+%F0%9F%9A%80" alt="Typing SVG" />
    </p>

    <!-- Live Portfolio Button -->
    <p>
      <a class="portfolio-btn" href="https://chiranjeeb-portfolio.vercel.app/" target="_blank">
        <img src="https://raw.githubusercontent.com/Chiranjeeb-Dash-Git/Portfolio/main/assets/live-portfolio-button.svg" alt="View live portfolio" />
      </a>
    </p>

  </div>
</body>
</html>


## 🚀 ACTIVE DEPLOYMENTS (Vercel & Render & Railway)

<table align="center">
  <tr>
    <td>
      <a href="https://full-stack-gen-ai-assistant.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=00F2FF&height=150&text=GEN-AI%20ASSISTANT&fontSize=25&fontColor=000000&desc=MERN%20+%20Groq%20AI&descAlignY=65&descSize=15" />
      </a>
    </td>
    <td>
      <a href="https://chiranjeeb-dash-git.github.io/Zerodha-/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=181717&height=150&text=ZERODHA%20CLONE&fontSize=25&fontColor=00F2FF&desc=Fintech%20+%20WebSockets&descAlignY=65&descSize=15" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://quantum-query-ai-agent.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=181717&height=150&text=QUANTUM%20QUERY&fontSize=25&fontColor=00F2FF&desc=Agentic%20Search%20&CodeReviewr&descAlignY=65&descSize=15" />
      </a>
    </td>
    <td>
      <a href="https://airbnb-global-stay-network.onrender.com/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=00F2FF&height=150&text=AIRBNB%20CLONE&fontSize=25&fontColor=000000&desc=Production%20MVC%20Marketplace&descAlignY=65&descSize=15" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://social-media-platform-azure-ten.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=00F2FF&height=150&text=SOCIAL%20PLATFORM&fontSize=25&fontColor=000000&desc=Next.js%2016%20+%20Neon%20SQL&descAlignY=65&descSize=15" />
      </a>
    </td>
    <td>
      <a href="https://document-manager-quo8.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=181717&height=150&text=DOCUMENT%20MANAGER&fontSize=25&fontColor=00F2FF&desc=Full-Stack%20Document%20Suite&descAlignY=65&descSize=15" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://smart-naff5gjfr-chiranjeeb-dash-gits-projects.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=181717&height=150&text=SMART%20ERP&fontSize=25&fontColor=00F2FF&desc=Next.js%20+%20Neon%20SQL&descAlignY=65&descSize=15" />
      </a>
    </td>
    <td>
      <a href="https://insuranceplatform-rho.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=00F2FF&height=150&text=INSURANCE%20PLATFORM&fontSize=23&fontColor=000000&desc=React%2019%20+%20Express%20+%20Prisma&descAlignY=65&descSize=15" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://examify-hub-seven.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=181717&height=150&text=EXAMIFY%20HUB&fontSize=25&fontColor=00F2FF&desc=Assessment%20OS%20+%20AI%20Telemetry&descAlignY=65&descSize=15" />
      </a>
    </td>
    <td>
      <a href="https://cloud-fs-ten.vercel.app/">
        <img src="https://capsule-render.vercel.app/api?type=rect&color=00F2FF&height=150&text=CLOUD%20FS&fontSize=25&fontColor=000000&desc=Cloud%20Storage%20&%20Sharing%20Suite&descAlignY=65&descSize=15" />
      </a>
    </td>
  </tr>
</table>

---

## 🛠️ SKILLS

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=javascript,nextjs,react,nodejs,express,mongodb,tailwind,docker,git,github&theme=dark)](https://skillicons.dev)

**JavaScript** • **React** • **Next.js** • **Node.js** • **Express** • **MongoDB** • **MySQL** • **GraphQL** • **Tailwind** • **Docker** • **LangChain** • **AI Integration**

</div>

---

## 🎓 EDUCATION & CREDENTIALS
- 🎓 **B.Tech (CSE)** — Biju Patnaik University of Technology (BPUT)
- 📜 **Full Stack MERN Development**
- 🌟 **Advanced AI-Integration in Web Environments**
- 🤖 **Production AI Agents: LangChain & LangGraph**

---

## 📞 CONNECT WITH ME...
<p align="center">
  <a href="mailto:chiranjeeb.email@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Chiranjeeb-Dash-Git"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/chiranjeeb-dash-/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00F2FF&height=120&section=footer&animation=twinkle" width="100%"/>
</p>
