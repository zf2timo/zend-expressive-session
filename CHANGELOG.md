# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 0.1.1 - TBD

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- [#5](https://github.com/zendframework/zend-expressive-session/pull/5) removes
  the method `LazySession::segment()`. This method was a remnant from a previous
  refactor, and not intended for the final API. Considering that `Session` does
  not implement the method, calling it would lead to a fatal error anyways.

### Fixed

- Nothing.

## 0.1.0 - 2017-10-10

Initial release.

### Added

- Everything.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.
