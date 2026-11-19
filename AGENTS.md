# Project layout

This is a single-file web app. GitHub Pages serves the app from `index.html` at the top level.

- `AGENTS.md` - project instructions and conventions
- `spec.md` - the project specification
- `prompts.md` - a log of requests and outcomes
- `index.html` - the complete web app
- `00_planning/` - planning notes and sketches
- `01_data/` - data files
- `02_validation/` - hand calculations and test cases
- `03_output/` - screenshots and exported results

Save every new file in the folder that matches its purpose: planning and sketches in `00_planning/`, data in `01_data/`, validation work in `02_validation/`, and generated screenshots or exports in `03_output/`. Keep implementation in the top-level `index.html` rather than creating additional source folders or files.

After each request, add an entry to `prompts.md`: what I asked, what you changed, and whether it worked.