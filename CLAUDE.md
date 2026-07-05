# CLAUDE.md — Brex font repository

Notes for AI agents and contributors working on this repo.

## What this repo is

Brex is a monospace typeface forked from IBM Plex Mono. This is a **font-source
repository**, not a software package. The fonts are the product. Do not make
design changes (glyph edits, metrics, spacing) unless explicitly asked — those
are the designer's calls.

## Layout

- `README.md` — project overview, build steps, license.
- `OFL.txt` — SIL Open Font License 1.1, inherited from IBM Plex Mono. Ship it
  with any redistributed binary.
- `dev/` — **untracked** working directory (in `.gitignore`):
  - `dev/01-ufo/` — UFO masters (Regular, Bold, Italic, Bold Italic), the
    buildable sources.
  - `dev/00-old/` — legacy FontLab VFJ/VFC studies and `DeltaRig-BrexMono.json`,
    kept for reference (binary, heavy — deliberately out of git).
- `docs/assets/icon.png` — repository icon.
- `.github/workflows/ci.yml` — validates any committed font binaries with
  fontTools + fontbakery; a source-only checkout has nothing to validate and
  passes with a notice.
- `PLAN.md` / `TODO.md` / `CHANGELOG.md` — roadmap, task list, history.

## Build

Binaries are built from the UFO masters with `fontmake` and validated with
`fontbakery` (see README). Compiled fonts ship on GitHub Releases, not in git.

## Conventions

- Keep binaries and heavyweight editor files out of git history — release
  artifacts carry the finished fonts.
- Preserve OFL attribution to IBM Corp. in any metadata or license edits.
