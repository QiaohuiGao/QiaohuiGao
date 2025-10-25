# 👋 Hi there, I'm Bonnie (Qiaohui Gao)
### AI Engineer | Full-Stack Developer | Product-Minded Technologist

🎓 **M.S. in Information Systems @ Northeastern University (Boston, MA)**  
💡 **Driven by curiosity to design intelligent systems that connect human insight with scalable automation.**  

---

### 🧭 About Me
I'm an AI Engineer passionate about turning research-level ideas into production-grade systems.  
My work bridges **machine learning, software engineering, and product strategy** — from designing hybrid RAG frameworks to deploying multimodal agents and scalable backend services.

- 💬 Ask me about **LLM system design, RAG pipelines, or intelligent product frameworks**  
- 🧠 Currently exploring **LangGraph, vector databases, and multi-agent orchestration**  
- 📫 Reach me at: **gao.qia@northeastern.edu** | [LinkedIn](https://www.linkedin.com/in/qiaohui-gao/)

---

### ⚙️ Tech Focus Areas
| Domain | Tools & Frameworks |
|--------|--------------------|
| **AI & ML Engineering** | PyTorch, LangChain, LangGraph, FAISS, OpenAI / Claude APIs, HuggingFace, TensorRT |
| **Full-Stack Development** | Flask, Spring Boot, React / Vite, Node.js, Vue.js, REST / GraphQL APIs |
| **Cloud & DevOps** | AWS (Lambda, ECS, S3, RDS), Docker, Kubernetes, Prometheus, Grafana, Terraform |
| **Databases & Storage** | PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, Pinecone |
| **Languages** | Python, Java, JavaScript, SQL |

---

### 🧠 Highlighted AI Projects

#### 🏥 [AI Triage & Patient Guide Agent (Harvard Medical School)](https://github.com/QiaohuiGao/AI_Triage_Agent)
> **LLM-powered clinical triage assistant** that interprets symptom descriptions, reasons through medical logic, and routes patients to the right care.

- Hybrid **RAG + rule-based** triage framework grounded by SNOMED-like ontology  
- **LLM reasoning (Claude / GPT-4o mini)** with confidence-weighted routing and safe response generation  
- <3 s median latency; ≥ 85 % routing accuracy validated on synthetic patient cases  

#### 🧩 [SmartCare Multimodal Troubleshooting Agent](https://github.com/QiaohuiGao/SmartCare_Agent)
> **Industrial AI assistant** that automates device fault diagnosis and operator training using manuals, SOPs, and multimodal inputs.

- **Hybrid RAG + deterministic state-machine** pipeline bounded by **YAML fault graphs**  
- **Qwen2-72B + Mixtral-8×7B ensemble** for bilingual reasoning with **knowledge-graph retrieval**  
- Multimodal fusion (OCR + ASR + text) → vectorized embeddings (FAISS + bge-m3) for contextual search  
- Flask + LangGraph agent orchestration with **ReAct-style tool calls** and Redis caching  
- CUDA + Docker Swarm deployment achieving ~1.8 s latency and 99.9 % uptime  

 #### 💼 [AI Sourcing Agent (Web Crawler + GPT Summarizer)](https://github.com/QiaohuiGao/BizNavigator_AISearchAgent)
> **Intelligent sourcing assistant** that automates supplier discovery, price comparison, and quote aggregation.

- Accepts **multi-keyword weighted inputs** (e.g., *“medical sensor [0.6], silicone tube [0.4]*”) to generate optimized Google queries.
- **Crawls and scrapes** result pages with Selenium + BeautifulSoup, extracting product specs, vendor contacts, and pricing tables.
- Uses **GPT-4o mini / Claude Haiku** to summarize supplier reliability and detect duplicates.
- **Exports structured leads to Excel / CSV** with ranking scores and metadata for easy follow-up.
- Planned extensions:  
  - 🔗 *Vector DB* of historical suppliers for **semantic re-ranking**  
  - 🤝 *Negotiation module* (LLM simulates buyer–supplier dialogue)  
  - 🛠 *FastAPI backend + React dashboard* for interactive sourcing

**Tech:** Python · Selenium · BeautifulSoup · LangChain · GPT-4o mini · Pandas · Excel Export  
**Focus:** AI automation · data pipeline design · information retrieval · business tooling

#### 🗄️ [Distributed Object Storage System (Raft + RocksDB)](https://github.com/QiaohuiGao/Distributed-Object-Storage-System)
> **Highly available distributed storage engine** supporting 9 000 concurrent 512 KB reads/writes per second.

- Implemented the **Raft consensus protocol** (leader election, log replication, dynamic cluster membership) for strong consistency.  
- Built **server-side caching with LRU eviction**, sustaining a **70 % cache hit rate**.  
- Customized **RocksDB** and **HashKV** for different workloads; optimized RocksDB for NVMe flash, improving write throughput **+35 %**.  
- Added **Prevote** to reduce leader switch frequency during network jitter, achieving **99 % system availability**.  
- Optimized **ReadIndex / FollowerRead** paths for relaxed-consistency reads, boosting read performance **+50 %**.  

**Tech:** C++ · RocksDB · HashKV · Raft · NVMe storage · gRPC · Docker  
**Focus:** distributed systems · consensus protocols · storage engine tuning · performance optimization

#### 🧍‍♀️ [AI-Based Physical Performance Evaluation Tool](https://github.com/QiaohuiGao/ExploreWorld)
> Flask + React system that estimates human fitness metrics from pose video input and provides **LLM-based personalized training suggestions**.

---

### 🌱 What I’m Learning
- Reinforcement learning for reasoning agents (ReAct + Graph-of-Thought)  
- Efficient RAG optimization (semantic chunking, hybrid retrieval, caching)  
- Frontend-LLM integration for **interactive AI products**  

---

### 🧰 Languages & Tools
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/redis/redis-icon.svg" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" width="40" height="40"/>
</p>

---

### 🧩 Quick Facts
- 🚀 Comfortable moving from **model architecture** → **API design** → **frontend integration**.  
- 🧭 Experienced with both **research prototypes** and **real-world deployments**.  
- 🎯 Open to roles in **AI Engineering**, **AI Product Management**, and **Full-Stack Development**.

---

⭐ **Let’s build intelligent systems that make real impact.**  
