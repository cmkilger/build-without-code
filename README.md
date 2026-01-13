# Build Without Code

A Non-Technical Guide to Creating Apps with AI

## About

This guide teaches non-technical founders and product owners how to build web and mobile applications using Claude Code. Rather than teaching programming, it teaches the *process* of working effectively with AI to turn ideas into working software.

## Prerequisites

- [Quarto](https://quarto.org/) - Install with `brew install quarto`

## Building the Book

```bash
# Preview with live reload
quarto preview

# Build HTML version
quarto render --to html

# Build PDF version
quarto render --to pdf

# Build all formats
quarto render
```

Output files are generated in the `_output/` directory.

## Project Structure

```
├── _quarto.yml          # Book configuration
├── index.qmd            # Preface
├── chapters/            # Book chapters (01-11)
├── assets/              # Images and other assets
├── CLAUDE.md            # Project context for Claude Code
└── README.md            # This file
```

## Chapters

1. Introduction
2. Getting Started with the Terminal
3. Installing Your CLI Assistant
4. Understanding the Landscape
5. Designing Your Project with AI
6. Version Control with GitHub
7. Building with Your CLI Assistant
8. Running and Testing Your Project
9. Quality Assurance with AI
10. Deploying Your Project
11. Growing Your Project

## Author

Cory Kilger

---

*This guide was written using Claude Code.*
