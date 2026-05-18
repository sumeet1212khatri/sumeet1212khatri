<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║           SUMEET KHATRI  ·  Systems & AI Engineer            ║
║     C++17 · Python · Low-Latency · Machine Learning          ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## `whoami`

```cpp
class SumeetKhatri {
    const std::string focus   = "C++ Systems · LLM Inference · HFT Engines";
    const std::string college = "B.Tech IT — Indus University, Ahmedabad (2026)";
    const std::string intern  = "SDE Intern @ STW Services LLP, Pune";
    const std::string goal    = "Systems Software Engineer";
    const std::string stack   = "C++17 | Python | AVX2/SIMD | OpenMP | FastAPI";
};
```

---

## Projects

### `NanoMind` — Custom LLM Inference Engine from Scratch
> 152M parameter GPT-2 trained from scratch · Hand-written C++17 inference engine · No llama.cpp

```
Architecture : GPT-2 (16L · 12H · 768D) trained on 500K GPT-4 quality samples
Engine       : C++17 · AVX2 SIMD · OpenMP · Session-persistent KV-Cache
Batch Prefill: 3× TTFT improvement (1013ms cold → 410ms warm, 2.47× KV speedup)
Throughput   : 35 tok/s @ concurrency=1 · SSE streaming · FastAPI + Boost.Asio
```

[![Repo](https://img.shields.io/badge/Repo-NanoMind-161b22?style=flat-square&logo=github)](https://github.com/sumeet1212khatri/Nano-Mind)
[![HuggingFace](https://img.shields.io/badge/🤗%20Live%20Demo-NanoMind-FFD21E?style=flat-square)](https://huggingface.co/spaces/NOT-OMEGA/NanoMind)

---

### `LogAI-Engine` — 3-Tier Hybrid Log Classifier
> Production-grade cascading pipeline: Regex → BERT/ONNX → Mistral-7B

```
Scale        : 2,000,000 enterprise logs · 318.29s wall time
Throughput   : ~6,286 logs/sec (ProcessPoolExecutor · multi-core)
Tier 1 Regex : 92.2% coverage · p50 latency 0.020ms · zero cost
Tier 2 BERT  : ONNX Runtime on CPU · 3–5× faster than PyTorch
Tier 3 LLM   : Mistral-7B via HF API · 500k-slot LRU MD5 cache · 74% cache hit
```

[![Repo](https://img.shields.io/badge/Repo-LogAI--Engine-161b22?style=flat-square&logo=github)](https://github.com/sumeet1212khatri/LogAI-Engine)
[![HuggingFace](https://img.shields.io/badge/🤗%20Live%20Demo-LogAI--Engine-FFD21E?style=flat-square)](https://huggingface.co/spaces/NOT-OMEGA/LogAI-Engine)

---

### `Orderflow-Replay-Engine` — HFT Exchange Simulator
> Price-time priority matching engine · C++17 · Strategy framework · Backtester

```
Architecture : Matching engine (std::map levels, std::list FIFO queues)
Risk Manager : 5-layer pre-trade checks · sliding-window rate limiter (1s)
Strategies   : MarketMaking · Momentum (EMA Cross) · MeanReversion (Z-Score)
Order Types  : LIMIT · MARKET · IOC · FOK · GoodForDay · StopLimit · Iceberg
Bugs Fixed   : 17 bugs (4 CRITICAL: iterator UB, mutex races, Windows pipe crash)
API          : FastAPI + subprocess IPC · real-time L2 orderbook · WebSocket
```

[![Repo](https://img.shields.io/badge/Repo-Orderflow--Replay--Engine-161b22?style=flat-square&logo=github)](https://github.com/sumeet1212khatri/Orderflow-replay-engine)
[![HuggingFace](https://img.shields.io/badge/🤗%20Live%20Demo-Orderflow-FFD21E?style=flat-square)](https://huggingface.co/spaces/NOT-OMEGA/orderflow-replay-engine)

---

### `HFT-OrderBook` — C++20 High-Performance Order Book
> Lock-free data structures · SPSC/MPMC queues · 20M order benchmark

```
Throughput   : Benchmarked at 20M orders · sub-microsecond matching latency
Memory       : Custom ObjectPool (lock-free freelist) · ArenaAllocator (O(1) reset)
Queues       : SPSCQueue (cache-line padded) · MPMCQueue (atomic CAS)
Order Types  : GTC · FAK · FOK · GFD · Market · PostOnly · StopLimit · Iceberg
Pipeline     : FastAPI + subprocess IPC · Dockerized · HF Spaces deployed
```

[![Repo](https://img.shields.io/badge/Repo-HFT--OrderBook-161b22?style=flat-square&logo=github)](https://github.com/sumeet1212khatri/High-Performance-CPP-Order-Matching-Engine)
[![HuggingFace](https://img.shields.io/badge/🤗%20Live%20Demo-HFT--OrderBook-FFD21E?style=flat-square)](https://huggingface.co/spaces/NOT-OMEGA/HFT-OrderBook)

---

### `CollabDocs` — Real-Time Collaborative Editor
> C++17 WebSocket server · Operational Transformation engine · Multi-user cursors

```
OT Engine    : 4-case pairwise transform (II, ID, DI, DD) · diamond convergence
Server       : Boost.Beast WebSockets · Boost.Asio coroutines · strand write queues
Batching     : Op broadcast batching (8ms/20-op window) · ~15–20× message reduction
Presence     : Per-user colored cursors · typing indicators · user join/leave events
```

[![Repo](https://img.shields.io/badge/Repo-CollabDocs-161b22?style=flat-square&logo=github)](https://github.com/sumeet1212khatri/CollabDocs)
[![HuggingFace](https://img.shields.io/badge/🤗%20Live%20Demo-CollabDocs-FFD21E?style=flat-square)](https://huggingface.co/spaces/NOT-OMEGA/Inference)

---

## Competitive Programming

<div align="center">

### Codeforces
[![Codeforces Stats](https://codeforces-readme-stats.vercel.app/api/card?username=sumeetkhatri398&theme=dark&v=1)](https://codeforces.com/profile/sumeetkhatri398)

### LeetCode
[![LeetCode Stats](https://leetcard.jacoblin.cool/sumeet_khatri?theme=dark&font=Fira+Code&ext=contest)](https://leetcode.com/u/sumeet_khatri/)

### CodeChef
[![CodeChef](https://img.shields.io/badge/CodeChef-sumeetkhatri__2-brown?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/sumeetkhatri)
 
</div>

---

## Tech Stack

```
Languages    │ C++17/20 · Python 3.11 · SQL
Systems      │ AVX2 SIMD · OpenMP 
ML / AI      │ PyTorch · ONNX Runtime · HuggingFace · sentence-transformers
Backend      │ FastAPI · Uvicorn · Gradio 
DevOps       │ Docker · CMake · GitHub Actions · HuggingFace Spaces
Internship   │ Power Automate · Power Apps · Copilot Studio · Dataverse · JS
```

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-sumeet1212khatri.github.io-0f0f0f?style=flat-square)](https://sumeet1212khatri.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-khatri--sumeet-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/khatri-sumeet)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-NOT--OMEGA-FFD21E?style=flat-square)](https://huggingface.co/NOT-OMEGA)

</div>
