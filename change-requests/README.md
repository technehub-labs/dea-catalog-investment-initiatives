# Change Requests: dea-catalog-investment-initiatives

This index tracks every change request that lands on this repository.

| CR | Title | Status | Notes |
|----|-------|--------|-------|
| [CR-II-CAT-01](CR-II-CAT-01-catalogue-foundation.md) | Catalogue foundation (kit bring-up) | Landed (this PR) | Standard kit: pointer, dependencies, schema projection, gates 1-6, workflows, FOUNDATIONS, record standard. No records admitted. |
| CR-II-CAT-02 | Initial population | Planned | Evidence-gated seed population per FOUNDATIONS §7. |

## Numbering

Series tag `CR-II-CAT-NN`, sequential. Cross-repo CRs that touch this
repository are recorded here with their home-repo identifier.
| [CR-II-CAT-02](CR-II-CAT-02-cr-ii-cat-02.md) | Entity Ingestion Groundwork (candidate intake queue + gates) | **Proposed (this PR)** | Gated intake: queue + blocking queue gate + admission tool (candidate-state subtrees, content-derived ids); pin v2.6.0→v2.8.0 + shard-aware toolchain re-vendor. No records. |
| [CR-II-CAT-03](CR-II-CAT-03-cr-ii-cat-03.md) | InvestmentInitiative Candidate Corpus | **Landed (this PR)** | 999 queue submissions from 1 bank(s); manifest with sha256s; queue gate CONFORMANT; no entities change. |
| [CR-II-CAT-01](CR-II-CAT-01-cr-ii-cat-01.md) | InvestmentInitiative Candidate Admission Batch 02 (Official Documents- Disbursement and Financial Information Letter for Additional Financing for TF0C6881 and TF0C6868.pdf (D34442276) … World Bank project document facets (facets)) | **Landed (this PR)** | Admitted 999 `InvestmentInitiative` CANDIDATE records via the gated intake workflow (queue gate → admission tool → catalog gates); candidates +999, canonical unchanged; records at `lifecycle_status: proposed` in `candidates/` subtrees. |
