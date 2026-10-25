# dojo

Step-through trainers and practice pages, served at **https://apsy3677.github.io/dojo/**. Each page is one self-contained HTML file; open it in any browser.

| Folder | Pages |
|---|---|
| `dsa/` | DSA Dojo (pattern cards, quizzes, spaced review, timer), monotonic stack, linked list, Kosaraju, bipartite, DP |
| `cpp/` | condition variable |
| `eda/` | static timing |
| `ai/` | AI evals explained, Applied AI runbook |

## Editing
- **Kit-based trainers** (DP, linked list, condition variable, static timing): edit `trainers-src/_src/*.src.html` or `trainers-src/_kit/*`, then run `./trainers-src/build.sh`. Don't edit the generated pages; their second line says so.
- **Monotonic stack, Kosaraju, bipartite:** hand-written, so edit them directly.
- **`dsa/dojo.html` and `dsa/cards.json`** are built from a private source and published by a script. Don't edit them here; the next publish overwrites any change.
- **Self-test:** open a kit trainer with `#selftest` at the end of the URL.
