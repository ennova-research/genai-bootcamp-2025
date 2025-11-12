# 🧠 Generative AI Bootcamp – Week 2
**Dates:** November 24–28, 2025 (Monday–Friday)  
**Theme:** *Databases & Data Pipelines for AI*  
**Goal:** Equip participants to manage, query, and integrate structured and unstructured data sources efficiently for generative AI workflows.

**Format:** Six 1-hour sessions per day, alternating between theoretical and practical.

---

## **Day 1 – Monday, November 24**  
**Theme:** *SQL Foundations for AI Data Workflows*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Introduction to Databases in AI Systems** | Overview of relational vs. non-relational databases; where and how they fit in LLM pipelines. |
| **10:45–11:45** | Practical | **SQL Lab 1: SELECT, WHERE, ORDER BY** | Query datasets using SQLite or BigQuery sandbox. Practice basic selection, filtering, and sorting. |
| **12:00–13:00** | Theoretical | **Joins, Aggregations & Views** | Learn to combine and summarize data for prompt retrieval contexts. |
| **14:30–15:30** | Practical | **SQL Lab 2: JOINs & Aggregations** | Write multi-table queries. Create simple materialized views. |
| **15:45–16:45** | Theoretical | **AI Meets SQL: Text-to-SQL with LLMs** | Understand semantic SQL generation and prompt-based query translation. |
| **17:00–18:00** | Practical | **Hands-on: Text-to-SQL Mini Project** | Use OpenAI / Gemini APIs to generate SQL queries from natural language prompts and validate outputs. |

---

## **Day 2 – Tuesday, November 25**  
**Theme:** *BigQuery & Data Integration*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Cloud Databases: BigQuery Architecture** | Learn BigQuery’s columnar storage, execution model, and cost principles. |
| **10:45–11:45** | Practical | **BigQuery Lab 1: Access via Python SDK** | Connect to BigQuery, run queries programmatically, fetch and visualize results in pandas. |
| **12:00–13:00** | Theoretical | **Schema Design for AI Workflows** | Understand how to model structured, semi-structured, and unstructured data for generative tasks. |
| **14:30–15:30** | Practical | **BigQuery Lab 2: Data Modeling** | Design schemas for prompts, embeddings, and metadata; create and populate tables. |
| **15:45–16:45** | Theoretical | **Optimizing Data Retrieval** | Indexing, partitioning, caching, and query optimization strategies. |
| **17:00–18:00** | Practical | **Performance Tuning Lab** | Compare query performance before/after indexing and caching; measure latency in Python scripts. |

---

## **Day 3 – Wednesday, November 26**  
**Theme:** *ETL Pipelines & Data Cleaning for Prompt Engineering*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **ETL Concepts for AI** | Explore Extract–Transform–Load pipelines in the context of AI data preparation. |
| **10:45–11:45** | Practical | **SQLModel Setup** | `db.py` implementing `get_engine()`, `get_session()`. Screenshot or log showing `/health/db` returns OK. |
| **12:00–13:00** | Theoretical | **Data Quality & Preprocessing** | Handle missing values, outliers, token limits, and prompt formatting. |
| **14:30–15:30** | Practical | **Define Tables & Initial Migration** | `migrations/` directory with `env.py` and an `init` revision. SQLite or Postgres DB initialized successfully. |
| **15:45–16:45** | Theoretical | **Prompt-Driven Data Transformation** | Discuss data filtering guided by prompt templates and contextual requirements. |
| **17:00–18:00** | Practical | **DB-Backed Prompt Store** | CRUD + activation working persistently. Restart app → data survives restart. |

---

## **Day 4 – Thursday, November 27**  
**Theme:** *NoSQL & Vector Databases*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **NoSQL Ecosystem Overview** | Explore document, key-value, columnar, and graph data models. |
| **10:45–11:45** | Practical | **Async Usage Logging** | After calling `/v1/predict`, a row appears in prompt_usage. |
| **12:00–13:00** | Theoretical | **Vector Databases for LLMs** | Understand embeddings, cosine similarity, and nearest-neighbor search. |
| **14:30–15:30** | Practical | **`/v1/history` Endpoint** | JSON response sample with ≥ 3 records and filter working. Endpoint tested successfully. |
| **15:45–16:45** | Theoretical | **Vector Store Comparison & Scaling** | Review FAISS, Pinecone, Weaviate, Milvus, and Redis. Discuss scalability and hybrid search. |
| **17:00–18:00** | Practical | **Postgres Migration + Optional Vector Store Experiment** | API connected to Postgres, all endpoints pass. Optional: small demo saving prompt embeddings to a local vector index. |

---

## **Day 5 – Friday, November 28**  
**Theme:** *Graph Databases & Integration Project*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Graph Databases & Cypher Language** | Introduction to graph theory concepts and Neo4j for knowledge graphs. |
| **10:45–11:45** | Practical | **DB Fixtures & Tests** | `pytest` passes; show test summary. |
| **12:00–13:00** | Theoretical | **Connecting Data Modalities** | Discuss hybrid pipelines combining SQL, NoSQL, and vector stores for RAG and agents. |
| **14:30–15:30** | Practical | **ETL-Lite Export to CSV** | CSV generated under `var/exports/` with ≥ 5 rows. |
| **15:45–16:45** | Theoretical | **Data Governance & Security in AI Systems** | Cover access control, anonymization, and compliance. |
| **17:00–18:00** | Practical | **Review, Showcase & Governance Reflection** | PR link to `feat/week2-db-pipelines` branch. Reflection note in PR or markdown file. |

---

### ✅ **Outcomes by End of Week 2**
- Mastery of **SQL, BigQuery, and NoSQL** for AI data management  
- Ability to **build ETL pipelines** and **prepare clean datasets** for LLM use  
- Hands-on experience with **FAISS / Chroma vector stores**  
- Understanding of **graph databases** and data relationships  
- Working prototype of an **AI data retrieval pipeline** for LLMs  
