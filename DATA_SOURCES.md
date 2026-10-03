# EarthSynoptic Data Sources

This document defines the institutional baseline for identifying, evaluating, recording, using, and maintaining scientific and geospatial data sources within EarthSynoptic.

It is intended to make source authority, provenance, uncertainty, transformation history, licensing constraints, and scientific limitations explicit and reviewable.

## Purpose

EarthSynoptic is intended to integrate scientific observations, historical records, geospatial products, derived datasets, and model outputs from multiple external and project-controlled sources.

A data source must not be treated as trustworthy merely because it is technically accessible, widely used, visually convincing, or convenient to integrate.

Source selection and continued use must be based on documented authority, scientific relevance, provenance, methodological suitability, licensing, technical characteristics, and known limitations.

This document governs source registration. It does not by itself grant permission to access, copy, cache, transform, redistribute, publish, or commercially reuse any external data.

## Current Registry Status

EarthSynoptic is presently in the foundation and research stage.

No external scientific dataset, external data service, monitoring feed, catalogue, map layer, imagery product, model product, or third-party data API is currently registered in this document as an active EarthSynoptic data source.

The absence of registered sources is intentional at this stage.

A provider, institution, dataset, service, or product must not be represented as an approved EarthSynoptic source until its identity, authority, provenance, licensing, scientific suitability, technical characteristics, and limitations have been reviewed and recorded.

## Source Authority Model

EarthSynoptic uses a source-authority hierarchy to guide evidence selection.

### Tier A — Authoritative Primary Sources

Tier A consists of first-party governmental, scientific, monitoring, geological, geodetic, meteorological, oceanographic, space, emergency-management, intergovernmental, or comparable authoritative institutions acting within their recognized area of responsibility.

Where an appropriate Tier A source exists and is scientifically suitable, it should normally take precedence over secondary republication or aggregation.

Tier A status does not remove the need to evaluate methodology, coverage, uncertainty, update status, licensing, technical accessibility, or fitness for the intended EarthSynoptic use.

### Tier B — Academic and Research Sources

Tier B consists of scientific material from universities, research institutes, scholarly collaborations, peer-reviewed publications, or academically maintained research datasets where the provenance and methodology are sufficiently documented.

Tier B material may provide primary research evidence, specialized datasets, validated models, historical reconstruction, or scientific interpretation not available from a Tier A source.

Academic status alone does not make a dataset globally authoritative or suitable for every use.

### Tier C — Supporting and Contextual Sources

Tier C consists of supporting material that may assist interpretation, implementation, cross-checking, documentation, or technical understanding but should not displace a stronger authoritative or primary scientific source where one exists.

Tier C evidence must be identified according to its actual role and evidentiary strength.

### Tier D — Discovery-Only Sources

Tier D includes commercial aggregators, general news reporting, blogs, unspecialized reference sites, social media, community discussion, crowd-sourced summaries, and similar discovery-oriented material.

Tier D material may be used to discover potentially relevant primary evidence.

Tier D material must not be treated as a canonical EarthSynoptic data source or canonical scientific evidence.

A fact or dataset discovered through Tier D material should be traced to an appropriate authoritative, scientific, or otherwise defensible source before canonical use.

## Source Qualification

Before a source is registered for EarthSynoptic use, the review should consider, where applicable:

- responsible institution or provider;
- institutional authority for the subject matter;
- scientific purpose of the dataset or product;
- observation, measurement, modelling, or derivation methodology;
- provenance and documentation quality;
- geographic coverage;
- temporal coverage;
- spatial and temporal resolution;
- coordinate reference system;
- update or acquisition cadence;
- versioning and revision practices;
- uncertainty and quality information;
- known gaps and limitations;
- access method;
- machine-readable formats or interfaces;
- operational stability;
- licensing and terms of use;
- attribution requirements;
- caching and redistribution restrictions;
- transformation constraints;
- privacy, security, or sensitivity considerations;
- and suitability for the intended EarthSynoptic scientific or technical use.

A source may be rejected even when technically accessible if its scientific, legal, provenance, quality, or operational characteristics are insufficient for the proposed use.

## Source Lifecycle Status

Future source records should carry an explicit lifecycle status rather than relying on implication.

Suitable registry states may include:

- **Candidate** — identified for evaluation but not approved for EarthSynoptic use;
- **Approved for research** — reviewed for a defined research or evaluation purpose;
- **Active** — approved for a defined current EarthSynoptic workflow;
- **Suspended** — temporarily unsuitable because of scientific, technical, licensing, security, availability, or integrity concerns;
- **Deprecated** — retained for historical traceability but no longer preferred for new use;
- **Retired** — no longer used except where necessary to reproduce historical results.

A lifecycle label must not imply greater scientific authority than the underlying source actually possesses.

## Required Source Record

A future registered source should document, where applicable:

- stable EarthSynoptic source identifier;
- source lifecycle status;
- source-authority tier;
- responsible provider or institution;
- official dataset, product, service, catalogue, or collection name;
- authoritative landing page or service endpoint;
- dataset or product identifier;
- scientific domain;
- observation, reported fact, derived product, model output, or other epistemic category;
- geographic coverage;
- temporal coverage;
- spatial resolution;
- temporal resolution;
- coordinate reference system;
- units;
- schema or format;
- acquisition or update cadence;
- retrieval date or timestamp;
- provider version, edition, revision, or release;
- immutable identifier or checksum where available and appropriate;
- methodology reference;
- quality-control information;
- uncertainty or confidence information;
- known limitations;
- license or terms-of-use identity;
- attribution requirements;
- access restrictions;
- redistribution or caching constraints;
- EarthSynoptic transformations;
- lineage to derived products;
- responsible EarthSynoptic component or workflow;
- review date;
- and relevant review notes.

Fields that are genuinely unavailable should be recorded as unavailable or not applicable rather than replaced with invented values.

## Scientific Provenance

Scientific provenance is a first-class requirement.

EarthSynoptic should preserve the relationship between a value or product and the evidence from which it originated.

Where applicable, provenance should identify:

- original provider;
- source product;
- retrieval context;
- source version or revision;
- observation or publication time;
- processing time;
- transformation history;
- software or model involved;
- parameters and assumptions;
- and downstream derived products.

Data copied through an intermediary should not lose the identity of the authoritative upstream source.

Provenance must not be rewritten merely to make a derived or aggregated product appear primary.

## Retrieval, Versioning, and Reproducibility

Data acquisition should be reproducible where technically and legally feasible.

A retrieval record should preserve enough information to determine what was obtained, from where, and under which version or temporal state.

Where providers expose mutable endpoints, EarthSynoptic should distinguish the retrieval time from the observation or event time.

Where immutable versions, release identifiers, checksums, snapshots, or provider revisions exist, they should be retained when appropriate.

Historical analyses should not silently substitute a newer dataset version when the original result depended on an earlier version.

## Transformations and Lineage

Raw provider data and EarthSynoptic-derived data are not interchangeable.

Transformations may include:

- reprojection;
- resampling;
- filtering;
- normalization;
- unit conversion;
- spatial joining;
- temporal alignment;
- aggregation;
- interpolation;
- classification;
- quality filtering;
- format conversion;
- statistical derivation;
- or model-based processing.

Material transformations should be documented sufficiently to permit scientific review and, where feasible, reproduction.

Derived products should retain lineage to the original source records.

A transformation must not erase or conceal relevant uncertainty, provenance, license constraints, or scientific limitations.

## Spatial, Temporal, and Semantic Metadata

Geoscience data can be misinterpreted when coordinate systems, units, timescales, datums, resolutions, or scientific meanings are implicit.

Source records should therefore preserve relevant metadata such as:

- coordinate reference system;
- horizontal datum;
- vertical datum where relevant;
- elevation or depth convention;
- units;
- time standard;
- event time;
- observation time;
- publication time;
- update time;
- retrieval time;
- spatial extent;
- temporal extent;
- spatial resolution;
- temporal resolution;
- measurement meaning;
- and applicable scientific definitions.

Semantically different quantities must not be combined merely because they share similar names or units.

## Uncertainty, Quality, and Limitations

EarthSynoptic must not present source data as more precise, complete, certain, current, or authoritative than the source evidence supports.

Where provided or scientifically derivable, relevant uncertainty, confidence, completeness, detection limits, error bounds, resolution limits, quality flags, and validation status should be preserved.

The absence of an uncertainty field does not imply zero uncertainty.

Missing observations must remain distinguishable from measured zero values.

Estimated, inferred, interpolated, modelled, and observed values must remain distinguishable where scientifically relevant.

Known data gaps and coverage limitations should be represented rather than silently filled with invented information.

## Licensing, Access, and Redistribution

Public accessibility does not imply unrestricted reuse.

Each external source remains subject to the rights, licenses, terms, policies, access restrictions, attribution requirements, redistribution conditions, caching rules, and other constraints established by its provider or applicable rights holder.

The EarthSynoptic software license does not relicense external datasets or services.

Source approval for scientific use does not automatically establish permission for redistribution.

Where license status or reuse rights are unclear, the data must not be represented as unrestricted.

Credentials, subscription access, contractual access, or technical access controls must not be interpreted as permission to redistribute underlying data.

## Attribution

Required source attribution must be preserved according to the applicable provider terms and scientific practice.

EarthSynoptic attribution must not imply endorsement, partnership, sponsorship, certification, or operational responsibility by an external provider unless such a relationship actually exists and is documented.

Attribution should remain traceable through transformed and derived products when required by license, provenance, or scientific integrity.

## Data Freshness and Availability

A source's current availability does not guarantee future availability.

Where freshness matters, EarthSynoptic should distinguish:

- observation time;
- provider publication or update time;
- EarthSynoptic retrieval time;
- processing time;
- and display or analysis time.

Data should not be described as real-time unless the actual acquisition and processing characteristics justify that term.

Delayed, stale, interrupted, incomplete, or temporarily unavailable data should not be silently represented as current.

EarthSynoptic does not currently guarantee continuous availability, ingestion latency, or freshness for any external data source.

## Conflicting or Overlapping Sources

Different credible sources may disagree because of methodology, revision state, spatial resolution, measurement technique, scientific interpretation, or institutional responsibility.

Conflicting values must not be silently merged merely to produce one apparently authoritative number.

Where material disagreement exists, EarthSynoptic should preserve the relevant source identities and determine whether one source has greater authority for the specific question.

Source-authority tier is an important consideration but is not a substitute for scientific analysis.

Resolution of a source conflict should be documented when it materially affects a scientific result or user interpretation.

## Derived Data and Model Outputs

Derived datasets, statistical products, scenarios, simulations, and model outputs must remain distinguishable from direct observations and provider-reported facts.

A model output does not become an observation merely because it is displayed on the same map or interface.

Derived products should identify relevant:

- source datasets;
- transformation or model;
- model version;
- parameters;
- assumptions;
- spatial and temporal resolution;
- uncertainty;
- validation status;
- and known limitations.

Probabilistic or scenario-based output must not be represented as a deterministic prediction unless the underlying scientific method genuinely supports that interpretation.

## Security and Sensitive Information

Data-source documentation must not expose credentials, access tokens, private keys, authentication cookies, confidential contractual information, or security-sensitive infrastructure details.

Restricted, personal, confidential, embargoed, export-controlled, protected, or otherwise sensitive information must not be committed to the repository merely for provenance convenience.

Where a source requires authenticated access, the registry may describe the access class without publishing secret authentication material.

## Registry Change Control

Adding a source to this document is a scientific and governance action, not merely a formatting change.

A proposed source addition should be reviewable against:

- authority;
- scientific relevance;
- provenance;
- quality;
- uncertainty;
- licensing;
- access conditions;
- technical fitness;
- security;
- privacy;
- interoperability;
- and maintainability.

Material changes to a registered source should update the applicable source record rather than silently replacing prior assumptions.

Where a source is deprecated, suspended, superseded, or retired, the historical record should remain traceable when necessary for reproducibility.

## Registered Sources

There are currently no registered source entries.

No provider, dataset, service, feed, catalogue, imagery product, model product, or external API should be inferred to be approved merely because it is mentioned elsewhere in planning, research, discussion, issues, or future architecture work.

Sources will be added only after source-specific review establishes sufficient evidence for their documented EarthSynoptic use.

## Relationship to Project Policies

This document should be read together with the repository's:

- [README](README.md);
- [Governance](GOVERNANCE.md);
- [Contributing Guidelines](CONTRIBUTING.md);
- [Security Policy](SECURITY.md);
- and [Code of Conduct](CODE_OF_CONDUCT.md).

The repository's Apache License applies to EarthSynoptic software as described in the project documentation and does not automatically apply to third-party scientific data.

More specific source licenses, provider terms, security requirements, and legal restrictions take precedence for the external material they govern.

## Current Limitations

EarthSynoptic does not currently operate a production data-ingestion platform, complete scientific source registry, global data catalogue, operational monitoring service, or guaranteed real-time data pipeline.

The source-governance model in this document establishes the baseline that future source-specific records must satisfy.

Its existence does not mean that planned data integrations have been implemented, scientifically validated, licensed for redistribution, or made operational.
