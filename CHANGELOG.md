# Changelog

All notable changes to this repository are documented in this file. Dates use
the committer's local time.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) semantics.
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned

- VS-D2 ;;; tests + PlantUML visuals (CR-ES-003 §28-§31).
- Additional foundational examples ;;; canonical enterprise model, agentic vs autonomous comparative scenario, closed loop feedback.

## [0.7.0] ; 2026-09-23 ; VS-D1b ;;; 1 OTCHERE Inc Fulfillment Autonomous Operations worked example per CR-ES-008 §23 + ADR-ES-008 §20

### Added

- examples/foundational/operations/otchere-autonomous-operations.yaml ;;; new ;; 10 autonomous operational loop steps ;; 7 escalation boundaries ;; 9 boundaries ;; 10 cardinal relationships

### Cardinal rules

- Author: Emmanuel A. Otchere
- D-004 clean ;;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc preserved (no ACME placeholder)
- Technology-neutral per ADR-ES-008 §18 + CR-ES-008 §3

## [0.8.0] ; 2026-09-23 ; VS-D1b ;;; 1 OTCHERE Inc Order-to-Cash Autonomous Value Stream worked example per CR-ES-009 §24 + ADR-ES-009 §23

### Added

- examples/foundational/value-streams/order-to-cash-autonomous.yaml ;;; new ;; 7 value stages with distributed autonomy ;; 8 escalation boundaries ;; 11 boundaries ;; 12 cardinal relationships

### Cardinal rules

- Author: Emmanuel A. Otchere
- D-004 clean ;;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc preserved (no ACME placeholder)
- Technology-neutral per ADR-ES-009 §16 + CR-ES-009 §3

## [0.6.0] ; 2026-09-23 ; VS-D1b ;;; 1 OTCHERE Inc Fulfillment Operations (Agentic Operations) worked example per CR-ES-007 §21 + ADR-ES-007 §25

### Added

- examples/foundational/operations/otchere-agentic-operations.yaml ;;; new ;; 10 operational loop steps ;; 5 operational context elements ;; 4 participating workflows ;; 8 boundaries ;; 9 cardinal relationships

### Cardinal rules

- Author: Emmanuel A. Otchere
- D-004 clean ;;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc preserved (no ACME placeholder)
- Technology-neutral per ADR-ES-007 §14 + CR-ES-007 §3

## [0.5.0] ; 2026-09-23 ; VS-D1b ;;; 2 OTCHERE Inc Order Fulfillment worked examples (Workflow + Agentic Workflow) per CR-ES-006 §27 + ADR-ES-006 §21

### Added

- examples/foundational/workflows/order-fulfillment-workflow.yaml ;;; new ;; 6 conventional steps
- examples/foundational/workflows/order-fulfillment-agentic-workflow.yaml ;;; new ;; 10 agentic steps ;; 8 characteristics ;; 14 boundaries ;; 8 cardinal relationships

### Cardinal rules

- Author: Emmanuel A. Otchere on both files
- D-004 clean ;;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc preserved (no ACME placeholder)
- Technology-neutral per ADR-ES-006 §14 + CR-ES-006 §3

## [0.4.0] ; 2026-09-23 ; VS-D1b ;; 1 OTCHERE Inc Pay-to-Fulfillment worked example per CR-ES-005 §20 + ADR-ES-005 §15

### Added

- examples/foundational/value-stream-pay-to-fulfillment.yaml ;;; new ;; 9 flow steps ;; 5 agentic scope entries ;; 10 boundaries demonstrated ;; illustrates agentic participation distributed across financial AND operational stages ;; technology-neutral ;; no AI vendor ;; no specific framework ;; no LLM

### Cardinal rules

- Author: Emmanuel A. Otchere on the example file
- D-004 clean ;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc naming preserved (no ACME placeholder)
- Technology-neutral per ADR-ES-005 §11 + CR-ES-005 §3

## [0.3.0] ; 2026-09-23 ; VS-D1b ;; 1 OTCHERE Inc Agentic Value Stream worked example (Order-to-Cash) per CR-ES-005 §19 + ADR-ES-005 §15

### Added

- examples/foundational/value-stream-order-to-cash-agentic.yaml ;;; new ;; 11 flow steps ;; 4 agentic scope entries ;; 10 cardinal relationships used ;; demonstrates all 8 Agentic Value Stream characteristics (delegated intent ;; contextual interpretation ;; dynamic action selection ;; agentic coordination ;; adaptive progression ;; bounded authority ;; intervention ;; outcome orientation) ;; 7 boundaries demonstrated (human-in-the-loop ;; bounded authority ;; outcome orientation ;; Agentic != AI ;; Agentic != Automation ;; Agentic != Autonomous ;; mixed realization ;; specialised of Value Stream)

### Cardinal rules

- Author: Emmanuel A. Otchere on the example file
- D-004 clean ;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc naming preserved (no ACME placeholder)

## [0.2.0] ; 2026-09-23 ; CR-ES-004 VS-D1b Agentic worked example

### Added

- examples/foundational/agent-customer-service.yaml ;;; OTCHERE Inc Customer Service Agent ;;; 7 flow steps ;;; demonstrates all 6 Agentic characteristics ;;; 8 of 11 CR-ES-004 §10 predicates used ;;; human escalation preserved per ADR-ES-004 §16

### Cardinal rules

- Author: Emmanuel A. Otchere on the example file
- D-004 clean ;;; 0 forbidden glyphs
- No vendor-specific material from embargoed sources
- OTCHERE Inc naming preserved (no ACME placeholder)

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

