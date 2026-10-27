# Notion Markdown & LaTeX Normalizer

A single-file (`index.html`), zero-backend web application designed for hosting on **GitHub Pages** (or running locally in any browser) to convert AI-generated study notes and Markdown into cleanly formatted Notion blocks via a simple **Ctrl+C → Ctrl+V** workflow.

## Folder Structure
- `index.html` — The complete, self-contained web application (HTML + CSS + Vanilla JS). Only this file is needed to run the app.
- `sample-ind-as-110.md` — Your original raw sample Markdown file (Ind AS 110 Consolidation Procedures) for testing.
- `notion-ready-sample.md` — The pre-converted Notion-ready Markdown output generated from your sample file.
- `README.md` — Quick-start instructions for local use and GitHub Pages deployment.

## What It Fixes Automatically
1. **LaTeX Delimiter Normalization:** Converts escaped block math (`\\[ ... \\]`) into `$$ ... $$` and escaped inline math (`\\( ... \\)`) into `$ ... $`, including equations inside `>` blockquotes.
2. **KaTeX `\text{...}` Ampersand Escaping:** Automatically escapes raw `&` inside `\text{Consolidated P&L ...}` to `\&` so Notion's equation parser never throws a syntax error.
3. **Table Cell Symbol Cleanup:** Replaces inline LaTeX arrows (`\(\rightarrow\)`) with `→` and spacing (`\(\quad\)`) with Unicode em-spaces (` `) inside Markdown tables.
4. **Multi-Line Table Cells (`<br>`):** Converts `<br>` tags inside Markdown table cells into Unicode Line Separators (`\u2028`) so multi-line journal entries paste into a single Notion table cell with clean line breaks.
5. **Optional ASCII Box → Mermaid Flowchart:** Keeps ASCII diagrams as clean `text` code blocks by default, with a toggle in the top bar to convert box-drawing flowcharts into Mermaid `flowchart TD` diagrams.
