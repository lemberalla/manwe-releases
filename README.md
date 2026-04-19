<p align="center">
  <img src="assets/manwe-icon-beta.webp" width="128" height="128" alt="Manwe">
</p>

<h1 align="center">AI doesn't need better answers. It needs better disagreement.</h1>

<p align="center">
  <strong>Manwe</strong> is a decision room for macOS.<br>
  Describe a decision. Get a debate. Receive an auditable decision record.
</p>

<p align="center">
  <a href="https://github.com/lemberalla/manwe-releases/releases/latest"><strong>Download the Beta</strong></a> · <a href="https://discord.gg/Nz6RExEpSD">Join the Discord</a> · <a href="https://askmanwe.com">Website</a>
</p>

---

Describe a decision or question. Manwe searches PubMed, arXiv, Semantic Scholar, and 10 other real sources, assembles a panel of AI advisors with diverse perspectives, and runs a multi-round debate. You get a structured decision record with predictions, confidence scores, evidence, risks, and a concrete action plan. Not a chat response.

Your advisors are alive. They remember past debates, develop worldviews over time, and transform when genuinely challenged. Between runs, they react to real-world knowledge in their domain — leave the app open and they grow.

<p align="center">
  <img src="assets/screenshot-1.png" width="100%" alt="The Panel — advisors debating with unique perspectives">
</p>

<p align="center">
  <img src="assets/screenshot-2.png" width="100%" alt="Structured decision record with predictions and confidence scores">
</p>

## Try asking

- "Should I leave my job to start a company? I'm 32, earning $140K, with 3 paying customers."
- "Will Bitcoin hit $200K by end of 2026?"
- "My doctor recommended a Whipple procedure — what are the risks and alternatives?"
- "I want to wash my car. The car wash is 50 meters away. Should I walk or drive?"

## Runs on your Mac

Runs locally on Apple Silicon. Or connect your cloud provider. Your choice.

Manwe runs Qwen locally via MLX — no API keys, no data leaving your device. For a quality leap, connect Claude, Codex, or any OpenAI-compatible API. Bring your own key, bring your own model.

| Model | Tier | Type | Requirements |
|-------|------|------|-------------|
| Qwen3 8B | Standard | Local | 8GB+ RAM, ~5GB download |
| Qwen3.5 9B | Pro | Local | 16GB+ RAM, ~5.5GB download |
| Qwen3.6 35B MoE | Ultra | Local | 36GB+ RAM, ~19GB download |
| Qwen3.5 35B MoE | Ultra | Local | 36GB+ RAM, ~19GB download |
| Claude Sonnet / Opus | Cloud | CLI | Claude Code CLI + subscription |
| Codex (GPT) | Cloud | CLI | Codex CLI + ChatGPT/OpenAI subscription |
| Qwen 3.6 Cloud | Cloud | CLI | Qwen Code CLI + authentication |
| Anthropic / OpenAI / Alibaba API | Cloud | API Key | Your own API key |
| OpenRouter, Groq, Together, Ollama... | Cloud | Custom | Any OpenAI-compatible endpoint |

## What makes it different

- **Chat first, run when ready** — talk a decision through, invite up to 3 advisors from your pool, then hit Run when you want a structured debate
- **Reasoning control** — pick how hard each model thinks. Low to Max, per model, for Claude, Codex, and API backends
- **Your data, their debate** — upload documents (PDF, TXT, MD) and every advisor sees your facts. The Auditor fact-checks claims against your actual data, not just web search
- **Real research, not vibes** — searches 13 sources (PubMed, Semantic Scholar, arXiv, OpenAlex, CORE, Wikipedia, BLS, GDELT, DuckDuckGo, Hacker News, Stack Exchange, ClinicalTrials.gov, DOAJ) before the debate starts
- **Advisors who actually disagree** — the panel always includes a Contrarian (challenges consensus) and an Auditor (fact-checks claims)
- **Living agents** — advisors develop worldviews, accumulate experience across runs, and react to real-world knowledge between debates
- **Personalized evidence** — each advisor reads research ranked by relevance to their specific expertise
- **Guest experts** — Manwe detects knowledge gaps and recruits specialists on the fly
- **Claim verification** — when agents cite statistics, the system auto-searches and regenerates with real evidence
- **You're in the room** — inject events mid-debate, interview individual advisors after
- **Continue chains** — follow up on any completed decision record with new questions
- **Foundation Models** — Apple's Neural Engine handles research tasks while the GPU runs debates

## Install

1. Download the latest DMG from [**Releases**](https://github.com/lemberalla/manwe-releases/releases/latest)
2. Open the DMG and drag Manwe to Applications
3. Launch — onboarding guides you through model setup

**Requires macOS 14.0+ and Apple Silicon (M1 or later).**

## Changelog

See [**Releases**](https://github.com/lemberalla/manwe-releases/releases) for the full version history.

## Feedback

This is a beta. Things will break.

**[Join the Discord](https://discord.gg/Nz6RExEpSD)** — bug reports, feature ideas, or just share your wildest decision records.

---

<p align="center">
  Made by Oncel Cebeci · <a href="https://tinythings.app">a tiny things app</a>
</p>
