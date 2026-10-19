# Changelog

## [2.0.0](https://github.com/callmenet/mcp-shell/compare/v1.1.1...v2.0.0) (2026-10-19)


### ⚠ BREAKING CHANGES

* replace secure-mode shell_exec with typed tools

### Features

* AST-based command unfurling for secure mode ([6ef72cd](https://github.com/callmenet/mcp-shell/commit/6ef72cdeb757a77778da3678bbe5d704752d0d5b))
* AST-based command unfurling for secure mode ([9654784](https://github.com/callmenet/mcp-shell/commit/9654784876fe42669c02fd6d1e5f5d3dbb3a4da6))
* change to yaml for sec config ([b9f3cd2](https://github.com/callmenet/mcp-shell/commit/b9f3cd286e48f48fea02420ac12229227cbcee14))
* confine child execution with a Landlock sandbox ([7220aeb](https://github.com/callmenet/mcp-shell/commit/7220aebcce61be38e719b3a4591dcd3071394d9b))
* confine child process execution with a Landlock sandbox ([5dc76ad](https://github.com/callmenet/mcp-shell/commit/5dc76add779490b271f605fca19ee9f1568013ba))
* **paths:** add workspace path confinement ([b398e0d](https://github.com/callmenet/mcp-shell/commit/b398e0d6833e695c360ffba54e4becd91158424f))
* primer ([1531906](https://github.com/callmenet/mcp-shell/commit/153190684eb7d14a893727bc7ac845649a5aa25d))
* publish Docker image to Docker Hub on release ([87eec2f](https://github.com/callmenet/mcp-shell/commit/87eec2fd39269e35c88ee58bb94a6afb96973df2))
* publish Docker image to Docker Hub on release ([99314e3](https://github.com/callmenet/mcp-shell/commit/99314e3cc236dc2c69341bdb1074071e60e119e1))
* replace secure-mode shell_exec with typed tools ([cda5814](https://github.com/callmenet/mcp-shell/commit/cda5814e83ccecb222ce9b1292a2dd556e7507e9))
* security context ([9edc12f](https://github.com/callmenet/mcp-shell/commit/9edc12f4a55a485d97506200faaf70ec1ab8cd68))
* **tools:** add file and git write tools behind writes_enabled ([a5cd368](https://github.com/callmenet/mcp-shell/commit/a5cd3687245ea61e92a45c54c76c28d02b0869b5))
* **tools:** add run_script with operator-defined argv ([ecbbfc0](https://github.com/callmenet/mcp-shell/commit/ecbbfc079c554a02b9c4ae906de8b927a5b233e0))
* **tools:** add typed read-only filesystem tools ([0426796](https://github.com/callmenet/mcp-shell/commit/0426796284a0daa0774bb51f81ba6e040f3f92d4))
* **tools:** add typed read-only git tools ([3ab4aea](https://github.com/callmenet/mcp-shell/commit/3ab4aead7a57a2a9169b177f8ee768e02098483b))


### Bug Fixes

* case-fold the git control-surface write guard (GHSA-vv99-jjh6-3c8x) ([2f724f6](https://github.com/callmenet/mcp-shell/commit/2f724f6316bddc857feba36963376baaf4e7bd2e))
* case-fold the git control-surface write guard (GHSA-vv99-jjh6-3c8x) ([aa868dc](https://github.com/callmenet/mcp-shell/commit/aa868dc6c1ba48a6d1675a52ee475f15f0338c62))
* check shell meta-characters ([4fb7e61](https://github.com/callmenet/mcp-shell/commit/4fb7e61b9cd29d94d4ac5c6b41959130592d8a4a))
* check shell meta-characters ([14ca5d8](https://github.com/callmenet/mcp-shell/commit/14ca5d84d9a02610f3c5506dd7c808e7f11e5ea1))
* enforce blocked_patterns and blocked_commands in secure mode ([65a2b3d](https://github.com/callmenet/mcp-shell/commit/65a2b3d1d4ab8edf252a2848c78a79e25b5e3ab8))
* make secure mode the default and keep interpreters out of the allowlist ([f31377f](https://github.com/callmenet/mcp-shell/commit/f31377fce6ec31114e5a4398c0e5270552bce09f))
* reject client writes to git's control surface (GHSA-c598-5pxh-5vq3) ([a9fb81c](https://github.com/callmenet/mcp-shell/commit/a9fb81c97cccb4315a2b4526e068ba59fe082928))
* reject client writes to git's control surface (GHSA-c598-5pxh-5vq3) ([6bf0b38](https://github.com/callmenet/mcp-shell/commit/6bf0b388eb63d9b44a8c06fb050c89ee56a3175e))
* secure mode by default + keep interpreters out of the allowlist ([df02c8c](https://github.com/callmenet/mcp-shell/commit/df02c8c74044a950d5c085626da8de49c7551cd5))
* **security:** deny abbreviated forms of denied git long options ([743791c](https://github.com/callmenet/mcp-shell/commit/743791c27351df9cc126271ded1916fb85021979))
* **security:** deny abbreviated forms of denied git long options ([d205560](https://github.com/callmenet/mcp-shell/commit/d2055602d78548c7634e3dddf22ee81e41e29193))
* **security:** deny-by-default argument allowlist for governed binaries ([ac4af99](https://github.com/callmenet/mcp-shell/commit/ac4af997ae1d1eb2adf0d0878b10a9fecf01ea1d))
* **security:** deny-by-default argument allowlist for governed binaries ([120aec2](https://github.com/callmenet/mcp-shell/commit/120aec2eed1fe750d9821e3943039597b855da1c))
* **security:** fail closed on privilege-drop and working-dir setup errors ([7fe9e88](https://github.com/callmenet/mcp-shell/commit/7fe9e88eaab59675895cf124d2994a81d770776a))

## [1.1.1](https://github.com/sonirico/mcp-shell/compare/v1.1.0...v1.1.1) (2026-09-25)


### Bug Fixes

* case-fold the git control-surface write guard (GHSA-vv99-jjh6-3c8x) ([aa868dc](https://github.com/sonirico/mcp-shell/commit/aa868dc))

## [1.1.0](https://github.com/sonirico/mcp-shell/compare/v1.0.1...v1.1.0) (2026-09-13)


### Features

* confine child process execution with a Landlock sandbox ([5dc76ad](https://github.com/sonirico/mcp-shell/commit/5dc76ad))

## [1.0.1](https://github.com/sonirico/mcp-shell/compare/v1.0.0...v1.0.1) (2026-09-13)


### Bug Fixes

* **security:** reject client writes to git's control surface (GHSA-c598-5pxh-5vq3) ([6bf0b38](https://github.com/sonirico/mcp-shell/commit/6bf0b38))

## [1.0.0](https://github.com/sonirico/mcp-shell/compare/v0.8.1...v1.0.0) (2026-09-04)


### ⚠ BREAKING CHANGES

* replace secure-mode shell_exec with typed tools

### Features

* **paths:** add workspace path confinement ([b398e0d](https://github.com/sonirico/mcp-shell/commit/b398e0d6833e695c360ffba54e4becd91158424f))
* replace secure-mode shell_exec with typed tools ([cda5814](https://github.com/sonirico/mcp-shell/commit/cda5814e83ccecb222ce9b1292a2dd556e7507e9))
* **tools:** add file and git write tools behind writes_enabled ([a5cd368](https://github.com/sonirico/mcp-shell/commit/a5cd3687245ea61e92a45c54c76c28d02b0869b5))
* **tools:** add run_script with operator-defined argv ([ecbbfc0](https://github.com/sonirico/mcp-shell/commit/ecbbfc079c554a02b9c4ae906de8b927a5b233e0))
* **tools:** add typed read-only filesystem tools ([0426796](https://github.com/sonirico/mcp-shell/commit/0426796284a0daa0774bb51f81ba6e040f3f92d4))
* **tools:** add typed read-only git tools ([3ab4aea](https://github.com/sonirico/mcp-shell/commit/3ab4aead7a57a2a9169b177f8ee768e02098483b))

## [0.8.1](https://github.com/sonirico/mcp-shell/compare/v0.8.0...v0.8.1) (2026-09-04)


### Bug Fixes

* **security:** deny abbreviated forms of denied git long options ([743791c](https://github.com/sonirico/mcp-shell/commit/743791c27351df9cc126271ded1916fb85021979))
* **security:** deny abbreviated forms of denied git long options ([d205560](https://github.com/sonirico/mcp-shell/commit/d2055602d78548c7634e3dddf22ee81e41e29193))

## [0.8.0](https://github.com/sonirico/mcp-shell/compare/v0.7.2...v0.8.0) (2026-08-27)


### Features

* **security:** close the allowlisted-binary-runs-anything class (GHSA-gg85-6grh-63fp) with deny-by-default executable classification, minimal child environment, git repo-config neutralisation, write-time output cap, and rejection of relative argv[0] and NUL bytes ([#28](https://github.com/sonirico/mcp-shell/pull/28))

## [0.7.2](https://github.com/sonirico/mcp-shell/compare/v0.7.1...v0.7.2) (2026-08-27)


### Bug Fixes

* **security:** fail closed on privilege-drop and working-dir setup errors ([7fe9e88](https://github.com/sonirico/mcp-shell/commit/7fe9e88eaab59675895cf124d2994a81d770776a))

## [0.7.1](https://github.com/sonirico/mcp-shell/compare/v0.7.0...v0.7.1) (2026-08-16)


### Bug Fixes

* **security:** deny-by-default argument allowlist for governed binaries ([ac4af99](https://github.com/sonirico/mcp-shell/commit/ac4af997ae1d1eb2adf0d0878b10a9fecf01ea1d))
* **security:** deny-by-default argument allowlist for governed binaries ([120aec2](https://github.com/sonirico/mcp-shell/commit/120aec2eed1fe750d9821e3943039597b855da1c))

## [0.7.0](https://github.com/sonirico/mcp-shell/compare/v0.6.0...v0.7.0) (2026-06-14)


### Features

* AST-based command unfurling for secure mode ([6ef72cd](https://github.com/sonirico/mcp-shell/commit/6ef72cdeb757a77778da3678bbe5d704752d0d5b))
* AST-based command unfurling for secure mode ([9654784](https://github.com/sonirico/mcp-shell/commit/9654784876fe42669c02fd6d1e5f5d3dbb3a4da6))
