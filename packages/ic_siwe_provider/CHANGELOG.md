# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.6] - 2024-03-25

### Added

- Runtime features that allow for customization of the provider canister behavior: `IncludeUriInSeed`, `DisableEthToPrincipalMapping` and `DisablePrincipalToEthMapping`. See [README.md](./README.md) for details.

## [0.0.5] - 2024-02-22

### Fixed

- Pre-built provider canister did not include metadata, now fixed.

## [0.0.4] - 2024-01-31

### Changed

- Service functions `prepare_login`, `login` and `get_delegation` have been renamed `siwe_prepare_login`, `siwe_login` and `siwe_get_delegation` respectively. See [ic_siwe_provider.did](./ic_siwe_provider.did) for details.

## [0.0.3] - 2024-01-15

- Sync version number with `ic-use-actor` and `ic-use-siwe-identity`.

## [0.0.1] - 2024-01-08

### Added

- First release. `ic_siwe_provider` v0.0.1 should be regarded as alpha software.
