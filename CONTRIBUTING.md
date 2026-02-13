# Contributing to BridgeAgent

First of all: thank you.
BridgeAgent is not just a collection of prompts — it is a structured framework for disciplined AI-driven software development. 
Before contributing, please read this document carefully.

## 🧠 Philosophy First
BridgeAgent follows a strict architectural doctrine defined in:
- `core/manifesto.md`
- `core/workflow.md`
- `skills/core/`

All contributions must respect:
1. **Architecture is unidirectional:** User → Architect → Engineer → QA.
2. **No agent breaks its role.**
3. **No code is written without a SPEC.**
4. **Context > Speed. Clarity > Assumption.**

If your contribution violates any of these principles, it will not be accepted.

## 🏗️ What You Can Contribute
We welcome contributions in the following areas:

### 1. Skills (`skills/`)
Examples: system-design frameworks, logic reasoning patterns, UI/UX heuristics, or domain-specific extensions (Web3, ML, Automation, etc.).
- Must be modular.
- Must not override core philosophy.
- Must define its goal and reasoning structure.

### 2. Extensions (`skills/extensions/`)
These add domain intelligence without modifying the core.
- Must be optional.
- Not interfere with Core rules.

### 3. Templates (`templates/`)
Structured project starters including `SPEC.md`, `TASK.md` and clear context.

## 🚫 What NOT to Contribute
- Random prompt collections.
- Role-breaking agent modifications.
- Code generators without QA flow.
- Anything that bypasses SPEC-first design.

## 🧪 Contribution Standards
Before submitting a Pull Request, ask yourself:
1. Does this respect the Manifesto?
2. Does this increase clarity?
3. Does this reduce hallucination risk?
4. Is this modular?

## 🛠️ How to Submit
1. Fork the repository.
2. Create a feature branch: `feature/skill-name`.
3. Keep commits clean and descriptive.
4. Submit a Pull Request explaining the problem it solves and its fit in the architecture.

---
*Build with rigor. Think before generating. Respect the system.*
