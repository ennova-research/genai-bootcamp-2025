# 🧠 Generative AI Bootcamp – Week 1
**Dates:** November 17–21, 2025 (Monday–Friday)  
**Theme:** *Software Engineering for AI Applications*  
**Format:** Six 1-hour sessions per day, alternating between **theoretical** and **practical**.  
**Goal:** Build a robust Python foundation for AI systems — from design patterns to containerized microservices.

---

## **Day 1 – Monday, November 17**  
**Theme:** *Python Refresher & Design Foundations*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Python for AI Engineering** | Refresher on Python syntax, data structures, list comprehensions, typing hints, and decorators. |
| **10:45–11:45** | Practical | **Notebook Warm-up: Clean Python Code** | Implement small utilities using `dataclasses`, `typing`, and `pathlib`. Emphasize readability and maintainability. |
| **12:00–13:00** | Theoretical | **Modules, Packages & Imports** | Deep dive into Python packaging, module resolution, and virtual environments. |
| **14:30–15:30** | Practical | **Hands-on: Modularization & Virtual Envs** | Split a script into modules, manage dependencies via `venv`/`poetry`, and test imports. |
| **15:45–16:45** | Theoretical | **Design Patterns Overview** | Explore Factory, Strategy, and Adapter patterns in AI application contexts. |
| **17:00–18:00** | Practical | **Coding Lab: Implement a Strategy Pattern** | Create a text-generation strategy system supporting different model backends (OpenAI, Gemini, Watson X). |

---

## **Day 2 – Tuesday, November 18**  
**Theme:** *OOP, Typing, and Async Programming*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **OOP in AI Systems** | Classes, inheritance, composition, interfaces, and mixins for scalable AI pipelines. |
| **10:45–11:45** | Practical | **OOP Implementation Lab** | Build a simple inference pipeline class hierarchy (Tokenizer → Model → OutputFormatter). |
| **12:00–13:00** | Theoretical | **Async Programming & API Concurrency** | Understand `asyncio`, tasks, and parallel API calls for LLM interactions. |
| **14:30–15:30** | Practical | **Async Hands-on: Concurrent LLM Calls** | Implement async requests to multiple model endpoints and measure latency. |
| **15:45–16:45** | Theoretical | **Observer & Adapter Patterns** | Study how to monitor events and wrap APIs for consistency across providers. |
| **17:00–18:00** | Practical | **Lab: Logging via Observer Pattern** | Add event logging to model calls; visualize asynchronous logs in real time. |

---

## **Day 3 – Wednesday, November 19**  
**Theme:** *APIs, Services, and Configuration Management*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Service Design & RESTful APIs** | Explore HTTP verbs, routing, and schema validation with FastAPI. |
| **10:45–11:45** | Practical | **FastAPI Lab: Create a Model Service Endpoint** | Build and test a REST API wrapping a simple AI model. |
| **12:00–13:00** | Theoretical | **Config, Logging & Error Handling** | Discuss `.env`, YAML/JSON configs, and structured logging (`logging`, `pydantic`, `rich`). |
| **14:30–15:30** | Practical | **Implement Config + Logging Layers** | Add configuration loading and robust error handling to the service. |
| **15:45–16:45** | Theoretical | **Testing & Quality Assurance** | Review unit testing, mocking, and CI basics for AI codebases. |
| **17:00–18:00** | Practical | **PyTest Lab: Mocking AI Calls** | Write tests mocking LLM responses; measure coverage and edge cases. |

---

## **Day 4 – Thursday, November 20**  
**Theme:** *Packaging, Distribution, and MLOps Integration*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Packaging AI Projects** | Explore `setup.py`, `pyproject.toml`, versioning, and dependency management. |
| **10:45–11:45** | Practical | **Hands-on: Package a Local Library** | Package your inference utilities as a Python library and publish locally. |
| **12:00–13:00** | Theoretical | **Intro to CI/CD for AI** | Understand pipelines for code testing, linting, and deployment (GitHub Actions / Cloud Build). |
| **14:30–15:30** | Practical | **CI Pipeline Simulation** | Create a simple YAML workflow for auto-testing and packaging. |
| **15:45–16:45** | Theoretical | **Docker Fundamentals** | Learn Docker concepts: images, layers, containers, and volumes. |
| **17:00–18:00** | Practical | **Docker Lab: Containerize Your Service** | Dockerize the FastAPI AI microservice with configs and dependencies. |

---

## **Day 5 – Friday, November 21**  
**Theme:** *Integration & Review*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **From Code to Cloud** | Recap of MLOps workflow: development → packaging → containerization → deployment. |
| **10:45–11:45** | Practical | **Mini-Project Kickoff: AI Microservice Suite** | Integrate modules into a cohesive AI microservice stack. |
| **12:00–13:00** | Theoretical | **Design Review & Optimization** | Evaluate design patterns and performance trade-offs in AI codebases. |
| **14:30–15:30** | Practical | **Debug & Optimize** | Profile performance, add async batching, and tune logging. |
| **15:45–16:45** | Theoretical | **Preview: Data Handling & Databases (Next Week)** | Bridge concepts from APIs to data pipelines and retrieval systems. |
| **17:00–18:00** | Practical | **Showcase: “AI Service in a Container”** | Individual presentations of containerized AI microservices with FastAPI and Docker. |

---

### ✅ **Outcomes by End of Week 1**
- Solid understanding of **Python design patterns for AI**  
- Working **FastAPI microservice** wrapping AI model logic  
- Experience with **async APIs, logging, error handling, and testing**  
- Packaged, **Dockerized** project ready for cloud deployment  
- Preparation for Week 2: *Databases & Data Pipelines for AI*
