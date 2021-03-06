# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [v1.3.0] - 2017-10-04
### Added
- Support for placeholders on PyStrings and TableNodes
- Placeholders chaining: use placeholders inside a placeholder
- Context Initializer: manipulate placeholders inside your Context

## [v1.2.1] - 2017-09-23
### Fixed
- Having empty .feature files does not cause an exception anymore

## [v1.2.0] - 2017-03-26
### Added
- CHANGELOG.md

### Changed
- Started keeping track of changes on CHANGELOG.md
- Variant branching done earlier (right after Gherkin's *.feature parsing phase)

### Fixed
- Behat --tags filter now works correctly on variant tagged scenarios

[Unreleased]: https://github.com/ciandt-dev/behat-placeholders-extension/compare/v1.3.0...HEAD
[v1.3.0]: https://github.com/ciandt-dev/behat-placeholders-extension/compare/v1.2.1...v1.3.0
[v1.2.1]: https://github.com/ciandt-dev/behat-placeholders-extension/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/ciandt-dev/behat-placeholders-extension/compare/v1.1.1...v1.2.0