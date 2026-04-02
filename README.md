# <p align="left">✨ Lakshmi Sowjanya Bhagodula ✨</p>
<p align="left">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=42A5F5&center=true&vCenter=true&width=600&lines=Senior+AI+%2F+ML+Engineer;" alt="Typing SVG" />
</p>

<p align="left">
  <a href="https://lsbhogadula.org"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/lakshmi-bhogadula/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:lakshmisowjanya275@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## ⚡ Executive Summary
Experienced **AI/ML Engineer (5+ Years)** with a specialized focus on **Generative AI (3+ Years)**. I bridge the gap between cutting-edge LLM research and production-grade enterprise systems. My expertise lies in architecting **Agentic AI** using multi-agent orchestration (LangGraph) and high-performance **RAG pipelines**.

> "Building autonomous intelligence that doesn't just predict the next word, but executes the next action."

- **Current Focus:** Autonomous agent systems with stateful memory and dynamic tool-calling.
- **Enterprise Impact:** Improved response accuracy by **35%** at US Bank via advanced RAG optimization.
- **Academic Background:** M.S. in Computer Science from Texas Tech University.

---

## 🛠️ Technical Powerhouse

### 🧠 Generative AI & Core Intelligence
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜%20LangChain-121011?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

| Domain | Technologies |
| :--- | :--- |
| **Generative AI** | LangGraph, LLaMA-3, Claude, Gemini, RAG, MCP, CrewAI |
| **Machine Learning** | Scikit-learn, XGBoost, Reinforcement Learning, TensorFlow |
| **LLM Ops / Tuning** | LoRA, PEFT, Prompt Engineering (CoT/Few-Shot), MLflow, W&B |
| **Data & Vectors** | Pinecone, OpenSearch, Azure AI Search, FAISS, PySpark, SQL |
| **Cloud & DevOps** | Azure ML, AWS SageMaker, GCP Vertex AI, Docker, Kubernetes, Terraform |
| **Engineering** | FastAPI, Flask, CI/CD, Prometheus, Grafana |

---

## 📈 Professional Trajectory

#### **GenAI Engineer | US Bank** *July 2024 – Present*
- Deployed Agentic AI systems using **LangGraph** for autonomous task execution.
- Fine-tuned **Llama-2** and **Gemma** for enterprise workloads using LoRA/PEFT.
- Built multimodal pipelines processing text, PDFs, and images via OCR and LLM-retrieval.

#### **Research Engineer | Texas Tech University**
*Sept 2022 – May 2024*
- Developed RL-based decision-making workflows and scalable NLP microservices.
- Automated end-to-end MLOps pipelines using GitHub Actions and MLflow.

#### **Data Scientist | Tata Consultancy Services (TCS)**
*Jan 2020 – Aug 2022*
- Increased user engagement by **15%** via collaborative filtering recommendation systems.
- Boosted CV model accuracy by **18%** for production object detection tasks.

---

## 🚀 Featured Project: Workup Agent: ERISA Denial Analysis System

[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/downloads/release/python-3120/)
[![LLM](https://img.shields.io/badge/Supported%20LLMs-GPT--4o%20%7C%20LLaMA3-orange.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

A production-ready, agentic system designed to analyze medical claim denials subject to ERISA guidelines. This system bridges advanced natural language synthesis with deterministic, auditable machine learning classifiers to simulate a highly specialized human claims analyst.


## 🏗️ System Architecture & Data Flow

This project utilizes a **Tool-Augmented Reasoning** paradigm, allowing an LLM to follow strict decision trees while dynamically calling isolated programmatic tools.

```mermaid
graph TD
    A[User CLI / API] -->|Invokes Command| B(Core Agent Pipeline)
    
    %% Agent Processing
    B -->|1. Load & Normalize| C[Claim Loader CSV]
    B -->|2. Orchestrate Workflow| D{Reasoning Loop}
    
    %% Tool Layer
    D -->|Calls| E[Classifier Tool]
    D -->|Calls| F[Playbook Retriever Tool]
    D -->|Calls| G[Session Store Tool]
    
    %% Operations
    E -->|TF-IDF + Logistic Reg| H[(Denial Taxonomy)]
    F -->|Keyword Match| I[(Playbook DB)]
    G -->|Persistence| J[(SQLite DB)]
    
    %% Output
    D -->|3. Synthesize| K[Output Synthesis]
    K -->|4. Validate| L{Schema Validator}
    L -->|Pass| M[Strict JSON Result]
    L -->|Fail| N[Error Handling / Retry]
```
---

## 📫 Let's Build Something Intelligent
I am always looking to discuss **Agentic AI frameworks**, **LLM Fine-tuning**, or **Responsible AI**. 

- **Location:** Liberty Hill, TX (Open to Remote)
- **Website:** [lsbhogadula.org](https://lsbhogadula.org)
- **Fun Fact:** I'm currently experimenting with indoor saffron farming—it's surprisingly similar to tuning an LLM: high sensitivity, specific environments, and great rewards!
