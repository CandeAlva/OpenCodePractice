# AGENTS.md

## Project
Static single-page site. No package manager, build step, tests, linter, or CI.

## Structure
- `index.html` — the only entrypoint and the entire site.
- `README.md` — Spanish project overview. Lists HTML/CSS/Tailwind/JavaScript, but only plain HTML exists today; don't assume tooling that isn't there.

## Running
- Open `index.html` directly in a browser, or serve it locally if a server is needed:
  ```sh
  python -m http.server 8000
  ```
- There is no `npm`/`pnpm`/`yarn` workflow and no test or verification command.

## Conventions
- Documentation and user-facing copy are in Spanish; keep that language when editing them.
