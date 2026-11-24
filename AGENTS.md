# Project layout

This is a single-file web app. Keep the required top-level files here:

- `index.html`: the GitHub Pages entry point and the only application file.
- `spec.md`: project requirements and behavior specifications.
- `AGENTS.md`: project structure and working rules.
- `prompts.md`: a log of requests and outcomes.

Numbered folders contain supporting project files:

- `00_planning/`: notes and sketches.
- `01_data/`: data files.
- `02_validation/`: hand calculations and test cases.
- `03_output/`: screenshots and exported results.

Save every new file in the folder that matches its purpose. Keep app implementation in top-level `index.html` unless the request explicitly requires a supporting file in one of the numbered folders.

After each request, add an entry to `prompts.md`: what was asked, what changed, and whether it worked.