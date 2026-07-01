# Hi, I'm Aidar 👋

**Backend engineer · Java & Spring Boot.** I build real products end-to-end and integrate AI/LLM features (RAG, agents) into them.

- 🧱 Into: concurrency-safe systems, PostgreSQL, clean REST APIs, reliable integrations
- 🤖 Production AI in the JVM world: Spring AI, pgvector RAG, OpenAI + Anthropic
- 🔭 Building **iz-merch** (phygital commerce platform) and **GameBazaar** (game-items marketplace) in public
- 📍 Bishkek, Kyrgyzstan · open to backend roles

### Tech
`Java 21` · `Spring Boot` · `Spring Data JPA / Hibernate` · `Spring Security` · `Spring AI` · `REST` · `WebSocket` · `PostgreSQL` · `MySQL` · `Testcontainers` · `Docker` · `CI/CD` · `GCP` · `AWS S3` · `TypeScript` · `Next.js`

### Featured projects

**iz-merch** — phygital commerce platform · *flagship, solo build*
A limited-edition merch platform I'm building end-to-end: Spring Boot 3 / Java 21 + PostgreSQL backend, Next.js admin console and public catalog. Focus is production-grade backend engineering correctness under concurrency, real security, and tests that run against real infrastructure.
- **Race-safe reservation engine** — concurrent buyers for the same unit resolve to a single winner via one atomic SQL UPDATE (losers get HTTP 409); reservation expiry is lazy, so there's no cleanup cron to babysit.
- **Security** — single-use hashed magic-link auth, server-side price snapshotting (client can't dictate price), Bucket4j rate limiting in front of auth, deny-by-default authorization.
- **Quality** — 275 integration tests against actual PostgreSQL (singleton Testcontainers, no H2), Flyway-versioned schema, RFC 7807 error responses, S3 / Cloudflare R2 storage.

**GameBazaar** — game-items marketplace
A full-stack marketplace with an escrow-style **order state machine** (`PENDING → PAID → DELIVERED → COMPLETED`) that rejects illegal transitions, per-order buyer/seller roles derived from the data model, and a review/reputation system. Java 21 / Spring Boot 3.5 + Spring Security (JWT) + Spring Data JPA, Next.js frontend.

**CoreCraft** — [`java-foundations`](https://github.com/aidarkazybekov/java-foundations) · [live site](https://aidarkazybekov.github.io/java-foundations/)
Core Java data structures, concurrency primitives & a DI container, **built from scratch, TDD-first** — 11 components, 104 tests, zero dependencies. A proof of understanding, not a library.

**DevCore** — [live](https://java-core.dent-premium.workers.dev/)
A deployed engineering learning & interview-prep platform: 100+ topics across Java, Spring, databases, and system design. Next.js on Cloudflare Workers, with an AI tutor and live code execution.

**Silk & Shine** — [`silk-and-shine-api`](https://github.com/aidarkazybekov/silk-and-shine-api) · [`web`](https://github.com/aidarkazybekov/silk-and-shine-web)
Full-stack business platform — Spring Boot 3 + Angular, JWT/BCrypt auth, Dockerized, GitHub Actions CI.

### Coming soon
**Tamyr** — *in design* · a graph-database platform modeling Kyrgyz kinship as a typed multigraph (Neo4j), formalizing traditional kin naming as graph traversal.

### Connect
[LinkedIn](https://www.linkedin.com/in/aidarkazybekov/) · [LeetCode](https://leetcode.com/u/aidarovich/) · kmoondar@gmail.com
