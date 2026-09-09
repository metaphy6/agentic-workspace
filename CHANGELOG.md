# Changelog

## [Unreleased]

### Added

- Codex is included by default and selectable with `--agents codex`: native
  project configuration, four adapted agent roles, explicit prompt skills,
  shared instructions and CodeGraph MCP for local ChatGPT desktop / Codex use.
- Codex agent identity is accepted in completion tracking rows.

### Changed

- Repository and framework renamed from `ai-vscode-basics` to `agentic-workspace`.
  All URLs, cache paths, documentation, scripts and the version stamp file now
  use the new name.
- Scaffolding requires Python 3.9+ and includes complete skill resource trees.
- Framework-only installer files are excluded when copying, rather than deleted
  from the target after installation; existing project setup files survive.

### Fixed

- Dry-run no longer creates a missing target directory.
- Generated MCP JSON and TOML preserve paths containing quotes and backslashes.
