# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added

* Ability to apply softmax derivative
  Note: this is enabled by default
* Travis and Appveyor continuous integration
* Small documentation updates
* Unit tests

### Changed

* The tifffile package is no longer required
* Improve speed for gradient update
* Remove OpenMP support for Windows due to build problems

### Fixed

* Loading of Windows C library for custom installations
* Cross-platform examples
* Saving and loading Python lists in network files

### Removed

## 1.0.0 - 2019-07-11

### Added
- Initial release

[Unreleased]: https://github.com/dmpelt/msdnet/compare/v1.0.0...HEAD
