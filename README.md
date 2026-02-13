# BridgeAgent: The Vibe-to-Code Framework

> **From Abstract Vibe to Engineering Reality.**
> An operating system for orchestrating AI agents, designed to bridge the gap between creative intent and professional code.

## 🌟 Architecture Overview

The flow is strictly unidirectional to prevent logic loops and hallucinations:

```mermaid
User (The Vibe) 
      ⬇
[ 🏛️ Architect Agent ] ──creates──> 📄 SPEC.md
      ⬇
[ 🔨 Engineer Agent ] ──reads───> 📄 TASK.md
      ⬇
      ├── writes code 
      ⬇
[ 🕵️ QA Agent ] ──────reviews───> 📄 REVIEW.md
      ⬇
✅ Final Output
```

## ⚡ How It Works
BridgeAgent is a protocol for intelligence. It forces the LLM to stop "guessing" and start "engineering".

- **The Architect** acts as a buffer. It interviews you until your idea is crystal clear.
- **The Spec** acts as a contract. No code is written until this file exists.
- **The Engineer** is strictly an executor. It follows the Spec, ensuring best practices (SOLID, DRY).
- **The QA** provides the safety net, ensuring the implementation matches the intent.

## 🔎 Who Is This For?

### 👨‍💻 Senior Developers
BridgeAgent is for developers who are tired of AI hallucinating architecture. It turns AI from a shortcut tool into a disciplined engineering assistant, enforcing role separation and anti-assumption protocols.

### 🚀 Founders & Builders
For entrepreneurs building MVPs and indie hackers who need technical product thinking. It forces clarity before code, reducing project failure dramatically.

### 🏢 Teams & Agencies
A structured AI workflow that enforces predictable behavior and clearer responsibility boundaries, serving as a blueprint for AI-assisted development teams.

## 📦 Installation
To activate BridgeAgent in your LLM (Gemini CLI, Claude, OpenAI), you must load the core contexts.

Load the following directories into your model's memory:
- `/core` (The laws and workflows)
- `/agents` (The personas)
- `/skills` (The reasoning frameworks)

**Initialization Prompt:**
"I have loaded the BridgeAgent framework. Please act as the Architect and help me define my new project."

---
*Created by Oratech*
