# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0]
### Uncategorized
- Update package 'publish' scripts
- monorepo: Update publishConfig to public
- rpc-methods: Fix controllers type import
- rpc-methods: Update invokePlugin per updated PluginController.add interface
- rpc-methods: Update manageAssets to support 'getAll' asset method
- rpc-methods: Use virtual rpc engine to access requestor domain in some methods; various tweaks
- rpc-methods: Add snap_manageAssets restricted method
- rpc-methods: Convert state methods to restricted
- rpc-methods: Refactor internal permitted method exports
- rpc-methods: Add getBip44Entropy, refactor internal restricted method exports
- rpc-methods: Add selectHooks utility function
- rpc-methods: Add hookNames property to handlers
- rpc-methods: Update types, export names
- monorepo: Add licenses, update npm registry
- monorepo: Fix packages publishConfig
- monorepo: Run lint without --fix in prepare scripts
- controllers, rpc-methods: Add various RPC methods and hooks
- rpc-methods: Add invokePlugin permission and methods
- rpc-methods: Allow multiple method names for restricted methods
- rpc-methods: Add restricted confirm method, update exports
- monorepo: Add @mm-snap/rpc-methods package

## [1.0.0]
### Uncategorized
- 0.35.2-flask.1 ([#1542](https://github.com/mcmire/snaps/pull/1542))
- 0.35.1-flask.1 ([#1539](https://github.com/mcmire/snaps/pull/1539))
- 0.35.0-flask.1 ([#1537](https://github.com/mcmire/snaps/pull/1537))
- Move `test-snaps` to this repository ([#1488](https://github.com/mcmire/snaps/pull/1488))
- Implement Jest environment for Snaps end-to-end testing ([#1438](https://github.com/mcmire/snaps/pull/1438))
- Improve JSON parsing safety ([#1499](https://github.com/mcmire/snaps/pull/1499))
- Fix manageState in `snaps-simulator` ([#1494](https://github.com/mcmire/snaps/pull/1494))
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
- Decouple caveats from RPC methods ([#1300](https://github.com/mcmire/snaps/pull/1300))
- 0.32.1 ([#1315](https://github.com/mcmire/snaps/pull/1315))
- 0.32.0 ([#1312](https://github.com/mcmire/snaps/pull/1312))
- 0.31.0 ([#1279](https://github.com/mcmire/snaps/pull/1279))
- Bump `@metamask/utils` to `5.0.0` and handle breaking changes ([#1276](https://github.com/mcmire/snaps/pull/1276))
- Bump `key-tree` to `7.0.0` ([#1275](https://github.com/mcmire/snaps/pull/1275))
- Update workflows to match `MetaMask/core` repository ([#1254](https://github.com/mcmire/snaps/pull/1254))
- Remove JSDOM from all packages ([#1241](https://github.com/mcmire/snaps/pull/1241))
- Implement tests using `webdriverio` ([#1231](https://github.com/mcmire/snaps/pull/1231))
- 0.30.0 ([#1224](https://github.com/mcmire/snaps/pull/1224))
- Fix remove snaps from subjects & update core packages ([#1194](https://github.com/mcmire/snaps/pull/1194))
- 0.29.0 ([#1187](https://github.com/mcmire/snaps/pull/1187))
- Standardise logging across all packages ([#1164](https://github.com/mcmire/snaps/pull/1164))
- Bump @metamask/permission-controller from 1.0.2 to 2.0.0 ([#1156](https://github.com/mcmire/snaps/pull/1156))
- Bump `@metamask/key-tree` to 6.2.1 ([#1142](https://github.com/mcmire/snaps/pull/1142))
- Fix typo in documentation ([#1140](https://github.com/mcmire/snaps/pull/1140))
- 0.28.0 ([#1138](https://github.com/mcmire/snaps/pull/1138))
- bump @metamask/key-tree version ([#1114](https://github.com/mcmire/snaps/pull/1114))
- BREAKING: Add support for snap registries ([#1090](https://github.com/mcmire/snaps/pull/1090))
- Use `@metamask/utils@3.4.0` ([#1102](https://github.com/mcmire/snaps/pull/1102))
- 0.27.1 ([#1084](https://github.com/mcmire/snaps/pull/1084))
- 0.27.0 ([#1079](https://github.com/mcmire/snaps/pull/1079))
- Prefer Babel for Jest coverage ([#1066](https://github.com/mcmire/snaps/pull/1066))
- 0.26.2 ([#1065](https://github.com/mcmire/snaps/pull/1065))
- 0.26.1 ([#1057](https://github.com/mcmire/snaps/pull/1057))
- 0.26.0 ([#1048](https://github.com/mcmire/snaps/pull/1048))
- Bump controllers packages ([#1039](https://github.com/mcmire/snaps/pull/1039))
- 0.25.0 ([#1011](https://github.com/mcmire/snaps/pull/1011))
- Bump @metamask/auto-changelog from 2.6.0 to 3.1.0 ([#1001](https://github.com/mcmire/snaps/pull/1001))
- Use controllers monorepo packages ([#955](https://github.com/mcmire/snaps/pull/955))
- Fix ESLint dependencies ([#1000](https://github.com/mcmire/snaps/pull/1000))
- Bump ESLint configs to latest version ([#963](https://github.com/mcmire/snaps/pull/963))
- 0.24.1 ([#975](https://github.com/mcmire/snaps/pull/975))
- 0.24.0 ([#968](https://github.com/mcmire/snaps/pull/968))
- Remove `wallet_enable` from examples ([#949](https://github.com/mcmire/snaps/pull/949))
- BREAKING: Rename packages to start with `snaps-` ([#937](https://github.com/mcmire/snaps/pull/937))
- Speed up CI by running jobs in parallel ([#917](https://github.com/mcmire/snaps/pull/917))
- 0.23.0 ([#919](https://github.com/mcmire/snaps/pull/919))
- Bump @metamask/utils to 3.3.0 ([#906](https://github.com/mcmire/snaps/pull/906))
- `@metamask/controllers@32.0.2` ([#868](https://github.com/mcmire/snaps/pull/868))
- 0.22.3 ([#856](https://github.com/mcmire/snaps/pull/856))
- 0.22.2 ([#841](https://github.com/mcmire/snaps/pull/841))
- Rename repository ([#842](https://github.com/mcmire/snaps/pull/842))
- 0.22.1 ([#824](https://github.com/mcmire/snaps/pull/824))
- 0.22.0 ([#810](https://github.com/mcmire/snaps/pull/810))
- Bump `@metamask/utils` to `3.1.0` ([#781](https://github.com/mcmire/snaps/pull/781))
- Add `MultiChainProvider` and `MultiChainController` ([#700](https://github.com/mcmire/snaps/pull/700))
- Add keyring endowment permission ([#777](https://github.com/mcmire/snaps/pull/777))
- Bump Jest to the latest version in all packages ([#750](https://github.com/mcmire/snaps/pull/750))
- 0.21.0 ([#776](https://github.com/mcmire/snaps/pull/776))
- Bump `@metamask/controllers` to `31.0.0` ([#769](https://github.com/mcmire/snaps/pull/769))
- 0.20.0 ([#711](https://github.com/mcmire/snaps/pull/711))
- 0.19.1 ([#698](https://github.com/mcmire/snaps/pull/698))
- 0.19.0 ([#687](https://github.com/mcmire/snaps/pull/687))
- Move JSON schemas and controller utils to utils package ([#623](https://github.com/mcmire/snaps/pull/623))
- 0.18.1 ([#640](https://github.com/mcmire/snaps/pull/640))
- 0.18.0 ([#634](https://github.com/mcmire/snaps/pull/634))
- 0.17.0 ([#625](https://github.com/mcmire/snaps/pull/625))
- @metamask/eslint config@9.0.0 ([#559](https://github.com/mcmire/snaps/pull/559))
- Rename package `publish` command to `publish:package` ([#547](https://github.com/mcmire/snaps/pull/547))
- 0.16.0 ([#540](https://github.com/mcmire/snaps/pull/540))
- @metamask/controllers@30.0.0 ([#535](https://github.com/mcmire/snaps/pull/535))
- Fix various monorepo / workspace issues ([#496](https://github.com/mcmire/snaps/pull/496))
- 0.15.0 ([#492](https://github.com/mcmire/snaps/pull/492))
- Update @metamask/auto-changelog to 2.6.0 ([#470](https://github.com/mcmire/snaps/pull/470))
- Use @metamask/utils ([#460](https://github.com/mcmire/snaps/pull/460))
- Fix yarn clean / build:clean not working on yarn 3 ([#469](https://github.com/mcmire/snaps/pull/469))
- Upgrade Yarn to v3 ([#463](https://github.com/mcmire/snaps/pull/463))
- 0.14.0 ([#454](https://github.com/mcmire/snaps/pull/454))
- 0.13.0 ([#447](https://github.com/mcmire/snaps/pull/447))
- 0.12.0 ([#425](https://github.com/mcmire/snaps/pull/425))
- 0.11.1 ([#403](https://github.com/mcmire/snaps/pull/403))
- 0.11.0 ([#401](https://github.com/mcmire/snaps/pull/401))
- Fix changelogs ([#339](https://github.com/mcmire/snaps/pull/339))
- 0.10.7 ([#337](https://github.com/mcmire/snaps/pull/337))
- 0.10.6 ([#312](https://github.com/mcmire/snaps/pull/312))
- 0.10.5 ([#306](https://github.com/mcmire/snaps/pull/306))
- 0.10.3 ([#293](https://github.com/mcmire/snaps/pull/293))
- 0.10.2 ([#283](https://github.com/mcmire/snaps/pull/283))
- 0.10.1 ([#277](https://github.com/mcmire/snaps/pull/277))
- 0.10.0 ([#246](https://github.com/mcmire/snaps/pull/246))
- Delete PermissionController and SubjectMetadataController ([#261](https://github.com/mcmire/snaps/pull/261))
- Fix snap controller utils export ([#239](https://github.com/mcmire/snaps/pull/239))
- 0.9.0 ([#218](https://github.com/mcmire/snaps/pull/218))
- 0.8.0 ([#198](https://github.com/mcmire/snaps/pull/198))
- 0.7.0 ([#193](https://github.com/mcmire/snaps/pull/193))
- 0.6.3 ([#177](https://github.com/mcmire/snaps/pull/177))
- 0.6.2 ([#173](https://github.com/mcmire/snaps/pull/173))
- 0.6.1 ([#170](https://github.com/mcmire/snaps/pull/170))
- Fix build and publish scripts ([#169](https://github.com/mcmire/snaps/pull/169))
- 0.6.0 ([#164](https://github.com/mcmire/snaps/pull/164))
- 0.5.0 ([#146](https://github.com/mcmire/snaps/pull/146))
- 0.4.0 ([#142](https://github.com/mcmire/snaps/pull/142))
- 0.3.1 ([#127](https://github.com/mcmire/snaps/pull/127))
- rpc-methods: Fix tsconfig.local.json ([#122](https://github.com/mcmire/snaps/pull/122))
- 0.3.0 ([#121](https://github.com/mcmire/snaps/pull/121))
- Added Service Messenger ([#100](https://github.com/mcmire/snaps/pull/100))
- 0.2.2 ([#99](https://github.com/mcmire/snaps/pull/99))
- 0.2.0 ([#93](https://github.com/mcmire/snaps/pull/93))
- Update package 'publish' scripts
- 0.1.0 ([#82](https://github.com/mcmire/snaps/pull/82))
- Add snaps-cli and snap-examples packages ([#72](https://github.com/mcmire/snaps/pull/72))
- Fix publishConfig of all packages ([#46](https://github.com/mcmire/snaps/pull/46))
- Add publish scripts to all packages ([#44](https://github.com/mcmire/snaps/pull/44))
- 0.0.6 ([#42](https://github.com/mcmire/snaps/pull/42))
- Add changelog linting to CI, fix changelog issues ([#41](https://github.com/mcmire/snaps/pull/41))
- Update TypeScript and ESLint dependencies ([#29](https://github.com/mcmire/snaps/pull/29))
- Standardize repository, remove lerna ([#16](https://github.com/mcmire/snaps/pull/16))
- Replace `prepare` scripts with `prepublishOnly` ([#15](https://github.com/mcmire/snaps/pull/15))
- @metamask/eslint-config*@6.0.0 ([#8](https://github.com/mcmire/snaps/pull/8))
- 0.0.5 ([#7](https://github.com/mcmire/snaps/pull/7))
- monorepo: Update publishConfig to public
- rpc-methods: Fix controllers type import
- 0.0.4 ([#6](https://github.com/mcmire/snaps/pull/6))
- rpc-methods: Update invokePlugin per updated PluginController.add interface
- 0.0.3 ([#5](https://github.com/mcmire/snaps/pull/5))
- rpc-methods: Update manageAssets to support 'getAll' asset method
- rpc-methods: Use virtual rpc engine to access requestor domain in some methods; various tweaks
- rpc-methods: Add snap_manageAssets restricted method
- rpc-methods: Convert state methods to restricted
- rpc-methods: Refactor internal permitted method exports
- rpc-methods: Add getBip44Entropy, refactor internal restricted method exports
- rpc-methods: Add selectHooks utility function
- rpc-methods: Add hookNames property to handlers
- 0.0.2 ([#4](https://github.com/mcmire/snaps/pull/4))
- rpc-methods: Update types, export names
- monorepo: Add licenses, update npm registry
- monorepo: Fix packages publishConfig
- monorepo: Run lint without --fix in prepare scripts
- controllers, rpc-methods: Add various RPC methods and hooks
- rpc-methods: Add invokePlugin permission and methods
- rpc-methods: Allow multiple method names for restricted methods
- rpc-methods: Add restricted confirm method, update exports
- monorepo: Add @mm-snap/rpc-methods package

## [0.35.2-flask.1]
### Fixed
- Fix type issue introduced by [#1532](https://github.com/MetaMask/snaps/pull/1532) ([#1541](https://github.com/MetaMask/snaps/pull/1541))

## [0.35.1-flask.1]
### Changed
- No changes this release.

## [0.35.0-flask.1]
### Added
- Add `snap_manageAccounts` RPC method ([#1290](https://github.com/MetaMask/snaps/pull/1290))

### Changed
- **BREAKING:** Build packages as both CJS and ESM ([#1519](https://github.com/MetaMask/snaps/pull/1519), ([#1532](https://github.com/MetaMask/snaps/pull/1532)))
  - This is breaking in the sense that imports to `dist/` will now require you to import either `dist/cjs` or `dist/esm`.
- **BREAKING:** Disallow deriving Ethereum keys ([#1217](https://github.com/MetaMask/snaps/pull/1217))
  - Coin type `60` is now blocked for derivation.
- Add `sideEffects: false` ([#1486](https://github.com/MetaMask/snaps/pull/1486))

### Fixed
- Fix BIP-32 path validation ([#1506](https://github.com/MetaMask/snaps/pull/1506))

## [0.34.1-flask.1]
### Changed
- No changes this release.

## [0.34.0-flask.1]
### Changed
- **BREAKING:** Rename `targetKey` to `targetName` as part of updating `PermissionController` ([#1450](https://github.com/MetaMask/snaps/pull/1450))

## [0.33.1-flask.1]
### Fixed
- Fix versions being passed incorrectly during snap install ([#1387](https://github.com/MetaMask/snaps-monorepo/pull/1387))

## [0.33.0-flask.1]
### Added
- Add subject type restrictions to snap-specific permissions ([#1366](https://github.com/MetaMask/snaps-monorepo/pull/1366))
- Add `createSnapsMethodMiddleware` from extension ([#1330](https://github.com/MetaMask/snaps-monorepo/pull/1330))

### Changed
- **BREAKING:** Add encrypt and decrypt hook to let implementations use their own functions ([#1331](https://github.com/MetaMask/snaps-monorepo/pull/1331))
- **BREAKING:** Add `snapIds` caveat mapper ([#1360](https://github.com/MetaMask/snaps-monorepo/pull/1360))
  - Snap dependencies must be specified in a simplified manner. See the PR for an example.

## [0.32.2]
### Changed
- No changes this release.

## [0.32.1]
### Fixed
- Fix `handleSnapInstall` side-effect re-installing all local snaps ([#1314](https://github.com/MetaMask/snaps-monorepo/pull/1314))

## [0.32.0]
### Changed
- Use side effects to install snaps via `wallet_snap` permission ([#1301](https://github.com/MetaMask/snaps-monorepo/pull/1301))

### Fixed
- Fix invoke snap error message ([#1293](https://github.com/MetaMask/snaps-monorepo/pull/1293))
- Ensure that same method hooks are used in type and builder ([#1292](https://github.com/MetaMask/snaps-monorepo/pull/1292))

## [0.31.0]
### Changed
- **BREAKING:** Target `ES2020` ([#1247](https://github.com/MetaMask/snaps-monorepo/pull/1247))
- Improve validation and sanitizing of snap IDs ([#1237](https://github.com/MetaMask/snaps-monorepo/pull/1237))

## [0.30.0]
### Changed
- Accept string operation for `snap_manageState` ([#1208](https://github.com/MetaMask/snaps-monorepo/pull/1208))
  - `snap_manageState` now accepts both enum and string types for its operations

### Removed
- **BREAKING:** Remove deprecated `snap_confirm` ([#809](https://github.com/MetaMask/snaps-monorepo/pull/809))

## [0.29.0]
### Added
- **BREAKING:** Improve request function types ([#1014](https://github.com/MetaMask/snaps-monorepo/pull/1014))
  - `snap.request` is now strongly typed in line with the JSON-RPC methods in this package

### Changed
- **BREAKING:** Replace `wallet_snap_*` permission with `wallet_snap` ([#1182](https://github.com/MetaMask/snaps-monorepo/pull/1182))
  - The new permission uses a caveat-based implementation to specify the snaps that are allowed to be interacted with

## [0.28.0]
### Changed
- **BREAKING:** Bump `key-tree` to `6.2.0` and use `Uint8Array` for secret recovery phrases ([#1137](https://github.com/MetaMask/snaps-monorepo/pull/1137))

## [0.27.1]
### Fixed
- Fix `snap_manageState` with empty state ([#1083](https://github.com/MetaMask/snaps-monorepo/pull/1083))
- Fix `snap_manageState` method hooks ([#1080](https://github.com/MetaMask/snaps-monorepo/pull/1080))

## [0.27.0]
### Changed
- **BREAKING:** Use custom UI in `snap_dialog` ([#1051](https://github.com/MetaMask/snaps-monorepo/pull/1051))
- **BREAKING:** Use SIP-6 algorithm for state encryption ([#1055](https://github.com/MetaMask/snaps-monorepo/pull/1055))
  - This breaks all existing snaps that use `snap_manageState`

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
### Added
- Add placeholder parameter for prompt dialog ([#1007](https://github.com/MetaMask/snaps-monorepo/pull/1007))

## [0.24.1]
### Fixed
- Fix `snap_getBip32PublicKey` manifest validation ([#970](https://github.com/MetaMask/snaps-monorepo/pull/970))

## [0.24.0]
### Added
- Add `snap_getEntropy` JSON-RPC method ([#940](https://github.com/MetaMask/snaps-monorepo/pull/940))
- Add permission validation to `snap.manifest.json` ([#910](https://github.com/MetaMask/snaps-monorepo/pull/910))

### Changed
- **BREAKING:** Remove `wallet_enable` and `wallet_installSnaps` in favor of `wallet_requestSnaps` ([#909](https://github.com/MetaMask/snaps-monorepo/pull/909))
- **BREAKING:** Refactor RPC method params and add tests ([#922](https://github.com/MetaMask/snaps-monorepo/pull/922))

### Removed
- **BREAKING:** Remove `snap_getAppKey` ([#867](https://github.com/MetaMask/snaps-monorepo/pull/867))

## [0.23.0]
### Changed
- **BREAKING:** Bump `@metamask/key-tree` to 6.0.0 ([#918](https://github.com/MetaMask/snaps-monorepo/pull/918))
  - All hexadecimal values are now prefixed with `0x`
  - The package no longer uses `Buffer`. Because of that some fields have been renamed.

## [0.22.3]
### Changed
- No changes this release.

## [0.22.2]
### Added
- Add JSON-RPC validation for Snap RPC requests ([#833](https://github.com/MetaMask/snaps-monorepo/pull/833))

## [0.22.1]
### Changed
- No changes this release.

## [0.22.0]
### Added
- Add `snap_dialog` method and deprecate `snap_confirm` ([#799](https://github.com/MetaMask/snaps-monorepo/pull/799))

## [0.21.0]
### Added
- Add `snap_getBip32PublicKey` RPC method ([#729](https://github.com/MetaMask/snaps-monorepo/pull/729))

### Changed
- Expose master fingerprints on BIP-32 and SLIP-10 nodes ([#773](https://github.com/MetaMask/snaps-monorepo/pull/773))
  - Accomplished by bumping `@metamask/key-tree` to `5.0.2`
- Allow deriving child nodes with `getBip32Entropy` ([#751](https://github.com/MetaMask/snaps-monorepo/pull/751))

### Removed
- **BREAKING:** Remove deprecated `snap_getBip44Entropy_*` method ([#717](https://github.com/MetaMask/snaps-monorepo/pull/717))

### Fixed
- Fix race condition in `wallet_getSnaps` ([#756](https://github.com/MetaMask/snaps-monorepo/pull/756))
- Fix fingerprint derivation on BIP-32 and SLIP-10 nodes ([#773](https://github.com/MetaMask/snaps-monorepo/pull/773))
  - Accomplished by bumping `@metamask/key-tree` to `5.0.2`

## [0.20.0]
### Added
- **BREAKING:** Add Transaction Insight API ([#642](https://github.com/MetaMask/snaps-monorepo/pull/642))
- Add `snap_getBip44Entropy` RPC method and deprecate `snap_getBip44Entropy_*` ([#690](https://github.com/MetaMask/snaps-monorepo/pull/690))

### Changed
- **BREAKING:** Simplify manifest format for permission caveats ([#705](https://github.com/MetaMask/snaps-monorepo/pull/705))

## [0.19.1]
### Changed
- No changes this release.

## [0.19.0]
### Added
- **BREAKING:** Add `snap_getBip32Entropy` method ([#683](https://github.com/MetaMask/snaps-monorepo/pull/683))
- Add new validation and limit for storage ([#621](https://github.com/MetaMask/snaps-monorepo/pull/621))

## [0.18.1]
### Changed
- No changes this release.

## [0.18.0]
### Changed
- Reduce TypeScript compilation target to ES2017 ([#628](https://github.com/MetaMask/snaps-monorepo/pull/628))

## [0.17.0]
### Changed
- **BREAKING:** Bump minimum Node version to 16 ([#601](https://github.com/MetaMask/snaps-monorepo/pull/601))
- **BREAKING:** Replace `getRpcMessageHandler` action with `handleRpcRequest` ([#497](https://github.com/MetaMask/snaps-monorepo/pull/497), [#557](https://github.com/MetaMask/snaps-monorepo/pull/557))

## [0.16.0]
### Changed
- No changes this release.

## [0.15.0]
### Changed
- No changes this release.

## [0.14.0]
### Changed
- **BREAKING:** Increase TypeScript compilation target to ES2020 ([#449](https://github.com/MetaMask/snaps-monorepo/pull/449))
  - This should not be breaking for consumers on any non-deprecated browser or Node.js version.

## [0.13.0]
### Added
- **BREAKING:** Add in-app notifications ([#419](https://github.com/MetaMask/snaps-monorepo/pull/419))

### Changed
- **BREAKING:** Bump `@metamask/key-tree` to `4.0.0` ([#446](https://github.com/MetaMask/snaps-monorepo/pull/446))

## [0.12.0]
### Changed
- No changes this release.

## [0.11.1]
### Fixed
- Fixed an issue with determining whether existing permissions satisfy requested permissions ([#402](https://github.com/MetaMask/snaps-monorepo/pull/402))

## [0.11.0]
### Changed
- **BREAKING:** Wait for unlock on some RPC methods ([#356](https://github.com/MetaMask/snaps-monorepo/pull/356))
- **BREAKING:** Use PermissionController:revokePermissionForAllSubjects ([#351](https://github.com/MetaMask/snaps-monorepo/pull/351))
- Upgraded TypeScript version to minimum 4.4 ([#360](https://github.com/MetaMask/snaps-monorepo/pull/360))

### Fixed
- **BREAKING:** Fix prompting for existing permissions ([#354](https://github.com/MetaMask/snaps-monorepo/pull/354))

## [0.10.7]
### Changed
- **BREAKING:** Bump minimum Node version from 12 to 14 ([#331](https://github.com/MetaMask/snaps-monorepo/pull/331))

## [0.10.6]
### Changed
- No changes this release.

## [0.10.5]
### Changed
- No changes this release.

## [0.10.3]
### Changed
- Throw when trying to invoke a non-installed Snap ([#286](https://github.com/MetaMask/snaps-monorepo/pull/286))

## [0.10.0]
### Added
- `snap_notify` RPC method ([#234](https://github.com/MetaMask/snaps-monorepo/pull/234))

### Changed
- **BREAKING:** Enforce JSON-compatibility of snap state ([#233](https://github.com/MetaMask/snaps-monorepo/pull/233))
  - This state was always supposed to be JSON-compatible, and this is now enforced.

## [0.9.0]
### Changed
- `@metamask/controllers@^25.1.0` ([#207](https://github.com/MetaMask/snaps-monorepo/pull/207))

## [0.8.0]
### Changed
- No changes this release.

## [0.7.0]
### Changed
- No changes this release.

## [0.6.3]
### Changed
- No changes this release.

## [0.6.2]
### Changed
- **BREAKING:** Rename restricted method permission builder exports ([#171](https://github.com/MetaMask/snaps-monorepo/pull/171))

## [0.6.1]
### Fixed
- Fix `snap_confirm` validation logic ([#168](https://github.com/MetaMask/snaps-monorepo/pull/168))
  - [0.6.0] contained a bug where the method would reject most valid parameter combinations.

## [0.6.0]
### Added
- "Endowment" permissions ([#152](https://github.com/MetaMask/snaps-monorepo/pull/152))

### Changed
- **BREAKING:** Support the new Snaps publishing specification ([#140](https://github.com/MetaMask/snaps-monorepo/pull/140))
  - This introduces several breaking changes to how Snaps are developed, hosted, and represented at runtime. See [the specification](https://github.com/MetaMask/specifications/blob/d4a5bf5d6990bb5b02a98bd3f95a24ffb28c701c/snaps/publishing.md) and the referenced pull request for details.
- **BREAKING:** Rename Snap `name` property to `id` ([#147](https://github.com/MetaMask/snaps-monorepo/pull/147))
- **BREAKING:** Update `snap_confirm` parameters ([#158](https://github.com/MetaMask/snaps-monorepo/pull/158))
- Improve types and documentation for `selectHooks` ([#149](https://github.com/MetaMask/snaps-monorepo/pull/149))

### Fixed
- Restricted Snap method `origin` handling ([#150](https://github.com/MetaMask/snaps-monorepo/pull/150))

## [0.5.0]
### Added
- Added `title` and `subtitle` to `snap_confirm` ([#145](https://github.com/MetaMask/snaps-monorepo/pull/145))

### Changed
- **BREAKING:** Update restricted RPC methods per new `PermissionController` ([#143](https://github.com/MetaMask/snaps-monorepo/pull/143))
- **BREAKING:** Convert all TypeScript `interface` declarations to `type` equivalents ([#143](https://github.com/MetaMask/snaps-monorepo/pull/143))
- Update restricted RPC methods per new permissions system ([#143](https://github.com/MetaMask/snaps-monorepo/pull/143))

## [0.4.0]
### Changed
- **BREAKING:** Consolidate Snap state management methods into single method ([#135](https://github.com/MetaMask/snaps-monorepo/pull/135))
  - `snap_manageState`
- **BREAKING:** Replace RPC method and permission description properties with docstrings ([#130](https://github.com/MetaMask/snaps-monorepo/pull/130))

### Removed
- **BREAKING:** Remove `snap_manageAssets` ([#134](https://github.com/MetaMask/snaps-monorepo/pull/134))

## [0.3.1]
### Changed
- No changes this release.

## [0.3.0]
### Changed
- **BREAKING:** Make `wallet_getBip44Entropy_*` implementation safer ([#115](https://github.com/MetaMask/snaps-monorepo/pull/115))
  - Implemented by means of using [`@metamask/key-tree@^3.0.0](https://github.com/MetaMask/key-tree/releases/tag/v3.0.0)
- **BREAKING:** Enforce consistent naming for Snaps-related functionality ([#119](https://github.com/MetaMask/snaps-monorepo/pull/119))

## [0.2.2]
### Fixed
- Package script issues ([#97](https://github.com/MetaMask/snaps-monorepo/pull/97), [#98](https://github.com/MetaMask/snaps-monorepo/pull/98))

## [0.2.0]
### Changed
- Update publish scripts ([#92](https://github.com/MetaMask/snaps-monorepo/pull/92))

## [0.1.0]
### Added
- Readme file ([#71](https://github.com/MetaMask/snaps-monorepo/pull/71))

### Changed
- **BREAKING:** Rename package to `@metamask/rpc-methods` ([#73](https://github.com/MetaMask/snaps-monorepo/pull/73))

## [0.0.6]
### Changed
- **BREAKING:** Migrate `CommandEngine` message format to JSON-RPC ([#11](https://github.com/MetaMask/snaps-monorepo/pull/11))
- **BREAKING:** Use generic execution environment interface ([#19](https://github.com/MetaMask/snaps-monorepo/pull/19))

## [0.0.5]
### Added
- First semi-stable release.

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
[0.12.0]: https://github.com/mcmire/snaps/compare/v0.11.1...v0.12.0
[0.11.1]: https://github.com/mcmire/snaps/compare/v0.11.0...v0.11.1
[0.11.0]: https://github.com/mcmire/snaps/compare/v0.10.7...v0.11.0
[0.10.7]: https://github.com/mcmire/snaps/compare/v0.10.6...v0.10.7
[0.10.6]: https://github.com/mcmire/snaps/compare/v0.10.5...v0.10.6
[0.10.5]: https://github.com/mcmire/snaps/compare/v0.10.3...v0.10.5
[0.10.3]: https://github.com/mcmire/snaps/compare/v0.10.0...v0.10.3
[0.10.0]: https://github.com/mcmire/snaps/compare/v0.9.0...v0.10.0
[0.9.0]: https://github.com/mcmire/snaps/compare/v0.8.0...v0.9.0
[0.8.0]: https://github.com/mcmire/snaps/compare/v0.7.0...v0.8.0
[0.7.0]: https://github.com/mcmire/snaps/compare/v0.6.3...v0.7.0
[0.6.3]: https://github.com/mcmire/snaps/compare/v0.6.2...v0.6.3
[0.6.2]: https://github.com/mcmire/snaps/compare/v0.6.1...v0.6.2
[0.6.1]: https://github.com/mcmire/snaps/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/mcmire/snaps/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/mcmire/snaps/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/mcmire/snaps/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/mcmire/snaps/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/mcmire/snaps/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/mcmire/snaps/compare/v0.2.0...v0.2.2
[0.2.0]: https://github.com/mcmire/snaps/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/mcmire/snaps/compare/v0.0.6...v0.1.0
[0.0.6]: https://github.com/mcmire/snaps/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/mcmire/snaps/releases/tag/v0.0.5
