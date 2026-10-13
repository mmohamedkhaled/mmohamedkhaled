# Mohamed Khaled

**Computer Engineering student at The American University in Cairo · Hardware security research**

I work on hardware security, mainly FPGA configuration security and Physically Unclonable Functions (PUFs). My current research is a secure-boot scheme for FPGAs that generates keys from PUFs at boot, so the device needs no dedicated secure key storage. I also study how machine learning breaks hardware security primitives, and I am applying to PhD programs for Fall 2027.

---

## Research interests

- **FPGA configuration security:** roots of trust for bitstream loading that can be verified openly.
- **PUFs and hardware identity:** designs that stay unpredictable against machine-learning modeling attacks within a practical area and reliability budget.
- **Machine learning and hardware security:** using learning-based methods both to attack hardware primitives and to verify hardware designs.

---

## Research experience

### The American University in Cairo — Research Assistant (Jun 2025 – present)
- Developing an open-source programming management unit (PMU) that controls FPGA bitstream configuration, as an open alternative to the proprietary units in Intel and Xilinx devices.
- Developed a PUF-based key-generation approach for secure boot that removes the need for dedicated secure non-volatile key storage. Paper in preparation for IEEE HOST 2027.
- Designed, simulated, and benchmarked PUF candidates for the design, comparing area overhead, reliability, and uniqueness.

### Microsoft — Undergraduate thesis mentorship (Feb 2026 – present)
- Improving temporal reasoning in small language models through fine-tuning and retrieval-augmented generation, with Microsoft mentors.

---

## Selected projects

### Hardware security

**[Arbiter PUF Modeling Attack](https://github.com/mmohamedkhaled/arbiter-puf-modeling-attack)**
Simulation framework for Arbiter PUFs and machine-learning modeling attacks against them. Using the standard parity (phi) feature transform, a linear model predicts responses of an unprotected Arbiter PUF with 99.3% accuracy; adding fixed stage permutations breaks linear separability and drops the same attack to 52.5%, close to random guessing.

**NeuralTram: systolic array for edge AI** *(private)*
Parameterized weight-stationary systolic array of INT8 multiply-accumulate cells, targeting SkyWater 130 nm at under 1 mm² and 100 MHz. Written in Yosys-compatible Verilog-2001 and verified with cocotb against a NumPy reference model.

**[RISC-V RV32I core](https://github.com/GM-Sniper/RISCV32I-CPU)** *(co-developer)*
RV32I processor in Verilog: ALU, control unit, register file, and analysis of pipeline hazards.

### Machine learning security

**[LLM Language Jailbreak Study](https://github.com/mmohamedkhaled/llm-language-jailbreak-study)**
Defensive measurement study of whether encodings (an invented language, ROT13/Base64, rare languages) bypass refusal training in 5 instruction-tuned models on AdvBench. Uses decode-fidelity checks, multiple judges with inter-rater agreement (kappa), and human adjudication. Harmful completions and model weights are withheld from the public release.

### Systems and cryptography

- **[cksumx](https://github.com/mmohamedkhaled/cksumx):** C++17 checksum tool and library on OpenSSL (SHA-2/3, BLAKE2) with constant-memory streaming and constant-time digest comparison.
- **[Hill Cipher](https://github.com/mmohamedkhaled/hill-cipher):** C++17 implementation with a known-plaintext key-recovery attack.
- **[Cybersecurity 101](https://github.com/mmohamedkhaled/cybersecurity-101):** 36 small, tested Python implementations of cryptography, hashing, and number theory.
- **[RansomVault-Lab](https://github.com/mmohamedkhaled/RansomVault-Lab):** teaching lab for hybrid encryption (AES-256-GCM with RSA-4096-OAEP key wrapping). It encrypts only local test files and contains no spreading or extortion logic.
- **[Attack Graph Analysis](https://github.com/mmohamedkhaled/attack-graph-analysis):** network attack graphs in NetworkX with path weights derived from CVSS scores.
- **[LPM-Rust](https://github.com/mmohamedkhaled/LPM-Rust):** Linux process manager in Rust with terminal, graphical, and command-line front ends.
- **RescueMesh** *(course project, private):* three-node fault-tolerant system in Rust with Raft-style leader election, compared against Bully and Chang–Roberts election; 100 automated tests with fault injection.
- **[Logic Circuits Simulator](https://github.com/mmohamedkhaled/Logic-Circuits-Simulator):** event-driven gate-level simulator with propagation delays.

---

## Industry experience

**Groupe SEB — Information Security Intern** (Jun – Sep 2026)
- Performed an authorized black/gray-box audit of a production multi-tenant e-commerce platform over five rounds: 45 findings (11 Critical, 13 High) scored with CVSS v3.1, including three end-to-end attack chains.
- Extended an in-house Python penetration-testing toolkit (249 scanner modules across web/API, cloud, and Active Directory) and set up on-premises LLM hosting so findings could be triaged without sending data to external APIs.

**Xanadu Group — Full Stack Engineer Intern** (Jun – Sep 2026)
- Built the corporate website in Next.js with a Node.js backend protected by rate limiting, CSRF protection, and input sanitization.

**Eden MEA — AI Engineering Intern** (Jan – Feb 2026)
- Built a financial data pipeline (n8n, AWS RDS) and an orchestration layer for AI agents.

---

## Education

**The American University in Cairo** — B.Sc. Computer Engineering, minors in Mathematics and Business (2022 – 2027)
GPA 3.77/4.00 · USAID Merit Award
Relevant courses: Security in Computing, AI Security, Computer Architecture, Digital Design, Computer Organization & Assembly, Operating Systems, Distributed Systems, Artificial Intelligence

**University of Central Florida** — Exchange semester, Computer Engineering (Spring 2025)

---

## Skills

| Area | Tools |
|---|---|
| Hardware | Verilog, FPGA, Vivado, Yosys, OpenFPGA, Icarus Verilog, cocotb, SkyWater 130 nm |
| Hardware security | PUFs, fuzzy extractors (BCH), secure bitstream loading (AES-256, SHA-256, HMAC), JTAG |
| Security | Penetration testing, LLM red-teaming, OWASP Top 10, CVSS v3.1 |
| Machine learning | PyTorch, Hugging Face, LoRA fine-tuning, RAG, NumPy, Pandas |
| Languages | Python, C++, C, Rust, Verilog, SQL, TypeScript |

---

## Leadership

**Enactus AUC — President** (Jun 2025 – present), previously Project Director for two years.
**Capsim Business Challenge** — global top 3 (May 2024).

---

## Contact

Email: [mohamedabdelfatah572@aucegypt.edu](mailto:mohamedabdelfatah572@aucegypt.edu) · [LinkedIn](https://www.linkedin.com/in/mohamed-khaled-3ba258322/)