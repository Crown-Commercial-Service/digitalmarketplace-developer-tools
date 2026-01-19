# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.7.0] - 2026-01-19

### Added

- Add task for `ruff` to replace `flake8` and `black`

## [1.6.0] - 2025-11-03

### Added

- Add compatibility for Python 3.14 (πthon)

## [1.5.1] - 2025-10-29

### Fixed

- Temporarily pin pip-tools

## [1.5.0] - 2025-04-04

### Added

- Updated `freeze_requirements` task to compile `pyproject.toml` for apps as well as packages

## [1.4.1] - 2025-04-03

### Fixed

- Make sure `test-parallel` is its own task for frontend testing

## [1.4.0] - 2025-04-04

### Added

- Added the `test_python_parallel` to enable running tests in parallel

## [1.3.2] - 2025-04-03

### Fixed

- Remove `wheel` from `install_pip_tools` task as it is installed by `setuptools`
- Add `setuptools` to the `install_pip_tools` task so we have the latest version

## [1.3.1] - 2024-12-13

### Fixed

- Run `pytest` with `python -m` to execute the tests against the local copy of the project directly

## [1.3.0] - 2024-12-13

### Added

- Update `freeze-requirements` task to compile `requirements-dev.txt` from the `pyproject.toml`

## [1.2.1] - 2024-11-01

### Fixed

- Make sure test files are excluded from releases

## [1.2.0] - 2024-11-01

### Changed

- Replace `setup.py` with `pyproject.toml`

### Added

- Add task for `black` (code formatting)

## [1.1.0] - 2024-05-14

### Changed

- Make the run all task run in debug mode

## [1.0.2] - 2021-10-13

### Changed

- Stop pinning pip-tools

## [1.0.1] - 2021-04-14

### Changed

- Change task run-all to depend on task requirements-dev

## [1.0.0] - 2021-04-14

### Added

- Add task for `mypy`
- Use colored for styled text instead of hand-coded escape sequences

### Fixed

- Fix bootstrap installing python requirements
