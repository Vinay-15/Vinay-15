<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=D9BED1&height=140&section=header&text=Vinay%20Chandra%20Konda&fontColor=4A3B47&fontSize=40&animation=fadeIn" alt="header"/>  
  
<a href="https://git.io/typing-svg">  
    <img src="https://readme-typing-svg.herokuapp.com?font=Montserrat&weight=500&size=25&duration=4000&pause=500&color=D9BED1&width=560&lines=Hi%2C+I'm+Vinay+Chandra+Konda;AI+Infrastructure+%2F+LLM+Serving+Engineer;vLLM+%7C+KV+Cache+%7C+PagedAttention;MS+Data+Science+%40+CU+Boulder" alt="Typing SVG"/>  
</a>  
  
<div>  
    <img src="./assets/cat-hack.gif" alt="Terminal GIF"/>  
</div>  
  
---  
  
### 👨‍💻 About Me  
  
I'm an **AI Infrastructure / LLM Serving** engineer and **MS in Data Science** candidate at **CU Boulder** (GPA 4.0/4.0). I focus on making LLM inference **fast, reliable, and memory-efficient under load** — benchmarking and fixing the points where **KV cache**, throughput, and latency break down on constrained GPUs.  
  
- 🔭 Building **KV-cache-aware LLM serving** on vLLM (PagedAttention, preemption, prefix caching)  
- 🛠️ Interested in **inference optimization, GPU memory management, and serving-stack reliability**  
- 🏥 Ex-**Stanford Health Care** (AI Dev Intern) · 🏦 Ex-**Oracle** (2 yrs, core banking at scale)  
- 🏆 **Red Bull Innovation Track Winner** — HackCU12  
  
---  
  
### ⚙️ Focus: AI Infrastructure & LLM Serving  
  
- **KV cache & memory management** — PagedAttention block pools, preemption/recompute, cache saturation  
- **Serving stacks** — vLLM, OpenAI-compatible APIs, concurrent load testing, prefix caching, chunked prefill  
- **Performance eval** — throughput, TTFT, p50/p99 latency, Prometheus `/metrics` instrumentation  
- **GPU & HPC** — NVIDIA A100 (MIG), CUDA version matching, Slurm scheduling, Apptainer/Docker containers  
  
`vLLM` · `PagedAttention` · `CUDA` · `PyTorch` · `Slurm/HPC` · `Apptainer/Docker` · `Prometheus` · `FastAPI`  
  
---  
  
### 🚀 Featured Project  
  
**[KV-Cache-Aware LLM Serving on Constrained GPUs](https://github.com/Vinay-15/KV_Cache_LLM_Serving)** — `vLLM` · `CUDA` · `A100 MIG` · `Slurm`  
- Deployed an OpenAI-compatible **vLLM** API on a memory-limited **20 GB A100 MIG** slice (CU Boulder Alpine HPC), scheduled with **Slurm** and containerized with **Apptainer**  
- Reproduced and quantified the **"KV-cache wall"**: doubling concurrency (64 → 128) cut throughput ~4,000 → ~1,700 tok/s, spiked p99 latency ~4 s → ~475 s, and triggered **2,075 KV preemptions** as the engine thrashed on evict/recompute  
- Built a benchmarking harness — concurrent load generator, `/metrics` scraper, and concurrency sweep — as a base for admission control, prefix caching, and scheduler/preemption changes  
  
---  
  
### 🧠 Broader Skills  
  
**LLMs & Agents:** `LangChain` · `LangGraph` · `RAG (FAISS + BM25 + RRF)` · `ReAct Agents` · `Pydantic` · `Multi-Agent Systems`  
**ML & Data:** `PyTorch` · `TensorFlow` · `Scikit-learn` · `Pandas` · `NumPy` · `PySpark`  
**Cloud & MLOps:** `AWS` · `GCP` · `Azure` · `Docker` · `Podman` · `Kafka` · `Airflow` · `Databricks` · `Snowflake`  
**Languages:** `Python` · `Scala` · `C/C++` · `PL/SQL` · `Shell/UNIX` · `SQL`  
  
---  
  
### 💼 Experience  
  
**🏥 AI Developer Intern — Stanford Health Care** *(May 2026 – Jul 2026 · 3 mo)*  
- Built a real-time **BACnet/IP data pipeline** and database from scratch for hospital telemetry feeding ML/agentic workflows  
- Deployed **on-premise LLM agents** with tool-calling, async concurrency, and hardened error handling; owned LLM-serving-stack uptime and health monitoring in a regulated environment  
  
**🏦 Software Developer — Oracle (Financial Services)** *(Aug 2023 – Aug 2025 · 2 yrs)*  
- Owned core banking modules serving **600+ institutions** (UBS, Access Bank); built data pipelines in Python/PL/SQL/Shell/REST  
- Automated an ETL + validation framework (**10K+ daily txns**, defects −30%); ran containerized deployments (Docker, Podman) at **99.9% uptime**  
  
---  
  
### 🤝 Connect with Me  
  
<div>  
    <a href="https://www.linkedin.com/in/vinaychandra15/">  
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>  
    </a>  
    <a href="https://github.com/Vinay-15">  
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>  
    </a>  
    <a href="mailto:vinaykonda15@gmail.com">  
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>  
    </a>  
</div>  
  
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=D9BED1&height=120&section=footer" alt="footer"/>
