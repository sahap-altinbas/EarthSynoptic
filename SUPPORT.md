# EarthSynoptic Support

This document explains the current support model for the EarthSynoptic project and directs different kinds of requests to the appropriate repository process.

EarthSynoptic is presently in the foundation and research stage. Support is therefore limited to the project capabilities, repository infrastructure, and maintainer availability that actually exist at this stage.

## Support Status

EarthSynoptic does not currently provide a supported production application, production API, operational hazard-warning service, commercial support program, help desk, telephone hotline, or guaranteed support service.

Repository support is provided on a best-effort basis.

There is currently no guaranteed response time, resolution time, service-level agreement, uptime commitment, compatibility commitment, or entitlement to individual support.

The absence of a response does not imply that a report, request, scientific claim, or proposed solution has been accepted or validated.

## Public Support Requests

For non-sensitive questions, reproducible problems, documentation concerns, or project-related requests, use the EarthSynoptic GitHub Issues system while that feature is enabled for the repository.

Before opening an issue:

- review the repository documentation;
- search existing issues where practical;
- determine whether the matter is actually related to EarthSynoptic;
- avoid including credentials, private information, confidential material, or sensitive vulnerability details;
- and provide enough context for another person to understand and reproduce the matter.

A public issue is not an appropriate channel for sensitive security reports or confidential conduct concerns.

## Appropriate Support Topics

Appropriate public support topics may include:

- clarification of repository documentation;
- reproducible repository defects;
- build, validation, or test problems once the relevant tooling exists;
- questions about documented configuration or project behavior;
- data-source or provenance questions relating to material used by EarthSynoptic;
- accessibility defects;
- interoperability concerns;
- licensing or attribution questions about EarthSynoptic-controlled material;
- feature proposals;
- scientific or technical clarification requests;
- and reports of inconsistencies between documented behavior and actual project behavior.

A support request may be redirected to another project policy or closed if it belongs in a different process.

## Bug Reports

A useful bug report should include, where applicable:

- a concise description of the problem;
- the EarthSynoptic version, commit, release, or branch involved;
- the operating system and relevant environment information;
- exact reproduction steps;
- expected behavior;
- actual behavior;
- relevant logs or error messages;
- screenshots or minimal examples where useful;
- whether the problem is consistently reproducible;
- and any known workaround.

Do not include secrets, access tokens, credentials, private keys, sensitive personal data, or confidential third-party information in a public bug report.

## Scientific and Data Questions

Scientific and data questions should identify the relevant evidence as precisely as practical.

Where applicable, include:

- the dataset, catalogue, model, or source involved;
- provider or authoritative institution;
- version or release;
- observation, publication, or retrieval date;
- geographic area;
- time period;
- coordinate reference system;
- spatial or temporal resolution;
- transformation or processing step;
- expected interpretation;
- observed discrepancy;
- and any known uncertainty or limitation.

EarthSynoptic support does not convert an unsupported scientific claim into an accepted scientific conclusion.

Questions involving scientific disagreement may require evidence review rather than a simple support response.

## Feature Requests

Feature requests are welcome as proposals, but submission does not imply acceptance, priority, scheduling, or implementation.

A useful feature request should explain:

- the problem to be solved;
- the intended user or workflow;
- why existing project behavior is insufficient;
- scientific or technical constraints;
- data or licensing implications;
- security and privacy implications where relevant;
- accessibility considerations;
- interoperability requirements;
- and possible alternatives.

Major architectural or scientific proposals may require deeper review under the project's [Governance](GOVERNANCE.md) and [Contributing Guidelines](CONTRIBUTING.md).

## Security Vulnerabilities

Do not report security vulnerabilities through a public support issue when doing so could expose sensitive security information.

Security vulnerabilities must be reported through the process defined in the repository's [Security Policy](SECURITY.md).

Security reports may be handled separately from ordinary support requests because responsible disclosure can require confidentiality.

## Conduct and Community Concerns

Harassment, threats, retaliation, privacy concerns, or other Code of Conduct matters should follow the process defined in the repository's [Code of Conduct](CODE_OF_CONDUCT.md).

Do not publish sensitive conduct-report details in a public support issue merely to obtain attention or escalation.

## Contribution Questions

Questions about contributing code, documentation, research, data, tests, designs, or other material should first consult the repository's [Contributing Guidelines](CONTRIBUTING.md).

Contribution review and user support are related but distinct processes.

A request for support does not create an entitlement to have a proposed contribution accepted.

## Natural-Hazard and Emergency Limitations

EarthSynoptic is not currently an emergency notification service, emergency response authority, operational forecasting authority, or official public-warning system.

Do not rely on this repository, its issues, its maintainer, future software components, model outputs, simulations, visualizations, or community discussions for immediate life-safety decisions.

For an active earthquake, tsunami, volcanic event, wildfire, flood, severe weather event, landslide, or other emergency, follow instructions and warnings issued by the competent official authorities for the affected jurisdiction.

A GitHub support request is not monitored as an emergency communications channel.

## Prediction and Simulation Limitations

EarthSynoptic support cannot provide guarantees that a future natural event will or will not occur at a particular place or time.

Scenario models, probabilistic assessments, simulations, historical patterns, and derived indicators must not be represented as deterministic predictions unless the underlying scientific methodology genuinely supports such a claim.

Support discussions should preserve relevant uncertainty, assumptions, limitations, model provenance, and validation status.

## Legal, Regulatory, and Professional Advice

Project support does not constitute legal, regulatory, engineering, medical, financial, emergency-management, insurance, investment, or other professional advice.

Questions about legal rights, regulatory obligations, emergency procedures, professional certification, or legally binding data-license interpretation may require advice from an appropriately qualified professional or competent authority.

Repository statements should not be treated as a substitute for such advice.

## Third-Party Services and Data

EarthSynoptic may reference, ingest, transform, visualize, or interoperate with external datasets, services, standards, libraries, or software.

The project cannot guarantee support for a third-party service, data provider, external API, network, device, library, operating system, or infrastructure that it does not control.

Where an issue originates entirely in a third-party product or service, the requester may need to contact the responsible provider.

EarthSynoptic support does not override third-party license terms, service conditions, access restrictions, or attribution requirements.

## Privacy and Sensitive Information

Public GitHub issues should be treated as public communications.

Do not post:

- passwords;
- access tokens;
- private keys;
- authentication cookies;
- non-public infrastructure details that create unnecessary security risk;
- confidential datasets;
- restricted information;
- unnecessary personal data;
- private correspondence;
- or other information that you are not authorized to disclose.

If sensitive information is accidentally published, removing it from a visible comment may not remove it from every historical, cached, mirrored, or notification copy.

Take appropriate credential-revocation or incident-response action where exposure has occurred.

## Response and Triage

Support requests may be reviewed for relevance, completeness, duplication, reproducibility, security sensitivity, scientific significance, and project scope.

A maintainer may:

- ask for additional information;
- request a minimal reproduction;
- redirect a request to another policy or repository process;
- identify a duplicate;
- apply an appropriate issue classification;
- defer a request;
- close a request that cannot be reproduced;
- close a request that is outside project scope;
- or decline work that the project cannot responsibly undertake.

Closure does not necessarily mean that the underlying concern is invalid. It may instead reflect scope, insufficient evidence, duplication, inability to reproduce, project maturity, or resource limitations.

## Support Priority

EarthSynoptic does not currently publish a formal support-priority matrix or guaranteed severity-response schedule.

In general, issues involving repository security, scientific integrity, data provenance, major correctness defects, accessibility barriers, or material project-integrity risks may warrant greater attention than cosmetic or speculative requests.

This is a triage principle, not a service-level commitment.

## Supported Versions

EarthSynoptic does not currently publish a stable supported release series.

Until formal releases and version-support policies are established, support should be understood in relation to the specific commit, branch, artefact, dataset version, or development state identified in the request.

Historical states may no longer reflect current project behavior.

## No Private General-Support Channel

EarthSynoptic does not currently publish a dedicated private general-support email address, ticketing system, customer portal, telephone service, or commercial support channel.

Do not infer the existence of a private support service from contributor, security, or conduct-reporting mechanisms.

Private channels documented for security or conduct matters must be used only for their intended purpose.

## No Guaranteed Individual Assistance

The project cannot guarantee personalized troubleshooting, implementation consulting, scientific analysis, data interpretation, deployment assistance, integration work, or one-to-one training.

Public documentation and reproducible issue records should be preferred where they can serve the broader project community without exposing sensitive information.

## Project Maturity

The support model will evolve as EarthSynoptic develops.

Future releases may require explicit policies for:

- supported versions;
- release lifecycles;
- deprecation;
- compatibility;
- migration;
- production incidents;
- service availability;
- operational monitoring;
- data freshness;
- API stability;
- or other support obligations.

Those mechanisms are not part of the current support model until they are actually established and documented.

## Related Project Policies

Support requests should be read together with the repository's:

- [README](README.md);
- [Contributing Guidelines](CONTRIBUTING.md);
- [Security Policy](SECURITY.md);
- [Code of Conduct](CODE_OF_CONDUCT.md);
- and [Governance](GOVERNANCE.md).

Where a more specific project policy applies, that policy takes precedence for the matter it governs.
