# ramsey/conventional-commits Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 1.3.1 - 2022-04-20

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Update how ramsey/conventional-commits uses input and output so this library will work properly (without interface errors) with symfony/console `^4.4.30`, `^5.3.7`, and `^6.0`.

## 1.3.0 - 2022-01-09

### Added

- Support finding `composer.json` when ramsey/conventional-commits is bundled within a Phar (see [#29](https://github.com/ramsey/conventional-commits/pull/29)).
- Allow use of version 6.x of required Symfony packages.

### Changed

- Move captainhook/captainhook to `require-dev` and suggest it as a dependency.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.2.0 - 2021-11-09

### Added

- Update [opis/json-schema](https://opis.io/json-schema) to version 2.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Update minimum Composer versions for [CVE-2021-41116](https://github.com/advisories/GHSA-frqg-7g38-6gcf).

## 1.1.2 - 2021-08-07

Maintenance release, updating project standards and dependencies only.

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.1.1 - 2020-10-26

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Require composer/composer as a standard (non-dev) dependency, since commit hooks do not call CaptainHook in the context of Composer

## 1.1.0 - 2020-10-26

### Added

- [#2](https://github.com/ramsey/conventional-commits/pull/2) enables configuration of Conventional Commits messages

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.0.1 - 2020-08-28

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Add ramsey/devtools to the project and refactor accordingly.

## 1.0.0 - 2020-08-12

Initial release

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.
