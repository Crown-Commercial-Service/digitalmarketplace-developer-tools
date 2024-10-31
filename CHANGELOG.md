# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

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
