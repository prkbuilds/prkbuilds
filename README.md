<!--
**PratikFandade/PratikFandade** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# prkbuilds

I build backend + infrastructure software: distributed systems, observability, and developer tooling.
Open to Backend / Infra / Platform / Distributed Systems roles (Go, C++, Rust).

## What I’m focused on
- Observability middleware for GenAI systems (OpenTelemetry, tracing conventions, tool-call spans)
- Distributed systems primitives (Raft, replication, consistency, failure handling)
- Systems monitoring (eBPF, Prometheus, Grafana) and performance debugging

## Featured projects
- otel-ai-go
  Drop-in Go HTTP + gRPC middleware that emits OpenTelemetry GenAI spans/events/attributes, including tool calls and multi-turn traces.
  Repo: https://github.com/prkbuilds/otel-ai-go

- KernelScope
  Linux process monitor using C++ + eBPF + Prometheus + Grafana, built for “why is my CPU spiking?” style debugging.
  Repo: https://github.com/prkbuilds/KernelScope

- Raft KV store (from scratch)
  A Raft-based distributed key-value store in Go using gRPC, focused on correctness and failure scenarios.
  Repo: https://github.com/prkbuilds/raft-kv

## Tech I use
- Languages: Go, Rust, C++, TypeScript
- Infra: gRPC, REST, OpenTelemetry, Prometheus, Grafana
- Systems: Linux, eBPF
- Cloud/DevOps: Docker, CI/CD (GitHub Actions), AWS basics

## How I build
- Ship small, iterate fast, and measure impact (latency, p95/p99, error rates, cost)
- Prefer clean APIs, boring reliability, and great docs
- Tests for correctness first, benchmarks for performance second

## What I’m looking for
Teams building:
- platform foundations (infra, shared services, orchestration, caching, storage)
- observability/monitoring stacks
- high-reliability backend systems

If you’re hiring for these, I’m happy to chat.

## Contact
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/pratikfandade)
- Email: [fandadep6@gmail.com](mailto:fandadep6@gmail.com)

## Notes
If you’re browsing my repos, start with the pinned ones above.

```
AI metadata: see ai-metadata.json (entry points, keywords, what to read first).
```
