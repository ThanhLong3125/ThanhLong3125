<div align="center">

<!-- Terminal Header Banner -->
<a href="https://github.com/ThanhLong3125">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2500&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&height=55&lines=Nguyen+Thanh+Long;Backend+%26+Cloud+Infrastructure;Real-Time+Streaming+%26+Edge+AI;Resilient.+Observable.+Secure." alt="Typing Banner" />
</a>

<p align="center">
  <code>Distributed Systems</code> &nbsp;•&nbsp;
  <code>Event-Driven Microservices</code> &nbsp;•&nbsp;
  <code>Real-Time Streaming</code> &nbsp;•&nbsp;
  <code>Cloud & DevOps</code>
</p>

<!-- Social Links -->
<p align="center">
  <a href="https://github.com/ThanhLong3125"><img src="https://img.shields.io/badge/GitHub-ThanhLong3125-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/thanhlongnguyen-dev"><img src="https://img.shields.io/badge/LinkedIn-thanhlongnguyen--dev-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:thanhlongnguyen.dev@gmail.com"><img src="https://img.shields.io/badge/Email-thanhlongnguyen.dev@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=ThanhLong3125&style=flat-square&color=0891B2&label=PROFILE+VIEWS" alt="Profile Views" />
</p>

</div>

---

### 💻 `whoami --spec`

```bash
thanhlong@core-system:~$ neofetch --profile
```

```yaml
identity:
  name: "Nguyen Thanh Long"
  role: "Backend Engineer"
  location: "Ho Chi Minh City, Vietnam"
  education: "B.S. in Data Science @ UTH (GPA: 3.5 / 4.0)"
  current_role: "Backend Developer @ SGOD Solutions (NestJS, Kafka, Redis, MongoDB)"

engineering_focus:
  - High-throughput REST & gRPC microservices with event-driven architecture
  - Real-time data & DSP audio streaming pipelines with backpressure management
  - Applied cryptography & tamper-evident audit logging (Ed25519, SHA-256)
  - Container orchestration, cloud autoscaling (GKE, K8s, HPA), and Linux performance
```

---

### 🛠️ `tech-stack --all`

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,python,bash&theme=dark" alt="Languages & Frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,kafka&theme=dark" alt="Databases & Streaming" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,gcp,linux,git&theme=dark" alt="Cloud & Infrastructure" />
</p>

<details open>
<summary><b>Detailed Technology Breakdown</b></summary>
<br/>

| Domain | Core Technologies & Protocols |
| :--- | :--- |
| **Languages & Scripting** | `TypeScript`, `JavaScript`, `Python`, `SQL`, `Bash` |
| **Backend & Microservices** | `Node.js`, `NestJS`, `gRPC (Protobuf)`, `RESTful APIs`, `WebSockets` |
| **Databases & Messaging** | `PostgreSQL`, `MongoDB`, `Redis (Caching, Rate Limiting)`, `Apache Kafka` |
| **Cloud & Infrastructure** | `Docker`, `Docker Compose`, `Kubernetes (K8s, HPA)`, `Google Kubernetes Engine (GKE)`, `Linux` |
| **Edge AI & Audio DSP** | `WebGPU`, `WASM SIMD`, `Whisper ASR (On-Device)`, `Web Audio API (FIR Resampling, Biquad Filter)` |

</details>

---

### 🚀 `ls -la ~/featured-projects/`

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ [ClearVoice](https://github.com/ThanhLong3125/ClearVoice)
> **Real-Time DSP Audio Streaming & On-Device AI Pipeline**  
> `TypeScript` · `Web Audio API` · `WebGPU` · `Whisper ASR`

- Local-first audio capture & streaming DSP pipeline with **48kHz $\rightarrow$ 16kHz FIR resampling** and **4th-order Biquad bandpass filter** (260Hz–3400Hz).
- Sequential clause chunking with **0.3s stride overlap** and bounded backpressure queues with dynamic token budgeting.
- **WebGPU hardware-accelerated** on-device Whisper inference (**RTF ~0.25**) with zero audio data transmitted externally.

</td>
<td width="50%" valign="top">

### 🛡️ [AegisLedger](https://github.com/ThanhLong3125/aegis-ledger)
> **Cryptographic Audit Trail Microservice**  
> `NestJS` · `TypeScript` · `PostgreSQL` · `Ed25519` · `SHA-256`

- High-assurance audit logging service utilizing **SHA-256 hash chaining** and **Ed25519 digital signatures** for non-repudiation.
- Implemented PostgreSQL append-only rules, database triggers, and automated tamper-detection alerts against unauthorized data modifications.
- Designed following Clean Architecture principles with complete test coverage.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☸️ [Cloud Autoscaling on Kubernetes](https://github.com/ThanhLong3125/autoscaling-kubernetes)
> **GKE Infrastructure & Load Testing Benchmark**  
> `Google Kubernetes Engine` · `Docker` · `HPA` · `K6`

- Production-grade microservices deployment on **Google Kubernetes Engine (GKE)** with containerization and Liveness/Readiness probes.
- Configured **Horizontal Pod Autoscaler (HPA)** to dynamically scale workloads (2 to 5 Pods) under simulated **K6** concurrent traffic spikes.
- Validated service mesh routing, zero-downtime rolling updates, and internal DNS discovery.

</td>
<td width="50%" valign="top">

### 📑 [Cryptocurrency Forecasting Benchmark](https://doi.org/10.15276/hait.09.2026.35)
> **Peer-Reviewed Journal Publication (HAIT, 2026)**  
> `Python` · `CCXT` · `Pandas` · `Time-Series ETL` · `Machine Learning`

- Published research paper in the *Herald of Advanced Information Technology* ([DOI: 10.15276/hait.09.2026.35](https://doi.org/10.15276/hait.09.2026.35)).
- Engineered an automated data extraction pipeline ingesting Binance real-time order books and candle data via **Python/CCXT**.
- Constructed and benchmarked a 23-feature financial time-series dataset.

</td>
</tr>
</table>
</div>
