# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2021-12-20
### Removed
- `bin/dw_` shims (https://github.com/awseward/dw-misc/pull/12)

## [0.0.4] - 2021-12-15
### Changed
- Consolidate `bin/dw_*` into `bin/dw *` (https://github.com/awseward/dw-misc/pull/10)

## [0.0.3] - 2021-12-15
### Fixed
- Add `-f` flag so that curl actually exits nonzero for non-2xx HTTP codes (https://github.com/awseward/dw-misc/pull/8)

## [0.0.2] - 2021-04-09
### Fixed
- Stop using unknown input as part of `mktemp` template. This could cause problems if said input contained any `X`s (https://github.com/awseward/dw-misc/pull/4)

## [0.0.1] - 2020-12-18
### Added
- Some dw-related scripts/binaries used in a couple different repos.
