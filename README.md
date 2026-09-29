# Prompt Lab

An interactive, AI-powered web app for learning prompt engineering by experimentation.

**Live demo:** https://claude.ai/artifact/4mzfmoArcRrHPSvZ9tk8Dh

**Category:** Machine Learning

## Overview

Prompt Lab lets you enter any task or question, switch on individual prompting techniques, and instantly compare a plain AI response against an engineered one for the same task. Instead of reading about prompt engineering, you see its effect live.

## Features

- **Live AI responses** — calls a real language model directly from the browser, no backend server required
- **Technique toggles** — role prompting, tone control, few-shot examples, and chain-of-thought, each switched on independently
- **Plain vs. engineered comparison** — the same task answered two ways, shown side by side
- **Prompt transparency** — a dedicated tab shows the exact engineered prompt text built from your selected toggles
- **Responsive design** — works on desktop and mobile, with light and dark theme support

## Concepts Demonstrated

- Zero-shot vs. engineered prompting
- Role / persona prompting
- Tone and style control
- Few-shot examples
- Chain-of-thought reasoning

## How It Works

1. Type a task or question and select any combination of techniques.
2. Click **Run in the lab**. The app builds an engineered prompt by layering instructions for each selected technique on top of your raw task.
3. Both the plain task and the engineered prompt are sent to the AI model at the same time.
4. The two responses stream back and display side by side for direct comparison.

## Tech Stack

- **Frontend:** HTML, CSS, and vanilla JavaScript (single self-contained file)
- **AI integration:** Claude (Anthropic) language model, called live from the page
- **Hosting:** published as a Claude Artifact web page

## Files

| File | Description |
|---|---|
| `prompt-lab.html` | Full source code of the application |
| `Prompt_Lab_Report.docx` | Project report (category, overview, features, tech stack) |
| `README.md` | This file |

## Author's Note

Responses are generated live per session and are not stored or logged anywhere by the app.
