Reference Information
=====================

Provenance for this README
--------------------------

* File name: README_Dataset-PitcherPlantMosquitoMicrobiota_v1.0.0.txt
* Authors: Kerri L. Coon
* Other contributors: Aldo A. Arellano
* Date created: 2023-01-11
* Date modified: 2023-01-11

Dataset Version and Release History
-----------------------------------

* Current Version:
  * Number: 1.0.0
  * Date: 2023-01-11
  * Persistent identifier: DOI: 10.5061/dryad.w0vt4b8sg
  * Summary of changes: n/a

* Embargo Provenance: n/a
  * Scope of embargo: n/a
  * Embargo period: n/a

Dataset Attribution and Usage
-----------------------------

* Dataset Title: Data for the article "Bacterial communities in carnivorous pitcher plants colonize and persist in inquiline mosquitoes"

* Persistent Identifier: https://doi.org/10.5061/dryad.w0vt4b8sg

* Dataset Contributors:

  * Creators: Aldo A. Arellano and Kerri L. Coon

* Date of Issue: 2023-01-11

* Publisher: University of Wisconsin-Madison

* License: Use of these data is covered by the following license:
  * Title: CC0 1.0 Universal (CC0 1.0)
  * Specification: https://creativecommons.org/publicdomain/zero/1.0/; the authors respectfully request to be contacted by researchers interested in the re-use of these data so that the possibility of collaboration can be discussed. 

* Suggested Citations:

  * Dataset citation:
    > Arellano, A.A. and K.L. Coon. 2022. Data for the article "Bacterial communities in carnivorous pitcher plants colonize and persist in inquiline mosquitoes", Dryad, Dataset, https://doi.org/10.5061/dryad.dfn2z354z.

  * Corresponding publication:
    > Arellano, A.A. and K.L. Coon. 2022. Bacterial communities in carnivorous pitcher plants colonize and persist in inquiline mosquitoes. Animal Microbiome 4:13. DOI: 10.1186/s42523-022-00164-1

Contact Information
-------------------

  * Name: Kerri L. Coon
  * Affiliations: Department of Bacteriology, University of Wisconsin-Madison
  * ORCID ID: https://orcid.org/0000-0002-2701-5195
  * Email: kerri.coon@wisc.edu
  * Address: e-mail preferred

- - -

Additional Dataset Metadata
===========================

Acknowledgements
----------------

* Funding sources: This work was supported by awards from the National Science Foundation (2019368) and U.S. Department of Agriculture (2018-67012-29991), as well as start-up funds from the University of Wisconsin-Madison (to KLC). AAA was further supported by a National Institutes of Health Biotechnology Training Fellowship (NIGMS-5-T32 GM135066), a Howard Hughes Medical Institute Gilliam Fellowship (GT14993), and the SciMed Graduate Research Scholars Program at UW-Madison.

* Other: We thank Erica Young, Gretchen Meyer, and the University of Wisconsin-Milwaukee Field Station for assistance with field sampling at the Cedarburg Bog State Natural Area in Wisconsin. We also thank William Bradshaw and Christina Holzapfel (University of Oregon) for assistance in establishing our laboratory colony of W. smithii, Candace Davison and the Radiation Science & Engineering Center at The Pennsylvania State University for assistance in preparing irradiated diet for use in our experiments, Garret Suen (UW-Madison) for assistance with sequencing, and members of the Coon laboratory at UW-Madison (Andrew Sommer, Holly Nichols, and Journey Prack) for assistance with maintaining our W. smithii laboratory colony and microscopy.

Dates and Locations
-------------------

* Dates of data collection: Field samples collected June-August 2020

* Geographic locations of data collection: Fieldwork conducted in the Cedarburg Bog Natural Area, Saukville, WI (see publication for more details)

* Other locations pertaining to dataset contents: Wet lab work performed at the University of Wisconsin-Madison. Samples were sequenced at the University of Wisconsin-Madison DNA Sequencing Facility.

- - -

Methodological Information
==========================

* Methods of data collection/generation: see manuscript for details

- - -

Data and File Overview
======================

Summary Metrics
---------------

* File count: 9
* Total file size: 809 KB
* Range of individual file sizes: 7 KB - 444 KB
* File formats: .csv, .rds, .txt

Table of Contents
-----------------

* all_annotated_statistical_analyses_code.txt
* CNV_vs_Gnoto_Wing_Measurements.csv
* dataframe_for_diversity_hypothesis_tests_FULL.csv	
* CNV_vs_Gnoto_Pupation_Day.csv
* Isolates_Pupation_Day.csv
* relative_abundance_for_stacked_bar_FIELD_LAB.csv
* relative_abundance_for_stacked_bar_LAB.csv
* phyloseq_full_analysis_set.rds
* decontam lab reads no outliers.rds

Setup
-----

* Unpacking instructions: n/a

* Relationships between files/folders: see file descriptions

* Recommended software/tools: R version 4.1.1

- - -

File/Folder Details
===================

Details for: all_annotated_statistical_analyses_code.txt
---------------------------------------

* Description: The only file that you need to open. Loads datasets and has code for reproducing all statistical analyses in the manuscript. 
	
* Format(s): .txt

* Size(s): 22 KB

* Dimensions: 670 lines


Details for: CNV_vs_Gnoto_Wing_Measurements.csv
---------------------------------------

* Description: A comma-delimited file containing the data needed to conduct the wing length comparisons for Fig. S5

* Format(s): .csv

* Size(s): 25 KB

* Dimensions: 411 rows x 4 columns

* Variables:
  * Treatment: adult treatment group; "Conventionally Reared" = adults that emerged from trays containing larvae reared conventionally in our standard laboratory colony, "Reintroduced Community" = adults that emerged from experimental plates containing gnotobiotic larvae recolonized with the mixed community of bacteria present under conventional rearing conditions (i.e., their ‘native microbiota’)
  * Cage_or_Plate: delineates adults derived from up to four independent trials
  * Sex: delineates "male" vs. "female" adults
  * Wing_Length: forewing length (in mm) for each adult


Details for: dataframe_for_diversity_hypothesis_tests_FULL.csv	
---------------------------------------

* Description: A comma-delimited file containing the data needed to conduct the inter-replicate alpha diversity comparisons for Fig. 6B. Contains "Day 5" data for microcosms generated using both lab- and field-derived bacteria.

Differential diversity among full set of samples (lab vs field).

* Format(s): .csv

* Size(s): 7 KB

* Dimensions: 76 rows x 9 columns

* Variables:
  * Sample ID: unique sample identifier
  * Shannon Sample-Wise: sample-wise shannon's index estimate for each sample
  * Shannon Error: shannon estimation error for each sample
  * Breakaway Estimate of Richness: breakaway richness estimate for each sample
  * Breakaway Error: breakaway richness estimation error for each sample
  * category1: "water" = water samples (lab or field), "larvae" = larval samples (lab or field), "new_adult" = newly emerged adult samples (lab only), "mature_adult" = mature adult samples (lab only)
  * category2: "field water" = field-derived water samples, "field larvae" = field-derived larval samples, "lab water" = lab-derived water samples, "lab larvae" = lab-derived larval samples, "newly emerged males" = newly emerged adult male samples (lab-reared), "newly emerged females" = newly emerged adult female samples (lab-reared), "mature males" = mature adult male samples (lab-reared), "mature females" = mature female adult samples (lab-reared)
  * category3: "field water" = field-derived water samples, "field larvae" = field-derived larval samples, "lab water" = lab-derived water samples, "lab larvae" = lab-derived larval samples, "new_adult" = newly emerged adult samples (lab-reared), "mature_adult" = mature adult samples (lab-reared)
  * field_lab: delineates samples derived from the "lab" vs. "field"


Details for: CNV_vs_Gnoto_Pupation_Day.csv
---------------------------------------

* Description: A comma-delimited file containing the data needed to estimate the average time to pupation of gnotobiotic larvae recolonized with the mixed community of bacteria present under conventional rearing conditions (i.e., their ‘native microbiota’)

* Format(s): .csv

* Size(s): 34 KB

* Dimensions: 1349 rows x 3 columns

* Variables:
  * ID: unique pupa identifier
  * Treatment: pupa treatment group; "Conventionally Reared" = pupae from trays containing larvae reared conventionally in our standard laboratory colony, "Reintroduced Community" = pupae from experimental plates containing gnotobiotic larvae recolonized with the mixed community of bacteria present under conventional rearing conditions (i.e., their ‘native microbiota’)
  * Day_Pupation: development time (in days) for each pupa from egg hatching to pupation


Details for: Isolates_Pupation_Day.csv
---------------------------------------

* Description: A comma-delimited file containing the data needed to conduct the development time comparisons for Fig. 5b

* Format(s): .csv

* Size(s): 12 KB

* Dimensions: 659 rows x 2 columns

* Variables:
  * Genus: larval treatment group; "Native microbiota" = gnotobiotic larvae recolonized with the mixed community of bacteria present under conventional rearing conditions, all other treatments = gnotobiotic larvae colonized by one of six bacterial isolates (C. pseudoglaebosa, Chromobacterium, E. coli K12, Elizabethkingia, Paraburkholderia, or Rhizobium)
  * Day_Pupation_27: development time (in days) for each larva from egg hatching to pupation; blank cells indicate larvae that did not pupate within 27 days after egg hatching


Details for: relative_abundance_for_stacked_bar_FIELD_LAB.csv
---------------------------------------

* Description: A comma-delimited file containing the data needed to generate the taxa bar plots in Fig. 1
		
* Format(s): .csv

* Size(s): 151 KB

* Dimensions: 1799 rows by 8 columns

* Variables:
  * SampleID: unique sample identifier
  * category1: delineates sample derived from "water" vs. "larvae"
  * category2: "field water" = field-derived water samples, "field larvae" = field-derived larval samples, "lab water" = lab-derived water samples, "lab larvae" = lab-derived larval samples
  * Kingdom: level 1 taxonomy for bacterial orders in Fig. 1
  * Phylum: level 2 taxonomy for bacterial orders in Fig. 1
  * Class: level 3 taxonomy for bacterial orders in Fig. 1
  * Order: bacterial orders in Fig. 1
  * value: relative abundance of each bacterial order in each sample


Details for: relative_abundance_for_stacked_bar_LAB.csv
---------------------------------------

* Description: A comma-delimited file containing the data needed to generate the taxa bar plots in Fig. 3
		
* Format(s): .csv

* Size(s): 49 KB

* Dimensions: 625 rows by 7 columns

* Variables:
  * Type: "eggs", "water" = water samples, "larvae" = larval samples, "newly-emerged adults" = newly emerged adult samples, "mature adults" = mature adult samples
  * Sample_Type: "CNV" = egg masses oviposited by conventionally reared females, "STR" = egg masses oviposited onto sterile filter paper in sterile water by mature adult females from surface-sterilized pupae, "male" = adult male samples, "female" = adult female samples; blank cells indicate water or larval samples
  * Kingdom: level 1 taxonomy for bacterial orders in Fig. 3
  * Phylum: level 2 taxonomy for bacterial orders in Fig. 3
  * Class: level 3 taxonomy for bacterial orders in Fig. 3
  * Order: bacterial orders in Fig. 3
  * value: relative abundance of each bacterial order in each sample


Details for: phyloseq_full_analysis_set.rds
---------------------------------------

* Description: Phyloseq object containing the ASV table (taxa abundances), sample metadata, taxonomy table (mapping between ASVs and higher-level taxonomic classifications), and phylogenetic tree (relations between the taxa) used to produce summary tables and all figures in the manuscript
		
* Format(s): .rds

* Size(s): 444 KB


Details for: decontam lab reads no outliers.rds
---------------------------------------

* Description: Phyloseq object containing the ASV table (taxa abundances), sample metadata, taxonomy table (mapping between ASVs and higher-level taxonomic classifications), and phylogenetic tree (relations between the taxa) used for all differential abundance analyses/significance tests
		
* Format(s): .rds

* Size(s): 65 KB


- - -
END OF README