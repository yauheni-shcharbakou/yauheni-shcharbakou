<div align="center">

# Yauheni Shcharbakou

### Node.js Backend Engineer | Event-driven Microservices on Kafka + NestJS

**FinTech · AdTech · Web3**

11 microservices designed and shipped · $13.2M in monthly deposits · avg API response time cut 12x

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white" alt="NATS" />
<img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white" alt="gRPC" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />

</div>

Backend developer with 4+ years of commercial experience building event-driven microservice systems in TypeScript. I own the server side of a product end to end - from architecture design to shipped features - and care most about the parts that quietly break products: correct money math, ordered event processing, and dependable third-party integrations.

On my current product - a FinTech/Web3 platform for card issuing and deposits - I am the key backend developer: 11 microservices, card-provider integrations, KYC and the auth layer, designed and built almost entirely from the ground up, plus code review and mentoring for the 2 backend developers who joined later.

## Selected Work

- **Designed and built 11 microservices** covering card issuance, deposits, payments, KYC and auth as the key backend developer on a FinTech/Web3 platform for card issuing and deposits serving 62,800 users - largely from scratch, event-driven on NestJS + Kafka + gRPC, every service on PostgreSQL (MikroORM), with independent scaling and isolated business logic.
- **Shipped a yield-deposit module** with automatic payouts at the end of the hold period - a new product flow that reached 7,600 deposits and $13.2M in monthly deposit volume.
- **Unified 3 card-issuing providers** behind one integration layer on the Adapter and Strategy patterns - the first integration took 3-4 weeks, the third took 4 days - and eliminated an ordering race condition between API calls and provider webhooks with a custom Kafka transport using strict partition-key ordering, so payment state transitions process in guaranteed order per transaction.
- **Cut the average transcript API response time 12x** (around 3s to 240ms) using compound indexes and aggregation at the MongoDB level, on a call-analytics backend where I also built an OpenSearch engine indexing around 50,000 transcripts with full-text search, filtering and aggregation, and covered the critical modules with Jest unit and e2e tests (82% coverage of the critical parts).
- **Designed alerting on Grafana + Loki** with delivery to Telegram - service errors surface in 5-15 minutes instead of being found by reading logs by hand - and I run prod incidents off it: when a card provider started failing issuance on part of its BINs, I disabled those BINs in the admin panel and escalated to the provider, so issuance kept working on the rest instead of the whole service stopping.
- **Shipped a self-service admin panel** (Next.js + Payload CMS) that let around 200 third-party game studios configure game mechanics, prize and competition rules on their own - previously every change required a platform developer.
- **Extended an AdminJS panel** with custom CkEditor plugins and React components for an AdTech product (ad-traffic arbitrage), and added video upload and storage through the Bunny API - editors manage content without developer involvement.

## Tech Stack

- **Core:** TypeScript, Node.js (async / event loop)

- **Frameworks:** NestJS, Express, Next.js, React, Payload CMS, AdminJS, CkEditor, decimal.js

- **Messaging & data:** Kafka (idempotent consumers, DLQ), NATS, gRPC, MongoDB (Mongoose), PostgreSQL (MikroORM), SQL, Redis, OpenSearch

- **Infra:** Docker, Docker Compose, WebSocket / Socket.io, HTTP/2, Grafana + Loki, AWS (Cognito, S3, CloudWatch), Bunny.net, CI/CD (GitHub Actions, GitLab)

- **Security & compliance:** JWT, OAuth2, 2FA, password hashing (bcrypt), KYC verification (Sumsub)

- **Testing:** Jest (unit + e2e), Postman

- **Practices:** event-driven architecture, microservices, REST API, SOLID, DDD

## Featured Projects

**[base](https://github.com/yauheni-shcharbakou/base)** - personal-website monorepo - hexagonal NestJS gRPC microservices and a Next.js / Refine admin panel, wired together by custom Protobuf and NATS JetStream codegen pipelines.

**[npm-packages](https://github.com/yauheni-shcharbakou/npm-packages)** - a collection of my own published TypeScript npm packages.

## Connect

- Email: yshcharbakou@gmail.com
- LinkedIn: https://www.linkedin.com/in/yauheni-shcharbakou/
- Telegram: [@yshcharbakou](https://t.me/yshcharbakou)
- Location: Tbilisi, Georgia (GMT+4)

**Open to remote and onsite / hybrid Node.js backend roles in Tbilisi.**
