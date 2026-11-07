<div align="center">

# Vinay Somala

**Data science · LLMs & RAG · Supply chain analytics · SQL & Python**

M.Sc. Applied Data Science & AI (SRH University Hamburg, 2025–2027) · SAP S/4HANA MM · Hamburg, Germany

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vinaysomala)
[![Email](https://img.shields.io/badge/Email-444444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vinay.doer@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=vercel&logoColor=white)](https://somalavinay.vercel.app)
[![Live dashboard](https://img.shields.io/badge/Live_dashboard-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://olist-retail-analytics-m4gmzrukba258sgprrpdke.streamlit.app)

</div>

> **Looking for:** Working Student · Internship · Master's Thesis in data science, AI, data analytics or supply chain analytics (Hamburg or remote)

## What I bring

- **Clean data you can trust:** SQL data models with automated quality checks and tests, not one-off scripts.
- **Numbers that answer a business question:** KPIs, dashboards and a written finding, not just charts.
- **AI you can check:** LLM applications that cite their sources, refuse when the evidence is missing, and are measured against a baseline.
- **Supply chain context:** SAP S/4HANA MM (Procure-to-Pay), demand forecasting, logistics analytics.

## Flagship projects

### LexiSyncAI: evidence-grounded legal Q&A (LLM & RAG)

**[Repository](https://github.com/somalavinay879-18/lexisync-ai)** · Python, Ollama (Qwen 2.5 7B), sentence-transformers, BM25, PyMuPDF, Tesseract OCR, Streamlit

| 78% vs 56% | 4 / 4 | 7 / 8 | 96.2% |
|:---:|:---:|:---:|:---:|
| correct answers vs the LLM alone | unanswerable questions refused (LLM alone: 0 / 4) | correct on an unseen contract | OCR character accuracy |

A local AI system that answers questions about legal PDFs and proves every answer: each claim cites the exact page and clause, the cited region is highlighted on the original page, and the system refuses when the documents do not contain the evidence.
- Hybrid search (BM25 + embeddings, rank fusion) with a cross-encoder reranker: paragraph-level recall@1 from 0.53 to 0.72.
- Claim verification and abstention; evaluated on 22 questions plus a held-out test on an unseen contract, with honest failure analysis.

### Olist Retail Analytics

**[Repository](https://github.com/somalavinay879-18/olist-retail-analytics) · [Live dashboard](https://olist-retail-analytics-m4gmzrukba258sgprrpdke.streamlit.app)** · SQL, DuckDB, Python, Streamlit, pytest, GitHub Actions

| 99,441 | 20 | 17 | 4 |
|:---:|:---:|:---:|:---:|
| orders modelled | automated data quality checks | tests run in CI | dashboard views |

End-to-end pipeline on a real e-commerce dataset: raw load, cleaning, star schema and SQL KPIs, a quality report, and a deployed dashboard.

**What the data shows**
- 6.8% of deliveries arrive late, and late orders score **2.27** in reviews vs **4.29** for on-time orders.
- Late deliveries spiked to **14.1%** and **19.0%** in February and March 2018 (normally 3–6%).
- Rio de Janeiro has a **12.1%** late rate vs **4.5%** in São Paulo.

**Forecast to stock levels:** weekly demand forecasts for the 10 largest categories; gradient boosting did not beat the simple “same as last week” baseline (22.6% WAPE), so its error drives the safety stock and reorder points.

## All projects

| Project | Result | Tools |
|---|---|---|
| **[LexiSyncAI](https://github.com/somalavinay879-18/lexisync-ai)** | Local RAG system for legal PDFs with page-and-clause citations, highlighted evidence and abstention: 78% correct vs 56% for the LLM alone, 7/8 on an unseen contract | Python, Ollama, sentence-transformers, Streamlit |
| **[Olist Retail Analytics](https://github.com/somalavinay879-18/olist-retail-analytics)** | Sales and delivery analytics on 99,441 orders: SQL star schema in DuckDB, 20 data quality checks, 17 CI tests and a [live dashboard](https://olist-retail-analytics-m4gmzrukba258sgprrpdke.streamlit.app) | Python, SQL, DuckDB, Streamlit, pytest |
| **[Supermarket Data Pipeline](https://github.com/somalavinay879-18/supermarket-data-pipeline)** | ETL merging 1,000 transactions with product costs into DuckDB, SQL KPIs and a dashboard of sales and profit by product line and city | Python, SQL, DuckDB, Streamlit |
| **[Crypto Price Direction Prediction](https://github.com/somalavinay879-18/crypto-price-prediction-ml)** | Next 15-minute direction for five Bybit pairs; Random Forest and XGBoost reach 52.5% accuracy vs 50.2% for a majority baseline on a time-based split (last 365 days held out, no leakage) | Python, scikit-learn, XGBoost |
| **[CareerTrack](https://github.com/somalavinay879-18/CareerTrack)** | Flask app to track job applications with search, CSV import/export and an analytics page; 22 automated tests, CI and Docker | Python, Flask, SQLite, Docker, pytest |

## Skills

| | |
|---|---|
| **Analysis** | Python, SQL, Pandas, NumPy, scikit-learn, XGBoost |
| **LLMs & GenAI** | RAG, hybrid search (BM25 + embeddings), cross-encoder reranking, Ollama, LLM evaluation |
| **Data & BI** | DuckDB, MySQL, MongoDB, Streamlit, Plotly, Excel |
| **Engineering** | Git, GitHub Actions (CI), pytest, Docker, Flask |
| **SAP & supply chain** | SAP S/4HANA MM, Procure-to-Pay, demand forecasting, AnyLogistix |
| **Languages** | English (professional), German (A2, improving), Hindi (professional), Telugu (native) |

## Education & certification

- **M.Sc. Applied Data Science & AI**, SRH University Hamburg, Oct 2025 – Sep 2027 (specialization Supply Chain Analytics)
- **SAP MM: Sourcing & Procurement with SAP S/4HANA**, TH Brandenburg (ERP4Students), 2026
- **SAP MM: Inventory Management & Invoice Verification**, TH Brandenburg (ERP4Students), winter 2026/27, in progress

---

<div align="center">

**Hiring a working student in data science, AI or supply chain analytics?** [Message me on LinkedIn](https://linkedin.com/in/vinaysomala) or [email me](mailto:vinay.doer@gmail.com).

</div>
