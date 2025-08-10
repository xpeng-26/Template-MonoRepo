# 🧪 Template-MonoRepo

[![CI/CD Status](https://img.shields.io/badge/CI/CD-Passing-brightgreen)](https://github.com/xpeng-26/Template-MonoRepo/actions)

> *A brief description of your project.*

---

## Vision & Purpose

**Repo** is to ...

This repository serves two primary purposes:
1.  To build and maintain a suite of robust, production-ready **content automation tools**.
2.  To explore the frontiers of AI content generation through **research and experimentation**.

Ultimately, the goal is to ...

## What's Inside?

This monorepo is organized into two main areas:

### 🚀 Production Workflows

These are stable, usable applications designed to solve specific content creation problems.
* **App 1**: .
* **App 2**: .
* *(More workflows to come...)*

### 🔬 R&D Experiments

This is where we explore cutting-edge techniques and ideas. Work here is experimental and may not be stable.
* **Exp 1**: .
* **Exp 2**: .

## Tech Stack

* **Core Language**: Python
* **Package & Env Management**: UV
* **Testing**: Pytest
* **Web UI**: Streamlit
* **API / Backend Services**: FastAPI
* **Containerization**: Docker
* **Core AI/ML**: OpenAI API, Gemini API, Hugging Face Transformers, PyTorch

## Getting Started

*(This section will be updated with setup and usage instructions soon.)*

1.  Clone the repository: `git clone https://github.com/xpeng-26/Template-MonoRepo.git`
2.  Navigate to the project directory: `cd Template-MonoRepo`
3.  ...

## Roadmap

- [ ] **Q3 2025**: Refine the workflow and onboard the first internal use case.

## Contributing


### Tools

1. `pyenv` to manage the Python virson.
2. `uv` to manage the dependencies. ![UV Project](https://docs.astral.sh/uv/concepts/projects/). ![UV Features](https://docs.astral.sh/uv/getting-started/features/#scripts)
3. `git`
4. `pre-commit` and `ruff`
5. `pytest`

### Creating a new project (subrepos)

```bash
mkdir hello-world
cd hello-world

git init
pyenv local 3.12
uv init

uv add pre-commit
uv add ruff
uv add pytest
```

### Managing dependencies

```bash
# activate the environment
source .venv/bin/activate
# add a new package
uv add requests
# remove a installed package
uv remove requests
# upgrade a installed package
uv lock --upgrade-package requests
```

### Development

```bash
source .venv/bin/activate
uv run example.py
# when calling uv run, it will automaticly lock and sync the environment, which is equvilent to
# uv lock
# uv sync

git add .
# ✨ This command will trigger the pre-commit hooks, automatically running ruff and commitlint
git commit -m "feat: add amazing new feature"
git push origin main
```

---
Made with ❤️ and a little bit of AI magic.

