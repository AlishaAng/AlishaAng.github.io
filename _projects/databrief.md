---
title: "DataBrief: AI-Powered Local Data Reports"
excerpt: "A privacy-first desktop app that analyses CSV files and generates plain English or technical reports using a local AI model — no cloud, no data exposure."
collection: projects
date: 2026-02-28
---

Tech: Python · JavaScript · React · FastAPI · Ollama · LLM · local AI

## DataBrief Tool

*DataBrief* is a privacy-first desktop application that analyses CSV files and generates clear, readable reports using a local AI model. It produces two types of output: a plain English summary for stakeholders, or a technical breakdown with code fixes for data teams — all without sending any data to the cloud.

The app runs entirely on your machine via [Ollama](https://ollama.com), with a React frontend and Python/FastAPI backend. Uploaded files are read into memory and discarded immediately after the report is generated, so your data never leaves your computer.

Key features include:
- **Dual report modes** — stakeholder-friendly plain English summaries, or technical breakdowns with suggested code fixes
- **100% local AI** — powered by Ollama (llama3), with no external API calls or subscriptions
- **Privacy by design** — files are never stored; nothing is sent to any external server
- **Simple setup** — one-command launch via `start.sh`

## My Contributions

- Designed and built a full-stack local AI application for automated data quality reporting • Integrated a locally-running LLM (via Ollama) with a React frontend and FastAPI backend • Prioritised privacy-first architecture — no cloud dependency, no data retention • Built for both technical and non-technical audiences with dual report modes.

### Links:

[GitHub](https://github.com/AlishaAng/databrief)