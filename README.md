<div align="center">
  <h1>Hey, I'm Dinakaran V 👋</h1>
  <p><strong>Systems & Data Infrastructure Engineer · Core at Ostrium Labs</strong></p>
  <p>
    <em>From cosmic-ray muon telescope instrumentation to distributed storage engines, real-time streaming & AI observability.</em>
  </p>

  <p>
    <a href="https://github.com/dina-kar"><img src="https://img.shields.io/github/followers/dina-kar?label=Followers&style=flat-square&color=238636" alt="Followers" /></a>
    <a href="https://www.npmjs.com/~dina-kar"><img src="https://img.shields.io/badge/npm-packages-cb3837?style=flat-square&logo=npm" alt="npm" /></a>
    <a href="mailto:dinakaranvijayakumar@outlook.com"><img src="https://img.shields.io/badge/Email-dinakaranvijayakumar%40outlook.com-blue?style=flat-square&logo=microsoftoutlook" alt="Email" /></a>
  </p>
</div>

---

### ⚡ What I'm Building & Shipping

- 🦀 **[Loams](https://github.com/ostrium-labs/loams)** (`Rust`, `Lance`, `Tantivy`, `DataFusion`, `Arrow Flight SQL`)  
  Unified hybrid retrieval and storage engine keeping vectors, full-text (BM25), graphs, and relational tables on your own object-storage bucket (S3/GCS/Azure/RustFS). Drop-in wire compatibility with **Qdrant**, **Elasticsearch**, and **Arrow Flight SQL**. Built to eliminate the multi-cluster sprawl of running Elasticsearch + Qdrant + Kafka + separate workflow engines.

- ⚡ **[qrc](https://github.com/ostrium-labs/qrc)** (`Rust`, `Cranelift`, `Compiler Tooling`, `CI`)  
  Fastest possible Rust debug builds. An Ostrium Labs research initiative establishing a two-lane architecture: a Cranelift-powered fast lane for rapid test/CI loops, while preserving stock `rustc` + LLVM for production release builds.

- 🤖 **[agent-ui](https://github.com/dina-kar/agent-ui)** (`TypeScript`, `React 19`, `Angular`, `Nx`)  
  Universal, backend-agnostic agent canvas SDK. Normalized event streams, human-in-the-loop approval gates, tool execution timelines, and workspace panels for AI coding agents.

- 📦 **[ngx-streamdown](https://github.com/dina-kar/ngx-streamdown)** (`Angular`, `Signals`, `npm`)  
  Streaming markdown renderer for Angular AI applications with real-time incomplete token syntax healing and signal reactivity.  
  👉 `npm install ngx-streamdown`

- 🛠️ **[A3 Stack](https://github.com/dina-kar/A3-Stack)** (`Next.js 15`, `NestJS`, `Mastra`, `Temporal`, `Kafka`)  
  Production-ready monorepo scaffolding tool for autonomous AI agents, distributed workflows, and background job orchestration.  
  👉 `npx create-a3-stack`

- 🎨 **[BrandByte](https://github.com/dina-kar/brandbyte)** & **[BReX](https://github.com/dina-kar/brex)**  
  Production AI apps: automated ad creative generation platform powered by FLUX.1 + LLaMA 3.3, and a privacy-first clinical blood report reasoning engine using Google Gemini.

---

### 🛠️ Architecture & Systems Expertise

```ascii
┌─────────────────────────────────┐
│     STORAGE & RETRIEVAL CORES   │  Rust · Lance · Tantivy · Apache DataFusion · Flight SQL · TiKV · ClickHouse
├─────────────────────────────────┤
│    SEARCH & VECTOR PLATFORMS    │  Elasticsearch (DSL / Lucene) · Qdrant (HNSW / Filtering) · Hybrid Fusion (RRF)
├─────────────────────────────────┤
│    STREAMING & BATCH COMPUTE    │  Redpanda · Apache Kafka · Apache Spark · Apache Flink
├─────────────────────────────────┤
│  DATA INTEGRATION & ETL / ELT   │  Airbyte · Singer Taps · Apache Camel · CDC / Custom Connectors
├─────────────────────────────────┤
│    ORCHESTRATION & RESILIENCE   │  Temporal (Durable Executions) · Apache Airflow · Kestra · BullMQ
├─────────────────────────────────┤
│   OBSERVABILITY & AI EVALS      │  Self-Hosted Langfuse · OpenTelemetry (OTel) · OpenObserve · Retrieval Evals
├─────────────────────────────────┤
│    AUTONOMOUS AGENT RUNTIMES    │  Headless Agent Canvases · Mastra · LangGraph · Event Reducers · Approval Gates
├─────────────────────────────────┤
│   LOW-LEVEL & INSTRUMENTATION   │  C · Python · AMD Xilinx FPGAs (Vivado) · FTDI Hardware Drivers · LabVIEW
└─────────────────────────────────┘
```

---

### 🔬 Deep Dives & Engineering Interests

- **Storage & Zero-Copy Retrieval**: Architecting log-as-spine storage primitives, decoupled compute/storage tiers on object buckets, and DataFusion-based vector + BM25 plan optimization.
- **AI Observability & Rigorous Evals**: Operating self-hosted **Langfuse** for prompt lifecycle management, LLM tracing, and offline/online evals on hybrid search retrieval accuracy; instrumenting distributed systems with **OpenTelemetry (OTel)** and **OpenObserve**.
- **Unified Ingestion & Integration**: Designing resilient ingestion pipelines with **Airbyte**, **Singer specifications**, and **Apache Camel** enterprise integration patterns (EIP).
- **Durable Workflows & Streaming**: Building deterministic, crash-resilient workflows using **Temporal**, paired with sub-millisecond event streaming via **Redpanda** and **Kafka**.
- **Physical Instrumentation & Hardware**: Interfacing high-frequency sensors, writing low-level drivers in C/Python for FTDI chips, and synthesizing digital signal processing algorithms on AMD Xilinx FPGAs (Vivado).

---

### 🏆 Key Milestones & Scientific Background

- 🔭 **Research Intern @ TIFR (Tata Institute of Fundamental Research, Ooty)**  
  Worked at the Cosmic Ray Laboratory on **GRAPES-3** (the world's largest and most sensitive cosmic-ray muon telescope tracking solar storms and thundercloud electrical potentials). Engineered low-level data acquisition routines in **C & Python**, interfaced high-speed **FTDI USB/FIFO chips**, and designed signal-processing algorithms for **AMD Xilinx FPGAs (Vivado)**.

- 🎓 **Education & Campus Systems**  
  B.E. in **Electronics and Instrumentation Engineering (EIE)** from **Government College of Technology (GCT Coimbatore)**. Architected and deployed the official campus placement management system ([gct-placements](https://github.com/dina-kar/gct-placements)).

- 🚀 **Engine Internals**  
  Merged **1,000+ PRs** across distributed engine storage primitives, metastores, log engines, and wire protocols for **Loams**.

- 📦 **NPM Package Author**  
  Maintainer and publisher of developer tooling and streaming markdown SDKs on **npm** (`ngx-streamdown`).

- 🤖 **Robotics Competitor**  
  Participated in the national **e-Yantra Robotics Competition** (IIT Bombay).

- 🎮 **Gamified Systems**  
  Built [Super Pixel Odyssey](https://github.com/dina-kar/super-pixel), a 2.5D game in Phaser.js gamifying real-world digital advertising auction models and pricing mechanics.

---

### 💻 Stack & Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,c,cpp,python,ts,go,kafka,spark,postgres,clickhouse,nextjs,react,angular,nodejs,nestjs,docker,kubernetes" alt="Tech Stack" />
</p>

| Category | Tools & Technologies |
| :--- | :--- |
| **Languages** | Rust, C, C++, Python, TypeScript, Go, Java, SQL, Verilog/VHDL |
| **Storage & Engines** | Lance, Tantivy, DataFusion, Arrow Flight, ClickHouse, TiKV/TiDB, Neon Postgres, Redis |
| **Search & Vectors** | Elasticsearch, Qdrant, LanceDB, HNSW, BM25, Reciprocal Rank Fusion (RRF) |
| **Streaming & Compute**| Redpanda, Apache Kafka, Apache Spark, Apache Flink |
| **Integration & ETL** | Airbyte, Singer Taps, Apache Camel, CDC Pipelines |
| **Orchestration** | Temporal (Durable Execution), Apache Airflow, Kestra, BullMQ |
| **Observability & Evals**| Self-Hosted Langfuse, OpenTelemetry (OTel), OpenObserve, Prometheus |
| **Hardware & Embedded**| AMD Xilinx Vivado, FPGA, FTDI Chip Drivers, LabVIEW, Digital Circuit Modeling |
| **App & UI Frameworks** | React 19, Next.js 15, Angular Signals, NestJS, FastAPI, Tailwind v4 |

---

### 📊 GitHub Activity & Insights

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dina-kar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Dinakaran's GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dina-kar&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dina-kar&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p>Let's connect: <a href="mailto:dinakaranvijayakumar@outlook.com">dinakaranvijayakumar@outlook.com</a> · <a href="https://github.com/dina-kar">GitHub @dina-kar</a></p>
</div>
