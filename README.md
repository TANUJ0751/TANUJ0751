# Hi, I'm Tanuj Jain

**AI/ML and backend engineer** based in Gwalior, India. I build machine learning systems and the products around them: LLM applications, real-time trading platforms, and the FastAPI backends and Flutter apps that ship them.

Currently an **AI/ML and Backend Engineer Intern at Synlane TechCore**.

[![Portfolio](https://img.shields.io/badge/Portfolio-tanujs.in-ffb547?style=flat-square&labelColor=0d1630)](https://tanujs.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tanujjainprofile-ffb547?style=flat-square&labelColor=0d1630)](https://linkedin.com/in/tanujjainprofile)
[![Email](https://img.shields.io/badge/Email-tanuj0751%40gmail.com-ffb547?style=flat-square&labelColor=0d1630)](mailto:tanuj0751@gmail.com)

## What I work on

- **LLM applications:** retrieval pipelines that cite their sources and decline to answer when the evidence is thin.
- **Real-time systems:** live market-data streaming, WebSocket fan-out to many clients, and order engines.
- **Production backends:** FastAPI services on MongoDB, PostgreSQL and Redis, with layered caching, rate limiting and role-based access.
- **Cross-platform apps:** Flutter clients (BLoC) and React/TypeScript dashboards that sit on top of those backends.

## Experience

**AI/ML and Backend Engineer Intern, Synlane TechCore** (Dec 2025 – Present, hybrid)
- Architected DreamLand, a multi-user trading platform with live NSE/MCX and forex order execution across 50K+ instruments via 250+ REST endpoints, served on AWS at about 62 ms average response time.
- Built the React/TypeScript monorepo for its admin, broker and client apps, including a command palette with global shortcuts and a trading-desk PnL heatmap.
- Cut server load by 76% with a RAM → Redis → MongoDB cache, and resolved race conditions in exposure validation and forced square-off in the order engine.
- Migrated push notifications from VAPID to Firebase Cloud Messaging, and delivered the [Synlane TechCore website](https://synlane.com) with its admin dashboard.

**AI/ML Engineer Intern, Labmentix** (Jun 2025 – Dec 2025, remote)
- Built Shopper Spectrum (RFM segmentation with clustering, collaborative-filtering recommendations, Streamlit) and CNN classifiers for brain MRI tumours (93.09% accuracy) and fish species (92.63% accuracy).

**ML Engineer Intern, Rinex AI** (Jul 2024 – Sep 2024, remote)
- Trained and fine-tuned 3+ deep learning models for computer vision and NLP in a five-engineer team.

## Selected work

| Project | What it is | Built with | When |
| --- | --- | --- | --- |
| **Avalio** | Multi-tenant POS and delivery platform for shops and restaurants: a backend with 40+ route modules, an offline-first Flutter POS app and a customer app. Live at [avalio.in](https://avalio.in). | FastAPI, MongoDB, Redis, Elasticsearch, Flutter, Razorpay | Nov 2025 – Present |
| **DreamLand** | Multi-user trading platform for NSE/MCX and forex with admin, broker and client apps (built at Synlane TechCore). | FastAPI, MongoDB, Redis, WebSockets, React, TypeScript, AWS | Dec 2025 – Present |
| **FinSight AI** | RAG research copilot over SEC 10-K and 10-Q filings with section-level citations; declines to answer on weak evidence. | FastAPI, Qdrant, BM25, RRF, cross-encoder reranking, PostgreSQL, GraphQL | Aug 2026 – Oct 2026 |
| **OpsPilot AI** | Event-driven AIOps platform: multi-detector anomaly pipeline, incident correlation over a service dependency graph and ranked root causes; remediation is approval-gated. | Kafka, FastAPI, scikit-learn, GraphQL | Aug 2026 – Oct 2026 |
| **StoxCircle** | Social network for traders on live Indian market prices. Live at [stoxcircle.com](https://stoxcircle.com). | Flutter, FastAPI, Redis, WebSockets, Kite Connect | 2026 |

Most of these repositories are private. I'm happy to walk through the code and design on request. More projects are on [tanujs.in/projects](https://tanujs.in/projects).

## Engineering highlights

- **Caching that pays off.** A local RAM → Redis → MongoDB cache that cut server load by 76% on a 250+ endpoint trading API.
- **Grounded retrieval.** Hybrid search (Qdrant dense vectors plus BM25, merged with reciprocal rank fusion) followed by cross-encoder reranking, with answers that must cite section-level evidence.
- **Market data at speed.** Live ticks streamed to WebSocket clients as compressed delta frames, with automatic reconnects and stall watchdogs.
- **Offline-first retail.** POS billing that keeps working without a connection, using local SQLite and a background sync service.
- **Safe automation.** Anomaly detection with threshold rules, z-score/MAD and Isolation Forest, where remediation is approval-gated and never executed automatically.

## Skills

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, Dart, SQL, Java, C/C++ |
| Backend and APIs | FastAPI, REST, WebSockets, GraphQL, JWT auth and RBAC, Pydantic, Razorpay |
| Databases and caching | MongoDB, PostgreSQL (Supabase), Redis, Elasticsearch, SQLite |
| Frontend and mobile | React, TypeScript, Tailwind CSS, Vite, Framer Motion, Flutter (BLoC) |
| Cloud and tools | AWS, Docker, Kafka, Firebase Cloud Messaging, Git |
| AI/ML | scikit-learn, TensorFlow, PyTorch, OpenCV, Streamlit, RAG (Qdrant, BM25) |

## Education

- **B.Tech in Computer Science and Design**, Madhav Institute of Technology and Science (2023 – 2026), CGPA 8.07
- **Diploma in Computer Science Engineering**, Dr. Bhim Rao Ambedkar Polytechnic College, Gwalior (2020 – 2023), CGPA 8.31

## Mentoring

- Mentored 80+ students in app development; 9 went on to choose app development as their career focus.
- Led IoT Foundation workshops for 100 students; 86 reported a better understanding of IoT and Arduino basics.

## Get in touch

Hiring for an ML or backend role, or have a project that needs a model in production? Email me at [tanuj0751@gmail.com](mailto:tanuj0751@gmail.com) or reach out on [LinkedIn](https://linkedin.com/in/tanujjainprofile).
