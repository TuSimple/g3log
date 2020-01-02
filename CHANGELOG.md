# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.2.4] - 2020-01-02
### Added
- Add G3_NO_STDERR_MESSAGE option to prevent g3log from messing up stderr
### Changed
- Small changes to log formatting

## [1.3.2.3] - 2020-01-02
### Added
- Accept std::string&& in saveMessage() to optimize large log entry processing

## [1.3.2.2] - 2019-12-27
### Added
- Add ERROR level by default
- Add LogCapture::vcapturef for function wrapping
### Changed
- Change `WARNING` to `WARN`, and align level texts
- Disable dynamic logging levels

## [1.3.2.1] - 2019-12-15
### Changed
- Add POSITION_INDEPENDENT_CODE flag when building static library
- Build static library by default

## [1.3.2] - 2019-12-02
### Added
- Forked master branch from `KjellKod/g3log`.
- Added tspkg support.