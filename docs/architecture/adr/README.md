# EarthSynoptic Architecture Decision Records

## Purpose

This directory is the canonical index for EarthSynoptic Architecture Decision Records (ADRs).

ADRs document significant architectural decisions, the evidence considered, the alternatives evaluated, the resulting consequences, and any later supersession. They complement `docs/architecture/README.md`, which defines the architecture foundation and decision discipline.

## Current Status

No architectural decision has been accepted at this baseline.

The absence of an ADR means that a technology, platform, framework, service, data format, deployment model, or other implementation choice must not be treated as an approved architectural commitment.

## When an ADR Is Required

Create an ADR before a significant decision becomes an implementation assumption.

An ADR is generally required for decisions that materially affect:

- system boundaries or service decomposition;
- mapping, rendering, geospatial delivery, or spatial-computing architecture;
- web, iOS, Android, cross-platform, or native-client strategy;
- backend language, runtime, or application framework;
- persistence, indexing, search, or geospatial database strategy;
- queues, event transport, streaming, or asynchronous processing;
- scientific data formats, schemas, tiling, packaging, or distribution;
- public APIs, interoperability standards, identifiers, or versioning;
- cloud, hosting, orchestration, deployment, or infrastructure topology;
- authentication, authorization, trust boundaries, secrets, or key management;
- observability, reliability, backup, disaster recovery, retention, or data lifecycle;
- choices with material security, privacy, accessibility, provenance, uncertainty, licensing, attribution, or scientific-integrity consequences.

Routine implementation details that do not create durable architectural constraints do not require an ADR.

## ADR Lifecycle

EarthSynoptic uses the following ADR states:

- `Proposed` — under evaluation; not an approved implementation commitment.
- `Accepted` — approved and canonical unless later superseded or explicitly deprecated.
- `Rejected` — evaluated but not selected; retained for decision history.
- `Superseded` — replaced by a later ADR; the replacement ADR must be identified.
- `Deprecated` — retained for historical traceability but no longer recommended for new implementation.

An ADR must not be marked `Accepted` until its evidence, alternatives, impacts, and decision rationale have been reviewed.

## File Naming

ADR files use a four-digit monotonically increasing identifier followed by a concise lowercase kebab-case title:

`NNNN-short-decision-title.md`

Examples:

- `0001-mapping-rendering-engine.md`
- `0002-primary-geospatial-database.md`

Identifiers must not be reused, even when an ADR is rejected, deprecated, or superseded.

The numeric identifier records decision chronology. It does not imply priority.

## Required ADR Content

Each ADR should contain, at minimum:

1. **Title and identifier**
2. **Status**
3. **Date**
4. **Decision owners or reviewers**
5. **Context and problem statement**
6. **Requirements and constraints**
7. **Decision drivers**
8. **Alternatives considered**
9. **Evidence and evaluation**
10. **Decision**
11. **Consequences and trade-offs**
12. **Security and privacy impact**, when applicable
13. **Accessibility impact**, when applicable
14. **Scientific, provenance, and uncertainty impact**, when applicable
15. **Licensing and attribution impact**, when applicable
16. **Operational, reliability, and observability impact**, when applicable
17. **Validation or review requirements**
18. **Supersession relationships**, when applicable
19. **References**

Sections that are not applicable should state that explicitly rather than being silently omitted when their absence could create ambiguity.

## Evidence Standard

ADR evidence should prefer authoritative primary technical documentation, standards, specifications, reproducible measurements, and direct project requirements.

Comparative evaluation should distinguish:

- verified facts;
- measured project-specific results;
- strong engineering inference;
- unresolved uncertainty;
- assumptions requiring later validation.

Marketing claims, community popularity, or familiarity alone are insufficient grounds for an architectural decision.

## Alternatives and Trade-offs

An ADR must record credible alternatives where alternatives exist.

The selected option should not be presented as universally superior. The ADR should state why it best satisfies the documented EarthSynoptic requirements under the known constraints and should identify material disadvantages that are accepted with the decision.

## Reversibility

Where practical, ADRs should identify the cost and feasibility of reversal or migration.

High-cost or difficult-to-reverse decisions require stronger evidence and validation before acceptance.

## Supersession

Accepted ADRs are immutable historical decision records except for minor non-semantic corrections.

When a material decision changes, create a new ADR and mark the earlier ADR `Superseded`. Both records must identify the relationship.

Do not rewrite historical rationale to make an earlier decision appear consistent with later knowledge.

## Implementation Relationship

Implementation must not silently outrun architectural governance.

If implementation would make a documented non-decision concrete, introduce a durable architectural dependency, or contradict an accepted ADR, the relevant ADR must be proposed or updated first.

An accepted ADR authorizes the recorded architectural decision only. It does not automatically approve unrelated implementation choices.

## Repository Consistency

ADRs must remain consistent with the repository's governance, security, contribution, data-source, data-license, attribution, and architecture-foundation policies.

When these policies impose stricter requirements than an ADR, the stricter repository policy governs until the conflict is explicitly resolved.

## ADR Index

No ADRs have been created yet.

| ID | Decision | Status | Date | Supersedes |
| --- | --- | --- | --- | --- |
| — | No ADRs at current baseline | — | — | — |

## Baseline Rule

Until an ADR is accepted, EarthSynoptic must preserve architectural optionality and must not represent candidate technologies as selected architecture.
