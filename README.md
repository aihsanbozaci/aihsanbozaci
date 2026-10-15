# Ahmet İhsan Bozacı

Backend developer with a focus on fintech systems, payment integrations, and transactional backend infrastructure. Experienced in handling high-volume transaction flows, asynchronous queues, and database performance tuning.

## Technical Skills

- **Backend & APIs:** PHP (Laravel), Go, Node.js, RESTful APIs, Webhook architectures
- **Relational Databases:** MySQL, PostgreSQL (schema design, indexing, ACID transactions, query optimization)
- **NoSQL & In-Memory:** Redis (queues, caching, rate limiting), MongoDB
- **In-Memory & Caching Strategies:** Redis (Atomic Lua scripting, Sorted Sets for sliding windows, Pub/Sub, memory-optimized caching patterns).
- **Search & Analytics:** Elasticsearch, OpenSearch (log analytics, search indexing)
- **Message Brokers & Event Streaming:** Kafka, RabbitMQ — Event-driven decoupling, consumer group management, dead-letter queues (DLX), and idempotent event processing.
- **Queues & Asynchronous Processing:** Redis Queues / Horizon, worker pools, batch job processing
- **Fintech & Payment Domain:** Virtual POS, payment gateways, 3D Secure, digital wallets, settlement and commission calculation, transaction integrity, fraud/risk checks
- **DevOps & Environment:** Docker, Docker Compose, Nginx, Linux, Git

## Highlighted Work: Multi-Tenant API Manager [![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white)](https://github.com/aihsanbozaci/multi-tenant-api-manager)

A lightweight API gateway layer built to handle tenant authentication, rate limiting, and request telemetry before hitting primary databases.

- **Tenant Validation:** Authentication and routing resolved via Redis to reduce unnecessary relational database connections.
- **Rate Limiting:** Sliding-window rate limiting using Redis Lua scripts to handle concurrent request spikes safely.
- **Asynchronous Telemetry:** Non-blocking logging that buffers request data in Redis and flushes to MySQL in batches.

## Contact

- **Email:** ahmetbozac@gmail.com
- **LinkedIn:** [linkedin.com/in/aihsanbozaci](https://www.linkedin.com/in/aihsanbozaci)
