[![Header Banner](images/github-banner-new.svg)](images/github-banner-new.svg)

# Hi, I'm Rosalina Torres 👋

MS Data Analytics Engineering @ Northeastern University · expected August 2026 · 3.7 GPA

Specializing in ML/AI systems, agentic architectures, and production data pipelines. Building intelligent, scalable systems that solve real problems — from databases to deployment.

---

## 🧠 Portfolio Architecture

**My projects form an interconnected ML ecosystem powered by a unified Memory Brain:**

```mermaid
flowchart TB
    subgraph Infra["Infrastructure"]
        Ollama["Ollama"]
        AgentCmd["Agent Commander"]
        Ollama -.-> AgentCmd
    end

    subgraph Agents["Autonomous Agents (21)"]
        direction LR
        AutoAgents["Automation<br/>Agents"]
        JobSwarm["Job Hunting<br/>Swarm"]
        MLToolkit["ML/AI<br/>Toolkit"]
        LinkedInAgent["LinkedIn<br/>Analyzer"]
    end

    subgraph MCPLayer["MCP Integration"]
        direction LR
        MemoryMCP["Memory Brain<br/>MCP"]
        MySQLMCP["MySQL MCP<br/>(Career)"]
        MongoMCP["MongoDB<br/>MCP"]
        FileMCP["Filesystem<br/>MCP"]
    end

    subgraph Brain["Memory Brain"]
        SQLite[("SQLite<br/>848+ Records<br/>Agent Coordination")]
    end

    subgraph Data["Data Sources"]
        direction LR
        UCI[("UCI HAR<br/>10k+ Samples")]
        Federal[("Federal<br/>Economic")]
        MySQLDB[("MySQL<br/>Career DB")]
        MongoDB[("MongoDB<br/>Extended")]
        Portfolio[("Portfolio &<br/>Resume")]
    end

    subgraph Projects["Strategic Innovation Pillars"]
        direction LR
        Motion["MotionInsight"]
        Game["Game Theory"]
        Career["Career Intel"]
    end

    subgraph Apps["Deployed Applications"]
        direction LR
        MotionApp["MotionInsight"]
        ForecastApp["ForecastPro"]
        JobHub["Job Hunting"]
    end

    AgentCmd --> Agents
    AgentCmd --> MCPLayer

    AutoAgents --> SQLite
    JobSwarm --> SQLite
    MLToolkit --> SQLite
    LinkedInAgent --> SQLite

    MemoryMCP --> SQLite
    MySQLMCP --> MySQLDB
    MongoMCP --> MongoDB
    FileMCP --> Portfolio

    SQLite --> Motion
    SQLite --> Career

    UCI --> Motion
    Federal --> Game
    MySQLDB --> Career
    MongoDB --> Career
    Portfolio --> Career

    Motion --> MotionApp
    Game --> ForecastApp
    Career --> JobHub

    classDef infra fill:#424242,stroke:#212121,color:#fff
    classDef mcp fill:#7b1fa2,stroke:#6a1b9a,color:#fff
    classDef brain fill:#e91e63,stroke:#c2185b,color:#fff
    classDef agents fill:#ff6f00,stroke:#e65100,color:#fff
    classDef data fill:#0277bd,stroke:#01579b,color:#fff
    classDef projects fill:#7b1fa2,stroke:#6a1b9a,color:#fff
    classDef apps fill:#00695c,stroke:#004d40,color:#fff

    class Ollama,AgentCmd infra
    class MemoryMCP,MySQLMCP,MongoMCP,FileMCP mcp
    class SQLite brain
    class AutoAgents,JobSwarm,MLToolkit,LinkedInAgent agents
    class UCI,Federal,MySQLDB,MongoDB,Portfolio data
    class Motion,Game,Career projects
    class MotionApp,ForecastApp,JobHub apps
```

### Architecture Highlights

| Layer | Components | Purpose |
|-------|------------|---------|
| **🧠 Memory Brain** | SQLite (848+ records) | Central coordination hub for all agents |
| **🔌 MCP Integration** | 4 MCP servers | Claude access to MySQL, MongoDB, SQLite, Filesystem |
| **🤖 Autonomous Agents** | 21 specialized agents | Job hunting, ML/AI toolkit, automation, LinkedIn |
| **🗄️ Data Foundation** | 5 databases | UCI HAR, Federal Economic, Career DB, Portfolio |
| **🚀 Strategic Pillars** | 3 flagship projects | MotionInsight, Game Theory, Career Intelligence |

---

## ⭐ Flagship Projects

| System | Key Metric | Tech Stack | Status |
|--------|------------|------------|--------|
| ✨ **Career Intelligence System** | **92.3% semantic match** · built ground-up | MySQL (architecture + conceptual design), MongoDB, SQLite, Sentence Transformers, Streamlit | Active |
| 🤖 **ARIA** | **Autonomous multi-agent workflow** built on CIS | Python, Memory Brain, Job APIs, Email Automation | Active |
| 🧠 **Memory Brain** | **848+ records, 21 agents** | SQLite, MCP Protocol, Ollama | Active |
| 🤗 **MENTOR (Mistral-7B)** | **Fine-tuned bilingual EN/ES tutor** · published on Hugging Face | Mistral-7B, PBL pedagogy, fine-tuning | Published |
| 💸 **Multi-Agent LLM Router** | **90% inference cost reduction** | Python, local-first LLMs, complexity-based routing | Active |
| 📊 **LinkedIn Brand Analyzer** | NLP + Network Analysis | SpaCy, NetworkX, PyVis | Active |

---

## 🎯 Featured Projects

### 🏆 Career Intelligence System
> **92.3% semantic matching accuracy** | Built ground-up: database architecture → semantic layer → UI

An intelligent career management platform that matches job opportunities to candidate profiles using advanced NLP and semantic similarity. I designed and built every layer: MySQL conceptual + physical database design, MongoDB for extended candidate data, SQLite for coordination, semantic matching pipeline, and the Streamlit interface. Features automated resume tailoring, cover letter generation, and application tracking.

**Tech:** Python, MySQL (architecture + conceptual design), MongoDB, SQLite, Sentence Transformers, Streamlit, MCP Integration

[View Project](https://github.com/rosalinatorres888/career-intelligence-system)

---

### 🧠 Memory Brain: Multi-Agent Coordination
> **848+ records** | **21 autonomous agents** | Central orchestration layer

A unified coordination system that connects all my AI agents through a shared SQLite database. Implements Model Context Protocol (MCP) servers for seamless Claude integration across MySQL, MongoDB, and filesystem resources.

**Tech:** Python, SQLite, MCP Protocol, Ollama, Local LLMs

[View Project](https://github.com/rosalinatorres888/memory-brain)

---

### 📊 LinkedIn Brand Analyzer
> NLP-powered brand sentiment & network analysis

Analyzes LinkedIn engagement patterns using NLP (SpaCy, VADER) for sentiment analysis and NetworkX for graph-based network clustering. Identifies which content topics drive high-value engagement from recruiters and industry connections.

**Tech:** Python, SpaCy, NetworkX, PyVis, BERTopic, Streamlit

[View Project](https://github.com/rosalinatorres888/linkedin-brand-analyzer)

---

### 🤖 ARIA — Autonomous Career Assistant
> Multi-agent autonomous workflow built on top of the Career Intelligence System

Where CIS provides the foundational data + semantic-matching platform, ARIA adds the autonomous agent layer: continuously monitoring job boards, matching opportunities against the CIS knowledge base, generating tailored outreach, and triggering notifications without human intervention. Integrates with Memory Brain for coordinated state across runs.

**Tech:** Python, Memory Brain coordination, Job APIs, Email Automation, agent orchestration

[View Project](https://github.com/rosalinatorres888/aria-career-assistant)

---

### 🤗 MENTOR — Fine-Tuned Mistral-7B Teaching Assistant
> Bilingual (EN/ES) project-based learning tutor · published on Hugging Face

A fine-tuned Mistral-7B model designed for project-based learning pedagogy: teaches by asking, not lecturing. Responds in both English and Spanish. Built around the principle that the best teachers help learners discover answers themselves.

**Tech:** Mistral-7B, fine-tuning, PBL pedagogy, bilingual instruction tuning

[View on Hugging Face](https://huggingface.co/spanishrose/mentor-mistral-7b-pbl)

---

### 💸 Multi-Agent LLM Router
> 90% inference cost reduction via local-first, complexity-based routing

Intelligent LLM routing system that classifies query complexity and routes accordingly: simple queries stay local (Ollama), complex queries escalate to cloud models. Reduces overall inference spend by ~90% without sacrificing output quality on harder tasks.

**Tech:** Python, local-first LLMs (Ollama), complexity classification, fallback architecture

[View Project](https://github.com/rosalinatorres888/multi-agent-llm-router)

---

### 📊 Additional Projects

| Project | Impact | Tech Stack | Links |
|---------|--------|------------|-------|
| **MotionInsight** | Entropy-Complexity Analysis | Python, Signal Processing, Streamlit | [Code](https://github.com/rosalinatorres888/human-activity-entropy) |
| **Democracy Clustering** | 195 Countries · 0.89 Silhouette | R, K-means, PCA | [Code](https://github.com/rosalinatorres888/democracy-clustering-analysis) |
| **Crypto ML Pipeline** | 85% Prediction Accuracy | TensorFlow, Airflow, PostgreSQL | [Code](https://github.com/rosalinatorres888/crypto-ml-pipeline) |
| **Network Intelligence** | 0.73 Correlation Discovery | NetworkX, NLP, Graph Analysis | [Code](https://github.com/rosalinatorres888/Advanced_Network_Intelligence) |

---

## 🚀 Currently

- 🎓 MS Data Analytics Engineering @ Northeastern (GPA: 3.7, Expected August 2026)
- 🤖 Building autonomous AI agents with Memory Brain coordination
- 🔌 Implementing MCP servers for AI-database integration
- 🎯 Career Intelligence System achieving 92.3% semantic matching
- 📝 Graduate Student Ambassador, College of Engineering

**Available for ML/AI Engineering roles**
- 📍 Open to relocation | Remote-friendly
- 💼 Authorized to work in the US
- 📅 Can start: Immediately

---

## 🛠️ Tech Stack

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ML/AI Frameworks
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Databases & Infrastructure
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Cloud & Deployment
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=rosalinatorres888&show_icons=true&theme=radical&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rosalinatorres888&layout=compact&theme=radical&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=rosalinatorres888&theme=radical&hide_border=true)

---

## 💼 Experience

**AI Data Trainer (Bilingual)** @ Alignerr *(2023 - Present)*
- Evaluating LLM responses for factual accuracy, bias detection, and ethical integrity
- Working with generative AI alignment tools and human-in-the-loop ML systems

**Regional Manager, Channel & Enterprise Sales (LATAM)** @ Collibra *(2018 - 2021)*
- Led data intelligence solution sales generating $2.4M+ revenue
- Enterprise data governance, catalog, and AI governance frameworks

**Regional Sales Manager** @ Zerto *(2015 - 2019)*
- Exceeded quotas up to 257%, Global Sales of the Year
- Cloud data protection and disaster recovery platforms

**Business Development Executive** @ Oracle Corp *(Earlier Career)*
- Exceeded targets by 135%, Top Gun and Fast Start awards
- Database management, cloud infrastructure, middleware solutions

---

## 🎓 Education

**Northeastern University** | M.S. Data Analytics Engineering | Boston, MA | Expected August 2026
- 3.7 GPA | Graduate Student Ambassador, College of Engineering
- Focus: Machine Learning, AI Systems, Production Pipelines

**Bridgewater State University** | B.S. Economics | Boston, MA

**University of Limerick** | Study Abroad | Ireland
- European Union Economics & Monetary Policy Analysis

---

## 📜 Certifications

- AWS Cloud Practitioner Certified
- Google Data Analytics Professional
- Generative AI Specialization Learning Path

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rosalina-torres)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://rosalina.sites.northeastern.edu)
[![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/spanishrose)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:torres.ros@northeastern.edu)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rosalinatorres888)

---

**💡 Open to collaboration on ML/AI projects and full-time opportunities!**

*Last updated: May 2026*
