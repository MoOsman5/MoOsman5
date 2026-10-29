<h1 align="center">Hi, I'm Mohamed Osman 👋</h1>
<h3 align="center">Senior Backend Engineer · NestJS · PostgreSQL · Distributed systems</h3>

<p align="center">
  <a href="https://mohamed-osman.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/mohamed-osman-2114b4240/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:imohamedosmann@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/MoOsman_5/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

---

### About me

I design and build backend systems that have to stay fast as the data grows.

At **ABS Courier** I designed and built the company's logistics platform from scratch, replacing a purchased legacy system. It now handles **20M+ shipments a year for 1,000+ users**, and I lead the team of 5 backend engineers behind it.

- 🏗️ Currently re-architecting the platform into a **multi-tenant SaaS** for external courier companies
- 🧑‍🏫 Teaching coding and robotics to young learners with the Digital Egypt Cubs Initiative (DECI)
- 🏆 ECPC competitor (Egyptian Collegiate Programming Contest)
- 📍 Giza, Egypt

### What I've built recently

| Problem | What I did |
| --- | --- |
| Shipment tables growing every day | Partitioned high-volume tables by date, keeping query times flat as the dataset grew |
| Reporting load hitting the primary DB | Added PostgreSQL read replicas behind PgBouncer and routed lag-tolerant reads off the primary |
| Slow, blocking background work | Moved bulk ingest, WhatsApp notifications and tracking events onto Bull queues with a dedicated worker |
| API latency | Introduced a Redis caching layer, improving response times **~3.7x** |
| Schema changes on live data | Ran zero-downtime migrations on live high-volume tables |
| External integrations | Built the public shipment-tracking and partner-facing APIs |

### Tech stack

**Backend**

<p>
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,express,graphql&theme=dark" alt="Backend"/>
</p>

**Databases & caching**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,redis,mysql,mongodb&theme=dark" alt="Databases"/>
</p>

**Infrastructure & observability**

<p>
  <img src="https://skillicons.dev/icons?i=docker,aws,nginx,githubactions,prometheus,grafana,git,linux&theme=dark" alt="Infrastructure"/>
</p>

**Frontend (when needed)**

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark" alt="Frontend"/>
</p>

Also: Bull queues · PgBouncer · OpenTelemetry · Loki · event-driven design · Architecture Decision Records

### GitHub stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MoOsman5&show_icons=true&count_private=true&theme=github_dark&hide_border=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MoOsman5&layout=compact&theme=github_dark&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MoOsman5&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>
