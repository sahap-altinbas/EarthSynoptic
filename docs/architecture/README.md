# EarthSynoptic Architecture

## Purpose

This directory is the canonical home for EarthSynoptic architecture documentation and Architecture Decision Records (ADRs).

Architecture documentation describes system boundaries, cross-cutting constraints, decision discipline, and the current state of architectural commitments. It must distinguish established repository facts from proposed or future design choices.

## Status

EarthSynoptic is currently in a foundation phase.

At this baseline:

- no application or source-code directory is established;
- no package or build manifest is established;
- no GitHub Actions workflow is established;
- no mapping or geospatial rendering engine is selected;
- no web or mobile application framework is selected;
- no backend runtime is selected;
- no database or persistence technology is selected;
- no event, queue, or streaming technology is selected;
- no cloud or deployment platform is selected.

References to technologies elsewhere in repository documentation do not constitute architectural adoption unless an accepted ADR explicitly records that decision.

## Architectural Principles

EarthSynoptic architecture must preserve the following principles as the system evolves.

### Evidence before commitment

Major technology and architecture choices must be based on documented requirements, authoritative technical evidence, reproducible evaluation where practical, and explicit trade-off analysis.

### Scientific provenance and uncertainty

Scientific observations, interpretations, derived products, and scenario outputs must retain source identity, provenance, revision context, uncertainty, limitations, and relevant model or methodology metadata.

### Explicit boundaries and contracts

System components should expose clear responsibilities and explicit interfaces. Data contracts, schemas, identifiers, versioning rules, and failure semantics should be defined before dependent implementation becomes entrenched.

### Reproducibility and auditability

Material scientific transformations and analytical workflows should be reproducible where practical. Architecture should support traceability from presented results back to source data, processing steps, versions, and assumptions.

### Security and least privilege

Security controls must be designed into system boundaries rather than added as an afterthought. Secrets must not be embedded in source. Access should follow least-privilege and capability-aware principles appropriate to each component.

### Reliability and observability

Operational components should expose sufficient telemetry to diagnose failures, data freshness problems, degraded dependencies, and processing anomalies without compromising sensitive information.

### Accessibility and cross-platform behavior

User-facing architecture must support accessible interaction and consistent behavior across the intended web and mobile platforms. Technology selection must account for accessibility requirements rather than treating them as post-implementation remediation.

### Licensing and attribution

Architecture that acquires, stores, transforms, caches, republishes, or combines external data must preserve provider-specific licensing, attribution, redistribution, and retention constraints.

## Architecture Decision Records

Significant architectural decisions must be recorded as ADRs before they become implementation assumptions.

An ADR is expected when a decision materially affects one or more of the following:

- system boundaries or service decomposition;
- mapping, rendering, or geospatial delivery architecture;
- client application frameworks or native-platform strategy;
- backend language, runtime, or application framework;
- persistence, indexing, or geospatial database strategy;
- event transport, queues, streaming, or asynchronous processing;
- scientific data formats, tiling, packaging, or distribution strategy;
- cloud, hosting, orchestration, or deployment architecture;
- authentication, authorization, trust boundaries, or secret management;
- observability, reliability, backup, disaster recovery, or retention;
- interoperability standards or public API contracts;
- decisions that materially affect security, privacy, accessibility, provenance, uncertainty, licensing, or attribution.

The planned ADR location is `docs/architecture/adr/`. Its index and individual ADRs will be established separately under controlled repository tasks.

## ADR Decision Discipline

Each future ADR should identify, at minimum:

- the decision title and status;
- the problem and decision context;
- requirements and constraints;
- considered alternatives;
- evidence and evaluation criteria;
- the selected decision, if one is made;
- consequences and accepted trade-offs;
- security, privacy, accessibility, scientific, provenance, licensing, and operational impacts where applicable;
- validation or review requirements;
- supersession relationships when a later ADR replaces an earlier decision.

An ADR must not present an unevaluated preference as a concluded fact.

## Non-Decisions at This Baseline

This architecture baseline does not select or authorize any specific mapping engine, frontend framework, mobile framework, backend runtime, database, event platform, cloud provider, container orchestrator, or deployment topology.

Names such as MapLibre, Cesium, React, Next.js, Flutter, React Native, SwiftUI, Jetpack Compose, PostgreSQL, PostGIS, Kafka, NATS, Redis, AWS, Azure, Google Cloud, or Kubernetes are not architectural commitments unless a future accepted ADR explicitly makes such a decision.

## Change Control

Architecture documentation must evolve through small, reviewable changes.

When implementation introduces a new architectural dependency or makes an existing non-decision concrete, the corresponding ADR should be created or updated before the repository treats that choice as canonical.

Architecture documentation must remain consistent with repository governance, security, contribution, data-source, data-license, and attribution policies.

## Current Baseline

The current architecture foundation establishes governance for future technical decisions only. It does not authorize application implementation, infrastructure provisioning, or technology adoption.
