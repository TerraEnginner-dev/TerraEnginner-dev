### Felix Bauer // Munich

Backend systems engineer specializing in database drivers, connection lifecycles, and high-throughput caching layers.

`
Stack: Python 3.11+ • AsyncIO • Redis • PostgreSQL • C Extensions
Focus: Connection Pooling • Serialization Efficiency • Protocol Invariants
`

---

#### 🔭 Upstream Tracks & Focus Areas

* **[redis/redis-py](https://github.com/redis/redis-py)** — Cluster command routing, socket timeout handling, and pipeline buffering.
* **[MagicStack/asyncpg](https://github.com/MagicStack/asyncpg)** — Prepared statement caches, binary protocol decoding, and pool eviction bounds.
* **[sqlalchemy/sqlalchemy](https://github.com/sqlalchemy/sqlalchemy)** — Async dialect wrappers and connection pool health checks.

---

#### ⚙️ Engineering Principles & Workflow

1. **Zero Resource Leaks**: Sockets, locks, and prepared statements must be strictly reclaimed during task cancellations.
2. **Atomic Regression Tests**: Every bug report must be accompanied by an isolated reproducer before any code is modified.
3. **Pre-Flight Invariant Validation**: Before committing upstream PRs, diffs are minimized and validated using [ZeroSlop™ CI](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems) to guarantee clean, green CI runs.

---
*Built with Python, Linux, and pre-flight verified with ZeroSlop CI.*
