# 👋 Hi, I'm Felix Yustian Setiono

### Senior Computer Vision Engineer & CV Team Lead | Edge AI & ML Systems Architect | LLM & Agentic Systems

Senior AI/ML engineer and researcher with **10+ years** of building and deploying intelligent autonomous systems — from **Edge AI** (TensorRT, NVIDIA Jetson) and real-time computer-vision pipelines to **LLM-powered agentic workflows** (LangChain, LangGraph, MCP). I bridge hardware-level optimization and high-level AI architecture: sub-66.7 ms latency on 15 simultaneous 1080p streams with TensorRT FP16 on one end, enterprise agentic systems for banking risk and fraud analytics on the other.

Now **Senior Computer Vision Engineer & CV Team Lead at Sigmawave AI (Singapore)**, leading multi-camera computer-vision systems for edge deployment, and **AI Architect & Technical Lead at V-TEKI**.

---

🌐 **[felixsetiono.my.id](https://felixsetiono.my.id)** · 🚀 **[All my projects, live from GitHub](https://felixyustian.github.io/projects.html)** · 🎬 **[Portfolio video](https://youtu.be/L-YUNmVDats)**

---

- 📧 **Email:** [felixyustian@gmail.com](mailto:felixyustian@gmail.com)
- 🌐 **Website:** [felixsetiono.my.id](https://felixsetiono.my.id)
- 💼 **LinkedIn:** [linkedin.com/in/felixsetiono](https://linkedin.com/in/felixsetiono)
- 🐦 **X:** [x.com/felixyustian](https://x.com/felixyustian)
- 📘 **Facebook:** [facebook.com/felixyustian](https://www.facebook.com/felixyustian)
- 📸 **Instagram:** [instagram.com/felixyustian](https://www.instagram.com/felixyustian/)
- 🎓 **Google Scholar:** [scholar.google.com/citations?user=W_NZMf4AAAAJ](https://scholar.google.com/citations?user=W_NZMf4AAAAJ&hl=en)
- 🔬 **ORCiD:** [orcid.org/0000-0002-5240-0466](https://orcid.org/0000-0002-5240-0466)
- 🗂️ **GitHub Pages:** [felixyustian.github.io](https://felixyustian.github.io)

---

## 🔬 Research & Technical Focus

- **Edge AI & High-Performance Computing:** TensorRT (FP16/INT8 quantization), NVIDIA Jetson, PyTorch Forward Hooks, inference acceleration, dynamic batching, latency budgeting
- **Multi-Camera Computer Vision:** detection and tracking (YOLO family, ByteTrack), cross-camera person re-identification, footfall analytics
- **Generative AI & Multi-Agent Systems:** QwenPaw (AgentScope), Qwen3-14B, LangChain, LangGraph, MCP (Model Context Protocol), Claude API (Anthropic), Gemini API, Prompt Engineering (CoT, ToT, RTCFC)
- **Document AI & Governed LLM Extraction:** Tesseract / PaddleOCR, Indonesian KTP extraction, schema-bound (Pydantic) extraction, grounding checks, and deterministic rule engines — the model structures language but never decides the verdict
- **Embedded AI & Robotics:** ROS, UAV / AUV / AGV systems, microcontroller integration (Arduino, STM32, Raspberry Pi, dsPIC), motor control algorithms
- **Software Architecture & MLOps:** Domain-Driven Design, async FastAPI, Go (Golang) microservices, Docker, experiment tracking, model versioning, GitHub Actions CI/CD
- **Data & Analytics:** ETL pipelines, RAG-based knowledge retrieval, data visualization (Pandas, Plotly, Tableau)

---

## 💻 Tech Stack

```
AI / ML          │ PyTorch · TensorFlow · Scikit-Learn · OpenCV · Pandas · NumPy · Plotly · MLOps
Generative AI    │ LangChain · LangGraph · MCP · QwenPaw (AgentScope) · Qwen3-14B · Claude API
                 │ Gemini API · OpenAI API · LLaMA · Transformers · Prompt Engineering (CoT / ToT / RTCFC)
Edge AI & HPC    │ TensorRT (FP16/INT8) · NVIDIA Jetson · Inference Acceleration · Dynamic Batching · RTOS
Computer Vision  │ YOLO11 / YOLOv8 · ByteTrack · SigLIP 2 · Re-ID · Core ML · Vision framework
OCR & Doc AI     │ Tesseract OCR · PaddleOCR · pdfplumber · Pydantic schema-bound extraction · rule engines
Programming      │ Python · Go (Golang) · C/C++ · JavaScript · TypeScript · Swift · HTML/CSS · SQL · PHP
Agentic Systems  │ QwenPaw · Playwright · BeautifulSoup4 · DOKU REST API · Redis · Event-Driven Scheduling
Web3 / On-Chain  │ Solidity · ERC-5192 soulbound · EIP-712 · Foundry · wagmi / viem · Lisk Sepolia
Cloud & DevOps   │ GCP · Azure ML · AWS · Vercel · Docker · Docker Compose · GitHub Actions · Git
Backend & APIs   │ FastAPI · Django · Node.js / Express · Next.js · Nginx · REST · WebSocket · Async I/O
Embedded         │ Raspberry Pi · Arduino · STM32 · NodeMCU · Xiao ESP-32 · dsPIC · Embedded C++
Robotics         │ UAV (Hexacopter, Quadrotor, VTOL) · AUV · AGV · Quadrupeds · Humanoid · ROS
Languages        │ Indonesian & Javanese (Native) · English — TOEFL iBT 80 · French — DELF A2
                 │ Mandarin — Business Chinese BCT 1 (2026) · Japanese & Korean (Basic)
```

---

## 🚀 Featured Projects

### 🏁 Hackathon & Competition Projects

- **[OpenClaw2026_NexaPaw_LapakPintar](https://github.com/felixyustian/OpenClaw2026_NexaPaw_LapakPintar)** *(Team NexaPaw — OpenClaw Agenthon 2026, RISTEK x Build Club | Best Payment Use Case Track)*
  **LapakPintar** — Autonomous multi-agent Business OS for Indonesia's 65 million SMEs. Five specialized agents running 24/7: **Pantau** (competitor price monitoring on Tokopedia/Shopee via Playwright), **Analitik** (Qwen3-14B sales forecasting + RAG), **Konten** (AI product content), **Bayar** (DOKU REST API payment reconciliation + anomaly detection), **Laporan** (daily business insights). Orchestrated by **QwenPaw (AgentScope)** + Qwen3-14B with long-term memory, skill registry, and event-driven scheduling.
  `Python 3.11 · QwenPaw · Qwen3-14B · Playwright · DOKU API · FastAPI · Redis · Docker Compose`

- **[neraca-fakta](https://github.com/felixyustian/neraca-fakta)** *(Sectors Hackathon 2026)* — 🌐 [Live demo](https://neraca-fakta.vercel.app)
  **Neraca Fakta** — fact-checks Indonesian stock tips (chat text, links, or screenshots) against official IDX financial data via the Sectors API. Governance pattern: the LLM (Claude / OpenAI / Gemini) only extracts typed claims; a **deterministic engine assigns every verdict** against fixed tolerances. Web app + Telegram + WhatsApp bots over one pipeline; 98-test suite; bilingual (ID/EN).
  `Python · FastAPI · React / TypeScript / Vite · SQLite · Claude / OpenAI / Gemini APIs · Sectors API`

- **[zkktp](https://github.com/felixyustian/zkktp)** *(Coinfest Asia 2026)*
  **zkKTP** — privacy-preserving proof-of-personhood for Indonesia: verify a KTP off-chain (Go gateway, KTP OCR + NIK validation, quality gate, liveness / selfie match, calibrated confidence gate), then mint a non-transferable **ERC-5192 soulbound credential** from an EIP-712 attestation. KTP, NIK and biometrics never touch the chain; a zero-knowledge unlinkability circuit is the roadmap upgrade.
  `Go 1.22 · Python 3.11 · FastAPI · OpenCV · Tesseract · React / wagmi · Solidity 0.8.24 · Foundry · Lisk Sepolia`

- **[jaga-perairan](https://github.com/felixyustian/jaga-perairan)** *(BRIN AIDeaNation 2026)*
  **Jaga Perairan** — Harmful Algal Bloom early-warning proof-of-concept: estimates harmful-particle density from microscope imagery and raises a tiered alert (AMAN / WASPADA / BAHAYA), end-to-end from a Go gateway to a FastAPI service to a web overlay. The detector is a classical placeholder, ready for a trained species model.
  `Python · FastAPI · Go · OpenCV · Docker Compose · Vercel`

---

### ⚡ Edge AI & Computer Vision

- **[visitor-counting-console](https://github.com/felixyustian/visitor-counting-console)**
  Multi-camera footfall analytics on existing CCTV: **YOLO11 + ByteTrack** entry/exit line-counting with per-track voting, occupancy vs cumulative-visitor separation, and no-double-count safeguards. OpenCV kiosk plus a FastAPI browser console with MJPEG overlays and a live WebSocket feed; SigLIP 2 zero-shot gender / age as a demographic baseline; TensorRT export and CUDA Docker.
  `Python · PyTorch · YOLO11 · ByteTrack · SigLIP 2 · FastAPI · OpenCV · TensorRT · Docker`

- **[crosscam-reid](https://github.com/felixyustian/crosscam-reid)**
  From-scratch **cross-camera person re-identification** pipeline: per-camera greedy-IoU tracking → appearance embedding (colour histogram or ResNet50) → online cross-camera gallery fusion with EMA prototypes. Ships a synthetic, self-scoring offline demo; CI on Python 3.9 / 3.12.
  `Python · NumPy · OpenCV · optional torchvision`

- **[PPE_Detection_TensorRT](https://github.com/felixyustian/PPE_Detection_TensorRT)**
  Enterprise-grade PPE compliance monitoring on **NVIDIA Jetson**: YOLOv11 with TensorRT FP16 quantization and **zero mAP degradation**, PyTorch Forward Hooks for Layer-Collapse mitigation, and an async FastAPI gateway handling **15 simultaneous 1080p RTSP streams at ≤66.7 ms latency**. Domain-Driven Design architecture.
  `Python · PyTorch · TensorRT · YOLOv11 · FastAPI · Docker · NVIDIA Jetson · C++`

- **[kyc-vision-system](https://github.com/felixyustian/kyc-vision-system)**
  Production-grade **KYC document verification** microservice: Go 1.22 API Gateway (JWT auth, rate limiting) + Python CV service — Indonesian KTP OCR (Tesseract 5, deskewing, regex extraction of NIK, Name, DOB, Address), image quality gating, YOLOv8 face detection, and selfie liveness check. CI/CD via GitHub Actions; Pytest + Go tests.
  `Go 1.22 · Python 3.11 · FastAPI · OpenCV · YOLOv8 · Tesseract OCR · Docker · GitHub Actions`

- **[PerceiveReason_Apple_M5](https://github.com/felixyustian/PerceiveReason_Apple_M5)**
  On-device **Perceive → Reason** pipeline for Apple Silicon: Core ML + Vision on the Neural Engine for perception, a swappable `LanguageModel` (Apple Foundation Models or Claude) for reasoning. MobileNetV3 conversion with int8 quantisation and a SwiftUI reference app.
  `Python · coremltools · Core ML · Swift · SwiftUI · Claude API`

---

### 🧠 Generative AI & Agentic Systems

- **[enterprise_ai_context_engine_fraud_risk_marketing](https://github.com/felixyustian/enterprise_ai_context_engine_fraud_risk_marketing)**
  Enterprise AI Context Engine powered by **LangGraph + MCP + Gemini API**, unifying AML/Fraud detection, Credit Risk underwriting, and Marketing Analytics via cyclic multi-agent orchestration, dynamic tool registration, and a human-readable explainability layer for compliance.
  `Python · LangChain · LangGraph · MCP · Gemini API · Pandas · Scikit-Learn · GCP`

- **[RouteReason](https://github.com/felixyustian/RouteReason)**
  Plain-language delivery routing: GPT-5.6 turns a described run into a schema-validated routing problem, a pluggable solver (Clarke-Wright reference, OR-Tools ready) plans it, and GPT-5.6 explains the tradeoffs with an interactive map.
  `Python · GPT-5.6 · OR-Tools · FastAPI`

- **[enterprise-agentic-pipeline](https://github.com/felixyustian/enterprise-agentic-pipeline)**
  Next.js + GPT-4o pipeline for multi-step document workflows: Zod-enforced structured outputs, tenant-isolated RAG context, and a self-scored confidence gate that hands low-confidence cases to human review.
  `Next.js · TypeScript · GPT-4o · Zod · RAG`

- **[edusenseai](https://github.com/felixyustian/edusenseai)**
  Adaptive learning platform with a Claude-powered tutor and quiz generator, course library, learning analytics, and XP / badge gamification.
  `FastAPI · Claude API · React 18 · Vite · SQLAlchemy · Tailwind CSS`

- **[synapse](https://github.com/felixyustian/synapse)**
  Full-stack AI meeting assistant on the **Claude (Anthropic) API**: transcript in → Executive Summary, Action Items, Decision Log, Key Topics, and a Follow-Up Email Draft. FastAPI backend + static frontend via Nginx; REST API (`/api/analyze`); Docker Compose.
  `Python · FastAPI · Claude API · HTML/CSS/JS · Nginx · Docker Compose · GitHub Actions`

- **[gemini-chatbot-v2](https://github.com/felixyustian/gemini-chatbot.-v2)**
  Full-stack Node.js chatbot on the **Gemini API** with real-time token streaming and multi-turn context management.
  `Node.js · JavaScript · Gemini API · Express`

---

### 📄 Document AI & Enterprise Architecture

- **[soji-ad-applicability](https://github.com/felixyustian/soji-ad-applicability)**
  Aviation Airworthiness Directive applicability engine: reads FAA / EASA AD PDFs and answers *"is aircraft X affected by AD Y?"* Regex isolates the operative clause (6 pages → ~400 chars), the LLM structures only that clause, and a **deterministic rule engine** decides with a per-decision audit trail. N-run stability and verbatim grounding checks; all supplied verification examples pass.
  `Python 3.11 · pdfplumber · Pydantic · Gemini / OpenAI / Anthropic APIs`

- **[veridoc](https://github.com/felixyustian/veridoc)**
  AI Document Intelligence design + FastAPI reference scaffold for ~60,000 financial documents/day: routed hybrid OCR, tiered extraction, fraud screening, and a calibrated confidence gate that auto-approves or escalates to human review. UU PDP & OJK compliance designed in.
  `Python · FastAPI · PaddleOCR · VLMs · Pydantic`

- **[benteng](https://github.com/felixyustian/benteng)**
  Enterprise OCR platform architecture for a multinational bank (~2M confidential documents/month, 99.9% availability): regional data planes for residency, zero-trust security, OpenShift GPU node pools, and a tested tamper-evident hash-chained audit log.
  `Kubernetes / OpenShift · Helm · OPA / Rego · Vault · Terraform · Python`

---

### 🤖 Robotics & Autonomous Systems

- **[krti2024_scu_unika — Team SIRI](https://github.com/felixyustian/krti2024_scu_unika)**
  Computer-vision autonomous hexacopter: onboard PyTorch real-time detection on Raspberry Pi, ROS sensor fusion, GPS-denied obstacle avoidance, and failsafe routines. *Indonesian Flying Robot Contest (KRTI) 2024.*
  `Python · PyTorch · OpenCV · ROS · Raspberry Pi · C++`

- **[krbai2024_scu_unika — Team SOUNDBOT (SOUNDBOT-ORCA)](https://github.com/felixyustian/krbai2024_scu_unika)**
  Modular AUV software stack: underwater target detection under variable turbidity, 6-DOF thruster vectoring, depth/pressure buoyancy control, and a mission state machine. Companion to the IJEECS SOUNDBOT-ORCA paper. *Indonesian Underwater Robot Contest (KRBAI) 2023 & 2024.*
  `Python · OpenCV · Embedded C · Depth Sensors · Motor Control`

- **[krtmi2024_scu_unika — Team SAURO](https://github.com/felixyustian/krtmi2024_scu_unika)**
  Autonomous trash-collector AGV: dual-processor design (Raspberry Pi vision + Arduino motor I/O), OpenCV classification, line-following, obstacle avoidance, and pickup actuation. *Indonesian Mobile Robot Contest (KRTMI) 2024.*
  `Python · OpenCV · Arduino · Raspberry Pi · C++`

---

### 🔬 Scientific CV, Web & Tools

- **[ai-plankton-case-study](https://github.com/felixyustian/ai-plankton-case-study)**
  Dense micro-object counting, extreme class-imbalance handling, and fine-grained taxonomic classification of microscopic plankton — full EDA → baseline → error-analysis notebook.
  `Python · PyTorch · OpenCV · Scikit-Learn · Jupyter Notebook`

- **[wc2026-prediction-dashboard](https://github.com/felixyustian/wc2026-prediction-dashboard)** — 🌐 [Live](https://smart-worldcup-2026-predictor.vercel.app/)
  World Cup 2026 prediction engine: Elo + Poisson match model and client-side Monte-Carlo tournament simulation conditioned on real results, with a live knockout bracket fed by a keyless ESPN pipeline on a GitHub Actions schedule.
  `JavaScript · Monte Carlo · Vercel Functions · GitHub Actions`

- **[semarang-smart-city](https://github.com/felixyustian/semarang-smart-city)** — 🌐 [Live](https://semarangsmartcity.vercel.app/)
  Interactive single-file microsite for a ten-year smart-city master plan for Kota Semarang (2026–2035): governance, transport, flood and subsidence resilience, and public services across four phases with go / no-go gates.
  `HTML · CSS · JavaScript`

- **[django_quizapp](https://github.com/felixyustian/django_quizapp)**
  AI-powered quiz platform: Django MVC, contextual AI question generation, and real-time scoring.
  `Python · Django · JavaScript · HTML/CSS`

- **[felixyustian.github.io](https://github.com/felixyustian/felixyustian.github.io)**
  This profile on GitHub Pages, with a [live projects page](https://felixyustian.github.io/projects.html) fed by the GitHub API. Personal website: [felixsetiono.my.id](https://felixsetiono.my.id).

---

## 💼 Work Experience

### Senior Computer Vision Engineer & CV Team Lead
**Sigmawave AI Pte. Ltd. — Singapore** | *September 2026 – Present* | Remote / Hybrid

- Rebuilt and optimized a multi-camera person re-identification and cross-camera tracking system for edge deployment; lead the CV engineering team across model design, optimization, and production MLOps.
- Optimize deep-learning models for inference efficiency, latency, throughput, and hardware constraints on edge targets.
- Own task allocation, technical standards, and code reviews for the CV team; coordinate cross-functional workflows to hit product milestones.
- Establish experiment tracking, model versioning, and CI/CD pipelines for production model reliability in live environments.
- Define operational boundaries, confidence thresholds, and fallback behaviours for safe real-world deployment; oversee data-curation pipelines and applied R&D from PoC to production.

### AI Architect & Technical Lead
**V-TEKI** | *July 2026 – Present* | Jakarta, Indonesia (Remote)

- Set technical direction for enterprise AI delivery across LLM, agentic, and computer-vision workstreams — defining target architectures and reviewing designs and source code to production standard.
- Drive MLOps and deployment standards (experiment tracking, model versioning, CI/CD) and lead architecture decisions from proposal through client delivery.
- Establish best practices for AI engineering, system deployment, and MLOps; contribute to reusable AI frameworks, technical standards, and documentation.
- Mentor AI engineers and cross-functional teams; support delivery through technical proposal reviews, solution architecture design, and client discussions.

### Technical Mentor - Garuda Hacks 7.0
**Garuda Hacks - Garuda Hacks 7.0** | *July 2026* | Remote, Indonesia

- Provided technical guidance on system design, AI/ML integration, and agentic-workflow deployment to hackathon teams under rapid-prototyping time constraints.
- Advised on technical viability and early-stage architecture to help teams avoid structural technical debt.

### Facilitator - Google Skills Arcade 2026
**Dicoding Indonesia — Google Skills Arcade 2026** | *July 2026 – Present* | Remote, Indonesia

- Mentor national tech talent through Google Cloud hands-on labs on cloud architecture and infrastructure.
- Review updated cloud-infrastructure modules and translate them into practical technical guidance for mentees.
- Facilitate troubleshooting discussions and community networking within the Google Skills developer ecosystem.

### Google Prompt Engineering Trainer (VILT)
**Smartbridge International — Last Mile Indonesia Program** | *February 2026 – July 2026* | Remote

Lead Trainer for a 30-hour Virtual Instructor-Led Training (VILT) on advanced Prompt Engineering, delivered to developer cohorts across Indonesia's national 'Last Mile' digital upskilling program.

- Taught advanced AI reasoning frameworks: Chain-of-Thought (CoT), Tree-of-Thought (ToT), and Self-Consistency to optimize LLM output accuracy and reliability
- Educated participants on Prompt Architecture (RTCFC Framework) and deep-level model parameters (Temperature, Top-P, Top-K) for precise model behavior control
- Guided developers through Vibe Coding, intent-based problem solving, and agentic workflows using the Gemini ecosystem and Google Cloud
- Covered cost-accuracy trade-offs, tokenization mechanics, and red-teaming / adversarial prompting for enterprise-grade AI safety

### AI Image Data Contributor (Freelance)
**SoftAge Information Technology Limited** | *February 2026 – July 2026* | Remote

- Contributed to the SrotPix Image Data Collection Project — generated high-quality structured visual datasets for AI model training across specialized categories including Character Consistency, Nested Objects, and Object Interactions
- Ensured strict adherence to dataset QA guidelines: metadata consistency, lighting continuity, and precise spatial framing
- Gained hands-on experience in the foundational data-gathering phase of the Generative AI model development lifecycle

### Freelance Software & AI Engineer
**PostWork AI** | *October 2025 – July 2026* | Remote

- Developed, fine-tuned, and evaluated AI models prior to production deployment
- Built bespoke software solutions for client-specific automation and ML integration needs across diverse remote engagements

### Lead AI Researcher & Robotics Technical Lead
**Soegijapranata Catholic University, Semarang** | *May 2014 – Present* | Onsite

- Architect and deploy real-time computer vision pipelines (PyTorch, OpenCV, C++) onto constrained edge hardware — Raspberry Pi and Pixhawk — for autonomous UAV, AUV, and AGV platforms competing in national robotics contests (KRTI, KRBAI, KRTMI)
- Founded and lead the university robotics team across 10+ national competitions; **1st Place** AEROCREATION 2017 (ITB) and **5th nationally**, Indonesian Aerial Robotics Contest 2016 (1 of 5 teams to finish the full autonomous mission)
- Built an end-to-end ML pipeline for human emotional-state estimation via multisensory data fusion (HRV + motion); published in Jurnal Elektrika USM (Oct 2024)
- Supervise 10+ concurrent student research teams annually across the full hardware-to-deployment lifecycle; introduced Git-based version control and structured ML evaluation workflows across the lab
- Designed and delivered undergraduate courses in Embedded Systems, AI/ML Applications, and Autonomous Robotics to cohorts of 20–40 students per semester
- **Research metrics:** Google Scholar — 40 citations, h-index 4 | Scopus ID 5326490710 — 18 citations, h-index 3

### Head of Electrical Energy Conversion Laboratory
**Soegijapranata Catholic University** | *August 2014 – March 2018* | Onsite

- Managed laboratory operations, equipment, and safety protocols supporting 15+ concurrent faculty and student research projects in power electronics and energy conversion

### Research Assistant — Electrical Energy Conversion Laboratory
**Bandung Institute of Technology (ITB)** | *January 2010 – August 2012* | Onsite

- Graduate research on Maximum Power Point Tracking (MPPT) algorithms for photovoltaic systems
- Results published at ICEEI 2011 (Bandung Institute of Technology) and Industrial Electronics Seminar 2009

### Teaching Assistant — Electrical Energy Conversion Laboratory
**Soegijapranata Catholic University** | *August – December 2009* | Onsite

### Engineering Intern — Painting Steel Section
**PT Astra Honda Motor, Jakarta** | *August 2007* | Onsite

---

## 🎓 Education

### Professional Engineer (Ir.)
**Institut Teknologi Indonesia, Serpong** | *April 2024 – October 2024* | GPA: 4.00 / 4.00

### Master of Electrical Engineering
**Bandung Institute of Technology (ITB), Bandung** | *January 2010 – August 2012* | GPA: 3.17 / 4.00
- Exchange Student: INP-ENSEEIHT, Toulouse, France (September 2012 – October 2013)

### Bachelor of Electrical Engineering
**Soegijapranata Catholic University, Semarang** | *August 2005 – December 2009*
- **Best Graduate Student Award** — December 2009 Commencement

---

## 📜 Certifications

- **Google Cloud Generative AI Leader** — Google Cloud · [Verify](https://coursera.org/share/7802f5349976ff81e1a92c4f5892996c)
- **McKinsey.org Forward Program** — McKinsey & Company · [Verify](https://www.credly.com/badges/56bc708e-79b0-4a68-857b-262c5b624e2c/public_url)
- **Claude 101** — Anthropic Academy · [Verify](https://verify.skilljar.com/c/2t82nnenecjm)
- **Claude Code 101** — Anthropic Academy · [Verify](https://verify.skilljar.com/c/dv7237fu926y)
- **Claude Platform 101** — Anthropic Academy · [Verify](https://verify.skilljar.com/c/2mvqufvr9tdy)
- **Google AI Essentials** — Google · [Verify](https://www.credly.com/badges/0d7b4ef7-97b5-40a7-b104-f2daf6e8400b/public_url)
- **Basics of Google Cloud Compute (Skill Badge)** — Google Cloud · [Verify](https://www.credly.com/badges/a46a52ff-e1dc-422d-a92d-9d65f853cafd/public_url)
- **Career Management Essentials (SkillsBuild)** — IBM · [Verify](https://www.credly.com/badges/329633b2-77e9-470a-b067-8698e6bfc355/public_url)
- **Business Chinese (BCT 1 / 商务汉语)** — Murz x Cetta Mandarin, Batch 8 · July 2026

---

## 🏆 Achievements & Awards

- 🛢️ **IOC Forum & Hackathon AI/ML Hulu Migas 2026** (SKK Migas) — Participant, University Category, Team Nusantara Edge Vision: air-gapped Edge-AI HSE compliance for offshore rigs (YOLOv11 INT8 / TensorRT PPE detection across 15 RTSP streams on Jetson Orin AGX, ArcFace crew recognition)
- 🤖 **OpenClaw Agenthon 2026** (RISTEK x Build Club, Devpost) — Participant, Team NexaPaw / LapakPintar — Best Payment Use Case Track (DOKU API integration)
- 🔬 **BRIN AIDeaNation 2026** (Indonesian National Research & Innovation Agency) — Finalist / Top 80
- 🔬 **BRIN AIDeaNation 2025** (Indonesian National Research & Innovation Agency) — Finalist / Top 80
- 🏅 **Coding & Algorithm Tournament 2026** (catournament.org) — Semi-Finalist
- 🌏 **Pan-SEA AI Developer Challenge 2025** (Angel Hacks & AI Singapore) — Semi-Finalist / Top 100
- 🎖️ **Google Student Ambassador 2025** (Google Indonesia) — Mentor for university delegates
- 🥇 **AEROCREATION 2017 National Essay Competition** (Bandung Institute of Technology) — 1st Place Nationally
- 🏆 **Indonesian Aerial Robotics Contest 2016** — 5th Place Nationally (1 of only 5 teams to complete the full autonomous mission)
- ⚖️ **Judge** — Indonesian Humanoid Robot Soccer Contest, National Robotics Contest 2015, Muhammadiyah University Yogyakarta
- 🎓 **Best Graduate Student Award** — Soegijapranata Catholic University, December 2009
- ✈️ **Exchange Fellowship** — INP-ENSEEIHT, Toulouse, France (International Master of EE & Embedded Systems, 2012–2013)
- 🌏 **AOTULE 2012 Participant** — Asia-Oceania Top Universities League on Engineering, Bandung Institute of Technology
- 🎓 **Maju Bareng AI Bootcamp 2025** (Hactiv8 Indonesia, Google & AVPN) — Participant
- 📚 **Pijak 2025** (IBM Skills Build & Dicoding Indonesia) — Participant
- 💻 **Microsoft Elevate 2025** (Microsoft Indonesia & Dicoding Indonesia) — Participant
- 🎧 **IDCamp 2025** (Indosat & Dicoding Indonesia) — Participant
- 🏦 **DBS Coding Camp 2026** (DBS Foundation & Dicoding Indonesia) — Participant
- ☁️ **AWS Back-End Academy 2025** (AWS & Dicoding Indonesia) — Participant
- 🌩️ **JuaraGCP Season 12 — 2026** (Google Developer Group Indonesia) — Participant

---

## 📚 Selected Publications

| Year | Title | Venue |
|------|-------|-------|
| 2025 | Advanced Line Follower Robot with Ultrasonic Sensor for Dynamic Obstacle Avoidance and Smartphone-based Control (2nd Author) | Jurnal Elektrika USM, Vol. 17 No. 1 · [DOI](https://doi.org/10.26623/elektrika.v17i1.11813) |
| 2024 | A Novel Approach of Human Emotional State Estimation System via ML-based Multisensory Datasets Fusion Methods (1st Author) | Jurnal Elektrika USM, Vol. 16 No. 2 · [DOI](https://doi.org/10.26623/elektrika.v16i2.10624) |
| 2021 | A Novel Room Categorization Approach to Semantic Localization for Domestic Service Robots | 21st ICCAS, Jeju, South Korea |
| 2020 | Human Emotional State Estimation Evaluation using Heart Rate Variability and Activity Data | 4th IEEE IRC 2020 |
| 2016 | Designing and Implementation of Autonomous Hexarotor / Quadrotor as UAV (2 papers) | ICITEE & ICITACEE 2016 |
| 2014 | Boost Inverter Control (PI + Hysteresis) · Solar PV Battery Charger (dsPIC30F4012) | ICITACEE 2014 |
| 2011 | Maximum Power Point Tracker as Regulated Voltage Supply using Ripple Correlation Control | ICEEI 2011, ITB |

🎓 **Google Scholar:** [scholar.google.com/citations?user=W_NZMf4AAAAJ](https://scholar.google.com/citations?user=W_NZMf4AAAAJ&hl=en) | 40 citations · h-index 4
📖 **Scopus ID:** [5326490710](https://www.scopus.com/authid/detail.uri?authorId=5326490710) | 18 citations · h-index 3 · **ORCID:** [orcid.org/0000-0002-5240-0466](https://orcid.org/0000-0002-5240-0466)

---

## 🤝 Professional Memberships

- 🔌 **IEEE** (Institute of Electrical and Electronics Engineers) — Regular Member
- 🏗️ **PII** (The Institution of Engineers Indonesia) — Regular Member
- 🧠 **KORIKA** (Collaborative Research and Industrial Innovation in Artificial Intelligence) — Regular Member
- 🚁 **APDI** (Indonesian Drone Pilot Association) — Regular Member
- 🐍 **Python Software Foundation (PSF)** — Member
- 🐍 **Python Indonesian Society** — Member

---

## 💡 What Drives Me

I'm passionate about **bridging theory and implementation** — taking ideas from algorithm design all the way to hardware realization. I thrive on solving complex bottlenecks in Edge environments, ensuring that AI models don't just perform well on paper, but execute flawlessly under strict latency and memory constraints in the real world.

Currently building **intelligent autonomous systems** that eliminate operational friction for real people — from multi-camera vision systems running at the edge, to governed LLM pipelines where the model structures language but deterministic logic makes the call.

---

📫 **Connect with me**

- 🌐 Website → [felixsetiono.my.id](https://felixsetiono.my.id)
- 💼 LinkedIn → [linkedin.com/in/felixsetiono](https://linkedin.com/in/felixsetiono)
- 📧 Email → [felixyustian@gmail.com](mailto:felixyustian@gmail.com)
- 🗂️ GitHub Pages → [felixyustian.github.io](https://felixyustian.github.io)
