> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

<!-- Add product-specific terms and preferred usage -->
<!-- Example: Use "workspace" not "project", "member" not "user" -->

## Style preferences

<!-- Add any project-specific style rules below -->

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- `ayuda/` y la pestaña «Ayuda» de `docs.json` se generan desde la ayuda in-app de la consola
  (glosario y preguntas frecuentes; decisión D-6). No se editan a mano: se corrige la ayuda en
  `vigia-console/src/app/core/help/` y se regenera con `npm run help:export && npm run help:mintlify`.

<!-- Define what should and shouldn't be documented -->
<!-- Example: Don't document internal admin features -->
