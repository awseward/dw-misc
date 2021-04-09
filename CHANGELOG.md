# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Fixed
- Stop using unknown input as part of `mktemp` template. This could cause problems if said input contained any `X`s (https://github.com/awseward/dw-misc/pull/4)

## [0.0.1] - 2019-12-18
### Added
- Some dw-related scripts/binaries used in a couple different repos.
