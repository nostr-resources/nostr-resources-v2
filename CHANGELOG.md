# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2026-03-18

### Added

- Full English content ported from v1 (all 27 sections)
- Full German translation (AI-assisted first draft, needs review)
- Base template with dark theme matching current site
- Sticky header with nav links and language switcher (EN/DE)
- Footer with CC license, sister projects, social icons (inline SVG)
- Prose styling for markdown content (headings, links, lists, blockquotes, code, footnotes)
- Action button styles
- OG/Twitter meta tags and Fathom analytics
- `nip05providers` shortcode replacing Jekyll for-loops
- Data files: projects.json, nip05providers.yaml
- Static assets: avatar, cover image, favicons

### Changed

- Font Awesome icons replaced with emoji
- GitHub links updated to point to v2 repo
- `nostr:` mention links in podcast section simplified

## [0.1.0] - 2026-03-18

### Added

- Hugo site scaffold with `hugo.yaml` configuration
- i18n support with English and German language configs
- Content directories per language (`content/en/`, `content/de/`)
- UI translation strings (`i18n/en.yaml`, `i18n/de.yaml`)
- Tailwind CSS via standalone CLI (no Node.js dependency)
- Makefile for local development (`make build`, `make serve`)
- GitHub Actions workflow for automated build and deploy to GitHub Pages
- README with setup and translation instructions
- MIT license

### Fixed

- Asset paths use `relURL` for correct loading on GitHub Pages subpaths
- `contentDir` set per language for proper content routing
