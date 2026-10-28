# Pedro Montezuma

**Software que roda na sua máquina.** Um binário estático, sem runtime, pequeno o bastante pra auditar.

Linux, Rust, C++. Dev lead na [JuSimples](https://jusimples.ai) de dia. Rio de Janeiro.

## Entregue

| | |
|---|---|
| `2026-10-24` | [imiric/qml-niri #25](https://github.com/imiric/qml-niri/pull/25) — mergeado. `CastModel` expondo screencasts do niri pro QML. C++ / Wayland. |
| `2026-08-25` | [harken v0.8.0](https://github.com/montezuma-p/harken/releases/tag/v0.8.0) — MCP server + CLI, speech-to-text offline pra agentes. Binário estático em Rust de 13 MB. No [crates.io](https://crates.io/crates/harken). |
| `2026-04` | [JuSimples](https://jusimples.ai) em produção — RAG jurídico sobre a legislação brasileira, FastAPI + pgvector no GCP. Engenheiro principal, do zero ao lançamento. |
| `2025-10` | [monitor_linux_ia](https://github.com/montezuma-p/monitor_linux_ia), [my-systems-showcase](https://github.com/montezuma-p/my-systems-showcase) — primeiras ferramentas e setups Linux públicos. |

## Harken

**Seu agente não consegue ouvir áudio. O harken resolve isso — localmente.**

<img src="https://raw.githubusercontent.com/montezuma-p/harken/main/docs/assets/demo-claude.gif" alt="Claude Code lendo cinco áudios de WhatsApp pelo harken, totalmente offline" width="720" />

```bash
$ harken voice-note.opus       # um arquivo
$ harken chat-export.zip       # áudios direto de um export do WhatsApp
$ harken mcp                   # MCP server: dá ouvidos ao seu agente
```

[![stars](https://img.shields.io/github/stars/montezuma-p/harken?style=flat&logo=github&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/stargazers)
[![crates.io](https://img.shields.io/crates/v/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://crates.io/crates/harken)
[![license](https://img.shields.io/github/license/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/blob/main/LICENSE-MIT)

whisper.cpp via FFI direto. Sem Python, sem ffmpeg, sem API key. Nada sai da máquina.

## Agora

Procurando projetos Linux, Wayland e low-level pra contribuir — e, com o tempo, manter. Se você mantém um e quer mãos, me escreve.

---

<sub>Rio de Janeiro · [LinkedIn](https://www.linkedin.com/in/montezuma-p/) · [montezuma@jusimples.ai](mailto:montezuma@jusimples.ai) · [pedromontezuma8@gmail.com](mailto:pedromontezuma8@gmail.com) · ⚫⚪ · [English](README.md)</sub>
