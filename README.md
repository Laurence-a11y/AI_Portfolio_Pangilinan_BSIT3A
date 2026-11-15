# Rence — Portfolio

Personal portfolio of Laurence R. Pangilinan (BSIT-3A, Angeles University Foundation).
Plain HTML, CSS and JavaScript. No build step and no dependencies.

## Files

```
index.html      page markup and templates
css/style.css   all styles and animations
js/app.js       content, project data and interactions
assets/img/     photos and screenshots
```

## Editing

- **Project text and screenshots:** `js/app.js`, inside `const PROJ = [ ... ]` (projects 01–10, in order).
- **AI cards and prompting examples:** `js/app.js`, inside `ais: [ ... ]`, `const prompts = [ ... ]` and `const habits = [ ... ]`.
- **About, reflection and contact text:** `index.html`, inside `<template id="tpl-main">`.
- **New images:** put them in `assets/img/` and reference them as `assets/img/your-file.png`.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server` in this folder and visit http://localhost:8000.
