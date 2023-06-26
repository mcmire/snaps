# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0]
### Uncategorized
- 1.0.0 ([#5](https://github.com/mcmire/snaps/pull/5))

## [1.0.0]
### Uncategorized
- 0.35.2-flask.1 ([#1542](https://github.com/mcmire/snaps/pull/1542))
- 0.35.1-flask.1 ([#1539](https://github.com/mcmire/snaps/pull/1539))
- 0.35.0-flask.1 ([#1537](https://github.com/mcmire/snaps/pull/1537))
- Move `test-snaps` to this repository ([#1488](https://github.com/mcmire/snaps/pull/1488))
- Implement Jest environment for Snaps end-to-end testing ([#1438](https://github.com/mcmire/snaps/pull/1438))
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
- Remove JSDOM from all packages ([#1241](https://github.com/mcmire/snaps/pull/1241))
- Implement tests using `webdriverio` ([#1231](https://github.com/mcmire/snaps/pull/1231))
- 0.30.0 ([#1224](https://github.com/mcmire/snaps/pull/1224))
- 0.29.0 ([#1187](https://github.com/mcmire/snaps/pull/1187))
- 0.28.0 ([#1138](https://github.com/mcmire/snaps/pull/1138))
- 0.27.1 ([#1084](https://github.com/mcmire/snaps/pull/1084))
- 0.27.0 ([#1079](https://github.com/mcmire/snaps/pull/1079))
- 0.26.2 ([#1065](https://github.com/mcmire/snaps/pull/1065))
- 0.26.1 ([#1057](https://github.com/mcmire/snaps/pull/1057))
- Add AVA test runner integration ([#1022](https://github.com/mcmire/snaps/pull/1022))
- 0.26.0 ([#1048](https://github.com/mcmire/snaps/pull/1048))
- 0.25.0 ([#1011](https://github.com/mcmire/snaps/pull/1011))
- Bump @metamask/auto-changelog from 2.6.0 to 3.1.0 ([#1001](https://github.com/mcmire/snaps/pull/1001))
- Fix ESLint dependencies ([#1000](https://github.com/mcmire/snaps/pull/1000))
- Bump ESLint configs to latest version ([#963](https://github.com/mcmire/snaps/pull/963))
- 0.24.1 ([#975](https://github.com/mcmire/snaps/pull/975))
- 0.24.0 ([#968](https://github.com/mcmire/snaps/pull/968))
- BREAKING: Rename packages to start with `snaps-` ([#937](https://github.com/mcmire/snaps/pull/937))
- Speed up CI by running jobs in parallel ([#917](https://github.com/mcmire/snaps/pull/917))

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

### Fixed
- Fix a few smaller issues when using the Webpack plugin with in-memory files ([#1225](https://github.com/MetaMask/snaps-monorepo/pull/1225))

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
### Changed
- No changes this release.

## [0.25.0]
### Changed
- No changes this release.

## [0.24.1]
### Changed
- No changes this release.

## [0.24.0]
### Added
- Add compile-time warning when using `Math.random` ([#950](https://github.com/MetaMask/snaps-monorepo/pull/950))

## [0.23.0]
### Fixed
- Fix Webpack plugin issue with existing files ([#858](https://github.com/MetaMask/snaps-monorepo/pull/858))

## [0.22.3]
### Changed
- No changes this release.

## [0.22.2]
### Changed
- No changes this release.

## [0.22.1]
### Changed
- No changes this release.

## [0.22.0]
### Changed
- No changes this release.

## [0.21.0]
### Added
- Run eval and fix manifest in bundler plugins ([#731](https://github.com/MetaMask/snaps-monorepo/pull/731))

## [0.20.0]
### Changed
- No changes this release.

## [0.19.1]
### Added
- Generate source maps from modified code ([#615](https://github.com/MetaMask/snaps-monorepo/pull/615))

## [0.19.0]
### Changed
- No changes this release.

## [0.18.1]
### Changed
- No changes this release.

## [0.18.0]
### Changed
- Reduce TypeScript compilation target to ES2017 ([#628](https://github.com/MetaMask/snaps-monorepo/pull/628))

## [0.17.0]
### Changed
- **BREAKING:** Bump minimum Node version to 16 ([#601](https://github.com/MetaMask/snaps-monorepo/pull/601))

## [0.16.0]
### Changed
- No changes this release.

## [0.15.0]
### Fixed
- Fix some typing issues ([#462](https://github.com/MetaMask/snaps-monorepo/pull/462))

## [0.14.0]
### Fixed
- Actually publish package contents ([#449](https://github.com/MetaMask/snaps-monorepo/pull/449))
  - Package contents were omitted from the previous version due to a build failure.

## [0.13.0]
### Changed
- No changes this release.

## [0.12.0]
### Added
- Initial release ([#420](https://github.com/MetaMask/snaps-monorepo/pull/420))

[Unreleased]: https://github.com/mcmire/snaps/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/mcmire/snaps/compare/v1.0.0...v2.0.0
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
[0.25.0]: https://github.com/mcmire/snaps/compare/v0.24.1...v0.25.0
[0.24.1]: https://github.com/mcmire/snaps/compare/v0.24.0...v0.24.1
[0.24.0]: https://github.com/mcmire/snaps/compare/v0.23.0...v0.24.0
[0.23.0]: https://github.com/mcmire/snaps/compare/v0.22.3...v0.23.0
[0.22.3]: https://github.com/mcmire/snaps/compare/v0.22.2...v0.22.3
[0.22.2]: https://github.com/mcmire/snaps/compare/v0.22.1...v0.22.2
[0.22.1]: https://github.com/mcmire/snaps/compare/v0.22.0...v0.22.1
[0.22.0]: https://github.com/mcmire/snaps/compare/v0.21.0...v0.22.0
[0.21.0]: https://github.com/mcmire/snaps/compare/v0.20.0...v0.21.0
[0.20.0]: https://github.com/mcmire/snaps/compare/v0.19.1...v0.20.0
[0.19.1]: https://github.com/mcmire/snaps/compare/v0.19.0...v0.19.1
[0.19.0]: https://github.com/mcmire/snaps/compare/v0.18.1...v0.19.0
[0.18.1]: https://github.com/mcmire/snaps/compare/v0.18.0...v0.18.1
[0.18.0]: https://github.com/mcmire/snaps/compare/v0.17.0...v0.18.0
[0.17.0]: https://github.com/mcmire/snaps/compare/v0.16.0...v0.17.0
[0.16.0]: https://github.com/mcmire/snaps/compare/v0.15.0...v0.16.0
[0.15.0]: https://github.com/mcmire/snaps/compare/v0.14.0...v0.15.0
[0.14.0]: https://github.com/mcmire/snaps/compare/v0.13.0...v0.14.0
[0.13.0]: https://github.com/mcmire/snaps/compare/v0.12.0...v0.13.0
[0.12.0]: https://github.com/mcmire/snaps/releases/tag/v0.12.0
