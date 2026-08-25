<div align="center">

**Idiomas:** [🇺🇸 English](README.md) | [🇧🇷 Português](README.pt.md)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=2800&pause=1800&color=00FF41&center=true&vCenter=true&width=800&lines=Oi!+Eu+sou+o+Pedro+Montezuma;Dev+Lead+%40+JuSimples;Backend+%E2%80%A2+Python+%E2%80%A2+Rust+%E2%80%A2+RAG;Linux+%26+seguran%C3%A7a+por+obsess%C3%A3o" alt="Typing SVG" />

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWF3N3N5dDJ5cjJkM2Q0ZW5vOGk2bGVzaWZrbXVoMGg5YnN4YnBzZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qgQUggAC3Pfv687qPC/giphy.gif" width="380" alt="coding gif"/>

🌴 Rio de Janeiro, Brasil

</div>

---

<div align="center">

### 🌟 Destaque — [Harken](https://github.com/montezuma-p/harken)

[![harken stars](https://img.shields.io/github/stars/montezuma-p/harken?style=flat&logo=github&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/stargazers)
[![harken release](https://img.shields.io/github/v/release/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/releases)
[![harken license](https://img.shields.io/github/license/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/blob/main/LICENSE)
[![crates.io](https://img.shields.io/crates/v/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://crates.io/crates/harken)

**Seu agente não escuta áudio. O Harken resolve isso — localmente.** MCP server + CLI num único binário estático de 13 MB em Rust (whisper.cpp via FFI): sem Python, sem ffmpeg, sem API key. No crates.io.

</div>

---

```bash
$ whoami
pedro-montezuma — dev lead @ jusimples (legaltech AI brasileira)

$ cat resumo.txt
Engenheiro backend: Python, Rust, infraestrutura cloud e sistemas de IA.
Engenheiro principal de uma plataforma de RAG jurídico, do zero à produção.
Security-first, observabilidade sempre, automatize tudo.

$ cat /etc/time
Vasco da Gama ⚫⚪
```

---

## 💼 Experiência

### Dev Lead / Lead Backend Engineer — [JuSimples](https://jusimples.ai)

*abr/2026 – Atual*

Liderança técnica do backend e da infraestrutura em produção da plataforma de IA da JuSimples (LegalTech).

- Arquitetura e decisões técnicas do sistema em produção.
- Evolução do pipeline de RAG, da segurança e da observabilidade.
- Operação contínua: deploys (Cloud Run), monitoramento e resposta a incidentes.

### Software Engineer (Backend) — JuSimples

*nov/2025 – abr/2026*

Engenheiro principal, responsável por levar a plataforma do zero até o lançamento em produção (abr/2026).

- Backend em Python e FastAPI.
- Pipeline de RAG sobre legislação brasileira (LegalBERT, pgvector).
- Autenticação híbrida (JWT + API keys) com práticas allowlist-first.
- Observabilidade: logs JSON estruturados, métricas e tracing.
- Infraestrutura GCP via Terraform (Cloud Run, Cloud SQL, Secret Manager).

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
| **Linguagens & Backend** | Python · FastAPI · SQL / PostgreSQL com pgvector · SQLAlchemy / Alembic · Rust (CLIs, Cargo) · Shell Script (Bash/Zsh) · JavaScript / TypeScript |
| **Cloud & Infraestrutura** | GCP — Cloud Run, Cloud SQL, Secret Manager, Cloud Storage, Cloud Scheduler, IAM · Terraform · Docker · Administração Linux · Virtualização (KVM/VMware/VirtualBox) |
| **IA & Dados** | RAG · Bancos vetoriais (pgvector) · Integração com LLMs (Gemini/OpenAI) · MCP servers (Model Context Protocol) · Transcrição local (whisper.cpp) · Embeddings (LegalBERT/sentence-transformers) · Web scraping |
| **Observabilidade & Segurança** | Logging estruturado JSON, OpenTelemetry, Prometheus · JWT, OAuth2, API keys, allowlist patterns · LGPD — telemetria e privacidade |
| **Ferramentas** | Git, GitHub — PRs, Issues, Actions |

---

## 🚀 Projetos em Destaque

### 🎙️ [Harken](https://github.com/montezuma-p/harken)

Transcrição de áudio para agentes de IA, 100% offline. Como **MCP server**, dá a qualquer agente (Claude Code incluso) a capacidade de ouvir áudio; como CLI, transcreve arquivos e pastas em lote. Um único binário estático de 13 MB em Rust sobre whisper.cpp via FFI direta — sem Python, sem ffmpeg, sem API key. Publicado no [crates.io](https://crates.io/crates/harken), MIT/Apache.

```bash
harken audio.opus                      # um arquivo
harken ~/Downloads/reunioes/           # pasta inteira, recursivo
harken export-chat.zip                 # extrai só os áudios de um export do WhatsApp
harken mcp                             # MCP server: dá ouvidos ao seu agente
```

`Rust` `whisper.cpp` `MCP` `crates.io`

### Outros projetos open source

- [monitor_linux_ia](https://github.com/montezuma-p/monitor_linux_ia) — Monitoramento de sistemas Linux com relatórios HTML gerados por IA.
- [backup-universal](https://github.com/montezuma-p/backup-universal) — Sistema de backup com detecção de tipo de projeto e exclusões automáticas.
- [linux-storage-manager](https://github.com/montezuma-p/linux-storage-manager) — Limpeza e arquivamento de storage com políticas de retenção.
- [iaprojeto-setup](https://github.com/montezuma-p/iaprojeto-setup) — Scaffolding de projetos via IA a partir de descrições em linguagem natural.
- [my-systems-showcase](https://github.com/montezuma-p/my-systems-showcase) — Documentação de setups Linux: dual-boot, labs KVM/QEMU, ambientes de segurança.

---

<div align="center">

## 📊 GitHub

<img src="./github-metrics.svg" alt="Linguagens mais usadas" />

</div>

---

## 🎮 Quando não tô codando...

- 🔧 Quebrando meu setup Linux (e consertando)
- 📚 Lendo docs às 3 da manhã
- 🎯 Automatizando coisas que não precisam de automação
- ⚫⚪ Pensando no Vasco

---

## 🎓 Idiomas & Formação

**Idiomas:** Português (nativo) · Inglês (fluente — Cambridge FCE) · Espanhol (básico)

- **Universidade Federal Rural do Rio de Janeiro (UFRRJ)** — Licenciatura em História · 2020 – atual
- **Alura** — Cursos livres de tecnologia (2025): lógica de programação, Git/GitHub, Linux CLI (DevOps), fundamentos de frontend
- **CNA / Cambridge** — Inglês, certificação FCE (Cambridge English First)

---

<div align="center">

## 📫 Bora se conectar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=flat&logo=linkedin&logoColor=00FF41)](https://www.linkedin.com/in/montezuma-p/)
[![Email](https://img.shields.io/badge/montezuma%40jusimples.ai-0D1117?style=flat&logo=gmail&logoColor=00FF41)](mailto:montezuma@jusimples.ai)
[![Email](https://img.shields.io/badge/pedromontezuma8%40gmail.com-0D1117?style=flat&logo=gmail&logoColor=00FF41)](mailto:pedromontezuma8@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=120&section=footer&text=Valeu%20pela%20visita!&fontSize=32&fontColor=00FF41&animation=twinkling&fontAlignY=75"/>

</div>
