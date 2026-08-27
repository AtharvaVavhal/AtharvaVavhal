<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141414,100:2b2b2b&height=4&width=1000" width="100%" alt=""/>

<br/>

# Atharva Vavhal

<sub>JAVA BACKEND ENGINEER &nbsp;·&nbsp; FULL-STACK DEVELOPER &nbsp;·&nbsp; SOFTWARE ENGINEER</sub>

<br/>
<br/>

Building backend-heavy systems on Java and Spring Boot, with full-stack products and applied AI on the side.
<br/>
B.Tech Computer Engineering, VIT Pune · Class of 2029

<br/>
<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-vavhal/)
[![GitHub](https://img.shields.io/badge/GitHub-141414?style=flat-square&logo=github&logoColor=white)](https://github.com/AtharvaVavhal)

<br/>
<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141414,100:2b2b2b&height=4&width=1000" width="100%" alt=""/>

</div>

<br/>

## Engineering Focus

My direction is deliberate: **Java → Spring Boot → backend architecture → databases → security → system design → scalable software.**

I build full-stack systems end to end and I'm exploring applied AI (RAG, LLM-backed applications) alongside that core path — not as a replacement for it. I care more about invariants holding under concurrent, retried, or partial-failure conditions than about how many frameworks a project name-drops.

<br/>

## Selected Work

### Spidosoft ERP — Enterprise ERP
*Modular monolith · Master data architecture · Built with an industry partner*

A modular ERP system being engineered for **Spidosoft Technologies OPC Pvt. Ltd.**, centered on a single source of truth for item, customer, and supplier master data. I lead the team as **Architecture & Backend lead**, with a faculty guide from the VIT Pune Computer Engineering department.

The system is architected as a modular monolith — React/TypeScript frontend, Java/Spring Boot backend, MySQL persistence — with the request lifecycle, security model, and module boundaries fully designed before implementation began. The React/TypeScript frontend foundation and a deployed landing experience are live; the Spring Boot backend, authentication, and master-data modules are in active development against that design.

<img src="https://img.shields.io/badge/React_19-141414?style=flat-square&logo=react&logoColor=61DAFB" height="20"/> <img src="https://img.shields.io/badge/TypeScript-141414?style=flat-square&logo=typescript&logoColor=3178C6" height="20"/> <img src="https://img.shields.io/badge/Vite-141414?style=flat-square&logo=vite&logoColor=646CFF" height="20"/> <img src="https://img.shields.io/badge/Java_21-141414?style=flat-square&logo=openjdk&logoColor=ED8B00" height="20"/> <img src="https://img.shields.io/badge/Spring_Boot-141414?style=flat-square&logo=springboot&logoColor=6DB33F" height="20"/> <img src="https://img.shields.io/badge/MySQL-141414?style=flat-square&logo=mysql&logoColor=4479A1" height="20"/> <sub>· backend in progress</sub>

[Live preview](https://spidosoft-erp-ch48.vercel.app/) · [Repository](https://github.com/AtharvaVavhal/spidosoft-erp) <sub>(private)</sub>

---

### PrintForge — Custom Print Commerce Platform
*Modular monolith · Database-enforced correctness · Payment reliability engineering*

A full-stack commerce platform for custom printing, architected around a principle I take seriously: **correctness lives in the database, not in application-level hope.** The frozen architecture blueprint specifies a NestJS/Prisma backend and PostgreSQL schema built to survive double-clicks, retried payments, and out-of-order webhooks by construction — not by convention.

Concretely, that means: a `PaymentAttempt` model with a partial unique index enforcing *at most one captured payment per order*, checkout wrapped in a single transaction that commits before any external Razorpay call, idempotent webhook ingestion via a unique event ID, and a Postgres-native transactional outbox (`FOR UPDATE SKIP LOCKED`) for notifications instead of reaching for Kafka or RabbitMQ before the scale justifies it.

The full module structure, the complete 20-model Prisma schema, and JWT auth infrastructure (rotation, reuse detection, session revocation) are built. Business logic behind each endpoint is the next phase — the services exist as scaffolded stubs, not yet wired to working routes.

<img src="https://img.shields.io/badge/NestJS-141414?style=flat-square&logo=nestjs&logoColor=E0234E" height="20"/> <img src="https://img.shields.io/badge/Prisma-141414?style=flat-square&logo=prisma&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/TypeScript-141414?style=flat-square&logo=typescript&logoColor=3178C6" height="20"/> <img src="https://img.shields.io/badge/JWT-141414?style=flat-square&logo=jsonwebtokens&logoColor=white" height="20"/> <sub>· Razorpay designed, not yet wired</sub>

[Repository](https://github.com/AtharvaVavhal/printforge) <sub>(private)</sub>

---

### Vahak (वाहक) — Offline-First Parcel Delivery
*Smart Kopargaon Hackathon 2026 · Team FaultLine · PS014*

A hackathon system-design project proposing parcel delivery riding on existing public bus routes instead of new fleet infrastructure. The core engineering idea: delivery handover confirmed by a **signed QR/PIN token — nonce-based, time-bound, single-use — verified entirely on-device**, so confirmation works even with zero connectivity at the point of handover.

Designed around an offline-first mobile client (React Native, WatermelonDB/SQLite) writing to a local outbox first and syncing idempotently to a NestJS/PostgreSQL+PostGIS backend on reconnect, with role-based access for sender, conductor, recipient, and admin inside a single codebase. This is a proposed architecture and hackathon prototype, not a validated production system — presented here as evidence of systems thinking around offline sync, event ordering, and security under unreliable connectivity, not as a finished product.

<img src="https://img.shields.io/badge/React_Native-141414?style=flat-square&logo=react&logoColor=61DAFB" height="20"/> <img src="https://img.shields.io/badge/NestJS-141414?style=flat-square&logo=nestjs&logoColor=E0234E" height="20"/> <img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/PostGIS-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/WatermelonDB-141414?style=flat-square&logo=sqlite&logoColor=lightblue" height="20"/> <sub>· hackathon prototype, PS014</sub>

<br/>

## Technical Stack

<table>
<tr>
<td width="140" valign="top"><sub><b>CORE</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Java-141414?style=flat-square&logo=openjdk&logoColor=ED8B00" height="22"/>
<img src="https://img.shields.io/badge/Spring_Boot-141414?style=flat-square&logo=springboot&logoColor=6DB33F" height="22"/>
<img src="https://img.shields.io/badge/Spring_Security-141414?style=flat-square&logo=springsecurity&logoColor=6DB33F" height="22"/>
<img src="https://img.shields.io/badge/REST_APIs-141414?style=flat-square&logo=fastapi&logoColor=white" height="22"/>
<img src="https://img.shields.io/badge/Hibernate-141414?style=flat-square&logo=hibernate&logoColor=59666C" height="22"/>
<img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="22"/>
<img src="https://img.shields.io/badge/Docker-141414?style=flat-square&logo=docker&logoColor=2496ED" height="22"/>
</td>
</tr>
<tr>
<td width="140" valign="top"><sub><b>FULL-STACK</b></sub></td>
<td>
<img src="https://img.shields.io/badge/React-141414?style=flat-square&logo=react&logoColor=61DAFB" height="22"/>
<img src="https://img.shields.io/badge/TypeScript-141414?style=flat-square&logo=typescript&logoColor=3178C6" height="22"/>
<img src="https://img.shields.io/badge/Vite-141414?style=flat-square&logo=vite&logoColor=646CFF" height="22"/>
<img src="https://img.shields.io/badge/Node.js-141414?style=flat-square&logo=nodedotjs&logoColor=339933" height="22"/>
<img src="https://img.shields.io/badge/NestJS-141414?style=flat-square&logo=nestjs&logoColor=E0234E" height="22"/>
<img src="https://img.shields.io/badge/React_Native-141414?style=flat-square&logo=react&logoColor=61DAFB" height="22"/>
</td>
</tr>
<tr>
<td width="140" valign="top"><sub><b>DATA</b></sub></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="22"/>
<img src="https://img.shields.io/badge/MySQL-141414?style=flat-square&logo=mysql&logoColor=4479A1" height="22"/>
<img src="https://img.shields.io/badge/MongoDB-141414?style=flat-square&logo=mongodb&logoColor=47A248" height="22"/>
<img src="https://img.shields.io/badge/Redis-141414?style=flat-square&logo=redis&logoColor=DC382D" height="22"/>
<img src="https://img.shields.io/badge/SQLite-141414?style=flat-square&logo=sqlite&logoColor=lightblue" height="22"/>
<img src="https://img.shields.io/badge/Prisma-141414?style=flat-square&logo=prisma&logoColor=white" height="22"/>
<img src="https://img.shields.io/badge/PostGIS-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="22"/>
</td>
</tr>
<tr>
<td width="140" valign="top"><sub><b>EXPLORING</b></sub></td>
<td>
<img src="https://img.shields.io/badge/System_Design-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/Distributed_Systems-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/AI/ML-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/RAG-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/LLM_Applications-141414?style=flat-square" height="22"/>
</td>
</tr>
</table>

<br/>

## Engineering Journey

<div align="center">

`DSA` → `OOP` → `Databases` → `Backend Development` → `Spring Boot` → `Security` → `System Design` → `Scalable Systems`

</div>

This is a direction I'm actively working through, not a completed ladder — each project above is chosen to push further along it.

<br/>

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AtharvaVavhal&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AtharvaVavhal&layout=compact&hide_border=true&theme=default" alt="Top Languages" height="165" />
</div>

<br/>

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-vavhal/)
[![GitHub](https://img.shields.io/badge/GitHub-141414?style=flat-square&logo=github&logoColor=white)](https://github.com/AtharvaVavhal)

<br/>

<img src="https://komarev.com/ghpvc/?username=AtharvaVavhal&style=flat-square&color=141414&label=profile+views" alt="Profile views" height="20"/>
