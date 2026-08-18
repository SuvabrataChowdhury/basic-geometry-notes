# Basic Geometry

A structured reference book on fundamental geometry, covering theorems, proofs, and key concepts from angles and lines through triangles, polygons, and circles.

## Topics Covered

- **Measurement of Angles** — angle definitions, degrees, and radians
- **Lines and Angles** — line theorems including vertical, corresponding, alternate, and consecutive angle relationships
- **Triangles** — core theorems such as the Pythagorean theorem, triangle inequality, and Thales' theorem
- **Triangle Congruence and Similarity** — SSS, SAS, ASA, AAS, HL, and AA conditions
- **Polygons and Quadrilaterals** — interior/exterior angle sums and parallelogram theorems
- **Circles** — inscribed angles, tangents, chords, and cyclic quadrilateral theorems

## Built With

This book is built using [mdBook](https://rust-lang.github.io/mdBook/), a Rust-based tool for creating online books from Markdown files. Math expressions are written in LaTeX and rendered in the browser.

## Local Development

```bash
# Install mdBook (requires Rust)
cargo install mdbook

# Preview the book with live reload
mdbook serve

# Build the static site
mdbook build
```

The generated site is output to the `book/` directory. Changes to files in `src/` are picked up automatically when serving.

## Contributing

Content lives in `src/`. To add or reorganize chapters, update `src/SUMMARY.md` — mdBook uses that file to determine the structure and navigation of the book.

## Deployment

Pushing to the `main` branch triggers an automated GitHub Actions workflow that builds and deploys the book to GitHub Pages.

## Author

[Suvabrata Chowdhury](https://github.com/SuvabrataChowdhury)
