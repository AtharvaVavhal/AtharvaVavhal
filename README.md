<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141414,100:2b2b2b&height=4&width=1000" width="100%" alt=""/>

<br/>

# Atharva Vavhal

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1200&color=8A8A8A&center=true&vCenter=true&width=560&lines=Java+Backend+Engineer;Full-Stack+Developer;Software+Engineer" alt="Typing SVG" />

<br/>

B.Tech Computer Engineering, VIT Pune · Class of 2029

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-vavhal/)
[![GitHub](https://img.shields.io/badge/GitHub-141414?style=flat-square&logo=github&logoColor=white)](https://github.com/AtharvaVavhal)
<img src="https://komarev.com/ghpvc/?username=AtharvaVavhal&style=flat-square&color=141414&label=profile+views" alt="Profile views" height="20"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141414,100:2b2b2b&height=4&width=1000" width="100%" alt=""/>

</div>

<br/>

## About

Java backend engineer working through **Java → Spring Boot → backend architecture → databases → security → system design → scalable software.**

I build full-stack systems end to end, and explore applied AI/ML — RAG and LLM-backed applications — alongside that core direction. I care more about invariants holding under concurrent, retried, or partial-failure conditions than about how many frameworks a project name-drops.

<br/>

## Current Focus

<div align="center">

`DSA` → `OOP` → `Databases` → `Backend Development` → `Spring Boot` → `Security` → `System Design` → `Scalable Systems`

</div>

This is an active engineering direction, not a completed ladder. Right now I'm going deeper into Java, Spring Boot, backend architecture, databases, transaction correctness, authentication/authorization, REST APIs, and system design — alongside applied AI/ML, RAG, and LLM applications.

<br/>

## Featured Projects

### Spidosoft ERP — Enterprise ERP
*Modular monolith · Master-data architecture*

A modular ERP system built for **Spidosoft Technologies OPC Pvt. Ltd.**, centered on a single source of truth for master data. I lead the project as **Architecture & Backend Lead**. The system is a modular monolith — Java 21/Spring Boot backend, React/TypeScript frontend, MySQL persistence — with JWT authentication and RBAC as part of the security model. The frontend foundation and a deployed landing experience are live; the backend and core modules are in active development.

<img src="https://img.shields.io/badge/Java_21-141414?style=flat-square&logo=openjdk&logoColor=ED8B00" height="20"/> <img src="https://img.shields.io/badge/Spring_Boot-141414?style=flat-square&logo=springboot&logoColor=6DB33F" height="20"/> <img src="https://img.shields.io/badge/React-141414?style=flat-square&logo=react&logoColor=61DAFB" height="20"/> <img src="https://img.shields.io/badge/TypeScript-141414?style=flat-square&logo=typescript&logoColor=3178C6" height="20"/> <img src="https://img.shields.io/badge/MySQL-141414?style=flat-square&logo=mysql&logoColor=4479A1" height="20"/> <sub>· backend in progress</sub>

[Repository](https://github.com/AtharvaVavhal/spidosoft-erp) · [Live preview](https://spidosoft-erp-ch48.vercel.app/)

---

### PrintForge — Custom Print Commerce Platform
*Modular monolith · Database-enforced correctness*

A commerce platform for custom printing, built around a NestJS/Prisma backend and a PostgreSQL schema engineered for correctness by construction. Concretely: `PaymentAttempt` uniqueness to enforce at most one captured payment per order, transactional checkout, idempotent payment webhook handling, a PostgreSQL transactional outbox, and JWT rotation with session revocation. Backend infrastructure and architecture are implemented; business services are still in development, and Razorpay integration is designed but not yet wired.

<img src="https://img.shields.io/badge/NestJS-141414?style=flat-square&logo=nestjs&logoColor=E0234E" height="20"/> <img src="https://img.shields.io/badge/Prisma-141414?style=flat-square&logo=prisma&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/JWT-141414?style=flat-square&logo=jsonwebtokens&logoColor=white" height="20"/> <sub>· Razorpay designed, not yet wired</sub>

[Repository](https://github.com/AtharvaVavhal/printforge)

---

### Vahak (वाहक) — Offline-First Parcel Delivery
*Smart Kopargaon Hackathon 2026 · PS014 · Team FaultLine*

A hackathon architecture/prototype for offline-first parcel delivery. Handover is verified with a signed, nonce-based, time-bound token checked on-device, so confirmation works without connectivity at the point of handover. Built around an offline-first mobile client (React Native, WatermelonDB/SQLite) syncing idempotently to a NestJS backend with PostgreSQL/PostGIS, with roles for sender, conductor, recipient, and admin. This is a hackathon prototype, not a production system — it demonstrates offline sync, event ordering, and security under unreliable connectivity.

<img src="https://img.shields.io/badge/React_Native-141414?style=flat-square&logo=react&logoColor=61DAFB" height="20"/> <img src="https://img.shields.io/badge/NestJS-141414?style=flat-square&logo=nestjs&logoColor=E0234E" height="20"/> <img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/PostGIS-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="20"/> <img src="https://img.shields.io/badge/SQLite-141414?style=flat-square&logo=sqlite&logoColor=lightblue" height="20"/> <sub>· hackathon prototype, PS014</sub>

<br/>

## Technical Stack

<table>
<tr>
<td width="150" valign="top"><sub><b>BACKEND & CORE</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Java-141414?style=flat-square&logo=openjdk&logoColor=ED8B00" height="22"/>
<img src="https://img.shields.io/badge/Spring_Boot-141414?style=flat-square&logo=springboot&logoColor=6DB33F" height="22"/>
<img src="https://img.shields.io/badge/Spring_Security-141414?style=flat-square&logo=springsecurity&logoColor=6DB33F" height="22"/>
<img src="https://img.shields.io/badge/Hibernate-141414?style=flat-square&logo=hibernate&logoColor=59666C" height="22"/>
<img src="https://img.shields.io/badge/REST_APIs-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/JWT-141414?style=flat-square&logo=jsonwebtokens&logoColor=white" height="22"/>
</td>
</tr>
<tr>
<td width="150" valign="top"><sub><b>FRONTEND & FULL-STACK</b></sub></td>
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
<td width="150" valign="top"><sub><b>DATABASES & INFRA</b></sub></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="22"/>
<img src="https://img.shields.io/badge/MySQL-141414?style=flat-square&logo=mysql&logoColor=4479A1" height="22"/>
<img src="https://img.shields.io/badge/MongoDB-141414?style=flat-square&logo=mongodb&logoColor=47A248" height="22"/>
<img src="https://img.shields.io/badge/Redis-141414?style=flat-square&logo=redis&logoColor=DC382D" height="22"/>
<img src="https://img.shields.io/badge/SQLite-141414?style=flat-square&logo=sqlite&logoColor=lightblue" height="22"/>
<img src="https://img.shields.io/badge/Prisma-141414?style=flat-square&logo=prisma&logoColor=white" height="22"/>
<img src="https://img.shields.io/badge/PostGIS-141414?style=flat-square&logo=postgresql&logoColor=4169E1" height="22"/>
<img src="https://img.shields.io/badge/Docker-141414?style=flat-square&logo=docker&logoColor=2496ED" height="22"/>
</td>
</tr>
<tr>
<td width="150" valign="top"><sub><b>ENGINEERING & EXPLORING</b></sub></td>
<td>
<img src="https://img.shields.io/badge/Git-141414?style=flat-square&logo=git&logoColor=F05032" height="22"/>
<img src="https://img.shields.io/badge/System_Design-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/Distributed_Systems-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/AI/ML-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/RAG-141414?style=flat-square" height="22"/>
<img src="https://img.shields.io/badge/LLM_Applications-141414?style=flat-square" height="22"/>
</td>
</tr>
</table>

<br/>

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AtharvaVavhal&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AtharvaVavhal&layout=compact&hide_border=true&theme=default" alt="Top Languages" height="165" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=AtharvaVavhal&theme=default&hide_border=true" alt="GitHub Streak" height="165" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/AtharvaVavhal/AtharvaVavhal/output/github-contribution-grid-snake.svg" alt="Contribution Snake" width="100%" />
</div>

<br/>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atharva-vavhal/)
[![GitHub](https://img.shields.io/badge/GitHub-141414?style=flat-square&logo=github&logoColor=white)](https://github.com/AtharvaVavhal)

<br/>
<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:141414,100:2b2b2b&height=4&width=1000" width="100%" alt=""/>

</div>
