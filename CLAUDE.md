# CLAUDE.md

Project guide for Claude Code. Read [AGENTS.md](AGENTS.md) for full architecture, conventions, and how to add a lesson — it is the canonical developer guide.

## ⚠️ Bilingual parity rule (must follow)
Every lesson exists as a Bangla (`lessons/NNNN-name.html`) and English (`lessons/NNNN-name-en.html`) twin with fully duplicated markup + JS. Any change to a feature, widget, button, or script in one file MUST be applied to its twin in the same task — translate only user-facing text; keep logic, IDs, and structure identical. Before finishing, diff the pair (e.g. counts of `<button`, `onclick=`, `function `) to confirm parity.
