# Python Basics — Learning Repository

> **Status:** beginner practicing Python from scratch to build a solid foundation.

Welcome! This repository is my study space — a **logbook of my first contact with Python**. You’ll find **lessons, exercises, and small practices** focused on consolidating fundamentals (e.g., **classes, lists, functions**) and starting to explore libraries like **Pandas**.

## Goals
- Track my progress as a **beginner** in Python.
- Keep simple, commented examples I can review later.
- Centralize **lessons** and **practice**: from **classes** to **lists**, including **functions** and **Pandas**.

## What’s inside
- Pandas (dataframes, basic exploration)
- Functions in Python (`def`, parameters, return)
- Lists (creation, slicing, methods)
- Small utility projects (e.g., converters)
- Exercise sets and guided practice
- Class notes and notebooks
- Assessments / simulated exams

## Current structure (summary of what’s included)
```
📄 AV 4
📄 Aula 10, Lista de Exercicios VIII, Listas
📄 Aula 9, Lista de Exercicios V, Funções em ´def´
📄 Aula 9, Lista de Exercicios VII, Funções em ´def´.ipynb
📄 Aula 9, def
📄 Conversor Básico.ipynb
📄 Exercícios Extras.ipynb
📄 Exercícios Propostos.ipynb
📄 Missão 1.sql
📄 Missão 2.sql
📄 Missão 3.sql
📄 Missão 4.sql
📄 Missão 5.sql
📄 Missão 6.sql
📄 Pandas Exploration.ipynb
📄 README_SQL.md
📄 README_SQL_EN.md
```

> Note: filenames follow the naming used in my course/class materials and may change as I reorganize.

## How to use
1. **Clone** the repository and open it in VSCode (or Jupyter):
   ```bash
   git clone <REPO-URL>
   cd <REPO-FOLDER>
   ```
2. (Optional) **Create a virtual environment** and install basic dependencies for notebooks:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -U pip
   pip install pandas jupyter ipykernel
   ```
3. **Run notebooks**:
   ```bash
   jupyter notebook
   ```
   or open them directly in **VSCode** with the “Jupyter” extension.

## Learning roadmap (draft)
- [X] Fundamentals: types, variables, `input()`, `print()`
- [X] Control flow: `if`, `for`, `while`
- [X] **Lists**, tuples, dictionaries; list/dict comprehensions
- [X] **Functions** (`def`, parameters, `return`, scope)
- [ ] **Classes** and OOP (attributes, methods, `__init__`)
- [X] **Pandas**: `Series`, `DataFrame`, reading CSV, `head()`, `info()`
- [ ] Best practices: naming, folder organization, `requirements.txt`
- [ ] Basic tests with `pytest`
- [ ] Mini‑projects: converters, small games, automations

## Conventions & good practices
- Large/generated files (datasets, `.ipynb_checkpoints/`) stay out of Git.
- Use a **`.gitignore`** to avoid committing unnecessary files.
- Commit early and small, with clear messages (e.g., `feat: add list exercises`, `fix: pandas example`).

## What I plan to add
- `requirements.txt` and/or `environment.yml`
- A `data/` folder with tiny sample datasets (or links to public data)
- A `LICENSE` (likely MIT) and an English + Portuguese description
- A `projects/` folder with small applied challenges

---

> **Note for recruiters/mentors:** this repo shows my early progress. Feedback is very welcome!
