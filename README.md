<div align="center">

# Yauheni Shcharbakou

### Node.js Backend Engineer | Event-driven Microservices on Kafka + NestJS

**FinTech · AdTech · Web3**

6 microservices shipped solo · API latency cut 12x · 2 card-provider integrations

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

Backend developer with 4+ years of commercial experience building event-driven microservice systems in TypeScript. I own backends end to end - from architecture to production - and care most about the parts that quietly break products: correct money math, ordered event processing, and dependable third-party integrations.

On my current FinTech platform I am the sole backend engineer - 6 microservices, card-provider integrations, and the auth layer, designed and taken to production.

## Selected Work

- **Designed and built 6 microservices** as the sole backend engineer on a FinTech/Web3 platform serving around 4,500 users and 1,000 issued cards - event-driven on NestJS + Kafka, with independent scaling and isolated business logic.
- **Reduced transcript API latency 12x** (around 3s to 250ms) using compound indexes and database-level aggregation.
- **Integrated 2 card-issuing providers** (Payca, Webscard) and eliminated an ordering race condition between API calls and their webhooks with a custom Kafka transport using strict partition-key ordering - payment state transitions now process in guaranteed order per transaction.
- **Shipped a self-service admin panel** (Next.js + Payload CMS) that let around 200 third-party game studios configure game mechanics, prize and competition rules on their own - previously every change required a platform developer.
- **Built an OpenSearch engine** indexing tens of thousands of call transcripts with full-text search, filtering, and aggregation.
- **Shipped precise money math** with decimal.js, removing floating-point rounding errors across card and payment operations.
- **Extended an AdminJS panel** with custom CkEditor plugins and React components for an ad-traffic arbitrage product, letting editors manage content without developer involvement.

## Tech Stack

- **Core:** TypeScript, Node.js (async / event loop)
- **Frameworks:** NestJS, Express, RxJS, Next.js, React, Payload CMS, AdminJS
- **Messaging & data:** Kafka, NATS, MongoDB (Mongoose), PostgreSQL (MikroORM), OpenSearch
- **Infra:** Docker, gRPC, WebSocket / Socket.io, AWS (Cognito, S3, CloudWatch), CI/CD (GitHub Actions, Vercel, Railway)
- **Security:** JWT, OAuth2, 2FA, bcrypt
- **Testing:** Jest (unit + e2e)

## Featured Projects

**[base](https://github.com/yauheni-shcharbakou/base)** - personal-website monorepo - hexagonal NestJS gRPC microservices and a Next.js / Refine admin panel, wired together by custom Protobuf and NATS JetStream codegen pipelines.

**[npm-packages](https://github.com/yauheni-shcharbakou/npm-packages)** - a collection of my own published TypeScript npm packages.

## Connect

- Email: yshcharbakou@gmail.com
- LinkedIn: https://www.linkedin.com/in/yauheni-shcharbakou/
- Telegram: [@yshcharbakou](https://t.me/yshcharbakou)
- Location: Tbilisi, Georgia

**Open to remote and onsite / hybrid Node.js backend roles in Tbilisi.**
