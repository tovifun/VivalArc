# Repository Guidelines

## Project Structure & Module Organization
`vivalarc.css` is the default stylesheet for Vivaldi 7.7+. Variant builds live in `variants/` (`autotab/`, `compact/`), and legacy snapshots are preserved under `archive/v6.9`, `archive/v7.0`, and `archive/v7.4`. User-facing docs are in `docs/`, with English files mirrored by `-cn` Chinese versions. Visual assets live in `assets/`, packaged themes in `themes/`, and reference screenshots in `screenshots/`.

## Build, Test, and Development Commands
This repo has no build pipeline; contributors edit CSS and Markdown directly.

- `git clone https://github.com/tovifun/VivalArc.git`: get a local copy.
- `rg -n "selector|token" vivalarc.css variants docs`: find related rules before editing.
- `git diff -- vivalarc.css variants/ docs/`: review style and doc changes before opening a PR.

For local verification, point Vivaldi Settings > Appearance > Custom UI Modifications at the repo root or a folder such as `variants/compact/`, then restart Vivaldi.

## Coding Style & Naming Conventions
Use 4-space indentation in CSS to match the existing files. Keep custom properties in `--kebab-case`, group related rules under brief block comments, and prefer small targeted overrides over large selector rewrites. Markdown filenames should stay lowercase and hyphenated; Chinese counterparts should keep the `-cn.md` suffix.

## Testing Guidelines
There is no automated test suite. Validate changes manually in Vivaldi 7.7+ using the default stylesheet and any touched variant. When editing shared UI areas, check light and dark themes, left tab layouts, and at least one platform-specific branch (`.mac`, `.win`, or `.linux`). Update screenshots or docs when behavior or setup steps change.

## Commit & Pull Request Guidelines
Recent history favors short, direct commit subjects such as `fix readme.md`, `vivalarc 1.1.0`, or `vivalarc_autotab tabbar background color fallback`. Keep commits focused on one change area. PRs should describe the affected version or variant, link the issue when applicable, and include before/after screenshots for visible UI changes.

## Repository Hygiene
Do not remove or rewrite archived versions unless the change is intentionally for legacy support. Avoid committing editor cruft or local OS artifacts such as `.DS_Store`, and keep packaged assets and docs in sync with any renamed folders.
