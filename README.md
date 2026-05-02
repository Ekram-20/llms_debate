# Multi-Agent Debate Reproduction

This project reproduces the paper:

> **Improving Factuality and Reasoning in Language Models through Multiagent Debate**  
> https://composable-models.github.io/llm_debate/

## Overview

The project implements a multi-agent debate framework where multiple LLM agents:
    1. Generate answers independently
    2. Critique each other’s responses
    3. Refine their answers through multiple debate rounds
    4. Produce a final improved answer

The goal is to evaluate whether collaborative reasoning improves accuracy and reduces hallucinations compared to a single-agent approach.

## Setup

1. Create a dedicated Python environment and activate it:

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
