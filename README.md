# Hi, I'm Anirudh 👋

**Backend & AI Engineer** building distributed systems and production-grade AI applications.

My foundation is backend engineering designing scalable microservices, event-driven systems, and reliable cloud services. I apply the same engineering discipline to LLM-powered applications, focusing on retrieval grounding, measurable evaluation, observability, and cost-aware deployments. I'm interested in building AI systems that are reliable enough to run in production, not just demos.

🎓 MS in Computer Science, Indiana University Bloomington (GPA 3.67) · BTech in Artificial Intelligence, SRM
🔬 Published in IEEE and Springer on deep learning and predictive modeling
📍 Bloomington, IN · Open to Software Engineer / Backend Engineer / AI Engineer roles

---

## 🛠️ Tech Stack

**Languages:** Python · Java · C/C++ · SQL · JavaScript

**Backend:** Spring Boot · Spring Data JPA · FastAPI · Flask · REST APIs · Microservices · Event-Driven Architecture

**AI / ML:** LLMs · LangChain · LangGraph · Agentic AI · Retrieval-Augmented Generation (RAG) · Prompt Engineering · scikit-learn · NLP

**Cloud & DevOps:** Docker · Kubernetes · Google Cloud Platform (Cloud Run, Firestore) · GitHub Actions · CI/CD

**Data & Messaging:** PostgreSQL · RabbitMQ · Qdrant · Firestore · SQLite · Hadoop

**Testing & Tooling:** JUnit · Mockito · Pytest · JaCoCo · Pydantic · Git · Maven

---

## 🚀 Featured Projects

### 🔍 PR Review Agent
*AI-powered GitHub pull request reviewer*
**Tech:** Python · Claude API · GitHub API · Pydantic

Retrieves dependency-aware code context from GitHub pull requests and generates schema-validated review findings as inline GitHub comments. Built a custom evaluation framework with a planted-bug dataset and automated scoring; on this benchmark the agent reached 100% recall, ~73% precision, and a 0.84 F1 score across security, reliability, and code-quality defects.

**Highlights**
- Retrieval-grounded reasoning over large codebases
- Agentic workflow with structured outputs
- Evaluation-driven development using measurable benchmarks

🔗 **Repository:** https://github.com/AnirudhOO7/pr_review_agent

---

### 🏨 Room Reservation Microservice
*Event-driven distributed booking system*
**Tech:** Spring Boot · RabbitMQ · PostgreSQL · Kubernetes

Built the Reservation Service within a microservice-based booking platform (user, room, reservation, and edge/gateway services). Validates bookings against the user and room services over HTTP, prevents double-bookings via an overlap query, enforces role-based booking policy (time limits, faculty-only rooms, booking windows), drives a PENDING → APPROVED/REJECTED/CANCELLED approval lifecycle across 11 REST endpoints, and publishes reservation events to RabbitMQ for downstream notification. Deployed on Kubernetes with PostgreSQL.

**Highlights**
- Event-driven microservice integrating with other services over a message bus
- Conflict detection and role-based booking rules
- Approval lifecycle, RabbitMQ events, and Kubernetes deployment

🔗 **Repository:** https://github.com/RoomReservationSystem/reservation-service

---

### 🧠 Self-Corrective RAG Agent
*Reflection-based Retrieval-Augmented Generation system*
**Tech:** FastAPI · LangChain · Qdrant · Hugging Face · Claude

Built a RAG system that evaluates retrieved context, identifies missing information, performs targeted re-retrieval, and generates responses only after sufficient grounding. Designed with an abstract vector-store interface, source-cited answers, and unit tests across the ingestion and retrieval pipeline.

**Highlights**
- Reflection-based retrieval loop
- Modular RAG architecture
- Cited answers and tested ingestion/retrieval pipeline

🔗 **Repository:** https://github.com/AnirudhOO7/Personal_knowledge_assistant

---

### 📰 Distributed News Aggregator
*Concurrent news ingestion and NLP pipeline*
**Tech:** GCP Cloud Run · Firestore · Flask · ThreadPoolExecutor

Developed a distributed news ingestion system processing over 500 headlines daily, reducing collection time by 75% through concurrent execution. Built an NLP pipeline for sentiment analysis and rule-based categorization, exposed through a secure REST API with authentication and pagination.

**Highlights**
- Concurrent data ingestion
- Cloud-native deployment on Google Cloud
- Secure REST API design

🔗 **Repository:** 

---

## 📈 Currently Building

- 🤖 AI-powered developer productivity tools
- ⚙️ Production-ready backend microservices
- 📚 Evaluation frameworks for LLM applications
- 🔍 Retrieval-grounded AI systems

---

## 📚 Publications

- **[A Survey on Predictive Modelling for Diverse Climate Conditions and Heavy Rainfall](https://link.springer.com/chapter/10.1007/978-981-97-4152-6_18)**
  *Springer – Lecture Notes in Networks and Systems (LNNS)*, 2024
- **[Hyperspectral Image Classification via Modified Stable Prototypical Networks](https://doi.org/10.1109/ICSCSS60660.2024.10625598)**
  *IEEE International Conference*, 2024 — Proposed a few-shot learning framework achieving a 23% improvement with limited labeled data.

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anirudh-sukumaran)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:emailtoanirudhs@gmail.com)

📧 emailtoanirudhs@gmail.com  ·  🔗 [linkedin.com/in/anirudh-sukumaran](https://www.linkedin.com/in/anirudh-sukumaran)

---

Thanks for visiting! Feel free to explore my repositories or reach out to discuss backend engineering, distributed systems, or production AI.

<!-- Optional GitHub stats — uncomment once your project repos are public and active.
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AnirudhOO7&show_icons=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AnirudhOO7&layout=compact)
-->
