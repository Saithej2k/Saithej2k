<div align="center">

# Saithej Singu

**Software engineer building backend systems, storage/reliability tooling, and applied AI workflows.**

M.S. in Computer and Information Science, University of Florida  
Based in the U.S. and open to relocation, remote, and hybrid roles

<p>
  <a href="https://www.linkedin.com/in/saithejsingu/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Saithej%20Singu-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:saithej2k3@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-saithej2k3%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

</div>

## Current Direction

I like code that makes system behavior easier to reason about: storage paths with measurable tradeoffs, service APIs with sharp contracts, diagnostics that surface failure modes early, and ML systems with evaluation loops instead of hand-waving.

`backend` / `storage internals` / `reliability` / `observability` / `developer tooling` / `applied AI`

## Shipping Notes

I keep a split-brain build loop: one side is original systems work, the other is upstream maintenance in codebases I did not design. The through-line is making behavior easier to inspect, test, and recover from.

**Featured build:** [`LocalAssist`](https://github.com/Saithej2k/LocalAssist)  
Say it once. It becomes a plan. LocalAssist is a 100% on-device iOS 26 assistant built with Swift, SwiftUI, App Intents, WidgetKit, and Apple Foundation Models. It focuses on guided generation, tool calling, typed streaming, deterministic fallback, and CI-gated evals.

**Upstream pattern:** I contribute where small changes remove ambiguity: clearer Jaeger SPM failure modes, safer Elastic connector CLI help paths, Kubernetes Helm configuration escape hatches, frontend state fixes, docs that match runtime behavior, and tests that pin the edge case rather than the happy path.

**Favorite kind of PR:** the one that makes the next engineer say, "oh, that is what this system does."

## Build Map

Storage and reliability

[`db-storage-engine`](https://github.com/Saithej2k/db-storage-engine) -> [`distributed-storage-engine`](https://github.com/Saithej2k/distributed-storage-engine) -> [`rocksdb-compaction-optimizer`](https://github.com/Saithej2k/rocksdb-compaction-optimizer)

Industrial diagnostics

[`equipment-control-diagnostic-simulator`](https://github.com/Saithej2k/equipment-control-diagnostic-simulator) -> deterministic CAN fault replay -> WPF diagnostic workbench

Applied AI and ranking

[`GenAI-Semantic-Search-Recommendation`](https://github.com/Saithej2k/GenAI-Semantic-Search-Recommendation) -> semantic retrieval and reranking -> [`Neural-Ad-Ranking-CTR-Prediction`](https://github.com/Saithej2k/Neural-Ad-Ranking-CTR-Prediction)

## Technical Range

- Languages: C++, Go, Python, Java, C#, SQL, Bash, TypeScript, JavaScript
- Backend: Spring Boot, FastAPI, REST APIs, gRPC, Protocol Buffers, Kafka, PostgreSQL, Redis, OpenSearch
- Storage and reliability: LSM trees, WAL recovery, MVCC, Raft, buffer pools, compaction scheduling, workload simulation
- Cloud and observability: AWS, Docker, Kubernetes, Terraform, GitHub Actions, Grafana, OpenTelemetry, metrics, tracing
- Applied AI: PyTorch, semantic search, recommendation systems, neural ranking, CTR prediction, Bayesian optimization
