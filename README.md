## Yingzi (Lindsey) Zhang

M.S. Computer Science at Northeastern University. I build backend services and the infrastructure around them, mostly on AWS.

This past summer I was an SDE intern on the **AWS Quick** team in New York, where I owned a feature end to end: publishing AI-generated dashboards out of a private workspace to public URLs. Most of the work was the boundary rather than the feature, deciding what to freeze, what to strip, and what should never leave the workspace at all.

**Looking for Summer 2027 SWE/SDE internships and New Grad roles** in backend, full-stack, cloud, or platform engineering.

**Languages:** Python · Java · Go · TypeScript

### Things I've built

- **[6.5840-distributed-systems](https://github.com/LindseyZ1205/6.5840-distributed-systems)** — Raft consensus in Go, a self-study implementation of MIT 6.5840 Lab 3: leader election, log replication, crash recovery and snapshots. Passes all 28 of the course's tests under the race detector in CI
- **[job-search-scanner](https://github.com/LindseyZ1205/job-search-scanner)** — scheduled pipeline that pulls open roles from five public job-board APIs, deduplicates against prior runs, filters by eligibility, and renders one-page ATS-parseable resumes
- **[careplan-project](https://github.com/LindseyZ1205/careplan-project)** — nursing care plan management system

### Open source

- **Spring Boot** — [fixed `PeriodStyle` throwing when formatting a zero period in weeks](https://github.com/spring-projects/spring-boot/pull/51892) (merged for 4.0.9)
- In review:
  - **Temporal Python SDK** — [restore frozensets when decoding typed JSON payloads](https://github.com/temporalio/sdk-python/pull/1898)
  - **LanceDB** — [preserve the Arrow schema when merging reranker scores](https://github.com/lancedb/lancedb/pull/4332)
  - **Haystack** — [sort `SentenceWindowRetriever` context before merging text](https://github.com/deepset-ai/haystack/pull/12976)
  - **LlamaIndex** — [stop copying `text_key` into node metadata on the Qdrant legacy path](https://github.com/run-llama/llama_index/pull/23265)
  - **Sentence Transformers** — [fix `bfloat16` crashes in `encode(precision=...)` and `quantize_embeddings`](https://github.com/huggingface/sentence-transformers/pull/4089)
  - **Docling** — [keep `dt`/`dd` groups wrapped in `div` elements in HTML description lists](https://github.com/docling-project/docling/pull/4390)

### How I work

I use AI tools heavily to get productive in an unfamiliar codebase in days rather than weeks. Then I do the part they will not do for you: making the result something a human can read, test, and audit.

### Reach me

- yingzizhang1205@gmail.com
- [LinkedIn](https://www.linkedin.com/in/yingzi-zhang-sde/)
- [lindseyz1205.github.io](https://lindseyz1205.github.io) — personal site and engineering notes
