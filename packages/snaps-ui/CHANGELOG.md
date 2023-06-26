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
- Improve JSON parsing safety ([#1499](https://github.com/mcmire/snaps/pull/1499))
- 0.34.1-flask.1 ([#1472](https://github.com/mcmire/snaps/pull/1472))
- Revert "0.34.1-flask.1 (#1469)" ([#1469](https://github.com/mcmire/snaps/pull/1469))
- 0.34.1-flask.1 ([#1469](https://github.com/mcmire/snaps/pull/1469))
- Lint each package in a separate CI job ([#1463](https://github.com/mcmire/snaps/pull/1463))
- Run all Jest tests with SWC ([#1462](https://github.com/mcmire/snaps/pull/1462))
- 0.34.0-flask.1 ([#1460](https://github.com/mcmire/snaps/pull/1460))
- Bump `@metamask/utils` and `@metamask/snaps-registry` ([#1457](https://github.com/mcmire/snaps/pull/1457))
- 0.33.1-flask.1 ([#1396](https://github.com/mcmire/snaps/pull/1396))
- 0.33.0-flask.1 ([#1382](https://github.com/mcmire/snaps/pull/1382))
- Revert "0.33.0-flask.1 (#1376)" ([#1376](https://github.com/mcmire/snaps/pull/1376))
- 0.33.0-flask.1 ([#1376](https://github.com/mcmire/snaps/pull/1376))
- devDeps: @lavamoat/allow-scripts@2.0.3->2.3.1 ([#1372](https://github.com/mcmire/snaps/pull/1372))
- Synchronize package versions across the workspace ([#1326](https://github.com/mcmire/snaps/pull/1326))
- Bump `MetaMask/action-npm-publish` to `v3` and update dependencies to use `workspace:^` ([#1325](https://github.com/mcmire/snaps/pull/1325))
- 0.32.2 ([#1318](https://github.com/mcmire/snaps/pull/1318))
- 0.32.1 ([#1315](https://github.com/mcmire/snaps/pull/1315))
- 0.32.0 ([#1312](https://github.com/mcmire/snaps/pull/1312))
- 0.31.0 ([#1279](https://github.com/mcmire/snaps/pull/1279))
- Bump `@metamask/utils` to `5.0.0` and handle breaking changes ([#1276](https://github.com/mcmire/snaps/pull/1276))
- Update workflows to match `MetaMask/core` repository ([#1254](https://github.com/mcmire/snaps/pull/1254))
- 0.30.0 ([#1224](https://github.com/mcmire/snaps/pull/1224))
- 0.29.0 ([#1187](https://github.com/mcmire/snaps/pull/1187))
- 0.28.0 ([#1138](https://github.com/mcmire/snaps/pull/1138))
- BREAKING: Add support for snap registries ([#1090](https://github.com/mcmire/snaps/pull/1090))
- Use `@metamask/utils@3.4.0` ([#1102](https://github.com/mcmire/snaps/pull/1102))
- 0.27.1 ([#1084](https://github.com/mcmire/snaps/pull/1084))
- 0.27.0 ([#1079](https://github.com/mcmire/snaps/pull/1079))
- BREAKING: Use custom UI in transaction insights ([#1047](https://github.com/mcmire/snaps/pull/1047))
- 0.26.2 ([#1065](https://github.com/mcmire/snaps/pull/1065))
- 0.26.1 ([#1057](https://github.com/mcmire/snaps/pull/1057))
- 0.26.0 ([#1048](https://github.com/mcmire/snaps/pull/1048))
- 0.25.0 ([#1011](https://github.com/mcmire/snaps/pull/1011))
- Bump @metamask/auto-changelog from 2.6.0 to 3.1.0 ([#1001](https://github.com/mcmire/snaps/pull/1001))

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
### Changed
- No changes this release.

## [0.33.1-flask.1]
### Changed
- No changes this release.

## [0.33.0-flask.1]
### Changed
- No changes this release.

## [0.32.2]
### Changed
- No changes this release.

## [0.32.1]
### Changed
- No changes this release.

## [0.32.0]
### Changed
- No changes this release.

## [0.31.0]
### Changed
- **BREAKING:** Target `ES2020` ([#1247](https://github.com/MetaMask/snaps-monorepo/pull/1247))

## [0.30.0]
### Changed
- No changes this release.

## [0.29.0]
### Changed
- No changes this release.

## [0.28.0]
### Changed
- No changes this release.

## [0.27.1]
### Changed
- No changes this release.

## [0.27.0]
### Changed
- No changes this release.

## [0.26.2]
### Changed
- No changes this release.

## [0.26.1]
### Changed
- No changes this release.

## [0.26.0]
### Removed
- **BREAKING:** Remove spacer component ([#1031](https://github.com/MetaMask/snaps-monorepo/pull/1031))

## [0.25.0]
### Added
- Initial release ([#978](https://github.com/MetaMask/snaps-monorepo/pull/978), [#1009](https://github.com/MetaMask/snaps-monorepo/pull/1009))

[Unreleased]: https://github.com/mcmire/snaps/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/mcmire/snaps/compare/v0.35.2-flask.1...v1.0.0
[0.35.2-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.1-flask.1...v0.35.2-flask.1
[0.35.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.0-flask.1...v0.35.1-flask.1
[0.35.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.1-flask.1...v0.35.0-flask.1
[0.34.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.0-flask.1...v0.34.1-flask.1
[0.34.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.33.1-flask.1...v0.34.0-flask.1
[0.33.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.33.0-flask.1...v0.33.1-flask.1
[0.33.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.32.2...v0.33.0-flask.1
[0.32.2]: https://github.com/mcmire/snaps/compare/v0.32.1...v0.32.2
[0.32.1]: https://github.com/mcmire/snaps/compare/v0.32.0...v0.32.1
[0.32.0]: https://github.com/mcmire/snaps/compare/v0.31.0...v0.32.0
[0.31.0]: https://github.com/mcmire/snaps/compare/v0.30.0...v0.31.0
[0.30.0]: https://github.com/mcmire/snaps/compare/v0.29.0...v0.30.0
[0.29.0]: https://github.com/mcmire/snaps/compare/v0.28.0...v0.29.0
[0.28.0]: https://github.com/mcmire/snaps/compare/v0.27.1...v0.28.0
[0.27.1]: https://github.com/mcmire/snaps/compare/v0.27.0...v0.27.1
[0.27.0]: https://github.com/mcmire/snaps/compare/v0.26.2...v0.27.0
[0.26.2]: https://github.com/mcmire/snaps/compare/v0.26.1...v0.26.2
[0.26.1]: https://github.com/mcmire/snaps/compare/v0.26.0...v0.26.1
[0.26.0]: https://github.com/mcmire/snaps/compare/v0.25.0...v0.26.0
[0.25.0]: https://github.com/mcmire/snaps/releases/tag/v0.25.0
