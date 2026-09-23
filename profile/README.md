<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://www.eversynced.com/assets/logo-secondary.svg">
    <img src="https://www.eversynced.com/assets/logo-primary.svg" alt="Eversynced" width="360">
  </picture>

  <h3>Every nearshore company claims they use AI. We actually measure it.</h3>
  <p>Senior LATAM product engineers, working inside an instrumented AI delivery framework.</p>

  <a href="https://eversynced.com">
    <img src="https://img.shields.io/badge/Website-285071?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  <a href="https://pheebs.ai">
    <img src="https://img.shields.io/badge/📡_Meet_Pheebs-E38750?style=for-the-badge" alt="Meet Pheebs">
  </a>
</div>

## Why Eversynced?

The nearshore market is saturated with "we use AI." Nobody can show you what that means inside a session: which models get used, whether tests run before a commit, how often AI output gets challenged before it ships.

We built a framework that proves it. Every Eversynced engineer operates inside it, contributes to it, and is measured by it. We then open-sourced the measurement tool so any team can run the same check on itself.

**Engineering company first. Nearshore second.**

## What's here

### Pheebs
<a href="https://github.com/Eversynced/pheebs">
  <img align="right" src="https://img.shields.io/badge/Open_Source-Apache_2.0-285071?style=for-the-badge&logo=github&logoColor=white" alt="Open source">
</a>

**[pheebs](https://github.com/Eversynced/pheebs)** - Local-first telemetry for AI coding agents  
Installs as lifecycle hooks in Claude Code, Cursor, and Codex, plus OpenTelemetry export where the agent supports it. Writes one JSONL line per event to your own machine and sends to a backend you control, if implemented and configured.

```bash
npm install -g pheebs   # Install
pheebs init             # Interactive setup, all three agents
pheebs doctor           # Check the wiring
```

<br clear="right"/>

### The AI Proficiency Model
<a href="https://github.com/Eversynced/pheebs/blob/main/docs/ai-proficiency-model.md">
  <img align="right" src="https://img.shields.io/badge/Versioned_Document-E38750?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Versioned document">
</a>

**[ai-proficiency-model.md](https://github.com/Eversynced/pheebs/blob/main/docs/ai-proficiency-model.md)** - Proficiency = repertoire + quality signals  
A versioned document describing the practices and signals that matter when working with AI agents. It gives structure to what would otherwise be a stream of raw events, and it is published on its own so it can evolve in the open and be adopted beyond Pheebs.

- **Layer 1, repertoire.** Twenty-four practices across six competencies: Models, Artifacts, MCP, Evals, Context management, Orchestration. Each is either Unobserved, Adopted, or Recurring.
- **Layer 2, quality signals.** Verification coverage, pushback rate, refinement-to-repair ratio, and wholesale-accept rate. What happens to AI output before it ships.

<br clear="right"/>

### Backend contract
<a href="https://github.com/Eversynced/pheebs/blob/main/docs/backend-contract.md">
  <img align="right" src="https://img.shields.io/badge/Self--host_it-7CDFEF?style=for-the-badge&logo=serverfault&logoColor=black" alt="Self-host">
</a>

**[Backend contract](https://github.com/Eversynced/pheebs/blob/main/docs/backend-contract.md)** — Five routes, and a reference implementation in the repo  
Pheebs holds a base URL and a token, nothing else. Stand up your own backend and telemetry goes from your developers' machines to your infrastructure. Pheebs never sees it.

<br clear="right"/>

## Get in touch

<div align="center">
  <a href="https://eversynced.com">
    <img src="https://img.shields.io/badge/Website-285071?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  <a href="https://www.linkedin.com/company/eversynced/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://eversynced.com/blog">
    <img src="https://img.shields.io/badge/Blog-E38750?style=for-the-badge&logo=rss&logoColor=white" alt="Blog">
  </a>
  <a href="https://eversynced.com/join-us">
    <img src="https://img.shields.io/badge/Join_us-7CDFEF?style=for-the-badge&logo=rocket&logoColor=black" alt="Join us">
  </a>
  <a href="mailto:info@eversynced.com">
    <img src="https://img.shields.io/badge/Email-FFE7BA?style=for-the-badge&logo=gmail&logoColor=black" alt="Email">
  </a>
  <a href="https://calendly.com/eversynced/meet-with-us">
    <img src="https://img.shields.io/badge/📅_Schedule_a_call-F9D649?style=for-the-badge&logoColor=black" alt="Schedule a call">
  </a>
</div>
