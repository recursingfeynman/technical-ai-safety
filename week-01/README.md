# Week 01 — Evals: currently more art than science

## Getting Started

### Prerequisites

- [uv](https://docs.astral.sh/uv/)
- [ollama](https://ollama.com/download)

### Setup

From the repository root:

```bash
cd week-01

uv sync
```

Pull a model (used in the notebook):

```bash
ollama pull deepseek-r1:1.5b
```

Start the Ollama server (keep this terminal open, or run as a service):

```bash
ollama serve
```

## Viewing evaluation logs

To open the Inspect viewer:

```bash
inspect-ai view --log-dir logs/
```
