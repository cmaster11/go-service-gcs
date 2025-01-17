# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)
and this project adheres to [Semantic Versioning](https://semver.org/).

## [v2.2.0] - 2021-07-21

### Added

- ci: Add gofmt action (#41)
- ci: Add diff check action (#44)
- ci: Add dependabot auto build support (#45)

### Changed

- storage: Update types in service.toml to golang types (#49)
- storage: Implement GSP-654 Unify List Behavior (#49)

### Fixed

- ci: Fix auto-build not work correctly

### Upgraded

- build(deps): Bump cloud.google.com/go/storage from 1.15.0 to 1.16.0 (#38)
- build(deps): Bump google.golang.org/api from 0.49.0 to 0.50.0 (#39)

## [v2.1.0] - 2021-06-29

### Added

- *: Implement GSP-87 Feature Gates (#31)
- storage: Implement GSP-93 Add ObjectMode Pair (#35)

### Changed

- *: Implement GSP-109: Redesign Features (#35)
- *: Implement GSP-117 Rename Service to System as the Opposite to Global (#35)

### Upgraded

- build(deps): Bump google.golang.org/api to 0.49.0 (#34)

## [v2.0.0] - 2021-05-24

### Added

- pair: Add gcs SSE-KMS support (#24)
- *: Implement GSP-47 & GSP-51 (#27)

### Changed

- storage: Idempotent storager delete operation (#26)
- *: Implement GSP-73 Organization rename (#29)

### Upgraded

- build(deps): Bump google.golang.org/api to 0.47.0 (#28)

## v1.0.0 - 2021-04-24

### Added

- Implement gcs service

[v2.2.0]: https://github.com/beyondstorage/go-service-gcs/compare/v2.1.0...v2.2.0
[v2.1.0]: https://github.com/beyondstorage/go-service-gcs/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/beyondstorage/go-service-gcs/compare/v1.0.0...v2.0.0
