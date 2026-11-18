<!-- Animated wave header -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Mohamed%20Amin%20El%20Filali&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-Stack%20Developer%20%C2%B7%20Self-Hosting%20Enthusiast%20%C2%B7%20Automation%20Nerd&descSize=17&descAlignY=58" alt="header" />
</div>

<!-- Typing animation -->
<div align="center">
  <a href="https://elfilaliamin.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&width=720&height=50&lines=I+build+and+self-host+production+web+apps+%F0%9F%9A%80;React+%C2%B7+TypeScript+%C2%B7+Node.js+%C2%B7+PostgreSQL;Docker+%C2%B7+Nginx+%C2%B7+Cloudflare+Zero+Trust;From+PLCs+and+electromechanics+to+clean+code+%E2%9A%99%EF%B8%8F;Open+to+junior+full-stack+%2F+backend+roles+%F0%9F%8E%AF" alt="Typing SVG" />
  </a>
</div>

<br>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-elfilaliamin.com-36BCF7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://elfilaliamin.com)
[![Medium](https://img.shields.io/badge/Medium-@elfilaliamin-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@elfilaliamin)
[![Email](https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elfilaliamin.design@gmail.com)
[![Location](https://img.shields.io/badge/Tetouan-Morocco-C1272D?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<img src="https://komarev.com/ghpvc/?username=elfilaliamin&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />

</div>

---

## 👋 About me

```ts
const amin = {
  role: "Full-Stack Developer",
  base: "Tetouan, Morocco 🇲🇦",
  background: ["Industrial automation", "Electromechanical troubleshooting"],
  philosophy: "Reliable, clean, maintainable.",
  hosting: "My own Alpine Linux home server (Docker + Nginx + Cloudflare Zero Trust)",
  loves: ["Automation tools", "Browser extensions", "Workflow optimization", "Arduino & embedded C"],
  funFact: "I enjoy reverse-engineering how web apps work 😄",
  languages: { Arabic: "native", English: "professional", French: "limited working" },
  lookingFor: "Junior full-stack or backend roles focused on practical, operational problem-solving",
};
```

---

## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧾 MySirati</h3>
      <p>AI-ready career data platform. Exports granular <b>JSON Resume</b> data for AI agents (LLM job matching) with key-based access.</p>
      <p><code>React 18</code> <code>TypeScript</code> <code>Express</code> <code>PostgreSQL 16</code> <code>Drizzle</code> <code>Docker</code></p>
      <p>🔐 Argon2 · Helmet · rate limiting</p>
      <a href="https://github.com/elfilaliamin/MySirati">GitHub</a> · <a href="https://mysirati.aminlab.site/">Live</a> · <a href="https://mysirati.aminlab.site/docs/">Docs</a>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 MasteryOS</h3>
      <p>Productivity and goal platform with KPI dashboards, Kanban and list views, course tracking and gamified rewards.</p>
      <p><code>React 19</code> <code>Vite</code> <code>Tailwind v4</code> <code>Express</code> <code>PostgreSQL</code> <code>GitHub Actions</code></p>
      <p>♾️ Infinite scroll · URL-persisted filters</p>
      <a href="https://github.com/elfilaliamin/MasteryOS/">GitHub</a> · <a href="https://masteryos.aminlab.site/">Live</a> · <a href="https://masteryos.aminlab.site/Docs/">Docs</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💰 Finance Tracker</h3>
      <p>Self-hosted personal finance platform: multi-currency wallets (cash, bank, crypto, credit), transfers, exact balance reconciliation and itemized receipts.</p>
      <p><code>React 18</code> <code>TypeScript</code> <code>Node 22</code> <code>Drizzle</code> <code>PostgreSQL 16</code> <code>VitePress</code></p>
      <p>🛡️ Argon2id · JWT in HTTP-only cookies · strict CSP</p>
      <a href="https://github.com/elfilaliamin/finance-tracker">GitHub</a> · <a href="https://finance.aminlab.site/">Live</a> · <a href="https://finance.aminlab.site/docs/">Docs</a>
    </td>
    <td width="50%" valign="top">
      <h3>🐧 Self-Hosted Linux Server</h3>
      <p>Alpine Linux home server used as a persistent staging and self-hosting environment, built from an old laptop.</p>
      <p><code>Alpine</code> <code>Docker</code> <code>Nginx</code> <code>SSH</code></p>
      <p>🔑 SSH keys · firewall · automated updates · local DNS</p>
      <a href="https://medium.com/@elfilaliamin/turn-an-old-laptop-into-a-home-server-with-alpine-linux-docker-and-portainer-09fd982daf59">Read the story on Medium</a>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🤖 Autonomous Obstacle-Avoiding Robot</h3>
      <p>Wheeled robot built end to end: wiring, power management, sensor calibration, chassis and Arduino firmware that reads an ultrasonic sensor and steers DC motors around obstacles.</p>
      <p><code>Arduino</code> <code>C/C++</code> <code>Ultrasonic sensor</code> <code>DC motors</code> · <a href="https://www.linkedin.com/feed/update/urn:li:activity:7346212816170741770/">See it in action</a></p>
    </td>
  </tr>
</table>

---

## 🏗️ How I ship and host my apps

```mermaid
flowchart LR
    U([🌍 User]) --> CF[☁️ Cloudflare<br/>Zero Trust Tunnel]
    CF --> NG[🧭 Nginx<br/>reverse proxy]
    NG --> FE[⚛️ React SPA]
    NG --> API[🟢 Node + Express API]
    API --> DB[(🐘 PostgreSQL)]
    GH[🐙 GitHub Actions CI] -. deploy .-> DC[🐳 Docker Compose]
    DC -.- NG
    subgraph HOME[🐧 Alpine Linux home server]
      NG
      FE
      API
      DB
      DC
    end
```

---

## 🧰 Tech stack

<div align="center">

**Languages & frameworks**

<img src="https://skillicons.dev/icons?i=js,ts,react,vite,tailwind,nodejs,express,postgres,mysql,python,arduino,c&perline=12" alt="stack" />

**DevOps & tools**

<img src="https://skillicons.dev/icons?i=docker,nginx,linux,git,github,githubactions,cloudflare,ps&perline=8" alt="devops" />

</div>

---

## 📊 Most used languages

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=elfilaliamin&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="top languages" />
</div>

---

## 🤝 Let's connect

<div align="center">

I'm currently looking for **junior full-stack or backend roles**. If you've got a practical, real-world problem to solve, let's talk.

[![Email me](https://img.shields.io/badge/📫_elfilaliamin.design@gmail.com-0e75b6?style=for-the-badge)](mailto:elfilaliamin.design@gmail.com)

[<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" height="30" alt="Medium" />](https://medium.com/@elfilaliamin)&nbsp;&nbsp;
[<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" height="30" alt="Facebook" />](https://fb.com/med.amin.elfilali)&nbsp;&nbsp;
[<img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" height="30" alt="Instagram" />](https://instagram.com/elfilali.medamin)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" alt="footer" />
