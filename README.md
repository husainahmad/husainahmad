# Ahmad Husain

**Senior Software Engineer | Engineering Manager | AI & Automation Engineer**

Software engineer and architect with **22+ years** building enterprise applications, backend
systems, and software platforms. My core expertise is **Java, Golang, Spring Boot, microservices,
and system integration** — from mobile apps and enterprise platforms to restaurant ordering and
payment systems. I have led engineering teams and owned architecture across product, backend, and
DevOps. More recently I have been building **AI-based applications** with LLMs, Spring AI, RAG,
and AI agents.

Based in Indonesia.

---

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?logo=spring&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Vaadin](https://img.shields.io/badge/Vaadin-00B4F0?logo=vaadin&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)

**Languages:** Java (EE/SE), Golang, Kotlin, PHP, JavaScript, C#
**Frameworks:** Spring Boot, Spring MVC, Spring Security, Spring AI, Hibernate, MyBatis, JPA, Laravel
**AI:** LLM integration, RAG, AI agents, tool calling, Ollama
**Cloud & Infra:** AWS, GCP, Docker, Kubernetes, Jenkins, CI/CD
**Databases:** PostgreSQL, MySQL, Oracle, SQL Server, MongoDB
**Messaging & Caching:** RabbitMQ, Redis
**Testing & Monitoring:** Mockito, JMeter, SonarQube, Datadog, TDD

---

## Experience

**Senior Software Architect** — Hyperscal, PT SOD Indonesia · *Apr 2025 – Present*
Architecting cloud-native backend services on AWS; designing highly available REST APIs with
Golang, PostgreSQL, and Redis; establishing engineering standards and architecture guidelines.

**Senior Java Developer** — Aleph Labs, Indonesia · *May 2024 – Apr 2025*
Secure Spring Boot backend services for enterprise digital platforms; resilience with Redis and
Resilience4j; introduced TDD and SonarQube quality gates.

**Engineering Manager** — TabSquare PTE Ltd (Singapore, Remote) · *Aug 2023 – Mar 2024*
Led delivery for digital restaurant ordering and hospitality platforms; coordinated backend,
product, and QA; directed migration from legacy services to Kubernetes microservices.

**Principal Engineer / Platform Manager / Lead Backend Engineer** — TabSquare PTE Ltd · *2017 – 2023*
Designed backend architecture for restaurant ordering, payment, loyalty, and operational
platforms; led monolith-to-microservices migration on Kubernetes; built scalable REST APIs for
high transaction volumes; improved observability, deployment automation, and reliability.

**Earlier career** — Mobile Developer Team Lead (Seekmi Global Services), Lead Engineer
(Samsung R&D Indonesia), Technical Lead (Imede Indonesia), Senior Developer & Mobile Engineer
roles (2003–2010) — backend systems, mobile platforms (Android, BlackBerry), and enterprise apps.

---

## Featured Projects

### POS Harmoni — POS & AI Ordering Assistant
An independent POS platform for restaurant operations: order management, menu management,
payments, promotions, and inventory — with an AI ordering assistant built on Spring AI and LLMs.

- Integrated LLMs with backend services using **Spring AI**.
- Implemented **tool calling** so the assistant retrieves real product and SKU data through APIs
  instead of inventing it.
- Explored **RAG** to give the assistant relevant business context.
- Connected ordering, menu, and promotion services through REST APIs.
- Designed backend workflows for order processing, product customization, pricing, and payments.

The platform is split into independent Spring Boot services behind a single API gateway, with
Vaadin admin/ordering UIs and native iPad, Android, and desktop clients.

| Service | Responsibility |
| --- | --- |
| `gateway` | Single entry point, routing, CORS, JWT resource server |
| `authentication` | Users, roles, JWT issuance |
| `order` | Orders, configuration, reporting |
| `menu` | Menu, categories, products, SKUs, pricing tiers |
| `customer` | Customers, sessions, messages — Hexagonal Architecture |
| `dashboard` | Admin UI (Vaadin) |
| `ai-order` | AI chat ordering frontend (Vaadin, SSE streaming) |
| `ipad-order` / `android-order` / `desktop-order` | Native clients (Swift, Kotlin, C++/Qt) |

**Technology:** Java, Spring Boot, Spring AI, Ollama, LLMs, MyBatis, MySQL, REST APIs, Microservices.

### AI Medical Chatbot — Closed-Domain Assistant
A grounded medical-information chatbot built with **Vaadin, Spring Boot, and Spring AI**.

- Closed-domain grounding on a fixed set of approved pages — refuses to invent prices, clinics,
  doctors, or medical facts.
- Streaming replies with `@Push`, per-session conversation memory, and Markdown rendering.
- Replies in the user's language, including honest "I don't know" fallbacks.

---

## What I Care About

- **Practical architecture** — systems that fit how the business actually operates.
- **Clear boundaries** — domain code that knows nothing about frameworks or transport.
- **Reliability at scale** — observability, automation, and predictable deployments.
- **Honest systems** — services that fail loudly and document their limitations.

---

## GitHub Stats

![Ahmad's GitHub stats](https://github-readme-stats.vercel.app/api?username=husainahmad&show_icons=true&hide_title=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=husainahmad&layout=compact&hide_title=true)

---

## Contact

- Email: [husainahmad@gmail.com](mailto:husainahmad@gmail.com)
- LinkedIn: [ahmad-husain-5251248](https://www.linkedin.com/in/ahmad-husain-5251248)
- GitHub: [@husainahmad](https://github.com/husainahmad)
