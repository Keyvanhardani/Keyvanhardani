### Keyvan Hardani

**Doctoral Researcher (PhD) | AI for Engineering Systems & Intelligent Security Systems**
Munich, Germany · IEEE Member

**TU Darmstadt** — PhD: AI for Engineering Systems & Intelligent Security Systems
**ZM-I Group** — Lead AI Engineer (AI-driven platforms for engineering & industrial applications)
M.Sc. Cybersecurity (HDBW Munich) · OSCP · CEH · 10+ CVE credits

---

**Research Focus**

- **Sovereign German LLMs** — pretraining from scratch, German tokenizers, license-audited data (Mankei · TU Darmstadt research project)
- **Benchmarks & Evaluation** — domain benchmarks with verified ground truth, hallucination-rate metrics (BelegBench, StatikBench)
- **Agentic AI & Autonomous Systems** — multi-agent orchestration, tool-using LLMs, planner/executor architectures
- **AI Automation** — end-to-end workflow automation, document → decision pipelines, RPA × LLM
- **Intelligent Security Systems** — ML for threat detection, LLM red-teaming, adversarial robustness
- **Intelligent Document Processing** — OCR, layout analysis, Vision-Language Models
- **AI for Engineering & Infrastructure** — technical documents, maps, plans, industrial data
- **Privacy-aware & Trustworthy ML** — GDPR-compliant pipelines, on-prem inference, PII redaction

---

### 🆕 Recent Highlights

**🏔️ Mankei — launching July 26, 2026** — sovereign German LLM family, pretrained from scratch
- German-first tokenizer, license-audited training data, verified synthetic data — no closed-API distillation
- Apache 2.0 · runs fully local (CPU-compatible) · dialect variants on the roadmap
- Official research project at **TU Darmstadt** (AI for Engineering Systems)
- 🌐 [mankei.ai](https://mankei.ai)

**🧾 Belegant-4B + BelegBench — July 2026, open source** — Swiss on-prem receipt & QR-invoice AI (DE / FR / IT)
- **84.7 % field exact match at 0.0 % hallucination** (BelegBench v1, n = 300) — every field passes a deterministic verification layer or gets flagged, never silently emitted
- First public benchmark for Swiss QR-invoices (QR-IBAN, QR-Referenz, MWST 8.1/2.6/3.8 %, CHE-UID)
- `pip install belegant` · 🤗 [belegant-4b](https://huggingface.co/Keyven/belegant-4b) · 💻 [belegant](https://github.com/Keyvanhardani/belegant) · [belegbench](https://github.com/Keyvanhardani/belegbench)

**🛡️ Mythos Research Edition v2.0** — outside-in replication of Anthropic's *Mythos Preview / Project Glasswing*
- 8-phase pipeline (was 7) — build-sandbox · adversarial self-challenge · cross-session false-positive memory
- Powered by Claude Opus 4.7 · ~$1 per targeted scan
- Vendor-ready disclosure templates: GHSA · HackerOne · CVE · Bugzilla
- Research scaffold — live exec validator & exploit development stay private
- ArXiv preprint in preparation

**📄 German-OCR 3.1 + German-Text 3.1** — local DSGVO document AI
- More compact, lower VRAM, same strict-JSON quality. Apache 2.0, GGUF.
- `ollama pull Keyvan/german-ocr-3.1`
- `ollama pull Keyvan/german-text-3.1`
- 🤗 Hugging Face: [Keyven](https://huggingface.co/Keyven) · 💻 GitHub: [Keyvanhardani/german-ocr](https://github.com/Keyvanhardani/german-ocr) · 🌐 Hosted/On-Prem: [german-ocr.de](https://german-ocr.de)
- **Next:** German-OCR Word Plugin — local via Ollama / vLLM / llama.cpp or hosted API

**🔐 April 2026 — 4 CVEs assigned** · 9 more in triage
- 3× **CVE-2026-40492 / 40493 / 40494** — *CRITICAL* in sail image decoders
- 1× *MEDIUM* in PhpSpreadsheet

---

### Current Projects

- **[Mankei](https://mankei.ai)** — sovereign German LLM family, pretrained from scratch · TU Darmstadt research project *(launch: July 26, 2026)*
- **[Belegant](https://github.com/Keyvanhardani/belegant)** / **[BelegBench](https://github.com/Keyvanhardani/belegbench)** — Swiss on-prem QR-invoice AI with deterministic verification + the benchmark behind it
- **StatikBench** — first German-language LLM benchmark for building norms & norm-based structural design, with solver-verified ground truth · TU Darmstadt research project *(release planned)*
- **[German-OCR 3.1](https://github.com/Keyvanhardani/german-ocr)** — local vision-language OCR for German documents (+ Text model 3.1)
- **Mythos Research Edition** — autonomous AI vulnerability-research scaffold *(research-only)*
- **[German-Privacy-Shield](https://github.com/Keyvanhardani/german-privacy-shield)** — GDPR-compliant PII detection & redaction
- **German-OCR Word Plugin** — local DSGVO document AI inside MS Word *(coming soon)*
- **[German-TTS](https://german-tts.de)** — German text-to-speech *(WIP / public release soon)*
- **[Deutschland-Assistent](https://deutschland-assistent.de)** — AI assistant for German document & workflow automation *(coming soon)*

---

### Stack

**💻 Languages** · Python · C++ · Go · TypeScript · Rust · SQL · Bash

**🤖 Agentic AI & Multi-Agent Systems**
LangGraph · LangChain · AutoGen · CrewAI · DSPy · OpenAI Swarm · ReAct · Reflexion · Tree-of-Thoughts · Planner / Executor · Tool-use & function calling · Multi-agent orchestration · Agent memory (short / long-term) · Self-critique loops · Browser-using agents · Sandboxed code execution · Agentic RAG

**🧠 LLM Apps · RAG · Evaluation**
Weaviate · FAISS · Pinecone · Qdrant · Chroma · Hybrid + semantic search · Re-ranking · GraphRAG · Knowledge graphs (Neo4j) · Structured outputs / JSON mode · Prompt caching · Guardrails AI · NeMo Guardrails · LangSmith · LangFuse · Phoenix · RAGAS

**🎯 Models · Training · Inference**
PyTorch · TensorFlow · ONNX · Transformers · PEFT · LoRA · QLoRA · DPO · ORPO · RLHF · TRL · Axolotl · Unsloth · DeepSpeed · FSDP · Hugging Face Hub · Ollama · llama.cpp · vLLM · SGLang · TGI · TensorRT-LLM · GGUF · MLX

**👁️ Vision & Multimodal**
Vision-Language Models (Qwen-VL · LLaVA · InternVL) · OCR · Layout analysis · Document AI · CLIP / SigLIP embeddings

**🔄 Automation & Workflows**
n8n · Temporal · Airflow · Prefect · Celery · Event-driven pipelines · Webhooks · Playwright · MS Office / Word automation

**🛠️ Infra & MLOps**
Docker · Kubernetes · FastAPI · CUDA · GPU orchestration · CI/CD · MLflow · Weights & Biases

**🔐 Security & Red-Team**
LLM red-teaming · Prompt injection (direct & indirect) · Adversarial ML · Vulnerability research · CVE workflow · GHSA · HackerOne · Bugzilla · GDPR / DSGVO · Threat modeling · OSINT · SBOM

---

### Contact

📧 [hardani@hotmail.de](mailto:hello@keyvan.ai)
🔗 [LinkedIn](https://linkedin.com/in/keyvanhardani)
🤗 [HuggingFace](https://huggingface.co/Keyven)
🦙 [Ollama](https://ollama.com/Keyvan)
🌐 [keyvan.ai](https://keyvan.ai) · [german-ocr.de](https://german-ocr.de)

<sub>Open to selected collaborations in agentic AI, applied automation, vision-language systems, and intelligent security.</sub>
