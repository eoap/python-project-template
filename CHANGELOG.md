<!--
Copyright 2026 Terradue

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Changelog

All notable changes to this archetype will be documented in this file.

The format is based on Keep a Changelog, and this project adheres to Semantic Versioning for template releases.

## [Unreleased]

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security

## [0.3.0] - 2026-07-16

### Added

- `PyPI - Version` and `PyPI - Python Version` in `README.md`. 

### Changed

- License shield and link rather than just mere description in `README.md`.

## [0.2.0] - 2026-07-10

### Changed

- `Taskfile.yaml` aligned according to common Terradue practices.
- `pyproject.toml` aligned according to common Terradue practices.
- Improved classifiers in `pyproject.toml`.

### Fixed

- `license_id` in `pyproject.toml` was hardcoded.
- Hardcoded `requires-python` in `pyproject.toml`, removed from `copier.yaml`

## [0.1.0] - 2026-07-08

### Added

- Initial deployment-ready Copier archetype layout using a top-level `template/` directory.
- Hatch-based Python project scaffold.
- Diátaxis documentation scaffold.
- MkDocs configuration.
- Apache-2.0 license, notice, and source headers.
- Taskfile integration with `Terradue/taskfile-utils`.
- GitHub Actions quality workflow.
- First packaged version of the Terradue Python project template.

[Unreleased]: https://github.com/Terradue/python-project-template/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/Terradue/python-project-template/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/Terradue/python-project-template/releases/tag/v0.1.0
