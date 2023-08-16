# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.2] - 2023-08-16

- uncheck diagnostic_describe_all_properties rule

## [2.0.1] - 2023-08-11

- uncheck sort_pub_dependencies rule

## [2.0.0] - 2023-08-11

- Updated rules

## [1.0.10] - 2022-01-10

### Fixed

- inference_failure_on_function_invocation removed from analysis_options.yaml, because it is not a rule.

## [1.0.9] - 2022-01-10

### Changed

- Added inference_failure_on_function_invocation rule as error

## [1.0.8] - 2022-01-09

### Changed

- Removed `strong-mode`: implicit-casts, implicit-dynamic because of deprecation

## [1.0.7] - 2022-12-29

### Changed

- Removed `discarded_futures` rule from analysis_options.yaml

## [1.0.6] - 2022-12-29

### Changed

- no_runtimeType_toString rule removed from analysis_options.yaml (again)

## [1.0.5] - 2022-12-29

### Changed

- no_runtimeType_toString rule removed from analysis_options.yaml

## [1.0.4] - 2022-12-29

### Changed

- Removed diagnostic_describe_all_properties rule from analysis_options.yaml

## [1.0.3] - 2022-12-29

### Fixed

- Fixed the conflict in `analysis_options.yaml`. The `prefer relative imports` rule was conflicting with the `prefer package imports` rule. The `prefer relative imports` rule was removed.

## [1.0.2] - 2022-12-29

### Changed

- Changed README.md

## [1.0.1] - 2022-12-29

### Added

- Added a changelog.
- Added a license.

## [1.0.0] - 2022-12-29

### Added

- Instantiated the repository.
- Implemented analysis_options.yaml
