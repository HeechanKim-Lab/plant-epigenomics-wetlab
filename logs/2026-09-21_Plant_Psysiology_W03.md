# Plant Physiology and Laboratory: Histochemical GUS Reporter Staining and Whole-Mount Seedling Optical Clearing (2026-09-21)

## Background & Project Narrative

### 1. Histochemical Reporter Systems: Enzymatic Mechanisms and Genetic Markers
* **$\beta$-Glucuronidase (GUS) Catalytic Cascade:** The *E. coli uidA*-encoded $\beta$-glucuronidase hydrolyzes the chromogenic substrate 5-bromo-4-chloro-3-indolyl-$\beta$-D-glucuronide (X-Gluc) into D-glucuronic acid and an indoxyl monomer (5-bromo-4-chloro-indoxyl). In the presence of oxygen and catalytic electron acceptors, two monomers undergo non-enzymatic oxidative dimerization to yield an insoluble 5,5'-dibromo-4,4'-dichloro-indigo precipitate, precisely localizing promoter activity at cellular resolution.
* **Target Genetic Lines:**
  * `At::CLV3p::GUS`: Demarcates the stem cell reservoir within the Central Zone (CZ) of the Shoot Apical Meristem (SAM). CLV3 peptide signaling activates receptor complexes to restrict *WUSCHEL* (*WUS*) expression in the organizing center, maintaining stem cell population homeostasis.
  * `At::CYCB1;1p::GUS`: Mitotic B-type cyclin reporter expressed strictly during late G2 and M phases, serving as an in situ proxy for mitotic division frequency across active meristems (SAM, RAM, and lateral root primordia).
  * `Mp::YUC2p::GUS`: Reflects localized de novo auxin (IAA) biosynthesis catalyzed by flavin monooxygenases at the apical notch of *Marchantia polymorpha*, governing planar polarity and dichotomous vegetative branching.

### 2. Physicochemical Roles of Fixative (FAA) and Optical Clearing (ClearSee) Agents
* **FAA Fixation Solution:**
  * *Formaldehyde ($2.5\%\text{ v/v}$):* Bifunctional covalent cross-linker that stabilizes structural proteins and cellular frameworks, immobilizing intracellular architecture against osmotic distortion.
  * *Glacial Acetic Acid ($2.5\%\text{ v/v}$):* Rapidly penetrating coagulant fixative that coagulates proteins and fixes nucleic acids, maintaining nuclear morphology and preventing nuclear distortion during subsequent tissue clearing.
  * *Ethanol ($45.0\%\text{ v/v}$):* Dehydrating solvent that extracts free cellular water to prevent tissue shrinkage, accelerates fixative penetration velocity, and enhances cell membrane permeability.
* **ClearSee Optical Clearing Formulation:**
  * *Xylitol ($10\%\text{ w/v}$):* High-refractive-index polyol that homogenizes internal optical refractive indices with the surrounding medium, minimizing light scattering across heterogeneous cell layers.
  * *Sodium Deoxycholate ($15\%\text{ w/v}$):* Anionic bile acid surfactant that solubilizes membrane lipids, extracts photosynthetic pigments (chlorophylls), and increases cell membrane permeability.
  * *Urea ($25\%\text{ w/v}$):* Chaotropic agent that disrupts non-covalent hydrogen bonds, denaturing light-scattering protein matrices to render dense plant tissues optically transparent.

### 3. Staining Buffer Chemistry & Inter-Species Optimization (*Arabidopsis* vs. *Marchantia*)

| Reagent / Component | *Arabidopsis thaliana* | *Marchantia polymorpha* | Mechanistic Role & Inter-Species Rationale |
| :--- | :--- | :--- | :--- |
| **Sodium Phosphate Buffer ($\text{pH } 7.0$)** | $40\text{ mM}$ | $40\text{ mM}$ | Physiological buffer maintaining the optimal pH environment for $\beta$-glucuronidase catalytic activity. |
| **Potassium Ferricyanide ($\text{K}_3[\text{Fe(CN)}_6]$)** | $5\text{ mM}$ | $1\text{ mM}$ | Catalytic oxidizing agent that accelerates oxidative dimerization of indoxyl intermediates, preventing soluble intermediate diffusion and sharpening localized spot boundaries. |
| **Potassium Ferrocyanide ($\text{K}_4[\text{Fe(CN)}_6]$)** | — | $1\text{ mM}$ | Functions with ferricyanide as a redox buffer to suppress non-specific oxidative background and refine focal precipitation. Omitted in *Arabidopsis* due to higher tissue tolerance to oxidants. |
| **EDTA** | $3\text{ mM}$ | $3\text{ mM}$ | Divalent metal ion chelator; suppresses endogenous metalloproteases and inhibits non-specific, cation-dependent enzyme side reactions to preserve substrate fidelity. |
| **Triton X-100** | $0.05\%\text{ (v/v)}$ | $0.01\%\text{ (v/v)}$ | Non-ionic surfactant enhancing cuticular and membrane permeability for X-Gluc entry. Reduced in *Marchantia* to prevent lysis of delicate, single-cell-layered thallus tissues. |
| **X-Gluc Substrate** | $0.5\text{ mg/mL}$ | $0.5\text{ mg/mL}$ | Chromogenic substrate cleaved by GUS; oxidizes and precipitates as insoluble indigo blue at transcriptional expression domains. |

---

## Experimental Design

### 1. Biological Systems & Genetic Cohorts
* **Angiosperm Vascular Model:** *Arabidopsis thaliana* (ecotype Columbia-0 [Col-0] wild-type; transgenic reporter lines `At::CLV3p::GUS` and `At::CYCB1;1p::GUS`).
* **Bryophyte Non-Vascular Model:** *Marchantia polymorpha* (accession Takarazuka-1 [Tak-1] haploid male wild-type; transgenic reporter line `Mp::YUC2p::GUS`).

### 2. Dual-Track Experimental Architecture
* **Track A: Histochemical GUS Reporter Profiling:** Utilizes pre-permeabilized seedlings/thalli stored in $90\%$ acetone at $-20^\circ\text{C}$ across transgenic reporter lines (`CLV3`, `CYCB1`, `YUC2`), undergoing two-step buffer washes, chromogenic substrate addition ($0.5\text{ mg/mL}$ X-Gluc), and static incubation at $37^\circ\text{C}$ overnight.
* **Track B: Whole-Mount Optical Clearing & Brightfield Histology:** Utilizes 7-day-old intact living wild-type specimens (Col-0, Tak-1), undergoing FAA cross-linking, centrifugal air evacuation ($13,000\text{ RPM}$, $1\text{ min}$), and rapid ClearSee optical clearing ($10\text{ min}$) for upright transmission microscopy.

### 3. Cohort Sample Allocation Matrix

| Track | Organism / Genotype | Culture Format & Age | Sample Unit | Primary Anatomical Targets |
| :--- | :--- | :--- | :--- | :--- |
| **Track A** | *A. thaliana* `CLV3p::GUS` | Solid MS medium; pre-permeabilized in $90\%$ acetone | 1 tube ($\sim 5\text{--}10$ seedlings) | Shoot apical meristem (SAM) stem cell niche |
| **Track A** | *A. thaliana* `CYCB1;1p::GUS` | Solid MS medium; pre-permeabilized in $90\%$ acetone | 1 tube ($\sim 5\text{--}10$ seedlings) | Actively dividing cells in SAM and RAM |
| **Track A** | *M. polymorpha* `Mp::YUC2p::GUS` | Solid $1/2$ B5 medium; pre-permeabilized in $90\%$ acetone | 1 tube ($\sim 3\text{--}5$ thalli) | Apical notch meristematic domain |
| **Track B** | *A. thaliana* Col-0 (WT) | Solid MS medium; 7 days post-sowing (Day 7) | 3 intact seedlings | Pavement cells, stomata, primary root, stele, RAM |
| **Track B** | *M. polymorpha* Tak-1 (WT) | Solid $1/2$ B5 medium; 7 days post-plating (Day 7) | 2 vegetative thalli | Apical notch cleft, thallus lamina, ventral rhizoids |

---

## Pre-Run Preparations

* **Reagents & Chemical Solutions:**
  * FAA Fixation Solution ($2.5\%\text{ formaldehyde}, 2.5\%\text{ glacial acetic acid}, 45\%\text{ ethanol}, 50\%\text{ ddH}_2\text{O}$)
  * ClearSee Optical Clearing Solution ($10\%\text{ w/v xylitol}, 15\%\text{ w/v sodium deoxycholate}, 25\%\text{ w/v urea}$)
  * Species-Specific Histochemical Staining Buffers:
    * *Arabidopsis* formulation (with and without $0.5\text{ mg/mL}$ X-Gluc)
    * *Marchantia* formulation (with and without $0.5\text{ mg/mL}$ X-Gluc)
  * Pre-treatment wash solvent: $90\%\text{ (v/v)}$ acetone stored at $-20^\circ\text{C}$
  * Decontamination solvent: $70\%\text{ (v/v)}$ and $100\%$ laboratory-grade ethanol
* **Consumables (Per Student Workstation):**
  * 5 × Sterile $1.5\text{ mL}$ microcentrifuge tubes (labeled: `CYCB1`, `CLV3`, `YUC2`, `1-2 Col-0`, `1-2 Mp Tak-1`)
  * Standard glass microscope slides ($\approx 25 \times 75\text{ mm}$) and glass coverslips ($\approx 24 \times 24\text{ mm}$)
  * Micropipette tips ($200\,\mu\text{L}$ and $1000\,\mu\text{L}$)
  * Fine laboratory task wipes
* **Equipment & Instrumentation:**
  * Certified chemical fume hood (mandatory for handling volatile formaldehyde and acetic acid)
  * High-speed benchtop microcentrifuge (operational up to $13,000\text{ RPM}$)
  * Constant-temperature dark incubator (calibrated to $37^\circ\text{C}$)
  * Upright transmission optical microscope equipped with digital camera monitor interface
  * Precision stainless steel micro-dissection forceps and micro-scalpels

## Reference Protocol

### 1. Histochemical $\beta$-Glucuronidase (GUS) Reporter Staining

#### Species-Specific Histochemical GUS Staining Buffer Formulations
| Component | *Arabidopsis thaliana* Working Concentration | *Marchantia polymorpha* Working Concentration | Functional Role in Assay |
| :--- | :--- | :--- | :--- |
| Sodium Phosphate Buffer ($\text{pH } 7.0$) | $40\text{ mM}$ | $40\text{ mM}$ | Neutral physiological buffering matrix |
| Potassium Ferricyanide ($\text{K}_3[\text{Fe(CN)}_6]$) | $5\text{ mM}$ | $1\text{ mM}$ | Catalytic electron acceptor; accelerates oxidative dimerization |
| Potassium Ferrocyanide ($\text{K}_4[\text{Fe(CN)}_6]$) | — | $1\text{ mM}$ | Redox buffer; restricts intermediate diffusion and over-oxidation |
| Ethylenediaminetetraacetic Acid (EDTA) | $3\text{ mM}$ | $3\text{ mM}$ | Metalloprotease inhibitor / heavy metal chelator |
| Triton X-100 | $0.05\%\text{ (v/v)}$ | $0.01\%\text{ (v/v)}$ | Non-ionic surfactant; enhances cuticular and membrane penetration |
| X-Gluc (5-bromo-4-chloro-3-indolyl-$\beta$-D-glucuronide) | $0.5\text{ mg/mL}$ | $0.5\text{ mg/mL}$ | Chromogenic enzymatic substrate |

#### Standard Operating Procedure: Enzymatic Labeling and Chromogenic Substrate Infiltration
* **1)** Harvest intact seedling or thallus specimens, submerge immediately into ice-cold $90\%\text{ (v/v)}$ acetone in a $1.5\text{ mL}$ microcentrifuge tube, and incubate at $-20^\circ\text{C}$ for $1\text{ hour}$ to permeabilize waxy cuticles and arrest endogenous metabolic activity.
* **2)** Carefully aspirate and discard the $90\%$ acetone supernatant without desorbing or damaging fragile plant tissue.
* **3)** Dispense an adequate volume of base staining buffer lacking X-Gluc substrate, invert the tube multiple times to rinse residual solvent, pulse spin down in a benchtop microcentrifuge, and decant the wash solution; repeat for a total of two wash cycles.
* **4)** Add species-specific staining buffer supplemented with $0.5\text{ mg/mL}$ X-Gluc until plant tissues are fully immersed.
* **5)** Transfer open or vented tubes into a vacuum desiccator and apply negative pressure for $15\text{ minutes}$ to evacuate apoplastic air pockets and drive the substrate solution into internal tissue layers.
* **6)** Seal reaction tubes and incubate in a constant-temperature dark incubator at $37^\circ\text{C}$ overnight ($12\text{--}16\text{ hours}$) to allow enzymatic cleavage of X-Gluc by $\beta$-glucuronidase and subsequent oxidative dimerization into insoluble 5,5'-dibromo-4,4'-dichloro-indigo (indigo blue) precipitate.

#### Standard Operating Procedure: Reaction Termination, Decolorization, and Stepwise Dehydration
* **1)** Aspirate the enzymatic staining buffer and immediately add $70\%\text{ (v/v)}$ ethanol until samples are fully submerged to quench $\beta$-glucuronidase activity and terminate the chromogenic reaction.
* **2)** Aspirate the $70\%$ ethanol and replace with an ethanol : acetic acid ($6:1\text{, v/v}$) clearing solution; incubate under gentle agitation until all green photosynthetic chlorophyll pigment is completely extracted from foliar and thalloid mesophyll.
* **3)** Aspirate the decolorizing solution and submerge cleared specimens in $70\%\text{ (v/v)}$ ethanol for $2\text{ hours}$ to stabilize cleared tissue architecture.
* **4)** Systematically dehydrate the samples through an ascending graded ethanol series to prevent osmotic collapse and cellular damage:
  $$70\% \longrightarrow 80\% \longrightarrow 90\% \longrightarrow 95\% \longrightarrow 100\%\text{ Ethanol}$$
  *(Technical Quality Control: Direct immersion into $100\%$ ethanol induces rapid osmotic dehydration, severe cytoplasmic shrinkage, and cell wall collapse; graded increments are mandatory)*.
* **5)** Mount processed specimens in mounting medium or glycerol on glass slides for brightfield optical microscopy.

---

### 2. Whole-Mount Seedling Fixation and ClearSee Optical Clearing

#### Tissue Fixation Solution Formulation
| Component | Concentration (% v/v) | Physicochemical Role |
| :--- | :--- | :--- |
| Formaldehyde | $2.5\%$ | Bifunctional covalent cross-linker; immobilizes structural proteins |
| Glacial Acetic Acid | $2.5\%$ | Rapid tissue penetrant; coagulates nucleoproteins and counteracts shrinkage |
| Ethanol ($100\%$) | $45.0\%$ | Dehydrating coagulant fixative; precipitates cellular matrix |
| Deionized Water ($\text{ddH}_2\text{O}$) | $50.0\%$ | Aqueous dilution solvent |

> **Hazard Precaution:** Formaldehyde is an acutely toxic, volatile carcinogen with strong mucosal irritant properties. All compounding and fluid handling must be executed within a certified chemical fume hood.

#### ClearSee Optical Clearing Formulation
| Component | Working Concentration (% w/v) | Physicochemical Role in Tissue Clarification |
| :--- | :--- | :--- |
| Xylitol | $10\%$ | High-refractive-index polyol; homogenizes internal optical refractive indices |
| Sodium Deoxycholate | $15\%$ | Anionic bile acid detergent; solubilizes membrane lipids and permeabilizes barriers |
| Urea | $25\%$ | Chaotropic denaturant; disrupts non-covalent hydrogen bonding to clarify proteins |
| Deionized Water ($\text{ddH}_2\text{O}$) | Balance to volume | Hydrophilic aqueous phase |

#### Standard Operating Procedure: Specimen Fixation
* **1)** Harvest fresh intact *Arabidopsis* seedlings or *Marchantia* gemmalings from growth media using fine forceps, carefully removing adhering agar to avoid optical contamination.
* **2)** Immediately transfer harvested specimens into a $1.5\text{ mL}$ microcentrifuge tube pre-filled with fixation solution, ensuring complete volumetric submersion.
* **3)** Evacuate internal air pockets and enforce fixative penetration by either applying vacuum desiccation or centrifuging tubes at maximum speed ($\ge 13,000\text{ RPM}$) for $1\text{ minute}$ in a benchtop microcentrifuge.
* **4)** Retain samples in fixation solution at $25^\circ\text{C}$ for routine same-day downstream clearing, or transfer to $4^\circ\text{C}$ for long-term specimen preservation.

#### Standard Operating Procedure: Optical Clearing and Wet-Mount Specimen Preparation
* **1)** **Primary Clearing Protocol (ClearSee Method):**
  * Retrieve fixed seedlings from the fixation solution and transfer directly into ClearSee clearing solution; allow tissue clarification to proceed for exactly $10\text{ minutes}$.
  * *(Technical Quality Control: Excessive exposure to ClearSee softens embryonic cell walls and leads to tissue disintegration, compromising histological resolution)*.
* **2)** **Alternative Solvent Clearing Protocol (Ethanol : Acetic Acid Method):**
  * Transfer fixed specimens directly into an ethanol : acetic acid ($6:1\text{, v/v}$) solution and incubate for $10\text{ minutes}$ prior to direct slide mounting.
* **3)** Transfer cleared intact seedlings onto a clean glass microscope slide.
* **4)** Using a sterile surgical scalpel under a stereomicroscope, micro-dissect target anatomical structures: cotyledons, shoot apex / shoot apical meristem (SAM), true leaves, and primary/lateral roots with root apical meristems (RAM).
* **5)** Pipette a drop of ClearSee clearing solution directly over the dissected plant tissues and overlay a coverslip without trapping air bubbles to finalize the preparate specimen.

## Bench Execution Log & Deviations

1. **Pre-Permeabilized Specimen Retrieval and Wash Equilibration**
   * **Target Reporter Cohorts:** Retrieved pre-conditioned plant material stored in $90\%\text{ (v/v)}$ acetone at $-20^\circ\text{C}$ across three transgenic reporter lines:
     * *Arabidopsis thaliana:* `At::CYCB1p::GUS` (mitotic cyclin G2/M-phase reporter) and `At::CLV3p::GUS` (shoot apical meristem stem cell niche marker).
     * *Marchantia polymorpha:* `Mp::YUC2p::GUS` (flavin monooxygenase-mediated auxin biosynthesis / apical notch marker).
   * **Solvent Clearance & Two-Step Buffer Wash:**
     * Carefully aspirated and discarded the spent $90\%$ acetone supernatant from each microcentrifuge tube without disturbing fragile seedling and thallus tissues.
     * Aliquoted $400\,\mu\text{L}$ of species-appropriate base histochemical staining buffer prepared without X-Gluc substrate into each tube.
     * Inverted tubes gently to rinse residual solvent, followed by a brief pulse spin-down in a benchtop microcentrifuge to collect wall-bound droplets and ensure specimens remained submerged at the tube base.
     * Aspirated and discarded the supernatant wash.
     * Repeated this sequence with an additional $400\,\mu\text{L}$ of substrate-free staining buffer (aliquot, inversion, pulse spin-down, and complete supernatant clearance) for a total of **two wash cycles** to thoroughly deplete residual acetone and equilibrate tissue $\text{pH}$ and osmolarity ($40\text{ mM}$ sodium phosphate, $\text{pH } 7.0$).

2. **Chromogenic Substrate Infiltration and Overnight Enzymatic Labeling**
   * **Substrate Addition:** Aliquoted $400\,\mu\text{L}$ of complete histochemical staining buffer supplemented with $0.5\text{ mg/mL}$ X-Gluc (5-bromo-4-chloro-3-indolyl-$\beta$-D-glucuronide) from stock vessels (`At-GUS(X)` and `Mp-GUS(X)`) directly into the labeled reaction tubes (`CYCB1`, `CLV3`, and `YUC2`), verifying complete volumetric immersion of all plant structures.
   * **Protocol Deviation (Omission of Vacuum Infiltration):** The canonical 15-minute vacuum desiccation cycle was **omitted**; the chromogenic substrate buffer was applied directly without apoplastic vacuum evacuation, relying on passive diffusion through permeabilized cuticular layers during extended thermal incubation.
   * **Overnight Chromogenic Incubation:** Transferred sealed, light-shielded sample tubes into a constant-temperature incubator maintained at **$37^\circ\text{C}$ overnight ($\sim 14\text{--}16\text{ hours}$)** to facilitate $\beta$-glucuronidase-mediated enzymatic cleavage of X-Gluc and progressive oxidative dimerization into insoluble indigo blue precipitates.
   ![Aliquoted Staining Buffers and Transgenic Reporter Line Tubes](../assets/2026-09-21_GUS_Staining.jpg)

3. **Whole-Mount Specimen Harvesting and Chemical Fixation**
   * **Biological Material Retrieval:**
     * *Arabidopsis thaliana* (Col-0): Harvested 7-day-old intact seedlings ($N = 3$) germinated on 2026-09-14 on Murashige and Skoog (MS) solid basal medium plates.
     * *Marchantia polymorpha* (Tak-1): Harvested vegetative gemmalings/thalli ($N = 2$) cultivated since 2026-09-14 on Gamborg's B5 solid medium plates.
   * **Sample Allocation:** Using ethanol-sanitized micro-forceps, transferred the 3 *Arabidopsis* seedlings into a labeled $1.5\text{ mL}$ microcentrifuge tube (`1-2 Col-0`) and the 2 *Marchantia* thalli into a separate tube (`1-2 Mp Tak-1`), ensuring complete exclusion of adhering solid agar matrix.
   * **FAA Fixation & Centrifugal Degassing:**
     * Aliquoted $400\,\mu\text{L}$ of FAA fixative solution ($2.5\%\text{ formaldehyde}, 2.5\%\text{ glacial acetic acid}, 45\%\text{ ethanol}, 50\%\text{ ddH}_2\text{O}$) into each tube to achieve complete specimen immersion.
     * Inverted tubes thoroughly to establish uniform contact across all cuticular interfaces.
     * Centrifuged at **13,000 RPM at room temperature (RT) for 1 minute** to force fixative infiltration into deep internal cell layers, pellet floating specimens, and displace trapped intercellular apoplastic air pockets into the liquid phase.
   * **Supernatant Clearance:** Carefully aspirated and discarded the toxic FAA fixative supernatant using a micropipette without disturbing the pelleted, fixed plant material at the tube base.
   ![Plant Tissue Sampling and Microcentrifuge Tube Allocation](../assets/2026-09-21_Seedling_Sample.jpg)

4. **Rapid Optical Clearing via ClearSee**
   * **Clearing Reagent Dispensation:** Aliquoted $400\,\mu\text{L}$ of ClearSee optical clearing reagent ($10\%\text{ w/v xylitol}, 15\%\text{ w/v sodium deoxycholate}, 25\%\text{ w/v urea}$) from a conical stock vessel directly over the pelleted tissues in tubes `1-2 At-Col-0` and `1-2 Mp Tak-1`.
   * **Tissue Clarification:** Inverted the tubes repeatedly to suspend the specimens within the viscous clearing matrix, followed by static incubation at **room temperature (RT) for exactly 10 minutes** until complete chlorophyll bleaching, refractive index matching, and tissue translucency were achieved.
   * **Technical Quality Control (Structural Preservation):** Clarification was strictly constrained to 10 minutes to avoid detergent-mediated tissue maceration and mechanical softening of juvenile cell walls prior to slide mounting.
   ![ClearSee Reagent Staging and Optical Clearing Setup](../assets/2026-09-21_Clear_See.jpg)

5. **Wet-Mount Slide Preparation and Upright Brightfield Optical Microscopy**
   * **Slide Mounting:** Carefully transferred the optically cleared *Arabidopsis* seedlings and *Marchantia* thalli from the microcentrifuge tubes onto clean glass microscope slides using fine dissection forceps. Positioned specimens flat in a droplet of ClearSee medium and mounted coverslips slowly at an angle to prevent air bubble entrapment.
   * **Microscope Configuration:** Positioned slides on the mechanical stage of an upright transmission optical microscope equipped with a digital camera telemetry interface, focused specimens under low magnification ($4\text{X}\text{--}10\text{X}$), and systematically resolved cellular architectures at high magnification ($20\text{X}\text{--}40\text{X}$).
   * ***Arabidopsis thaliana* (Col-0) Morphological Inspection:**
     * *Epidermal Pavement Cells & Stomatal Complexes:* Resolved undulating, puzzle-piece jigsaw pavement cells alongside mature guard cell pairs defining stomatal apertures across the foliar epidermis.
     ![Arabidopsis Leaf Epidermal Pavement Cells and Stomatal Complexes](../assets/2026-09-21_At_Stomata.jpeg)
     * *Root Apex & Meristematic Zone:* Resolved the conical root cap, columella cell files, the quiescent center within the Root Apical Meristem (RAM), and the distal zone of rapid cell division and elongation.
     ![Arabidopsis Root Apex and Root Apical Meristem (RAM) Architecture](../assets/2026-09-21_At_Root1.jpeg)
     * *Root Stele & Differentiation Zone:* Visualized the central vascular bundle showing organized tracheary elements with lignified wall thickenings, flanked by cortex and epidermal cell files initiating tubular root hair outgrowths.
     ![Arabidopsis Root Differentiation Zone and Central Vascular Stele](../assets/2026-09-21_At_Root2.jpeg)
   * ***Marchantia polymorpha* (Tak-1) Morphological Inspection:**
     * *Apical Notch & Meristematic Inset:* Captured the deep apical notch cleft at the thallus margin containing meristematic initial cells responsible for dichotomous vegetative branching, accompanied by emergent protective mucilage papillae.
     ![Marchantia polymorpha Apical Notch Invagination and Meristematic Zone](../assets/2026-09-21_Mp_Norch.jpeg)
     * *Thallus Lamina Ground Architecture:* Examined the transparent polygonal parenchyma cell network forming the internal photosynthetic ground tissue.
     ![Marchantia polymorpha Vegetative Thallus Lamina Cellular Organization](../assets/2026-09-21_Mp_Thallus.jpeg)
     * *Ventral Rhizoid Structures:* Resolved elongated unicellular rhizoid filaments projecting from the ventral thallus epidermis, discriminating both smooth-walled and internally peg-tuberculated structural walls.
     ![Marchantia polymorpha Ventral Unicellular Rhizoid Filaments](../assets/2026-09-21_Mp_Rhizoid.jpeg)