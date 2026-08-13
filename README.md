<div align="center">
  <img src="assets/profile.jpg" width="150" alt="Zixi Chen profile photo" />
  <h1>Zixi Chen | 陈子熹</h1>
  <p><strong>Undergraduate Researcher @ Xi'an Jiaotong-Liverpool University</strong></p>
  <p><strong>LLM Agents · Reliable AI Systems · Biomedical Machine Learning</strong></p>
  <p>
    <a href="mailto:1697362254@qq.com">Email</a> ·
    <a href="https://github.com/czx6365">GitHub</a>
  </p>
</div>

---

## About Me

I am an undergraduate student in Information and Computing Science at Xi'an Jiaotong-Liverpool University. My work sits at the intersection of **LLM agents, software engineering, retrieval and verification, biomedical sequence modeling, and applied machine learning**.

I am particularly interested in research questions where model capability alone is not enough: systems must also handle incomplete context, noisy evidence, changing environments, reproducible evaluation, and reliable decision making.

My current focus is on building **evidence-aware and testable AI systems** with retrieval, tool use, verification, self-correction, structured memory, and reproducible experiments.

## Selected Research & Engineering

| Project | Research / Engineering Focus | Keywords |
| --- | --- | --- |
| [**ECHO-Repro**](https://github.com/czx6365/ECHO-Repro) | Environment-aware LLM agent for synthesizing executable bug reproduction harnesses and validating them with Fail-to-Pass criteria | LLM Agent, SWE-bench, CI, Bug Reproduction |
| [**SelfCorrect Agent**](https://github.com/czx6365/agent_selfcorrect) | Studies when LLM self-correction helps or hurts using calculator-gated refinement, reflection memory, retrieval, and unit-test feedback | Self-Correction, Reflection, Tool Feedback, Evaluation |
| [**ECG Research**](https://github.com/czx6365/ECG) | 12-lead ECG representation learning with heartbeat-level tokenization, masked pretraining, and downstream risk prediction | ECG, Representation Learning, PyTorch |
| [**HeritageHub**](https://github.com/czx6365/CPT202_GroupProject) | Full-stack platform with JWT authentication, RBAC, review workflow, auditability, and lifecycle management | Spring Boot, React, MySQL, Software Engineering |
| [**Controllable Multi-Interest Recommendation**](https://github.com/czx6365/Controllable-Multi-Interest-Framework-for-Recommendation) | Sequential recommendation and multi-interest user representation learning | Recommendation, Multi-Interest Learning, TensorFlow |

## Research Interests

- **LLM agents for software engineering:** bug reproduction, CI validation, tool use, execution feedback, and automated debugging.
- **Reliable agent workflows:** retrieval, verification, confidence-guided routing, structured SOPs, memory, and self-correction.
- **Retrieval-augmented systems:** BM25, dense retrieval, hybrid search, evidence construction, and grounded generation.
- **Biomedical sequence modeling:** ECG tokenization, adaptive masking, representation learning, and clinically meaningful downstream prediction.
- **Recommendation systems:** controllable generation, multi-interest modeling, and user behavior representation.

## Current Research Highlights

### ECHO-Repro

Research prototype for turning issue / log / trace / repository context into a **minimal executable reproduction harness**. The system explicitly separates source, test, and environment evidence, executes the generated harness, classifies failure modes, repairs recoverable errors, and uses **Fail-to-Pass validation** as the final success criterion.

### SelfCorrect Agent

Experimental study of LLM self-correction on **GSM8K** and **HumanEval**. The repository compares Direct, CoT, Self-Refine, Reflection, CRITIC, unit-test repair, and verified-example retrieval under fixed evaluation settings, with an emphasis on when correction introduces regressions instead of improvements.

### ECG Language Modeling

Research on 12-lead ECG representation learning using heartbeat-level tokenization and masked pretraining, with downstream experiments for coronary stenosis risk prediction. Current work investigates adaptive masking, selective masked-token learning, and evidence-aware fine-tuning.

## Selected Experience

- **Chinese University of Hong Kong (Shenzhen) — Research Assistant:** contributed to industrial CI failure diagnosis research, including topology-aware evidence construction, case memory, investigation paths, baseline reproduction, and evaluation.
- **Huawei × CUHK-Shenzhen Collaboration — AI Engineering Project Member:** worked on RTOS / MindSpore intelligent fault diagnosis with data governance, retrieval, LLM-based verification, confidence routing, and SOP-based diagnostic workflows.
- **Guangdong Telecom Planning & Designing Institute — AI Large Model Engineering Intern:** implemented enterprise RAG workflows with LangChain-Chatchat, FastAPI, Streamlit, BM25 + FAISS hybrid retrieval, and self-correction.
- **iFLYTEK Healthcare Technology — Big Data Development Intern:** worked on layered healthcare data warehousing, SQL / ETL pipelines, data-quality validation, and production migration checks.

## Tech Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

**LLM / Agent:** RAG, Tool Calling, Agent Workflow, LangChain, LangGraph, Prompt Engineering, Self-Correction, LLM Evaluation  
**Retrieval / Modeling:** BM25, FAISS, Embedding Retrieval, Hybrid Search, LoRA / SFT, vLLM, PyTorch  
**Backend / Data:** FastAPI, Spring Boot, REST APIs, MySQL, JPA, SQL, ETL Validation  
**Engineering:** Linux, Git, Docker, CI/CD, LaTeX

## Awards & Additional Information

- 2026 Mathematical Contest in Modeling (MCM) — **Meritorious Winner**.
- IELTS Overall Band **7.0**.
- Interested in graduate study and research opportunities in **LLM agents, reliable AI, software engineering for AI, and biomedical machine learning**.

---

<div align="center">
  <strong>Research-oriented portfolio: methods, experiments, reproducibility, and engineering evidence.</strong>
</div>
