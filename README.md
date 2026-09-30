# Aaryan Dhand

Software engineering student at the University of Calgary. I build backend systems and data and LLM pipelines.

![Calgary, AB](https://img.shields.io/badge/Calgary%2C%20AB-555?style=flat-square)
![Open to full-time roles from May 2027](https://img.shields.io/badge/open%20to%20full--time%20roles-from%20May%202027-2ea44f?style=flat-square)
[![Portfolio](https://img.shields.io/badge/portfolio-aaryandhand.com-0969da?style=flat-square)](https://aaryandhand.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-aaryandhand-0969da?style=flat-square)](https://linkedin.com/in/aaryandhand)

I finish my BSc in Software Engineering (Schulich School of Engineering, University of Calgary) in April 2027. I co-founded TowQuick, a multi-tenant roadside-assistance platform I'm still building, and I recently built a retrieval-augmented question-answering pipeline over Ontario Energy Board filings. Before that I worked on LLM and ML systems at Vivordo and a SQL Server data warehouse at Hydro One.

> [!NOTE]
> I'm looking for full-time software engineering roles starting May 2027, and I'm open to relocating.

## Featured projects

### [Regulatory Filings RAG Pipeline](https://github.com/Dhandu7/regulatory-filings-rag)

A bronze, silver, gold pipeline that ingests Ontario Energy Board filings and serves a question-answering API where Claude answers with numbered citations to the source filing, docket, section, and page.

- Parsed 314 of 334 regulator PDFs into 18,233 section-aware chunks and quarantined 13 image-only files.
- Cross-encoder reranking and neighbor-chunk expansion raised LLM-judged answer accuracy from 83% to 97% on a 30-question dev set and from 91% to 100% on a 22-question held-out set I wrote before tuning.
- Every index build is gated on a dbt build of 8 models and 42 tests. GitHub Actions CI and a Docker Compose stack run on every push.

`Python` `PostgreSQL` `pgvector` `dbt` `FastAPI` `LangChain` `Prefect` `Docker` `Claude API`

### [AcmePlex](https://github.com/Dhandu7/AcmePlex)

A movie-booking platform in Java with a Spring Boot backend, built around the Model-View-Controller pattern.

`Java` `Spring Boot`

### More

- **NBA Betting Odds Analyzer:** trains and evaluates five classifiers per query, picks the best by validation ROC-AUC, and tracks runs in MLflow. `Python` `scikit-learn` `XGBoost` `MLflow`
- **Pathways:** a React and Flask platform for refugees and immigrants, with real-time translation and tailored job postings. `React` `Flask` `DynamoDB` `AWS`
- **Java Disaster Victim Database System:** a Java application that manages disaster-victim data in a custom SQL database. `Java` `SQL`
- **DriveAwake:** a React app that tracks drivers' EOG signals to help prevent road incidents. `React` `Flask` `Arduino`

## Experience

| Role | Where | When | What I did |
| --- | --- | --- | --- |
| Co-Founder, Product & Development | TowQuick | Jun 2026 to present | Multi-tenancy with PostgreSQL Row-Level Security and a zero-downtime driver migration, Stripe Connect payouts, and the dispatch microservice. |
| AI & Machine Learning Engineer | Vivordo | Oct 2025 to Jul 2026 | Cut LLM inference latency by 57% in a RAG insight pipeline and built a multimodal stress model. |
| Data Analyst Co-op | Hydro One Networks | May 2025 to May 2026 | SQL Server warehouse ingesting 10GB a day across three sources, and a six-person ETL team that made material quantification 6x faster. |
| Software Developer | TechStart UCalgary & Tidefall Studios | Oct 2024 to Jun 2025 | Improved Unity gameplay runtime performance by 40% and built a modular item framework that made integration 90% faster. |

## Tech I use

| | |
| --- | --- |
| **Languages** | `Java` `TypeScript` `JavaScript` `Python` `C++` `C#` `C` `SQL` |
| **Backend** | `Spring Boot` `Node.js` `Express` `FastAPI` `Flask` `REST APIs` `PostgreSQL` |
| **Data and ML** | `pgvector` `dbt` `DuckDB` `Prefect` `pandas` `PyTorch` `TensorFlow` `scikit-learn` `MLflow` |
| **LLMs** | `Anthropic API` `RAG` `LangChain` `Cross-encoder reranking` `LLM-as-judge evaluation` |
| **Frontend** | `React` `HTML/CSS` |
| **Cloud and tooling** | `AWS` `Google Cloud` `Supabase` `Docker` `GitHub Actions` `Git` `Playwright` `Vitest` `Linux` |

## Also

- Leading SCENR as product manager of a 10-person student team, a collaborative trip-intelligence app.
- Currently taking Computer Graphics and Applied Data Analytics. Completed Applied Machine Learning, Databases, Software Architecture, Data Structures & Algorithms, and Operating Systems.
- Best Design at TechStart 2025. Jason Lang Scholarship and Suncor Energy Dependant Scholarship, 2022 to 2026.

## Contact

[aaryandhand.com](https://aaryandhand.com) · [LinkedIn](https://linkedin.com/in/aaryandhand)
