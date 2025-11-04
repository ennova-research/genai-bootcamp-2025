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
| **10:45–11:45** | Practical | **Lab: Build an ETL Script** | Implement a Python ETL pipeline to clean and normalize text data from CSV/JSON. |
| **12:00–13:00** | Theoretical | **Data Quality & Preprocessing** | Handle missing values, outliers, token limits, and prompt formatting. |
| **14:30–15:30** | Practical | **Text Cleaning & Tokenization Lab** | Use `spaCy`, `tiktoken`, and regex to preprocess data for embeddings or fine-tuning. |
| **15:45–16:45** | Theoretical | **Prompt-Driven Data Transformation** | Discuss data filtering guided by prompt templates and contextual requirements. |
| **17:00–18:00** | Practical | **Mini Project: Clean Dataset for Prompting** | Prepare a dataset for use in RAG or fine-tuning scenarios. Export clean output to BigQuery/CSV. |

---

## **Day 4 – Thursday, November 27**  
**Theme:** *NoSQL & Vector Databases*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **NoSQL Ecosystem Overview** | Explore document, key-value, columnar, and graph data models. |
| **10:45–11:45** | Practical | **MongoDB / Firebase Lab** | Store and query unstructured JSON documents for AI apps. |
| **12:00–13:00** | Theoretical | **Vector Databases for LLMs** | Understand embeddings, cosine similarity, and nearest-neighbor search. |
| **14:30–15:30** | Practical | **Vector Store Lab: FAISS / Chroma** | Build a local FAISS index; perform similarity search over embeddings. |
| **15:45–16:45** | Theoretical | **Vector Store Comparison & Scaling** | Review FAISS, Pinecone, Weaviate, Milvus, and Redis. Discuss scalability and hybrid search. |
| **17:00–18:00** | Practical | **Integration Challenge: Semantic Search Demo** | Combine embedding generation with FAISS for question-answer retrieval. |

---

## **Day 5 – Friday, November 28**  
**Theme:** *Graph Databases & Integration Project*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Graph Databases & Cypher Language** | Introduction to graph theory concepts and Neo4j for knowledge graphs. |
| **10:45–11:45** | Practical | **Neo4j Lab: Build a Mini Knowledge Graph** | Create entities and relationships, query using Cypher. |
| **12:00–13:00** | Theoretical | **Connecting Data Modalities** | Discuss hybrid pipelines combining SQL, NoSQL, and vector stores for RAG and agents. |
| **14:30–15:30** | Practical | **Integration Lab: Unified Data API** | Build a Python layer integrating SQL + vector queries for retrieval. |
| **15:45–16:45** | Theoretical | **Data Governance & Security in AI Systems** | Cover access control, anonymization, and compliance. |
| **17:00–18:00** | Practical | **Showcase: End-to-End Retrieval Pipeline** | Teams present a complete ETL → store → query → retrieval pipeline powering a generative model. |

---

### ✅ **Outcomes by End of Week 2**
- Mastery of **SQL, BigQuery, and NoSQL** for AI data management  
- Ability to **build ETL pipelines** and **prepare clean datasets** for LLM use  
- Hands-on experience with **FAISS / Chroma vector stores**  
- Understanding of **graph databases** and data relationships  
- Working prototype of an **AI data retrieval pipeline** for LLMs  
