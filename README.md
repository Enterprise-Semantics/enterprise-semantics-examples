# enterprise-semantics-examples

> Enterprise-Semantics reference applications: canonical enterprise model, Agentic Value Stream worked example, Agentic vs Autonomous comparative scenario.

This repository holds **worked examples** that double as **provenance evidence** for the seed in [`enterprise-semantics`](https://github.com/Enterprise-Semantics/enterprise-semantics). Every example here must validate against the conformance harness in [`enterprise-semantics-test-probe`](https://github.com/Enterprise-Semantics/enterprise-semantics-test-probe).

## Status

**First + second + third example tranches (v0.1.0 Value Stream + v0.2.0 Agentic + v0.3.0 Agentic Value Stream).** Value Stream examples landed via VS-D1b on 2026-09-23 (3 example YAMLs in examples/foundational/: value-stream-order-to-cash.yaml, value-stream-pay-to-fulfillment.yaml, value-stream-process-boundary.yaml).

## Planned examples

- `canonical-enterprise-model/` ;;; a minimal but complete enterprise model exercising Capability, Value Stream, Process, Workflow, AI Agent, Agentic Workflow, Closed Loop.
- `agentic-value-stream-worked/` ;;; the Agentic Value Stream concept from FND-ES-000 section 15 worked end-to-end.
- `agentic-vs-autonomous/` ;;; a comparative scenario that distinguishes Agentic from Autonomous, per FND-ES-001 section 9.
- `closed-loop-feedback/` ;;; Closed Loop, Feedback, FeedForward, Signal, Observation, Decision, Control, Adaptation exercised in a small example.

## Relationship to other repositories

| Repository | Relationship |
|------------|--------------|
| [`enterprise-semantics`](https://github.com/Enterprise-Semantics/enterprise-semantics) | Source: examples reference concept IDs from this repository. |
| [`enterprise-semantics-test-probe`](https://github.com/Enterprise-Semantics/enterprise-semantics-test-probe) | Conformance: examples must validate. |

## License

Apache License 2.0. See [LICENSE](https://github.com/Enterprise-Semantics/enterprise-semantics-examples/blob/main/LICENSE).
