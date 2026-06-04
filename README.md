<div align="center">

# Yauheni Shcharbakou

### Node.js Backend Engineer | Event-driven Microservices on Kafka + NestJS

**FinTech · AdTech · Web3**

8 microservices shipped solo · incident detection cut from 24h to 10 min · API latency down 10-15x

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/NATS-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white" alt="NATS" />
<img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />

</div>

Backend developer with 4 years of commercial experience building event-driven microservice systems in TypeScript. I own backends end to end - from architecture to deploy - and care most about the parts that quietly break products: correct money math, ordered event processing, and incidents that surface in minutes instead of hours.

On my current FinTech platform I am the sole backend engineer - 8 microservices, card-provider integrations, and the auth layer, all designed and built from scratch.

## Selected Work

- **Architected 8 microservices from scratch** as the sole backend engineer on a FinTech/Web3 platform - event-driven on NestJS + Kafka, with independent scaling and isolated business logic.
- **Cut incident detection from 24+ hours to under 10 minutes** by building real-time alerting on Telegram and centralized logs with Redis debounce.
- **Reduced transcript API latency 10-15x** (around 3s to 200-300ms) using compound indexes and database-level aggregation.
- **Eliminated a payment ordering race condition** between API calls and provider webhooks via a custom Kafka transport with strict partition-key ordering - payment state transitions now process in guaranteed order per transaction.
- **Sped up page loads 30-50%** with a Redis image-caching layer.
- **Built an OpenSearch engine** indexing tens of thousands of call transcripts with full-text search, filtering, and aggregation.
- **Shipped precise money math** with decimal.js, removing floating-point rounding errors across card and payment operations.

## Tech Stack

**Core:** TypeScript, Node.js (async/event loop, worker_threads, child_process, streams)
**Frameworks:** NestJS, Express, RxJS, Next.js, React
**Messaging & data:** Kafka, NATS, Redis, BullMQ, MongoDB (Mongoose), PostgreSQL, OpenSearch
**Infra:** Docker, gRPC, WebSocket / Socket.io, AWS (Cognito, S3, CloudWatch), CI/CD (GitHub Actions, Vercel, Railway)
**Security:** JWT, OAuth2, 2FA, bcrypt
**Testing:** Jest (unit + e2e)

## Featured Projects

**[base](https://github.com/yauheni-shcharbakou/base)** - full-stack monorepo on Turborepo. Backend: NestJS + NATS JetStream microservices over gRPC. Admin: Next.js + Refine + MUI with server actions and server-side auth via http-only cookies. PostgreSQL through MikroORM.

**[npm-packages](https://github.com/yauheni-shcharbakou/npm-packages)** - a collection of my own published TypeScript npm packages.

**[YumaSpotify](https://github.com/not-yumasoft/spotify)** - Spotify-style audio-streaming clone. Built realtime interaction over WebSocket from scratch, set up CI/CD on GitHub Actions deploying to Vercel + Railway, and extracted shared socket logic into an auto-published npm package. Stack: NestJS, TypeORM, Socket.io, React, Firebase Storage.

## Connect

- Email: iipekolict@gmail.com
- LinkedIn: https://www.linkedin.com/in/yauheni-shcharbakou/
- Telegram: [@NATOvetc](https://t.me/NATOvetc)
- Location: Tbilisi, Georgia

**Open to remote Node.js backend roles.**
