# Change Log

All notable changes to the "Its Dark" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Restored the authentic v9.0.0 palette as the design identity: `#141518` canvas, teal `#80cbc4` and cyan `#00ffff` accents, `#ffff7e` activity bar, `#c692fa` breadcrumb, and the original syntax spectrum
- Rebuilt Its Light from the same v9 accent, semantic, and syntax roles with contrast-targeted light variants
- Restored the v9 `editorWarning` colors and added the three list-filter-widget colors to both themes for exact key parity (271 keys each)

### Changed
- Replaced unregistered color IDs (`button.separatorForeground`, `debugToolBar.iconForeground`, `debugToolBar.interactiveElementForeground`, `searchEditor.focusBackground`, `notificationCenter.background`) with a valid key or removed them
- Restored distinct ANSI blue (`#82aaff`) and cyan (`#89ddff`); made black and white terminal entries visible in both themes
- Made the activity-bar active indicator visible; strengthened focus borders and active tab borders
- Improved contrast of comments, line numbers, warning text, and bright ANSI variants
- Aligned the manifest and README description with the v9-token-based identity
- Regenerated all preview images from the restored palette and added Its Light screenshots
- Rewrote the README around positioning, measured contrast, both previews, and a FAQ

## [10.0.1] - 2026-11-19

### Changed
- Version bump following the 10.0.0 marketplace publish

## [10.0.0] - 2026-11-19

### Added
- Its Light theme
- Expanded color coverage and four additional syntax token rules

### Changed
- Unified slate-and-navy palette with accessibility and readability refinements
- Refreshed marketplace assets and documentation

## [9.0.1] - 2026-11-19

### Changed
- Published the expanded dark theme and Its Light under the 9.0.1 version number

## [9.0.0] - 2026-11-19

### Changed
- Major theme overhaul: professional dark palette and refined syntax colors
- Updated extension metadata and marketplace assets

## [8.0.1] - 2026-11-19

### Changed
- Minor color refinements and sample image updates

## [8.0.0] - 2026-11-19

### Added
- Initial public release of Its Dark theme

[Unreleased]: https://github.com/iamismile/its-dark/compare/v10.0.1...HEAD
[10.0.1]: https://github.com/iamismile/its-dark/compare/v10.0.0...v10.0.1
[10.0.0]: https://github.com/iamismile/its-dark/compare/v9.0.1...v10.0.0
[9.0.1]: https://github.com/iamismile/its-dark/compare/v9.0.0...v9.0.1
[9.0.0]: https://github.com/iamismile/its-dark/compare/v8.0.1...v9.0.0
[8.0.1]: https://github.com/iamismile/its-dark/compare/v8.0.0...v8.0.1
[8.0.0]: https://github.com/iamismile/its-dark/releases/tag/v8.0.0
