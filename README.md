# Hi, I'm Samia 👋

**AI Engineer** focused on building production-grade AI systems including LLM agents, Retrieval-Augmented Generation (RAG) pipelines, and computer vision applications.

🎓 **Master of AI** graduate (Australia Awards Scholar) specializing in Natural Language Processing  
🔬 Currently building AI systems combining LLMs, search, and vision models  
📍 🎯 Targeting Human-Centered AI and ML Engineering roles in **Singapore, UK, and Remote**

---

## Featured Projects

### nl-db-agent — Agentic RAG for Natural Language Database Queries

Routes plain English questions to SQL, industry documents, or both — automatically.

**How it works:**
- 🗄️ **SQL route** — "What is our total revenue by genre?" → queries Chinook DB → Rock $826.65
- 📄 **Document route** — "What is global music revenue growth?" → searches Pinecone → +4.8% (IFPI 2025)
- 🔀 **Both route** — "How does our Rock revenue compare to global trends?" → combines both sources

**Technical highlights:**
- LangGraph state machine (7 nodes, 3 routing paths)
- Pinecone vector DB — 2,462 vectors from 4 real industry PDFs
- LLM-as-judge evaluation framework (route-specific scoring)
- HCD features: explainability panel + human feedback loop (mirrors RLHF)
- 86.1% benchmark accuracy (36 queries, 6 tiers) · 0% SQL hallucination

**Stack:** LangGraph · GPT-4o-mini · Pinecone · FastAPI · Next.js · Google Cloud Run

🔗 [Repository](https://github.com/SAMithila/nl-db-agent) · [Live Demo](https://llm-sql-agent-ui.vercel.app)

---

### RAG Document Intelligence
Production-grade Retrieval-Augmented Generation system for querying document collections.

**Features:**
- Hybrid retrieval (vector + keyword search)
- Query expansion (HyDE)
- Hallucination detection
- 74% accuracy across 38 evaluation queries

🔗 [Repository](https://github.com/SAMithila/rag-document-intelligence)

---

### LLM API Gateway
Unified backend for multiple AI providers powering 5 AI products.

**Capabilities:**
- Single API for multiple LLM providers
- Automatic failover (Groq → Gemini → OpenAI)
- Real-time cost tracking
- Session management (in-memory + Redis)

**Supports:** OpenAI | Gemini | Groq

🔗 [Repository](https://github.com/SAMithila/llm-api-gateway)

---

### Object Detection + Tracking Pipeline
Computer vision system for real-time object detection and tracking.

**Tech:**
- Mask R-CNN for detection
- SORT tracking algorithm with Kalman filtering
- Self-supervised evaluation metrics
- 78.4% tracking accuracy with 100% ID stability

🔗 [Repository](https://github.com/SAMithila/object-detection-tracking-pipeline)

---

## AI Systems Expertise

| Area | Skills |
|------|--------|
| LLM Applications | Agentic RAG, LangGraph, LLM-as-judge Evaluation, Human-Centered AI, Tool Use, Function Calling |
| Search & Retrieval | Hybrid Search (Vector + BM25), Pinecone, Query Expansion, ChromaDB |
| **Prompt Engineering** | Few-shot, Chain-of-Thought, System Prompts |
| **Computer Vision** | Object Detection, Tracking, Medical Imaging, Foundation Models (SAM) |
| **Infrastructure** | API Orchestration, Multi-provider Failover, Session Management |

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | Python |
| **AI/ML** | PyTorch, TensorFlow, Transformers, LLMs, NLP, Computer Vision |
| **LLM Ecosystem** | OpenAI, Anthropic, Groq, Google Gemini, LangChain, LangGraph |
| **Backend** | FastAPI, REST APIs, Redis |
| **Tools** | Docker, Git, CI/CD (GitHub Actions), VS Code, Jupyter |

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samiaafrinmithila)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:samiaafrinmithila@gmail.com)

---

### ⭐ Open to AI/ML Engineer opportunities
