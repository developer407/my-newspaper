# My Newspaper — Interest Profile

Built from a scan of `P:\Projects` on 2026-11-14, reordered by the user the same day.
Sections are listed in priority order. Earlier sections get more stories and more space.
★★★ = top focus, ★★ = regular, ★ = brief coverage only.

## Daily editions — THREE separate papers every day

| Paper | Name | Contents | Saved as |
|---|---|---|---|
| 1 | **The AI Engineer** | Section 1 only (AI Engineering), in depth | `editions/YYYY-MM-DD/1-ai-engineer.html` |
| 2 | **The Dev Digest** | Sections 2–9, in priority order | `editions/YYYY-MM-DD/2-dev-digest.html` |
| 3 | **The Daily Extras** | The "Daily extras" section | `editions/YYYY-MM-DD/3-daily-extras.html` |

Schedule: every day at **8:00 AM** (local time).

Length & format:
- Paper 1 and Paper 2: **20 stories each**. Paper 3: about 10 items (3 AI tools, 3 GitHub repos, 3 project ideas, 1 "learn this today").
- Every story shows: headline · source + date · a **quick summary** (2–3 sentences) · a one-line **"Why it matters to you"**.
- Every story also has a collapsible **"Read deeper"** panel: a longer explanation (1–3 paragraphs, with code or config snippets where useful) plus links to the original article and 1–2 related sources.
- Each paper opens with a "Top 3 in 30 seconds" box and a table of contents linking to its sections.
- Only news from the last ~48 hours (allow up to 7 days for slower topics). Never repeat a story covered in the previous 3 days' editions.

Rules:
- No story appears in more than one paper on the same day.
- Paper 1 gets the most depth. Paper 2 gives sections 6–9 short coverage. Paper 3 is short and fun.

---

# PAPER 1 — The AI Engineer

## 1. AI Engineering ★★★ (TOP PRIORITY — lead story always comes from here)
- LLM model releases, benchmarks & pricing: OpenAI, Anthropic Claude, Google Gemini, Meta Llama, Mistral, DeepSeek, Qwen
- Spring AI (ChatClient, tool calling, MCP, advisors, pgvector vector store, OpenAI/Anthropic/Gemini/Ollama models)
- AI agents: LangGraph, LangChain, agent frameworks, multi-agent systems, agent design patterns
- Model Context Protocol (MCP): new servers, clients, spec changes
- RAG, embeddings, vector databases (pgvector, Qdrant), evals, prompt engineering
- Running models locally: Ollama, open-weight models, quantization
- AI coding tools: Claude Code, Cursor, Copilot, AI app/website builders
- AI product ideas & startups: AI receptionists, AI recruiting/resume tools, AI travel agents, "AI COO", AI SaaS
- Important AI research papers explained simply

---

# PAPER 2 — The Dev Digest

## 2. Java & Spring Ecosystem ★★★
- Java 17 / 21 and new JDK releases (virtual threads, records, pattern matching)
- Spring Boot 3.x → 4.x migration
- Spring Security + JWT (jjwt), OAuth2 client
- Spring Data JPA / Hibernate, validation, caching, actuator
- Lombok, springdoc-openapi (Swagger), JUnit 5, Testcontainers, Jib, Maven

## 3. Node / MERN & Python Backends ★★
- Python for AI: FastAPI, Pydantic, SQLAlchemy, Alembic
- Node.js, Express, MongoDB/Mongoose, Socket.IO (real-time apps)

## 4. Creator & Career ★★
- Developer YouTube/course creation (project-based full-stack and AI tutorials)
- Indian tech ecosystem, startups & funding, SaaS ideas
- AI engineer and Java/full-stack job market, interview trends, system design interviews

## 5. Security ★★
- Critical CVEs in Spring, Java libraries, npm packages, AI/LLM tooling (prompt injection, MCP security)
- Auth best practices (JWT, OAuth2, passkeys)

## 6. Microservices & Spring Cloud ★
- Spring Cloud releases, Eureka, Config Server, API Gateway, OpenFeign, Resilience4j
- Apache Kafka, RabbitMQ, event-driven architecture
- System design: sagas, outbox pattern, observability

## 7. Databases & DevOps ★
- MySQL, PostgreSQL, Redis
- Docker & Docker Compose, Kubernetes, GitHub Actions CI/CD
- AWS S3, Cloudinary

## 8. Payments & Integrations ★
- Razorpay, Stripe (API changes, India payment rules/UPI)
- Twilio, email, WebSockets

## 9. Frontend: React Ecosystem ★
- React 19, Vite, Next.js, Redux Toolkit, React Hook Form + Zod
- Tailwind CSS v4, shadcn/ui, Radix UI, MUI, TypeScript

---

# PAPER 3 — The Daily Extras

## Daily extras
- AI tool of the day
- GitHub repo of the day (AI agents / Spring AI / LLM projects first)
- "Project idea of the day" (AI SaaS or AI-powered full-stack project worth building or teaching)
