# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [5.4.0](https://github.com/tannerntannern/ts-mixer/compare/v5.3.0...v5.4.0) (2020-11-18)


### Features

* deep decorator inheritance ([6daabc5](https://github.com/tannerntannern/ts-mixer/commit/6daabc5d340d20c8eda4fe96b635a54f6a7e18fb))

## [5.3.0](https://github.com/tannerntannern/ts-mixer/compare/v5.3.0-beta.0...v5.3.0) (2020-06-01)

## [5.3.0-beta.0](https://github.com/tannerntannern/ts-mixer/compare/v5.2.1...v5.3.0-beta.0) (2020-05-31)


### Features

* add hasMixin function ([#27](https://github.com/tannerntannern/ts-mixer/issues/27)) ([c8bfc2d](https://github.com/tannerntannern/ts-mixer/commit/c8bfc2d48854808755088332636e8d166007ed9f))

### [5.2.1](https://github.com/tannerntannern/ts-mixer/compare/v5.2.0...v5.2.1) (2020-05-08)


### Bug Fixes

* mix decorator not preserving constructor name ([7274fa2](https://github.com/tannerntannern/ts-mixer/commit/7274fa26a68e05cc59cde1108610e6a1ab51b430))

## [5.2.0](https://github.com/tannerntannern/ts-mixer/compare/v5.2.0-beta.1...v5.2.0) (2020-04-29)

## [5.2.0-beta.1](https://github.com/tannerntannern/ts-mixer/compare/v5.2.0-beta.0...v5.2.0-beta.1) (2020-04-23)


### Bug Fixes

* wrong this in init functions for Mixin(A, Mixin(B, C)) scenario ([0ba1128](https://github.com/tannerntannern/ts-mixer/commit/0ba11283c63a878271b85c282f75190758101e63))

## [5.2.0-beta.0](https://github.com/tannerntannern/ts-mixer/compare/v5.1.0...v5.2.0-beta.0) (2020-04-13)


### Features

* adds init func feature for impure constructors ([99a946b](https://github.com/tannerntannern/ts-mixer/commit/99a946b8e272773f6bafd7a7e8bf8313517dec16))

## [5.1.0](https://github.com/tannerntannern/ts-mixer/compare/v5.1.0-beta.0...v5.1.0) (2020-03-27)

## [5.1.0-beta.0](https://github.com/tannerntannern/ts-mixer/compare/v5.0.0...v5.1.0-beta.0) (2020-03-26)


### Features

* decorator support for class-validators, typeORM, etc ([2c14812](https://github.com/tannerntannern/ts-mixer/commit/2c1481237b325916ca95dbb9e33141b3220f8068))

## [5.0.0](https://github.com/tannerntannern/ts-mixer/compare/v5.0.0-beta.0...v5.0.0) (2020-03-01)

## [5.0.0-beta.0](https://github.com/tannerntannern/ts-mixer/compare/v4.0.0...v5.0.0-beta.0) (2020-02-02)


### Features

* adds and tests a nearestCommonAncestor function ([b084579](https://github.com/tannerntannern/ts-mixer/commit/b084579d5ac52e0b456be95ff6b776309b436473))
* initial static inheritance implementation ([8467c40](https://github.com/tannerntannern/ts-mixer/commit/8467c40c9748e769eebf77b45cccad5ce785bac9))
* initial version of proxyMix ([95a91c7](https://github.com/tannerntannern/ts-mixer/commit/95a91c78e5f05af75cfc95d82a65ce5b3413b9f1))
* makes mixin constructor argument inference slightly smarter ([b844b5c](https://github.com/tannerntannern/ts-mixer/commit/b844b5c93f5eab0d6f522559ed567f67291fae76))


### Bug Fixes

* mixins with shared ancestor when using proxy prototype ([5af189d](https://github.com/tannerntannern/ts-mixer/commit/5af189d9903083f675f65b5039875c4aa97be1a6))
* resolves indefinite tuple issue with `Longest` type ([68342b0](https://github.com/tannerntannern/ts-mixer/commit/68342b0a3fe224a485f220039af872050aa941fc))
* static chain inheritance ([0aca8f0](https://github.com/tannerntannern/ts-mixer/commit/0aca8f056a005ccf27cc564d5a84abe1ef999d7b))
