# Sajal Malhotra

Undergraduate in Information Technology at the National Institute of Technology, Jalandhar (Class of 2029).

I build full-stack web platforms, real-time competition engines, and retrieval infrastructure.

[LinkedIn](https://www.linkedin.com/in/sajal-malhotra1) • [Email](mailto:malhotrasajal243@gmail.com) • [GitHub](https://github.com/SAJAL-MALHOTRA)

---

## Projects

### [Cybernauts Arena](https://github.com/SAJAL-MALHOTRA/cybernauts-arena)
Real-time 16-team simultaneous 1v1 tournament platform engineered for collegiate hackathons.
- Central authoritative clock engine synchronizing 16 participant client tables with sub-millisecond precision.
- Audio cues generated procedurally via the native Web Audio API and telemetry transitions handled via Framer Motion.
- **Stack:** TypeScript, Next.js, React, Express.js, Web Audio API

### [DSA Lecture RAG](https://github.com/SAJAL-MALHOTRA/dsa-lecture-rag)
Evaluation-driven retrieval-augmented generation system indexing 305 DSA lecture video transcripts.
- Hybrid retrieval combining BM25Okapi with multilingual MiniLM dense embeddings using Reciprocal Rank Fusion (RRF).
- Evaluated against a 104-query benchmark with TOST equivalence testing and data leakage audits.
- In-browser Python sandbox execution powered by Pyodide (WebAssembly), eliminating server-side execution load.
- **Stack:** Python, FastAPI, PyTorch, Pyodide (WASM), BM25

### [India Salary & Career Intelligence Platform](https://github.com/SAJAL-MALHOTRA/salary-predictor)
Compensation estimation and review analysis engine trained on 43,000+ AmbitionBox records.
- Voting ensemble regressor combining Random Forest and HistGradientBoosting (R² = 0.5655, MAE = 3.85 LPA).
- Semantic search across 33,200+ employee review embeddings using FAISS.
- Automated take-home pay calculator reflecting Budget 2024–2026 tax slabs, standard deductions, and EPF rules.
- **Stack:** Python, scikit-learn, FAISS, Streamlit, Plotly

### [DevDex](https://github.com/SAJAL-MALHOTRA/devdex)
Developer profile and digital identity platform with in-person contact sharing.
- Hardware-themed dashboard and public profile pages rendered at `/developers/[username]`.
- PostgreSQL database hosted on Supabase secured with strict Row-Level Security (RLS) policies.
- Client-side RFC 6350 vCard (.vcf) generation and dynamic QR codes for instant mobile contact saves.
- **Stack:** Next.js, React, TypeScript, Supabase, PostgreSQL, Tailwind CSS

### [Surveillance Illumination Classification](https://github.com/SAJAL-MALHOTRA/surveillance-illumination-classification)
3-class computer vision classification pipeline (Dark, Normal, Bright) for surveillance feeds.
- Top competition leaderboard placement (score 0.211+) under strict CPU-only constraints.
- Fuses 128-D handcrafted luminance descriptors with deep representations from ResNet-18, EfficientNet-B0, and ResNet-34 into a 10-fold bagged MLP.
- **Stack:** Python, PyTorch, OpenCV, scikit-learn

---

## Technical Skills

- **Languages:** C, C++, Python, JavaScript, TypeScript, SQL
- **Frontend:** React, Next.js, Tailwind CSS, Framer Motion
- **Backend & Systems:** Node.js, Express.js, FastAPI, REST APIs, WebSockets
- **Databases & Vector Search:** PostgreSQL, Supabase, FAISS
- **Machine Learning & Tools:** PyTorch, scikit-learn, Git, Docker (basics)
