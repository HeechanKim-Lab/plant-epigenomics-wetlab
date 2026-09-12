# Plant Epigenomics Wet-Lab Protocols & Records

Forensic bench records, assay optimization logs, and standard operating procedures (SOPs) supporting epigenomics and molecular genetics research at the Plant Immunity & Epigenetics Laboratory.

**Repository Status: Active / In Progress**  
*This repository serves as an ongoing electronic bench record. Protocols, quality control validations, and logs are continuously updated alongside active experimental cycles.*

---

## Assays & Technical Workflows

### 1. Targeted Amplicon Deep Sequencing
* **System:** CRISPR/Cas edit validation in *S1UPF3a* knockout line candidates of *Solanum lycopersicum* cv. 'Micro-Tom'.
* **Methodology:** Three-step nested PCR pipeline incorporating locus-specific amplification, secondary nested resolution, and tertiary dual-indexing adapters.
* **Optimization:** Implemented spatial 0° / 180° side-wall loading to isolate row and column index primers, preventing non-specific annealing prior to thermal denaturation.
* **QC & Purification:** Preparative 0.8% agarose gel electrophoresis followed by silica-membrane column extraction and spectrophotometric purity profiling ($A_{260}/A_{280}$, $A_{260}/A_{230}$).

### 2. Quantitative Real-Time PCR (qPCR)
* **Experimental Architecture:** High-throughput 384-well optical microplate arrays evaluating gene expression dynamics across transgenerational tomato cohorts (Parent, F1) exposed to regional soil regimes (Gyeongju, Gijang B).
* **Assay Design:** Multi-gene layout profiling target loci (*UPF2*, *SRRM1-like*) normalized against endogenous *Actin* across 24 biological samples run in technical triplicate.
* **Photoprotection & Consistency:** Bottom-up progressive loading sequence coupled with localized adhesive optical film shielding to prevent SYBR Green photobleaching during manual pipetting.
* **Analysis:** Relative quantification via comparative $\Delta\Delta C_t$ analysis with replicate-block outlier auditing.

### 3. Nucleic Acid & Protein Biochemistry
* **Total RNA Extraction:** Cryogenic leaf pulverization via liquid-nitrogen-cooled TissueLyser adapters (30 Hz), acid guanidinium thiocyanate-phenol-chloroform (TRIzol) phase separation, and on-bench TURBO DNase genomic DNA clearance.
* **Genomic DNA Isolation:** Modified CTAB protocol using reduced initial lysis volumes (200–300 µL) during motorized mechanical drilling to eliminate aerosol splashing and sample cross-contamination, followed by dual PCI organic extractions.
* **Plasmid Vector Isolation:** Alkaline lysis extraction of pGEX-5X-1 expression vectors from *Escherichia coli* DH5α, concentrating 2.8 mL culture payloads into low-volume elutions (40 µL).
* **Total Protein Extraction:** Detergent-reducing buffer formulation (Tris-HCl, EDTA, NaCl, Triton X-100, SDS, freshly added DTT, and protease inhibitors) combined with cryogenic TissueLyser disruption and NanoDrop $A_{280}$ absorbance normalization.

### 4. Plant Propagation & Physiology Assays
* **Stratification & Germination:** 72-hour dark cold moist stratification (4°C) to break dormancy and synchronize germination kinetics in *Arabidopsis thaliana* (Col-0).
* **Hydrodynamic Matrix Sowing:** Modified wide-bore glass Pasteur pipettes deployed for hydrodynamic seed singulation in 3 × 4 spatial matrices over convex-packed substrate.
* **Pathogen Challenge Preparation:** Seed surface sterilization using 20% NaClO supplemented with Triton X-100, incorporating buoyant-seed exclusion to purge low-viability embryos prior to infection assays.
* **In Vitro Culture:** Standardized formulation of 0.5× Murashige & Skoog (MS) solid media (2.15 g/L MS basal salts, 10 g/L sucrose, 0.5 g/L MES, pH 5.8 calibrated via KOH, solidified with 7 g/L plant agar).

---

## Directory Organization

```text
.
├── assets/    # Primary documentation: gel imaging, instrument displays, and bench setups
├── logs/      # Chronological markdown records: protocols, reaction mixtures, and deviations
└── README.md  # Core repository documentation
```

