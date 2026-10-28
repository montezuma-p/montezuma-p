# Pedro Montezuma

**Software that runs on your machine.** One static binary, no runtime, small enough to audit.

Linux, Rust, C++. Dev lead at [JuSimples](https://jusimples.ai) by day. Rio de Janeiro.

## Shipped

| | |
|---|---|
| `2026-10-24` | [imiric/qml-niri #25](https://github.com/imiric/qml-niri/pull/25) — merged. `CastModel` exposing niri screencasts to QML. C++ / Wayland. |
| `2026-08-25` | [harken v0.8.0](https://github.com/montezuma-p/harken/releases/tag/v0.8.0) — MCP server + CLI, offline speech-to-text for agents. 13 MB static Rust binary. On [crates.io](https://crates.io/crates/harken). |
| `2026-04` | [JuSimples](https://jusimples.ai) in production — legal RAG over Brazilian legislation, FastAPI + pgvector on GCP. Primary engineer, zero to launch. |
| `2025-10` | [monitor_linux_ia](https://github.com/montezuma-p/monitor_linux_ia), [my-systems-showcase](https://github.com/montezuma-p/my-systems-showcase) — first public Linux tooling and setups. |

## Harken

**Your agent cannot listen to audio. harken fixes that — locally.**

<img src="https://raw.githubusercontent.com/montezuma-p/harken/main/docs/assets/demo-claude.gif" alt="Claude Code reading five WhatsApp voice notes through harken, fully offline" width="720" />

```bash
$ harken voice-note.opus       # one file
$ harken chat-export.zip       # voice notes straight out of a WhatsApp export
$ harken mcp                   # MCP server: give your agent ears
```

[![stars](https://img.shields.io/github/stars/montezuma-p/harken?style=flat&logo=github&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/stargazers)
[![crates.io](https://img.shields.io/crates/v/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://crates.io/crates/harken)
[![license](https://img.shields.io/github/license/montezuma-p/harken?style=flat&logoColor=00FF41&color=0D1117&labelColor=0D1117)](https://github.com/montezuma-p/harken/blob/main/LICENSE-MIT)

whisper.cpp via direct FFI. No Python, no ffmpeg, no API key. Nothing leaves the machine.

## Now

Looking for Linux, Wayland and low-level projects to contribute to — and, in time, to maintain. If you maintain one and want hands, write me.

---

<sub>Rio de Janeiro · [LinkedIn](https://www.linkedin.com/in/montezuma-p/) · [montezuma@jusimples.ai](mailto:montezuma@jusimples.ai) · [pedromontezuma8@gmail.com](mailto:pedromontezuma8@gmail.com) · ⚫⚪ · [Português](README.pt.md)</sub>
