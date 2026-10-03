# Contributing to EarthSynoptic

Thank you for your interest in contributing to EarthSynoptic.

EarthSynoptic is intended to become a global geoscience and Earth-systems intelligence platform with strong requirements for scientific integrity, provenance, uncertainty representation, security, accessibility, and reproducibility.

Contributions should therefore be technically sound, scientifically defensible where scientific claims are involved, appropriately scoped, and explicit about their assumptions and limitations.

## Project Status

EarthSynoptic is currently in the foundation and research stage.

The repository does not yet publish a production application, production API, supported production release, or operational hazard-warning service.

Architecture, data governance, security controls, development standards, scientific-source policies, and other project foundations are being established before broad application implementation begins.

Contributions that introduce major architectural commitments, application frameworks, infrastructure dependencies, mapping stacks, data platforms, or other long-lived technical decisions may require prior design review before implementation.

## Before Contributing

Before beginning substantial work:

- review the current repository documentation and open issues;
- verify that the proposed work is consistent with the current project stage;
- avoid duplicating work already in progress;
- identify significant scientific, architectural, security, licensing, or data-governance implications;
- and discuss large or potentially irreversible changes before implementation.

Small documentation corrections and similarly narrow changes generally do not require advance design discussion.

## Contribution Principles

Contributions should:

- be focused on a clearly defined problem or improvement;
- minimize unrelated changes;
- distinguish verified facts from assumptions, estimates, interpretations, and hypotheses;
- preserve scientific and technical provenance;
- avoid unsupported claims;
- document important limitations and uncertainty;
- avoid unnecessary dependencies or premature architectural commitments;
- respect security, privacy, licensing, and attribution requirements;
- and remain understandable and maintainable by future contributors.

A contribution should not present planned, experimental, simulated, or incomplete functionality as operational capability.

## Scientific and Geoscience Contributions

Scientific contributions require particular care because EarthSynoptic is intended to work with natural-hazard and Earth-system information.

Where applicable, contributions should identify:

- the authoritative source or scientific reference;
- dataset, model, or methodology name;
- publisher or responsible institution;
- relevant version or release;
- observation or publication date;
- spatial and temporal resolution;
- coordinate reference system or geospatial assumptions;
- transformations or derived processing;
- uncertainty or confidence information;
- known limitations;
- and provenance sufficient to reproduce or audit the result.

Authoritative first-party scientific and governmental sources should be preferred where available.

Peer-reviewed and authoritative academic material may supplement first-party sources when appropriate.

Secondary commercial summaries, general media, blogs, social media, and similar discovery sources should not be treated as canonical scientific evidence when more authoritative sources exist.

Scientific disagreement, competing models, and unresolved uncertainty should be represented explicitly rather than silently resolved.

## Hazard, Risk, and Simulation Claims

Contributions involving earthquakes, tsunamis, volcanoes, faults, geological hazards, structural consequences, scenario modelling, or similar safety-relevant subjects must avoid unsupported deterministic claims.

Where applicable, derived or simulated outputs should distinguish:

- observations from model outputs;
- deterministic calculations from probabilistic estimates;
- scenario assumptions from measured conditions;
- model resolution from real-world precision;
- and scientific uncertainty from missing data.

A model result must not be represented as certainty merely because it can be calculated or visualized.

Claims about a specific structure, location, population, or future event require evidence appropriate to the claim and must respect the scientific and legal limitations of the available data.

## Data Contributions

Do not add a dataset merely because it is publicly accessible.

Before proposing inclusion of external data, determine whether the project has the legal and technical right to use, transform, cache, redistribute, or display it.

Data-related contributions should document, where applicable:

- source;
- license or terms of use;
- attribution requirements;
- redistribution restrictions;
- access method;
- update frequency;
- versioning behavior;
- geographic coverage;
- temporal coverage;
- resolution;
- known quality limitations;
- provenance;
- and any restrictions relevant to derived products.

Third-party datasets retain their own licenses and terms. The EarthSynoptic software license does not automatically relicense external data.

Do not commit restricted, confidential, proprietary, personally sensitive, or unlawfully obtained data.

## Software and Architecture Contributions

EarthSynoptic favors explicit interfaces, modular design, typed contracts where appropriate, schema validation, reproducibility, observability, testing, and documented architectural reasoning.

Major technology selections should be supported by evidence rather than preference alone.

Changes that materially affect architecture, storage, geospatial processing, mapping, APIs, security boundaries, deployment, distributed processing, or other foundational concerns may require an Architecture Decision Record or equivalent design review before implementation.

Until a component-specific standard is established:

- follow the conventions already present in the relevant component;
- keep public interfaces deliberate and documented;
- avoid hidden global state where practical;
- validate external inputs;
- handle failure modes explicitly;
- and avoid introducing dependencies without a clear need.

Do not assume that a technology mentioned in planning or research documentation has already been adopted.

## Security

Do not disclose suspected vulnerabilities through public issues, pull requests, discussions, commits, or other public channels.

Follow the repository's [Security Policy](SECURITY.md) and use GitHub Private Vulnerability Reporting for security-sensitive reports.

Never commit:

- passwords;
- access tokens;
- API keys;
- private keys;
- authentication cookies;
- production credentials;
- confidential configuration;
- or other secrets.

Use synthetic or non-sensitive values in examples and tests.

Security-sensitive changes should identify relevant trust boundaries, threat assumptions, validation behavior, and potential failure modes.

## Accessibility

User-facing contributions should consider accessibility from the beginning rather than treating it as a later retrofit.

EarthSynoptic targets WCAG 2.2 Level AA where feasible and must also respect applicable native-platform accessibility requirements.

Changes affecting interaction, visualization, color, keyboard use, focus management, semantics, motion, data presentation, or assistive-technology behavior should describe relevant accessibility considerations.

## Issues

Issues should describe a concrete problem, proposal, research question, or task.

Where relevant, include:

- a concise summary;
- current behavior;
- expected behavior;
- reproduction steps;
- scientific or technical context;
- affected component;
- source or dataset references;
- screenshots or logs when useful;
- environment information;
- and known limitations or uncertainty.

Do not use public issues to report security vulnerabilities.

Avoid presenting speculation as a confirmed defect or scientific fact.

## Pull Requests

Keep pull requests focused and reviewable.

A pull request should explain:

- what changes;
- why the change is needed;
- the scope of the change;
- how it was validated;
- relevant tests or checks;
- scientific or data provenance where applicable;
- licensing or attribution implications where applicable;
- security implications where applicable;
- and any known limitations or follow-up work.

Unrelated refactoring, formatting, dependency upgrades, or feature work should normally be separated into independent changes.

External contributors should normally work on a dedicated branch and propose changes through a pull request.

Repository maintainers may use controlled workflows appropriate to the current project stage, subject to repository security rules.

## Commits and Repository Integrity

Commit messages should describe the purpose of the change clearly.

Commits intended to reach the protected default branch must satisfy the repository's applicable GitHub rules, including verified-signature requirements.

Do not rewrite shared history or attempt to bypass repository protections.

Force-push behavior, branch deletion, signed-commit requirements, and other protections are governed by the active repository ruleset.

## Testing and Validation

A contribution should include validation proportional to its risk and scope.

Where applicable, validation may include:

- automated tests;
- schema validation;
- static analysis;
- type checking;
- security checks;
- scientific cross-checks;
- reproducibility checks;
- geospatial validation;
- accessibility testing;
- performance measurements;
- and manual verification.

Do not describe a test as passing unless it was actually executed successfully in the stated environment.

If a required validation cannot currently be performed, state that limitation explicitly.

## Documentation

Documentation should describe the repository as it actually exists.

Avoid documenting planned functionality as though it were already implemented.

Technical and scientific documentation should make important assumptions, data sources, uncertainty, limitations, security implications, and version dependencies explicit where relevant.

Relative repository links are preferred when linking to files that live within this repository.

## AI-Assisted Contributions

AI-assisted tools may be used as part of a contributor's workflow, but they do not transfer responsibility away from the contributor.

The contributor remains responsible for verifying:

- technical correctness;
- scientific accuracy;
- provenance;
- licensing;
- security;
- attribution;
- generated references;
- tests;
- and the final submitted content.

Do not submit fabricated citations, invented APIs, nonexistent datasets, unsupported scientific claims, or unverified generated output.

## Licensing and Intellectual Property

EarthSynoptic software is licensed under the Apache License 2.0 unless explicitly stated otherwise.

By submitting a contribution, you must have the right to provide the submitted material under the applicable project terms.

Do not submit material copied from incompatible, proprietary, confidential, or otherwise unauthorized sources.

Third-party code, datasets, models, imagery, documentation, and other materials remain subject to their respective licenses and terms.

Any required attribution, notice, or redistribution condition must be identified before third-party material is incorporated.

## Review and Acceptance

Submission does not guarantee acceptance.

A contribution may require revision or may be declined because of scientific, technical, architectural, security, licensing, accessibility, maintainability, scope, or project-stage considerations.

Review decisions should be based on documented project requirements and the evidence relevant to the proposed change.

As EarthSynoptic matures, these contribution requirements will evolve alongside its architecture, release processes, development tooling, scientific governance, and operational responsibilities.
