# Backend Engineer Checklist

A practical checklist for backend engineers who want to build stronger fundamentals in **Go**, **Java**, **distributed systems**, **databases**, **networking**, **observability**, and **engineering delivery**.

[![Stars](https://img.shields.io/github/stars/happysnaker/backend-engineer-checklist?style=social)](https://github.com/happysnaker/backend-engineer-checklist/stargazers)
[![Support](https://img.shields.io/badge/support-WeChat%20%26%20Alipay-7aa2ff)](https://happysnaker.github.io/support/)
[![Async Review](https://img.shields.io/badge/review-Quick%20read%20%2F%20async-9b87f5)](https://happysnaker.github.io/review/)

This repository is designed to be useful for:

- self-study
- interview preparation
- onboarding plans
- team skill mapping
- personal growth reviews

> Want a copy you can adapt for your own interview prep, weekly growth plan, or team leveling rubric? Click **Use this template** on GitHub and generate your own version.
>
> Want the blunt version on your own GitHub / README instead of self-auditing? I offer a **¥29.9 quick read** and a **¥99 async packaging pass** on the [review page](https://happysnaker.github.io/review/).

## Why people star / share this repo

- it is concise enough to use as a real weekly checklist
- it covers backend, systems, databases, networking, and delivery together
- it works for interviews, onboarding, and self-review instead of only one scenario

If you find it useful, please **star the repo**, share it, and consider supporting ongoing updates via the [support page](https://happysnaker.github.io/support/).

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

## Quick weekly use

A simple way to use this repo without overthinking it:

1. pick 3 unchecked items
2. turn each one into a tiny reading / coding / note-taking task
3. make at least one item visible in public work (repo, note, demo, or OSS fix)
4. repeat weekly instead of treating this as a one-time read

---

## Related repos

If you want a fuller public backend portfolio around this checklist:

- [`system-design-checklist`](https://github.com/happysnaker/system-design-checklist) — practical framework for interviews, design reviews, and architecture tradeoffs
- [`go-service-starter`](https://github.com/happysnaker/go-service-starter) — minimal production-minded Go HTTP service starter
- [`CSAPPLabsAndNotes`](https://github.com/happysnaker/CSAPPLabsAndNotes) — systems-learning notes covering CS:APP labs, memory, binaries, shells, and proxies

---

## Contribution

Suggestions and improvements are welcome.

If you'd like to support my open-source work, you can do so here:

- [Support page](https://happysnaker.github.io/support/)
- WeChat Pay / Alipay support options are listed there
- Details for lightweight async feedback on a public GitHub profile or README are also listed there

If this checklist helped your interview prep, onboarding plan, or self-review, small support helps me keep expanding these public backend resources.

Common support fit:

- **¥9.9** — if this checklist helped you identify one blind spot
- **¥19.9** — if it helped your interview prep or onboarding roadmap
- **best payment note** — `backend-engineer-checklist`
- **fastest path** — tip directly if the checklist helped; use **¥29.9** / **¥99** only if you want concrete edits back
- **¥99** — if you want async feedback on your public GitHub profile / README packaging

## License

MIT
