# argus-safety-icsr-processing

> Pharmacovigilance ICSR Processing in Oracle Argus Safety 8.4 | Methotrexate ADR | 5 Cases | MedDRA V28.1

## Overview

End-to-end ICSR processing in Oracle Argus Safety 8.4 using published literature case reports of methotrexate-associated adverse drug reactions. Covers the complete ICSR lifecycle — case intake, triage, data entry, MedDRA coding, causality assessment, narrative writing, and regulatory reporting assessment.

- **Drug:** Methotrexate (Human PV)
- **PV System:** Oracle Argus Safety 8.4
- **MedDRA Version:** V28.1
- **Cases Processed:** 5 ICSRs
- **Report Type:** Literature (PubMed / PMC)
- **Regulatory Framework:** ICH E2A | WHO-UMC | CIOMS | EU GVP Module VI
- **Prepared by:** Nick Iver Majaw, PharmD

---

## Cases Processed

| Case ID | Primary Event | Seriousness | Causality | Outcome |
|---|---|---|---|---|
| 26US000284 | Pancytopenia + Mucosal inflammation | Hospitalized, Medically Significant | Related | Recovered |
| 26US000285 | Pneumonitis + Pancytopenia | Hospitalized, Life-threatening | Related | Recovered |
| 26US000286 | Neutropenia + Thrombocytopenia + Mucosal inflammation | Life-threatening, Medically Significant | Related | Unknown |
| 26US000287 | Bone marrow failure + Skin ulcer | Hospitalized, Medically Significant | Related | Unknown |
| 26US000288 | Pancytopenia + Mucosal inflammation | Hospitalized, Medically Significant, Death | Related | Fatal (2/5) / Recovered (3/5) |

---

## Skills Demonstrated

### ICSR Processing in Argus Safety 8.4
- Case intake and BookIn — assigned Argus case IDs, receipt dates, report type, literature reference
- Case triage — assessed seriousness criteria, determined 15-day expedited reporting under ICH E2A
- Data entry — patient demographics, suspect drug details, dosage regimens, product indication, reporter information
- MedDRA V28.1 coding — verbatim to PT mapping using Argus MedDRA browser across 9 event terms
- Causality assessment — WHO-UMC scale applied; all cases assessed as Related
- Narrative writing — CIOMS-style full and abbreviated narratives for all 5 cases
- Activities documentation — contact log, action items with 15-day due dates, routing comments, audit trail
- Regulatory reporting assessment — 15-day MedWatch 3500A expedited reporting assessed for all serious cases

### MedDRA Coding (V28.1)
| Verbatim | SOC | PT | Code |
|---|---|---|---|
| Pancytopenia | Blood and lymphatic system disorders | Pancytopenia | 10033661 |
| Mucositis | General disorders and administration site conditions | Mucosal inflammation | 10028116 |
| Pneumonitis | Respiratory, thoracic and mediastinal disorders | Pneumonitis | 10035742 |
| Neutropenia | Blood and lymphatic system disorders | Neutropenia | 10029354 |
| Thrombocytopenia | Blood and lymphatic system disorders | Thrombocytopenia | 10043554 |
| Bone marrow suppression | Blood and lymphatic system disorders | Bone marrow failure | 10006026 |
| Skin ulcers | Skin and subcutaneous tissue disorders | Skin ulcer | 10040791 |

### Reporting
- Generated Case Data Analysis Report in Argus Safety 8.4 — PT distribution, outcome profile (Fatal 20%, Recovered 40%, Resolved 20%, Unknown 20%), gender breakdown
- Configured ICH PSUR Line Listing Report for FDA R2 reporting destination

---


## Source Literature

1. Quan Soon KL et al. A Case Report on Iatrogenic Methotrexate Toxicity. Cureus. 2024. DOI: 10.7759/cureus.64081
2. Silva MM et al. Methotrexate Toxicity — Pneumonitis and Pancytopenia. Cureus. 2022. DOI: 10.7759/cureus.23078
3. Adverse drug reaction to methotrexate: pharmacogenetic origin. PMID: 17242415. 2007.
4. Atypical Methotrexate Toxicity — Severe Bone Marrow Suppression. PMC12495944. 2025.
5. Subedi B et al. Mucocutaneous Toxicity Following MTX Medication Error. JNMA. 2025. DOI: 10.31729/jnma.8905

---

## Tools & Technologies

![Oracle Argus Safety](https://img.shields.io/badge/Oracle_Argus_Safety-8.4-red)
![MedDRA](https://img.shields.io/badge/MedDRA-V28.1-blue)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-green)

---

*Nick Iver Majaw | PharmD | github.com/Nickiver04*
