# 🏎️ Tuning the AI Racecar

A Generative AI experiment inspired by Formula 1 engineering — testing how small prompt tweaks and design decisions affect LLM performance, accuracy, and latency.

## 📌 Overview

In Formula 1, a 2mm change in front wing angle can mean the difference between pole position and crashing out. This project explores how similar “micro-decisions” in GenAI — like rewording a prompt or changing context window size — produce outsized effects on a system’s behavior.

## 🎯 Goal

Use **Vertex AI**, **LangChain**, and structured prompt experimentation to:

- Identify how subtle prompt tweaks affect hallucination rate
- Measure latency and cost trade-offs under different settings
- Visualize prompt performance like lap times on an F1 circuit
- Encourage systems-level thinking in GenAI application design

## 🛠️ Tech Stack

- 🧠 Vertex AI / Gemini
- 🔗 LangChain
- 📊 BigQuery (optional for logging)
- 📈 Python + Matplotlib for visualizations
- 📓 Jupyter / Google Colab

## 📁 Repo Structure

- `notebooks/` → all experiments and evaluation runs
- `data/` → prompts, context documents, configs
- `results/` → output generations, latency logs, plots
- `paper/` → academic-style writeup (for arXiv or PDF)

## 🚀 Roadmap

- [ ] First experiment: prompt tone vs hallucination rate
- [ ] Benchmarking latency + token usage
- [ ] Radar charts comparing prompt types
- [ ] Medium article + GitHub showcase
- [ ] Optional arXiv submission (structured paper format)

## 📖 Inspired By

- *How to Build a Car* by Adrian Newey
- OpenAI, Anthropic, and Google AI system papers

## 👋 Author

Sanjit Sharma — technology consultant, systems thinker, and machine learning engineer in the making.

https://www.linkedin.com/in/sanjitsharma1/
