# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.6.2] - 2024-11-23

### Changed

- aws-sdk-s3 = "1.62.0"


## [1.6.1] - 2024-09-23

### Changed

- aws-sdk-s3 = "1.51.0"
- Supported Rust Versions (MSRV) = 1.78.0


## [1.6.0] - 2024-07-20

### Fixed

- `--delete` option does not stop the pipeline after a failure
- `--disable-stalled-stream-protection` not working #32

### Changed

- aws-sdk-s3 = "1.41.0"


## [1.5.0] - 2024-06-15

### Added

- Added Additional checksum(SHA256/SHA1/CRC32/CRC32C) based incremental transfer `--check-additional-checksum` option.
- Added `get_errors_and_consume()` to `Pipeline` to get errors.

### Changed

- aws-sdk-s3 = "1.36.0"

## [1.4.0] - 2024-06-02

### Added

- Added HTTPS proxy authentication support.
- Added `--check-etag` and `--check-etag` & `--auto-chunksize` option.

### Changed

- aws-sdk-s3 = "1.32.0"

## [1.3.0] - 2024-04-28

### Added

- Added [Stalled-stream protection](https://github.com/awslabs/aws-sdk-rust/discussions/956) support(enabled by default).
- Added Express One Zone integration tests.

### Changed

- aws-sdk-s3 = "1.24.0"

## [1.2.0] - 2024-03-28

### Added

- Added Amazon S3 Express One Zone storage class support.

### Changed

- aws-sdk-s3 = "1.21.0"

## [1.1.0] - 2023-12-25

### Fixed

- fixed `--aws-sdk-tracing` bug.

### Changed

- aws-sdk-s3 = "1.11.0"

## [1.0.0] - 2023-11-28

### Changed

- Initial release.
- aws-sdk-s3 = "1.1.0" 