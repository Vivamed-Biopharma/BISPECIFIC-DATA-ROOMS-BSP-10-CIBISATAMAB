# BSP-10-CIBISATAMAB

## Executive Summary

| Property | Value |
|----------|-------|
| **Drug** | Cibisatamab |
| **Targets** | CEA (CEACAM5) × CD3 |
| **Indication** | Colorectal Cancer |
| **Innovation** | Glycoform-selective CEA binding to minimize GI toxicity |
| **Category** | Bispecific Antibody |

---

## V9 Scoring (Validated 2026-02-06)

| Metric | Score |
|--------|-------|
| **Patentability** | 7.25/10.0 |
| **In Silico Enablement** | 8.75/10.0 |
| **Commercial Value** | 7.5/10.0 |
| **Composite (P+S+C)** | 23.50/30.0 |
| **rNPV Estimate** | $95.0M |

---

## Sequence Validation

All antibody VH/VL sequences validated for correct framework features:
- Proper N-terminal framework residues (QVQL/EVQL for VH, DIVMTQ/DIQMTQ for VL)
- Conserved Cysteine residues for disulfide bonds
- JH/Jkappa joining regions present
- CDR3 sequences are specific (not generic)

**Status: VALIDATED** (2026-02-06)

---

## Computational Data

### Shared Data Repository

All computational data for this bispecific program lives in the shared data room:
**[Bispecific-BSP-02-ELRANATAMAB](https://github.com/nickharris808/Bispecific-BSP-02-ELRANATAMAB)**

| Directory | Files | Content |
|-----------|-------|---------|
| `01_reference_data/` | 117 | Boltz-2 (AlphaFold3) CIF structures, MSA files, confidence scores |
| `02_aggregation_analysis/` | 19 | Aggrescan3D APR mapping |
| `03_variant_designs/` | 45 | ProteinMPNN + RFdiffusion variant designs |
| `04_validation_results/` | 256 | EvoEF2 ddG, NetSolP solubility, ThermoMPNN, DeepImmuno |

### Validation Tools

Boltz-2 (AlphaFold3), DiffDock-L, ProteinMPNN, RFdiffusion, Aggrescan3D, NetSolP, ThermoMPNN, DeepImmuno

---

## Original Analysis

# BSP-10-CIBISATAMAB

# BSP-10-CIBISATAMAB

**Summary:** The invention describes a novel variant of the bispecific antibody cibisatamab engineered with glycoform-selective CEA binding domains to minimize gastrointestinal toxicity while maintaining efficacy in colorectal cancer.

**Patentability Score:** 8.0/10
**In-Silico Score:** 9.0/10
**Gemini rNPV:** $250.0M

**Patentability Analysis:**
The invention addresses the known dose-limiting gastrointestinal toxicity of cibisatamab (CEA-TCB) by introducing a tumor-selective binding mechanism based on differential glycosylation. While cibisatamab and anti-CEA antibodies (like Sm3e, which the provided VH/VL resembles) are prior art, the specific engineering for glycoform selectivity to differentiate tumor CEA from normal epithelial CEA represents a novel and non-obvious improvement. This 'bio-better' approach creates a strong position for a selection invention or improvement patent.

**In-Silico Analysis:**
The application utilizes a state-of-the-art computational pipeline, including Boltz-2 (AlphaFold3 derivative) for structure prediction, DiffDock-L for binding poses, and Aggrescan3D for developability. The inclusion of specific validation metrics (solubility >0.85, Tm >65°C) and immunogenicity screening (DeepImmuno) demonstrates comprehensive in silico enablement beyond simple sequence generation.

