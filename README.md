# Hi, I'm Mohamed Khaled 
**Research Engineer | Aspiring PhD & Master Candidate in AI & Hardware Security**

I'm a systems engineer and researcher working at the intersection of **Computer Architecture, Hardware Security, and Applied AI** — bridging low-level silicon microarchitecture with high-level agentic and neural reasoning systems.

My background combines open-source hardware fundamentals with industry experience building agentic systems. I focus on engineering secure intelligent hardware, auditing microarchitectural threat surfaces, and exploring ML vulnerabilities at the physical layer.

---

## 🔬 Core Research & Technical Pillars
* **AI & Hardware Security Intersection:** Machine learning attacks on physical/hardware primitives (e.g., Physical Unclonable Function modeling), automated hardware backdoor/Trojan verification, and agentic code auditing frameworks.
* **Computer Architecture & Silicon Workflows:** RTL design (Verilog), processor design (RISC-V ISA), structural control unit FSMs, pipeline hazard mitigations, logic optimization, and memory-safe systems programming (Rust).
* **Applied Cryptography & Network Defense:** Secure-by-design cryptographic system deployment (authenticated symmetric encryption combined with asymmetric key wrapping models), topological threat graphing, and CVSS-driven risk derivation.

---

## 🎓 Education
### **The American University in Cairo** — *B.Sc. in Computer Engineering, Minor in Math & Business* (2022 – 2027)
* **Honors:** USAID Merit Award
* **Relevant Coursework:** Security in Computing, AI Security, Computer Architecture, Digital Design, Computer Organization & Assembly Language, Operating Systems, Distributed Systems, Computer Networks, Data Structures & Algorithms, Analysis & Design of Algorithms, Artificial Intelligence, Database Systems, Software Engineering
* **Mathematics:** Linear Algebra, Discrete Mathematics, Calculus, Probability & Statistics

### **University of Central Florida (UCF)** — *Exchange Semester, Computer Engineering* (Spring 2025)

---

## 💼 Research & Industry Experience
### **Microsoft** — *Thesis Mentorship* (Feb 2026 – Present)
* Researching **Temporal Reasoning** with Microsoft mentors: fine-tuning **Small Language Models (SLMs)** and implementing **Retrieval-Augmented Generation (RAG)** to enhance model reasoning.

### **The American University in Cairo** — *Research Assistant* (Jun 2025 – Present)
* Developing an **open-source programming management unit (PMU)** that controls FPGA bitstream configuration, an open alternative to the proprietary equivalents in Intel and Xilinx devices (paper in preparation).
* Designing, simulating, and benchmarking **Physically Unclonable Functions (PUFs)** for use in the design, analyzing trade-offs between area overhead, reliability, and uniqueness.

### **Groupe SEB** — *Information Security Intern* (Jun 2026 – Sep 2026)
* Developed and extended an in-house **Python penetration-testing toolkit** (174K+ LOC, 249 scanner modules) covering web/API, cloud (AWS/GCP/Azure/Kubernetes), and Active Directory attack classes, exposed via CLI, Flask dashboard, JSON-RPC API, and MCP server.
* Executed an authorized black/gray-box **security audit** of a production multi-tenant e-commerce platform over five test rounds, documenting **45 actionable findings** (11 Critical, 13 High) with CVSS v3.1 scoring, three end-to-end kill chains, and a prioritized remediation roadmap.
* Deployed on-premises **LLM and OCR hosting** (Ollama, llama.cpp) and integrated it into AI-assisted finding triage, keeping sensitive data off external APIs.

### **Xanadu Group** — *Full Stack Engineer Intern* (Jun 2026 – Sep 2026)
* Built the group's corporate website in **Next.js 16** with a scroll-driven logo assembly (**GSAP ScrollTrigger**, Lenis), dynamic detail routes, interactive portfolio cards, and a **MapLibre** MENA network map.
* Designed a guided contact flow on a custom **Node.js** backend with rate limiting, CSRF protection, and input sanitization; added dynamic OG images, reduced-motion accessibility, and **Vitest** tests.

### **Eden MEA** — *AI Engineering Intern* (Jan 2026 – Feb 2026)
* **Financial Intelligence Pipeline:** Engineered an end-to-end financial intelligence pipeline using **n8n** and **AWS RDS (PostgreSQL)**.
* **Autonomous AI Agent System:** Co-architected and implemented a fully autonomous agent framework driven by Anthropic's Claude APIs. Engineered the orchestration layer to allow the agent to capture abstract user specifications, automatically generate code architectures, run native test suites, execute self-debugging loops, resolve environment dependencies, schedule internal tasks, and handle continuous multi-cloud deployment.
* **Scalable Infrastructure & DevOps:** Built and optimized robust relational data infrastructure using PostgreSQL deployed on AWS RDS. Containerized microservice clusters via Docker to enforce cross-environment parity. Developed deep workflow automation routines using n8n deployed across hybrid AWS and Azure enterprise boundaries.

---

## 🌟 Featured Projects Showcase

### ⚡ AI-Driven Hardware Security
#### 🧩 [Arbiter PUF Modeling Attack](https://github.com/mmohamedkhaled/arbiter-puf-modeling-attack) *(Project Owner)*
* Designed an offensive hardware evaluation suite focused on modeling **Arbiter Physical Unclonable Functions (PUFs)**.
* Demonstrated the fragility of silicon delay-based security primitives by collecting Challenge-Response Pairs (CRPs) and utilizing mathematical machine learning models to simulate, map, and successfully clone the hardware fingerprint with high predictive accuracy.

#### 🗣️ [LLM Language Jailbreak Study](https://github.com/mmohamedkhaled/llm-language-jailbreak-study) *(Project Owner)*
* Ran a defensive red-team measurement study asking whether an **encoding channel** — an invented language (SPUN), ciphers (ROT13/Base64), rare or real languages, or fine-tuned fluency — can bypass an LLM's refusal training.
* Built the evaluation harness around the public AdvBench set and measured **5 instruction-tuned models**, with decode-fidelity gating, multi-judge labeling (keyword + LLM judges with agreement/kappa reporting), and human adjudication.
* Included LoRA fine-tuning on benign data and internal refusal-activation probes; elicited completions, weights, and keys are deliberately withheld from the public release.

#### 🧮 NeuralTram — Systolic Array for Edge AI *(private repo)*
* Designed a minimal **weight-stationary systolic array** (parameterized N×M grid of INT8 multiply-accumulate cells) for edge-AI inference, targeting **SkyWater 130nm** in under 1 mm² at 100 MHz.
* Written in Yosys-compatible Verilog-2001 and verified with **cocotb** testbenches against a NumPy golden model.

---

### 💻 Computer Architecture & Low-Level Systems
#### ⚙️ [RISC-V 32I CPU Core](https://github.com/GM-Sniper/RISCV32I-CPU) *(Contributor & Co-Developer)*
* Built a clean-room implementation of a 32-bit RISC-V processor conforming to the **RV32I ISA** specification from scratch using Verilog.
* Implemented the underlying execution architecture including Arithmetic Logic Units (ALUs), structural control unit Finite State Machines (FSMs), and register file access logic.
* Analyzed pipeline data hazards and microarchitectural bottlenecks — developing foundational knowledge on where physical side-channels and microarchitectural leaks manifest.

#### 🦀 [LPM-Rust](https://github.com/mmohamedkhaled/LPM-Rust) *(Project Owner)*
* Co-built a **Linux Process Manager** in **Rust** with three front ends: a keyboard-driven terminal UI (Ratatui), a graphical UI (egui), and a scriptable CLI.
* Supports real-time CPU/memory monitoring, filtering and sorting, process-tree and detail views, historical trend tracking, and process control (kill, terminate, pause, resume) with confirmation prompts.

#### 🚨 RescueMesh *(course project, private repo)*
* Building a three-peer distributed cloud in **Rust** for simulated smart-campus emergency coordination, covering election-based load balancing, fault tolerance, and recovery.
* Uses Raft-style consensus with pre-vote and leadership transfer, benchmarked in simulation against the Bully and Chang-Roberts ring election algorithms.
* Ships a workload generator, a fault-injection control tool, and 87 unit tests plus 13 end-to-end tests.

#### 🎛️ [Logic Circuits Simulator](https://github.com/mmohamedkhaled/Logic-Circuits-Simulator) & [Digital Clock](https://github.com/mmohamedkhaled/Digital_Clock) *(Project Owner)*
* **Logic Circuits Simulator:** Programmed a discrete event logic simulator capable of simulating logical gate propagation delays and boolean algebra processing.
* **Digital Clock:** Designed and implemented a digital time-tracking logic architecture, mapping register increments to timing matrices.

---

### 🧠 Advanced Machine Learning & Deep Learning
#### 📆 [Temporal News Reasoning](https://github.com/Abdallah-Afifi/temporal-news-reasoning) *(Contributor)*
* Contributed to an advanced Natural Language Processing (NLP) framework built to test and expand cognitive temporal logic in Transformers.
* Worked on dataset preprocessing pipelines, fine-tuning methodologies, and chronology-focused evaluation structures to stress-test large language models on tracking data consistency, causal chains, and timeline reconstruction.

#### 📓 [ML Fundamentals Notebooks](https://github.com/mmohamedkhaled/ml-fundamentals-notebooks) *(Project Owner)*
* Compiled an academic repository of deep dives, implementations, and derivations covering core machine learning algorithms from scratch. Includes regression, categorization, mathematical validation frameworks, and optimization mechanics.

#### 🎯 Open-CUAS Simulator *(private repo)*
* Built a Python ground-station simulator for counter-drone interception in 2D and 3D, using **Kalman filtering** to smooth noisy detections and predict target trajectories and **proportional navigation** to compute the intercept vector.
* Supports an interactive mouse-driven target mode and an optional **YOLOv8** camera/video detection mode.

---

### 🛡️ Cryptography & Defensives
#### 🏹 Hunter Toolkit *(private repo)*
* Built a modular, **detection-only** security toolkit in Python with **217 native scanner modules** and 65 optional external-tool adapters, driven from a unified CLI, an interactive shell, and a web dashboard.
* Covers recon (port scanning, DNS and subdomain enumeration, HTTP/TLS fingerprinting), modern web/API classes (GraphQL abuse, JWT key confusion, SSTI, request smuggling, OAuth and SAML flaws, LLM prompt injection), cloud (S3/GCS/Azure/IAM/Kubernetes), and Active Directory posture.
* Gates every high/critical detector behind a negative control or differential check so findings are proven with bounded, non-destructive probes and reported with remediation guidance.

#### 🔐 [Cybersecurity 101](https://github.com/mmohamedkhaled/cybersecurity-101) *(Project Owner)*
* Wrote 36 small, self-contained Python implementations of cryptography (AES, RSA, Diffie-Hellman), hashing, checksums/CRC, number theory, and networking math, organized as a learning path by difficulty.
* Every script is import-safe with built-in tests, and 27 of them run on the standard library alone.

#### ✅ [cksumx](https://github.com/mmohamedkhaled/cksumx) *(Project Owner)*
* Built a **C++17** command-line tool and embeddable library on OpenSSL's libcrypto for computing and verifying file checksums (SHA-1/2/3, BLAKE2, MD5, RIPEMD-160).
* Streams files in fixed-size chunks so huge inputs hash in constant memory, and compares digests in constant time to mitigate timing side-channels.

#### 🔢 [Hill Cipher](https://github.com/mmohamedkhaled/hill-cipher) *(Project Owner)*
* Implemented the classical Hill cipher in dependency-free **C++17**: encryption, decryption with modular key-inverse validation, and a **known-plaintext attack** that recovers the key and self-verifies.
* Covered by unit tests and a byte-for-byte regression suite.

#### 📦 [RansomVault-Lab](https://github.com/mmohamedkhaled/RansomVault-Lab) *(Project Owner)*
* Developed a highly structured, educational python-based security toolkit simulating modern file-encryption frameworks.
* Constructed a pristine hybrid cryptographic orchestration layer utilizing **AES-256-GCM** for authenticated file stream data encryption wrapped by **RSA-4096 (OAEP + SHA-256)** keys for secure asymmetric management.
* Fully structured as an immutable, safe-by-design package with zero-extortion, localized environments, and rigorous validation tests.

#### 📊 [Attack Graph Analysis (aga)](https://github.com/mmohamedkhaled/attack-graph-analysis) *(Project Owner)*
* Modeled security landscapes by implementing network asset threat structures using graph-theoretic Python libraries (`NetworkX`, `Matplotlib`).
* Generated topological network maps to evaluate vulnerability chains, deriving adaptive path weights utilizing dynamic CVSS (Common Vulnerability Scoring System) parameter metrics.
* Authored a professional security disclosure policy (`SECURITY.md`) outlining vulnerability reporting procedures and structural legal safe harbor constraints.

---

### 🌐 Full-Stack Web
#### 🏠 AUC ResLife Management System *(private repo)*
* Built a Residential Life dashboard for the American University in Cairo in **Next.js 16**, TypeScript, and Tailwind CSS on **Supabase** (PostgreSQL, Auth, Row Level Security).
* Staff look up students by ID to manage housing assignments, visit logs, and form requests; every change is written to an automatic audit trail, and Google Form responses sync in through a webhook.

---

## 🛠️ Technical Ecosystem & Toolkit

| Category | Tools |
|---|---|
| **Languages** | Python, C++, Rust, Verilog, C, JavaScript/TypeScript, SQL (PostgreSQL) |
| **Hardware & EDA** | FPGA, Vivado, Yosys, Icarus Verilog, OpenFPGA, SkyWater 130nm (sky130), cocotb, Digital Design |
| **Hardware Security** | PUFs, Fuzzy Extractors (BCH), Secure Bitstream Loading (AES-256, SHA-256, HMAC), JTAG |
| **Security** | Penetration Testing, LLM Red-Teaming, OWASP Top 10, CVSS v3.1 |
| **AI & ML** | SLMs, RAG, LoRA Fine-Tuning, Local LLM Hosting (Ollama, llama.cpp), AI Agent Orchestration, Temporal Reasoning, PyTorch, Hugging Face, NetworkX, Pandas, NumPy, Jupyter |
| **Web** | Next.js, React, Node.js, Flask, Supabase, Tailwind CSS, GSAP, MapLibre, Vitest |
| **Systems & Cloud** | Docker, AWS (RDS/EC2), Azure, PostgreSQL, Git, n8n |

---

## 🏆 Leadership & Achievements
* **Enactus AUC** — *President* (Jun 2025 – Present): Directing overall strategy and operations for social entrepreneurship initiatives and corporate partnerships.
* **Capsim Business Challenge** (May 2024): Global top 3 out of hundreds of teams.

---

## 📬 Let's Connect & Collaborate
I am highly interested in discussing **PhD opportunities, collaborative research projects, or advanced engineering positions** in AI hardware optimization, microarchitectural security, or cryptographic hardware modeling.

* 🌐 **LinkedIn:** [Mohamed Khaled](https://www.linkedin.com/in/mohamed-khaled-3ba258322/)
* 💻 **GitHub Profile:** [@mmohamedkhaled](https://github.com/mmohamedkhaled)
* 🎓 **Academic Email:** [mohamedabdelfatah572@aucegypt.edu](mailto:mohamedabdelfatah572@aucegypt.edu)
