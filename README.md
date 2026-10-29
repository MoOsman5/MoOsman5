<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Mohamed Osman — Senior Backend Engineer"/>
</p>

<p align="center">
  <a href="https://mohamed-osman.com"><img src="https://img.shields.io/badge/Portfolio-mohamed--osman.com-0b1224?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/mohamed-osman-eg"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:imohamedosmann@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/MoOsman_5/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

## 👋 About me

I design and build backend systems that have to stay fast as the data grows.

At **ABS Courier** I designed and built the company's logistics platform from scratch, replacing a purchased legacy system. It now handles **20M+ shipments a year for 1,000+ users**, and I lead the team of 5 backend engineers behind it.

```ts
const mohamed = {
  role: "Senior Backend Engineer · Backend Team Lead @ ABS Courier",
  location: "Giza, Egypt 🇪🇬",
  stack: ["TypeScript", "Node.js", "NestJS", "PostgreSQL", "Redis", "Bull", "Docker", "AWS"],
  focus: ["database performance", "queue-based processing", "multi-tenant SaaS"],
  currently: "re-architecting the platform into a multi-tenant SaaS for courier companies",
  alsoShips: ["React", "Next.js", "React Native"],
};
```

## 🏗️ The platform I built

<p align="center">
  <img src="./assets/architecture.svg" width="100%" alt="ABS Courier platform architecture"/>
</p>

| Problem | What I did |
| --- | --- |
| Shipment tables growing every day | Partitioned high-volume tables by date, keeping query times flat as the dataset grew |
| Reporting load hitting the primary DB | Added PostgreSQL read replicas behind PgBouncer and routed lag-tolerant reads off the primary |
| Slow, blocking background work | Moved bulk ingest, WhatsApp notifications and tracking events onto Bull queues with a dedicated worker |
| API latency | Introduced a Redis caching layer, improving response times **~3.7x** |
| Schema changes on live data | Ran zero-downtime migrations on live high-volume tables |
| External integrations | Built the public shipment-tracking and partner-facing APIs |

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,express,graphql,postgres,redis,mysql,mongodb&perline=9&theme=dark" alt="Backend and databases"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=docker,aws,nginx,githubactions,prometheus,grafana,linux,react,nextjs&perline=9&theme=dark" alt="Infrastructure and frontend"/>
</p>

<p align="center"><sub>Also: Bull queues · PgBouncer · OpenTelemetry · Loki · event-driven design · Architecture Decision Records</sub></p>

## 📈 GitHub activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=MoOsman5&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0b1224" alt="GitHub stats"/>
  <img height="170" src="https://streak-stats.demolab.com?user=MoOsman5&theme=tokyonight&hide_border=true&background=0b1224" alt="GitHub streak"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MoOsman5/MoOsman5/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/MoOsman5/MoOsman5/output/github-snake.svg" alt="Contribution snake"/>
  </picture>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MoOsman5&label=Profile%20views&color=e0234e&style=flat-square" alt="Profile views"/>
</p>
