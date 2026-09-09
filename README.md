# Origamify: Origami Studio

A browser-based crease-pattern editor that brings a paper-folding interest into an interactive programming project.

## What to look at

The implementation lives in [index.html](index.html): a drawing workspace, crease tools, properties and validation feedback. The single-file structure makes the interaction logic and rendering easy to inspect without a framework build.

## Run locally

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://localhost:8000 in a browser. There is no package-install step. The page references a web-hosted font, so a fully offline experience may use fallback typography.

## Scope

This is an editor prototype, not a guarantee that an arbitrary crease pattern can be physically folded. Treat the displayed checks as implementation-specific feedback, and verify geometry and foldability independently before relying on them.

The project demonstrates browser interaction, geometric representation and the translation of a hands-on craft into software. It does not claim to generate any requested three-dimensional object from a picture.
