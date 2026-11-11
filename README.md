# Ahmad Husain

**Backend & Full-Stack Engineer** — Java, Spring Boot, Vaadin, and Point-of-Sale systems.

I design and build production-grade POS and ordering platforms: microservices backends,
server-side Java UIs, AI-assisted ordering, and native clients for iPad, Android, and desktop.

---

## Tech Stack

![Java](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x_|_4.x-6DB33F?logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud_Gateway-6DB33F?logo=spring&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?logo=spring&logoColor=white)
![Vaadin](https://img.shields.io/badge/Vaadin-24_|_25-00B4F0?logo=vaadin&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?logo=mybatis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/C++/Qt-00599C?logo=cplusplus&logoColor=white)

**Backend:** Java 21, Spring Boot, Spring WebFlux, Spring Security, JWT, MyBatis, MySQL, Flyway, Apache Commons DBCP2, OpenAPI/Swagger, GraalVM native
**Frontend:** Vaadin Flow (Lumo themes), React/Vite dev bundle, server-side Java UI
**AI:** Spring AI, OpenAI-compatible LLMs, SSE streaming, RAG-style grounding
**Architecture:** Microservices, API Gateway, Hexagonal (Ports & Adapters), DDD-lite domain modeling
**Clients:** Swift/iOS (iPad), Kotlin/Android, C++/Qt desktop

---

## Featured Projects

### POS Harmoni — Restaurant Point-of-Sale Platform
A complete, multi-service POS ecosystem for restaurant operations, built as independent
Spring Boot services behind a single API gateway.

| Service | Responsibility | Stack |
| --- | --- | --- |
| `gateway` | Single entry point, routing, CORS, JWT resource server | Spring Cloud Gateway, Spring Security |
| `authentication` | Users, roles, JWT issuance | Spring Boot, MyBatis, MySQL |
| `order` | Orders, configuration, reporting | Spring Boot, MyBatis, Flyway |
| `menu` | Menu, categories, products, SKUs, pricing tiers | Spring Boot, MyBatis |
| `customer` | Customers, sessions, messages — **Hexagonal Architecture** | Spring Boot, MyBatis, Flyway |
| `dashboard` | Admin UI for menu & configuration | Vaadin 24, Spring WebFlux |
| `ai-order` | AI chat ordering frontend | Vaadin 25, Spring WebFlux, SSE |
| `ipad-order` | Native iPad ordering client | Swift / Xcode |
| `android-order` | Native Android ordering client | Kotlin |
| `desktop-order` | Desktop POS client | C++ / Qt |

**Highlights**
- Clean **Hexagonal Architecture** in the customer service: pure domain, use-case ports, and MyBatis adapters with no framework leakage into the domain.
- **Soft-delete** strategy for customer conversations to preserve business history and FK integrity.
- **Flyway**-managed schema migrations and centralized DB credentials.
- **Streaming AI ordering** over Server-Sent Events, fully decoupled from the backend via HTTP clients.

### AI Medical Chatbot — Closed-Domain Assistant
A grounded medical-information chatbot for PlacidWay's ITC Immunity Therapy Center.

- **Vaadin 25 + Spring Boot 4 + Spring AI** with `@Push` streaming replies.
- Closed-domain grounding on 7 approved pages — refuses to invent prices, clinics, doctors, or medical facts.
- Per-session conversation memory (last 20 messages), Markdown rendering, and honest "I don't know" fallbacks.
- Replies in the user's language, including refusals.

---

## What I Care About

- **Clear boundaries** — domain code that knows nothing about Spring, MyBatis, or JSON.
- **Honest systems** — services that fail loudly and document their limitations instead of hiding them.
- **Real clients** — the same backend serving web, iPad, Android, and desktop without duplication.
- **Maintainable UI** — server-side Vaadin where it removes an entire frontend stack.

---

## GitHub Stats

![Ahmad's GitHub stats](https://github-readme-stats.vercel.app/api?username=husainahmad&show_icons=true&hide_title=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=husainahmad&layout=compact&hide_title=true)

---

## Contact

- Email: [husainahmad@gmail.com](mailto:husainahmad@gmail.com)
- GitHub: [@husainahmad](https://github.com/husainahmad)
