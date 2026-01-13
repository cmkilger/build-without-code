# Repository Guidelines

## Project Structure & Module Organization
This repository is a Quarto book. Source content lives in `.qmd` files:
- `index.qmd` is the preface.
- `chapters/` contains ordered chapters (`01-11`), and `_quarto.yml` defines the build order.
- `assets/` holds images and supporting media.
- `styles.scss` customizes the HTML theme.
Build outputs go to `_output/` (generated).

## Build, Test, and Development Commands
Quarto is required (see `README.md`). Key commands:
- `quarto preview` — live-reload preview in a browser.
- `quarto render --to html` — build the HTML book.
- `quarto render --to pdf` — build the PDF book.
- `quarto render` — build all formats (HTML, PDF, EPUB).

## Coding Style & Naming Conventions
- Content is in Markdown/Quarto (`.qmd`). Keep a conversational, non-jargony tone with brief inline definitions.
- Follow the existing chapter numbering pattern: `chapters/NN-topic.qmd`.
- Use Quarto callouts for example prompts:

```markdown
:::{.callout-tip}
## Example Prompt
"Your example prompt here"
:::
```

## Testing Guidelines
No automated tests are configured. Validate changes by running `quarto preview` locally and reviewing rendered output for formatting issues.

## Commit & Pull Request Guidelines
Git history uses concise, imperative, sentence-case messages (e.g., “Add cover image”, “Fix inline code contrast”). Follow that pattern.
For pull requests, include:
- A short description of the change and affected chapters.
- Any related issue or context.
- Screenshots of visual changes (HTML/PDF) when styling or layout is modified.

## Agent Notes
If you are using an AI assistant, review `CLAUDE.md` for tone, callout conventions, and content guidance before drafting chapters.
