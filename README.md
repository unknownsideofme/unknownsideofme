<div align="center">

# Debanjan Rakshit

### **Software Engineer · AI Systems · Systems Engineering**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-peach-delta-57.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debanjan-rakshit-558912289/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/unknownsideofme)
[![Profile Views](https://komarev.com/ghpvc/?username=unknownsideofme&style=for-the-badge&color=007ec6)](https://github.com/unknownsideofme)

<br/>

I build autonomous agent infrastructure, custom Kubernetes operators, and high-performance backend systems. My work bridges low-level systems engineering with modern AI orchestration—from building lightweight causal neural networks for real-time signal processing to designing tamper-evident governance pipelines for LLM agents.

</div>

---

## What I Build

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### AI Systems & Governance
![AI Badge](https://img.shields.io/badge/Domain-AI_%26_Governance-0052CC?style=flat-square&logo=openai&logoColor=white)

Autonomous agent orchestration platforms, Model Context Protocol (MCP) integrations, OPA policy enforcement, and lightweight neural network architectures for real-time inference.

</td>
<td width="50%" valign="top">

### Systems & Infrastructure
![Systems Badge](https://img.shields.io/badge/Domain-Systems_%26_K8s-D9381E?style=flat-square&logo=kubernetes&logoColor=white)

Kubernetes controllers and custom CRDs, air-gapped infrastructure monitoring, thread-safe in-memory cache engines, and self-healing systems.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Search & Signal Processing
![Search Badge](https://img.shields.io/badge/Domain-Search_%26_Audio-008080?style=flat-square&logo=pytorch&logoColor=white)

Hybrid retrieval engines combining sparse BM25 encoding with dense vector representations, alongside STFT spectrogram-based speech enhancement models.

</td>
<td width="50%" valign="top">

### Full-Stack & Developer Tooling
![Tools Badge](https://img.shields.io/badge/Domain-Full__Stack_%26_Tools-6B46C1?style=flat-square&logo=react&logoColor=white)

Decoupled web applications utilizing multi-level progressive loading architectures, streaming HTTP APIs, and AI-powered browser developer tools.

</td>
</tr>
</table>
</div>

---

## Currently Building

### [Agent Observability Kit (AOK)](https://github.com/unknownsideofme/agent-observability-orchestrator)
![Active Status](https://img.shields.io/badge/Status-Active_Development-0052CC?style=flat-square)

An orchestration platform that runs autonomous AI agents as first-class Kubernetes workloads with Prometheus metrics, Open Policy Agent (OPA) permission checks, and tamper-evident audit trails.

```
  ┌─────────────────┐       ┌─────────────────┐       ┌─────────────────┐
  │  LLM Planner    ├──────►│  OPA Policy     ├──────►│ Prometheus      │
  │  (Groq/OpenAI)  │       │  Permission     │       │ Metrics & Audit │
  └────────┬────────┘       └────────┬────────┘       └─────────────────┘
           │                         │
           ▼                         ▼
  ┌─────────────────────────────────────────────────────────────────────┐
  │         Kubernetes Agent CRD Deployment (Isolated Pods)             │
  └─────────────────────────────────────────────────────────────────────┘
```

`Python` · `Kubernetes` · `OPA Policy` · `Prometheus` · `Groq / OpenAI API`

---

### [AirGap NOC Copilot & Operator](https://github.com/unknownsideofme/server-health-restoration-agent)
![Active Status](https://img.shields.io/badge/Status-Active_Development-0052CC?style=flat-square)

A 100% offline, Go-based Kubernetes operator designed for air-gapped datacenters that monitors infrastructure telemetry, predicts time-to-impact (TTI) for failures, and executes repair skills via the Model Context Protocol (MCP).

```
  ┌────────────────────────┐      ┌─────────────────────────┐      ┌────────────────────────┐
  │ Hardware Telemetry Stream ├──►│ Predictive TTI Analyzer ├──►│ MCP Skill Execution    │
  └────────────────────────┘      └─────────────────────────┘      └────────────────────────┘
```

`Go` · `Kubernetes Operator` · `MCP Protocol` · `React 18` · `Telemetry`

---

## Featured Projects

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### Agent Observability Orchestrator
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/agent-observability-orchestrator)
![K8s CRD](https://img.shields.io/badge/Architecture-K8s_CRD-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Autonomous AI agent lifecycle governance and operational control platform for Kubernetes.

- Orchestrates AI agents as isolated Kubernetes Deployments managed via custom `Agent` CRDs.
- Intercepts agent tool executions to validate permissions against Open Policy Agent (OPA) policies.
- Emits Prometheus metrics for agent failure rates and policy denial counts.

**Tech:** `Python` `Kubernetes` `OPA` `Prometheus` `Docker`

</td>
<td width="50%" valign="top">

### AirGap NOC Copilot & Operator
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/server-health-restoration-agent)
![Go Operator](https://img.shields.io/badge/Architecture-Go_Operator-00ADD8?style=flat-square&logo=go&logoColor=white)

Predictive telemetry and self-healing infrastructure operator for air-gapped environments.

- Implements a custom 10-resource Kubernetes Operator written in Go to monitor hardware topographies.
- Predicts failure lead times (Time-to-Impact / TTI) prior to network/hardware outages.
- Leverages Model Context Protocol (MCP) to trigger automated OS and network repair skills.

**Tech:** `Go` `Kubernetes` `MCP` `React` `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Single-Threaded Cache Engine
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/single-thread-cache-engine)
![C++ Cache](https://img.shields.io/badge/Architecture-C%2B%2B_Systems-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

High-performance, thread-safe in-memory key-value cache server with REST API interface.

- Built in C++ implementing an LRU eviction policy via `std::unordered_map` and doubly-linked `std::list`.
- Thread-safe operations using mutex locks for safe concurrent access across HTTP REST endpoints.
- Dedicated background worker thread for non-blocking cleanup of expired TTL cache entries.

**Tech:** `C++` `HTTP REST` `Multithreading` `LRU Cache` `JSON`

</td>
<td width="50%" valign="top">

### CLARITY-Net
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/CLARITY-Net)
![Speech AI](https://img.shields.io/badge/Architecture-Causal_U--Net-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

Lightweight Causal U-Net for real-time speech enhancement on spectrograms.

- Deep learning speech denoising network constrained to 63,896 trainable parameters.
- Operates on Short-Time Fourier Transform (STFT) log-magnitude spectrograms with an RTF of 0.309.
- Achieves 13.7 dB SI-SDR, 2.865 PESQ, and 0.906 STOI objective speech-quality scores.

**Tech:** `Python` `PyTorch` `Deep Learning` `STFT` `Audio AI`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### SLIFTEX
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/SLIFTEX)
![Hybrid Search](https://img.shields.io/badge/Architecture-Hybrid_Search-008080?style=flat-square&logo=fastapi&logoColor=white)

Similarity and Linguistic Filtering system for title verification and duplicate detection.

<div align="center">
  <img src="https://i.pinimg.com/736x/0f/f5/3f/0ff53fb915b656b22f51eccf71e77dd9.jpg" width="90%" alt="SLIFTEX System Architecture"/>
</div>

- Hybrid search engine combining sparse BM25 lexical keyword matching with dense semantic embeddings via Ollama (Llama 3.2).
- Integrated Pinecone vector database index for fast multi-dimensional vector similarity retrieval.

**Tech:** `Python` `FastAPI` `Llama 3.2` `Pinecone` `BM25`

</td>
<td width="50%" valign="top">

### QryptMail
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-blue?style=flat-square&logo=github)](https://github.com/unknownsideofme/QryptMail)
![Web Architecture](https://img.shields.io/badge/Architecture-Progressive_Web-61DAFB?style=flat-square&logo=react&logoColor=black)

Enterprise webmail client featuring a 3-level progressive data loading architecture.

<div align="center">
  <img src="https://raw.githubusercontent.com/unknownsideofme/QryptMail/main/qrypt.mail.frontend/src/assets/hero.png" width="90%" alt="QryptMail Interface"/>
</div>

- 3-Level loading: initial lightweight metadata fetch, lazy detail hydration, and direct HTTP/2 attachment streaming.
- Abstract `MailProvider` pattern for transparent multi-provider mail synchronization (Gmail, Outlook).

**Tech:** `Node.js` `Express` `React` `Vite` `OAuth 2.0`

</td>
</tr>
</table>
</div>

---

## Technical Stack

<div align="center">

### Languages & Core Systems
<img src="https://skillicons.dev/icons?i=py,go,cpp,js,ts,html,css&perline=7" alt="Languages" />

<br/>

### AI, ML & Frameworks
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,fastapi,nodejs,express,react,vite&perline=7" alt="Frameworks & AI" />

<br/>

### Infrastructure, Cloud & Databases
<img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,postgres,redis,git,github&perline=7" alt="Infrastructure" />

</div>

<br/>

| Category | Technical Focus |
| :--- | :--- |
| **Languages** | Python · Go · C++ · JavaScript / TypeScript |
| **Backend & Systems** | FastAPI · Node.js / Express · REST APIs · gRPC / Protobuf · Multithreading |
| **AI & Machine Learning** | PyTorch · LLMs · RAG · Model Context Protocol (MCP) · LangChain · STFT Processing |
| **Cloud & Infrastructure** | Kubernetes (Controllers, CRDs) · Docker · OPA (Open Policy Agent) · Prometheus · Linux |
| **Databases & Vector Stores** | Pinecone · Redis · PostgreSQL · In-Memory Caches |

---

## GitHub Analytics & Activity

<div align="center">

<table border="0">
  <tr>
    <td align="center" valign="middle">
      <img height="175" src="https://github-readme-stats-eight-theta.vercel.app/api?username=unknownsideofme&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
    </td>
    <td align="center" valign="middle">
      <img height="175" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=unknownsideofme&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
    </td>
  </tr>
</table>

</div>

---

## Engineering Interests

- **Agentic Governance & Safety**: Building execution sandboxes, policy engines, and audit trails for LLM agents.
- **Kubernetes Controllers & Operators**: Extending K8s APIs to automate complex infrastructure maintenance and monitoring.
- **Low-Latency AI & Audio Systems**: Designing memory-efficient neural networks for real-time signal processing on edge devices.
- **Hybrid Retrieval & Search Architecture**: Combining sparse lexical search (BM25) with dense vector embeddings for precise domain retrieval.

---

<div align="center">

### Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-peach-delta-57.vercel.app/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debanjan-rakshit-558912289/)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/unknownsideofme)

<br/>

*Debanjan Rakshit · [portfolio-peach-delta-57.vercel.app](https://portfolio-peach-delta-57.vercel.app/)*

</div>
