# dinoflag-alt-splice
This repository contains modified scripts for gene-prediction methods to recognise the non-canonical (alternative) intron splice sites, tailored for dinoflagellate genomes.

**AUGUSTUS_modified_files.tar.gz**: the modified scripts for AUGUSTUS (7 files): 
~~~~
etraining.cc
geneticcode.hh
introntrain.cc
properties.cc
properties.hh
types.cc
types.hh
~~~~
The modified/added lines in these scripts are commented with `changed for GA-AG splice site - YONG LI`, or `added for GA-AG splice site - YONG LI`. These lines can be modified accordingly in the corresponding files available from the ab initio gene prediction package of AUGUSTUS (http://bioinf.uni-greifswald.de/augustus/).

**PASA_modified_files.tar.gz**: the modified script for PASA (1 file): 
~~~~
CDNA_alignment.pm
~~~~
The modified lines in this PERL module are commented with `add GA-AG for Symbiodinium - YONG LI` or `add revcomp of GA-AG for Symbiodinium - YONG LI`. These lines can be modified accordingly in the corresponding PERL module of the same name in PASA (https://github.com/PASApipeline/PASApipeline)

These scripts were originally available at http://smic.reefgenomics.org/download/. These scripts have been used and cited in the following papers:
1. Aranda et al. (2016) Genomes of coral dinoflagellate symbionts highlight evolutionary adaptations conducive to a symbiotic lifestyle. Scientific Reports 6: 39734. (https://doi.org/10.1038/srep39734)
2. Liu et al. (2018) Symbiodinium genomes reveal adaptive evolution of functions related to coral-dinoflagellate symbiosis. Communications Biology 1: 95. (https://doi.org/10.1038/s42003-018-0098-3)
