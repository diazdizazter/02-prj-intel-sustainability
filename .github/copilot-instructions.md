Students are beginners learning the basics of HTML and CSS.

We provide the simplest, beginner-friendly code possible.

We do not use advanced CSS layout methods like grid, unless asked.

We provide comments to help students understand each part of the generated code.

## Project overview
- This is a single-page site built with plain HTML and CSS.
- Key files: index.html for structure, style.css for all styling, img/ for assets (e.g., intel-header-logo.svg).
- The page is a timeline of Intel sustainability milestones with a hero header, then a list of card blocks.

## Layout and content patterns
- Keep the HTML structure simple and semantic: a header section, then one section containing repeated card divs.
- The timeline cards are plain divs with h2, h3, and p; avoid extra wrappers unless needed for clarity.
- Preserve the existing instructional HTML comments that guide students.
- Use basic CSS layout tools (flexbox, margins, padding); avoid CSS grid unless the user asks for it.
- Add short, beginner-friendly comments in CSS and HTML for any non-obvious styling.

## Workflow notes
- There is no build, test, or tooling step; open index.html directly to view changes.
- Keep changes self-contained in index.html and style.css.
