<div align="center">

# Saithej Singu

**Software engineer building reliable backend systems, storage and diagnostic tooling, and applied AI workflows.**

M.S. in Computer and Information Science, University of Florida  
Based in the U.S. and open to relocation, remote, and hybrid roles

<p>
  <a href="https://www.linkedin.com/in/saithejsingu/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Saithej%20Singu-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:saithej2k3@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-saithej2k3%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

</div>

## Engineering Focus

I like building software where system behavior is visible and testable: storage paths with measurable tradeoffs, backend services with clear contracts, diagnostic workflows that recover cleanly from faults, and ML systems that can be evaluated instead of guessed at.

- Backend infrastructure, distributed systems, service APIs, and data pipelines
- Storage and reliability work with LSM trees, WALs, compaction, buffering, and replayable benchmarks
- Real-time and industrial software with telemetry, CAN workflows, state machines, and fault handling
- Applied AI and machine learning for retrieval, recommendation, ranking, and optimization

## Technical Toolkit

| Area | Tools |
| --- | --- |
| Languages | C++, Go, Python, Java, C#, SQL, Bash, TypeScript, JavaScript |
| Backend and systems | Spring Boot, FastAPI, REST APIs, gRPC, Protocol Buffers, Kafka, PostgreSQL, Redis, RocksDB, OpenSearch |
| Cloud and observability | AWS, Docker, Kubernetes, Terraform, GitHub Actions, Grafana, OpenTelemetry, metrics, tracing |
| Storage and reliability | LSM trees, WAL recovery, MVCC, Raft, buffer pools, compaction scheduling, workload simulation |
| Real-time and industrial | STM32, FreeRTOS, CAN Bus, CANopen, motion control, hardware abstraction, telemetry parsing |
| Applied AI | PyTorch, semantic search, recommendation systems, neural ranking, CTR prediction, Bayesian optimization |

## Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/rocksdb-compaction-optimizer">Compaction Scheduling Optimizer</a></h3>
      <p>C++ simulator for studying level-based LSM-tree compaction scheduling under write-heavy workloads.</p>
      <p>Compares legacy level scoring, pending-flush-aware scoring, and hysteresis to reduce stalled writes and avoid noisy schedule switching.</p>
      <p><strong>Signals:</strong> C++, storage engines, LSM trees, compaction, deterministic simulation</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/distributed-storage-engine">Distributed Storage Engine</a></h3>
      <p>Replicated key-value storage engine with Raft, WAL-backed LSM trees, MVCC transactions, gRPC APIs, and Rust YCSB benchmarks.</p>
      <p><strong>Signals:</strong> Go, Raft, LSM, WAL, MVCC, gRPC, benchmark tooling</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/db-storage-engine">DB Storage Engine</a></h3>
      <p>C++20 storage engine with an LRU-K buffer pool, concurrent B+ tree, and write-ahead log recovery.</p>
      <p><strong>Signals:</strong> C++, database internals, concurrency, recovery, buffer management</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/equipment-control-diagnostic-simulator">Equipment Control and Diagnostic Simulator</a></h3>
      <p>End-to-end industrial simulator for STM32-style FreeRTOS device nodes, a C++20 Linux CAN gateway, deterministic CAN fault replay, and a C#/.NET WPF diagnostic workbench.</p>
      <p><strong>Signals:</strong> C++, FreeRTOS, CAN, CANopen, WPF, fault injection, diagnostic tooling</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/GenAI-Semantic-Search-Recommendation">GenAI Semantic Search and Recommendation</a></h3>
      <p>RAG recommender with LLM query expansion, Hugging Face bi-encoder retrieval over FAISS, cross-encoder reranking, and grounded result summaries.</p>
      <p><strong>Signals:</strong> Python, FastAPI, FAISS, semantic retrieval, reranking, evaluation</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/Neural-Ad-Ranking-CTR-Prediction">Neural Ad-Ranking and CTR Prediction</a></h3>
      <p>CTR prediction system built around a DCN-v2 PyTorch model, deterministic C++ feature hashing, sigmoid calibration, and a production-style gRPC serving API.</p>
      <p><strong>Signals:</strong> PyTorch, C++, gRPC, Redis, feature hashing, ranking models</p>
    </td>
  </tr>
</table>

## Open-Source Engineering

I avoid claiming upstream PRs before maintainers accept them.

- Currently have upstream PRs in review across Elastic, Grafana, Kubernetes, Nextcloud, Xata, and CP Initiative projects; I will add them here after merge.

## Contact

For backend, infrastructure, storage, real-time systems, or applied AI roles, reach me at [saithej2k3@gmail.com](mailto:saithej2k3@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/saithejsingu/).
