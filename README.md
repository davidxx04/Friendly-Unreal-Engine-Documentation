## Friendly Unreal Engine Documentation

A curated Obsidian-style vault of bite-sized Unreal Engine notes, how-tos and reference material — written as plain Markdown so you can open, edit and publish it anywhere.

This repository is a personal knowledge base organized around practical UE5 topics: blueprints, C++, world-building, inputs, version control and more. It’s optimized for human readers (and Obsidian lovers), not a packaged binary or plugin.

---

## How this is distributed

- Files are plain Markdown (`.md`) and live in folders. You’ll find high-level notes and step-by-step how-tos under folders like:
  - `General notes/`
  - `How to dos/`
  - `logic programming/` (contains `blueprints/` and `c++/` subfolders)
  - `World/` (levels, Actors, Components, UObjects)
  - `not important (images)/` (images copied from screenshots)
  - `Version control/` (git notes)

- Images are stored in the `not important (images)/` folder as PNGs. Everything you need to read and reuse the content is included — no compiled assets, no engine project files.

This means the content is frictionless to clone, edit, and publish. It’s intentionally lightweight: Markdown + images = maximum portability.

---

## Quick start

Clone the repo and open it in your editor or Obsidian:

```powershell
git clone <your-repo-url>
cd 'Friendly Unreal Engine Documentation'
# Open in VS Code
code .
# Or open the folder with Obsidian
```

Open any `*.md` file (for example `How to dos/Give inputs to your game.md`) to begin reading or editing.

---

## How to use / publish

Pick whichever workflow fits you:

- Obsidian
  - Drop the folder into your Obsidian vaults and enjoy link graphing, backlinks and the Obsidian editor.

- GitHub (docs website)
  - Convert to a docs site quickly with MkDocs or Docusaurus. Example with MkDocs:

  ```powershell
  pip install mkdocs mkdocs-material
  mkdocs new . --no-input
  # Edit mkdocs.yml to include the folders you want to publish
  mkdocs serve  # preview locally
  mkdocs build   # build site/html
  ```

- GitHub Pages
  - Build the site with MkDocs (or GitHub Actions) and publish to GitHub Pages for a public documentation site.

---

## Contribution guidelines (simple)

- Edit Markdown directly. Keep paragraphs short and add headings.
- Images: add PNGs into `not important (images)/` and reference them relatively.
- Create a branch, make changes, open a pull request. Use clear commit messages.

If you want to reorganize topics, prefer small, atomic PRs (move one folder or file at a time) so history stays clear.

---

## Recommended .gitignore

You may want to ignore editor and OS cruft. Example entries:

```
# OS
.DS_Store
Thumbs.db

# Editor
.vscode/
*.code-workspace

# Obsidian local cache (if any)
.trash/
```

---

## License & reuse

These are Markdown notes intended for learning and sharing. If you'd like a license for public distribution, consider adding one (for docs, Creative Commons Attribution-ShareAlike is often a good fit; for code, MIT or Apache is common). If you want, I can add a LICENSE file — tell me which license you prefer.

---

## Notes & tips (pro-tips)

- Keep file names short and use kebab-case or spaces consistently — this vault currently mixes both; normalizing helps cross-platform linking.
- Use relative links in Markdown so notes keep working when moved or published.
- When publishing, trim `not important (images)/` or reorganize screenshots into topic-specific subfolders.

---

## TL;DR — Why this repo exists

Because learning Unreal Engine is messy. This repo keeps small, practical notes and recipes in plain Markdown so they’re easy to read, share, and evolve. It’s your portable UE brain.

If you want, I can: add a license, scaffold an `mkdocs.yml` and GitHub Actions workflow to publish it, or standardize filenames. Tell me which and I’ll do it.
