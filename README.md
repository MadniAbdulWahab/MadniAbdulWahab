# Abdul Wahab Madni

Research software engineer at the University of Bonn's Hertz Chair for Artificial Intelligence and
Neuroscience. I build full-stack and data-heavy software in Java/Spring Boot, Python, TypeScript/React
and C++, and I care about tests, reproducibility and code other people can maintain.

M.Sc. Computer Science, University of Bonn · Bonn, Germany ·
[LinkedIn](https://linkedin.com/in/abdul-wahab-madni) · madniabdulwahab@gmail.com

---

### What I work on

- **Research software (CAIAN, University of Bonn, since January 2024):** Python and MATLAB tools for
  research data, and Java/Spring Boot features for the Calibench benchmark platform, in a shared,
  reviewed codebase with GitLab CI: user administration, password reset with Spring Security,
  ranking views with confidence intervals, and recovery of interrupted benchmark jobs on a Linux
  server.

### Selected projects

| Project | What it shows | Stack |
|---|---|---|
| [**DataPipe**](https://github.com/MadniAbdulWahab/cpp-data-processing-engine) | Chunked, typed CSV engine with a bounded thread pool, deterministic aggregation merges and a pybind11 Python module. CI on GCC and Clang. | C++20 · CMake · CTest · pybind11 · GitHub Actions |
| [**GymTrack**](https://github.com/MadniAbdulWahab/gymtrack-core) ([live](https://gym-tracker.madniabdulwahab.workers.dev)) | Local-first workout PWA I built to replace an app that kept progress analytics behind a subscription. IndexedDB for instant offline writes, keyset-paginated sync to Supabase/PostgreSQL with row-level security. Core data layer and sync engine public with 31 tests; 100+ tests in the full app. | React · TypeScript · Dexie · Supabase · Vitest · Cloudflare |
| [**SplitLedger**](https://github.com/MadniAbdulWahab/splitledger) ([live](https://splitledger-madni.duckdns.org)) | Shared-expenses app for friends: imports bank statements instead of typing, settles up with one GiroCode scan in a banking app, and keeps an append-only double-entry ledger with a SHA-256 hash chain so history can't be silently rewritten. Idempotent APIs, typo-tolerant PostgreSQL search, accounts with invite links, installable web app. Deployed and verified on AWS entirely with Terraform (ECS Fargate, RDS, SQS, Kotlin Lambda, CloudWatch alarms) and self-hosted with HTTPS on a free Oracle Cloud VM. 204 API tests against real PostgreSQL. | Java 21 · Spring Boot · PostgreSQL · React · TypeScript · Kotlin · AWS · Terraform |
| [**GraphRAG QA**](https://github.com/MadniAbdulWahab/graphrag) | Knowledge graph built from SQuAD passages with an LLM (11.7k nodes, 14.3k edges), Louvain communities, hybrid BM25 + FAISS retrieval; evaluated with BLEU/ROUGE/BERTScore, Recall@k/MRR and a text-only RAG baseline. | Python · PyTorch · Transformers · NetworkX · FAISS |
| [**Supply Chain Lakehouse**](https://github.com/MadniAbdulWahab/supply-chain-operations) | Bronze/silver/gold pipeline over 1.25M shipment events with idempotent loads, quarantine, late-arriving data handling and a Power BI model; ported to Microsoft Fabric and reconciled 40/40 checks against the DuckDB version. | Python · PySpark · Delta Lake · Microsoft Fabric · DuckDB · Power BI |
| [**FIFA 26 Companion**](https://github.com/MadniAbdulWahab/fifa26) ([live](https://madniabdulwahab.github.io/fifa26/)) | World Cup app with provider adapters that normalise external APIs, TanStack Query caching and a seeded Monte Carlo tournament simulation. | React · TypeScript · TanStack Query · Vitest · GitHub Actions |
| [**Cowboy Shootout**](https://github.com/MadniAbdulWahab/cowboy-shootout) | Java 21 simulation with O(1) circle operations, seeded injectable randomness, streamed JSON protocol with SHA-256, 30 JUnit tests and a Monte Carlo fairness analysis. | Java 21 · Maven · JUnit · Jackson |
| [**Insurance Sales BI**](https://github.com/MadniAbdulWahab/sap-insurance-sales-bi) | Star schema (2 facts, 6 dimensions), manifest-driven data-quality checks, reconciliation and a six-page SAP Analytics Cloud story. | Python · SQL · SQLite · SAP Analytics Cloud |

### Tools I use most

Python · SQL · Java · Spring Boot · Kotlin · FastAPI · C++ · TypeScript · React · PostgreSQL ·
Docker · Linux · Git · GitHub Actions · AWS · Terraform · pandas · PyTorch · Power BI

Languages: English (C2), German (B1), Urdu (native)
