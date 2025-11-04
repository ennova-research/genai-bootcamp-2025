# 🧠 Generative AI Bootcamp – Week 3
**Dates:** December 1–4, 2025 (Monday–Thursday)  
**Theme:** *Generative AI Paradigms (I): LLMs & Prompt Design*  
**Goal:** Master core LLM concepts, transformer mechanisms, and advanced prompt engineering with evaluation and fine-tuning methods.  
**Format:** Six 1-hour sessions per day, alternating between **theoretical** and **practical**.  

---

## **Day 1 – Monday, December 1**  
**Theme:** *Transformers and LLM Foundations*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **From Word2Vec to Transformers** | Review evolution from embeddings to self-attention. Explore positional encoding, encoder–decoder structures, and context windows. |
| **10:45–11:45** | Practical | **Hands-on: Visualizing Attention** | Use `transformers` and `torch` to load a small model (e.g., DistilBERT). Visualize attention maps and token dependencies. |
| **12:00–13:00** | Theoretical | **Understanding LLM Architecture** | Examine layers, tokenization, and memory mechanisms of GPT, Gemini, and Watson X models. |
| **14:30–15:30** | Practical | **Model Introspection Lab** | Query model metadata, token limits, and embeddings via API. Compare small vs. large model outputs. |
| **15:45–16:45** | Theoretical | **Context Windows & Scaling Laws** | Learn how model size, context length, and compute affect performance and reasoning capacity. |
| **17:00–18:00** | Practical | **Prompt-Length Experiment** | Test how token context affects output accuracy. Measure truncation and coherence effects using varying prompt sizes. |

---

## **Day 2 – Tuesday, December 2**  
**Theme:** *Prompt Engineering Principles*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Prompt Taxonomy: Zero-Shot to Chain-of-Thought** | Learn structured prompting techniques: zero-shot, one-shot, few-shot, CoT, and ReAct. |
| **10:45–11:45** | Practical | **Prompt Lab 1: Systematic Experimentation** | Craft prompts using OpenAI and Gemini APIs. Compare answer quality, temperature, and reasoning depth. |
| **12:00–13:00** | Theoretical | **Prompt Design Frameworks & Templates** | Explore template libraries, dynamic prompt construction, and persona-based prompting. |
| **14:30–15:30** | Practical | **Prompt Lab 2: Template Builder in Python** | Build a modular prompt factory in Python with placeholders, variables, and reusable patterns. |
| **15:45–16:45** | Theoretical | **Prompt Guardrails & Responsible Design** | Discuss bias control, toxicity mitigation, and the Guardrails AI framework for safe prompting. |
| **17:00–18:00** | Practical | **Prompt Filtering Lab** | Implement content filters and constraint prompts (e.g., refusal handling, output moderation). |

---

## **Day 3 – Wednesday, December 3**  
**Theme:** *Fine-Tuning and Adaptation Techniques*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Fine-Tuning Fundamentals** | Understand supervised fine-tuning, instruction tuning, and reinforcement learning from human feedback (RLHF). |
| **10:45–11:45** | Practical | **Fine-Tuning Prep Lab** | Clean and tokenize custom datasets for fine-tuning. Use `datasets` and `transformers` libraries. |
| **12:00–13:00** | Theoretical | **Parameter-Efficient Fine-Tuning (PEFT & LoRA)** | Learn low-rank adaptation, prefix-tuning, and adapter methods to reduce training cost. |
| **14:30–15:30** | Practical | **LoRA Mini Lab** | Fine-tune a small open-source model (e.g., TinyLlama) using LoRA with sample data. |
| **15:45–16:45** | Theoretical | **Evaluating Fine-Tuned Models** | Define evaluation metrics: perplexity, BLEU, toxicity, relevance, precision, and drift. |
| **17:00–18:00** | Practical | **Model Evaluation Lab** | Compute evaluation metrics using a held-out validation set. Visualize results in notebooks. |

---

## **Day 4 – Thursday, December 4**  
**Theme:** *LLM Evaluation & Prompt Optimization Project*

| Time | Type | Topic | Description / Learning Activities |
|------|------|--------|----------------------------------|
| **09:30–10:30** | Theoretical | **Evaluation Frameworks & Tools** | Overview of evaluation pipelines: TruthfulQA, HELM, and custom metrics for enterprise LLMs. |
| **10:45–11:45** | Practical | **Evaluation Toolkit Lab** | Implement automated evaluation using open frameworks or custom scoring scripts. |
| **12:00–13:00** | Theoretical | **Optimizing Prompts for Business Use Cases** | Explore task-specific optimization: summarization, classification, and agentic reasoning. |
| **14:30–15:30** | Practical | **Prompt Optimization Challenge** | Refine prompts for accuracy, creativity, and safety. Log and compare iterations. |
| **15:45–16:45** | Theoretical | **Connecting Fine-Tuning & Prompting** | Discuss hybrid workflows (RAG + tuning + prompt design). Prepare for agent-based next week. |
| **17:00–18:00** | Practical | **Showcase: Prompt Evaluation Project** | Present a project combining fine-tuning, prompting, and evaluation. Peer review session. |

---

### ✅ **Outcomes by End of Week 3**
- Strong understanding of **transformer and LLM architectures**  
- Mastery of **prompt engineering techniques** (zero-shot → CoT)  
- Experience with **PEFT / LoRA fine-tuning**  
- Ability to **evaluate model quality and prompt effectiveness**  
- Prepared foundation for Week 4: *LLM Agents & Tool Use*
