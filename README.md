# SCPS Tech Hub

Instructional technology guides for Shenandoah County Public Schools.

Built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

---

## Getting Started (First-Time Setup)

### 1. Install Python (if you don't have it)

Download Python from [python.org](https://www.python.org/downloads/). During installation, **check the box that says "Add Python to PATH"**.

### 2. Install MkDocs and the Material theme

Open a terminal (Command Prompt on Windows, Terminal on Mac) and run:

```bash
pip install mkdocs mkdocs-material
```

### 3. Clone or download this project

If using Git:
```bash
git clone https://github.com/YOUR-USERNAME/scps-tech-hub.git
cd scps-tech-hub
```

Or just download and extract the ZIP file.

### 4. Preview the site locally

```bash
mkdocs serve
```

Then open your browser to [http://127.0.0.1:8000](http://127.0.0.1:8000)

The site will auto-refresh when you save changes to any file.

---

## Daily Workflow

Your day-to-day workflow is simple:

1. **Write or edit a guide** — Open any `.md` file in the `docs/` folder with a text editor (VS Code recommended)
2. **Preview your changes** — Run `mkdocs serve` and check the site in your browser
3. **Deploy** — Run `mkdocs gh-deploy` to publish to GitHub Pages

That's it. Three steps.

---

## Adding a New Guide

1. Create a new `.md` file in the appropriate folder (e.g., `docs/tools/canvas/create-assignment.md`)
2. Write the guide using Markdown (see existing guides for examples)
3. Add the guide to the `nav` section in `mkdocs.yml`
4. Preview with `mkdocs serve`
5. Deploy with `mkdocs gh-deploy`

---

## Adding a New Tool

1. Create a new folder under `docs/tools/` (e.g., `docs/tools/newtool/`)
2. Add an `index.md` landing page for the tool
3. Add individual guide `.md` files
4. Update the `nav` section in `mkdocs.yml`
5. Update `docs/tools/index.md` to list the new tool

---

## Deploying to GitHub Pages

### First time:
1. Create a GitHub repository (e.g., `scps-tech-hub`)
2. Push this project to the repo
3. Run `mkdocs gh-deploy`
4. Your site will be live at `https://YOUR-USERNAME.github.io/scps-tech-hub/`

### Every time after:
```bash
mkdocs gh-deploy
```

One command. Done.

---

## Project Structure

```
scps-tech-hub/
├── mkdocs.yml              # Site configuration (navigation, theme, plugins)
├── README.md               # This file
└── docs/                   # All content lives here
    ├── index.md            # Homepage
    ├── tools/              # Guides organized by tool
    │   ├── index.md
    │   ├── masteryconnect/
    │   │   ├── index.md
    │   │   ├── setup-tracker.md
    │   │   ├── link-to-canvas.md
    │   │   ├── create-assessment.md
    │   │   ├── item-bank.md
    │   │   ├── administer-assessment.md
    │   │   ├── bubble-sheets.md
    │   │   ├── reading-tracker.md
    │   │   ├── running-reports.md
    │   │   └── grouping-students.md
    │   ├── canvas/
    │   ├── google-classroom/
    │   ├── gemini/
    │   ├── lightspeed/
    │   └── diffit/
    ├── tasks/              # Guides organized by task
    │   ├── index.md
    │   └── (task pages)
    ├── quickstart/         # 5-minute quick start guides
    │   └── index.md
    └── about/              # About and contributing info
        ├── index.md
        └── contributing.md
```

---

## Markdown Quick Reference

| What You Want | What You Type |
|---------------|---------------|
| **Bold text** | `**Bold text**` |
| *Italic text* | `*Italic text*` |
| A link | `[link text](url)` |
| An image | `![alt text](path/to/image.png)` |
| A heading | `## Heading Level 2` |
| A numbered list | `1. First item` |
| A bullet list | `- Item` |
| A tip box | `!!! tip "Title"` followed by indented content |
| A warning box | `!!! warning "Title"` followed by indented content |
| A collapsible section | `??? question "Title"` followed by indented content |
| A code block | Triple backticks around the code |
| A table | `| Header | Header |` with `|--------|--------|` separator |
