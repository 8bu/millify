# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.3.0] - 2020-07-25
### Changed
- Outputs an empty suffix if units array is not sufficient length
- Renamed `lowerCase` option to `lowercase` (no breaking change)

## [3.2.1] - 2020-05-12
### Changed
- Update dependencies

## [3.2.0] - 2020-05-12
### Fixed
- Catch and log errors in the command line

## [3.1.5] - 2020-05-12

### Changed
- Change workflow to publish on tag push events

## [3.1.5] - 2020-05-12

### Changed
- Reduce size of packaged tarball by removing source files

## [3.1.4] - 2020-05-12

### Fixed
- Prevent infinite loop but caused by `null` values (thanks @dbankier)

## [3.1.3] - 2019-11-22

### Changed
- Make `options` parameter optional

## [3.1.2] - 2019-09-01

### Changed
- Logic to decipher unit index

## [3.1.1] - 2019-09-01

### Changed
- Convert project to Typescript 
- Updated dependencies

## [3.1.0] - 2017-05-15

### Changed
- Completely rewrite logic and refactor library core.

### Added
- Ability to run package from CLI.
- Option `units` to override default suffixes.
- Option `space` to add a space between digit and suffix.
- Option `decimalSeparator` to override default decimal separator.
- Git hooks for code linting.
- New tests.
- Changelog.

### Removed
- Dependency on `round-to` package.

## [3.0.0] - 2017-04-17

### Added
- ESLint and Prettier for code lint/formatting.
- Option `lowerCase` to output result in lower case.
- Greater test coverage.

### Changed
- Second function parameter to be an object for options. (**BREAKING CHANGE**)
- Renamed `decimal` option to `precision`. (**BREAKING CHANGE**)
- Replaced mocha test library with ava.
- Created `src` directory for library code.
