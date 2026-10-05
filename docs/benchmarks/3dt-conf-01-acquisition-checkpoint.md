# 3DT-CONF-01 Acquisition Evidence Checkpoint

## Project

- Project: EarthSynoptic
- Subtitle: Global Geoscience & Earth Systems Intelligence Platform
- Repository: https://github.com/sahap-altinbas/EarthSynoptic
- Checkpoint identifier: `3DT-CONF-01-ACQUISITION-CHECKPOINT`
- Milestone state: `PARTIAL_COMPLETE_BLOCKED_BY_LICENSE`

This document is a repository-level evidence checkpoint for the 3DT-CONF-01 benchmark acquisition milestone.

It records the audited state established by GÖREV-175B. It does not replace the external acquisition evidence and does not move benchmark evidence into the Git repository.

## Pinned upstream source

- Source repository: `CesiumGS/3d-tiles-samples`
- Pinned commit: `a30bfdf2d6cc55f4c3078e8aea3a793af6ebfd56`
- Pinned tree: `bb2ca785d55692e1f74bf83a3adcd48c7b0d4714`

## Selected sample state

| Sample | State |
| --- | --- |
| MetadataGranularities | `ACCEPTED` |
| SparseImplicitOctree | `ACCEPTED` |
| MultipleContents | `ACCEPTED` |
| TilesetWithFullMetadata | `BLOCKED_LICENSE_UNRESOLVED` |
| PropertyAttributesPointCloud | `ACCEPTED` |

Summary:

- Selected samples: 5
- Accepted samples: 4
- Blocked samples: 1
- Remaining selected samples: 1
- Acquisition-eligible remaining samples: 0
- Conformance family complete: false
- Further acquisition authorized: false
- License resolution required: true

### TilesetWithFullMetadata license block

`TilesetWithFullMetadata` remains blocked because explicit license evidence has not been established for that sample.

Canonical block reason:

`UNRESOLVED_NO_EXPLICIT_LICENSE_EVIDENCE`

License status must not be inferred from neighboring samples.

The fact that adjacent or related samples may carry CC0 licensing does not establish license inheritance for `TilesetWithFullMetadata`.

No acquisition is authorized unless explicit license evidence is established.

## Canonical acquisition ledger

External ledger:

`C:\EarthSynoptic-Benchmark-Data\manifests\acquisition-ledger.jsonl`

Audited identity:

- Record count: 13
- Byte length: 85481
- SHA-256: `485e70fa55603ff8a7b661f468a4e113b7bf0fb0563fba6bc9cdbe6b07eb299e`
- Mutation policy: append-only
- Previous-ledger SHA-256 links: 12
- Previous-ledger SHA-256 link failures: 0

### Ledger indexing rule

Physical record 1 is the `ledger_header`.

The header intentionally does not contain a `record_index` property.

Physical records 2 through 13 use:

`record_index = physical record number`

Audited indexing state:

- HeaderRecordIndexPresent: false
- HeaderIndexExemptionValid: true
- IndexedArtifactStateRecordCount: 12
- MissingRecordIndexCount: 0
- RecordIndexMismatchCount: 0

MetadataGranularities historical scope clarification:

Record 5 is the historical ACCEPTED `artifact_batch_state`.

Record 6 clarifies that record 5 `fixture_complete=true` represents sample-level completion for MetadataGranularities and does not represent completion of the entire five-sample conformance family.

## Deterministic raw inventory

External raw evidence remains outside the Git repository.

Audited raw inventory:

- Raw artifact count: 75
- Total byte length: 4747639
- SHA-256: `17549c835a6ef5af98f21f0a384a91f46da5443005dd2cd3b4556814cc32661f`

The deterministic inventory fingerprint was constructed from lexically sorted records of:

`<relative-path>|<byte-length>|<sha256>`

with one LF-terminated line per raw artifact.

Audited sample partition:

- MetadataGranularities: 21 files
- SparseImplicitOctree: 45 files
- MultipleContents: 3 files
- PropertyAttributesPointCloud: 6 files
- TilesetWithFullMetadata: 0 files

No raw directory for `TilesetWithFullMetadata` is expected while the license remains unresolved.

## Canonical transfer-log identities

### MetadataGranularities

- File: `GOREV-156_3DT-CONF-01_MetadataGranularities_GLBS-transfer.jsonl`
- Byte length: 22841
- Record count: 22
- SHA-256: `40d084b223571e424173331ea7dc1abb83f3f401b55b931e85828afd20506cea`

### SparseImplicitOctree

- File: `GOREV-162_3DT-CONF-01_SparseImplicitOctree-transfer.jsonl`
- Byte length: 64094
- Record count: 47
- SHA-256: `15bf5cbbe41b50a43d1cc010a78bd0d17cc7cba3a9490b85626f27173bf22eb0`

### MultipleContents

- File: `GOREV-166_3DT-CONF-01_MultipleContents-transfer.jsonl`
- Byte length: 4775
- Record count: 5
- SHA-256: `3f14770fb6011d03f45e821c8a9758a45e7599e05c84b6d33c6d42a0f06b6c13`

### PropertyAttributesPointCloud

- File: `GOREV-172_3DT-CONF-01_PropertyAttributesPointCloud-transfer.jsonl`
- Byte length: 9818
- Record count: 8
- SHA-256: `3777265b13e1a278a79a20ccc5460092bf2b98ceb1e04c6b9d6fd7a38ce8ff8f`

## Milestone audit identity

Latest successfully completed substantive milestone audit:

`GÖREV-175B`

Result:

`PASS / CLOSED`

Milestone SHA-256:

`6601ba014bfcf17fd74731df3f89ad8bf46cd3c8ec69be39b30ecd8e6acd7fc4`

Audited integrity results:

- AcquisitionTreeIntegrity: PASS
- LedgerStructureIntegrity: PASS
- LedgerAppendOnlyIntegrity: PASS
- SampleStateIntegrity: PASS
- TransferLogIntegrity: PASS
- RepositoryIntegrity: PASS

## External evidence boundary

The canonical acquisition evidence root remains:

`C:\EarthSynoptic-Benchmark-Data`

This Git checkpoint does not copy or embed the external evidence set.

The following remain outside the EarthSynoptic Git repository:

- raw benchmark artifacts;
- the canonical acquisition ledger;
- transfer logs;
- staging artifacts;
- `.partial` files.

At the audited checkpoint:

- staging file count: 0;
- `.partial` file count: 0.

This document records identities, counts, hashes, state and provenance references only.

## Architecture and technology-selection boundary

This checkpoint is not an Architecture Decision Record.

It does not select CesiumJS, MapLibre GL JS, OpenLayers, Mapbox GL JS, ArcGIS Maps SDK for JavaScript, deck.gl, or any other mapping, rendering, globe, visualization or runtime technology.

The use of `CesiumGS/3d-tiles-samples` as a pinned benchmark evidence source does not imply selection of CesiumJS or any Cesium runtime technology.

Technology selection remains subject to the separate benchmark, governance and ADR process.
