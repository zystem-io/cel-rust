# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.9.2](https://github.com/zystem-io/cel-rust/compare/cel-interpreter-v0.9.1...cel-interpreter-v0.9.2) - 2025-10-23

### Added

- Implement Short-Circuit Evaluation for AND Expressions to Fix Issue #117 ([#118](https://github.com/zystem-io/cel-rust/pull/118))

### Fixed

- improve `Context::add_variable` `Err` type ([#127](https://github.com/zystem-io/cel-rust/pull/127))

### Other

- release ([#107](https://github.com/zystem-io/cel-rust/pull/107))
- Add `min` function ([#130](https://github.com/zystem-io/cel-rust/pull/130))
- Fix typos. ([#125](https://github.com/zystem-io/cel-rust/pull/125))
- Add custom Duration and Timestamp types for conversion with serde ([#89](https://github.com/zystem-io/cel-rust/pull/89))
- Export timestamp and duration fn as they were ([#112](https://github.com/zystem-io/cel-rust/pull/112))
- ValueType copy & debug ([#113](https://github.com/zystem-io/cel-rust/pull/113))
- Expose Serialization and ToJson errors ([#114](https://github.com/zystem-io/cel-rust/pull/114))
- Fix compilation without chrono ([#111](https://github.com/zystem-io/cel-rust/pull/111))
- Fix default features, cleanup dependencies & other minor code improvements ([#109](https://github.com/zystem-io/cel-rust/pull/109))
- Added missing timestamp macros ([#106](https://github.com/zystem-io/cel-rust/pull/106))
- release ([#95](https://github.com/zystem-io/cel-rust/pull/95))
- Support `.map` over map ([#105](https://github.com/zystem-io/cel-rust/pull/105))
- Detailed parse error ([#102](https://github.com/zystem-io/cel-rust/pull/102))
- Fix `clippy::too_long_first_doc_paragraph` lints. ([#101](https://github.com/zystem-io/cel-rust/pull/101))
- Support empty/default contexts, put chrono/regex behind features ([#97](https://github.com/zystem-io/cel-rust/pull/97))
- Fix `clippy::empty_line_after_doc_comments` lints ([#98](https://github.com/zystem-io/cel-rust/pull/98))
- Allow `.size()` method on types ([#88](https://github.com/zystem-io/cel-rust/pull/88))
- Conformance test fixes ([#79](https://github.com/zystem-io/cel-rust/pull/79))
- Convert CEL values to JSON ([#77](https://github.com/zystem-io/cel-rust/pull/77))
- Bumped versions
- Removing panics, unimplementeds, etc from interpreter ([#75](https://github.com/zystem-io/cel-rust/pull/75))
- Update parser, interpreter to Rust 2021 edition ([#72](https://github.com/zystem-io/cel-rust/pull/72))
- Fix `rustdoc::bare_url` lints. ([#71](https://github.com/zystem-io/cel-rust/pull/71))
- Fix typos. ([#70](https://github.com/zystem-io/cel-rust/pull/70))
- support for escaping in Bytes and bytes macro ([#64](https://github.com/zystem-io/cel-rust/pull/64))
- Fixed variable type changing due to serialization ([#68](https://github.com/zystem-io/cel-rust/pull/68))
- Err out on unknown function ([#66](https://github.com/zystem-io/cel-rust/pull/66))
- Only use minimal set of chrono features ([#63](https://github.com/zystem-io/cel-rust/pull/63))
- Bumped versions for release
- Get variable and function references from expression ([#61](https://github.com/zystem-io/cel-rust/pull/61))
- Fix method/fn parsing and lookup ([#59](https://github.com/zystem-io/cel-rust/pull/59))
- Make Functions Send + Sync ([#55](https://github.com/zystem-io/cel-rust/pull/55))
- Added missing endsWith macro for String ([#51](https://github.com/zystem-io/cel-rust/pull/51))
- Clippy ([#50](https://github.com/zystem-io/cel-rust/pull/50))
- Added support for .matches macro on String ([#49](https://github.com/zystem-io/cel-rust/pull/49))
- Bump interpreter version to 0.7.1 ([#46](https://github.com/zystem-io/cel-rust/pull/46))
- Make functions module public ([#45](https://github.com/zystem-io/cel-rust/pull/45))
- Fixes #41: Don’t panic on invalid comparisons. ([#42](https://github.com/zystem-io/cel-rust/pull/42))
- Bump version to 0.7.0
- Implement Serialize for Value ([#40](https://github.com/zystem-io/cel-rust/pull/40))
- Bumped cel-interpreter to 0.6.1
- Support indexing maps with any valid key type ([#36](https://github.com/zystem-io/cel-rust/pull/36))
- Support heterogeneous comparisons for numeric types ([#37](https://github.com/zystem-io/cel-rust/pull/37))
- Fixed missing function ([#35](https://github.com/zystem-io/cel-rust/pull/35))
- Bumping to v0.6.0 ([#34](https://github.com/zystem-io/cel-rust/pull/34))
- Feat/serializer ([#33](https://github.com/zystem-io/cel-rust/pull/33))
- Expose Context.clone(...) method to external crates ([#31](https://github.com/zystem-io/cel-rust/pull/31))
- Fix links to examples ([#29](https://github.com/zystem-io/cel-rust/pull/29))
- Cargo release version bumps
- Supporting thread-safe execution ([#22](https://github.com/zystem-io/cel-rust/pull/22))
- Support indexed-based map accesses
- Merge pull request #20 from clarkmcc/19-fix-operator-precedence
- Updating cargo dependencies
- Bumped dep version in cel-interpreter
- Bumped versions
- Merge pull request #11 from clarkmcc/function-value-resolvers
- Cleanup, linting, and more examples
- Fixing a few quirks and adding more function examples
- Removed the need for this() or FromThis traits
- More cleanup
- More cleanup
- Updated README with function example
- General clean up
- Lots of tidying and documenting
- Ported existing functions to use magic params
- Renamed target to this
- wip
- Working on magic functions
- First pass of function value resolvers
- Fixed failing test
- Bunch of renaming and cleanup
- Updated crate metadata
- Bumping versions, updating, preparing for cargo release
- Bumping versions, updating readme, preparing for cargo release
- Updating deps
- Simplify adding timestamps and durations
- Added .string() function and duration formatting
- Added function context for better function utilities ([#7](https://github.com/zystem-io/cel-rust/pull/7))
- Simplified duration parsing ([#8](https://github.com/zystem-io/cel-rust/pull/8))
- Added some examples about how to use the library ([#5](https://github.com/zystem-io/cel-rust/pull/5))
- Support Timestamp type ([#4](https://github.com/zystem-io/cel-rust/pull/4))
- Fixed test and updated status badge
- Added .startsWith method for README example completeness
- Added support for spec-compatible durations
- Cleaning up max function
- Added max function
- Benchmarks
- Updated `all` function to support map keys
- Added spec-compatible `filter` and `all` functions with tests
- Added spec-compatible `map` function and tests
- Added spec-compatible `has` function and tests
- Added spec-compatible size function and tests
- Removed experimental set support
- Set benchmarks
- Set operations and conversion functions
- Set tests and new error types
- Added contains and intoSet functions
- Set difference operations on map and array
- Converted CelType::List from array to Vec
- Updated readme
- Support map merging using '+' operator
- Lots more overhauling and cleanup
- Grab bag of changes including failable functions and map traversal
- Add versions to workspace paths
- Implement sub/mul/div/rem for float/integer CelType variants
- (cargo-release) start next development iteration {{next_version}}
- Try this
- 0.1.2
- Fix versions
- (cargo-release) version 0.1.1
- Remove build dependencies
- Update
- Split the project out into sub-crates

## [0.9.1](https://github.com/clarkmcc/cel-rust/compare/cel-interpreter-v0.9.0...cel-interpreter-v0.9.1) - 2025-04-29

### Added

- Implement Short-Circuit Evaluation for AND Expressions to Fix Issue #117 ([#118](https://github.com/clarkmcc/cel-rust/pull/118))

### Fixed

- improve `Context::add_variable` `Err` type ([#127](https://github.com/clarkmcc/cel-rust/pull/127))

### Other

- Add `min` function ([#130](https://github.com/clarkmcc/cel-rust/pull/130))
- Fix typos. ([#125](https://github.com/clarkmcc/cel-rust/pull/125))
- Add custom Duration and Timestamp types for conversion with serde ([#89](https://github.com/clarkmcc/cel-rust/pull/89))
- Export timestamp and duration fn as they were ([#112](https://github.com/clarkmcc/cel-rust/pull/112))
- ValueType copy & debug ([#113](https://github.com/clarkmcc/cel-rust/pull/113))
- Expose Serialization and ToJson errors ([#114](https://github.com/clarkmcc/cel-rust/pull/114))
- Fix compilation without chrono ([#111](https://github.com/clarkmcc/cel-rust/pull/111))
- Fix default features, cleanup dependencies & other minor code improvements ([#109](https://github.com/clarkmcc/cel-rust/pull/109))
- Added missing timestamp macros ([#106](https://github.com/clarkmcc/cel-rust/pull/106))

## [0.9.0](https://github.com/clarkmcc/cel-rust/compare/cel-interpreter-v0.8.1...cel-interpreter-v0.9.0) - 2024-10-30

### Other

- Support `.map` over map ([#105](https://github.com/clarkmcc/cel-rust/pull/105))
- Detailed parse error ([#102](https://github.com/clarkmcc/cel-rust/pull/102))
- Fix `clippy::too_long_first_doc_paragraph` lints. ([#101](https://github.com/clarkmcc/cel-rust/pull/101))
- Support empty/default contexts, put chrono/regex behind features ([#97](https://github.com/clarkmcc/cel-rust/pull/97))
- Fix `clippy::empty_line_after_doc_comments` lints ([#98](https://github.com/clarkmcc/cel-rust/pull/98))
- Allow `.size()` method on types ([#88](https://github.com/clarkmcc/cel-rust/pull/88))
- Conformance test fixes ([#79](https://github.com/clarkmcc/cel-rust/pull/79))
- Convert CEL values to JSON ([#77](https://github.com/clarkmcc/cel-rust/pull/77))
