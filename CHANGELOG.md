# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- `OFL.txt` — SIL Open Font License 1.1 with IBM Plex + Brex attribution (fork was redistributed without its license text).
- `.github/workflows/ci.yml` — font-validation CI: opens and fontbakery-checks any committed font binaries.
- `CLAUDE.md` — repository notes for contributors and AI agents.
- `.gitattributes` — binary handling for font/editor files, LF for text sources.
- `docs/assets/icon.png` — repository icon ("Plex, reimagined").

### Changed
- Rewrote the truncated `README.md` into a full overview: what Brex is, build steps (fontmake + fontbakery), license, credits.
- Extended `.gitignore` with font build-output and macOS patterns.

### Removed
- Stray tooling artifacts: `md.txt`, `REFACTOR_FILELIST.txt`, `llms.txt`.

### Earlier setup
- Initial project setup with repository structure
- IBM Plex Mono source UFO files (Regular, Bold, Italic, Bold Italic)
- Legacy FontLab VFJ/VFC files for BrexMono variants
- DeltaRig configuration file for font production
- Python-focused .gitignore configuration
- Updated .gitignore to exclude development directory from version control

## [0.0.1] - 2025-06-29

### Added
- Initial repository creation
- Basic README.md describing project as an IBM Plex fork