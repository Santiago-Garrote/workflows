# Changelog

<!--toc:start-->
- [Changelog](#changelog)
  - [v1.1.1](#v111)
  - [v1.1.0](#v110)
<!--toc:end-->

All notable changes to this repository are documented in this file.

This project follows Semantic Versioning.

---

## v1.1.1

### Changed
- Frontend Code Quality workflow
  - Removed coverage artifact handling to simplify the workflow
  - Coverage generation and upload are now responsibility of consuming workflows

### java-ci
- No changes

---

## v1.1.0

### Added
- New reusable workflow: **Frontend Code Quality**
  - Tool-agnostic frontend CI workflow
  - Supports type checking, linting, formatting, and testing
  - Commands are fully configurable by consumers
  - Optional coverage artifact upload

### java-ci
- No changes
