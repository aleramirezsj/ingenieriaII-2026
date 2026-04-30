# Copilot Instructions

## Project overview

- This repository contains coursework for **Ingenieria II** focused on client-side web development.
- The current site is a **single static page** served directly from the repository root.
- `index.html` is the entry point and currently contains all rendered UI.
- Bootstrap 5.3.8 is loaded from the jsDelivr CDN inside `index.html`; there is no package manager, bundler, or asset pipeline.
- Local assets are referenced with relative paths from `index.html`, such as `img/riverplate.webp`.
- `css/` and `js/` already exist as folders for future expansion, but they are not currently wired into `index.html`.

## Build, test, and lint

- There are currently **no repository-defined build, test, or lint commands**.
- There is no `package.json`, test runner config, or linter config in the repo, so do not assume npm scripts or single-test commands exist.
- For manual preview, open `index.html` in a browser or serve the repository root as static files.

## Key conventions

- Keep page content in **Spanish** unless the surrounding content is being intentionally translated.
- Prefer changes that keep the project working as a **plain static site**: HTML, CSS, JavaScript, images, and CDN includes.
- If you add local CSS or JavaScript, explicitly link it from `index.html`; nothing in the repo auto-discovers assets.
- Preserve simple relative paths from the root page (`img/...`, future `css/...`, `js/...`) so the site still works when opened directly in a browser.
- Reuse Bootstrap utility classes before introducing custom structure or extra dependencies, because the current page styling depends on Bootstrap being present globally.

## MANDATORY INSTRUCTIONS
- Hablame en español, por favor. No quiero que me hables en inglés.

## Recomendaciones
- Cada vez que ingreses un nuevo código, inserta un comentario en español que explique las etiquetas utilizadas
- los ejemplos y el contenido en general necesito que esten en español
