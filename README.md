# MSc Fall 2026

Semester repository for the AI MSc. Each course lives in `courses/` as a submodule, so the semester folder records which commit of each course belongs to this term.

## Courses

| Course | Path | Repository |
|---|---|---|
| Deep Generative Models | [courses/DGM_25855](courses/DGM_25855) | [AliNikkhah2001/DGM_25855](https://github.com/AliNikkhah2001/DGM_25855) |

Homework 1 (study sheet, teaching guide, written solutions, coding assignment) and Homework 2 (theoretical sheet, VAE notebook, and normalizing-flow notebook) are published from the course repository.

## Clone

```bash
git clone --recurse-submodules https://github.com/AliNikkhah2001/MSc_Fall_2026.git
```

If the semester was cloned without its courses:

```bash
git submodule update --init --recursive
```

This semester is itself a submodule of [AI_MSc](https://github.com/AliNikkhah2001/AI_MSc).
