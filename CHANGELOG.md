# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0](https://github.com/OpenNHP/opennhp/compare/v1.0.0...v1.1.0) (2026-05-27)


### Features

* **demo:** add demo.nhp TLS proxy to AC nginx ([cc0647c](https://github.com/OpenNHP/opennhp/commit/cc0647c9ab689524291d1fa1e80e6d45f07dc060))
* **demo:** add demo.nhp TLS proxy to AC nginx ([738a996](https://github.com/OpenNHP/opennhp/commit/738a996f061c8df9ee1e9bc62b8fc9781e451d27))
* **js-agent:** add CBOR token support for loading NHP-Agent parameters ([1fb9793](https://github.com/OpenNHP/opennhp/commit/1fb979382c69d2a289a4fa51b888e069da422cd9))
* **js-agent:** add CBOR token support for loading NHP-Agent parameters ([cc36a68](https://github.com/OpenNHP/opennhp/commit/cc36a684348b57bf348301bcf126f17d8a8c04e2))


### Bug Fixes

* address code review feedback for CBOR token modal ([c245470](https://github.com/OpenNHP/opennhp/commit/c245470358412b8650496aa58536d8ff4a916ade))
* **core:** remove cgo dependency from errors ([a7aa3e6](https://github.com/OpenNHP/opennhp/commit/a7aa3e63cbec97cefa3f0489ba48fa30ff2efffb))
* **core:** remove cgo dependency from errors ([6558da6](https://github.com/OpenNHP/opennhp/commit/6558da644bfe391ab9ac88c6375e15827c4b6f6d))
* **demo:** address code review feedback for demo.nhp TLS ([c2f23ac](https://github.com/OpenNHP/opennhp/commit/c2f23acde90f8d4be9b0b1778a410c6463cc6e66))
* **demo:** address follow-up PR review issues for demo.nhp TLS ([3a779a4](https://github.com/OpenNHP/opennhp/commit/3a779a42b33030b6e976fff5c4c8131574010556))
* **demo:** address follow-up PR review issues in demo.nhp renewal workflow ([6be6d4d](https://github.com/OpenNHP/opennhp/commit/6be6d4df38757c8a616b578c5803656cfb7e5c3e))
* **demo:** address follow-up review issues in TLS automation ([ae4b87f](https://github.com/OpenNHP/opennhp/commit/ae4b87f70782d02aebe855e035b7e7830febae51))
* **demo:** address PR review issues for demo.nhp TLS proxy ([d3cc4b5](https://github.com/OpenNHP/opennhp/commit/d3cc4b518e1bb355334927bb42f1c7d17c88999e))
* **demo:** address PR review issues for demo.nhp TLS proxy ([b599278](https://github.com/OpenNHP/opennhp/commit/b5992780cdf73dbcd88ea6892662a64cb44bc33b))
* **demo:** address PR review issues for optional demo.nhp TLS deployment ([5747bee](https://github.com/OpenNHP/opennhp/commit/5747bee0dfc914def84ea1b0f1b74c71a5ce35da))
* **demo:** address review follow-ups for demo.nhp TLS ([c8f6dbc](https://github.com/OpenNHP/opennhp/commit/c8f6dbc9a1432d99050b0159777c1708e59b774d))
* **demo:** correct step ordering, full cert chain, and add -target comment ([f85ddd8](https://github.com/OpenNHP/opennhp/commit/f85ddd88d26c66133bbae8377e299c298273e1f6))
* **js-agent:** address code review feedback for CBOR token modal ([08598cc](https://github.com/OpenNHP/opennhp/commit/08598cc5b5915ba97137854003c44dcc225145ae))
* **noise:** never carry zeroed intermediate chain key between packets ([e7886f8](https://github.com/OpenNHP/opennhp/commit/e7886f8ec675f7a06d3151c8da24900cdf5ced9f))
* **terraform:** mark derived-from-sensitive outputs as nonsensitive ([73dbc24](https://github.com/OpenNHP/opennhp/commit/73dbc24445f69484edd5b347a22cdd596c652564))
* **terraform:** mark derived-from-sensitive outputs as nonsensitive ([9501ba2](https://github.com/OpenNHP/opennhp/commit/9501ba234b182ba5f945c29b0b8bd33aaa894a91))

## [1.0.0](https://github.com/OpenNHP/opennhp/compare/v0.7.3...v1.0.0) (2026-05-15)


### ⚠ BREAKING CHANGES

* **relay:** remove legacy POST /relay; tighten routing contract

### Features

* **js-agent:** add EN/zh-cn language switcher to demo page ([5a7f89d](https://github.com/OpenNHP/opennhp/commit/5a7f89dd9c28b6bf32d1839f9693fce521b6b610))
* **js-agent:** add EN/zh-cn language switcher to demo page ([ca4604e](https://github.com/OpenNHP/opennhp/commit/ca4604e3883b1d99e005f527b1d8638455c94979))
* **js-agent:** expose NHPAgent.version + bump VERSION to 0.7.3 ([e9ba4a4](https://github.com/OpenNHP/opennhp/commit/e9ba4a42a93d485bb22e95f1ca303c169ae51cad))
* **js-agent:** expose NHPAgent.version sourced from nhp/version/VERSION ([0616094](https://github.com/OpenNHP/opennhp/commit/061609405b84098ce8f9a158aedaee3db1feaec0))
* **js-agent:** scope perf metric to network round trip; demo form polish ([1f5408d](https://github.com/OpenNHP/opennhp/commit/1f5408d752ba2a1a5037f3de0436d6f6760f34a3))
* **js-agent:** scope perf metric to network round trip; demo form polish ([8b4c869](https://github.com/OpenNHP/opennhp/commit/8b4c869ab227fdf86714f927351af2ad85671edd))
* **relay:** support multiple nhp-server clusters via pubkey-derived id ([eef8b56](https://github.com/OpenNHP/opennhp/commit/eef8b56dedeb75e0302080b5a31c552df4d16f63))
* **relay:** support multiple nhp-server clusters via pubkey-derived id ([d083653](https://github.com/OpenNHP/opennhp/commit/d0836539febc6b9ea4b264d2b55d1a30d2749270))


### Bug Fixes

* **js-agent:** prevent protected server section from wrapping to two lines ([fbc4ae1](https://github.com/OpenNHP/opennhp/commit/fbc4ae18e37774cb45d97c3f66fc6f98abd041d2))
* **js-agent:** prevent protected server section from wrapping to two lines ([ca398f4](https://github.com/OpenNHP/opennhp/commit/ca398f48625e72230edafce557c2c392566be82e))
* **js-agent:** shorten protected server text to prevent wrapping ([6a9d475](https://github.com/OpenNHP/opennhp/commit/6a9d4752939ff14f5cbc78a81a01244d09a6a615))
* **js-agent:** shorten protected server text to prevent wrapping ([d282fae](https://github.com/OpenNHP/opennhp/commit/d282fae22c036a1e47646802f7c2c71270bbe00a))
* **js-agent:** sync package-lock.json version with package.json ([811f1cf](https://github.com/OpenNHP/opennhp/commit/811f1cf47ba1125e2d403d8f41eb40296f63eb3e))
* **js-agent:** update i18n strings to match shortened text ([0daaba2](https://github.com/OpenNHP/opennhp/commit/0daaba2a4054ba601256bff6384ea24966868e14))
* **js-agent:** update i18n strings to match shortened text ([1000647](https://github.com/OpenNHP/opennhp/commit/1000647bb2759b9a5e93493ca8d7fd6e3656d9f1))
* **relay:** spell "behavior" the American way to satisfy misspell linter ([768725a](https://github.com/OpenNHP/opennhp/commit/768725a132b9151c8ab5165c4940289f19f4d8b2))


### Code Refactoring

* **relay:** remove legacy POST /relay; tighten routing contract ([bda88e1](https://github.com/OpenNHP/opennhp/commit/bda88e18108874bd38c02744f467cb37a4894321))

## [0.7.3](https://github.com/OpenNHP/opennhp/compare/v0.7.2...v0.7.3) (2026-05-08)


### Bug Fixes

* **js-agent:** always load demo config from server, drop localStorage cache ([7f80de1](https://github.com/OpenNHP/opennhp/commit/7f80de1eddcdb819730008c9597f1a222645ee0b))
* **js-agent:** always load demo config from server, drop localStorage… ([f1eb543](https://github.com/OpenNHP/opennhp/commit/f1eb543573a7b65bd7f17372f994b5af6b8895c4))
* **plugins:** align shared deps with endpoints to fix plugin.Open ([a4acc5f](https://github.com/OpenNHP/opennhp/commit/a4acc5fca84d2bd577f236054ddbcf2950643e91))
* **plugins:** align shared deps with endpoints to fix plugin.Open ([5390ffa](https://github.com/OpenNHP/opennhp/commit/5390ffa15b49b884baa87167f162e828b64046f8))

## [0.7.2](https://github.com/OpenNHP/opennhp/compare/v0.7.1...v0.7.2) (2026-05-07)


### Features

* **js-agent:** success overlay, IP footer, and code panel polish ([bd38ed7](https://github.com/OpenNHP/opennhp/commit/bd38ed7ae2675f170fe67f18afdaa261f4792c25))
* **js-agent:** success overlay, IP footer, and code panel polish ([b55f14c](https://github.com/OpenNHP/opennhp/commit/b55f14ced9bb89ec8061e40aa04703aba6094493))
* **server-plugin:** polish basic auth-plugin demo page ([2b7a3f9](https://github.com/OpenNHP/opennhp/commit/2b7a3f91936543d2d3466d45abf7a47d8267769f))
* **server-plugin:** polish basic auth-plugin demo page ([599eb8c](https://github.com/OpenNHP/opennhp/commit/599eb8cc9c4180da381c84f81eb7b0e9c06e1df0))


### Miscellaneous Chores

* release 0.7.2 ([3e83d00](https://github.com/OpenNHP/opennhp/commit/3e83d00b596e3387cdfc75177362c6f825875fd2))

## [Unreleased]

## [0.6.0] - 2025-06-11

### Added
- eBPF/XDP packet filtering support for high-performance knocking
- Docker local debugging environment
- `PASS_KNOCKIP_WITH_RANGE` mode for AC to include IP address ranges

### Changed
- Refactored peer hostname resolve logic
- Aligned UDP open resource behavior with HTTP version
- Server now continues when AC connections are lost in resource groups

### Fixed
- CGO compilation issues
- Escape mod bug
- Possible nil pointer dereference
- Size comparison error

## [0.5.0] - 2025-04-13

### Added
- Plugin system for NHP-Server with separate modules
- Improved build system for server plugins

### Changed
- Separated modules to accommodate building of nhp-serverd and its plugins

## [0.4.1] - 2025-04-06

### Added
- DHP (Data Hiding Protocol) function code
- SM2 P256 ECDH curve support
- Default cipher scheme configuration for DE

### Changed
- Using GMSM as default cipher scheme
- Updated Makefile for building DE on Linux

### Fixed
- Removed redundant logging
- Fixed SM2 P256 ECDH curve usage

## [0.4.0] - 2024-09-04

### Added
- Initial public release
- Jekyll-based documentation site
- GitHub Pages deployment

### Changed
- Updated code structure and symbols to be more self-explanatory

## [0.3.6] - 2024-09-03

### Added
- Pre-release version with core NHP protocol implementation
- Agent, Server, and AC components
- Noise Protocol Framework integration
- Curve25519 and SM2 cipher scheme support

[Unreleased]: https://github.com/OpenNHP/opennhp/compare/v0.6.0...HEAD
[0.6.0]: https://github.com/OpenNHP/opennhp/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/OpenNHP/opennhp/compare/v0.4.1...v0.5.0
[0.4.1]: https://github.com/OpenNHP/opennhp/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/OpenNHP/opennhp/compare/v0.3.6...v0.4.0
[0.3.6]: https://github.com/OpenNHP/opennhp/releases/tag/v0.3.6
