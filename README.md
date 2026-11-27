# Hi, I'm Augusto Souza 👋

### Senior Ruby on Rails Engineer · Backend, data & search · Rio de Janeiro, Brazil (UTC-3)

I build and modernize Rails applications that handle large public datasets: from a legacy Rails 4 monolith with ~13 million records to a brand-new Rails 8 app. I like the unglamorous work that makes software fast and reliable: finding the N+1 query, adding the right index, writing the test that catches the regression.

**Open to remote roles** (contractor or full-time) · fluent English · full overlap with US Eastern Time

[![LinkedIn](https://img.shields.io/badge/LinkedIn-augustodesouzacardoso-0A66C2?logo=linkedin)](https://www.linkedin.com/in/augustodesouzacardoso)
[![Email](https://img.shields.io/badge/Email-augustodesouzacardoso%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:augustodesouzacardoso@gmail.com)
[![RubyGems](https://img.shields.io/gem/v/rails-br.svg?label=rails-br)](https://rubygems.org/gems/rails-br)

---

## 🏢 What I do at work

**Full Stack Developer (Ruby on Rails)** at Cast Group, for the Public Prosecutor's Office of Goiás (MPGO), since 2022.
That code is private, so here is what it adds up to:

- **Transparency Portal:** legacy Rails 4 app with ~13M public records across PostgreSQL and Oracle and 140+ exportable reports. I'm its second-largest contributor since 2022 (635 commits, 430 merge requests, 331 releases). In 2026 the MPGO earned the Diamond Seal, the top tier of Brazil's National Public Transparency Program (PNTP).
- **Performance:** cut the slowest report from ~9 s to ~3 s (p90 18 s → 8 s) by removing N+1 queries, adding caching and parallel fetching, and replacing a `GROUP BY` with an indexed query.
- **Open Data API:** 96 REST endpoints in 10 categories, documented with Swagger (rswag), ~490 RSpec tests.
- **Rails 8 Intranet:** laid the foundation of the rebuild (auth, Pundit, layout, Docker) and wrote over half of its commits; 5,000+ users.
- **Data & search:** 7 PostgreSQL schemas + Oracle, versioned queries and stored procedures, monthly data loads; 67 of 98 Elasticsearch-indexed models.

---

## 🌟 Open source & projects

### 💎 [rails-br](https://github.com/AugustoPresto/rails-br) · published on [RubyGems](https://rubygems.org/gems/rails-br)

Brazilian helpers for Ruby and Rails: **CPF, CNPJ (including the new alphanumeric format), Pix keys and BR Code, currency and dates**. A modern successor to Brazilian Rails, archived since 2018.

- No monkey patching: immutable value objects, ActiveModel validators and attribute types (`:br_currency`, `:br_date`), money always in `BigDecimal`
- Follows the official specs: the Pix BR Code generator reproduces the Central Bank's example byte for byte
- CI across **Ruby 2.7–3.4 and Rails 6.0–8.0**; ~200 RSpec examples
- Tested inside real Rails apps on PostgreSQL and MySQL: 342 tests and 60,800 concurrent requests with no wrong response, plus a 1-million-record load test. That run caught two bugs, fixed in 0.3.0

`Ruby` `Rails` `ActiveModel` `RSpec` `Appraisal` `GitHub Actions` `Docker`

### 🤖 [DocChat](https://github.com/AugustoPresto/docchat) · [live demo](https://docchat-2byq.onrender.com/)

Chat with your PDFs: a full-stack RAG app that runs fully offline with Ollama or in the cloud with Groq/OpenAI.

- **Hybrid retrieval:** FAISS semantic search + BM25 keyword search merged with Reciprocal Rank Fusion. On a 469-page book it answered 8/12 test questions vs 5/12 with vectors alone, at ~4 ms per query
- Streaming answers, page citations, background indexing with live progress, no login
- Runs on weak machines: ONNX embeddings (no PyTorch); one free Render service for frontend + API
- CI with tests and lint for both backend and frontend

`Python` `FastAPI` `LangChain` `FAISS` `React` `Vite` `Docker`

### 📡 [Lead Streaming Service](https://github.com/AugustoPresto/lead-streaming-service)

Rails 7.1 API that ingests, scores and segments marketing lead events in real time.

`Rails` `Kafka/Redpanda` `PostgreSQL` `Elasticsearch` `ClickHouse` `Prometheus` `Sentry` `RSpec` `React`

### 📱 [FavelaZap](https://github.com/AugustoPresto/favelazap)

Mobile-first Progressive Web App built for low-bandwidth connections and affordable phones.

`Rails` `JavaScript` `PostgreSQL` `PWA`

---

## 🛠 Tech

**Backend:** Ruby · Ruby on Rails (4 → 8) · REST APIs · Sidekiq · Redis · Python / FastAPI
**Data & search:** PostgreSQL · Oracle (SQL, PL/SQL) · MySQL · Elasticsearch
**Testing:** RSpec · FactoryBot · WebMock · VCR · TDD
**DevOps:** Docker · GitHub Actions · GitLab · Render · Fly.io · Heroku
**Frontend:** JavaScript · React · HTML/CSS · Bootstrap
**Learning now:** AWS · TypeScript · AI agents and LLM evaluation

---

## 🎓 Background

Journalism (PUC-Rio) and an MBA in Digital Marketing (FGV) before code, so I write clearly: tickets, docs and pull requests people can follow. I spent 4 years as a Ruby on Rails teaching assistant at Le Wagon.

📫 **augustodesouzacardoso@gmail.com** · [LinkedIn](https://www.linkedin.com/in/augustodesouzacardoso)
