<p align="center">
  <img src="assets/manwe-icon-beta.webp" width="96" height="96" alt="Manwe">
</p>

<h1 align="center">Manwe</h1>

<p align="center">
  <strong>An AI workspace that learns how you work.</strong><br>
  Your context, models and tools, together on your Mac.
</p>

<p align="center">
  <a href="https://github.com/lemberalla/manwe-releases/releases/latest"><strong>Download for Mac</strong></a> ·
  <a href="https://askmanwe.com/handbook/">Handbook</a> ·
  <a href="https://askmanwe.com">Website</a> ·
  <a href="https://discord.gg/e7q8AfXkx">Discord</a>
</p>

---

Research a question, work with an advisor, review a repository, or create something with your files and connected apps. Manwe keeps useful context so you can return to the work and continue with a different model when you need to.

This repository hosts the signed Mac installers and release notes. Start with the [handbook](https://askmanwe.com/handbook/) for setup and practical examples.

## What you can do

| | |
|---|---|
| **Worlds and memory** | Give projects and areas of life their own context. Keep goals, constraints and relationships together, with personal preferences in their own place. Inspect retained knowledge in the memory map. |
| **Learning from feedback** | Small on-device neural classifiers learn patterns from retained corrections and choices. Review, undo or set aside memory, and control automatic remembering and learning. |
| **Persistent advisors** | Return to specialists with their own instructions, model choices and retained lessons. Work with one, ask for second opinions, or bring a team together. |
| **Research and Deep Review** | Investigate a topic with sources and relevant World context. Review code in a selected repository, inspect evidence and save useful findings even when questions remain open. |
| **Files, browser and apps** | Read and edit granted files, use terminal commands and connected tools, and create documents, spreadsheets, presentations and interactive results. |
| **Developer tools** | Search large repositories, use editor context from VS Code, Cursor or Xcode, and run work in a local Docker container when configured. |
| **Repeatable work** | Keep methods as skills, save tasks as workflows, run them on demand or on a schedule, and watch for changes. |
| **Saved work and sharing** | Reopen generated files and retained versions. Export reports as PDF, HTML or slides, or share pages served from your awake Mac. |

## Install or update

1. Download the DMG from the [latest release](https://github.com/lemberalla/manwe-releases/releases/latest).
2. Quit Manwe if it is running, open the DMG and drag Manwe into Applications. Choose Replace when updating.
3. Open Manwe. On a fresh install, onboarding helps you choose a model and set up your context.

Manwe is Developer ID signed and notarized by Apple. Published downloads include a `SHA256SUMS` file for checking the installer.

**Already using 0.9.9 or later?** Use **Check for Updates…** in the profile menu or **Settings → General**. With automatic update checks enabled, an update indicator appears when a newer version is available. In 0.9.92 and later, the update button appears above your profile.

**Updating from 0.9.7?** Manwe creates a recovery archive before upgrading your existing data. Conversations, reports, Worlds and promoted memory are preserved. The legacy reusable advisor roster is reset, and you choose your model and complete onboarding again. To roll back, follow the instructions in the archive; do not open upgraded data with 0.9.7.

## Models and requirements

Requires an **Apple Silicon Mac (M1 or later) running macOS 14 or later**. Local models need a separate download and enough memory for the chosen model.

- **Local models:** Gemma 4 E4B is the recommended responsive option. Larger Gemma and Qwen options are experimental. You can also link supported installed MLX models or connect a separately running OpenAI-compatible local server.
- **Model subscriptions:** use supported Codex and Claude Code connections through your configured local sign-in.
- **API providers:** connect your own supported provider or compatible endpoint and API key.

Your Worlds and conversation history stay in Manwe when you switch models. Local model inference runs on your Mac. Cloud inference and connected services receive the context needed for the work you send to them; web research also uses online services. Manwe is not entirely offline. See the [privacy policy](https://askmanwe.com/privacy/).

Some local intelligence features require a newer macOS version. VS Code and Cursor context require Manwe’s editor extension; Xcode context requires Accessibility permission. Container execution requires a running local Docker Desktop engine. Individual Apple app integrations request their respective macOS permissions.

## Background work

With the optional background helper enabled in Manwe and approved in macOS, supported scheduled workflows and watches can run after you quit the app while your Mac is awake. Local-model work waits until Manwe is open.

Advisor background learning runs while Manwe is open, idle and online, within the learning allowances you configure.

## Start here

- [Read the handbook](https://askmanwe.com/handbook/) or [download the PDF](https://askmanwe.com/downloads/manwe-handbook-0.9.9.pdf).
- [See how Manwe works](https://askmanwe.com/how-it-works/) and [explore use cases](https://askmanwe.com/use-cases/).
- [Read release notes and version history](https://github.com/lemberalla/manwe-releases/releases).
- [Join Discord](https://discord.gg/e7q8AfXkx) or email [hello@askmanwe.com](mailto:hello@askmanwe.com) for feedback.

The [web app](https://app.askmanwe.com/) remains available separately from the Mac workspace.

---

Made by Oncel Cebeci · [Tiny Things](https://tinythings.app)
