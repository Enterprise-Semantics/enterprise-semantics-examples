# Changelog

All notable changes to this repository are documented in this file. Dates use
the committer's local time.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) semantics.
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned

- VS-D2 ;;; tests + PlantUML visuals (CR-ES-003 §28-§31).
- Additional foundational examples ;;; canonical enterprise model, agentic vs autonomous comparative scenario, closed loop feedback.

## [0.1.0] ; 2026-09-23 ; VS-D1b Value Stream example tranche

### Added

- `examples/foundational/value-stream-order-to-cash.yaml` ;;; worked Order-to-Cash Value Stream example for OTCHERE Inc per CR-ES-003 §18 + ADR-ES-003 §22. 5 Value Stages (Capture Demand, Confirm Order, Fulfil Order, Deliver Offering, Realize Payment). ILLUSTRATIVE ;;; not a canonical catalog entry.
- `examples/foundational/value-stream-pay-to-fulfillment.yaml` ;;; worked Pay-to-Fulfillment Value Stream example per CR-ES-003 §20 + ADR-ES-003 §22. 6 Value Stages (Establish Payment, Confirm Transaction, Authorize Fulfillment, Prepare Fulfillment, Fulfill Demand, Confirm Realization). Demonstrates Value Stream semantic independence from process taxonomy.
- `examples/foundational/value-stream-process-boundary.yaml` ;;; comparative execution example per CR-ES-003 §32 + ADR-ES-003 §8 + §16. Same Value Stream (Order-to-Cash) realised through three different execution models (human-led, automated, agentic) without changing the Value Stream identity.

### Scope

This release implements VS-D1b of CR-ES-003 ;;; the worked example tranche for Value Stream. The 3 examples illustrate the foundational definition (Order-to-Cash), the process-taxonomy independence (Pay-to-Fulfillment), and the critical Value Stream vs Process boundary (comparative execution). No concept YAML mutation, no schema mutation, no validation rule addition. Per CR-ES-003 §32 ;;; the examples use OTCHERE Inc as the enterprise context ;;; no ACME is introduced.

### Governance

- ADR-ES-003 (Proposed, governance slot 0005) ;;; ratifies the foundational Value Stream decision ;;; §22 is the example anchor.
- CR-ES-003 (Proposed, governance slot 0011) ;;; carries §18 + §20 + §32 example requirements.
- FND-ES-AG-008 (Established 2026-09-22) ;;; establishes the WSF grounding classification referenced throughout.

### Cardinal rules applied

- Author: Emmanuel A. Otchere (cardinal author rule, 2026-09-23) ;;; present in all 3 new example files.
- No en-dash (U+2013) or em-dash (U+2014) in any new file (D-004 dash rule). Section dividers use `;;;` boundary lines per existing convention.
- No vendor-specific material from embargoed sources in any new file (cardinal embargo, 2026-09-22).
- ES is sourced from SDO-neutral standardisation only (ISO/IEC, ITU-T, ETSI, NIST).
- OTCHERE Inc used as enterprise example per CR-ES-003 §32 ;;; no ACME introduced.

### Held non-actions

- No tests or PlantUML visuals (held for VS-D2).
- No ADR-ES-003 promotion to Accepted (gated on CR-ES-003 implementation completion).
- No release tag (per v3.1.4 user directive).

## [0.0.1] ; 2026-09-02 ; Skeleton

### Added

- README.md (purpose, ownership, status, relationship to other repos).
- CODEOWNERS (sole owner: @emmanuel-a-otchere).
- CHANGELOG.md (this file).
- .gitignore (credential, AI-model, and workspace-noise patterns).
- LICENSE (Apache-2.0).

