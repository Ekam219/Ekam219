<h1 align="center">Ekamjot Jaggi</h1>
<p align="center">
  <b>Trading Engineer · Flow Traders, Hong Kong</b><br/>
  C++17/20 HFT · Lock-free systems · Exchange connectivity · Sub-millisecond latency
</p>

<p align="center">
  <a href="https://linkedin.com/in/ekam-jot-singh-938419249"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:jota74530@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=Ekam219&style=flat&color=0e75b6"/>
</p>

---

### What I do

I build and maintain **co-located, low-latency trading infrastructure** at [Flow Traders](https://www.flowtraders.com/) — exchange connectivity, market-data feed handlers, and event-driven middleware for digital-assets strategies operating at **sub-millisecond latency**.

Previously: quant engineering intern at Triapti Research (C++ tick ingestion, Kafka pipelines), open-source contributor to Google DeepMind tooling, and internship at Telus International (Node.js microservices on Kubernetes).

---

### Core stack

| Domain | Technologies |
|---|---|
| **Systems / HFT** | C++17/20, lock-free queues, feed handler architecture, co-located Linux |
| **Streaming** | Apache Kafka, multithreaded pipelines, real-time risk monitoring |
| **Infra & DevOps** | Docker, Kubernetes, Helm, ArgoCD, Jenkins, GitHub Actions |
| **Observability** | Prometheus, Grafana, latency profiling, structured logging |
| **Algorithms** | Graph theory, dynamic programming, probabilistic optimization, ICPC |
| **Other** | Python, SQL, Bash |

---

### Featured projects

#### [`market-data-aggregator`](https://github.com/Ekam219/market-data-aggregator) — C++17
> 1M+ ticks/sec ingestion pipeline with lock-free SPSC queues, CRC32 validation, sub-10ms p99 latency, Google Test suite, Docker/CI.

Key design: cache-line aligned `Tick` struct (64 bytes), compile-time CRC32 LUT, per-feed latency histogram, feed state machine (CONNECTING → ACTIVE → STALE → DROPPED → RECOVERING).

#### [`Probabilistic-Optimization-of-MSTs`](https://github.com/Ekam219/Probabilistic-Optimization-of-Minimum-Spanning-Trees-under-Edge-Uncertainty-on-Competitive-Ratio) — C++
> Cut & Cycle Model 2-approximation for MST under edge uncertainty. 35% fewer edge queries vs baseline. Benchmarked over 500+ randomized test cases.

#### [`VISION_AI`](https://github.com/Ekam219/VISION_AI) — Published research
> AI-assisted navigation for visually impaired users. Obstacle detection + depth estimation via Google Gemini. 94% satisfaction across 15 pilot users. Published in IJCSPUB Vol. 14, Issue 2, 2024.

---

### Competitive programming & awards

- 🥇 **Global Rank #47** — Google Solution Challenge (2024)
- 🏆 **Rank #1** — TechX Nova Global Hackathon (5,000+ participants)
- 🎯 **Top 5%** — Adobe Gen-Solve Hackathon
- 🔢 **ICPC** — Amritapuri Regional Qualifier
- 🎓 Full merit scholarship, NIT Jalandhar (Top 5% cohort)

---

### GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ekam219&layout=compact&theme=github_dark&langs_count=6&hide=html,css,procfile" height="140"/>
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Ekam219&theme=github-dark-blue&hide_border=true" height="140"/>
</p>

---

<p align="center"><i>Always interested in low-latency systems, exchange infrastructure, and competitive algorithms.</i></p>
