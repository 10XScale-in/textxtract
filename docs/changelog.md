# Changelog

All notable changes to the `textxtract` project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0]

### Added
- Support for both file paths and bytes input in extractors
- Enhanced `FileInfo` dataclass with comprehensive file metadata
- Context manager support for both sync and async extractors
- Improved logging with structured file information
- Thread pool optimization for async operations

### Changed
- Unified API: both extractors use `extract()` method name
- Enhanced error handling with custom exception hierarchy
- Improved documentation with professional styling
- Better test coverage for all input methods

### Fixed
- Memory leaks in async operations
- Temporary file cleanup issues
- Type hint improvements

For detailed information about any release, see the [API Documentation](api.md) and [Usage Guide](usage.md).