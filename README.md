# ICLR 2027 incremental revision: Remember What You Thought, Not What You Said

LaTeX source for the conservative incremental revision. This version retains
the original paper's structure and every original figure, while adding the
corrected v3 measurement, scale, Alignment, and RL-QA experiments in yellow.

- `main.tex` — root file (compile with `latexmk -pdf main.tex`)
- `sections/` — paper sections (intro, related, setup, results, extensions, conclusion, appendix)
- `tables/` — all tables, auto-generated from raw experiment records
- `figures/` — all figures (PDF), auto-generated
- `references.bib` — bibliography (33 entries, audited)

Change `\showupdatestrue` to `\showupdatesfalse` in `main.tex` for a clean
copy. The anonymous ICLR submission mode is enabled; restore authors and
uncomment `\iclrfinalcopy` only for a camera-ready version.
