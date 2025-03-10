# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [3.2.0-rc.2](https://github.com/formatjs/react-intl/compare/v3.2.0-rc.1...v3.2.0-rc.2) (2019-08-29)


### Bug Fixes

* fix tests & add corresponding formatToParts fns ([855e272](https://github.com/formatjs/react-intl/commit/855e272))


### Features

* extend numberformat to unified ([#1462](https://github.com/formatjs/react-intl/issues/1462)) ([a7f2104](https://github.com/formatjs/react-intl/commit/a7f2104))

## [3.2.0-rc.1](https://github.com/formatjs/react-intl/compare/v3.2.0-rc.0...v3.2.0-rc.1) (2019-08-29)

## [3.2.0-rc.0](https://github.com/formatjs/react-intl/compare/v3.1.2...v3.2.0-rc.0) (2019-08-29)

### Features

* add support for formatToParts ([e8167f3](https://github.com/formatjs/react-intl/commit/e8167f3))
* introduce Parts component ([a1b5ff1](https://github.com/formatjs/react-intl/commit/a1b5ff1)), closes [#1048](https://github.com/formatjs/react-intl/issues/1048)

### [3.1.13](https://github.com/formatjs/react-intl/compare/v3.1.12...v3.1.13) (2019-08-28)


### Bug Fixes

* handle relative time when it hits 0 ([3b9df15](https://github.com/formatjs/react-intl/commit/3b9df15)), closes [#1455](https://github.com/formatjs/react-intl/issues/1455)

### [3.1.12](https://github.com/formatjs/react-intl/compare/v3.1.11...v3.1.12) (2019-08-26)


### Bug Fixes

* type def for forwardRef in injectIntl, fix [#1444](https://github.com/formatjs/react-intl/issues/1444) ([45887bf](https://github.com/formatjs/react-intl/commit/45887bf))
* update intl-messageformat ([d1271b6](https://github.com/formatjs/react-intl/commit/d1271b6)), closes [#1451](https://github.com/formatjs/react-intl/issues/1451) [#1442](https://github.com/formatjs/react-intl/issues/1442)

### [3.1.11](https://github.com/formatjs/react-intl/compare/v3.1.10...v3.1.11) (2019-08-21)


### Bug Fixes

* remove params spread, potentially fix [#1424](https://github.com/formatjs/react-intl/issues/1424) ([aeb177c](https://github.com/formatjs/react-intl/commit/aeb177c))

### [3.1.10](https://github.com/formatjs/react-intl/compare/v3.1.9...v3.1.10) (2019-08-20)


### Bug Fixes

* fix UMD build ([fc17473](https://github.com/formatjs/react-intl/commit/fc17473)), closes [#1423](https://github.com/formatjs/react-intl/issues/1423)
* fix UMD build, defer react-is to external ([4731805](https://github.com/formatjs/react-intl/commit/4731805))

### [3.1.9](https://github.com/formatjs/react-intl/compare/v3.1.8...v3.1.9) (2019-08-16)


### Bug Fixes

* fix UMD build ([ad78e3f](https://github.com/formatjs/react-intl/commit/ad78e3f)), closes [#1423](https://github.com/formatjs/react-intl/issues/1423)
* move react & @types/react to devDep, fixes [#1389](https://github.com/formatjs/react-intl/issues/1389) ([0133241](https://github.com/formatjs/react-intl/commit/0133241)), closes [/github.com/yarnpkg/yarn/issues/3951#issuecomment-316424639](https://github.com/formatjs//github.com/yarnpkg/yarn/issues/3951/issues/issuecomment-316424639)

### [3.1.8](https://github.com/formatjs/react-intl/compare/v3.1.7...v3.1.8) (2019-08-13)


### Bug Fixes

* remove injectIntl types from component props ([#1415](https://github.com/formatjs/react-intl/issues/1415)) ([9b359ec](https://github.com/formatjs/react-intl/commit/9b359ec)), closes [#1414](https://github.com/formatjs/react-intl/issues/1414)

### [3.1.7](https://github.com/formatjs/react-intl/compare/v3.1.5...v3.1.7) (2019-08-13)


### Bug Fixes

* avoid wrapping components with injectIntl ([#1413](https://github.com/formatjs/react-intl/issues/1413)), fixes [#1412](https://github.com/formatjs/react-intl/issues/1412) ([ce560e7](https://github.com/formatjs/react-intl/commit/ce560e7))
* fix state typo, fixes [#1411](https://github.com/formatjs/react-intl/issues/1411) ([46ad1c8](https://github.com/formatjs/react-intl/commit/46ad1c8))

### [3.1.6](https://github.com/formatjs/react-intl/compare/v3.1.5...v3.1.6) (2019-08-12)


### Bug Fixes

* fix state typo, fixes [#1411](https://github.com/formatjs/react-intl/issues/1411) ([46ad1c8](https://github.com/formatjs/react-intl/commit/46ad1c8))

### [3.1.5](https://github.com/formatjs/react-intl/compare/v3.1.4...v3.1.5) (2019-08-11)


### Bug Fixes

* drop @types/react version to 16.0 ([1669f0e](https://github.com/formatjs/react-intl/commit/1669f0e))

### [3.1.4](https://github.com/formatjs/react-intl/compare/v3.1.3...v3.1.4) (2019-08-11)


### Bug Fixes

* Fix broken links in Getting Started (fix [#1403](https://github.com/formatjs/react-intl/issues/1403)) ([#1405](https://github.com/formatjs/react-intl/issues/1405)) ([57f0748](https://github.com/formatjs/react-intl/commit/57f0748))
* generate lib instead of mjs ([99f9257](https://github.com/formatjs/react-intl/commit/99f9257)), closes [#1395](https://github.com/formatjs/react-intl/issues/1395) [#1407](https://github.com/formatjs/react-intl/issues/1407)

### [3.1.3](https://github.com/formatjs/react-intl/compare/v3.1.1...v3.1.3) (2019-08-09)


### Bug Fixes

* allow string in formatDate & formatTime ([aed8c68](https://github.com/formatjs/react-intl/commit/aed8c68)), closes [#1396](https://github.com/formatjs/react-intl/issues/1396)
* create initial intl for Provider ([4306275](https://github.com/formatjs/react-intl/commit/4306275))
* formatRelativeTime type def unit param ([cb7da58](https://github.com/formatjs/react-intl/commit/cb7da58))
* remove contextType usage ([660a546](https://github.com/formatjs/react-intl/commit/660a546))

### [3.1.2](https://github.com/formatjs/react-intl/compare/v3.1.1...v3.1.2) (2019-08-09)


### Bug Fixes

* allow string in formatDate & formatTime ([aed8c68](https://github.com/formatjs/react-intl/commit/aed8c68)), closes [#1396](https://github.com/formatjs/react-intl/issues/1396)
* formatRelativeTime type def unit param ([cb7da58](https://github.com/formatjs/react-intl/commit/cb7da58))
* remove contextType usage ([660a546](https://github.com/formatjs/react-intl/commit/660a546))

### [3.1.1](https://github.com/yahoo/react-intl/compare/v3.1.0...v3.1.1) (2019-08-02)


### Bug Fixes

* only createIntl from filteredProps ([d665f31](https://github.com/yahoo/react-intl/commit/d665f31))

## [3.1.0](https://github.com/yahoo/react-intl/compare/v3.0.0...v3.1.0) (2019-08-06)


### Bug Fixes

* add "types" property to package.json ([#1394](https://github.com/yahoo/react-intl/issues/1394)) ([a82ddd0](https://github.com/yahoo/react-intl/commit/a82ddd0))
* add createIntlCache to top level index, fixes [#1393](https://github.com/yahoo/react-intl/issues/1393) ([19398d7](https://github.com/yahoo/react-intl/commit/19398d7))


### Features

* generate .mjs instead of lib ([5fd070d](https://github.com/yahoo/react-intl/commit/5fd070d))

## [3.0.0](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.23...v3.0.0) (2019-08-06)


### Bug Fixes

* rm core pkg for now ([223d2cf](https://github.com/yahoo/react-intl/commit/223d2cf))
* rm rollup for core, reduce @types/react version ([336d365](https://github.com/yahoo/react-intl/commit/336d365))
* type definitions and make behavior match spec more ([2030bdd](https://github.com/yahoo/react-intl/commit/2030bdd))

## [3.0.0-beta.23](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.22...v3.0.0-beta.23) (2019-08-02)

### Features

- simplify provider inheritance, add new APIs ([#1387](https://github.com/yahoo/react-intl/issues/1387)) ([227a444](https://github.com/yahoo/react-intl/commit/227a444)), closes [#1386](https://github.com/yahoo/react-intl/issues/1386) [#1376](https://github.com/yahoo/react-intl/issues/1376)

## [3.0.0-beta.22](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.21...v3.0.0-beta.22) (2019-07-29)

### Bug Fixes

- rm componentWillReceiveProps from relative ([964159b](https://github.com/yahoo/react-intl/commit/964159b))

### Features

- upgrade intl-messageformat with new apostrophe escape ([f59607e](https://github.com/yahoo/react-intl/commit/f59607e))

## [3.0.0-beta.21](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.20...v3.0.0-beta.21) (2019-07-28)

### Bug Fixes

- fix doc for rich text formatting ([00cbf80](https://github.com/yahoo/react-intl/commit/00cbf80))
- FormattedRelativeTime with high seconds values ([#1385](https://github.com/yahoo/react-intl/issues/1385)) ([a7f1dfa](https://github.com/yahoo/react-intl/commit/a7f1dfa))

## [3.0.0-beta.20](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.19...v3.0.0-beta.20) (2019-07-25)

### Bug Fixes

- upgrade intl-messageformat and tests ([1dfe7fd](https://github.com/yahoo/react-intl/commit/1dfe7fd))

## [3.0.0-beta.19](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.18...v3.0.0-beta.19) (2019-07-25)

### Features

- allow formatDate and formatTime to take string type ([#1369](https://github.com/yahoo/react-intl/issues/1369)) ([d110548](https://github.com/yahoo/react-intl/commit/d110548))
- Allow formatting embedded XML ([#1379](https://github.com/yahoo/react-intl/issues/1379)) ([61d3c1b](https://github.com/yahoo/react-intl/commit/61d3c1b))
- Upgrade guide implementing RelativeTime behavior ([#1374](https://github.com/yahoo/react-intl/issues/1374)) ([f8ddcd0](https://github.com/yahoo/react-intl/commit/f8ddcd0))

## [3.0.0-beta.18](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.17...v3.0.0-beta.18) (2019-07-12)

### Bug Fixes

- **types:** Change type to allow autocompletion and existence checking ([#1368](https://github.com/yahoo/react-intl/issues/1368)) ([20d39e6](https://github.com/yahoo/react-intl/commit/20d39e6))

### Features

- make `formatMessage` take in `ReactElement` ([#1367](https://github.com/yahoo/react-intl/issues/1367)) ([15ed625](https://github.com/yahoo/react-intl/commit/15ed625))

## [3.0.0-beta.17](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.16...v3.0.0-beta.17) (2019-07-11)

### Bug Fixes

- add default tagName to HTML message ([#1361](https://github.com/yahoo/react-intl/issues/1361)) ([e86befe](https://github.com/yahoo/react-intl/commit/e86befe))

## [3.0.0-beta.16](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.15...v3.0.0-beta.16) (2019-07-09)

### Features

- expose a core bundle w/o parser ([#1358](https://github.com/yahoo/react-intl/issues/1358)) ([0a6ca3f](https://github.com/yahoo/react-intl/commit/0a6ca3f))
- support textComponent="", fixes [#1330](https://github.com/yahoo/react-intl/issues/1330) ([#1354](https://github.com/yahoo/react-intl/issues/1354)) ([3f27902](https://github.com/yahoo/react-intl/commit/3f27902))
- upgrade formatjs dev ([#1357](https://github.com/yahoo/react-intl/issues/1357)) ([61b536b](https://github.com/yahoo/react-intl/commit/61b536b))

## [3.0.0-beta.15](https://github.com/yahoo/react-intl/compare/v3.0.0-beta-8...v3.0.0-beta.15) (2019-06-28)

### Bug Fixes

- escape defaultMessage properly, fixes [#1158](https://github.com/yahoo/react-intl/issues/1158) ([#1345](https://github.com/yahoo/react-intl/issues/1345)) ([96e9bae](https://github.com/yahoo/react-intl/commit/96e9bae))
- reduce TS version to 3.3 ([#1348](https://github.com/yahoo/react-intl/issues/1348)) ([6dfef2b](https://github.com/yahoo/react-intl/commit/6dfef2b))
- **deps:** move @formatjs/intl-relativetimeformat to deps ([#1349](https://github.com/yahoo/react-intl/issues/1349)) ([310bb62](https://github.com/yahoo/react-intl/commit/310bb62))

### Features

- add standard-version ([b656847](https://github.com/yahoo/react-intl/commit/b656847))
- pass in formatters to IntlMessageFormat for perf ([#1343](https://github.com/yahoo/react-intl/issues/1343)) ([303a4ea](https://github.com/yahoo/react-intl/commit/303a4ea))
- switch to npm ([#1334](https://github.com/yahoo/react-intl/issues/1334)) ([0eab294](https://github.com/yahoo/react-intl/commit/0eab294))
- Use React.Fragment as default textComponent ([#1326](https://github.com/yahoo/react-intl/issues/1326)) ([6e03fa3](https://github.com/yahoo/react-intl/commit/6e03fa3))
- **types:** export WithIntlProps ([#1350](https://github.com/yahoo/react-intl/issues/1350)) ([16d7ed9](https://github.com/yahoo/react-intl/commit/16d7ed9))
- **types:** export WrappedComponentProps ([#1351](https://github.com/yahoo/react-intl/issues/1351)) ([af650b4](https://github.com/yahoo/react-intl/commit/af650b4))

## [3.0.0-beta.14](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.13...v3.0.0-beta.14) (2019-07-03)

### Bug Fixes

- **deps:** move @formatjs/intl-relativetimeformat to deps ([#1349](https://github.com/yahoo/react-intl/issues/1349)) ([310bb62](https://github.com/yahoo/react-intl/commit/310bb62))

## [3.0.0-beta.13](https://github.com/yahoo/react-intl/compare/v3.0.0-beta.12...v3.0.0-beta.13) (2019-07-03)

### Bug Fixes

- escape defaultMessage properly, fixes [#1158](https://github.com/yahoo/react-intl/issues/1158) ([#1345](https://github.com/yahoo/react-intl/issues/1345)) ([96e9bae](https://github.com/yahoo/react-intl/commit/96e9bae))
- reduce TS version to 3.3 ([#1348](https://github.com/yahoo/react-intl/issues/1348)) ([6dfef2b](https://github.com/yahoo/react-intl/commit/6dfef2b))
