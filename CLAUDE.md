# Build Without Code

A Quarto book teaching non-technical founders to build web and mobile apps using Claude Code.

## Project Overview

- **Format**: Quarto book (.qmd files)
- **Output**: HTML and PDF
- **Audience**: Non-technical founders and product owners
- **Goal**: Teach the *process* of AI-assisted development, not specific tech stacks

## File Structure

```
cc_book/
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Preface
├── chapters/
│   ├── 01-introduction.qmd
│   ├── 02-terminal-basics.qmd
│   ├── 03-installing-claude-code.qmd
│   ├── 04-understanding-landscape.qmd
│   ├── 05-designing-with-ai.qmd
│   ├── 06-version-control.qmd
│   ├── 07-building.qmd
│   ├── 08-running-testing.qmd
│   ├── 09-quality-assurance.qmd
│   ├── 10-deploying.qmd
│   └── 11-growing-project.qmd
└── assets/              # Images (if needed)
```

## Conventions

### Example Prompts
Use Quarto callout syntax for example prompts:
```markdown
:::{.callout-tip}
## Example Prompt
"Your example prompt here"
:::
```

### Tone & Style
- Conversational and encouraging
- No jargon without inline explanation
- Focus on empowerment, not hand-holding
- No emojis unless explicitly requested
- One clear path (avoid presenting multiple options)

### Content Guidelines
- Define terms inline as they appear (no separate glossary)
- Guide readers through what AI *can't* do (account creation, app store submission, etc.)
- Keep it focused: 20-30 pages total

## Build Commands

```bash
# Preview the book (opens in browser with live reload)
quarto preview

# Build HTML output
quarto render --to html

# Build PDF output
quarto render --to pdf

# Build both formats
quarto render
```

## Output

Generated files go to `_output/` (excluded from git).
