# R&D — Machine Learning, Deep Learning & AI

Production-grounded notes on ML/DL/AI systems — same philosophy as the
[System Design & Architecture](https://github.com/abhibatsa/architecting-software)
repo: requirement to production, not textbook theory. Built from systems
actually shipped (recommendation engines, resume-scoring pipelines, threat
detection, generative content systems), not research reconstructions.

This repo consolidates what would otherwise have been two separate planned
repos (Agentic AI & GenAI, and Prompt Engineering) into one home for
everything ML/AI-adjacent — narrower repos fragment an already-niche
audience; one well-organized repo compounds authority faster.

## 🗺️ Structure

| # | Folder | Covers |
|---|---|---|
| 01 | [Machine Learning Fundamentals](./01-machine-learning-fundamentals) | Supervised/unsupervised learning, bias-variance, feature engineering, evaluation metrics |
| 02 | [Deep Learning & Neural Networks](./02-deep-learning-and-neural-networks) | Perceptrons, backprop, CNNs, RNNs/LSTMs, transformer architecture |
| 03 | [Data Science](./03-data-science) | Statistics for engineers, experimentation/A-B testing, data pipeline design |
| 04 | [Information Retrieval & Search](./04-information-retrieval-and-search) | Ranking, embeddings, vector search, recommendation systems |
| 05 | [NLP & LLMs](./05-nlp-and-llms) | Tokenization, embeddings, attention, fine-tuning, evaluation |
| 06 | [Agentic AI & GenAI](./06-agentic-ai-and-genai) | Agent architecture, tool use, orchestration, eval systems |
| 07 | [Prompt Engineering](./07-prompt-engineering) | Production prompting patterns, not prompt-hacking tricks |
| 08 | [Case Studies](./08-case-studies) | Full requirement-to-production write-ups of real ML/AI systems built |
| 09 | [Interview Prep](./09-interview-prep) | ML/AI system design and applied-ML interview questions |

## Why this repo exists, specifically

Most "learn AI/ML" content on GitHub is either pure theory (math-heavy,
no production concerns) or pure tooling tutorials (how to call an API,
no systems thinking). This repo sits in the gap: how do you actually
architect, evaluate, and ship an AI system — multi-tenant usage metering,
eval pipelines that catch regressions before users do, agent architectures
that fail gracefully, not just demo well.

## 📬 Beyond the repo

Same model as the flagship repo — content here stays free. Deeper,
applied work happens through:
- **Newsletter / YouTube:** [links]
- **Consulting / Advisory:** [FuturestaQ link] — for teams building or
  hardening their own AI/agentic systems

## 🤝 Contributing

Same standards as the flagship repo — see its
[CONTRIBUTING.md](https://github.com/abhibatsa/architecting-software/blob/main/CONTRIBUTING.md)
for the style guide (real numbers over vague claims, "what we'd do
differently" is non-negotiable on every case study).

## 📄 License

MIT (recommended, matches the flagship repo — maximizes reuse/sharing).
