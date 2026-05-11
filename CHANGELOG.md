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
- chore: tighten clippy rules in program crate
- feat: agent runner exposes hook callbacks
- misc: chore(api): version bump
- fix: event ordering under burst load
- fix: agent name validator off-by-one
- fix: handle null pointer in client.batch()
- fix: catch rate clamp on legendary spawns
- fix: trade signer verification
- feat: structured logger json mode
- perf: precompute matchup weights
- misc: chore: add keywords to package.json
- fix: race condition in event bus
- fix: gym badge double-mint guard
- perf: cache pda derivation
- misc: chore(cli): version bump
- doc: add architecture sequence diagram
- misc: chore(sdk): version bump
- feat: cli help text formatting
- doc: clarify gym challenge mechanics
- fix: typo in monster description
- feat: api graceful shutdown
- feat: optional logger color output
- chore: pin actions/checkout to v4
- feat: backup service emits metrics
- perf: faster type effectiveness lookup
- perf: lazy load monster-data table
- doc: deployment table on README
- chore: align dependencies across workspace
- fix: rate limiter window calculation
- chore: switch to dtolnay/rust-toolchain
- perf: skip redundant battle simulator passes
- feat: api supports CORS preflight
- fix: evolve stat scaling off by one stage
- misc: docs: clarify license scope

