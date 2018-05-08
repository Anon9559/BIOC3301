# BIOC3301
This repository contains the scripts used in my BIOC3301 project

1) Core Analysis: This folder contains all the relevant scripts for preprocessing of data. The scripts in this folder were carried out on all years with the excpetion of "Join paired ends", which was only carried out in the 2018 dataset. This folder should be viewed first. The BIOM tables produced for 2016, 2017 and 2018 from this core pipeline are used as inputs for the scripts in the "Merging files" folder

2) Merging Files: This folder contains scripts that a) merged the OTU tables from the respective years b) merged the three mapping files and c) removal of erroneous 2018 samples. The output of these scripts is this corrected_merged_otu_table. This is the merged OTU table for 2016 2017 and 2018 but with the 2018 samples outside of Gordon Square gardens removed 

3) 16-17-18 Core microbiome analysis: This folder contains the scripts that were used in the analysis of the 16-17-18 dataset. It also contains a folder "stats" which contains scripts for all stats analyses carried out on this year set 

4) 16-17 Core microbiome analysis: This folder contains the scripts used in the analysis of the 16-17 dataset. These scripts are identical to the ones used for analysis of 17-18 and 16-18 datasets, the only difference being the minimum sampling depth argument that is passed to the "CDA on Core 50 Microbiome table" script. This number varies between datasets and is based on the output of "Summmarise core microbiome table" in all cases. The lowest number of sample counts is used.

The "Stats" folder within the 16-17 Core microbiome analyis folder contains the scripts used statistically analyse resultant data. These scripts are also reflective of the stats scripts used in the 16-18 and 17-18 datasets, the only thing that is different in all cases are the file paths and output paths 
