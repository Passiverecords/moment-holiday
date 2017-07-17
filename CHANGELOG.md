# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]


## 1.1.0 - 2017-07-17
### Added
- `previousHoliday` and `nextHoliday` functions.
- `holidays` alias function for `holiday`.

### Changed
- Moved holidays object from `moment.fn.holidays` to `moment.holidays`.
- Fixed bug where `holidaysBetween` function would only return holidays for the start year.
- `holidaysBetween` function now returns an array of moment objects rather than an object.


## 1.0.0 - 2017-07-16
### Added
- Initial release.

[Unreleased]: https://github.com/kodie/moment-holiday/compare/v1.0.0...HEAD
[1.1.0]: https://github.com/kodie/moment-holiday/compare/v1.0.0...v1.1.0