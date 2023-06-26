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
- Delete Multichain/Keyring code ([#1527](https://github.com/mcmire/snaps/pull/1527))
- Fix BIP-32 path validation ([#1506](https://github.com/mcmire/snaps/pull/1506))
- Improve JSON parsing safety ([#1499](https://github.com/mcmire/snaps/pull/1499))
- 0.34.1-flask.1 ([#1472](https://github.com/mcmire/snaps/pull/1472))
- Build simulator vendor before main build ([#1471](https://github.com/mcmire/snaps/pull/1471))
- Revert "0.34.1-flask.1 (#1469)" ([#1469](https://github.com/mcmire/snaps/pull/1469))
- 0.34.1-flask.1 ([#1469](https://github.com/mcmire/snaps/pull/1469))
- Lint each package in a separate CI job ([#1463](https://github.com/mcmire/snaps/pull/1463))
- Run tests in CI for `snaps-simulator` ([#1454](https://github.com/mcmire/snaps/pull/1454))
- Run all Jest tests with SWC ([#1462](https://github.com/mcmire/snaps/pull/1462))
- Build vendor files separate from own files in Webpack ([#1459](https://github.com/mcmire/snaps/pull/1459))
- 0.34.0-flask.1 ([#1460](https://github.com/mcmire/snaps/pull/1460))
- Bump `@metamask/utils` and `@metamask/snaps-registry` ([#1457](https://github.com/mcmire/snaps/pull/1457))
- Update core monorepo libs ([#1450](https://github.com/mcmire/snaps/pull/1450))
- Fix linting of snaps-simulator ([#1442](https://github.com/mcmire/snaps/pull/1442))
- Export permissions specification builders ([#1432](https://github.com/mcmire/snaps/pull/1432))

## [0.35.2-flask.1]
### Fixed
- Fix type issue introduced by [#1532](https://github.com/MetaMask/snaps/pull/1532) ([#1541](https://github.com/MetaMask/snaps/pull/1541))

## [0.35.1-flask.1]
### Fixed
- Fix publishing to NPM ([#1538](https://github.com/MetaMask/snaps/pull/1538))

## [0.35.0-flask.1]
### Added
- Add dark mode ([#1453](https://github.com/MetaMask/snaps/pull/1453))

### Changed
- **BREAKING:** Build packages as both CJS and ESM ([#1519](https://github.com/MetaMask/snaps/pull/1519), ([#1532](https://github.com/MetaMask/snaps/pull/1532)))
  - This is breaking in the sense that imports to `dist/` will now require you to import either `dist/cjs` or `dist/esm`.
- Add `sideEffects: false` ([#1486](https://github.com/MetaMask/snaps/pull/1486))
- Add support for E2E testing mode, to be used by `@metamask/snaps-jest` ([#1438](https://github.com/MetaMask/snaps/pull/1438), [#1488](https://github.com/MetaMask/snaps/pull/1488))

### Fixed
- Fix response typing in `snaps-simulator` ([#1498](https://github.com/MetaMask/snaps/pull/1498))
- Fix `snap_manageState` in `snaps-simulator` ([#1494](https://github.com/MetaMask/snaps/pull/1494))

## [0.34.1-flask.1]
### Changed
- No changes this release.

## [0.34.0-flask.1]
### Added
- Migrate `snaps-simulator` to `snaps-monorepo` ([#1408](https://github.com/MetaMask/snaps/pull/1408), [#1418](https://github.com/MetaMask/snaps/pull/1418))

[Unreleased]: https://github.com/mcmire/snaps/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/mcmire/snaps/compare/v0.35.2-flask.1...v1.0.0
[0.35.2-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.1-flask.1...v0.35.2-flask.1
[0.35.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.35.0-flask.1...v0.35.1-flask.1
[0.35.0-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.1-flask.1...v0.35.0-flask.1
[0.34.1-flask.1]: https://github.com/mcmire/snaps/compare/v0.34.0-flask.1...v0.34.1-flask.1
[0.34.0-flask.1]: https://github.com/mcmire/snaps/releases/tag/v0.34.0-flask.1
