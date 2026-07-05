# Brex Font TODO List

## Modernization pass (2026-07)
- [x] Complete the truncated README (build steps, license, credits) per STYLE_GUIDE
- [x] Add OFL.txt (SIL OFL 1.1) with IBM Plex + Brex attribution
- [x] Add font-validation CI (.github/workflows/ci.yml)
- [x] Add CLAUDE.md repository notes
- [x] Add .gitattributes for proper file handling
- [x] Update .gitignore for font development patterns
- [x] Generate repository icon (docs/assets/icon.png)
- [x] Remove stray tooling artifacts (md.txt, REFACTOR_FILELIST.txt, llms.txt)

## Phase 1: Foundation
- [ ] Create proper directory structure (sources/, fonts/, documentation/, scripts/, tests/, specimens/)
- [ ] Move UFO files from dev/01-ufo/ to sources/
- [ ] Archive FontLab files to legacy/ directory
- [ ] Set up Python virtual environment
- [ ] Create requirements.txt with fontmake, fonttools, fontbakery
- [ ] Create Makefile with build targets for TTF, OTF, WOFF, WOFF2
- [ ] Write basic build script using fontmake
- [x] Update .gitignore for font development patterns
- [x] Create .gitattributes for proper file handling
- [ ] Test basic font generation from UFO sources

## Phase 2: Identity & Differentiation
- [ ] Analyze differences between IBM Plex Mono and existing BrexMono files
- [ ] Document design decisions and target use cases
- [ ] Create comparison specimens (Brex vs IBM Plex)
- [ ] Define character set and glyph coverage goals
- [ ] Plan programming ligatures and special symbols
- [ ] Update font metadata and naming in UFO files
- [ ] Establish version numbering scheme (start at 1.0.0)
- [ ] Create proper copyright and license attribution

## Phase 3: Quality & Testing
- [ ] Set up fontbakery configuration
- [ ] Create automated testing scripts
- [ ] Generate font proofs and specimens
- [ ] Test fonts on macOS, Windows, Linux
- [ ] Test in popular code editors (VS Code, IntelliJ, Sublime)
- [ ] Test in terminal emulators
- [ ] Validate web font performance
- [ ] Set up regression testing

## Phase 4: Documentation & Release
- [ ] Write comprehensive README.md
- [ ] Create installation guides for each platform
- [ ] Write CONTRIBUTING.md
- [ ] Document build process
- [ ] Set up GitHub Actions for CI/CD
- [ ] Configure automated releases
- [ ] Create release packages (zip, tar.gz)
- [ ] Set up npm package configuration
- [ ] Write initial release notes

## Phase 5: Launch & Distribution
- [ ] Create GitHub Release for v1.0.0
- [ ] Publish to npm registry
- [ ] Submit to Homebrew
- [ ] Create font specimen website
- [ ] Announce on relevant forums/communities
- [ ] Set up issue templates
- [ ] Create Code of Conduct
- [ ] Monitor initial user feedback

## Future Enhancements
- [ ] Add more weights (Light, Medium, Heavy)
- [ ] Create italic variants for all weights
- [ ] Implement programming ligatures
- [ ] Add Powerline symbols
- [ ] Expand language coverage
- [ ] Create variable font version
- [ ] Optimize for specific use cases (terminal, coding)
- [ ] Create display version for headings

## Maintenance Tasks
- [ ] Set up dependency update automation
- [ ] Create security policy
- [ ] Establish release schedule
- [ ] Set up analytics for usage tracking
- [ ] Create feedback collection system
- [ ] Regular fontbakery compliance checks
- [ ] Performance benchmarking
- [ ] Community engagement plan