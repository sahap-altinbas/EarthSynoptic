# EarthSynoptic Data Licenses

This document defines the institutional baseline for identifying, verifying, recording, reviewing, and preserving licensing and usage conditions associated with external scientific and geospatial data used by EarthSynoptic.

It complements [DATA_SOURCES.md](DATA_SOURCES.md), which governs scientific source authority, provenance, quality, uncertainty, and source registration.

This document is governance documentation and is not legal advice.

## Purpose

EarthSynoptic may depend on external datasets, services, feeds, catalogues, imagery, maps, model products, scientific publications, and other third-party materials.

Technical access to such material does not by itself establish permission to copy, cache, transform, redistribute, publish, sublicense, commercially exploit, or incorporate that material into derived products.

Each external source must therefore be evaluated according to its actual license, terms of use, access conditions, attribution requirements, and other applicable restrictions.

## Current Registry Status

EarthSynoptic is presently in the foundation and research stage.

There are currently no registered external data-license entries in this document.

No provider-specific license, permission, waiver, public-domain status, redistribution right, commercial-use right, caching permission, or derivative-use permission should be inferred for EarthSynoptic merely because a dataset, institution, API, service, map, publication, or product is discussed elsewhere.

Source-specific license records will be added only after the relevant evidence has been reviewed.

## Separation of Software and Data Licensing

EarthSynoptic software is licensed under the Apache License, Version 2.0, as documented in [LICENSE](LICENSE).

That software license applies to EarthSynoptic software within its applicable scope.

The EarthSynoptic software license does not automatically relicense external datasets, scientific products, maps, imagery, publications, APIs, services, fonts, icons, models, or other third-party material.

A file, dataset, service, or product does not become Apache-2.0 licensed merely because EarthSynoptic software can access, display, process, transform, or reference it.

Software licensing and external-data licensing must therefore remain explicitly separated.

## Source-Specific Licensing Principle

Licensing must be evaluated at the level of the actual source, dataset, product, service, release, collection, or other legally relevant material.

A provider may distribute different products under different terms.

A single product may also expose different rights depending on:

- version;
- access method;
- geographic region;
- user class;
- intended use;
- redistribution method;
- contractual relationship;
- account type;
- publication channel;
- or changes in provider policy.

A license conclusion for one product must not be generalized to unrelated products from the same institution without evidence.

## License and Terms Authority

A license record should rely on the strongest available first-party evidence.

Where applicable, relevant evidence may include:

- an official license file;
- provider terms of use;
- dataset-specific usage terms;
- official metadata;
- an official API policy;
- an official data policy;
- an official copyright or rights statement;
- a legally applicable waiver;
- an official public-domain statement;
- a contractual agreement;
- or another authoritative provider statement.

Secondary summaries may assist discovery but must not replace authoritative license evidence where first-party evidence exists.

A repository issue, planning note, discussion, blog post, search result, or informal statement must not be treated as definitive license authority without appropriate evidence.

## Required Data-License Record

A future registered data-license entry should document, where applicable:

- stable EarthSynoptic source identifier corresponding to DATA_SOURCES.md;
- provider or rights holder;
- dataset, product, service, collection, or resource name;
- provider version, edition, revision, or release where relevant;
- license or terms-of-use name;
- license identifier where a verified identifier exists;
- authoritative license or terms location;
- date the applicable terms were reviewed;
- scope of the reviewed material;
- copyright or rights statement where relevant;
- attribution requirement;
- notice-preservation requirement;
- redistribution status;
- caching status;
- local-storage status;
- transformation or derivative-use status;
- publication status;
- commercial-use status;
- sublicensing status where relevant;
- API-specific restrictions where relevant;
- access restrictions;
- authentication or subscription conditions;
- rate-limit or technical-use conditions where relevant;
- geographic or jurisdictional limitations where applicable;
- expiry or review conditions where applicable;
- unresolved ambiguities;
- and review notes.

Unknown or unresolved rights must be recorded as unknown or unresolved rather than converted into assumed permission.

## Permission Dimensions

A data-license record should distinguish separate permission dimensions rather than reducing all rights to a single permitted or prohibited flag.

Relevant dimensions may include:

- access;
- download;
- local storage;
- transient caching;
- persistent caching;
- transformation;
- creation of derived products;
- public display;
- publication;
- redistribution;
- bulk redistribution;
- machine-to-machine service;
- commercial use;
- sublicensing;
- archival retention;
- and use in trained or derived computational models where specifically relevant.

Permission in one dimension does not imply permission in another.

For example, permission to access or display a service does not automatically establish permission to redistribute its underlying data.

## Attribution Requirements

Attribution requirements must be preserved when required by the applicable license, provider terms, contractual conditions, or scientific practice.

A source record should identify:

- required attribution text where authoritative terms prescribe it;
- required provider name;
- required copyright statement;
- required license notice;
- required hyperlink or reference where applicable;
- placement requirements;
- persistence requirements for transformed or derived products;
- and any prohibition against implying endorsement.

EarthSynoptic attribution must not imply sponsorship, certification, partnership, operational responsibility, or endorsement unless such a relationship actually exists and is documented.

## Notice Preservation

Some third-party licenses or terms may require preservation or reproduction of notices, acknowledgements, copyright statements, or other legal text.

Such obligations must be recorded source by source.

EarthSynoptic must not create, alter, remove, or summarize a legally required notice in a manner that changes its required meaning.

If a verified third-party obligation later requires a repository-level or distribution-level NOTICE or third-party-notice artefact, that artefact should be created from the actual obligation rather than from a placeholder assumption.

The current repository baseline contains no registered data-license notice obligation.

## Redistribution

Redistribution rights must be verified independently from access rights.

Public availability, free access, anonymous download, or open network access does not by itself prove permission for redistribution.

A future license record should state whether redistribution is:

- permitted;
- permitted with conditions;
- prohibited;
- restricted to a defined form;
- restricted to a defined audience;
- dependent on attribution;
- dependent on share-alike or equivalent conditions;
- dependent on separate permission;
- or unresolved.

Where redistribution rights are unresolved, EarthSynoptic must not represent the material as freely redistributable.

## Caching and Local Storage

Caching and storage rights can differ from display or access rights.

A source-specific review should determine, where applicable, whether EarthSynoptic may:

- cache responses temporarily;
- store data persistently;
- maintain local mirrors;
- create offline packages;
- archive historical versions;
- retain data after provider updates;
- or redistribute cached copies.

Operational convenience must not override provider restrictions.

Where only transient access is authorized, EarthSynoptic must not silently convert that authorization into persistent storage.

## Transformations and Derived Products

Scientific transformation does not automatically remove underlying license obligations.

Relevant transformations may include:

- reprojection;
- resampling;
- filtering;
- aggregation;
- interpolation;
- classification;
- unit conversion;
- statistical derivation;
- format conversion;
- spatial or temporal joining;
- visual rendering;
- feature extraction;
- or model-based processing.

A source-specific license record should determine whether transformations and derived products are permitted and whether attribution, redistribution, share-alike, notice, or other obligations continue to apply.

A technically derived output must not automatically be treated as legally independent from its source material.

## Commercial Use

Commercial-use status must be recorded explicitly where it matters.

The absence of a fee does not prove permission for commercial use.

Likewise, an openly accessible dataset must not be described as commercially reusable unless the applicable rights or terms support that conclusion.

Where commercial use requires separate permission, subscription, attribution, contract, or another condition, that condition should be recorded.

## Public Domain and Open Data Claims

Terms such as public domain, open data, open access, free, unrestricted, or government data must not be applied without appropriate evidence.

Public-domain status may depend on jurisdiction, authorship, source, product type, or other legal facts.

An official public-domain statement should be preserved as evidence where relevant.

Even where copyright restrictions do not apply, attribution, scientific provenance, privacy, database rights, contract terms, access policies, trademarks, or other obligations may still require separate consideration.

EarthSynoptic must not infer public-domain status solely from the identity of a governmental or public institution.

## Open Licenses

Where an external dataset is distributed under a recognized open license, EarthSynoptic should record the exact verified license and the version where applicable.

Open licensing does not mean that all obligations disappear.

Applicable requirements may include:

- attribution;
- license notice preservation;
- indication of modifications;
- share-alike conditions;
- source-reference requirements;
- database-specific obligations;
- or other license-specific terms.

License compatibility must be considered when multiple sources are combined into a composite or derived product.

## Access Terms and Technical Conditions

Some external services impose conditions through API terms, service agreements, acceptable-use policies, access credentials, request limits, or technical controls.

Such conditions are distinct from copyright licensing and should be recorded when they materially affect EarthSynoptic use.

Possession of credentials does not establish a right to redistribute underlying data.

Circumventing access controls, contractual restrictions, or provider safeguards is not an acceptable method for obtaining data rights.

## Authentication and Secrets

Data-license documentation must not contain passwords, access tokens, API keys, private keys, authentication cookies, secret URLs, or other credentials.

Where authenticated access is relevant, the record may describe the access class without exposing secret material.

Contractual or confidential terms that cannot lawfully or appropriately be published must not be committed merely to make the public registry appear complete.

## Terms Changes and Versioning

Provider licenses and terms may change over time.

Where the applicable terms are mutable, EarthSynoptic should record the review date and, where possible, the applicable version, revision, archived evidence, or other reproducible identifier.

A later change in provider terms must not silently rewrite the licensing conditions that applied to an earlier historical workflow.

Material changes should trigger review of affected source records and downstream uses.

## License Ambiguity

When license status is unclear, conflicting, incomplete, inaccessible, or dependent on unresolved interpretation, the uncertainty must be recorded.

Uncertainty must not be converted into permission by default.

Suitable statuses may include:

- verified permitted;
- verified permitted with conditions;
- verified prohibited;
- separate permission required;
- license not identified;
- terms ambiguous;
- review incomplete;
- or legal review required.

A technically desirable dataset may remain unavailable for integration if its rights cannot be established sufficiently for the intended use.

## Conflicting Terms

A provider may expose multiple documents that appear to govern the same material.

Where license files, API terms, website terms, dataset metadata, contracts, or other documents conflict or appear to conflict, EarthSynoptic must not silently choose the most permissive interpretation.

The conflict should be documented and resolved through authoritative clarification or appropriate review before relying on the disputed permission.

## Composite and Multi-Source Products

A composite EarthSynoptic product may inherit constraints from multiple underlying sources.

The most permissive source does not automatically determine the rights for the entire composite.

Source-specific attribution, redistribution, derivative-use, notice, and share-alike requirements should remain traceable through the composite workflow.

Where source conditions are incompatible with the intended product, those sources should not be combined merely because the combination is technically possible.

## Derived Scientific and Model Outputs

Derived scientific outputs, statistical products, scenarios, simulations, rendered layers, and model products may involve multiple rights layers.

A derived result should identify relevant underlying source records and license records where necessary.

Scientific transformation alone must not be used to conceal, discard, or bypass applicable rights or attribution obligations.

Model outputs should be evaluated according to both their scientific provenance and any relevant rights associated with their inputs, software, model assets, or training material where applicable.

## Provider Identity and Endorsement

Use of external data must not imply that a provider endorses EarthSynoptic.

Provider names, institutional identities, logos, trademarks, seals, and branding may be governed separately from the underlying data license.

Permission to use data does not automatically grant permission to use provider branding.

EarthSynoptic documentation should distinguish factual attribution from endorsement.

## Registry Change Control

Adding or changing a data-license record is a governance action.

A proposed record should be supported by evidence sufficient to establish the rights and restrictions relevant to the intended use.

Material updates should identify:

- what changed;
- why the interpretation changed;
- which authoritative evidence supports the change;
- which EarthSynoptic sources or products are affected;
- and whether previously produced or distributed material requires review.

Historical records should remain traceable where necessary for reproducibility or compliance.

## Registered Data Licenses

There are currently no registered external data-license entries.

No source-specific permission is granted by this empty baseline.

Future records must correspond to reviewed sources in [DATA_SOURCES.md](DATA_SOURCES.md) and must be supported by source-specific licensing or terms evidence.

## Relationship to Project Policies

This document should be read together with:

- [DATA_SOURCES.md](DATA_SOURCES.md);
- [README](README.md);
- [Governance](GOVERNANCE.md);
- [Contributing Guidelines](CONTRIBUTING.md);
- [Security Policy](SECURITY.md);
- and [LICENSE](LICENSE).

DATA_SOURCES.md governs scientific source registration and provenance.

DATA_LICENSES.md governs the rights, restrictions, obligations, and review status associated with those sources.

Neither document overrides the authoritative terms established by an external provider or applicable rights holder.

## Current Limitations

EarthSynoptic does not currently maintain a complete external-data license registry, legal-rights database, production compliance engine, automated license-compatibility resolver, or automated terms-monitoring system.

The repository currently contains no registered external data-license entries.

The absence of an entry must not be interpreted as permission.

Source-specific rights must be established before EarthSynoptic represents external material as reusable, redistributable, transformable, cacheable, commercially usable, or otherwise licensed for a particular purpose.
