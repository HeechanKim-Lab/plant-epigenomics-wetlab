# Plant Wet-Lab Records

Bench records from molecular biology and plant work in the Plant Immunity & Epigenetics Laboratory, May to September 2026: nucleic acid and protein extraction from tomato, qPCR, plasmid preparation, amplicon library PCR for genotyping CRISPR knockout candidates, Arabidopsis seed handling and a bacterial infection assay, and two course practicals on GUS reporter lines. Each log gives the reference protocol, what was done at the bench, and the deviations from the protocol.

**Status:** ongoing; logs are added as experiments are done.

---

## 1. Overview

The logs belong to five lines of work:

| Work | Question or purpose | Logs |
| :--- | :--- | :--- |
| Tomato multi-generation soil experiment | Molecular material from plants whose parents were treated with soil suspensions from Gijang B (GB) or Gyeongju (GJ), or with MES buffer: P, F1 and F3 generations | 2026-05-28, 2026-05-29, 2026-06-18, 2026-06-24, 2026-06-25, 2026-07-07, 2026-07-20 |
| *SlUPF3a* knockout candidates in tomato cv. Micro-Tom | Genotyping of 15 candidate lines by amplicon deep sequencing of the target site | 2026-07-28 |
| Arabidopsis bacterial infection (planned BPA project) | Effect of bisphenol A on infection by *Pseudomonas syringae*; seed preparation, sowing and a method test with untreated plants | 2026-07-21, 2026-07-24, 2026-09-15 |
| NMD reporter cloning | cDNA from Arabidopsis Col-0 and tomato cv. Moneymaker as template for cloning candidate sequences (including *SNC1*) into a RUBY reporter | 2026-09-09 |
| Course "Plant Physiology and Laboratory" | Media, seed sterilization, *Marchantia* gemmae plating, GUS staining and tissue clearing | 2026-09-14, 2026-09-21 |

The 1/2 MS medium (2026-07-01) and the plasmid preparation (2026-07-09) are separate records. In earlier observations of the tomato project (not part of this repository), plants grown with GJ soil were larger and plants grown with GB soil ripened earlier.

---

## 2. Log index

| Date | Log | Content | Results recorded |
| :--- | :--- | :--- | :--- |
| 2026-05-28 | [Tomato protein extraction](logs/2026-05-28_Tomato_Protein_Extraction.md) | 64 leaf samples (P, F3); TissueLyser; NanoDrop A280 of pooled samples | — |
| 2026-05-29 | [Tomato RNA extraction](logs/2026-05-29_Tomato_RNA_Extraction.md) | Same 64 samples; TRIzol; TURBO DNase; PCI clean-up | — |
| 2026-06-18 | [Tomato DNA extraction](logs/2026-06-18_Tomato_DNA_Extraction.md) | 18 leaf samples; CTAB with drill grinding; two PCI extractions | — |
| 2026-06-24 | [Tomato protein extraction, P](logs/2026-06-24_Tomato_Protein_Extraction.md) | 12 P-generation samples; mortar grinding; pooled NanoDrop A280 | — |
| 2026-06-25 | [Tomato RNA extraction, P](logs/2026-06-25_Tomato_RNA_Extraction.md) | Same 12 samples; TRIzol; TURBO DNase on one of two aliquots | — |
| 2026-07-01 | [1/2 MS medium](logs/2026-07-01_MS_media.md) | 1 L of 1/2 MS with 0.7% agar | — |
| 2026-07-07 | [Tomato F1 qPCR](logs/2026-07-07_Tomato_qPCR.md) | 24 F1 cDNA samples; *UPF2*, *SRRM1-like*, *Actin*; 384-well plate | Ct values not included |
| 2026-07-09 | [Plasmid extraction](logs/2026-07-09_Plasmid_DNA_Extraction.md) | pGEX-5X-1 from *E. coli* DH5α; spin columns; 40 µL elution | 123.5 and 125.8 ng/µL |
| 2026-07-20 | [Reagent notes](logs/2026-07-20_Chemical_Properties.md) | Properties, roles and safety of the extraction reagents | — |
| 2026-07-21 | [Seed sterilization](logs/2026-07-21_Arabidopsis_Bacteria_Pathogen_Infection_Preparation.md) | Col-0 seeds; 20% NaClO with Triton X-100; 72 h stratification | — |
| 2026-07-24 | [Arabidopsis sowing](logs/2026-07-24_Arabidopsis_Sowing.md) | 2 trays × 12 cells × 12 seeds; Pasteur-pipette sowing | — |
| 2026-07-28 | [*SlUPF3a* amplicon libraries](logs/2026-07-28_Tomato_DNA_Deep_Sequencing.md) | 15 lines; CTAB; three-step PCR with dual indexes; gel extraction | 3.5–106.2 ng/µL |
| 2026-09-09 | [cDNA synthesis](logs/2026-09-09_cDNA_Synthesis.md) | `At` and `MM` RNA; oligo(dT); SuperScript II | 59.1–61.6 ng/µL (diluted reactions) |
| 2026-09-14 | [Course week 2](logs/2026-09-14_Plant_Physiology_W02.md) | MS and 1/2 B5 plates; seed sterilization; gemmae plating | growth after 7 days |
| 2026-09-15 | [Arabidopsis infection](logs/2026-09-15_Arabidopsis_Bacteria_Infection.md) | *Pss* B728a at OD600 = 0.0001; leaf discs at 3 dpi; spot plating | 2.24 × 10⁴–1.76 × 10⁶ CFU/cm² |
| 2026-09-21 | [Course week 3](logs/2026-09-21_Plant_Physiology_W03.md) | GUS staining of *CLV3*, *CYCB1;1* and *MpYUC2* reporters; FAA/ClearSee clearing | GUS images |

---

## 3. Methods

### Nucleic acid and protein extraction

* **RNA:** grinding in liquid nitrogen (TissueLyser at 30 Hz, or mortar and pestle); TRIzol and chloroform; isopropanol precipitation; TURBO DNase; PCI clean-up; sodium acetate, glycogen and ethanol precipitation.
* **Genomic DNA:** CTAB lysis at 65 °C with grinding by a handheld drill; the initial buffer volume was reduced (200–300 µL before grinding, the rest afterwards) to limit splashing; two PCI extractions; isopropanol precipitation.
* **Plasmid:** alkaline lysis and silica spin columns (FAPD buffers); 2.8 mL culture per preparation; 40 µL elution.
* **Protein:** Tris-HCl, NaCl and EDTA buffer with Triton X-100, SDS, DTT and protease inhibitor; NanoDrop A280.

### PCR-based assays

* **Amplicon libraries (*SlUPF3a*):** 1st PCR with locus primers, 2nd nested PCR, 3rd PCR with dual indexes (D701–D702 × D501–D508). Index primers were placed on opposite sides of the tube wall and combined by the spin-down. 0.8% agarose gels; gel extraction of the 3rd PCR products; NanoDrop (A260/A280, A260/A230).
* **qPCR (tomato F1):** 384-well plate, SYBR Green, 10 µL reactions; *UPF2* and *SRRM1-like* with *Actin* as reference; 24 cDNA samples in technical triplicate; master mix loaded tier by tier with light shielding; relative quantification by 2^−ΔΔCt.
* **cDNA:** oligo(dT) priming and SuperScript II; 42 °C for 60 min, 70 °C for 15 min; diluted to 200 µL.

### Plant and microbiology work

* **Arabidopsis seeds:** 20% NaClO with Triton X-100 for 1 min, floating seeds discarded, three washes, 72 h at 4 °C in the dark; sowing with a wide-bore Pasteur pipette, 12 seeds per cell in a 3 × 4 grid.
* **Infection assay:** *P. syringae* cultures in KB with rifampicin (two-step culture); needleless-syringe infiltration at OD600 = 0.0001; leaf discs at 3 dpi; serial dilution and spot plating on LB with rifampicin; CFU per cm² of leaf.
* **Media:** 1/2 MS (2.15 g/L MS, 10 g/L sucrose, 0.5 g/L MES, pH 5.8, 7 g/L agar); MS with gellan gum and 1/2 B5 with agar for the course.
* **Histology (course):** GUS staining with X-Gluc; FAA fixation and ClearSee clearing; bright-field microscopy.

---

## 4. Results recorded in the logs

* **Plasmid:** 123.5 and 125.8 ng/µL (two preparations).
* ***SlUPF3a* amplicon libraries:** 3.5–106.2 ng/µL (mean 37.6 ng/µL); A260/A280 between 1.80 and 2.00 for 12 of 15 samples; A260/A230 below 1.0 for 13 of 15 samples.
* **cDNA:** 59.1–61.6 ng/µL in the diluted reactions.
* **Infection test (untreated Col-0, *Pss* B728a):** 2.24 × 10⁴ to 1.76 × 10⁶ CFU/cm² at 3 dpi (log10 4.35–6.24; 8 leaves).
* **Course practicals:** GUS signal at the shoot apex (*CLV3p::GUS*), root and shoot apices (*CYCB1;1p::GUS*) and apical notches (*MpYUC2p::GUS*).

Protein readings, qPCR Ct values and sequencing results are not included in the logs.

---

## 5. Instruments and kits named in the logs

TissueLyser; NanoDrop and NanoDrop 2000c (Thermo Scientific); WiseTherm HB-96D dry bath; Bio-Rad C1000 Touch thermal cycler; iBright 1500 imaging system; Vision Scientific VS-8480S shaking incubator; Brand Transferpette-8 multichannel pipette; TRIzol; TURBO DNase; SuperScript II reverse transcriptase (Invitrogen); FAPD plasmid kit buffers; gel extraction buffers GDB and NSW.

---

## 6. Repository layout

```text
.
├── README.md
├── assets/   # photos of bench setups, instruments, gels and microscopy, named YYYY-MM-DD_description
└── logs/     # one Markdown log per experiment or day, named YYYY-MM-DD_Title.md
```
