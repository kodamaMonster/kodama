# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-04-23

### Added
- Initial workspace layout: on-chain program, TypeScript SDK, REST API, Python agents, CLI.
- Anchor program skeleton under `programs/kodama` with placeholder program ID.
- TypeScript SDK with Anchor client bindings (`@kodama/sdk`).
- Express REST API with WebSocket event feed (`@kodama/api`).
- Python agent framework with strategy engine under `agents/`.
- CLI tool `kodama` for trainer management (`@kodama/cli`).
- Full build manifests: `Anchor.toml`, workspace `Cargo.toml`, per-crate manifests.
- Community files: Code of Conduct, Contributing guide, Security policy, Roadmap.
- CI workflow with format and structure checks.
- Dependabot config for npm, cargo, and GitHub Actions.

[0.1.0]: https://github.com/kodamacom/kodama/releases/tag/v0.1.0

## [Unreleased]
- perf: skip redundant battle simulator passes
- feat: api supports CORS preflight
- fix: evolve stat scaling off by one stage
- misc: docs: clarify license scope

