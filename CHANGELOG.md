# Changelog

All **notable changes** to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
Each log entry can be in the following kind: **Added**[^1], **Changed**[^2], **Deprecated**[^3], **Removed**[^4], **Fixed**[^5] and **Security**[^6]

## [Unreleased]

## [0.4.0] - 2021-12-16

### Added

- Publish to npm using GitHub Actions

### Changed

- Package name to `estileira`

### Fixed

- Only prepare husky on non-ci environment

### Security

- fix vulnerabilities

## [0.3.0] - 2021-12-14

### Added

- pre-commit hook lint code
- exports utilities tools as separate sub-path

## [0.2.0] - 2021-12-14

### Added

- vertical rhythm utility
- color utility
- setup typography with vertical rhythm
- Linter ([stylelint](https://stylelint.io/))
- npm scripts:
  - `format` - fix code styles with prettier
  - `format:check` - print code styles warns to stdout without fixing them
  - `lint` - run stylelint

[unreleased]: https://github.com/pherval/scss-framework/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/pherval/scss-framework/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/pherval/scss-framework/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/pherval/scss-framework/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/pherval/scss-framework/releases/tag/v0.1.0

[^1]: `Added` for new features.
[^2]: `Changed` for changes in existing functionality.
[^3]: `Deprecated` for soon-to-be removed features.
[^4]: `Removed` for now removed features.
[^5]: `Fixed` for any bug fixes.
[^6]: `Security` in case of vulnerabilities.
