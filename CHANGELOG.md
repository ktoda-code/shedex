# Changelog

All notable changes to **Shedex** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Initial recurrence scheduling engine (`ScheduleEngine`) with support for:
    - Daily, weekly, monthly rules
    - Day-of-week and nth occurrence rules
    - Multiple start times per day
    - UTC-normalized date handling with timezone conversion
- `ScheduleRule` for defining recurrence patterns
- `ScheduleOptions` for first-day-of-week and other settings
- Unit tests for core scheduling logic
- Maven `pom.xml` configured for Apache License 2.0 and Java 21
- Basic package documentation (`package-info.java`)

### Changed

- _Nothing yet_

### Fixed

- _Nothing yet_

---

## [0.1.0] - 2025-08-15

### Added

- **Initial public release** of Shedex
- Core scheduling engine and recurrence rules
- Apache 2.0 licensing and project metadata

---

[Unreleased]: https://github.com/ktoda-code/shedex/compare/0.1.0...HEAD

[0.1.0]: https://github.com/ktoda-code/shedex/releases/tag/0.1.0
