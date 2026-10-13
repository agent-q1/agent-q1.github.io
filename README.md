# Suhas Shankar's site

The root is the blog homepage. The previous portfolio is preserved at
`/archived/`. Interactive articles live under `/posts/`.

`/posts/accuracy-robustness/` is a marimo WebAssembly export of
`blog/investigate_relationship_between_accuracy_and_robustness.py` in the
`aimo-interp-investigate-black-box` checkout. Its `public/` CSV files are
part of the export so the article can run in the browser on GitHub Pages.

Preview the site locally with `uv run python -m http.server --directory .`.
