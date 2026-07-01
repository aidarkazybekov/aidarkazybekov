# Hi, I'm Aidar 👋

**Backend engineer · Java & Spring Boot.** I build real products end-to-end and integrate AI/LLM features (RAG, agents) into them.

- 🧱 Into: concurrency-safe systems, PostgreSQL, clean REST APIs, reliable integrations
- 🤖 Production AI in the JVM world: Spring AI, pgvector RAG, OpenAI + Anthropic
- 🔭 Building **iz-merch** (phygital commerce platform) and **GameBazaar** (game-items marketplace) in public
- 📍 Bishkek, Kyrgyzstan · open to backend roles

### Tech
`Java 21` · `Spring Boot` · `Spring Data JPA / Hibernate` · `Spring Security` · `Spring AI` · `REST` · `WebSocket` · `PostgreSQL` · `MySQL` · `Testcontainers` · `Docker` · `CI/CD` · `GCP` · `AWS S3` · `TypeScript` · `Next.js`

### Featured projects

**iz-merch** — phygital commerce platform · *flagship, in active development*
A limited-edition merchandise SaaS I build solo, end-to-end — Spring Boot 3 / Java 21 + PostgreSQL backend, a Next.js admin + public catalog, and a full customer reservation & order flow.
- **Race-safe reservation engine** — a single atomic SQL `UPDATE` resolves concurrent buyers to one winner (HTTP 409), with lazy expiry (no cleanup cron).
- **Security** — single-use hashed magic-link auth, server-side price snapshotting, Bucket4j rate limiting ahead of auth, deny-by-default.
- **Quality** — 275 integration tests on real PostgreSQL (singleton Testcontainers), RFC 7807 errors, Flyway migrations, S3 / Cloudflare R2 storage.

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
[LinkedIn](https://www.linkedin.com/in/aidarkazybekov/) · [LeetCode](https://leetcode.com/u/5Yej3KAAzs/) · kmoondar@gmail.com
