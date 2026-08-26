# Debanjan Rakshit

**Software Engineer · AI Systems · Systems Engineering**

I build autonomous agent infrastructure, custom Kubernetes operators, and high-performance backend systems. My work focuses on bridging low-level systems programming with practical AI orchestration—from building lightweight causal neural networks for real-time signal processing to designing tamper-evident governance pipelines for LLM agents.

---

## What I Build

### AI Systems & Governance
Autonomous agent orchestration platforms, model context protocol (MCP) integrations, OPA policy enforcement, and lightweight neural network architectures for real-time inference.

### Systems & Infrastructure
Kubernetes controllers and CRDs, air-gapped infrastructure monitoring, thread-safe in-memory cache engines, and self-healing systems.

### Search & Signal Processing
Hybrid retrieval engines combining sparse BM25 encoding with dense vector representations, alongside STFT spectrogram-based speech enhancement models.

### Full-Stack & Developer Tooling
Decoupled web applications utilizing multi-level progressive loading architectures, streaming HTTP APIs, and browser developer extensions.

---

## Currently Building

### [Agent Observability Kit (AOK)](https://github.com/unknownsideofme/agent-observability-orchestrator)
An orchestration and governance platform that runs autonomous agents as first-class Kubernetes workloads with Prometheus metrics, Open Policy Agent (OPA) permission checks, and tamper-evident audit trails.  
`Python` · `Kubernetes` · `OPA` · `Prometheus` · `Groq / OpenAI API`

### [AirGap NOC Copilot & Operator](https://github.com/unknownsideofme/server-health-restoration-agent)
A 100% offline, Go-based Kubernetes operator designed for air-gapped environments that monitors infrastructure telemetry, predicts time-to-impact (TTI) for failures, and executes repair skills via the Model Context Protocol (MCP).  
`Go` · `Kubernetes Operator` · `MCP` · `React 18` · `Telemetry`

---

## Featured Projects

### [Agent Observability Orchestrator (AOK)](https://github.com/unknownsideofme/agent-observability-orchestrator)
*Autonomous AI agent lifecycle governance and operational control platform for Kubernetes.*

- Orchestrates AI agents as isolated Kubernetes Deployments managed via custom `Agent` CRDs.
- Intercepts agent tool executions to validate permissions against Open Policy Agent (OPA) policies before execution.
- Emits Prometheus metrics for agent failure rates, policy denial counts, and token usage, maintaining a tamper-evident event stream.

`Python` · `Kubernetes` · `OPA` · `Prometheus` · `Docker`

---

### [AirGap NOC Copilot & K8s Operator](https://github.com/unknownsideofme/server-health-restoration-agent)
*Predictive telemetry and self-healing infrastructure operator for air-gapped environments.*

- Implements a custom 10-resource Kubernetes Operator written in Go to monitor multi-tenant datacenter hardware and network topographies.
- Autonomous failure prediction estimating lead times (Time-to-Impact / TTI) prior to network/hardware outages.
- Leverages the Model Context Protocol (MCP) to trigger automated OS and network repair skills without external cloud dependencies.

`Go` · `Kubernetes` · `MCP Protocol` · `React` · `Docker`

---

### [Single-Threaded Cache Engine](https://github.com/unknownsideofme/single-thread-cache-engine)
*High-performance, thread-safe in-memory key-value cache server with REST API interface.*

- Built in C++ implementing a Least Recently Used (LRU) eviction policy via `std::unordered_map` and doubly-linked `std::list`.
- Thread-safe operations using mutex locks, allowing safe concurrent access across HTTP REST endpoints.
- Dedicated background worker thread for non-blocking cleanup of expired Time-To-Live (TTL) cache entries.

`C++` · `HTTP REST API` · `Multithreading` · `LRU Cache` · `JSON`

---

### [CLARITY-Net](https://github.com/unknownsideofme/CLARITY-Net)
*Lightweight Causal U-Net for real-time speech enhancement on spectrograms.*

- Research implementation of a speech denoising neural network constrained to 63,896 trainable parameters.
- Operates on Short-Time Fourier Transform (STFT) log-magnitude spectrograms with a Real-Time Factor (RTF) of 0.309 for low-latency edge deployment.
- Achieves 13.7 dB SI-SDR, 2.865 PESQ, and 0.906 STOI objective speech-quality scores.

`Python` · `PyTorch` · `Deep Learning` · `STFT Spectrograms` · `Audio Signal Processing`

---

### [SLIFTEX](https://github.com/unknownsideofme/SLIFTEX)
*Similarity and Linguistic Filtering system for title verification and duplicate detection.*

- Hybrid search engine combining sparse BM25 lexical keyword matching with dense semantic embeddings via Ollama (Llama 3.2).
- Integrated Pinecone vector database index for fast multi-dimensional vector similarity retrieval.
- Utilizes `RecursiveCharacterTextSplitter` pipelines for chunking and semantic coherence preservation.

`Python` · `FastAPI` · `Llama 3.2` · `Pinecone` · `BM25` · `LangChain`

---

### [QryptMail](https://github.com/unknownsideofme/QryptMail)
*Enterprise webmail client featuring a progressive data loading architecture.*

- 3-Level progressive loading strategy: initial lightweight metadata fetch, lazy detail hydration on selection, and direct HTTP/2 attachment streaming.
- Decoupled monorepo architecture separating the Node.js/Express API gateway from the React/Vite neumorphic frontend.
- Abstract `MailProvider` pattern for transparent multi-provider mail synchronization (Gmail, Outlook).

`Node.js` · `Express` · `React` · `Vite` · `OAuth 2.0` · `Streaming APIs`

---

## Technical Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | Python · Go · C++ · JavaScript / TypeScript |
| **Backend & Systems** | FastAPI · Node.js / Express · REST APIs · gRPC / Protobuf · Multithreading |
| **AI & Machine Learning** | PyTorch · LLMs · RAG · Model Context Protocol (MCP) · LangChain · STFT Processing |
| **Cloud & Infrastructure** | Kubernetes (Controllers, CRDs) · Docker · OPA (Open Policy Agent) · Prometheus · Linux |
| **Databases & Vector Stores** | Pinecone · Redis · PostgreSQL · In-Memory Caches |

---

## Engineering Interests

- **Agentic Governance & Safety**: Building execution sandboxes, policy engines, and audit trails for LLM agents.
- **Kubernetes Controllers & Operators**: Extending K8s APIs to automate complex infrastructure maintenance and monitoring.
- **Low-Latency AI & Audio Systems**: Designing memory-efficient neural networks for real-time signal processing on edge devices.
- **Hybrid Retrieval & Search Architecture**: Combining sparse lexical search (BM25) with dense vector embeddings for precise domain retrieval.

---

## Connect

- **Portfolio**: [portfolio-peach-delta-57.vercel.app](https://portfolio-peach-delta-57.vercel.app/)
- **LinkedIn**: [debanjan-rakshit](https://www.linkedin.com/in/debanjan-rakshit-558912289/)
- **GitHub**: [@unknownsideofme](https://github.com/unknownsideofme)
