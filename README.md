<div align="center">

# Saithej Singu

**Software engineer building reliable backend systems, real-time diagnostic tools, and applied AI workflows.**

M.S. in Computer and Information Science, University of Florida  
Based in the U.S. and open to relocation, remote, and hybrid roles

<p>
  <a href="https://www.linkedin.com/in/saithejsingu/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Saithej%20Singu-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:saithej2k3@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-saithej2k3%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/prometheus/client_golang/pull/2019"><img alt="Prometheus PR" src="https://img.shields.io/badge/Prometheus-client__golang-E6522C?style=flat-square&logo=prometheus&logoColor=white"></a>
</p>

</div>

## Engineering Focus

I like building software where system behavior matters: backend services that stay observable, control workflows that handle faults predictably, and applied ML systems that can be tested, served, and improved without mystery.

- Distributed systems, backend infrastructure, and service APIs
- Real-time and industrial software with telemetry, state machines, CAN workflows, and fault handling
- Applied AI and machine learning for retrieval, recommendation, ranking, and optimization
- Observability and open-source engineering with Prometheus, Grafana, OpenTelemetry, and CI/CD

## Technical Toolkit

| Area | Tools |
| --- | --- |
| Languages | C++, Go, Python, Java, C#, SQL, Bash, TypeScript, JavaScript |
| Backend and systems | Spring Boot, FastAPI, REST APIs, gRPC, Protocol Buffers, Kafka, PostgreSQL, Redis, RocksDB, OpenSearch |
| Cloud and observability | AWS, Docker, Kubernetes, Terraform, GitHub Actions, Prometheus, Grafana, OpenTelemetry |
| Real-time and industrial | STM32, FreeRTOS, CAN Bus, CANopen, motion control, hardware abstraction, telemetry parsing, diagnostic interfaces |
| Applied AI | PyTorch, semantic search, recommendation systems, neural ranking, CTR prediction, Bayesian optimization, experimentation |

## Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/equipment-control-diagnostic-simulator">Equipment Control and Diagnostic Simulator</a></h3>
      <p>End-to-end industrial simulator for STM32-style FreeRTOS device nodes, a C++20 Linux CAN gateway, deterministic CAN fault replay, and a C#/.NET WPF diagnostic workbench.</p>
      <p>Models initialization, calibration, homing, recipe execution, alarm handling, shutdown, and recovery across virtual CAN devices with replayable JSONL telemetry.</p>
      <p><strong>Signals:</strong> C++, FreeRTOS, CAN, CANopen, WPF, fault injection, diagnostic tooling</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/GenAI-Semantic-Search-Recommendation">GenAI Semantic Search and Recommendation</a></h3>
      <p>RAG recommender with LLM query expansion, Hugging Face bi-encoder retrieval over FAISS, cross-encoder reranking, and grounded result summaries.</p>
      <p>Includes a FastAPI serving path, BM25 baseline, and ranking evaluation with nDCG@10, MRR@10, and recall@10.</p>
      <p><strong>Signals:</strong> Python, FastAPI, FAISS, semantic retrieval, reranking, recommendation systems</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/Neural-Ad-Ranking-CTR-Prediction">Neural Ad-Ranking and CTR Prediction</a></h3>
      <p>Click-through-rate prediction system built around a DCN-v2 PyTorch model, deterministic C++ feature hashing, sigmoid calibration, and a production-style gRPC serving API.</p>
      <p>Supports synthetic local training for the full train, checkpoint, and prediction loop, with Redis-backed calibration overrides for serving.</p>
      <p><strong>Signals:</strong> PyTorch, C++, gRPC, Redis, feature hashing, ranking models</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/Bayesian-Optimization-for-Process-Prediction">Bayesian Optimization for Process Prediction</a></h3>
      <p>Gaussian-process Bayesian optimization for a noisy process-yield prediction problem, comparing EI and UCB acquisition functions against a grid-search baseline.</p>
      <p>Includes process simulation, convergence artifacts, MATLAB equivalents, and a PyTorch regressor trained on simulated noisy measurements.</p>
      <p><strong>Signals:</strong> Python, PyTorch, Gaussian processes, SciPy, scikit-learn, optimization</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Saithej2k/TransactionIngest">TransactionIngest</a></h3>
      <p>Hourly .NET batch job that reconciles 24-hour card transaction snapshots into SQLite, records field-level audit history, and tracks ingestion runs.</p>
      <p>Designed for idempotent snapshot processing with deduplication, revocation, reactivation, finalization, transactional writes, and focused xUnit coverage.</p>
      <p><strong>Signals:</strong> C#, .NET, EF Core, SQLite, batch processing, auditability</p>
    </td>
    <td width="50%" valign="top">
      <h3>What I look for in systems</h3>
      <p>Clear contracts, measurable behavior, small recovery loops, and tests that prove the workflow rather than just the happy path.</p>
      <p>I am especially interested in backend and infrastructure roles where performance, fault tolerance, observability, and maintainable design all matter.</p>
    </td>
  </tr>
</table>

## Open-Source Engineering

I have contributed to Prometheus [`client_golang`](https://github.com/prometheus/client_golang), the Go instrumentation library for Prometheus metrics.

- Open pull request: [`prometheus/client_golang#2019`](https://github.com/prometheus/client_golang/pull/2019) - `[codex] fix metric vec label input aliasing`
- Focus area: Go metrics instrumentation, API behavior, and regression coverage

## Contact

For backend, infrastructure, real-time systems, applied AI, or observability-focused roles, reach me at [saithej2k3@gmail.com](mailto:saithej2k3@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/saithejsingu/).
