<img src="assets/hero.svg" width="100%" alt="Mradul Garg: full-stack developer who builds AI products and ships them to production"/>

<p align="center">
  <a href="https://my-portfolio-nu-mauve-3hwthnyqyz.vercel.app/"><img src="https://img.shields.io/badge/portfolio-0B0F17?style=for-the-badge&logo=vercel&logoColor=A3E635" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/mradul-garg-972ab7339/"><img src="https://img.shields.io/badge/linkedin-0B0F17?style=for-the-badge&logo=linkedin&logoColor=A3E635" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/Mradul_Garg/"><img src="https://img.shields.io/badge/leetcode-0B0F17?style=for-the-badge&logo=leetcode&logoColor=A3E635" alt="LeetCode"/></a>
  <a href="mailto:mradulgarg2005@gmail.com"><img src="https://img.shields.io/badge/mradulgarg2005@gmail.com-0B0F17?style=for-the-badge&logo=gmail&logoColor=A3E635" alt="Email"/></a>
</p>

<p align="center">
  <img src="assets/terminal.svg" width="88%" alt="Terminal: whoami prints Mradul Garg, full-stack developer, Ghaziabad, India. focus.txt lists MERN apps in production on Docker, Nginx and AWS EC2; AI products on a multi-provider LLM layer; Chrome extensions with safety rails; DSA in C++. deploy.sh deploys CodeVerse live."/>
</p>

## 🚢 Things I've shipped

### CodeVerse: interview prep that runs in production
<sub><a href="https://interviewlattice.duckdns.org/"><b>Live ↗</b></a> · <a href="https://github.com/mradul-08/interview_platform"><b>Code</b></a></sub>

One place to prepare for interviews: DSA practice with real code execution, aptitude tests, mock interviews, study groups and chat. I built it end to end and run it on my own server.

<img src="assets/codeverse-flow.svg" width="100%" alt="CodeVerse architecture: React browser to Nginx over HTTPS to the Express API, which runs code in Docker sandboxes, stores data in MongoDB and hosts mock interviews on LiveKit."/>

<details>
<summary><b>What's inside</b></summary>

- Submitted code runs in short-lived Docker containers with **no network access** and a read-only filesystem (C++, Java, Python, JavaScript)
- Problems with test cases, verdicts, discussions, bookmarks and sheets
- Timed aptitude tests with analytics, streaks and badges
- Mock interviews in LiveKit rooms, study groups with leaderboards, direct messages and notifications
- Production on Ubuntu EC2: Nginx for HTTPS, systemd restarts, a health check every 5 minutes, and daily MongoDB backups kept for 14 days
</details>

`React 19` `Vite` `Express 5` `MongoDB` `Socket.IO` `Passport` `BullMQ` `Docker` `Nginx` `AWS EC2`

---

### GenWeb.ai: describe a website, get a live website
<sub><a href="https://genweb-ai-delta.vercel.app/"><b>Live ↗</b></a> · <a href="https://github.com/mradul-08/Genweb.ai"><b>Code</b></a></sub>

Type an idea in plain words and get a complete responsive website. Keep chatting to change it ("add a dark mode toggle"), then deploy it to a public URL in one click.

<img src="assets/genweb-flow.svg" width="100%" alt="GenWeb.ai flow: your idea goes through a prompt enhancer, then an AI provider with fallback across Groq, Mistral, Cerebras and OpenRouter, becomes responsive HTML and is deployed to a live URL."/>

<details>
<summary><b>What's inside</b></summary>

- If one AI provider is down or rate-limited, the next one takes over, with key rotation and availability tracking
- Edits by chat change only the part you asked for and keep the rest of the design
- Source view with direct editing, undo and redo, and desktop, tablet and mobile previews
- Dashboard with search, thumbnails and deployment status; redeploy or take a site offline
- Google sign-in through Firebase, JWT cookie sessions, and Razorpay credit purchases with signature checks
</details>

`React` `Vite` `Framer Motion` `Node.js` `Express` `MongoDB` `Firebase` `Razorpay`

---

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📨 LinkedIn Smart Messenger</h3>
      <sub><a href="https://github.com/mradul-08/linkedin-smart-messenger"><b>Code</b></a> · v4.2.0</sub>
      <p>A Chrome extension for personal LinkedIn outreach. It has its own search language (<code>company:google -intern</code>), typo-tolerant people search, an inbox reply system, schedules, follow-ups and AI drafts. It never sends anything until you press Yes, and it keeps to daily limits.</p>
      <code>Manifest V3</code> <code>JavaScript</code> <code>Claude API</code> <code>Playwright</code>
    </td>
    <td width="50%" valign="top">
      <h3>🎨 Portfolio</h3>
      <sub><a href="https://my-portfolio-nu-mauve-3hwthnyqyz.vercel.app/"><b>Live ↗</b></a> · <a href="https://github.com/mradul-08/MY-PORTFOLIO"><b>Code</b></a></sub>
      <p>My animated portfolio. It has a contact form and a password-protected admin area where I upload new resume versions to Vercel Blob, so the live resume changes without a redeploy.</p>
      <code>Next.js</code> <code>TypeScript</code> <code>GSAP</code> <code>Framer Motion</code>
    </td>
  </tr>
</table>

## 🧰 Toolbox

| I write | I build with | I ship with |
|:-:|:-:|:-:|
| <img src="https://skillicons.dev/icons?i=cpp,c,js,ts,html,css&perline=3&theme=dark" alt="C++, C, JavaScript, TypeScript, HTML, CSS"/> | <img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,nodejs,express,mongodb,redis,firebase&perline=3&theme=dark" alt="React, Next.js, Redux, Tailwind, Node.js, Express, MongoDB, Redis, Firebase"/> | <img src="https://skillicons.dev/icons?i=docker,aws,nginx,linux,git,postman&perline=3&theme=dark" alt="Docker, AWS, Nginx, Linux, Git, Postman"/> |

**LLMs I plug in:** `Groq` · `Mistral` · `Cerebras` · `SambaNova` · `OpenRouter` · `Cloudflare Workers AI` · `Claude`

## 📈 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mradul-08&background=0B0F17&border=1E293B&ring=A3E635&fire=FB923C&currStreakNum=F1F5F9&sideNums=F1F5F9&currStreakLabel=A3E635&sideLabels=CBD5E1&dates=64748B&stroke=1E293B" width="49%" alt="GitHub streak"/>
  <a href="https://leetcode.com/u/Mradul_Garg/"><img src="https://leetcard.jacoblin.cool/Mradul_Garg?theme=dark&font=JetBrains%20Mono&ext=activity&border=0&radius=10" width="49%" alt="LeetCode stats"/></a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mradul-08/mradul-08/output/snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/mradul-08/mradul-08/output/snake.svg" width="100%" alt="Snake eating my contribution graph"/>
</picture>

<p align="center"><code>$ exit</code> · thanks for stopping by. I'm open to SDE internships, freelance work and full-time roles: <a href="mailto:mradulgarg2005@gmail.com">say hi</a>.</p>
