<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,2,24,35&height=220&section=header&text=Awesome%20Developer%20Arsenal%20⚡&fontSize=38&fontAlignY=38&desc=The%20Curated%20Compendium%20of%20Free%20Tiers,%20Developer%20Tools,%20Cheatsheets%20&descSize=16&descAlignY=62&fontColor=ffffff" width="100%" alt="Awesome Developer Arsenal" />

  <p align="center">
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome" /></a>
    <a href="https://github.com/shubhmangalam19-collab/awesome-developer-arsenal/stargazers"><img src="https://img.shields.io/github/stars/shubhmangalam19-collab/awesome-developer-arsenal?style=flat-square&color=FFD700" alt="Stars" /></a>
    <a href="https://github.com/shubhmangalam19-collab/awesome-developer-arsenal/forks"><img src="https://img.shields.io/github/forks/shubhmangalam19-collab/awesome-developer-arsenal?style=flat-square&color=blue" alt="Forks" /></a>
    <a href="https://github.com/shubhmangalam19-collab/awesome-developer-arsenal/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-CC0--1.0-green.svg?style=flat-square" alt="License: CC0-1.0" /></a>
    <a href="https://github.com/shubhmangalam19-collab/awesome-developer-arsenal/pulls"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" /></a>
  </p>

  <p align="center">
    <b>A laser-focused, battle-tested collection of generous free tiers, modern web & AI tools, production checklists, and developer cheatsheets.</b><br/>
    <i>Hand-picked to help solo developers, indie hackers, and engineers ship fast without burning cash.</i>
  </p>

  <sub>Maintained with ❤️ by <a href="https://github.com/shubhmangalam19-collab">@shubhmangalam19-collab</a> & open-source contributors</sub>

</div>

---

## 📌 Table of Contents

- [🆓 The Zero-Cost Production Stack (Free Tiers That Deliver)](#-the-zero-cost-production-stack-free-tiers-that-deliver)
  - [Hosting & Compute](#hosting--compute)
  - [Databases & Storage](#databases--storage)
  - [Authentication & User Management](#authentication--user-management)
  - [AI & LLM Inference APIs](#ai--llm-inference-apis)
- [🛠️ Modern Terminal & Productivity Utilities](#️-modern-terminal--productivity-utilities)
- [🎨 UI Components & Design Systems](#-ui-components--design-systems)
- [🧠 System Design & Architecture Cheatsheet](#-system-design--architecture-cheatsheet)
  - [API Protocol Decision Matrix](#api-protocol-decision-matrix)
  - [Database Selection Flowchart](#database-selection-flowchart)
  - [Caching Strategies at a Glance](#caching-strategies-at-a-glance)
- [⚡ Git & Command-Line Emergency Kit](#-git--command-line-emergency-kit)
- [🛡️ Production Security & Quality Checklist](#️-production-security--quality-checklist)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🆓 The Zero-Cost Production Stack (Free Tiers That Deliver)

Services offering high-utility free tiers or generous perpetual allowances for building production MVPs.

### Hosting & Compute

| Provider | Best Used For | Free Allowance | Notes |
| :--- | :--- | :--- | :--- |
| **[Cloudflare Pages & Workers](https://pages.cloudflare.com/)** | Static sites, edge APIs, serverless | 100k req/day (Workers), unlimited bandwidth (Pages) | ⚡ Fast global CDN with zero cold starts. |
| **[Vercel](https://vercel.com/)** | Next.js, frontend frameworks | 100 GB bandwidth, free automated SSL, edge middleware | Best DX for React/Next ecosystems. |
| **[Render](https://render.com/)** | Web services, Docker containers, cron jobs | 750 free instance hours/month | Great PaaS alternative to Heroku (spins down on idle). |
| **[Fly.io](https://fly.io/)** | Global full-stack Docker deployments | Up to 3 shared-cpu-1x VMs, 3GB volume storage | Deploy server applications close to users. |
| **[Koyeb](https://www.koyeb.com/)** | Serverless containers & microservices | 2 free nano services, 512MB RAM | Native Docker deployment, automated SSL. |

### Databases & Storage

| Provider | Type | Free Allowance | Highlights |
| :--- | :--- | :--- | :--- |
| **[Supabase](https://supabase.com/)** | PostgreSQL | 2 active databases, 500MB storage, 50k MAU | Full Postgres with Realtime, Auth, and Storage. |
| **[Neon](https://neon.tech/)** | Serverless Postgres | 0.5 GB storage, instant branching | Serverless Postgres with instant point-in-time branch copies. |
| **[Turso](https://turso.tech/)** | SQLite (LibSQL) at the Edge | 9 GB storage, 500 databases | Ultra-low latency distributed SQLite. |
| **[MongoDB Atlas](https://www.mongodb.com/atlas)** | Document NoSQL | 512 MB shared cluster | Managed NoSQL with built-in search triggers. |
| **[Upstash](https://upstash.com/)** | Redis & Kafka | 10k commands/day (Redis), serverless | REST-based Redis client designed for edge runtimes. |
| **[Cloudflare R2](https://www.cloudflare.com/developer-platform/r2/)** | S3-Compatible Object Storage | 10 GB/month, **0$ egress fees** | No surprise egress bandwidth bills. |

### Authentication & User Management

| Provider | Method | Free Tier Limit | Highlights |
| :--- | :--- | :--- | :--- |
| **[Clerk](https://clerk.com/)** | Hosted & Drop-in UI | 10,000 Monthly Active Users | Unmatched drop-in React/Next components & session management. |
| **[Supabase Auth](https://supabase.com/auth)** | OAuth, Magic Links, Passwords | 50,000 Monthly Active Users | Native Postgres Row-Level Security (RLS) integration. |
| **[Auth.js (NextAuth)](https://authjs.dev/)** | Open-Source Self-hosted | 100% Free (Open Source) | Complete control, zero vendor lock-in. |
| **[Kinde](https://kinde.com/)** | Modern Auth & Feature Flags | 7,500 Monthly Active Users | Built-in user permissions, enterprise SSO ready. |

### AI & LLM Inference APIs

| Provider | Models Available | Free Allowance / Perks | Highlights |
| :--- | :--- | :--- | :--- |
| **[Google AI Studio](https://aistudio.google.com/)** | Gemini 1.5 Flash / Pro, Gemini 2.0 | Generous rate-limited free API keys | 1M+ token context window, multimodal vision/audio. |
| **[GroqCloud](https://groq.com/)** | Llama 3.3, Mistral, Gemma | Generous free rate-limits (TPU/LPU) | 🚀 Fastest token inference speed (500+ tokens/sec). |
| **[OpenRouter](https://openrouter.ai/)** | Multiple open models | Access to free ranked endpoints | Unified single API for dozens of models. |
| **[Hugging Face Inference](https://huggingface.co/)** | Open Source NLP / Diffusion | Free shared endpoints | Great for prototyping embeddings and classifiers. |

---

## 🛠️ Modern Terminal & Productivity Utilities

Essential CLI tools to speed up everyday development by 10x:

| Tool | Language | Replaces | What It Does |
| :--- | :--- | :--- | :--- |
| **[zoxide](https://github.com/ajeetdsouza/zoxide)** | Rust | `cd` | Smarter `cd` command that remembers your most used directories (`z proj`). |
| **[ripgrep](https://github.com/BurntSushi/ripgrep)** | Rust | `grep` | Blazingly fast recursive text search in codebases respecting `.gitignore`. |
| **[bat](https://github.com/sharkdp/bat)** | Rust | `cat` | Cat clone with syntax highlighting, line numbers, and Git diff integration. |
| **[fzf](https://github.com/junegunn/fzf)** | Go | — | General-purpose interactive fuzzy finder for shell history, files, and commands. |
| **[lazygit](https://github.com/jesseduffield/lazygit)** | Go | Git GUI | Simple, keyboard-driven terminal UI for everyday git operations. |
| **[eza](https://github.com/eza-community/eza)** | Rust | `ls` | Modern replacement for `ls` with tree views, icons, and git status flags. |
| **[HTTPie](https://httpie.io/)** | Python | `curl` | Human-friendly CLI HTTP client with formatted JSON outputs. |

---

## 🎨 UI Components & Design Systems

Stop reinventing buttons, modals, and dropdowns. Copy-paste these modern component systems:

- **[shadcn/ui](https://ui.shadcn.com/)** — Re-usable components built using Radix UI and Tailwind CSS. Not an npm dependency — you own the code.
- **[Aceternity UI](https://ui.aceternity.com/)** — Trendsetting animated components, hero sections, and micro-interactions for modern SaaS landing pages.
- **[Magic UI](https://magicui.design/)** — 50+ animated UI elements, interactive backgrounds, and effects built with React and Framer Motion.
- **[Lucide Icons](https://lucide.dev/)** — Clean, consistent, tree-shakeable SVG icon collection with first-party bindings for React, Vue, Svelte, and Flutter.
- **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first CSS framework for rapid UI development.

---

## 🧠 System Design & Architecture Cheatsheet

### API Protocol Decision Matrix

| Protocol | Best For | Pros | Cons |
| :--- | :--- | :--- | :--- |
| **REST** | Public APIs, standard CRUD | Universal support, HTTP caching, simple debugging | Over-fetching / under-fetching data. |
| **GraphQL** | Complex data graphs, mobile apps | Single request for nested data, client-defined schemas | Caching complexity, N+1 query traps. |
| **tRPC** | Full-stack TypeScript apps | 100% end-to-end typesafety without code generation | Tied to TypeScript ecosystems. |
| **gRPC** | Internal microservices, streaming | Blazing fast HTTP/2 binary serialization (Protobuf) | Difficult browser inspection; binary format. |
| **WebSockets** | Live chat, real-time gaming | Full-duplex bidirectional communication | Stateful connections, harder load balancing. |

### Database Selection Flowchart

```
What is your primary data shape?
├── Relational with strong ACID guarantees (users, billing, orders)?
│   └── ➔ PostgreSQL / MySQL
├── Flexible hierarchical documents with dynamic schemas?
│   └── ➔ MongoDB / DynamoDB
├── Ultra-fast in-memory key-value, queues, or session cache?
│   └── ➔ Redis / Upstash
├── High-frequency time-series telemetry or sensor metrics?
│   └── ➔ TimescaleDB / InfluxDB
└── High-dimensional embeddings for AI semantic search?
    └── ➔ pgvector (Postgres) / Qdrant / Pinecone
```

### Caching Strategies at a Glance

1. **Cache-Aside (Lazy Loading)**: Application queries the cache. If missing (cache miss), reads from DB and populates cache. *Best for read-heavy workloads.*
2. **Write-Through**: Application writes data to the cache, which immediately writes to DB synchronously. *Strong data consistency, higher write latency.*
3. **Write-Behind (Write-Back)**: Application writes to cache; cache asynchronously batches updates to DB. *Blazing write performance, potential data loss risk if node crashes.*

---

## ⚡ Git & Command-Line Emergency Kit

Keep these one-liners handy when things go wrong:

```bash
# 1. Undo the last commit but KEEP all your changed files staged
git reset --soft HEAD~1

# 2. Undo the last commit and UNSTAGE files (keep your edits intact)
git reset HEAD~1

# 3. Discard ALL unstaged and staged changes (nuclear reset)
git reset --hard HEAD
git clean -fd

# 4. Change the commit message of your most recent commit
git commit --amend -m "new message"

# 5. Stash only unstaged changes (keep what is in index)
git stash -k

# 6. Find a lost commit, deleted branch, or reset accident
git reflog
# Restore that commit:
git checkout -b recovered-branch <COMMIT_HASH>

# 7. Interactive rebase to squash last 3 commits into 1 clean commit
git rebase -i HEAD~3

# 8. Pull remote changes cleanly without creating merge commit clutter
git pull --rebase origin main
```

---

## 🛡️ Production Security & Quality Checklist

Before shipping your project to the public:

- [ ] **No Secrets in Repo**: Run `git secrets` or check `.env` is listed in `.gitignore`.
- [ ] **Rate Limiting**: Enforce IP/token rate limits on authentication and AI endpoints (e.g. `@upstash/ratelimit`).
- [ ] **Input Sanitization**: Validate all incoming payloads with schema validators ([Zod](https://zod.dev/) / [Pydantic](https://docs.pydantic.dev/)).
- [ ] **CORS Configuration**: Explicitly whitelist trusted origins instead of wildcard `*` with credentials.
- [ ] **Security Headers**: Ensure `X-Content-Type-Options: nosniff`, `X-Frame-Options: DENY`, and strict `Content-Security-Policy` are enabled.
- [ ] **Error Masks**: Ensure stack traces are hidden from public API responses in production mode.
- [ ] **Database Connection Pooling**: Avoid exhausting DB connection pools in serverless environments (use Prisma Accelerate, Neon Pooler, or Supabase PgBouncer).

---

## 🤝 Contributing

We welcome community contributions! Found an awesome free tool, a generous tier, or a life-saving cheatsheet?
1. Check the [Contributing Guide](CONTRIBUTING.md).
2. Fork the repository and open a clean Pull Request.
3. Help fellow developers level up!

---

## 📄 License

This repository is licensed under the [Creative Commons Zero v1.0 Universal](LICENSE) (Public Domain Dedication). Feel free to share, fork, and learn!
