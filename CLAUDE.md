# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a reveal.js presentation titled "From Prompts to Agents: Building with AI at Different Levels of Autonomy" by Synthetic Users. The presentation explores the evolution from prompt engineering to flow engineering to agentic AI.

## Architecture

- **presentation.html**: Main presentation file containing all slides inline as HTML sections within reveal.js structure
- **Agentic_AI_Slides.md**: Markdown source content for the slides (reference/draft format)
- **dist/**: Contains reveal.js framework files (CSS, JS, themes)
- **plugin/**: Reveal.js plugins for highlighting, markdown, math, notes, search, and zoom
- **logo_SU-removebg-preview.png**: Synthetic Users logo used in presentation
- **slides.pdf**: Exported PDF version of the presentation

## Presentation Structure

The presentation follows a logical flow through 14 slides:
1. Title slide with Synthetic Users branding
2. Introduction and agenda
3. Evolution spectrum (Prompt → Flow → Agent)
4-5. Prompt and Flow engineering recap
6-8. Agentic AI fundamentals and capabilities
9-11. Advantages, real-world applications, and future vision
12-13. Challenges and strategic guidance
14. Q&A and contact information

## Styling and Theming

The presentation uses a custom dark theme with:
- Primary color: #42affa (blue)
- Background: Dark gradient (#1c1e33 to #141525)
- Custom CSS for spectrum visualizations, branding, and typography
- Monokai syntax highlighting theme

## Development Commands

To view the presentation:
```bash
# Open presentation.html in a web browser
open presentation.html
```

To make content changes:
- Edit slides directly in presentation.html within `<section>` tags
- Use Agentic_AI_Slides.md as content reference
- Maintain reveal.js section structure for proper slide transitions

## Key Files for Editing

- **presentation.html**: Primary file for all slide content and styling
- **Agentic_AI_Slides.md**: Content source and reference material
- Custom CSS is embedded in presentation.html head section (lines 16-145)