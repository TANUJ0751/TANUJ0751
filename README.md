# Hi, I'm Tanuj Jain

**AI/ML engineer.** I build machine learning systems and the products around them: LLM applications, real-time trading platforms, and the FastAPI backends and Flutter apps that ship them.

[![Portfolio](https://img.shields.io/badge/Portfolio-tanujs.in-ffb547?style=flat-square&labelColor=0d1630)](https://tanujs.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-tanujjainprofile-ffb547?style=flat-square&labelColor=0d1630)](https://linkedin.com/in/tanujjainprofile)
[![Email](https://img.shields.io/badge/Email-tanuj0751%40gmail.com-ffb547?style=flat-square&labelColor=0d1630)](mailto:tanuj0751@gmail.com)

## What I work on

- **LLM applications:** retrieval pipelines that cite their sources and decline to answer when the evidence is thin, plus the evaluation around them.
- **Real-time systems:** live market-data streaming, WebSocket fan-out to many clients, and order engines.
- **Production backends:** FastAPI services on MongoDB, PostgreSQL and Redis, with layered caching, rate limiting and role-based access.
- **Cross-platform apps:** Flutter clients (BLoC, Riverpod) and React dashboards that sit on top of those backends.

## Selected work

| Project | What it is | Built with | Status |
| --- | --- | --- | --- |
| **Avalio** | Point-of-sale, inventory and delivery platform for shops and restaurants: one API, an admin console and four apps (POS, customer, delivery partner, waiter). | FastAPI, MongoDB, Redis, Elasticsearch, Flutter, React | Live at [avalio.in](https://avalio.in) |
| **StoxCircle** | A social network for traders: circles, trade ideas, watchlists and price alerts on top of live Indian market prices. | Flutter, FastAPI, MongoDB, Redis, WebSockets, Kite Connect | Live at [stoxcircle.com](https://stoxcircle.com) |
| **FinSight AI** | Research copilot over SEC 10-K and 10-Q filings. Every claim carries a citation to company, filing, year, section and page. | FastAPI, Qdrant, BM25, cross-encoder reranking, PostgreSQL, Streamlit | In development |
| **OpsPilot AI** | AIOps platform that detects anomalies, correlates them into incidents and ranks likely root causes. The LLM explains; it never detects, and fixes need human approval. | Python, Kafka, scikit-learn, GraphQL, Prometheus, Grafana | In development |
| **DreamLand** | Multi-asset trading platform for equities, commodities and forex, with separate admin, broker and client apps. | FastAPI, MongoDB, Redis, WebSockets, React, TypeScript | |
| **Synlane website and CRM** | Marketing site for a software studio with a built-in admin for leads, the sales pipeline and content. | React, TypeScript, Tailwind, FastAPI, MongoDB | Live at [synlane.com](https://synlane.com) |
| **Bharat Tibbat Sanyog Manch** | Bilingual English/Hindi website and admin console for a national non-profit, replacing its legacy PHP site. | FastAPI, MongoDB, Redis, React, Netlify | In development |
| **GotraVahi** | Digital record book for hereditary genealogists who track births, marriages and migrations for their clans. | FastAPI, PostgreSQL, SQLAlchemy, Alembic | In development |

Most of these repositories are private. I'm happy to walk through the code and design on request. More projects are on [tanujs.in/projects](https://tanujs.in/projects).

## Engineering highlights

- **Market data at speed.** Streamed the Zerodha Kite tick feed to WebSocket clients as compressed delta frames, with automatic reconnects and a stall watchdog. The Flutter client keeps up with 50+ ticks per second by dropping stale updates and patching quotes in place.
- **Fan-out that doesn't fall over.** A WebSocket bridge that serves normalized ticks to many clients, with a bounded send queue per client, silence watchdogs on every upstream feed and a health endpoint that fails when a feed stalls.
- **Grounded retrieval.** Hybrid search (dense vectors in Qdrant plus BM25, merged with reciprocal rank fusion) followed by cross-encoder reranking, and answers that must cite page-level evidence.
- **Offline-first retail.** POS billing that keeps working without a connection, using local SQLite and a background sync service, backed by a three-level cache (in-process, Redis, MongoDB).
- **Safe automation.** Anomaly detection with rules, robust z-scores and Isolation Forest, where the LLM only explains evidence and remediation is approval-gated.

## Tech stack

| Area | Tools |
| --- | --- |
| Machine learning | PyTorch, scikit-learn, TensorFlow, OpenCV, YOLO |
| LLMs and retrieval | OpenAI, Gemini, Anthropic, LangChain, Qdrant, BM25, cross-encoders |
| Backend | Python, FastAPI, MongoDB, PostgreSQL, Redis, Elasticsearch, Kafka, GraphQL, WebSockets, Celery |
| Apps | Flutter (BLoC, Riverpod), React, TypeScript, Vite |
| Infrastructure | Docker, GitHub Actions, AWS S3, Firebase, Render, Netlify, Prometheus, Grafana |

## Get in touch

Hiring for an ML or backend role, or have a project that needs a model in production? Email me at [tanuj0751@gmail.com](mailto:tanuj0751@gmail.com) or reach out on [LinkedIn](https://linkedin.com/in/tanujjainprofile).
