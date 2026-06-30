# Backend Engineer Checklist

A practical checklist for backend engineers who want to build stronger fundamentals in **Go**, **Java**, **distributed systems**, **databases**, **networking**, **observability**, and **engineering delivery**.

This repository is designed to be useful for:

- self-study
- interview preparation
- onboarding plans
- team skill mapping
- personal growth reviews

If you find it useful, please **star the repo** and share it.

---

## How to use this checklist

Use it in any of these ways:

- mark what you already understand well
- identify weak spots before interviews
- turn unchecked items into weekly learning tasks
- use it as a roadmap for junior-to-mid or mid-to-senior backend growth

Legend:

- [ ] not comfortable yet
- [x] comfortable / can explain / can apply

---

## 1. Programming fundamentals

### Go
- [ ] Understand pointers, interfaces, slices, maps, and common memory pitfalls
- [ ] Understand goroutines, channels, `context`, cancellation, and timeouts
- [ ] Know when to use worker pools, pipelines, fan-in, and fan-out
- [ ] Understand `sync.Mutex`, `RWMutex`, `WaitGroup`, `Once`, and atomics
- [ ] Can reason about escape analysis, allocation patterns, and performance hotspots
- [ ] Can design small, testable packages with clear interfaces

### Java
- [ ] Understand JVM memory model basics, GC tradeoffs, and object allocation patterns
- [ ] Understand collections, concurrency primitives, thread pools, and futures
- [ ] Understand exception handling, class loading, and reflection tradeoffs
- [ ] Can design maintainable service-layer and data-layer abstractions

---

## 2. Operating systems and networking

- [ ] Understand processes vs threads, context switching, and basic scheduling ideas
- [ ] Understand virtual memory, page faults, and why locality matters
- [ ] Understand file descriptors, sockets, and basic I/O models
- [ ] Understand TCP handshake, retransmission, flow control, and connection lifecycle
- [ ] Understand HTTP/1.1, HTTP/2, keep-alive, headers, retries, and timeouts
- [ ] Understand DNS basics, TLS basics, and common reverse-proxy deployment patterns
- [ ] Can explain the difference between latency, throughput, concurrency, and parallelism

---

## 3. Databases and storage

### Relational databases
- [ ] Understand indexes, covering indexes, composite indexes, and query plans
- [ ] Can identify common causes of slow SQL and fix them methodically
- [ ] Understand transactions, isolation levels, locks, and deadlocks
- [ ] Understand replication basics, failover tradeoffs, and schema migration safety

### Caching and KV systems
- [ ] Understand cache-aside, write-through, write-back, and invalidation tradeoffs
- [ ] Understand hot key, cache stampede, penetration, and consistency issues
- [ ] Know how to use Redis responsibly for rate limiting, queues, locks, or counters

---

## 4. Distributed systems

- [ ] Understand idempotency and why retries can create duplicate effects
- [ ] Understand service discovery, load balancing, and health checking basics
- [ ] Understand circuit breaking, backoff, and timeout budgeting
- [ ] Understand eventual consistency and common compensation patterns
- [ ] Understand message queues, consumer groups, retry queues, and dead-letter queues
- [ ] Understand common tradeoffs in RPC and API design
- [ ] Can reason about failure domains and remove single points of failure

---

## 5. API and service design

- [ ] Can design clean REST or RPC APIs with stable naming and versioning ideas
- [ ] Know how to validate inputs and define good error models
- [ ] Understand authentication vs authorization
- [ ] Know how to design pagination, filtering, sorting, and rate-limiting behavior
- [ ] Can write API docs that help other engineers integrate faster

---

## 6. Observability and debugging

- [ ] Use structured logging instead of ad-hoc print debugging
- [ ] Understand metrics, traces, and logs and when each is most useful
- [ ] Know how to define service-level indicators and meaningful alerts
- [ ] Can debug latency spikes, error-rate spikes, and resource saturation methodically
- [ ] Can use profiling or flame graphs to investigate performance bottlenecks

---

## 7. Reliability and production thinking

- [ ] Think in terms of blast radius, rollback safety, and degradation behavior
- [ ] Understand canary, blue-green, and phased rollout ideas
- [ ] Know how to make background jobs safe to retry
- [ ] Know how to prevent duplicate processing and data corruption
- [ ] Understand configuration management, secrets management, and operational safety

---

## 8. Engineering execution

- [ ] Can break ambiguous work into clear technical tasks
- [ ] Can write design notes or RFCs for medium-size changes
- [ ] Can review code for correctness, maintainability, and operational risk
- [ ] Can communicate tradeoffs clearly instead of only proposing one option
- [ ] Can write useful documentation for future maintainers

---

## 9. Backend project signals

Strong public signals usually include at least a few of the following:

- [ ] A real service or starter template with a clear README
- [ ] Open-source contributions to known projects
- [ ] Notes or writeups that demonstrate systems understanding
- [ ] Practical examples involving APIs, storage, queues, or observability
- [ ] Evidence of reliability, testing strategy, and production thinking

---

## 10. Suggested learning order

If you are early in backend engineering, a useful order is:

1. language fundamentals
2. OS + networking basics
3. SQL + indexing + transactions
4. HTTP APIs and service design
5. caching and queues
6. observability and debugging
7. distributed systems and production tradeoffs

---

## Contribution

Suggestions and improvements are welcome.

If you'd like to support my open-source work, you can do so from my GitHub profile:

- [Support my work](https://github.com/happysnaker#support-my-open-source-work)

## License

MIT
