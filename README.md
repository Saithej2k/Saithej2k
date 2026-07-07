<div align="center">

# Saithej Singu

**Software engineer with experience across backend systems, storage/reliability tooling, observability, and applied AI workflows.**

I build service APIs, storage-heavy systems, diagnostics, and small AI tools where correctness has to survive real inputs.

M.S. in Computer Science, University of Florida  
Based in the U.S.; open to relocation, remote, and hybrid roles

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

## PR Fingerprints

Small upstream patches, grouped by what they change:

`runtime truth` -> clearer Jaeger SPM disabled-metrics behavior: [`jaeger#8878`](https://github.com/jaegertracing/jaeger/pull/8878)  
`operator escape hatch` -> Helm service-network override for AWS application networking: [`aws#973`](https://github.com/aws/aws-application-networking-k8s/pull/973)  
`CLI ergonomics` -> help output that works without local config: [`elastic/connectors#4109`](https://github.com/elastic/connectors/pull/4109)  
`UI edge polish` -> timestamp/search/rendering fixes in production apps: [`nextcloud#2604`](https://github.com/nextcloud/collectives/pull/2604), [`FlowFuse#2152`](https://github.com/FlowFuse/node-red-dashboard/pull/2152)

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
