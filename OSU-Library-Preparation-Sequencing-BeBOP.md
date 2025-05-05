---
# MIOP terms
methodology_category: Omics Analysis
project: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols'
purpose: 'PCR [OBI:0000415], Library Preparation [OBI:0000711]'
analyses: 'PCR [OBI:0000415], Library Preparation [OBI:0000711]'
geographic_location: 'North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]'
broad_scale_environmental_context: 'marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]'
local_environmental_context: 'oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024]'
environmental_medium: 'sea water [ENVO:00002149], polymerase chain reaction [OBI:0000415]'
target: 'amplicon sequencing assay [OBI_0002767]'
creator: 'Shannon Brown, Han Weinrich, Zachary Gold, Sean McAllister'
materials_required: 'vortexer [OBI:0400118], PCR instrument [OBI:0000989], Centrifuge [OBI:0400106]'
skills_required: 'sterile technique, pipetting skills, standard molecular technique'
time_required: '1 day'
personnel_required: 1
language: en
issued: '2025-05-01'
audience: scientists
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'
hasVersion: 1
license: 'CC0 1.0 Universal'
maturity level: mature

# FAIRe terms
barcoding_pcr_appr: 'two-step pcr'
pcr2_amplificationReactionVolume: 50
pcr2_commercial_mm: '2x KAPA HiFi HotStart ReadyMix'
pcr2_dna_vol: 5
pcr2_cond: 'initial denaturation:95_3; denaturation:95_0.5; annealing:55_0.5; elongation:72_0.5;8'
pcr2_annealingTemp: 55
pcr2_cycles: 8
pcr2_method_additional: 'Amplicon, P. C. R., Clean-Up, P. C. R., & Index, P. C. R. (2013). 16s metagenomic sequencing library preparation. Illumina: San Diego, CA, USA, 21.
sequencing_location: Oregon State University Center for Quantitative Life Sciences Genomics Core'
platform: ILLUMINA
instrument: Illumina MiSeq
seq_kit: 'Illumina MiSeq Reagent Kit v.3 (600-cycle) (Cat_No:MS-102-3003)'
lib_layout: paired end
lib_screen: 'The library was prepared following the "16S Metagenomic Sequencing Library Preparation: Preparing 16S Ribosomal RNA Gene Amplicons for the Illumina MiSeq System" purified using an Ampure XP Bead Amplicon Clean Up before PCR2, an Ampure XP Bead Amplicon Clean Up after PCR2, normalized by measuring DNA concentration via Qubit Fluorometric Quantification (ThermoFisher Scientific) using Broad Range chemistry (Cat_No:Q33265) and pooling equal DNA product, and diluted to 8 pM before loading it onto a MiSeq Flow Cell.'
adapter_forward: TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG
adapter_reverse: GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG
lib_conc: 8
lib_conc_unit: pM
lib_conc_meth: Qubit
phix_perc: 10
seq_method_additional: 'PhiX was spiked in at 10%'

---

# NOAA PMEL OME Oregon State University Metabarcoding Library Preparation Protocol 

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for the list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|<http://orcid.org/0000-0003-0490-7630>	|2025-05-01|
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | <https://orcid.org/0000-0001-9808-2638>|2025-05-01|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | <http://orcid.org/0009-0007-6063-0986>|2025-05-01|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|<http://orcid.org/0000-0001-6654-3495>|2025-05-01|

## RELATED PROTOCOLS


#### Internal Protocols
| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
|NOAA-PMEL-OME Machida Metazoan 18S V8 PCR Protocol | <https://doi.org/10.5281/zenodo.11398146>|v1.0| 2024-05-30|
|NOAA-PMEL-OME Parada Universal 16S PCR Protocol | <https://doi.org/10.5281/zenodo.11398127>|v1.0| 2024-05-30|

## RELATED EXTERNAL PROTOCOLS

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Amplicon, P. C. R., Clean-Up, P. C. R., & Index, P. C. R. (2013). 16s metagenomic sequencing library preparation. Illumina: San Diego, CA, USA, 21. | <https://emea.illumina.com/content/dam/illumina-support/documents/documentation/chemistry_documentation/16s/16s-metagenomic-library-prep-guide-15044223-b.pdf> | Illumina | 2013 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-05-01 | Initial release |


### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinet|
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|OSU CQLS| Oregon State University Center for Quantitative Life Sciences Genomics Core
|dNTP	|deoxynucleotide triphosphate|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies'
|HT1| Hybridization Buffer
|MBARI| Monterey Bay Aquarium Research Institute|
|MBON	|Marine Biodiversity Observation Network|
|NOAA|National Oceanic and Atmospheric Administration|
|NTC	|No template control
|OME	|Ocean Molecular Ecology
|PCR| Polymerase chain reaction |
|RSB| Resuspension Buffer |
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE    | Personal protective equipment |
|UW| University of Washington
| UDI | Unique Dual Index |
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

## BACKGROUND

### Summary

This protocol is used by [Oregon State University Center for Quantitative Life Sciences Genomics Core](https://cqls.oregonstate.edu/core/genomics) to prepare next-generation amplicon/metabarcoding sequencing libraries from OSU CQLS generated PCR products. PCR1 product is first cleaned using Ampure XP beads, then barcoded using unique, sample-specific Illumina Nextera XT Unique Combinatorial Indices (2x 10bp), then cleaned using Ampure XP beads, then quantified by Qubit Fluorometric Quantification (ThermoFisher Scientific) using Broad Range chemistry, and normalized and pooled to the same total DNA copies, and then sequenced on a MiSeq using the MiSeq Reagent Kit v.3 (600-cycle) (Cat_No:MS-102-3003). This standard two-step PCR sequencing library preparation methodology allows for the reuse of indices across multiple samples, enabling  96 total libraries to be sequenced on a single MiSeq run.

### Method description and rationale

Advantages to this protocol include ease of use, leveraging commercially available Illumina sequencing kits. This protocol's steps include: _PCR1 Amplicon Cleanup_, _Barcoding/Indexing PCR_, _PCR2 Amplicon Cleanup_, _Library Quantification, Normalization, Pooling, and Final Size Selection_, and _Sequencing_. 
For samples collected prior to 2021, NOAA PMEL OME conducted eDNA sample collection and filtration. OSU CQLS conducted DNA extractions and PCR amplification prior to this protocol ((See our NOAA PMEL OME [Methods](https://zenodo.org/communities/noaa_ome)). Sterivexes were shipped on dry ice to OSU CQLS in Corvallis, OR, USA where they were extracted and PCR amplified (separate BeBOP protocols) and then processed using this protocol. PCR1 product was first cleaned to remove excess primers, dNTPs, and primer dimer using an Ampure XP bead cleanup protocol. Cleaned PCR product is then indexed through a second barcoding PCR step using Illumina Nextera XT combinatorial indices. Indexed PCR product is then again cleaned using an Ampure XP bead cleanup protocol. Cleaned PCR2 product is then quantified via QuBit BR flurometry and then normalized and pooled by even total DNA copy numbers into a final pooled library. The library is then sequenced on an Illumina MiSeq at the OSU CQLS using the MiSeq Reagent Kit v.3 (600-cycle). The sequencing core demultiplexes raw sequence data, and downstream bioinformatics is conducted via [REVAMP](https://github.com/McAllister-NOAA/REVAMP).

This protocol is less detailed than our typical protocols, as we do not conduct this protocol ourselves. However, we capture the necessary [FAIRe](https://fair-edna.github.io/) relevant information.

### Spatial coverage and environment(s) of relevance

This protocol can be used for library preparation of any marker gene region of any eDNA or bulk biological sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used, such as wearing PPE to avoid skin or eye contact.

### Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time needed to execute the procedure

This protocol takes about 4-5 hours to execute per plate. There is a safe-stopping point after the PCR Amplicon Cleanup, Indexing PCR, Normalization, and Pooling steps. Across all stopping points, the plate can be stored for up to a week at 4°C, with storage at -20˚C for up to 6 months.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| Vortex | Vortex Genie | Scientific Industries | 1 | Can be substituted with generic |
| PCR Plate Centrifuge | Microplate Centrifuge | Generic Brand | 1 | Can be substituted with generic |
| Mag Stand | 96-Well Magnetic Separator | Generic Brand | 1 | Can be substituted with generic |
| 0.5-10 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 100-1000 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 uL 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Serological Pipette | Eppendorf Easypet 3 Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Ice Bucket | Generic | Generic | 1 | |
| QuBit Flurometer | Flurometric DNA quantification device | ThermoFisher Scientific | 1 | Can be substituted with generic fluorometric quantitation with dsDNA binding dye reagents |


| **Consumable equipment** |
| 96-well PCR plate | Armadillo PCR Plate, 96-well, clear, clear wells | ThermoFisher | 1 | Can be substituted with generic |
| Aluminum Foil Sealing Tape | AlumaSeal II Sealing Foils for PCR and Cold Storage | VWR | 7 | Can be substituted with generic | 
| 8-Strip Tubes | 0.2 mL 8-Strip PCR Tubes | Generic Brand | 5 | tubes without caps attached are better |
| Microcentrifuge Tubes | 2.0 mL Microcentrifuge Tube | Generic Brand | 8 | Can be substituted with generic|
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be substituted with generic - must be sterile and filtered |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be substituted with generic - must be sterile and filtered |
| RNase/DNase‐free reagent wells | VWR sterile multichannel reagent reservoirs, disposable | VWR | 1 | (case) VWR, Cat_NO:89094‐658 can be substituted with generic |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| **Chemicals** |
| 80% Ethanol | Molecular biology grade ethanol |
| PCR grade Water| Molecular biology grade water |
| 10 mM Tris pH 8.5 | Molecular biology grade Tris solution |
| AMPure XP beads  | AMPure XP Bead-Based Reagent | Beckman Coulter Life Sciences | 1 | (mL vial) is 500 reactions |
| Nuclease-free water | Nuclease-Free Water (not DEPC-Treated) | ThermoFisher Scientific | 1 | (5 mL vial) Cat_No: A63880 |
| Illumina XT Indexes Sets A, B, C, D | Illumina Nextera XT Indexes| Illumina | 1 | Nextera XT Index Kit v2 Set A (96 Indexes, 384 Samples) FC-131-2001; Nextera XT Index Kit v2 Set B (96 Indexes, 384 Samples) FC-131-2002; Nextera XT Index Kit v2 Set C (96 Indexes, 96 Samples) FC-131-2003; Nextera XT Index Kit v2 Set D (96 Indexes, 384 Samples) FC-131-2004 |
| 2x KAPA HiFi HotStart ReadyMix | Premixed 2X solution of Taq DNA Polymerase, dNTPs, and Reaction Buffer | Roche | 1 | (kit) Master Mix includes Taq DNA polymerase, dNTPs, MgCl2, and reaction buffer (Cat_No: 07958927001) |
| Qubit dsDNA BR Assay Kit | reagents for fluorometric quantification of DNA | ThermoFisher Scientific | 1 | (10 mL) Cat_No:Q32850 |
| MiSeq Reagent Kit v.3 (600-cycle)  | Includes one SP flow cell, one buffer cartridge, one cluster cartridge, and one sequencing cartridge to support a 600-cycle run on the MiSeq System. | Illumina | 1 | (flow cell) Cat_No:MS-102-3003 |
| PhiX Control v3 | Kitted DNA control for the Illumina sequencing platform. Compatible with Single and Paired End reads up to 150 base pairs. | Illumina | 1 | (tube) (10ul of 10nM template solution) Cat_No:FC‐110‐3001 |
| 1 N NaOH, molecular biology grade | NaOH needed for denaturing DNA | General lab supplier | 1 | (mL) |
| 10 mM Tris-HCl, pH 8.5 with 0.1% Tween 20 | Buffered Tween needed for denaturing DNA | General lab supplier | 1 | (mL) |

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Sterilize workspaces and durable equipment, including pipettes within the BSC, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
2. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. 
3. Run the UV light in the BSC for 30 minutes before starting work.
4. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). Recommended labeling scheme includes the plate name, primer, date of PCR, and personnel initials.
5. Label all microcentrifuge tubes both on the side and on the top of the tube. Recommended labeling scheme includes library name or reagent, date of PCR, and personnel initials.

#### PCR1 Amplicon Cleanup

#### Preparation
1. Bring the AMPure XP beads to room temperature.

#### Procedure 
Amplicons were then cleaned by AMPure XP beads to purify the amplicon away from free primers and primer dimer species following the Illumina 16S Preparation Guide instructions:

1. Centrifuge PCR1 plate at 1,000 × g at 20°C for 1 minute.
3. Vortex AMPure XP beads for 30 seconds. 
4. Add an appropriate volume of beads to a disposable well, depending on the quantity of samples to be processed.
4. Add 20 µl of beads to each PCR1 product using a multichannel pipette. Change tips between columns.
5. Mix by aspirating and expelling 10x times.
6. Incubate on the lab bench for 5 minutes.
7. Place the plate on a magnetic plate for 2 minutes or until the supernatant has cleared.
8. Keep PCR1 plate on the magnetic plate and remove and discard the supernatant using a multichannel pipette. Change tips between samples.
9. Keep PCR1 plate on the magnetic plate and add 200 µl of freshly prepared 80% ethanol to each sample well using a multichannel pipette.
10. Incubate on magnetic plate for 30 seconds.
11. Carefully remove and discard the ethanol supernatant.
10. Repeat steps 9-11, performing a second ethanol wash.
11. Use a P20 multichannel pipette with fine pipette tips to remove excess ethanol.
11. Air‐dry samples for 10 minutes, keeping the PCR1 plate on the magnetic bead stand.
12. Remove the PCR1 plate from the magnetic stand and then add 52.5 µl of 10 mM Tris pH 8.5 to each well using a multichannel pipette.
13. Mix by aspirating and expelling 10x times.
14. Incubate on lab bench for 2 minutes.
15. Place the plate on the magnetic stand for 2 minutes or until the supernatant has cleared.
16. Transfer 50 µl of the supernatant from the PCR1 plate to a new labeled 96‐well PCR plate.

This is a safe stopping point. Plates can be sealed and stored at ‐20°C for up to a week.

##### Quality control
No quality control is conducted.

#### Barcoding/Indexing PCR

This step attaches dual indices and Illumina sequencing adapters using the Nextera XT
Index Kit.

#### Procedure

1. The indexing PCR included P2x KAPA HiFi HotStart ReadyMix, 5 µL Illumina Nextera XT Index Primer 1 (F, N7XX), 5 µL Illumina Nextera XT Index Primer 2 (S5XX), 5 µl of template DNA (cleaned amplicon from the first PCR reaction), and 10 µL PCR Grade Water for a total volume of 50 µL.
2.  Thermocycling conditions consisted of an initial denaturation of 95 °C for 3 minutes, followed by 8 cycles of  95 °C for 30 sec, 55 °C for 30 seconds, and 72 °C for 30 seconds, followed by a final extension of 72˚C for 5 minutes, and a hold at 4˚C. 

**Primer Sequences Used**: Illumina Nextera XT primer sequences

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| Illumina-Nextera-XT-PCR-F Index 1 (i7) Adapters | forward | CAAGCAGAAGACGGCATACGAGAT-[**i7**]-GTCTCGTGGGCTCGG |
| Illumina-Nextera-XT-PCR-R Index 2 (i5) Adapters| reverse | AATGATACGGCGACCACCGAGATCTACAC-[**i5**]-TCGTCGGCAGCGTC|

**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |----- |
| 2x KAPA HiFi HotStart ReadyMix |2600| 25 |100% |50% |
| Forward Primer |520| 5 |10 μM |0.5 μM |
| Reverse Primer |520| 5 |10 μM | 0.5 μM |
| Nuclease-Free Water |1040|10 | N/A|N/A |
| Template DNA|N/A| 5 | 100%|8% |
| **Total**|**4680**| **50** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multiplied by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|3min|	1X
|**Normal Cycling**||||
|Denaturation|	95°C|	30s|	8X|
|Annealing|	55°C|	30s	|8X|
|Extension 	|72°C	|30s	|8X|
|Final Extension 	|72°C	|5min	|8X|
|Hold	|4°C	|∞	|1X|

**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing. This step is post-PCR and thus should occur in the post-PCR spaces.*

1. Set out Illumina Nextera XT primers and samples to thaw.
2. Vortex and spin down thawed samples, primers, and nuclease-free water. Then tap/flick Kapa Master Mix rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted above in the reagent mixture table.
4. Set out the template DNA to thaw if frozen.
5. Aliquot 45 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 5 μL DNA template to each well
8. Seal the PCR plate with foil.
9. Spin down the plate, and then transport in cooler blocks before placing in the thermocycler.
10.  Run thermocycler protocol.


##### Quality control
No quality control is conducted.

#### PCR2 Amplicon Cleanup


#### Preparation
1. Bring the AMPure XP beads to room temperature.

#### Procedure 
Amplicons were then cleaned by AMPure XP beads to purify the amplicon away from free primers and primer dimer species following the Illumina 16S Preparation Guide instructions:

1. Centrifuge PCR2 plate at 1,000 × g at 20°C for 1 minute.
3. Vortex AMPure XP beads for 30 seconds. 
4. Add an appropriate volume of beads to a disposable well, depending on the quantity of samples to be processed.
4. Add **56** µl of beads to each PCR2 product using a multichannel pipette. Change tips between columns.
5. Mix by aspirating and expelling 10x times.
6. Incubate on the lab bench for 5 minutes.
7. Place the plate on a magnetic plate for 2 minutes or until the supernatant has cleared.
8. Keep PCR2 plate on the magnetic plate and remove and discard the supernatant using a multichannel pipette. Change tips between samples.
9. Keep PCR2 plate on the magnetic plate and add 200 µl of freshly prepared 80% ethanol to each sample well using a multichannel pipette.
10. Incubate on magnetic plate for 30 seconds.
11. Carefully remove and discard the ethanol supernatant.
10. Repeat steps 9-11 performing a second ethanol wash.
11. Use a P20 multichannel pipette with fine pipette tips to remove excess ethanol.
11. Air‐dry samples for 10 minutes, keeping the PCR2 plate on the magnetic bead stand.
12. Remove the PCR2 plate from the magnetic stand and then add **27.5** µl of 10 mM Tris pH 8.5 to each well using a multichannel pipette.
13. Mix by aspirating and expelling 10x times.
14. Incubate on lab bench for 2 minutes.
15. Place the plate on the magnetic stand for 2 minutes or until the supernatant has cleared.
16. Transfer 50 µl of the supernatant from the PCR2 plate to a new labeled 96‐well PCR plate.

This is a safe stopping point. Plates can be sealed and stored at ‐20°C for up to a week.

##### Quality control
No quality control is conducted.

#### Library Quantification, Normalization, Pooling, and Final Size Selection 

##### Library Quantification

1. Quantify DNA using Qubit dsDNA BR Assay Kit following manufacturer's instructions.


##### Normalization

1. Calculate DNA concentration in nM, based on the size of DNA amplicons as follows:

	(concentration in ng/µL)/(660 g/mol * average library size) = concentration in nM
	Example:
	15ng/µL/(660 g/mol * 500 bp) = 45 nM

2. Dilute library in Resupension Bugger or 10 mM Tris pH 8.5 to 4nM

##### Pooling

1. Pool 5 µL of each uniquely tagged library into microcentrifuge tube for final cleaned pool.
2. Vortex and spin.

##### Final Size Selection

1. The Machida marker resulted in primer dimer (shorter 170bp peak) with main target ~500bp. From NorsemanWOAC_Pool1 (OSU876/OSU1034, DY20-12 cruise), primer dimer was removed using a by BluePippin size selection. For Norseman18S Pool2 (OSU1089, NO20-01 cruise) and Axial 2020 cruise an additional AMPure XP magnetic bead cleanup was conducted instead utilizing the entire pool (See above).

##### Quality control
For metagenomics samples, >100,000 reads per sample is sufficient to fully survey the bacterial composition. This number of reads allows for sample pooling to the maximum level of 96 libraries, given the MiSeq output of > 20 million reads. Theoretically on a perfect MiSeq run up to 125 samples for a single marker could be sequenced at once.

##### Quality control
For metagenomics samples, >100,000 reads per sample is sufficient to fully survey the bacterial composition. This number of reads allows for sample pooling to the maximum level of 96 libraries, given the MiSeq output of > 20 million reads. Theoretically, on a perfect MiSeq run up to 125 samples for a single marker could be sequenced at once.

#### Sequencing

Sample library pools were denatured and sequenced on an Illumina MiSeq (San Diego, CA) at OSU CDLS using the Illumina MiSeq Reagent Kit v.3 (600-cycle) (Cat_No:MS-102-3003) following the "Illumina 16S Metagenomic Sequencing Library Preparation" guide. Specifically, libraries were diluted to 8 pM and run with 10% PhiX.

##### Preparation
1. Turn on 1.7mL heat block and set to 96°C
2. That MiSeq reagent cartridge at room temperature.
3. Create ice-water bath using 3:1 ice to water ratio.

##### Denature DNA
1. Mix 4 nM pooled library (5 μl) 0.2 N NaOH (5 μl) in new microcentrifuge tube.
2. Set aside the remaining 0.2 N NaOH dilution for PhiX. (Use within 12 hours)
3. Briefly vortex briefly sample solution. Then centrifuge at 280 × g for 1 minute at room temperature.
4. Incubate on benchtop for 5 minutes.
5. Combine 10µL Denatured DNA with 990 µL pre-chilled HT1 buffer to generate a 20 pM denatured library in 1mM NAOH.
6. Place denatured DNA on ice.

##### Dilute Denatured DNA
1. Add 240 µL 20 pM denatured library to 360 µL pre-chilled HT1 to make 8 pM final concentration denatured DNA library.
2. Briefly mix (flick/tap/invert) and spin the sample
3. Place the final denatured library on ice.

##### Denature and Dilution of PhiX Control
1. Add 2 μl 10 nM PhiX library to 3 µL 10 mM Tris pH 8.5 in a new microcentrifuge tube to make a 4nM PhiX library
2. Add 5 µL 4 nM PhiX library to 5µL 0.2 N NaOH to make a 2 nM PhiX library solution
3. Briefly vortex and spin
4. Incubate on benchtop for 5 minutes.
5. Combine 10µL Denatured PhiX with 990 µL pre-chilled HT1 buffer to generate a 20 pM denatured PhiX library in 1 mM NAOH.
6. Add 240 µL 20 pM denatured PhiX library to 360 µL pre-chilled HT1 to make 8 pM final concentration denatured PhiX library.
7. Briefly mix (flick/tap/invert) and spin the sample
8. Place the final denatured library on ice.

##### Combine Amplicon Library and PhiX Control
1. Add 30 µL denatured and diluted PhiX control library to 570 µL of denatured and diluted amplicon library
2. Place on ice until ready to run the MiSeq cartridge
3. Incubate at 96˚C for 2 minutes. Only start this step when ready to run the flow cell.
4. Mix by inverting and place into the ice-water bath
5. Incubate in ice-water bath for 5 minutes


##### Quality Control
Necessary quality control measures were performed at the sequencing center before sequencing.

### Basic troubleshooting guide

- Use a unique index for each sample. Multiple different markers (e.g. MiFish Teleost 12S, 16S Universal Parada, Leray CO1) from different PCRs can be pooled together for sequencing. Similar markers (e.g. MiFish Elasmobranch 12S and Teleost 12S) will be difficult to disentangle bioinformatically.
- See the _16S Metagenomic Sequencing Library Preparation
Preparing: 16S Ribosomal RNA Gene Amplicons for the Illumina MiSeq System_ for detailed recommendations and advanced troubleshooting.


## REFERENCES
1. Amplicon, P. C. R., Clean-Up, P. C. R., & Index, P. C. R. (2013). 16s metagenomic sequencing library preparation. Illumina: San Diego, CA, USA, 21.

## APPENDIX A: DATASHEETS
See [PCR Protocol Sheet](https://github.com/marinednadude/NOAA-PMEL-OME-MiFish-mod-Universal-Teleost-12S-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME%20MiFish%20mod%20Universal%20Teleost%2012S%20PCR%20Protocol%20Sheet.xlsx)
