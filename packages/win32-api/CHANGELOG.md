# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [9.1.0](https://github.com/waitingsong/node-win32-api/compare/v9.0.0...v9.1.0) (2020-02-06)


### Features

* add user EnumDisplayDevicesW() ([9a9e321](https://github.com/waitingsong/node-win32-api/commit/9a9e3213d5bfa59a8b43f81c53b2aee41cec4568))





# [9.0.0](https://github.com/waitingsong/node-win32-api/compare/v8.0.0...v9.0.0) (2020-01-21)


* refactor!: change type of handle from Buffer to number (uint32/uint64) ([47be79e](https://github.com/waitingsong/node-win32-api/commit/47be79e0875bb8b33575ba4cb815705a4e161d87))


### BREAKING CHANGES

* the apis accept only number|bignum|string, no null any more





# [8.0.0](https://github.com/waitingsong/node-win32-api/compare/v7.1.0...v8.0.0) (2020-01-10)

**Note:** Version bump only for package win32-api





# [7.1.0](https://github.com/waitingsong/node-win32-api/compare/v7.0.2...v7.1.0) (2020-01-10)


### Features

* **win32-api:** define CW_USEDEFAULT in user32/constants.ts ([697e4df](https://github.com/waitingsong/node-win32-api/commit/697e4dfcef565fa9e3bf662ce888e714ba7eb814))





## [7.0.2](https://github.com/waitingsong/node-win32-api/compare/v7.0.1...v7.0.2) (2019-12-23)

**Note:** Version bump only for package win32-api





## [7.0.1](https://github.com/waitingsong/node-win32-api/compare/v7.0.0...v7.0.1) (2019-12-23)

**Note:** Version bump only for package win32-api





# [7.0.0](https://github.com/waitingsong/node-win32-api/compare/v6.2.0...v7.0.0) (2019-12-23)


### chore

* **deps:** use ffi-napi instead of ffi ([bfa006c](https://github.com/waitingsong/node-win32-api/commit/bfa006c468e93813cfedce68eb2e94fd901058cc))


### BREAKING CHANGES

* **deps:** remove nodejs v8 support





# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [6.2.0](https://github.com/waitingsong/node-win32-api/compare/v6.1.0...v6.2.0) (2019-10-11)

# [6.1.0](https://github.com/waitingsong/node-win32-api/compare/v6.0.0...v6.1.0) (2019-03-17)


### Features

* **kernel32:** add GetSystemTimes() ([9a7587f](https://github.com/waitingsong/node-win32-api/commit/9a7587f))



<a name="3.9.0"></a>
# [3.9.0](https://github.com/waitingsong/node-win32-api/compare/v3.8.0...v3.9.0) (2019-02-22)


### Features

* add user32.PostMessageW() ([7b02830](https://github.com/waitingsong/node-win32-api/commit/7b02830))



<a name="3.8.0"></a>
# [3.8.0](https://github.com/waitingsong/node-win32-api/compare/v3.7.1...v3.8.0) (2019-02-22)


### Features

* add user32.SendMessageW() ([a3036d6](https://github.com/waitingsong/node-win32-api/commit/a3036d6))



<a name="3.7.1"></a>
## [3.7.1](https://github.com/waitingsong/node-win32-api/compare/v3.7.0...v3.7.1) (2019-02-22)



<a name="3.7.0"></a>
# [3.7.0](https://github.com/waitingsong/node-win32-api/compare/v3.6.0...v3.7.0) (2019-02-21)


### Bug Fixes

* catch test error ([5efe156](https://github.com/waitingsong/node-win32-api/commit/5efe156))
* createDir() path resolve under linux ([c6d1274](https://github.com/waitingsong/node-win32-api/commit/c6d1274))
* error TS1345: An expression of type 'void' cannot be tested for truthiness ([0085713](https://github.com/waitingsong/node-win32-api/commit/0085713))


### Features

* add Observable functions ([c9364db](https://github.com/waitingsong/node-win32-api/commit/c9364db))
* do isPathAccessible() first within isDirFileExists() ([9ddae98](https://github.com/waitingsong/node-win32-api/commit/9ddae98))
* export native assert() ([683cea8](https://github.com/waitingsong/node-win32-api/commit/683cea8))
* export statAsync ([c832590](https://github.com/waitingsong/node-win32-api/commit/c832590))
* remove log() and logger() ([27e1e29](https://github.com/waitingsong/node-win32-api/commit/27e1e29))
