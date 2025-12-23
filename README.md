# Kubernetes (Documentation Stripped)

This is a modified version of [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes)
with all documentation files removed. It is used for benchmarking AI coding agents.

**Full git history is preserved** - you can use git blame, log, etc.

## What was removed

- All `doc.go` files
- All `README.md` files (replaced with this one)
- All `DESIGN.md`, `CONTRIBUTING.md` files
- Package-level documentation comments from `.go` files
- Contents of `docs/` and `examples/` directories

## Purpose

This repository is indexed in Sourcegraph for the CodeContextBench documentation
generation benchmark. By removing existing documentation, we can test whether
AI agents with access to Sourcegraph tools can generate accurate documentation
from code alone.

## Original Source

Based on kubernetes/kubernetes. Full git history is preserved.
See the original repository for the complete, documented codebase.

## License

Apache License 2.0 (same as original Kubernetes)
