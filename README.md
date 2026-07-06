<div align="center">

<!-- Dynamic header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Pratham%20Ranka&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Software%20Engineer%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20Open%20Source&descAlignY=55&descSize=16" width="100%" />

</div>

<br />

<!-- Typing animation -->
<div align="center">
  
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=1000&color=3B82F6&center=true&vCenter=true&multiline=false&width=700&lines=Shipped+payment+infra+for+%2419M%2B+AUM+%40+PAASA+(YC+S24);Engineered+distributed+sandbox+runtime+on+Kubernetes;Merged+PRs+into+20k%2B+star+OSS+repos;LeetCode+1500%2B+%E2%80%A2+Systems+%26+Concurrency)](https://git.io/typing-svg)

</div>

<br />

<!-- Social links -->
<div align="center">

[![Portfolio](https://img.shields.io/badge/prathamranka.in-0D1117?style=for-the-badge&logo=firefox&logoColor=3B82F6&labelColor=0D1117)](https://prathamranka.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prathamranka06)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prathamworks06@gmail.com)

</div>

---

## `$ whoami`

```
┌──────────────────────────────────────────────────────────────────┐
│  > CS Undergrad @ Thapar Institute of Engineering & Technology   │
│  > Ex SWE Intern @ PAASA (YC S24) — sole backend engineer        │
│  > Shipped production payment infrastructure at scale            │
│  > Open source contributor — merged into 20k★ repos              │
│  > Executive Board, OWASP TIET — ran HackOWASP with 1000+ devs   │
│  > Top 10 / 1200+ teams — HACK4DELHI 2026 (IEEE × Govt of Delhi) │
└──────────────────────────────────────────────────────────────────┘
```

I build systems where correctness isn't optional. Payment flows, distributed runtimes, concurrency-safe APIs — the kind of infra that needs to work right the first time, every time.

---

## `$ cat experience.log`

### PAASA · YC S24 · Software Engineer Intern
`Mar 2026 – May 2026 · Remote`

- Owned the full backend of a live fintech product managing **$19M+ AUM** — zero transaction integrity violations in production
- Architected payment infra: API Gateway → ELB → NGINX → Kafka → Docker/K8s, maintaining **p50 <1s and p99 <2.5s** under concurrent load
- Built blue-green K8s deployments with Prometheus + Grafana, reducing MTTR to **minutes** from anomaly to root cause
- Enforced Luhn algorithm, KYC/AML, GlomoPay webhooks with idempotency key enforcement and atomic rollback

---

## `$ git log --oneline --open-source`

| Repo | PR | Impact |
|------|-----|--------|
| **MedusaJS** `★20k+` | [#15634](https://github.com/medusajs/medusa/pull/15634) | Fixed cursor pagination correctness in product search |
| **MedusaJS** `★20k+` | [#15699](https://github.com/medusajs/medusa/pull/15699) | Fixed Vite dependency range compatibility regression |
| **Theneo** `YC W22` | Internal | Shipped validation logic + automated tests for CLI audit tooling |

---

## `$ ls -la projects/`

### LeaseForge — Kubernetes Sandbox Orchestration
`TypeScript · Kubernetes · Optimistic Concurrency Control · Apr–May 2026`

Engineered a K8s lease orchestration layer that prevents sandbox double-allocation under concurrent API load via `resourceVersion` semantics and optimistic concurrency control. Zero session state corruption across 8 coordinated sandbox runners on a multi-replica Kind cluster.

→ Lease contention · OCC conflicts · FIFO failure recovery · Promise-based locking · Process isolation

---

### StarSwap — High-Throughput Exchange API
`Node.js · PostgreSQL · Redis · Prisma · Docker · Feb–Mar 2026`

Replaced O(N) SQL scans with Redis sorted-set Token Bucket rate-limiting (O(log N)). Eliminated 100% of P2002 race conditions across parallel write operations via indexed cursor pagination and atomic transactions. Push-to-deploy CI/CD with zero manual errors.

→ RFC-compliant headers · Prisma connection pooling · Atomic rollback · GitHub Actions

---

## `$ tech --stack`

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Backend & Infra**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

## `$ github --stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=PrathamRanka&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=3B82F6&icon_color=06B6D4&text_color=e6edf3&ring_color=3B82F6&include_all_commits=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PrathamRanka&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=3B82F6&text_color=e6edf3&langs_count=8" height="165" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=PrathamRanka&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=3B82F6&ring=3B82F6&fire=06B6D4&currStreakLabel=3B82F6&sideLabels=e6edf3&dates=8b949e" width="70%" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=PrathamRanka&bg_color=0D1117&color=3B82F6&line=3B82F6&point=06B6D4&area=true&area_color=3B82F620&hide_border=true" width="100%" />

</div>

---

## `$ achievements --notable`

```
[✓] Top 10 / 1200+ teams  →  HACK4DELHI 2026 (IEEE × Government of Delhi)
[✓] 1500+ rating          →  LeetCode  |  200+ problems: graphs, DP, concurrency
[✓] 3 merged PRs          →  YC-backed OSS repos (MedusaJS, Theneo)
[✓] HackOWASP 8.0 OEC     →  80+ sponsors, 1000+ participants
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling" width="100%" />

<sub>Building production systems one commit at a time · <a href="https://prathamranka.in">prathamranka.in</a></sub>

</div>
