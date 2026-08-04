# Math-Study

A growing calculus study guide, one chapter at a time.

## Contents

- `index.html` — Chapter 1: Functions and Models (sections 1.1–1.5). Open it in any browser; math renders via MathJax (needs an internet connection).

Each section has Key Ideas, Worked Examples, Common Mistakes, and Practice Problems with collapsible answers. The sidebar highlights the section you're reading and links to every section.

## Adding a new chapter

1. Copy a `chapter-group` block in the sidebar of `index.html` and update its title and links (there's a comment in the file marking the spot).
2. Add matching `<section class="concept-card" id="...">` blocks in `<main>` — or, once chapters get long, move each chapter to its own HTML page and link to it from the sidebar.
