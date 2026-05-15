<p align="center">
  <a href="https://atomicbot.ai">
    <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/logo.png" width="120" alt="Atomic" />
  </a>
</p>

<p align="center">
  <a href="https://atomicbot.ai">Website</a> ·
  <a href="https://github.com/AtomicBot-ai/atomicbot#readme">Docs</a> ·
  <a href="https://discord.gg/2TXafRV69m">Discord</a> ·
  <a href="https://x.com/atomicbot_ai">X</a>
</p>

<p align="center">
  Open-source local AI — agents, chat, and inference. Private by default.
</p>

---

### Atomic Chat

<a href="https://github.com/AtomicBot-ai/Atomic-Chat/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/Atomic-Chat?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/Atomic-Chat?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/Atomic-Chat?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/Atomic-Chat#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/Atomic-Chat/raw/main/assets/preview.png" width="100%" alt="Atomic Chat" />
</p>

An open-source desktop AI app. Run local LLMs from Hugging Face or connect cloud models (OpenAI, Anthropic, Mistral, Groq, MiniMax, others). Available on macOS, Windows, and iOS.

#### Download

<p>
  <a href="https://github.com/AtomicBot-ai/Atomic-Chat/releases/latest"><img src="https://img.shields.io/badge/Download_for-macOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="44" alt="Download for macOS" /></a>&nbsp;
  <a href="https://github.com/AtomicBot-ai/Atomic-Chat/releases/latest"><img src="https://img.shields.io/badge/Download_for-Windows-0078D4?style=for-the-badge&logo=windows11&logoColor=white" height="44" alt="Download for Windows" /></a>&nbsp;
  <a href="https://apps.apple.com/us/app/atomic-chat-private-local-ai/id6761720226"><img src="https://img.shields.io/badge/Download_for-iOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="44" alt="Download for iOS" /></a>
</p>

#### Local OpenAI-compatible server

```sh
curl http://localhost:1337/v1/chat/completions -d '{
  "model": "llama-3.2-3b-instruct",
  "messages": [{ "role": "user", "content": "Why is the sky blue?" }]
}'
```

#### Highlights

- Run LLMs (Llama, Gemma, Qwen, others) from Hugging Face — fully offline
- Connect cloud providers: OpenAI, Anthropic, Mistral, Groq, MiniMax
- Custom assistants for specialized tasks
- MCP integration for agentic capabilities
- Native iOS app, not a wrapper

---

### Atomic LLaMA

<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant/commits/master"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-llama-cpp-turboquant?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-llama-cpp-turboquant#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/atomic%20llama.png" width="100%" alt="Atomic LLaMA" />
</p>

A `llama.cpp` fork with TurboQuant KV cache compression and Gemma 4 MTP speculative decoding. ~30-50% throughput gains on the same hardware, drop-in compatible with upstream tools and GGUF.

#### TurboQuant KV cache

WHT-rotated 2/3/4-bit KV cache with backend-native kernels (Metal `TurboFlash`, CUDA, Vulkan, HIP). `turbo3` is the default — 3-bit, ~4.3× compression vs F16.

```sh
llama-server -m model.gguf -c 32768 -ngl 99 -fa on \
  -ctk turbo3 -ctv turbo3
```

#### Gemma 4 MTP speculative decoding

Pair any `gemma4` target with the official `gemma4_assistant` head — loaded into the target context, no second tokenizer or KV cache. +30-50% short-prompt throughput on Gemma 4 26B-A4B / 31B at 85-88% accept rate. [Pre-built assistant heads on Hugging Face.](https://huggingface.co/collections/AtomicChat/gemma-4-assistant-gguf)

```sh
llama-server -m gemma-4-target.gguf -c 16384 -ngl 99 -ngld 99 -fa on \
  --mtp-head gemma-4-assistant-Q4_K_M.gguf \
  --spec-type mtp --draft-block-size 3
```

#### Also included

- `TQ3_1S` / `TQ4_1S` weight quantization via `llama-quantize` — 25-35% smaller than Q8_0, single-digit % PPL delta
- Regularly synced with `ggml-org/llama.cpp`
- Powers local inference in Atomic Chat, Atomic Hermes, and Atomic Agent

---

### Atomic Hermes

<a href="https://github.com/AtomicBot-ai/atomic-hermes/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-hermes?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-hermes/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-hermes?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-hermes/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-hermes?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-hermes#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/hermes-ui.png" width="100%" alt="Atomic Hermes" />
</p>

A native autonomous AI agent for desktop. Built on the [Hermes Agent](https://github.com/NousResearch/hermes-agent) core by Nous Research, with computer use, time-travel file history, and offline operation.

#### Download

<p>
  <a href="https://github.com/AtomicBot-ai/atomic-hermes/releases/latest"><img src="https://img.shields.io/badge/Download_for-macOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="44" alt="Download for macOS" /></a>
</p>

#### Highlights

- Computer use with native OCR (Apple Vision / Windows.Media.Ocr) — pixel-accurate click coordinates, no guessing
- Time-travel file history: every file the agent touches is snapshotted before and after, one-click diff or restore
- Self-improving skills and memory: the agent writes its own procedures and decides what to remember across sessions
- Bundled inference engine, or 20+ cloud providers (OpenRouter, Anthropic, OpenAI, Gemini, DeepSeek, others)
- One agent across 16+ messengers — Telegram, Discord, Slack, WhatsApp, Signal, iMessage, Email, Matrix, Teams
- 40+ tools, MCP-native: file ops, web search, code execution, subagents, cron, browser automation, [agentskills.io](https://agentskills.io) Skills Hub
- Approval modals for dangerous shell commands and writes

---

### Atomic Claw

<a href="https://github.com/AtomicBot-ai/atomicbot/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomicbot?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomicbot/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomicbot?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomicbot/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomicbot?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomicbot#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/.github/raw/main/assets/chat.jpg" width="100%" alt="Atomic Bot" />
</p>

A native desktop app that turns [OpenClaw](https://github.com/openclaw/openclaw) (330k+ stars) into a personal AI assistant. No terminal, no config, no Docker.

#### Download

<p>
  <a href="https://github.com/AtomicBot-ai/atomicbot/releases/latest"><img src="https://img.shields.io/badge/Download_for-macOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="44" alt="Download for macOS" /></a>&nbsp;
  <a href="https://github.com/AtomicBot-ai/atomicbot/releases/latest"><img src="https://img.shields.io/badge/Download_for-Windows-0078D4?style=for-the-badge&logo=windows11&logoColor=white" height="44" alt="Download for Windows" /></a>&nbsp;
  <img src="https://img.shields.io/badge/Linux-Coming_Soon-555?style=for-the-badge&logo=linux&logoColor=white" height="44" alt="Linux — coming soon" />
</p>

#### Highlights

- Drafts emails, schedules meetings, summarizes docs, automates the browser
- 13,000+ skills from ClawHub
- Multi-model: Claude, GPT, Gemini — switch on the fly with your own API keys
- One AI across Telegram, Slack, Discord, WhatsApp
- Built-in Whisper transcription, local or cloud
- Persistent memory across sessions and tasks
- Auto-updates to the latest OpenClaw release

---

### Atomic Computer Use

<a href="https://github.com/AtomicBot-ai/atomic-computeruse/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-computeruse?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-computeruse/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-computeruse?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-computeruse/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-computeruse?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://www.npmjs.com/package/@atomicbotai/computer-use"><img src="https://img.shields.io/npm/v/@atomicbotai/computer-use?style=flat&logo=npm&label=npm&color=cb3837" alt="npm" /></a>

Framework-agnostic desktop automation for AI agents. Screenshot, click, type, scroll, drag, OCR — works with any tool-calling LLM, MCP server, or custom pipeline.

#### Install

```sh
npm install @atomicbotai/computer-use
```

#### Use

```ts
import { screenshot, click, type } from "@atomicbotai/computer-use";

const { image, anchors } = await screenshot();
const send = anchors.find(a => a.text === "Send");
await click(send.x, send.y);
await type("hello");
```

#### Packages

- [`@atomicbotai/computer-use`](https://www.npmjs.com/package/@atomicbotai/computer-use) — TypeScript library: OCR, actions, overlay, session lock
- [`@atomicbotai/computer-use-mcp`](https://github.com/AtomicBot-ai/atomic-computeruse-mcp) — MCP server for Claude Desktop, Cursor, Windsurf, or any MCP client

#### Highlights

- Zero-dependency native OCR (Apple Vision on macOS, Windows.Media.Ocr on Windows) — no Tesseract, no cloud, no API keys
- Pixel-accurate UI anchors: `"Send" at (1450, 890)` instead of guessing from a downscaled screenshot
- Full action set: click / double / triple, type, press, scroll, drag, hold key, clipboard, app switch, list displays
- Native overlay (Swift on macOS, PowerShell on Windows) shows when the agent is driving the mouse and keyboard
- File-based session lock prevents two agents from fighting over the desktop
- Guardrails against misclicks in dock/launcher and submit zones
- Per-action debug artifacts: screenshots, OCR results, tool outputs

---

### ClawHub Layer API

<a href="https://github.com/AtomicBot-ai/clawhub-layer-api/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/clawhub-layer-api?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/clawhub-layer-api/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/clawhub-layer-api?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/clawhub-layer-api/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/clawhub-layer-api?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/clawhub-layer-api#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

A complete REST API for [ClawHub](https://github.com/openclaw/clawhub). The official ClawHub API exposes a subset of the data; this layer aggregates everything into clean endpoints, no Convex knowledge required.

#### Highlights

- Full coverage: skills, metadata, and everything the official API doesn't expose
- Auto-syncing: periodically pulls and caches the latest data from Convex
- Standard REST, no upstream dependency at query time
- Drop-in for apps, bots, and workflows

---

### Atomic Agent

<a href="https://github.com/AtomicBot-ai/atomic-agent/stargazers"><img src="https://img.shields.io/github/stars/AtomicBot-ai/atomic-agent?style=flat&logo=github&label=Stars&color=f5c542" alt="Stars" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent/network/members"><img src="https://img.shields.io/github/forks/AtomicBot-ai/atomic-agent?style=flat&logo=github&label=Forks&color=4ac1f2" alt="Forks" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent/commits/main"><img src="https://img.shields.io/github/last-commit/AtomicBot-ai/atomic-agent?style=flat&label=Last%20Commit&color=blueviolet" alt="Last Commit" /></a>&nbsp;
<a href="https://github.com/AtomicBot-ai/atomic-agent#readme"><img src="https://img.shields.io/badge/Docs-Read-2196F3?style=flat" alt="Docs" /></a>

<p align="center">
  <img src="https://github.com/AtomicBot-ai/atomic-agent/raw/main/assets/demo.gif" width="100%" alt="Atomic Agent" />
</p>

A local-first operator agent for `llama.cpp`. Standalone SEA binary, tuned for small local models. Data, traces, browser profile, memory, and model traffic stay on your machine.

#### Install

```sh
curl -fsSL https://api.atomicbot.ai/agent-install | sh
```

#### Run

```sh
atomic-agent
```

#### Capabilities

- System browser via ARIA snapshots, shell, filesystem, documents (PDF/DOCX/XLSX), git, clipboard, HTTP, notifications
- GBNF grammar-constrained tool calls, parallel tool batches, cache-hot prompt prefix, externalized state in SQLite
- Local Markdown skills loaded on demand, FTS5 note recall, durable cron and webhook-triggered tasks
- TUI, CLI, OpenAI-compatible HTTP server, and a Tauri sidecar speaking newline-delimited JSON
- Policy-gated dangerous actions, append-only NDJSON traces with prompt-drift replay

---

### Community

<p>
  <a href="https://discord.gg/2TXafRV69m"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>&nbsp;
  <a href="https://x.com/atomicbot_ai"><img src="https://img.shields.io/badge/X-000?style=for-the-badge&logo=x&logoColor=fff" alt="X" /></a>&nbsp;
  <a href="https://www.linkedin.com/company/atomicbot/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=fff" alt="LinkedIn" /></a>
</p>

<sub>© 2026 Atomic · <a href="https://atomicbot.ai">atomicbot.ai</a></sub>
