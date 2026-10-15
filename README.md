# Clear

A clean browser task manager that evolves the original add/delete list into a usable daily-planning tool.

## Features

- Add tasks with high, medium or low priority and optional due dates
- Mark tasks complete, delete tasks, or clear completed work
- Filter all, active and completed tasks
- Keeps tasks in the browser with `localStorage`
- Responsive, keyboard-friendly interface with no build step

Open `index.html` in a modern browser to run it.

## Quality and deployment

[![Validate and deploy site](https://github.com/Fakude/TO-DO/actions/workflows/pages.yml/badge.svg)](https://github.com/Fakude/TO-DO/actions/workflows/pages.yml)

The GitHub Actions workflow validates `list.js` on pushes and pull requests, then deploys successful `main` branch updates to GitHub Pages. Main files: `index.html`, `list.css`, `list.js`, and `.github/workflows/pages.yml`.
