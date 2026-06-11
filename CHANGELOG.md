# Changelog

All notable changes to this project are documented here.
The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.0.2] - 2026-06-12

### Fixed
- Removed all `!important` declarations; bold, italic, and the editor cursor are
  now styled via selector specificity and the `--caret-color` variable.
- Replaced the `text-decoration-color` underline on backlinks with a
  `border-bottom`, clearing the "partially supported" CSS lint warning.

### Changed
- Renamed `PaperSourceDark.png` to `screenshot.png` so the theme screenshot
  resolves during submission, and updated the README reference.

## [1.0.1] - 2026-06-12

### Added
- MIT license file.
- Expanded README with a color palette table, full feature list, and detailed
  installation instructions.

### Changed
- Aligned the `manifest.json` author name with the README and license, and set
  `authorUrl`.

## [1.0.0] - 2026-06-11

### Added
- Initial release.
