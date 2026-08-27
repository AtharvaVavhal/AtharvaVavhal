<div align="center">

# Atharva Vavhal

**Java Backend Engineer · Full-Stack Developer · Software Engineer**

Building backend-heavy systems on Java and Spring Boot, with full-stack products and applied AI on the side.
B.Tech Computer Engineering, VIT Pune · Class of 2029

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-vavhal/)
[![GitHub](https://img.shields.io/badge/GitHub-141414?style=flat-square&logo=github&logoColor=white)](https://github.com/AtharvaVavhal)

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

`React 19` `TypeScript` `Vite` — backend: `Java 21` `Spring Boot` `MySQL` (in progress)

[Live preview](https://spidosoft-erp-ch48.vercel.app/) · [Repository](https://github.com/AtharvaVavhal/spidosoft-erp) *(private)*

---

### PrintForge — Custom Print Commerce Platform
*Modular monolith · Database-enforced correctness · Payment reliability engineering*

A full-stack commerce platform for custom printing, architected around a principle I take seriously: **correctness lives in the database, not in application-level hope.** The frozen architecture blueprint specifies a NestJS/Prisma backend and PostgreSQL schema built to survive double-clicks, retried payments, and out-of-order webhooks by construction — not by convention.

Concretely, that means: a `PaymentAttempt` model with a partial unique index enforcing *at most one captured payment per order*, checkout wrapped in a single transaction that commits before any external Razorpay call, idempotent webhook ingestion via a unique event ID, and a Postgres-native transactional outbox (`FOR UPDATE SKIP LOCKED`) for notifications instead of reaching for Kafka or RabbitMQ before the scale justifies it.

The full module structure, the complete 20-model Prisma schema, and JWT auth infrastructure (rotation, reuse detection, session revocation) are built. Business logic behind each endpoint is the next phase — the services exist as scaffolded stubs, not yet wired to working routes.

`NestJS` `Prisma` `PostgreSQL` `TypeScript` `JWT` — Razorpay integration designed, not yet wired

[Repository](https://github.com/AtharvaVavhal/printforge) *(private)*

---

### Vahak (वाहक) — Offline-First Parcel Delivery
*Smart Kopargaon Hackathon 2026 · Team FaultLine · PS014*

A hackathon system-design project proposing parcel delivery riding on existing public bus routes instead of new fleet infrastructure. The core engineering idea: delivery handover confirmed by a **signed QR/PIN token — nonce-based, time-bound, single-use — verified entirely on-device**, so confirmation works even with zero connectivity at the point of handover.

Designed around an offline-first mobile client (React Native, WatermelonDB/SQLite) writing to a local outbox first and syncing idempotently to a NestJS/PostgreSQL+PostGIS backend on reconnect, with role-based access for sender, conductor, recipient, and admin inside a single codebase. This is a proposed architecture and hackathon prototype, not a validated production system — presented here as evidence of systems thinking around offline sync, event ordering, and security under unreliable connectivity, not as a finished product.

`React Native` `NestJS` `PostgreSQL` `PostGIS` `WatermelonDB` — hackathon prototype, PS014

<br/>

## Technical Stack

**Core Engineering**
Java · Spring Boot · Spring Security · REST APIs · JPA / Hibernate · PostgreSQL · Docker

**Full-Stack**
React · TypeScript · Vite · Node.js · NestJS · React Native

**Data**
PostgreSQL · MySQL · MongoDB · Redis · SQLite · Prisma · PostGIS

**Currently Exploring**
System Design · Distributed Systems · AI/ML · RAG · LLM Applications

<br/>

## Engineering Journey

```
DSA → OOP → Databases → Backend Development → Spring Boot → Security → System Design → Scalable Systems
```

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
