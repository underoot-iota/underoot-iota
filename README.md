<h1 align="center">Shantanu Chaudhary</h1>

<p align="center"><strong>Backend engineer — payments infrastructure, distributed systems, and LLM agents that run in production.</strong></p>

<p align="center">
  <a href="https://underoot-iota.github.io"><img src="https://img.shields.io/badge/Portfolio-underoot--iota.github.io-8e4327?style=flat-square" alt="Portfolio"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/underoot-iota/"><img src="https://img.shields.io/badge/LinkedIn-Shantanu%20Chaudhary-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Shantanu Chaudhary on LinkedIn"></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Bengaluru,%20India-IST%20%2B05:30-2b2b2b?style=flat-square" alt="Bengaluru, India">
  &nbsp;
  <img src="https://visitor-badge.laobi.icu/badge?page_id=underoot-iota.underoot-iota" alt="profile visitors">
</p>

---

### About

I'm a backend engineer in Bengaluru working on **payments infrastructure and distributed systems**. At **slice** I own the bill-payments backend — the Go service behind every BBPS bill in the app, carrying **1.7M+ transactions a month** — and I'm on call for it and three other services on the payments path. Go and Java over gRPC and REST, Kafka pipelines, PostgreSQL, Redis, Kubernetes and ArgoCD on AWS. Most of my time goes into making write paths correct under concurrency, keeping batch pipelines inside their window, and designing services so the next feature is a small change instead of a migration.

I also **build with LLM agents, not just alongside them**. I work on an agent that reviews every production deploy — it reads the metrics, the logs and the code diff and decides whether a release is doing what it claimed it would. Python, FastAPI, Temporal, Claude on AWS Bedrock. The interesting problem there isn't prompting; it's that an agent holding production credentials is reading attacker-influenceable text, so the trust boundaries matter more than the reasoning does.

I built the **Claude Code** harness my team ships through, too: a task orchestrator over explorer, planner and reviewer subagents, an in-repo knowledge base with eval suites, and MCP-backed observability skills that turn an alert into a live investigation.

Before slice I **built DreamPlay's backend from the ground up at Dream11** — matchmaking, contest join, a Glicko rating system — joining when it was an idea and staying through **0 → 1.5M+ users in six months**. Earlier, an internship at **BrowserStack**. B.Tech in Information Technology, IIIT Allahabad.

### Building on the side

- **Digital Kanha** — a Godot 4 Android companion app, built solo: a manifest-driven 2D cutout character assembled at runtime, a headless-tested time and save simulation with versioned migrations, and a JSON content pipeline validated against schema. *Private while the art pipeline settles.*
- **Reel Reminder** — turns the "saved reels I'll never watch" pile into one daily nudge. Share a link from any app, it pulls metadata, tags it with an LLM, and reminds you once a day. React Native + Expo on Supabase — Postgres with RLS, Edge Functions, pg_cron. *Private while I make the Android share-sheet patches durable.*
- **[iotaCut](https://github.com/underoot-iota/iotaCut)** — poking at an open-source CapCut replacement with MCP support.

### Earlier

[sql_editor](https://github.com/underoot-iota/sql_editor) — a browser-based SQL editor · [movie recommendations with a knowledge graph](https://github.com/underoot-iota/movie_recommendation_system_with_knowledge_graph) — Python · [TOMS](https://github.com/underoot-iota/TOMS_SE_Project) — a Flutter/Firebase IoT app · [Sparsh 2024](https://sparsh2024.vercel.app) — my college fest's site · plus marketing sites for a couple of real businesses. Useful groundwork, from before the backend work.

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,java,python,ts,react,postgres,redis,kafka,aws,docker,kubernetes,git&perline=6" alt="Go, Java, Python, TypeScript, React, PostgreSQL, Redis, Kafka, AWS, Docker, Kubernetes, Git">
</p>

<p align="center"><sub>Go · Java · Python · TypeScript/React · gRPC · Kafka · PostgreSQL · Redis · Temporal · Elasticsearch · AWS · Docker · Kubernetes · ArgoCD · Grafana · LLM agents · Claude Code · MCP · Langfuse · AWS Bedrock</sub></p>

### Away from the keyboard

Digital art and Photoshop. Anime: Vinland Saga (farming arc supremacy), Mushishi, Monster, Berserk (1997 > everything), Frieren, Cowboy Bebop. Games: Outer Wilds (don't google anything), Hades, Celeste (chapter 9 pending), Disco Elysium, Elden Ring (still stuck on Malenia).

---

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=underoot-iota&show_icons=true&theme=gotham&hide_border=true&count_private=true&include_all_commits=true" alt="Shantanu Chaudhary GitHub stats" height="165">
  <img src="https://streak-stats.demolab.com/?user=underoot-iota&theme=gotham&hide_border=true" alt="GitHub contribution streak" height="165">
</p>
