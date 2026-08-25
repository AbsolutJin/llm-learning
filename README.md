# LLM Learning

A self-paced roadmap from **full-stack developer → LLM engineer** — going from zero machine-learning knowledge to genuinely understanding how large language models work and building LLM-powered apps. Every concept is tested against local models running on your own machine.

**▶ Live roadmap:** https://absolutjin.github.io/llm-learning/

## What this is

An interactive, single-page study plan. Reading-first, lab-backed, and paced at ~5–8 hrs/week over **14 weeks**. Progress (checkpoints) is stored locally in your browser — no account, no backend.

The guiding idea: *read a little, then poke it.* After every concept there's a hands-on lab you run against your own local models, so an observed idea sticks better than a read one.

## The path

| Phase | Weeks | Focus |
|-------|-------|-------|
| **A** | 1–2   | Python for developers — idioms, tooling, the Pythonic mindset |
| **B** | 3–4   | ML & neural-net foundations — just enough ground floor |
| **C** | 5–8   | How LLMs actually work — tokens, attention, training & sampling, quantization |
| **D** | 9–10  | Working with LLMs in practice — the API, structured output, prompt engineering |
| **E** | 11–14 | Building LLM-powered apps — chat app, RAG, tool calling, agents + capstone |

A future phase (training & fine-tuning your own models) waits at the end — for once the rest feels solid.

## How to use

1. Open the [live page](https://absolutjin.github.io/llm-learning/).
2. Go in order — each phase builds on the last.
3. Do the labs, not just the reading.
4. Tick the checkpoints as you go; your progress saves automatically in that browser.

## Local setup

The labs assume a local LLM server (llama.cpp-style, OpenAI-compatible API at `http://127.0.0.1:8080`) running your own quantized models. Tokenization, sampling, quantization and API labs all run against that setup.

---

*Personal learning project — built for one setup and one goal.*
