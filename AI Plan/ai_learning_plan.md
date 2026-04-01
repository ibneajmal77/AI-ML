---
name: Muhammad Awais – Complete AI Architect Learning Plan
description: Full curriculum for AI Architect from scratch. Covers every layer: math, ML, deep learning, LLMs, GenAI, RAG, agents, MLOps, safety, and architecture. Read this at the start of every session.
type: project
---

# AI Architect — Complete Learning Plan
**Learner:** Muhammad Awais | Dubai, UAE | ibneajmal77@gmail.com
**Goal:** AI/ML Engineer → Senior AI Engineer → **AI Architect / Principal AI Architect**
**Method:** Learns directly from Claude. No videos. No lectures. Claude teaches interactively.
**Style:** Explain concept → Show code → Ask question → Confirm understanding → Move forward

---

## HOW TO USE THIS FILE (Instructions for every Claude session)

1. Read this entire file at the start of each session
2. Find the **CURRENT STATUS** section — it tells you exactly where Awais is
3. Continue from the **NEXT LESSON** marked below
4. Teach interactively: explain → example → question → confirm → next
5. After each lesson is completed, mentally note what was covered
6. When Awais says "save progress" or session ends, update this file:
   - Mark completed lessons with ✅
   - Update CURRENT STATUS section
   - Update NEXT LESSON
   - Add notes to SESSION LOG

---

## CURRENT STATUS

**Current Stage:** Stage 0 — Not Started
**Current Topic:** Not started — Begin with Stage 0, Lesson 0.1
**Last Session:** No sessions yet
**Next Lesson:** Stage 0 → Lesson 0.1: Dev environment setup for AI
**Confidence Level:** N/A

---

## LEARNER PROFILE

- 8 years Full Stack Engineering (Senior level)
- Strong: Python, Azure, Docker, Kubernetes, Kafka, Redis, PostgreSQL, Microservices
- Certified: Azure Solutions Architect Expert (AZ-305)
- MSc Software Engineering
- Location: Dubai, UAE — targeting UAE AI job market
- **Despite experience: treat every concept as if he has never seen it before**
- **When teaching, use his background as analogies ONLY — do not skip topics**
- Kafka knowledge → use for streaming AI pipelines analogies
- Kubernetes knowledge → use for model deployment analogies
- Microservices knowledge → use for AI system design analogies
- Azure knowledge → use for Azure AI services analogies

---

## COMPLETE CURRICULUM

---

### STAGE 0 — PREREQUISITES: DATA STACK, MATH & DEVELOPER SETUP
> Goal: Have the mathematical and tooling foundation every subsequent stage builds on.
> Without this, you cannot truly understand what ML models are doing.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 0.1 | Dev environment setup: Python, Jupyter, VS Code, Git for AI projects | ⬜ | |
| 0.2 | NumPy: arrays, shapes, broadcasting, vectorized operations | ⬜ | |
| 0.3 | Pandas: DataFrames, filtering, groupby, merge, pivot — the daily tool | ⬜ | |
| 0.4 | Data visualization: matplotlib, seaborn, plotly — seeing your data | ⬜ | |
| 0.5 | Exploratory Data Analysis (EDA): how to understand a dataset before modeling | ⬜ | |
| 0.6 | Statistics for ML: distributions, mean/variance/std, correlation, Central Limit Theorem | ⬜ | |
| 0.7 | Probability and Bayes theorem: the math behind ML decisions | ⬜ | |
| 0.8 | Linear algebra for ML: vectors, matrices, dot products, eigenvalues — intuition first | ⬜ | |
| 0.9 | Calculus for ML: derivatives, chain rule, gradients — intuition only, no proofs | ⬜ | |
| 0.10 | Stage 0 Project: Full EDA report on a real Kaggle dataset — visualize, summarize, find patterns | ⬜ | |
| **Paper** | "A Few Useful Things to Know About Machine Learning" — Domingos 2012 | ⬜ | |
| **Write** | Blog post: "What I learned doing my first EDA as a software engineer" | ⬜ | |

---

### STAGE 1 — FOUNDATIONS OF MACHINE LEARNING
> Goal: Understand what ML is, how it learns, and be able to build and evaluate any classical model.
> This stage covers ALL types of ML — supervised, unsupervised, and the algorithms inside each.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 1.1 | What is Machine Learning — the real explanation, not the marketing version | ⬜ | |
| 1.2 | Types of ML: Supervised, Unsupervised, Reinforcement, Self-supervised — when each applies | ⬜ | |
| 1.3 | How a model "learns": loss functions, gradients, and optimization — the full loop | ⬜ | |
| 1.4 | Linear Regression: your first ML model, built from scratch in NumPy | ⬜ | |
| 1.5 | Classification: Logistic Regression — from regression to decisions | ⬜ | |
| 1.6 | K-Nearest Neighbors (KNN): distance-based learning, no training required | ⬜ | |
| 1.7 | Naive Bayes: probabilistic classification — the math made simple | ⬜ | |
| 1.8 | Support Vector Machines (SVM): maximum margin classification | ⬜ | |
| 1.9 | Decision Trees: splitting data by information gain | ⬜ | |
| 1.10 | Random Forests: ensemble learning — many weak models, one strong one | ⬜ | |
| 1.11 | Gradient Boosting: XGBoost and LightGBM — the industry workhorse | ⬜ | |
| 1.12 | Unsupervised Learning: K-Means clustering — grouping without labels | ⬜ | |
| 1.13 | DBSCAN and hierarchical clustering: finding clusters of any shape | ⬜ | |
| 1.14 | Dimensionality Reduction: PCA, t-SNE, UMAP — seeing high-dimensional data | ⬜ | |
| 1.15 | Overfitting, Underfitting, Bias-Variance tradeoff — the central tension in ML | ⬜ | |
| 1.16 | Cross-validation: k-fold, stratified k-fold, leave-one-out | ⬜ | |
| 1.17 | Hyperparameter tuning: Grid Search, Random Search, Bayesian Optimization | ⬜ | |
| 1.18 | Evaluation metrics: Accuracy, Precision, Recall, F1, AUC-ROC, confusion matrix | ⬜ | |
| 1.19 | Data preprocessing: scaling, encoding, null handling, imbalanced data (SMOTE, class weights) | ⬜ | |
| 1.20 | Feature Engineering: creating better inputs from raw data | ⬜ | |
| 1.21 | Full ML pipeline with scikit-learn: from raw data to evaluated model in one script | ⬜ | |
| 1.22 | Stage 1 Project: End-to-end classifier (scikit-learn + FastAPI + Azure deployment + Kaggle entry) | ⬜ | |
| **Paper** | "XGBoost: A Scalable Tree Boosting System" — Chen & Guestrin 2016 | ⬜ | |
| **Write** | Blog post: "How I built my first ML model as a backend engineer" | ⬜ | |

---

### STAGE 2 — DEEP LEARNING & NEURAL NETWORKS
> Goal: Understand how neural networks work at every level and build/train them with PyTorch.
> This is the foundation for everything in Stages 3–6.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 2.1 | What is a neural network — no magic, just math and matrix multiplication | ⬜ | |
| 2.2 | Neurons, layers, activations: ReLU, Sigmoid, Softmax, GELU — what each does | ⬜ | |
| 2.3 | Loss functions: MSE, CrossEntropy, BCE — what they actually measure | ⬜ | |
| 2.4 | Backpropagation: how the network learns by walking back through the chain rule | ⬜ | |
| 2.5 | Optimizers: SGD, Adam, AdamW, RMSProp — which to use and why | ⬜ | |
| 2.6 | Learning rate schedulers: StepLR, CosineAnnealing, ReduceLROnPlateau | ⬜ | |
| 2.7 | GPU/CUDA setup: why training on GPU matters and how to use it in PyTorch | ⬜ | |
| 2.8 | PyTorch basics: tensors, autograd, device management (CPU/GPU) | ⬜ | |
| 2.9 | Building your first neural network in PyTorch (nn.Module, forward pass) | ⬜ | |
| 2.10 | The training loop — every line explained: forward, loss, backward, step | ⬜ | |
| 2.11 | Regularization: Dropout, Batch Normalization, Layer Normalization, Weight Decay | ⬜ | |
| 2.12 | Transfer Learning: using pre-trained weights and fine-tuning them | ⬜ | |
| 2.13 | Convolutional Neural Networks (CNNs): how computers see images | ⬜ | |
| 2.14 | Autoencoders and Variational Autoencoders (VAE): learning compressed representations | ⬜ | |
| 2.15 | Recurrent Networks (RNN, LSTM, GRU): processing sequences and time series | ⬜ | |
| 2.16 | Sequence-to-Sequence and Encoder-Decoder architecture: how translation works | ⬜ | |
| 2.17 | The Attention Mechanism: the single idea that changed everything in AI | ⬜ | |
| 2.18 | Transformers: the architecture explained piece by piece (read the paper alongside this) | ⬜ | |
| 2.19 | Hugging Face: models, pipelines, tokenizers, datasets — the AI ecosystem | ⬜ | |
| 2.20 | Stage 2 Project: Train and deploy a text classifier (PyTorch + Hugging Face + FastAPI) | ⬜ | |
| **Paper** | "Attention Is All You Need" — Vaswani et al. 2017 (THE foundational paper) | ⬜ | |
| **Write** | Blog post: "Transformers explained without the math PhD" | ⬜ | |

---

### STAGE 3 — LARGE LANGUAGE MODELS (LLMs)
> Goal: Deeply understand LLMs — how they work, how to use them, evaluate them, secure them, fine-tune them.
> After this stage you can build LLM-powered applications professionally.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 3.1 | What is an LLM — how GPT/Claude/Gemini actually work under the hood | ⬜ | |
| 3.2 | Tokenization: how text becomes numbers (BPE, WordPiece, SentencePiece) | ⬜ | |
| 3.3 | Pretraining, fine-tuning, RLHF: the three phases of building an LLM | ⬜ | |
| 3.4 | Context windows, temperature, top-p, top-k, repetition penalty — every parameter explained | ⬜ | |
| 3.5 | LLM evaluation: BLEU, ROUGE, perplexity, benchmarks (MMLU, HumanEval, HellaSwag) | ⬜ | |
| 3.6 | Model selection framework: when to use GPT-4o vs Claude vs Gemini vs open-source | ⬜ | |
| 3.7 | Calling LLM APIs: OpenAI, Azure OpenAI, Anthropic, Google — SDK patterns | ⬜ | |
| 3.8 | Prompt Engineering: zero-shot, few-shot, chain-of-thought, self-consistency, meta-prompting | ⬜ | |
| 3.9 | System prompts, roles, and conversation structure | ⬜ | |
| 3.10 | Tool calling / Function calling: LLMs that invoke APIs and return structured results | ⬜ | |
| 3.11 | Structured outputs: making LLMs return valid JSON reliably (Pydantic + instructor) | ⬜ | |
| 3.12 | Streaming responses: real-time token output with server-sent events | ⬜ | |
| 3.13 | Multimodal LLMs: text + image + audio (GPT-4V, Claude Vision, Gemini) | ⬜ | |
| 3.14 | LLM security: prompt injection, jailbreaking, indirect injection — attack and defense | ⬜ | |
| 3.15 | Fine-tuning LLMs: when to fine-tune vs prompt engineer vs RAG — decision framework | ⬜ | |
| 3.16 | LoRA and QLoRA: efficient fine-tuning without full GPU clusters | ⬜ | |
| 3.17 | RLHF, DPO, Constitutional AI: how models are aligned to human preferences | ⬜ | |
| 3.18 | Open-source LLMs: LLaMA 3, Mistral, Phi-3, Falcon — run locally with Ollama | ⬜ | |
| 3.19 | LLM cost optimization: context caching, prompt caching, model routing, batching | ⬜ | |
| 3.20 | Stage 3 Project: Domain-specific LLM assistant (Azure OpenAI + FastAPI + streaming + deployed) | ⬜ | |
| **Paper** | "Language Models are Few-Shot Learners" (GPT-3) — Brown et al. 2020 | ⬜ | |
| **Write** | Blog post: "How to choose the right LLM for your use case" | ⬜ | |

---

### STAGE 4 — GENERATIVE AI (BEYOND LLMs)
> Goal: Understand the full generative AI landscape — images, audio, video, multimodal, Arabic AI.
> An AI Architect must know what each modality can and cannot do and when to use it.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 4.1 | The GenAI landscape: LLMs, diffusion models, GANs, VAEs — where each fits | ⬜ | |
| 4.2 | Diffusion models: how Stable Diffusion and DALL-E actually work step by step | ⬜ | |
| 4.3 | Working with image generation APIs: DALL-E 3, Stability AI, Azure AI Vision | ⬜ | |
| 4.4 | GANs (Generative Adversarial Networks): generator vs discriminator, training instability | ⬜ | |
| 4.5 | Text-to-speech and speech-to-text: Whisper (ASR), ElevenLabs, Azure Speech Service | ⬜ | |
| 4.6 | Video generation: Sora, Runway, Kling — capabilities, limitations, and API use | ⬜ | |
| 4.7 | Multimodal generation pipelines: combining text + image + audio in one system | ⬜ | |
| 4.8 | CLIP and multimodal embeddings: connecting images and text in vector space | ⬜ | |
| 4.9 | Arabic NLP fundamentals: morphology, diacritics, right-to-left, challenges vs English | ⬜ | |
| 4.10 | Arabic AI models: AraBERT, CAMeL, AraGPT2, Jais (G42's LLM) — UAE differentiator | ⬜ | |
| 4.11 | Arabic NLP in production: sentiment analysis, NER, summarization in Arabic | ⬜ | |
| 4.12 | Stage 4 Project: Multimodal AI pipeline (Arabic text + image + audio processing) | ⬜ | |
| **Paper** | "Jais and Jais-chat: Arabic-Centric Foundation Language Model" — G42/MBZUAI 2023 | ⬜ | |
| **Write** | Blog post: "Building AI for Arabic — what every UAE AI engineer must know" | ⬜ | |

---

### STAGE 5 — RAG (RETRIEVAL-AUGMENTED GENERATION)
> Goal: Build production-grade RAG systems from scratch, evaluate them rigorously, and know every failure mode.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 5.1 | What is RAG and why it exists — the problem LLMs have that RAG solves | ⬜ | |
| 5.2 | Embeddings: turning meaning into numbers — semantic vs lexical similarity | ⬜ | |
| 5.3 | Embedding models: OpenAI text-embedding-3, BGE, sentence-transformers, multilingual | ⬜ | |
| 5.4 | Vector similarity search: cosine similarity, dot product, L2 distance | ⬜ | |
| 5.5 | ANN algorithms: HNSW, IVF, PQ — how vector DBs search fast at scale | ⬜ | |
| 5.6 | pgvector: turning PostgreSQL into a vector database (you already know Postgres!) | ⬜ | |
| 5.7 | Choosing a vector DB: Qdrant, Pinecone, Weaviate, ChromaDB — trade-offs and when | ⬜ | |
| 5.8 | Document loading: PDFs, Word, HTML, databases — handling every real-world format | ⬜ | |
| 5.9 | Chunking strategies: fixed-size, recursive, semantic — trade-offs | ⬜ | |
| 5.10 | The full RAG pipeline: ingest → chunk → embed → store → retrieve → generate | ⬜ | |
| 5.11 | Hybrid search: combining dense vector search + keyword search (BM25) | ⬜ | |
| 5.12 | Re-ranking: improving retrieval quality (Cohere Rerank, cross-encoders) | ⬜ | |
| 5.13 | RAG evaluation: faithfulness, relevancy, context recall — RAGAS framework | ⬜ | |
| 5.14 | Advanced RAG: HyDE, multi-query retrieval, parent-child chunking, RAPTOR | ⬜ | |
| 5.15 | GraphRAG: combining knowledge graphs with RAG (Microsoft's approach) | ⬜ | |
| 5.16 | Multimodal RAG: handling images, tables, and diagrams inside documents | ⬜ | |
| 5.17 | RAG failure modes: silent retrieval failure, context stuffing, hallucination from context | ⬜ | |
| 5.18 | Agentic RAG: RAG inside an agent decision loop | ⬜ | |
| 5.19 | Stage 5 Project: Production RAG chatbot (pgvector + FastAPI + Redis + RAGAS evaluation) | ⬜ | |
| **Paper** | "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks" — Lewis et al. 2020 | ⬜ | |
| **Write** | Blog post: "How to evaluate your RAG system — beyond vibes testing" | ⬜ | |

---

### STAGE 6 — AI AGENTS & MULTI-AGENT SYSTEMS
> Goal: Build autonomous AI agents that reason, use tools, maintain memory, and collaborate.
> Agents are the fastest-growing area of AI in 2024–2025.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 6.1 | What is an AI agent — definition, components, the agent loop | ⬜ | |
| 6.2 | The ReAct pattern: Reasoning + Acting — think, act, observe, repeat | ⬜ | |
| 6.3 | Tools: giving agents the ability to call functions, APIs, databases, search | ⬜ | |
| 6.4 | Agent memory: short-term (context window), long-term (vector store), episodic | ⬜ | |
| 6.5 | LangChain: chains, tools, agents — core concepts and when to use them | ⬜ | |
| 6.6 | LangGraph: building stateful multi-step agents with graph-based control flow | ⬜ | |
| 6.7 | Agent state machines: nodes, edges, conditional routing, cycles | ⬜ | |
| 6.8 | Multi-agent systems: orchestrator + worker pattern | ⬜ | |
| 6.9 | Agent communication patterns: sequential, parallel, hierarchical, swarm | ⬜ | |
| 6.10 | CrewAI: role-based multi-agent frameworks with personas | ⬜ | |
| 6.11 | AutoGen (Microsoft): enterprise multi-agent conversation patterns | ⬜ | |
| 6.12 | Human-in-the-loop: when agents must pause and request human approval | ⬜ | |
| 6.13 | Agent cost management: token budgets, loop limits, cost alerts — agents can be expensive | ⬜ | |
| 6.14 | Agent security: prompt injection in tool results, sandboxing, output validation | ⬜ | |
| 6.15 | MCP (Model Context Protocol): Anthropic's standard for tool integration | ⬜ | |
| 6.16 | Agent evaluation: how to measure if an agent is actually working correctly | ⬜ | |
| 6.17 | Agent observability: LangSmith, LangFuse — tracing every step of the agent | ⬜ | |
| 6.18 | Guardrails: keeping agents safe, on-task, and within budget | ⬜ | |
| 6.19 | Production agents: error handling, retries, fallbacks, timeouts, circuit breakers | ⬜ | |
| 6.20 | Stage 6 Project: Multi-agent research and report generation system (full production) | ⬜ | |
| **Paper** | "ReAct: Synergizing Reasoning and Acting in Language Models" — Yao et al. 2022 | ⬜ | |
| **Write** | Architecture doc: "Designing a production multi-agent system — decisions and trade-offs" | ⬜ | |

---

### STAGE 7 — MLOps & LLMOps
> Goal: Deploy, version, monitor, test, and maintain ML and LLM systems in production at scale.
> This is what separates engineers who build demos from engineers who build systems.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 7.1 | What is MLOps and why it matters — the full picture beyond "just deploying a model" | ⬜ | |
| 7.2 | Experiment tracking with MLflow: runs, parameters, metrics, artifacts | ⬜ | |
| 7.3 | Experiment tracking with Weights & Biases (W&B): sweeps, reports, team features | ⬜ | |
| 7.4 | Data versioning with DVC: tracking datasets and pipelines like code | ⬜ | |
| 7.5 | Model registry: versioning, staging (dev/staging/prod), approval workflows | ⬜ | |
| 7.6 | Feature stores: what they solve, Feast — real-time + offline feature serving | ⬜ | |
| 7.7 | Pipeline orchestration: Apache Airflow for ML workflow scheduling | ⬜ | |
| 7.8 | Data quality testing: Great Expectations — never trust your data | ⬜ | |
| 7.9 | Testing ML systems: data tests, model behavior tests, integration tests | ⬜ | |
| 7.10 | Model serving: FastAPI (manual), BentoML, TorchServe — options and trade-offs | ⬜ | |
| 7.11 | Containerizing ML models: Docker for AI workloads — GPU-enabled containers | ⬜ | |
| 7.12 | Deploying on Kubernetes: KServe and Seldon Core for production model serving | ⬜ | |
| 7.13 | ML CI/CD pipelines: automating training and deployment with GitHub Actions + MLflow | ⬜ | |
| 7.14 | Data drift detection: Evidently AI — knowing when your model starts to break | ⬜ | |
| 7.15 | Model monitoring: performance dashboards, latency tracking, cost dashboards | ⬜ | |
| 7.16 | LLMOps: prompt versioning, LLM cost tracking, token monitoring, eval pipelines | ⬜ | |
| 7.17 | Distributed training: DDP, DeepSpeed, FSDP, Ray Train — when you need scale | ⬜ | |
| 7.18 | Azure ML and Azure AI Foundry: full managed MLOps on Azure (your AZ-305 applies) | ⬜ | |
| 7.19 | A/B testing models: shadow deployment, canary releases, champion/challenger patterns | ⬜ | |
| 7.20 | Infrastructure as Code for AI: Terraform for GPU infrastructure and AI services | ⬜ | |
| 7.21 | Stage 7 Project: Full MLOps pipeline (W&B + MLflow + Evidently + K8s + CI/CD) | ⬜ | |
| **Paper** | "Hidden Technical Debt in Machine Learning Systems" — Sculley et al. 2015 (NIPS) | ⬜ | |
| **Write** | Architecture doc: "MLOps blueprint for a production AI system on Azure" | ⬜ | |

---

### STAGE 8 — AI SAFETY, ETHICS & GOVERNANCE
> Goal: Build AI systems that are safe, fair, explainable, and compliant with law and policy.
> As an AI Architect, you own governance decisions — this stage gives you the knowledge to own them.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 8.1 | AI hallucinations: causes, types, measurement, and mitigation strategies | ⬜ | |
| 8.2 | Bias in ML models: types of bias, how to detect and mitigate them | ⬜ | |
| 8.3 | Fairness metrics: demographic parity, equalized odds, individual fairness | ⬜ | |
| 8.4 | Explainability: SHAP values and LIME — making black-box models interpretable | ⬜ | |
| 8.5 | Adversarial attacks: how models are fooled and how to make them robust | ⬜ | |
| 8.6 | LLM guardrails: input/output filtering with Llama Guard, NeMo Guardrails | ⬜ | |
| 8.7 | PII detection and data privacy in AI systems (masking, anonymization, synthetic data) | ⬜ | |
| 8.8 | Red-teaming AI: structured methodology for finding vulnerabilities | ⬜ | |
| 8.9 | GDPR and EU AI Act: what they require from AI systems you architect | ⬜ | |
| 8.10 | UAE AI governance: TDRA AI Policy, UAE National AI Strategy 2031, Smart Dubai | ⬜ | |
| 8.11 | AI risk assessment frameworks: NIST AI RMF, ISO 42001 | ⬜ | |
| 8.12 | Model cards and datasheets: documentation standards every AI system needs | ⬜ | |
| 8.13 | Responsible AI frameworks: Microsoft RAI, Google PAIR, Anthropic Acceptable Use | ⬜ | |
| 8.14 | AI incident response: what to do when your AI system fails or causes harm in production | ⬜ | |
| **Paper** | "Model Cards for Model Reporting" — Mitchell et al. 2019 | ⬜ | |
| **Write** | Architecture doc: "AI governance framework for a UAE enterprise AI system" | ⬜ | |

---

### STAGE 9 — ADVANCED SPECIALIZATIONS
> Goal: Go deep in the high-value areas that UAE enterprises and global AI teams need most.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 9.1 | Advanced LLM architectures: Mixture of Experts (MoE), sparse transformers, SSMs | ⬜ | |
| 9.2 | Reinforcement Learning fundamentals: MDPs, Q-learning, policy gradients, PPO | ⬜ | |
| 9.3 | Graph Neural Networks (GNN) and knowledge graphs in AI systems | ⬜ | |
| 9.4 | Edge AI: quantization, pruning, ONNX, TFLite — AI on constrained hardware | ⬜ | |
| 9.5 | Time-series forecasting: Prophet, NeuralProphet, TiDE, TFT — for FinTech and energy | ⬜ | |
| 9.6 | Recommendation systems: collaborative filtering, content-based, hybrid, two-tower models | ⬜ | |
| 9.7 | Speech and Voice AI: ASR (Whisper), TTS, speaker diarization, full voice pipelines | ⬜ | |
| 9.8 | AI for FinTech: fraud detection, credit scoring, AML, risk modeling | ⬜ | |
| 9.9 | Computer Vision for smart cities: YOLO, object tracking, surveillance AI — UAE context | ⬜ | |
| 9.10 | AI research literacy: how to read papers, follow arXiv, evaluate new model claims | ⬜ | |
| **Paper** | "Scaling Laws for Neural Language Models" — Kaplan et al. 2020 | ⬜ | |
| **Write** | Blog post: "AI specializations with the highest demand in the UAE market" | ⬜ | |

---

### STAGE 10 — AI ARCHITECTURE & SYSTEM DESIGN
> Goal: This is the architect stage. Design, document, and defend complete enterprise AI systems.
> Covers every decision an AI Architect must make: data, compute, integration, cost, governance, scale.

| # | Lesson | Status | Notes |
|---|--------|--------|-------|
| 10.1 | The AI Architect role: what it is, how it differs from AI Engineer, what you own | ⬜ | |
| 10.2 | AI system design methodology: requirements → constraints → trade-offs → architecture | ⬜ | |
| 10.3 | Data architecture for AI: data lakes, lakehouses, Delta Lake, Apache Iceberg | ⬜ | |
| 10.4 | Event-driven AI: Kafka + ML for real-time streaming inference (your Kafka knowledge applies!) | ⬜ | |
| 10.5 | AI microservices patterns: inference APIs, async processing, fan-out, circuit breakers | ⬜ | |
| 10.6 | Designing for scale: horizontal scaling of inference, model parallelism, load balancing | ⬜ | |
| 10.7 | AI cost modeling: TCO calculation, cost-per-inference, API vs self-hosted economics | ⬜ | |
| 10.8 | Build vs Buy vs Fine-tune: the decision framework every architect must master | ⬜ | |
| 10.9 | Technology evaluation: how to systematically score and choose AI tools, models, and vendors | ⬜ | |
| 10.10 | Azure-native AI architecture: AI Foundry, Azure ML, Cognitive Services, Azure OpenAI — patterns | ⬜ | |
| 10.11 | Architecture Decision Records (ADRs) for AI: structure, what to capture, how to present | ⬜ | |
| 10.12 | AI system case studies: how Netflix, Uber, LinkedIn, Spotify, and G42 design AI | ⬜ | |
| 10.13 | Presenting AI architecture: translating technical design for C-suite, boards, and product | ⬜ | |
| 10.14 | AI project scoping: estimating data requirements, compute, timeline, and risk | ⬜ | |
| 10.15 | CAPSTONE: Design a complete enterprise AI architecture (full document + diagrams + ADRs + cost model) | ⬜ | |
| **Paper** | "Designing Data-Intensive Applications" — Kleppmann (architecture chapters 1, 2, 11, 12) | ⬜ | |
| **Write** | Full architecture document: "Enterprise AI Architecture Proposal" (this is your portfolio centerpiece) | ⬜ | |

---

## PORTFOLIO PROJECTS

| # | Project | Stage | What It Demonstrates | Status |
|---|---------|-------|---------------------|--------|
| P0 | Full EDA report (Jupyter + Kaggle dataset) | After Stage 0 | Data fluency, visualization, storytelling | ⬜ |
| P1 | ML classifier (scikit-learn + FastAPI + Azure + Kaggle submission) | After Stage 1 | Classical ML, deployment, cloud | ⬜ |
| P2 | Deep learning text classifier (PyTorch + Hugging Face + deployed API) | After Stage 2 | Neural networks, fine-tuning, serving | ⬜ |
| P3 | Domain-specific LLM assistant (Azure OpenAI + FastAPI + streaming) | After Stage 3 | LLM integration, prompt design, production API | ⬜ |
| P4 | Multimodal GenAI pipeline (Arabic text + image + audio) | After Stage 4 | GenAI breadth, Arabic NLP (UAE differentiator) | ⬜ |
| P5 | Production RAG chatbot (pgvector + FastAPI + Redis + RAGAS evaluation) | After Stage 5 | Full RAG, evaluation, production-grade | ⬜ |
| P6 | Multi-agent system (LangGraph + tools + memory + LangFuse observability) | After Stage 6 | Agentic AI, multi-agent orchestration | ⬜ |
| P7 | Full MLOps pipeline (W&B + MLflow + Evidently + K8s + CI/CD) | After Stage 7 | End-to-end MLOps, production operations | ⬜ |
| P8 | Enterprise AI architecture document (full system design + diagrams + ADRs + cost model) | After Stage 10 | Architect-level thinking, documentation, design | ⬜ |

---

## PAPER READING TRACK
> One foundational paper per stage. An AI Architect must be able to read and discuss research.

| Stage | Paper | Status |
|-------|-------|--------|
| Stage 0 | "A Few Useful Things to Know About Machine Learning" — Domingos 2012 | ⬜ |
| Stage 1 | "XGBoost: A Scalable Tree Boosting System" — Chen & Guestrin 2016 | ⬜ |
| Stage 2 | "Attention Is All You Need" — Vaswani et al. 2017 | ⬜ |
| Stage 3 | "Language Models are Few-Shot Learners" (GPT-3) — Brown et al. 2020 | ⬜ |
| Stage 4 | "Jais and Jais-chat: Arabic-Centric Foundation LLM" — G42/MBZUAI 2023 | ⬜ |
| Stage 5 | "RAG for Knowledge-Intensive NLP Tasks" — Lewis et al. 2020 | ⬜ |
| Stage 6 | "ReAct: Synergizing Reasoning and Acting" — Yao et al. 2022 | ⬜ |
| Stage 7 | "Hidden Technical Debt in Machine Learning Systems" — Sculley et al. 2015 | ⬜ |
| Stage 8 | "Model Cards for Model Reporting" — Mitchell et al. 2019 | ⬜ |
| Stage 9 | "Scaling Laws for Neural Language Models" — Kaplan et al. 2020 | ⬜ |
| Stage 10 | "Designing Data-Intensive Applications" — Kleppmann (Ch. 1, 2, 11, 12) | ⬜ |

---

## TECHNICAL WRITING TRACK
> One blog post or architecture document per stage. Architects write. Writing builds credibility.
> Publish on LinkedIn Articles or Medium. Tag: #AIArchitect #UAE #GenerativeAI

| Stage | Writing Piece | Status |
|-------|--------------|--------|
| Stage 0 | "What I learned doing my first EDA as a software engineer" | ⬜ |
| Stage 1 | "How I built my first ML model as a backend engineer" | ⬜ |
| Stage 2 | "Transformers explained without the math PhD" | ⬜ |
| Stage 3 | "How to choose the right LLM for your use case" | ⬜ |
| Stage 4 | "Building AI for Arabic — what every UAE AI engineer must know" | ⬜ |
| Stage 5 | "How to evaluate your RAG system — beyond vibes testing" | ⬜ |
| Stage 6 | "Designing a production multi-agent system — decisions and trade-offs" | ⬜ |
| Stage 7 | "MLOps blueprint for a production AI system on Azure" | ⬜ |
| Stage 8 | "AI governance framework for a UAE enterprise AI system" | ⬜ |
| Stage 9 | "AI specializations with the highest demand in the UAE market" | ⬜ |
| Stage 10 | Full enterprise AI architecture proposal (portfolio centerpiece) | ⬜ |

---

## CERTIFICATIONS PLAN

| Cert | Provider | Priority | Timing | Notes |
|------|----------|----------|--------|-------|
| Azure AI-900: AI Fundamentals | Microsoft | Quick win | Before Stage 1 | Fast, builds vocabulary, easy with AZ-305 background |
| Hugging Face NLP Course | Hugging Face (free) | HIGH | After Stage 2 | Practical, free, well-respected |
| NVIDIA DLI: Fundamentals of Deep Learning | NVIDIA (free) | HIGH | After Stage 2 | GPU-focused, highly practical |
| AI-102: Azure AI Engineer Associate | Microsoft | HIGH | After Stage 3 | Builds on AZ-305, UAE market demand |
| AWS ML Specialty | AWS | Medium | After Stage 7 | Broadens cloud coverage |
| Google Professional ML Engineer | Google | Medium | After Stage 7 | Strong signal, covers MLOps well |
| Databricks ML Professional | Databricks | Medium | After Stage 7 | Data lakehouse + ML pipelines |
| Microsoft Azure AI Architect (when available) | Microsoft | HIGHEST | After Stage 10 | Directly aligned to goal |

---

## CAREER MILESTONES

| Milestone | After Stage | What You Can Do |
|-----------|------------|-----------------|
| GenAI Engineer (entry) | Stage 5 | Build LLM apps, RAG systems, basic agents — job-ready |
| AI Engineer (mid-senior) | Stage 7 | Full AI systems in production with MLOps — strong hire |
| Senior AI Engineer | Stage 8 | Safety, governance, ethics — trusted on critical systems |
| **AI Architect** | **Stage 10** | **Design enterprise AI systems, own technology decisions, lead teams** |

---

## REALISTIC TIMELINE
> Based on 1 focused lesson per day as a working professional in Dubai.
> Add buffer: review days, project weeks, certification study.

| Stage | Lessons | Estimated Weeks |
|-------|---------|-----------------|
| Stage 0 — Prerequisites | 10 | 2–3 weeks |
| Stage 1 — ML Foundations | 22 | 5–6 weeks |
| Stage 2 — Deep Learning | 20 | 5–6 weeks |
| Stage 3 — LLMs | 20 | 5–6 weeks |
| Stage 4 — GenAI | 12 | 3–4 weeks |
| Stage 5 — RAG | 19 | 4–5 weeks |
| Stage 6 — Agents | 20 | 4–5 weeks |
| Stage 7 — MLOps | 21 | 5–6 weeks |
| Stage 8 — Safety | 14 | 3–4 weeks |
| Stage 9 — Specializations | 10 | 2–3 weeks |
| Stage 10 — Architecture | 15 | 4–5 weeks |
| **Total** | **~183 lessons** | **~42–53 weeks (10–13 months)** |

---

## SESSION LOG

| Session | Date | Topics Covered | Lessons Completed | Notes |
|---------|------|----------------|-------------------|-------|
| 1 | (not started) | — | — | Revised plan — now AI Architect aligned. Start Stage 0, Lesson 0.1 |

---

## HOW CLAUDE SHOULD TEACH AWAIS

1. **Always start fresh from this file** — read it, find where he is, continue from NEXT LESSON
2. **Teach concept first** — plain English, no jargon until the concept is clear
3. **Use analogies from his background** — Kafka (streaming), Kubernetes (orchestration), Postgres (vector DB), microservices (AI services), Azure (cloud AI), Docker (containers)
4. **Then show code** — always with line-by-line comments explaining every line
5. **Then ask a question** — "Can you explain back what X does?" or "What would happen if we change Y?"
6. **Wait for his answer** before moving on
7. **Correct gently** if wrong, confirm clearly if right
8. **Mark lesson complete only when he can explain it** — not just read it
9. **Never rush** — one concept at a time, fully understood before advancing
10. **Paper reading**: When a paper lesson appears, summarize the key ideas interactively — do not just list the abstract
11. **Writing prompts**: When a writing lesson appears, help him outline the blog post or architecture document and give feedback on his draft
12. **At end of session** — summarize what was covered, tell him what's next, ask him to say "save progress"

---

## PROGRESS SUMMARY

- **Total Lessons:** ~183 lessons + 9 portfolio projects + 8 certifications + 11 papers + 11 writing pieces
- **Completed:** 0 / 183
- **Current Stage:** Stage 0 — Not Started
- **GenAI Engineer milestone:** After Stage 5 (~6–7 months)
- **AI Engineer milestone:** After Stage 7 (~9–10 months)
- **AI Architect milestone:** After Stage 10 (~12–13 months)
