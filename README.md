# Mathematical Foundations of AI Safety — SISSA 2026

Personal notes, code, and resources from the **SISSA School on the Mathematical Foundations of AI Safety**,  
held at SISSA (Scuola Internazionale Superiore di Studi Avanzati), Trieste, Italy, November 16–27, 2026.

**School website:** https://sites.google.com/view/mathaisafetysissa  
**GitHub Pages:** https://CristopherErazo.github.io/sissa-ai-safety-school-2026/

## Repository Structure

```
sissa-ai-safety-school-2026/
├── docs/                    # GitHub Pages website (Nerfies/Bulma)
│   ├── index.html
│   └── static/css/
├── lectures/
│   ├── notes/               # Lecture notes (.md, with LaTeX)
│   │   └── TEMPLATE.md      # Copy this for each new lecture
│   └── material/            # Slides/PDFs (when publicly shared)
├── tutorials/               # Hands-on sessions (.ipynb)
├── summary/                 # Weekly and overall summaries
├── pyproject.toml           # Python environment (uv)
└── README.md
```

## Topics

**Week 1 — Foundations of AI Alignment (Nov 16–20)**
- Why is AI dangerous? AI alignment as a mathematical problem
- How AI labs align their AIs; control of misaligned AIs
- Scalable oversight, debate, and locally consistent arguments
- Agent foundations, multi-agent systems, open-source game theory
- Solomonoff induction, abstractions, and world models
- Formal verification with Lean

**Week 2 — Deep Learning & Singular Learning Theory (Nov 23–27)**
- Mysteries of deep learning (double descent, grokking, emergence)
- Singular learning theory (Watanabe's framework, RLCT)
- Mathematical AI safety problem labs

## Setup

This project uses [uv](https://docs.astral.sh/uv/) for Python environment management.

```bash
# Install uv if needed: https://docs.astral.sh/uv/getting-started/installation/
uv sync
```

Run Jupyter notebooks:

```bash
uv run jupyter lab
```

## Notes Format

Lecture notes are written in Markdown with LaTeX math:
- Inline math: `$f(x) = x^2$`
- Display math: `$$\int_0^\infty f(x)\,dx$$`

Renders natively in VS Code (with [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)) and Obsidian.  
To create a new note, copy `lectures/notes/TEMPLATE.md` and fill in the fields.

---

*Topics: ai-safety, ai-alignment, singular-learning-theory, lean, solomonoff-induction, agent-foundations, scalable-oversight*
