<h1 align="center">Hi 👋, I'm Nico Uicich</h1>
<h3 align="center">Senior Software Engineer · fintech + LLMs</h3>
<p align="center">Buenos Aires, Argentina · remote</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nicolas-uicich"><img src="https://img.shields.io/badge/LinkedIn-nicolas--uicich-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Nicouicich"><img src="https://img.shields.io/github/followers/Nicouicich?style=for-the-badge&logo=github&label=Followers" /></a>
  <a href="https://twitter.com/NicoUicich"><img src="https://img.shields.io/twitter/follow/NicoUicich?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

---

### 👨‍💻 About Me

I build the payments backend and the LLM layer on top of it.
5+ years in TypeScript and Node.js, the last two where money and AI meet.

Today I'm on the **Ramps team at Rise**, a global payroll platform that pays contractors in fiat and stablecoins. I work on money movement: virtual bank accounts, fiat on and off ramps, crypto withdrawals and a public payroll API.

Before that I led the backend for a platform with **25M+ users**.

---

### 🤖 What I've built on the LLM side

- 🗄️ **Agents over company data** — read-only SQL against a company's own databases plus RAG on pgvector over its documents, routed between Claude and OpenAI by task. Multi-tenant, with a public API to embed the agents anywhere. Live at [growe.ar](https://growe.ar).
- 🧾 **Extraction pipeline for a finance app** — chat messages, voice notes and receipt photos become structured transactions. Card and account numbers are masked before anything reaches the model. The LLM calls typed tools; the database does the math.
- 🏠 **Local-first home hub** — a 39-tool agent over cameras and smart devices on a 7B model through Ollama, with a cloud fallback. Weekly-retrained vision classifier, cross-camera person re-ID, natural-language event search and fully local voice.

I build with Claude Code every day and have shipped internal MCP servers and Claude Code skills for my team.

> Most of this lives in private repos. The contribution graph below includes them.

---

### 🛠 Tech Stack

#### 🔧 Backend & Data

<p align="left">
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="36" height="36" alt="TypeScript" title="TypeScript" /></a>
  <a href="https://nodejs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" height="36" alt="Node.js" title="Node.js" /></a>
  <a href="https://nestjs.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" width="36" height="36" alt="NestJS" title="NestJS" /></a>
  <a href="https://fastify.dev/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastify/fastify-original.svg" width="36" height="36" alt="Fastify" title="Fastify" /></a>
  <a href="https://www.python.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" height="36" alt="Python" title="Python" /></a>
  <a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="36" height="36" alt="FastAPI" title="FastAPI" /></a>
  <a href="https://www.postgresql.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" height="36" alt="PostgreSQL" title="PostgreSQL" /></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="36" height="36" alt="MySQL" title="MySQL" /></a>
  <a href="https://www.mongodb.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="36" height="36" alt="MongoDB" title="MongoDB" /></a>
  <a href="https://redis.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="36" height="36" alt="Redis" title="Redis" /></a>
  <a href="https://kafka.apache.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="36" height="36" alt="Kafka" title="Kafka" /></a>
</p>

#### ☁️ Infra & Delivery

<p align="left">
  <a href="https://aws.amazon.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="36" height="36" alt="AWS" title="AWS" /></a>
  <a href="https://cloud.google.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="36" height="36" alt="GCP" title="Google Cloud" /></a>
  <a href="https://www.docker.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="36" height="36" alt="Docker" title="Docker" /></a>
  <a href="https://kubernetes.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" width="36" height="36" alt="Kubernetes" title="Kubernetes" /></a>
  <a href="https://github.com/features/actions" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" width="36" height="36" alt="GitHub Actions" title="GitHub Actions" /></a>
  <a href="https://vercel.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vercel/vercel-original.svg" width="36" height="36" alt="Vercel" title="Vercel" /></a>
  <a href="https://supabase.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" width="36" height="36" alt="Supabase" title="Supabase" /></a>
  <a href="https://www.cloudflare.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cloudflare/cloudflare-original.svg" width="36" height="36" alt="Cloudflare" title="Cloudflare" /></a>
</p>

#### 🧠 AI

<p align="left">
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/RAG%20%C2%B7%20pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="RAG / pgvector" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code" />
</p>

#### 🖥 Frontend when needed

<p align="left">
  <a href="https://vuejs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="36" height="36" alt="Vue.js" title="Vue.js" /></a>
  <a href="https://nuxt.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nuxtjs/nuxtjs-original.svg" width="36" height="36" alt="Nuxt" title="Nuxt" /></a>
  <a href="https://react.dev/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="36" height="36" alt="React" title="React" /></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="36" height="36" alt="Next.js" title="Next.js" /></a>
  <a href="https://tailwindcss.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="36" height="36" alt="Tailwind CSS" title="Tailwind CSS" /></a>
</p>

---

### 📊 GitHub Stats

<p align="left">
  <a href="https://github.com/Nicouicich"><img src="https://github-readme-stats.vercel.app/api?username=Nicouicich&show_icons=true&theme=radical&count_private=true&include_all_commits=true" alt="Nico's GitHub Stats" /></a>
  <a href="https://github.com/Nicouicich"><img src="https://github-readme-streak-stats.herokuapp.com/?user=Nicouicich&theme=radical" alt="GitHub streak" /></a>
</p>

---

### 🤝 Let's Connect

Building something where money and LLMs meet? Message me.

<p align="center">
  <a href="mailto:nico_uicich@outlook.com?subject=👋%20Hola%20Nico" target="_blank">
    <img src="https://img.shields.io/badge/Email-nico__uicich%40outlook.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/nicolas-uicich" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-@nicolas--uicich-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://growe.ar" target="_blank">
    <img src="https://img.shields.io/badge/growe.ar-live-22C55E?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
</p>

---

Thanks for visiting! 👋
