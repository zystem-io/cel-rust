# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.8.2](https://github.com/zystem-io/cel-rust/compare/cel-parser-v0.8.1...cel-parser-v0.8.2) - 2025-10-23

### Added

- Implement Short-Circuit Evaluation for AND Expressions to Fix Issue #117 ([#118](https://github.com/zystem-io/cel-rust/pull/118))

### Other

- release ([#107](https://github.com/zystem-io/cel-rust/pull/107))
- release ([#95](https://github.com/zystem-io/cel-rust/pull/95))
- Detailed parse error ([#102](https://github.com/zystem-io/cel-rust/pull/102))
- Update lalrpop to 0.22 from 0.19.x ([#99](https://github.com/zystem-io/cel-rust/pull/99))
- Fix `clippy::empty_line_after_doc_comments` lints ([#98](https://github.com/zystem-io/cel-rust/pull/98))
- Conformance test fixes ([#79](https://github.com/zystem-io/cel-rust/pull/79))
- Bumped versions
- Update parser, interpreter to Rust 2021 edition ([#72](https://github.com/zystem-io/cel-rust/pull/72))
- Faster bytes parsing ([#69](https://github.com/zystem-io/cel-rust/pull/69))
- support for escaping in Bytes and bytes macro ([#64](https://github.com/zystem-io/cel-rust/pull/64))
- Bumped versions for release
- Get variable and function references from expression ([#61](https://github.com/zystem-io/cel-rust/pull/61))
- Fix method/fn parsing and lookup ([#59](https://github.com/zystem-io/cel-rust/pull/59))
- Clippy ([#50](https://github.com/zystem-io/cel-rust/pull/50))
- Implement string parser ([#24](https://github.com/zystem-io/cel-rust/pull/24))
- Cargo release version bumps
- Supporting thread-safe execution ([#22](https://github.com/zystem-io/cel-rust/pull/22))
- Merge pull request #20 from clarkmcc/19-fix-operator-precedence
- Updating cargo dependencies
- Fixed operator precedence #19
- Fixing cel-parser README example
- Bumped versions
- Adds a bunch of parser tests
- Refactor code to hide parser internals
- Updated crate metadata
- Bumping versions, updating, preparing for cargo release
- Bumping versions, updating readme, preparing for cargo release
- Added spec-compatible `map` function and tests
- Removed experimental set support
- Added contains and intoSet functions
- Lots more overhauling and cleanup
- Removed support for doubly quoted strings to fix LALRPOP errors
- (cargo-release) start next development iteration {{next_version}}
- 0.1.2
- (cargo-release) version 0.1.1
- Update
- Split the project out into sub-crates

## [0.8.1](https://github.com/clarkmcc/cel-rust/compare/cel-parser-v0.8.0...cel-parser-v0.8.1) - 2025-04-29

### Added

- Implement Short-Circuit Evaluation for AND Expressions to Fix Issue #117 ([#118](https://github.com/clarkmcc/cel-rust/pull/118))

## [0.8.0](https://github.com/clarkmcc/cel-rust/compare/cel-parser-v0.7.1...cel-parser-v0.8.0) - 2024-10-30

### Other

- Detailed parse error ([#102](https://github.com/clarkmcc/cel-rust/pull/102))
- Update lalrpop to 0.22 from 0.19.x ([#99](https://github.com/clarkmcc/cel-rust/pull/99))
- Fix `clippy::empty_line_after_doc_comments` lints ([#98](https://github.com/clarkmcc/cel-rust/pull/98))
- Conformance test fixes ([#79](https://github.com/clarkmcc/cel-rust/pull/79))
