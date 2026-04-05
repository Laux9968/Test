# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Project Overview

A minimal beginner HTML/JavaScript learning project hosted on GitHub. The repository contains a single interactive HTML page that demonstrates basic DOM manipulation with vanilla JavaScript.

**Repository**: `Laux9968/Test`
**Author**: Laux9968 (mrlaux@gmail.com)

## Repository Structure

```
Test/
└── Test        # Single HTML file — the entire project
```

There is no build system, package manager, test framework, or CI/CD configuration. This is a static HTML project with no dependencies.

## The Main File: `Test`

A standalone HTML page (`Test`) that:
- Displays a heading and a paragraph
- Has a button wired to `changeText()` via an `onclick` attribute
- On click, replaces the paragraph text using `document.getElementById().innerHTML`

No external scripts, stylesheets, or assets are referenced.

## Development Workflow

### Viewing the page
Open `Test` directly in any browser — no server needed.

### Making changes
Edit `Test` directly. Since there is no build step, changes are immediately visible on reload.

### Running tests
No test infrastructure exists. Manual browser testing is the only approach.

### Linting / formatting
No linters or formatters are configured.

## Git Conventions

- **Development branch**: `claude/add-claude-documentation-dep35`
- **Main branch**: `main`
- Commits have been made via the GitHub web interface; commit messages are short and descriptive (e.g. "Create Test", "Update Test").
- Keep the same style: brief, imperative commit messages.

## Key Conventions for AI Assistants

- **Do not add a build system or package manager** unless explicitly requested.
- **Do not add a DOCTYPE declaration** — the current file intentionally omits it (it was removed in a prior commit).
- **Keep JavaScript inline** inside `<script>` tags within the HTML file; do not split into separate files unless asked.
- **No frameworks** — use plain HTML/CSS/JS only.
- **Branch**: all changes must be committed and pushed to `claude/add-claude-documentation-dep35`.
- Push with: `git push -u origin claude/add-claude-documentation-dep35`
