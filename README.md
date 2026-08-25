<div align="center">

**Languages:** [🇺🇸 English](README.md) | [🇧🇷 Português](README.pt.md)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=2800&pause=1800&color=00FF41&center=true&vCenter=true&width=800&lines=Hi!+I'm+Pedro+Montezuma;Dev+Lead+%40+JuSimples;Backend+%E2%80%A2+Python+%E2%80%A2+Rust+%E2%80%A2+RAG;Linux+%26+security+by+obsession" alt="Typing SVG" />

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWF3N3N5dDJ5cjJkM2Q0ZW5vOGk2bGVzaWZrbXVoMGg5YnN4YnBzZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" width="380" alt="coding gif"/>

🌴 Rio de Janeiro, Brazil

</div>

---

<div align="center">

### 🌟 Featured — [Harken](https://github.com/montezuma-p/harken)

[![harken stars](https://img.shields.io/github/stars/montezuma-p/harken?style=flat&logo=github&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/stargazers)
[![harken release](https://img.shields.io/github/v/release/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/releases)
[![harken license](https://img.shields.io/github/license/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/blob/main/LICENSE)
[![crates.io](https://img.shields.io/crates/v/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://crates.io/crates/harken)

**Your agent cannot listen to audio. Harken fixes that — locally.** MCP server + CLI in a single 13 MB static Rust binary (whisper.cpp via FFI): no Python, no ffmpeg, no API key. On crates.io.

</div>

---

```bash
$ whoami
pedro-montezuma — dev lead @ jusimples (brazilian legaltech AI)

$ cat summary.txt
Backend engineer: Python, Rust, cloud infrastructure and AI systems.
Primary engineer of a legal RAG platform, zero to production.
Security-first mindset, observability always, automate everything.

$ cat /etc/team
Vasco da Gama ⚫⚪
```

---

## 💼 Experience

### Dev Lead / Lead Backend Engineer — [JuSimples](https://jusimples.ai)

*Apr 2026 – Present*

Technical lead for the backend and production infrastructure of JuSimples' Brazilian LegalTech AI platform.

- Architecture and technical decisions for the production system.
- Continued evolution of the RAG pipeline, security, and observability.
- Day-to-day operation: deployments (Cloud Run), monitoring, and incident response.

### Backend Engineer — JuSimples

*Nov 2025 – Apr 2026*

Primary engineer responsible for taking the AI platform from zero to first production launch (April 2026).

- Backend in Python and FastAPI.
- RAG pipeline over Brazilian legislation (LegalBERT, pgvector).
- Hybrid authentication (JWT + API keys) with allowlist-first practices.
- Observability: structured JSON logs, metrics, and tracing.
- GCP infrastructure as code via Terraform (Cloud Run, Cloud SQL, Secret Manager).

---

## 🧰 Stack

![Python](https://img.shields.io/badge/Python-0D1117?style=flat&logo=python&logoColor=00FF41)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat&logo=fastapi&logoColor=00FF41)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-0D1117?style=flat&logo=postgresql&logoColor=00FF41)
![GCP](https://img.shields.io/badge/Google%20Cloud-0D1117?style=flat&logo=googlecloud&logoColor=00FF41)
![Terraform](https://img.shields.io/badge/Terraform-0D1117?style=flat&logo=terraform&logoColor=00FF41)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat&logo=docker&logoColor=00FF41)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat&logo=linux&logoColor=00FF41)
![Bash](https://img.shields.io/badge/Bash-0D1117?style=flat&logo=gnubash&logoColor=00FF41)
![Rust](https://img.shields.io/badge/Rust-0D1117?style=flat&logo=rust&logoColor=00FF41)

| | |
|---|---|
| **Languages & Backend** | Python · FastAPI · SQL / PostgreSQL with pgvector · SQLAlchemy / Alembic · Rust (CLI tooling, Cargo) · Shell Script (Bash/Zsh) · JavaScript / TypeScript |
| **Cloud & Infrastructure** | GCP — Cloud Run, Cloud SQL, Secret Manager, Cloud Storage, Cloud Scheduler, IAM · Terraform · Docker · Linux administration · Virtualization (KVM/VMware/VirtualBox) |
| **AI & Data** | RAG · Vector databases (pgvector) · LLM integration (Gemini/OpenAI) · MCP servers (Model Context Protocol) · Local speech-to-text (whisper.cpp) · Embeddings (LegalBERT/sentence-transformers) · Web scraping |
| **Observability & Security** | Structured JSON logging, OpenTelemetry, Prometheus · JWT, OAuth2, API keys, allowlist patterns · LGPD-aware telemetry and privacy |
| **Tools** | Git, GitHub — PRs, Issues, Actions |

---

## 🚀 Key Projects

### 🎙️ [Harken](https://github.com/montezuma-p/harken)

Speech-to-text for AI agents, fully offline. As an **MCP server**, it gives any agent (Claude Code included) the ability to hear audio; as a CLI, it batch-transcribes files and folders. One 13 MB static Rust binary on whisper.cpp via direct FFI — no Python, no ffmpeg, no API key. Published on [crates.io](https://crates.io/crates/harken), MIT/Apache.

```bash
harken voice-note.opus                 # one file
harken ~/Downloads/meetings/           # whole folder, recursive
harken chat-export.zip                 # pull voice notes straight out of a WhatsApp export
harken mcp                             # MCP server: give your agent ears
```

`Rust` `whisper.cpp` `MCP` `crates.io`

### Other open source projects

- [monitor_linux_ia](https://github.com/montezuma-p/monitor_linux_ia) — Linux system monitoring with AI-generated HTML reports.
- [backup-universal](https://github.com/montezuma-p/backup-universal) — Smart backup system with project-type detection and automatic exclusions.
- [linux-storage-manager](https://github.com/montezuma-p/linux-storage-manager) — Storage cleanup and archiving with retention policies.
- [iaprojeto-setup](https://github.com/montezuma-p/iaprojeto-setup) — AI-driven project scaffolding from natural-language descriptions.
- [my-systems-showcase](https://github.com/montezuma-p/my-systems-showcase) — Documentation of Linux setups: dual-boot, KVM/QEMU labs, security environments.

---

<div align="center">

## 📊 GitHub

<img src="./github-metrics.svg" alt="Top languages" />

</div>

---

## 🎮 When I'm not coding...

- 🔧 Breaking my Linux setup (and fixing it)
- 📚 Reading docs at 3 AM
- 🎯 Automating things that don't need automation
- ⚫⚪ Thinking about Vasco

---

## 🎓 Languages & Education

**Languages:** Portuguese (native) · English (fluent — Cambridge FCE) · Spanish (basic)

- **Universidade Federal Rural do Rio de Janeiro (UFRRJ)** — Bachelor's in History (Licenciatura) · 2020 – Present
- **Alura** — Tech professional development courses (2025): programming logic, Git/GitHub, Linux CLI (DevOps), frontend fundamentals
- **CNA / Cambridge** — English, FCE certification (Cambridge English First)

---

<div align="center">

## 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=flat&logo=linkedin&logoColor=00FF41)](https://www.linkedin.com/in/montezuma-p/)
[![Email](https://img.shields.io/badge/montezuma%40jusimples.ai-0D1117?style=flat&logo=gmail&logoColor=00FF41)](mailto:montezuma@jusimples.ai)
[![Email](https://img.shields.io/badge/pedromontezuma8%40gmail.com-0D1117?style=flat&logo=gmail&logoColor=00FF41)](mailto:pedromontezuma8@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=32&fontColor=00FF41&animation=twinkling&fontAlignY=75"/>

</div>
