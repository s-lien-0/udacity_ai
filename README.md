# Projects — Udacity Master’s in AI

This repository is a running record of my work through Udacity’s *Master’s in AI* learning path.
Each folder represents a concrete deliverable: a project with a clear goal, a reproducible setup,
and an executable entrypoint.

---

## Repository structure

```
udacity_ai/
├── course-1/
│   ├── project-1/
│   └── project-2/
└── course-2/
    ├── project-1/
    └── project-2/

```

Each project should be self-contained and follow a predictable layout:

```
project-name/
├── README.md
├── src/
├── tests/              # optional
├── requirements.txt    # or pyproject.toml
├── data/               # optional; typically gitignored
└── outputs/            # optional; typically gitignored
```

---

## Running a project

Each project folder includes its own `README.md` with the exact commands.

Typical setup:

```bash
cd udacity/<course>/<project>
python -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
pip install -r requirements.txt
python -m src.main
```

If a project uses a different entrypoint (CLI, Streamlit, notebook runner, etc.), it should be documented in that project’s README.

---

## Standards

A project is considered complete when it includes:
- `README.md` with purpose, setup, run commands, and expected outputs
- pinned dependencies (`requirements.txt` or `pyproject.toml`)
- reproducible runs where practical (seeded training, fixed splits)
- no large binaries committed to git

---

## Progress

### Core
- [ ] Core 1 — AI Programming with Python
- [ ] Core 2 — Data Analyst
- [ ] Core 3 — TBD
- [ ] Core 4 — TBD
- [ ] Core 5 — TBD
- [ ] Core 6 — TBD
- [ ] Core 7 — TBD

### Electives
- [ ] Elective 1 — TBD
- [ ] Elective 2 — TBD
- [ ] Elective 3 — TBD

---

## License

Personal learning repository.
Udacity-provided starter code/assets remain under their original terms.
