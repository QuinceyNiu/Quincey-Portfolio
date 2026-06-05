# Backend Developer | AI Products

---

## Technical Skills

- **Backend**: Java, Python, Spring Boot, FastAPI, RESTful APIs, Kafka, Redis, MinIO
- **AI / LLM**: RAG, ReAct Agent, Function Calling, MCP, Prompt Engineering, Qwen3-Max, bge-m3
- **Data / Search**: PostgreSQL, SQLite, Elasticsearch, Milvus, vector search, metadata management
- **Frontend / Delivery**: React, TypeScript, Vue, Docker, GitLab CI/CD, debugging, MVP validation
- **Languages**: Mandarin Chinese, English

---

## Professional Experience

**AI Full-Stack Engineer**  
*Shanghai Xiaoling Biopharmaceutical Technology Co., Ltd.*  
*Jan 2026 - May 2026* | Shanghai, China  

- Designed and delivered the **X-AGEING RAG medical assistant MVP** using **FastAPI, React, and TypeScript**, integrating medical knowledge retrieval, Qwen3-Max report post-processing, and source citation for traceable health-check report analysis.
- Built a hybrid RAG architecture combining **Milvus vector retrieval** with PageIndex single-document section reranking, routing clinical guidelines, lab indicators, and disease encyclopedias by `doc_type`.
- Implemented medical knowledge ingestion and retrieval services, including PDF/Markdown parsing, semantic chunking, **bge-m3 embeddings**, Milvus vector storage, metadata management, and Top-K retrieval by abnormal health indicators.
- Injected retrieved evidence into LLM post-processing prompts and displayed source document, section, page, excerpt, and retrieval-channel markers to improve explainability and reduce medical hallucination risk.

**Software Engineer**  
*Tripalink Corp.*  
*May 2024 - Dec 2025* | United States  

- Designed and implemented a **RAG-based property knowledge base** and **GenAI search suggestion service**, vectorizing property descriptions, FAQs, and lease terms into **Elasticsearch** for keyword plus semantic hybrid retrieval.
- Used **Kafka** to decouple document upload, parsing, vectorization, and retrieval workflows.
- Implemented chunked and resumable large-file uploads with **Spring Boot, Redis, and MinIO**, reducing knowledge-base update latency from hours to minutes.
- Launched GenAI search suggestions by vectorizing natural-language user intent to retrieve Top-K relevant listings and candidate search terms, improving search conversion by approximately **15%**.
- Optimized slow queries, cache strategy, and API concurrency to improve backend reliability and performance.

---

## Project Experience

**PaiCLI Agent**  
*AI Coding Agent / Independent Developer Project*  
*Mar 2026 - May 2026*  

- Independently developed a terminal AI coding agent similar to Claude Code, supporting **ReAct reasoning**, Function Calling, Plan-and-Execute orchestration, MCP tool invocation, long-term memory, and RAG codebase search.
- Designed an extensible **ToolRegistry** that exposes file I/O, command execution, code search, web search, and external MCP tools as agent-selectable functions.
- Built a **Planner → DAG → Executor** execution path to decompose complex tasks into dependency-aware subtasks.
- Used `asyncio` and `ThreadPoolExecutor` to execute independent subtasks in parallel and improve multi-step development task efficiency.
- Implemented cross-session memory and codebase retrieval with context summary compression, **tree-sitter** code chunking, BM25 plus vector-similarity hybrid search, and a `search_code` agent tool.

---

## Education

**University of Pittsburgh**  
*Sep 2022 - Apr 2024*  

- M.S. in Computer Science

**Changzhou University**  
*Sep 2018 - Jun 2022*  

- B.S. in Computer Science and Technology
