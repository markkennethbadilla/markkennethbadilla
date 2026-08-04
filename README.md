<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1215,25:1a3a2a,50:2d6a4f,100:52b788&height=230&section=header&text=Mark%20Kenneth%20Badilla&fontSize=42&fontColor=d8f3dc&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%C2%B7%20Cebu%20City%2C%20Philippines&descSize=15&descColor=95d5b2&descAlignY=55" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Crimson+Text&weight=600&size=22&duration=3500&pause=1200&color=95D5B2&center=true&vCenter=true&repeat=true&width=700&height=45&lines=planting+seeds+of+code+%E2%80%94+watching+systems+grow;every+project+is+a+living+ecosystem;rooted+in+craft%2C+reaching+for+the+sun" alt="Typing SVG" />
</a>

</div>

<br/>

### 🌱 &nbsp; The Seed

AI Engineer from Cebu City, Philippines. BSIT, Magna Cum Laude — CIT-University, class of 2025. Currently at **WeAssist**.

I build agentic harnesses — the gates, guardrails, and verification layers that let LLM agents write production code safely — and the production systems that come out of them. I believe in patient craftsmanship: plant good roots, prune what doesn't work, and let automation do the watering.

<div align="center">

> *"The best code is code that replaces manual work entirely."*
> 
> — me, mass-automating everything

</div>

---

### 🌿 &nbsp; The Canopy

<div align="center">

**Bedrock** &nbsp;·&nbsp; Languages & Runtimes

![TypeScript](https://img.shields.io/badge/TypeScript-2d6a4f?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-2d6a4f?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-2d6a4f?style=flat-square&logo=javascript&logoColor=white)
![Java](https://img.shields.io/badge/Java-2d6a4f?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-2d6a4f?style=flat-square&logo=postgresql&logoColor=white)

**Canopy** &nbsp;·&nbsp; Frameworks & Libraries

![Next.js](https://img.shields.io/badge/Next.js-40916c?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-40916c?style=flat-square&logo=react&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-40916c?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-40916c?style=flat-square&logo=node.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-40916c?style=flat-square&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-40916c?style=flat-square&logo=prisma&logoColor=white)

**Mycelium** &nbsp;·&nbsp; AI & Data

![OpenRouter](https://img.shields.io/badge/OpenRouter-52b788?style=flat-square&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-52b788?style=flat-square&logo=n8n&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-52b788?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-52b788?style=flat-square&logo=redis&logoColor=white)

**Watershed** &nbsp;·&nbsp; Infrastructure

![Cloudflare](https://img.shields.io/badge/Cloudflare-74c69d?style=flat-square&logo=cloudflare&logoColor=0b1215)
![Linux](https://img.shields.io/badge/Linux-74c69d?style=flat-square&logo=linux&logoColor=0b1215)
![Docker](https://img.shields.io/badge/Docker-74c69d?style=flat-square&logo=docker&logoColor=0b1215)
![Coolify](https://img.shields.io/badge/Coolify-74c69d?style=flat-square&logo=coolify&logoColor=0b1215)
![BullMQ](https://img.shields.io/badge/BullMQ%20%2F%20Redis-74c69d?style=flat-square&logo=redis&logoColor=0b1215)
![Git](https://img.shields.io/badge/Git-74c69d?style=flat-square&logo=git&logoColor=0b1215)

</div>

---

### 🪵 &nbsp; Groundwork

<div align="center">

*Infrastructure & Resilience — where the roots hold.*

</div>

**300+ self-authored static checks** across four production repos, chained into the build (gate suite, zero-warning lint, type checks) so an agent — or a tired human — physically cannot ship a regression. The gates audit themselves: I found a bypass in my own gate-skip logic and closed it the same day.

Underneath: **three self-hosted servers across three providers**, private network, nothing exposed to the public internet. Six live outage drills including killing the main server outright — back to writing in 66s, zero data lost. One **18-step zero-downtime deploy engine** ships five production apps byte-identically, and every deploy proves its backup restores before anything migrates. Cloudflare-fronted Linux, orchestrated with **Docker + Coolify**, **BullMQ/Redis** carrying the background work, multi-model **LLM cascades** and self-hosted voice/TTS pipelines on the same rails.

The philosophy: build the watering system once, then let it run unattended.

---

### 🗺️ &nbsp; Mapped Terrain

<table>
<tr>
<td colspan="2">

#### 🛡️ &nbsp; [public-agent-provisioning](https://github.com/markkennethbadilla/public-agent-provisioning) — Agent Guardrails Toolkit

> **Gate, don't ask.** A batteries-included toolkit that makes AI coding agents safe *by construction* — physical PreToolUse/Stop hooks, pre-commit/pre-push git gates, and a two-layer skill system that **block the wrong move and print the fix**, instead of hoping a prompt holds. Cross-platform, `SKILL.md`-native, zero bundled secrets.

`Physical guardrails` `Claude Code` `Hooks & Gates` `Cross-platform`

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td width="50%">

#### 🧹 &nbsp; [clean-pipe](https://github.com/markkennethbadilla/clean-pipe) — Data Normalization

> AI pipeline that cleans, validates, and normalizes messy data. Configurable rules, batch processing, LLM-assisted transforms.

`TypeScript` `OpenRouter` `Node.js`

</td>
<td width="50%">

#### ⚡ &nbsp; [flow-llm](https://github.com/markkennethbadilla/flow-llm) — Semantic Cache

> Caching layer for LLM APIs. Reduces redundant calls with semantic similarity matching. Drop-in middleware.

`TypeScript` `Node.js` `Embeddings`

</td>
</tr>
</table>



---

<div align="center">

<a href="mailto:markkennethbadilla@gmail.com">
  <img src="https://img.shields.io/badge/Email-74c69d?style=for-the-badge&logo=gmail&logoColor=0b1215" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=markkennethbadilla&color=2d6a4f&style=flat-square&label=Profile+Views" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1215,25:1a3a2a,50:2d6a4f,100:52b788&height=100&section=footer" width="100%" />

</div>
