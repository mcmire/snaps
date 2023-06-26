# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0]
### Uncategorized
- 0.35.2-flask.1 ([#1542](https://github.com/mcmire/snaps/pull/1542))
- 0.35.1-flask.1 ([#1539](https://github.com/mcmire/snaps/pull/1539))
- 0.35.0-flask.1 ([#1537](https://github.com/mcmire/snaps/pull/1537))
- Add missing `prepare-manifest:preview` and `publish:preview` scripts ([#1528](https://github.com/mcmire/snaps/pull/1528))
- Implement Jest environment for Snaps end-to-end testing ([#1438](https://github.com/mcmire/snaps/pull/1438))
- Improve JSON parsing safety ([#1499](https://github.com/mcmire/snaps/pull/1499))
- 0.34.1-flask.1 ([#1472](https://github.com/mcmire/snaps/pull/1472))
- Revert "0.34.1-flask.1 (#1469)" ([#1469](https://github.com/mcmire/snaps/pull/1469))
- 0.34.1-flask.1 ([#1469](https://github.com/mcmire/snaps/pull/1469))
- Lint each package in a separate CI job ([#1463](https://github.com/mcmire/snaps/pull/1463))
- Run all Jest tests with SWC ([#1462](https://github.com/mcmire/snaps/pull/1462))
- 0.34.0-flask.1 ([#1460](https://github.com/mcmire/snaps/pull/1460))
- Bump `@metamask/utils` and `@metamask/snaps-registry` ([#1457](https://github.com/mcmire/snaps/pull/1457))

## [0.35.2-flask.1]
### Fixed
- Fix type issue introduced by [#1532](https://github.com/MetaMask/snaps/pull/1532) ([#1541](https://github.com/MetaMask/snaps/pull/1541))

## [0.35.1-flask.1]
### Changed
- No changes this release.

## [0.35.0-flask.1]
### Changed
- **BREAKING:** Build packages as both CJS and ESM ([#1519](https://github.com/MetaMask/snaps/pull/1519), ([#1532](https://github.com/MetaMask/snaps/pull/1532)))
  - This is breaking in the sense that imports to `dist/` will now require you to import either `dist/cjs` or `dist/esm`.
- Add `sideEffects: false` ([#1486](https://github.com/MetaMask/snaps/pull/1486))

## [0.34.1-flask.1]
### Changed
- No changes this release.

## [0.34.0-flask.1]
### Added
- Initial release ([#1268](https://github.com/MetaMask/snaps/pull/1268))

## [0.30.0]
### Changed
- No changes this release.

[Unreleased]: https://github.com/mcmire/snaps/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/mcmire/snaps/compare/v0.35.2-flask.1...v1.0.0
[0.35.2-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.1-flask.1...v0.35.2-flask.1
[0.35.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.0-flask.1...v0.35.1-flask.1
[0.35.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.1-flask.1...v0.35.0-flask.1
[0.34.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.0-flask.1...v0.34.1-flask.1
[0.34.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.30.0...v0.34.0-flask.1
[0.30.0]: https://github.com/mcmire/snaps/releases/tag/v0.30.0
