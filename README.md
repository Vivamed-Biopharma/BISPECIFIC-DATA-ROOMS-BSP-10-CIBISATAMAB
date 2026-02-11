# BSP-10-CIBISATAMAB: Glycoform-Selective Bispecific Antibody

![Status](https://img.shields.io/badge/Status-Pre--Clinical-blue.svg)
![License](https://img.shields.io/badge/License-Proprietary-red.svg)
![Category](https://img.shields.io/badge/Category-Bispecific_Antibody-green.svg)

### Executive Summary

This data room contains the complete preclinical, in-silico validation package for **BSP-10-CIBISATAMAB**, a next-generation bispecific T-cell engager. The asset is a "bio-better" variant of cibisatamab, engineered with a novel glycoform-selective binding arm for Carcinoembryonic Antigen (CEA). This innovation is designed to mitigate the known dose-limiting gastrointestinal toxicity of the parent molecule by preferentially targeting tumor-associated CEA over CEA expressed on healthy epithelial tissues, thereby improving the therapeutic index for the treatment of colorectal cancer.

---

### Innovation Profile

| Property                    | Description                                                                                                                                                                                                    |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mechanism of Action**     | Redirects T-cells via a CD3-engaging arm to selectively kill tumor cells expressing a specific glycoform of CEA (CEACAM5). The CEA-binding arm is engineered to differentiate between tumor and normal tissue CEA. |
| **Targets**                 | **1. Tumor Antigen:** Carcinoembryonic Antigen (CEA / CEACAM5) <br> **2. Immune Effector:** CD3 Epsilon Chain (CD3ε) on T-cells                                                                                     |
| **Therapeutic Area**        | Oncology                                                                                                                                                                                                       |
| **Indication**              | Colorectal Cancer (CRC)                                                                                                                                                                                        |
| **Differentiation from Prior Art** | The core innovation is the introduction of a tumor-selective binding mechanism based on differential glycosylation. Unlike the parent molecule (cibisatamab / CEA-TCB) and other anti-CEA antibodies (e.g., Sm3e), which bind CEA broadly, BSP-10-CIBISATAMAB is engineered for glycoform selectivity. This represents a novel and non-obvious improvement designed to significantly widen the therapeutic window. |

### Scientific Rationale

The clinical development of first-generation CEA-targeting T-cell engagers, such as cibisatamab, has been hampered by on-target, off-tumor toxicity. CEA is expressed at high levels on colorectal tumors but is also present on the apical surface of healthy gastrointestinal epithelial cells. This leads to T-cell-mediated killing of normal tissue, resulting in dose-limiting gastrointestinal adverse events (e.g., diarrhea, colitis).

BSP-10-CIBISATAMAB solves this critical problem by exploiting a key biological difference: the post-translational glycosylation of CEA is aberrant in tumor cells compared to normal epithelial cells. The CEA-binding domains of this molecule have been computationally engineered to preferentially recognize these tumor-specific glycoforms. This selective engagement is hypothesized to concentrate T-cell cytotoxic activity at the tumor site while sparing healthy GI tissue, thereby overcoming the principal safety liability that has limited the therapeutic potential of this drug class.

### Asset Valuation and Scoring

The following metrics reflect the most recent internal validation of the asset.

| Metric                     | Score           | Date Validated |
| -------------------------- | --------------- | -------------- |
| **Patentability**          | 7.25 / 10.0     | 2026-02-06     |
| **In Silico Enablement**   | 8.75 / 10.0     | 2026-02-06     |
| **Commercial Value**       | 7.5 / 10.0      | 2026-02-06     |
| **Composite Score (P+S+C)**| **23.50 / 30.0**| 2026-02-06     |
| **rNPV Estimate**          | **$95.0M**      | 2026-02-06     |

*Note: An earlier analysis from the initial patent filing estimated a Gemini rNPV of $250.0M based on a patentability score of 8.0/10 and an in-silico score of 9.0/10. The scores above represent the current, fully validated program values.*

---

### In Silico Validation & Developability

The BSP-10-CIBISATAMAB program was enabled by a state-of-the-art computational pipeline to design and de-risk the lead candidate.

#### Computational Methods Employed

| Method          | Platform                    | Purpose                                           |
| --------------- | --------------------------- | ------------------------------------------------- |
| **Structure Prediction** | Boltz-2                   | *AlphaFold3 derivative for high-accuracy modeling*|
| **Binding Pose Prediction** | DiffDock-L                | *Simulating antibody-antigen interactions*        |
| **Variant Design**      | ProteinMPNN / RFdiffusion   | *Generative design of novel binding interfaces*   |
| **Stability Analysis**    | ThermoMPNN / EvoEF2 ddG     | *Predicting thermal stability (Tm) and ΔΔG*       |
| **Solubility Prediction** | NetSolP                   | *Aqueous solubility score prediction*             |
| **Aggregation Analysis**  | Aggrescan3D               | *Mapping of aggregation-prone regions (APRs)*     |
| **Immunogenicity Screen** | DeepImmuno                | *In silico prediction of immunogenic epitopes*    |

#### Key Developability Metrics

The final candidate sequences meet rigorous in silico criteria for manufacturability and safety.

| Parameter           | Threshold        | Result                                   |
| ------------------- | ---------------- | ---------------------------------------- |
| **Solubility Score**| > 0.85           | **Pass**                                 |
| **Melting Temp (Tm)**| > 65°C           | **Pass**                                 |
| **Sequence Integrity**| Standard Rules | **VALIDATED** (as of 2026-02-06)         |

Sequence integrity validation confirms that all VH/VL domains contain correct framework features, including N-terminal residues (e.g., QVQL/EVQL), conserved cysteines for disulfide bonds, proper JH/Jκ joining regions, and non-generic CDR3 sequences.

---

### Patent & Intellectual Property Summary

The invention constitutes a selection invention or improvement patent over existing anti-CEA bispecific antibodies. The patentability rests on the novel and non-obvious engineering of the CEA-binding domain for glycoform selectivity, which directly addresses the well-documented toxicity limitations of prior art. This "bio-better" approach provides a strong basis for composition of matter claims on the specific antibody sequences and method of use claims for treating colorectal cancer with an improved safety profile.

---

### Data Room Index

All computational data for this bispecific program is located in a centralized repository. **Note: The raw data files reside in the `Bispecific-BSP-02-ELRANATAMAB` GitHub repository, which serves as the shared data lake for this program series.**

**Data Location:** **[`Bispecific-BSP-02-ELRANATAMAB`](https://github.com/nickharris808/Bispecific-BSP-02-ELRANATAMAB)**

| Directory Path                          | File Count | Description                                                                                             |
| --------------------------------------- | ---------- | ------------------------------------------------------------------------------------------------------- |
| `01_reference_data/`                    | 117        | Contains reference structural data, including Boltz-2 (AlphaFold3) generated CIF structures, MSA files, and pLDDT confidence scores for the target and antibody variants. |
| `02_aggregation_analysis/`              | 19         | Results from Aggrescan3D, including detailed mapping of Aggregation Prone Regions (APRs) on the antibody surface. |
| `03_variant_designs/`                   | 45         | Candidate sequences generated by the ProteinMPNN and RFdiffusion generative models for the CEA-binding arm. |
| `04_validation_results/`                | 256        | Comprehensive validation data for all designed variants, including outputs from EvoEF2 (ddG), NetSolP (solubility), ThermoMPNN (stability), and DeepImmuno (immunogenicity). |

### Usage

This data room serves as the central information hub for due diligence and internal program review for BSP-10-CIBISATAMAB.

1.  **Review Scientific Rationale:** Understand the core hypothesis and differentiation of this asset.
2.  **Assess Valuation:** Consult the V9 scoring table for the latest validated metrics.
3.  **Examine In Silico Data:** Cross-reference the computational methods with the raw data located in the linked GitHub repository to audit the design and de-risking process. The `04_validation_results/` directory contains the key data supporting the selection of the final candidate.
4.  **Evaluate IP Position:** Use the patent summary as a starting point for freedom-to-operate and patentability analysis.