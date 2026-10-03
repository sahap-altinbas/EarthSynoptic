# Security Policy

EarthSynoptic treats security as a core engineering and governance requirement.

This policy defines how security vulnerabilities affecting the EarthSynoptic project should be reported and how security-related information should be handled during the project's current foundation and research phase.

## Project Security Status

EarthSynoptic is currently in the foundation and research stage.

No production application, production API, supported production release, or operational hazard-warning service is currently published by this repository.

Security reports are nevertheless accepted for repository content and project infrastructure where applicable, including source code, development tooling, dependency configuration, build and automation logic, GitHub Actions workflows, security-sensitive configuration, secret handling, data-ingestion components, APIs, and other software components as they are introduced.

## Supported Versions

EarthSynoptic has not yet published a production release.

| Target | Security status |
| --- | --- |
| `main` | Active development branch. Security reports are accepted for review. No production-support or compatibility guarantee is currently provided. |
| Tagged production releases | None published. |

This section will be updated when formal releases and supported-version lifecycles are established.

## Reporting a Vulnerability

Use GitHub Private Vulnerability Reporting for vulnerabilities that may affect EarthSynoptic.

From the EarthSynoptic repository on GitHub:

1. Open the **Security** area.
2. Open **Advisories**.
3. Select **Report a vulnerability**.
4. Submit the report privately through GitHub's vulnerability-reporting workflow.

Do **not** disclose an unremediated vulnerability through a public GitHub issue, discussion, pull request, commit message, social-media post, or other public channel.

If private vulnerability reporting is temporarily unavailable, avoid publishing vulnerability details publicly while an appropriate private reporting channel is being restored or documented.

## Information to Include

Where available and safe to provide, a vulnerability report should include:

- a concise summary of the issue;
- the affected component, path, configuration, or functionality;
- the relevant commit, branch, or release identifier;
- prerequisites or conditions required to reproduce the issue;
- clear reproduction steps;
- a minimal proof of concept where appropriate;
- the observed and expected behavior;
- the potential confidentiality, integrity, availability, scientific-integrity, or supply-chain impact;
- known mitigations or workarounds;
- and relevant technical references.

Do not include real credentials, authentication tokens, private keys, personal data, confidential third-party information, or unrelated sensitive material in a report.

Secrets used only to demonstrate an issue should be synthetic, revoked, or otherwise non-sensitive.

## Security Review and Coordination

Reports will be reviewed to determine whether the reported behavior is reproducible, security-relevant, and within the scope of EarthSynoptic.

Maintainers may request additional technical information before reaching a conclusion.

Where a vulnerability is confirmed, remediation and disclosure should be coordinated privately until an appropriate fix, mitigation, advisory, or other response is available.

Reporter attribution may be provided when appropriate and with the reporter's consent.

Because EarthSynoptic has not yet entered production operation, no formal security-response service-level agreement is currently published. Any future response or remediation targets will be documented explicitly rather than implied.

## Responsible Testing

Security research must be conducted in a manner that avoids harm.

Testing must not:

- degrade or disrupt availability;
- destroy, alter, or corrupt data;
- access information or accounts without authorization;
- use or expose real credentials or secrets;
- target users through social engineering;
- interfere with emergency, scientific, governmental, or public-safety systems;
- generate misleading scientific or hazard information;
- or target infrastructure operated by GitHub, scientific data providers, government agencies, cloud providers, or other third parties without their explicit authorization.

A vulnerability in an external service, dataset provider, library, platform, or other third-party system should normally be reported to the responsible organization through that organization's security process.

EarthSynoptic may separately assess whether such a third-party vulnerability creates a dependency, integration, or supply-chain risk for this project.

## Scientific and Operational Security

Because EarthSynoptic is intended to work with geoscience, natural-hazard, and Earth-system information, security includes more than conventional software vulnerabilities.

Security-relevant concerns may also include issues that could materially affect:

- scientific data provenance;
- dataset authenticity or integrity;
- model or transformation lineage;
- uncertainty representation;
- geospatial data integrity;
- unauthorized modification of hazard-related information;
- integrity of automated data-ingestion pipelines;
- or trust boundaries between authoritative sources and derived products.

A scientific disagreement, modelling limitation, incomplete dataset, or uncertainty in a scientific result is not automatically a software security vulnerability. Such matters should be handled through the appropriate scientific, data-quality, or project-governance process unless a security control or trust boundary is also affected.

## Third-Party Components and Services

EarthSynoptic may depend on third-party software, scientific datasets, APIs, mapping services, imagery, infrastructure, and other external resources.

A security issue originating solely in a third-party product or service remains subject to that provider's security policy and disclosure process.

Reports concerning the way EarthSynoptic integrates with, configures, validates, authenticates to, or otherwise depends on a third-party component may still be relevant to this project.

## Bug Bounty

EarthSynoptic does not currently operate a bug-bounty or vulnerability-reward program.

Submission of a vulnerability report does not imply eligibility for financial compensation or any other reward.

If a formal vulnerability-reward program is established in the future, its terms will be documented separately.

## Policy Evolution

This security policy will evolve as EarthSynoptic introduces production releases, public services, APIs, deployment infrastructure, supported-version lifecycles, and additional security controls.

Security requirements that are not yet applicable to the current foundation-stage repository will be documented when they become operationally relevant.
