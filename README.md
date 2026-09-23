# 👋 Hello, I'm Amol Gode
### Backend Engineer @ Zelthy | 4+ Years | Python · Django · Go · Kafka · gRPC · Docker
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:contacting.amol@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/amol-gode)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-600%2B_Problems-darkgreen?style=for-the-badge&logo=geeksforgeeks)](https://www.geeksforgeeks.org/user/17amolgode/)
[![LeetCode](https://img.shields.io/badge/LeetCode-250%2B_Problems-orange?style=for-the-badge&logo=leetcode)](https://leetcode.com/u/17amolgode/)
[![CCA-F](https://img.shields.io/badge/Anthropic-Claude_Certified_Architect_(Foundations)-8A2BE2?style=for-the-badge&logo=anthropic)](https://drive.google.com/file/d/1pjx0T1hpeb5wdRdvVzwnwutD-NZL7fnF/view)

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00F700&width=500&lines=Backend+Engineer+%7C+Django+%7C+Go+%7C+gRPC;Kafka+%7C+Event-Driven+Systems+%7C+Docker;REST+APIs+%7C+PostgreSQL+%7C+Celery;AI+Agents+%7C+Claude+Certified+Architect;800%2B+DSA+Problems+%7C+GFG+%2B+LeetCode" />
</p>

---

## 🚀 About Me
- **Backend Engineer** with **4+ years** of production experience in **Python, Django, and DRF** — building healthcare / Patient Support Program platforms at scale.
- Built **data lake infrastructure** using **Kafka + Debezium (CDC)**, handling **5K+ events/sec at peak**, and a **Celery + Redis**-backed notification system handling **7K+ notifications/day** across email, SMS, and push.
- Hands-on with **REST API design**, **digital onboarding** (eKYC, Aadhaar e-Sign, document verification), and **large-scale data workflows**.
- **Claude Certified Architect – Foundations (CCA-F)** — built **Claude Agent Studio**, a configurable agent control-plane with a full agentic tool-use loop, centralized tool registry, and per-run observability.
- Built a **Distributed Unique ID Generator** — Snowflake algorithm in Go + gRPC, **338 req/sec**, **p95 175ms**, **0.00% error** under 1,000 concurrent users.
- Solved **800+ DSA problems** across GeeksForGeeks (600+) and LeetCode (250+).

---

## 🛠️ Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,go,postgresql,docker,redis,react,git,github,aws,kafka,kubernetes" />
</p>

**Languages:** Python, Go, JavaScript, SQL  
**Frameworks:** Django, Django REST Framework, Celery, React  
**Databases & Messaging:** PostgreSQL, Redis, MySQL, Kafka  
**Tools & AI:** Docker, Kubernetes, gRPC, Protobuf, Prometheus, Grafana, AWS, FCM, Anthropic SDK

---

## 📌 Featured Projects

### 🔀 [Order Saga Event-Driven System](https://github.com/AmolGode/order-saga-event-system)
`Kafka` `Python` `Django` `Golang` `PostgreSQL` `Docker` — [HLD Diagram](https://github.com/AmolGode/order-saga-event-system/blob/main/HLD.png)
- Built a **Kafka-based saga pattern** system (order placement → inventory reservation → payment processing → confirmation) with independent workers coordinated via topics and **compensating events** on failure.
- Each of the 4 services (order, inventory, payment, analytics) runs its own **Django API** and **Go-based Kafka-consumer worker** with an isolated PostgreSQL database; added **PgBouncer** in front of the order DB for transaction-mode connection pooling.
- Instrumented Kafka consumer lag via a **Prometheus exporter** with **Grafana** dashboards.

### 🤖 [Claude Agent Studio](https://github.com/AmolGode/Claude-Agent-Studio)
`Django` `DRF` `PostgreSQL` `React` `Anthropic SDK`
- **Agent control-plane** — configure Claude agents (model, system prompt, tool set) at runtime via UI; no code changes to spin up a new agent.
- Implemented the full **agentic tool-use loop** (Anthropic SDK) with a centralized `@register_tool` registry that **auto-generates JSON schemas** from type hints.
- Real **DB-backed tool execution** (orders, customers, refunds) plus per-run **token + latency observability** captured through a single tool runner.

### ⚡ [Distributed Unique ID Generator](https://github.com/AmolGode/distributed-id-generator)
`Go` `gRPC` `Django` `Prometheus` `Grafana` `Docker` `k6`
- Implemented **Twitter's Snowflake algorithm** in Go — generating **4,096 collision-free, time-sortable IDs/ms** with zero database coordination.
- Achieved **338 req/sec** sustained throughput, **p95 latency 175ms** under **1,000 concurrent users** at **0.00% error rate** (k6 load test).
- Built an in-memory **rate limiter** (fixed window, 10 req/5s per user) and full observability with **Prometheus + Grafana** — 6 auto-provisioned dashboard panels.

### 🔧 Other Projects
- **[Pollster](https://github.com/AmolGode/Pollster)** — `Django` `Celery` `MySQL` — poll generation and voting platform with Celery-automated poll expiry after 24 hours.
- **[Secure Pass Keeper](https://github.com/AmolGode/Secure-Pass-Keeper-Django-React)** — `DRF` `PostgreSQL` `React` — credential manager with end-to-end encryption and token authentication.

---

## 🏆 Achievements
- 🎓 Earned the **Claude Certified Architect – Foundations (CCA-F)** certification by **Anthropic** — agentic systems, tool use, and production AI architecture. [Certificate](https://drive.google.com/file/d/1pjx0T1hpeb5wdRdvVzwnwutD-NZL7fnF/view)
- Solved **800+ DSA problems** across [GeeksForGeeks](https://www.geeksforgeeks.org/user/17amolgode/) (**600+**) and [LeetCode](https://leetcode.com/u/17amolgode/) (**250+**).
- Built Aadhaar **eKYC + e-Sign** patient-onboarding flows processing **15K+ verifications/month** at Zelthy.
- Built **Kafka + Debezium** data lake infrastructure handling **5K+ events/sec at peak**, and a **Celery + Redis** notification system handling **7K+ notifications/day**.
