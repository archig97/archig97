# 👋 Hi, I’m Archismita Ghosh

**Software Engineer | Backend & Full-Stack Developer | AI/ML Enthusiast**

📍 Raleigh–Durham–Chapel Hill, NC  
🎓 M.S. in Computer Science — North Carolina State University  
💼 Former Software Engineer @ LTIMindtree  

🔗 [LinkedIn](https://linkedin.com/in/archismitaghosh)  
🔗 [GitHub](https://github.com/archig97)

---

## 👩‍💻 About Me

I am a software engineer with experience building **scalable backend systems, APIs, and AI-powered applications**.  
My work focuses on **clean architecture, performance optimization, and reliable system design**.

Currently pursuing my Master’s in Computer Science at NC State, where I work on projects involving **distributed systems, AI/ML, and cloud-native development**.

---

## 🧠 Technical Skills

### Programming Languages
- Java, Python, JavaScript

### Backend & APIs
- Spring Boot, Node.js  
- REST APIs, SOAP  
- JSON, XML  

### Frontend
- React, Redux  
- HTML, CSS, jQuery  

### Databases
- MySQL, MongoDB, NoSQL

### Cloud & DevOps
- AWS, CloudWatch  
- Docker, Jenkins  
- GitHub, Bitbucket  

### Security
- JWT, OAuth, OpenID  
- Role-Based Access Control  

### Development Practices
- Agile & Scrum  
- TDD & Automated Testing  
- System Design  
- Performance Optimization  

---

## 💼 Experience

### **Software Engineer — LTIMindtree**  
*June 2022 – July 2024*

- Developed and maintained backend services for financial and customer communication systems using **Java and Spring Boot**.
- Designed RESTful APIs for transaction handling, reporting, and preference management.
- Automated backend workflows, reducing manual effort and improving processing efficiency by ~30%.
- Optimized database queries and indexing to improve API performance.
- Implemented asynchronous background processing to improve system scalability.
- Debugged production issues using centralized logging and tracing.
- Built unit and integration tests to improve reliability and reduce regressions.

---

## 🚀 Projects

### 🔹 SnapBot – AI-Powered Learning Assistant
**Tech:** Python, LangChain, OpenAI, JavaScript, Redis

- Built an AI assistant to help students understand and debug Snap! programs.
- Designed a custom XML parser to extract structured data from Snap! projects.
- Implemented a **Retrieval-Augmented Generation (RAG)** pipeline for accurate responses.
- Added Redis-based session storage for multi-turn conversations.
- Built a web interface with real-time streaming responses.

---

### 🔹 Patient Management System
**Tech:** Java, Spring Boot, Kafka, Docker, AWS

- Developed backend microservices for patient and billing workflows.
- Implemented event-driven architecture using Kafka.
- Secured APIs with JWT-based authentication and role-based access control.
- Enabled inter-service communication using gRPC.
- Containerized services using Docker and simulated cloud infrastructure with AWS LocalStack.

---

### 🔹 BlackVault — Real-Time Graph-Based Fraud Detection System  
**Tech:** Python, FastAPI, Valkey (Key-Value Store), WebSockets, Docker  

- Built a real-time fraud detection system that analyzes financial transactions and flags suspicious accounts instantly. Instead of evaluating accounts individually, the system models the ecosystem as a **graph** — where accounts are nodes and transactions are connections (edges).

- Implemented **graph traversal using BFS (Breadth-First Search)** to measure how close an account is to known risky accounts and to propagate risk through connected networks. This helps detect coordinated fraud rings rather than isolated anomalies.

- Used **Valkey**, a high-performance **key–value datastore**, as the core database to manage all system state with very low latency. Different data structures were used for different purposes:
  - **Streams** → store incoming transactions in real time
  - **Hashes** → store account profiles and risk scores
  - **Sets** → represent graph relationships between accounts
  - **Sorted Sets** → maintain a live ranking of high-risk accounts
  - **Counters with expiration (TTL)** → track short-term behavioral patterns like transaction velocity and volume

- Designed the backend using **FastAPI** to support real-time ingestion, risk computation, and API responses for dashboards. State updates were kept deterministic using atomic operations in the datastore to avoid race conditions during concurrent transactions.

- Built a **transaction simulator** to generate realistic patterns such as rapid transfers, circular transactions, and suspicious bursts of activity, allowing the system to be tested under load.

- Exposed REST APIs and live data endpoints so a dashboard could visualize:
  - Risk scores
  - Suspicious accounts
  - Transaction activity
  - Behavioral metrics

- Containerized components with **Docker** to simplify setup and ensure consistent execution across environments.

This project demonstrates how core computer science concepts like **graphs, BFS traversal, and key–value storage** can be applied to solve real-world problems in fintech systems and fraud detection.

## 📌 Interests
- Backend & distributed systems  
- AI-powered developer tools  
- Scalable system design  
- Cloud-native applications  
- Fintech & healthcare platforms  

---

## 📫 Contact
- 📧 Email: archismitaghosh@yahoo.com  
- 🔗 LinkedIn: https://linkedin.com/in/archismitaghosh  
- 💻 GitHub: https://github.com/archig97  
<!--
**archig97/archig97** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
