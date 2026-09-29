<h1 align="center">Hi there 👋, I'm Lindsey!</h1>

<p align="center">I build backend services and the infrastructure around them, mostly on AWS.</p>

---

🌟 **About Me**

- 🎓 M.S. in Computer Science, Northeastern University (2024-2027)
- 💼 SDE Intern, **Amazon Web Services** — AWS Quick team, New York (Summer 2026)
- 💼 Software Engineer Intern, **EasyScaleCloud** — S3 data lake with Lambda, Step Functions and Delta Lake (Summer 2025)
- 💼 Software Engineer Intern, **Terra Byte X** — Python/FastAPI microservices on AWS (2024)
- 🇺🇸 U.S. Permanent Resident — no visa sponsorship required
- 🔍 **Looking for Summer 2027 SWE/SDE internships and New Grad roles** in backend, full-stack, cloud, or platform engineering

This past summer at AWS I owned a feature end to end: publishing AI-generated dashboards out of a private workspace to public URLs. Most of the work was the boundary rather than the feature, deciding what to freeze, what to strip, and what should never leave the workspace at all.

---

🛠️ **Languages & Tools**

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
</p>

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch"/>
</p>

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xOS4zNSAxMC4wNEE3LjQ5IDcuNDkgMCAwIDAgMTIgNEM5LjExIDQgNi42IDUuNjQgNS4zNSA4LjA0QTUuOTk0IDUuOTk0IDAgMCAwIDAgMTRjMCAzLjMxIDIuNjkgNiA2IDZoMTNjMi43NiAwIDUtMi4yNCA1LTUgMC0yLjY0LTIuMDUtNC43OC00LjY1LTQuOTZ6Ii8%2BPC9zdmc%2B" alt="AWS"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
</p>

---

🚀 **Things I've Built**

- **[video-processing-pipeline](https://github.com/LindseyZ1205/video-processing-pipeline)** — Spring Boot service that transcribes audio and video uploads asynchronously: presigned S3 uploads, S3 events over SQS, and an idempotent worker with DynamoDB leases, retries and a dead-letter queue. Integration tests run the whole flow against LocalStack in CI and check that an event delivered three times is transcribed exactly once
- **[6.5840-distributed-systems](https://github.com/LindseyZ1205/6.5840-distributed-systems)** — Raft consensus in Go, a self-study implementation of MIT 6.5840 Lab 3: leader election, log replication, crash recovery and snapshots. Passes all 28 of the course's tests under the race detector in CI
- **[job-search-scanner](https://github.com/LindseyZ1205/job-search-scanner)** — scheduled pipeline that pulls open roles from five public job-board APIs, deduplicates against prior runs, filters by eligibility, and renders one-page ATS-parseable resumes
- **[careplan-project](https://github.com/LindseyZ1205/careplan-project)** — nursing care plan management system

---

🌱 **Open Source**

- **Spring Boot** — [fixed `PeriodStyle` throwing when formatting a zero period in weeks](https://github.com/spring-projects/spring-boot/pull/51892) (merged for 4.0.9)
- **Temporal Python SDK** — [restored frozensets when decoding typed JSON payloads](https://github.com/temporalio/sdk-python/pull/1898) (merged)
- In review:
  - **Testcontainers for Java** — [fix a deadline overflow in `WaitingConsumer.waitUntilEnd` for very large timeouts](https://github.com/testcontainers/testcontainers-java/pull/12093)
  - **Micrometer** — [stop `HttpSender` from trimming HTTP Basic authentication passwords](https://github.com/micrometer-metrics/micrometer/pull/8015)
  - **Eclipse Paho MQTT Python client** — [stop the `publish` and `subscribe` helpers from mutating the caller's TLS options](https://github.com/eclipse-paho/paho.mqtt.python/pull/959)
  - **APScheduler** — [fix `IntervalTrigger` elapsed time across DST transitions](https://github.com/agronholm/apscheduler/pull/1145)
  - **LanceDB** — [preserve the Arrow schema when merging reranker scores](https://github.com/lancedb/lancedb/pull/4332)
  - **Haystack** — [sort `SentenceWindowRetriever` context before merging text](https://github.com/deepset-ai/haystack/pull/12976)
  - **LlamaIndex** — [stop copying `text_key` into node metadata on the Qdrant legacy path](https://github.com/run-llama/llama_index/pull/23265)
  - **Sentence Transformers** — [fix `bfloat16` crashes in `encode(precision=...)` and `quantize_embeddings`](https://github.com/huggingface/sentence-transformers/pull/4089)
  - **Docling** — [keep `dt`/`dd` groups wrapped in `div` elements in HTML description lists](https://github.com/docling-project/docling/pull/4390)

---

💡 **How I Work**

I use AI tools heavily to get productive in an unfamiliar codebase in days rather than weeks. Then I do the part they will not do for you: making the result something a human can read, test, and audit.

---

📫 **How to Reach Me**

<p>
  <a href="mailto:yingzizhang1205@gmail.com"><img src="https://img.shields.io/badge/Email-yingzizhang1205%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email: yingzizhang1205@gmail.com"/></a>
  <a href="https://www.linkedin.com/in/yingzi-zhang-sde/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat" alt="LinkedIn"/></a>
  <a href="https://lindseyz1205.github.io"><img src="https://img.shields.io/badge/Website-222222?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPHBhdGggZD0iTTIgMTJoMjAiLz48cGF0aCBkPSJNMTIgMmExNS4zIDE1LjMgMCAwIDEgNCAxMCAxNS4zIDE1LjMgMCAwIDEtNCAxMCAxNS4zIDE1LjMgMCAwIDEtNC0xMCAxNS4zIDE1LjMgMCAwIDEgNC0xMHoiLz48L3N2Zz4%3D" alt="Website"/></a>
</p>
