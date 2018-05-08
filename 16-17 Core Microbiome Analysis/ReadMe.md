16-18 CORE MICROBIOME ANALYSIS

1) The script "Remove 2018 Samples" was used to remove all 2018 samples in the corrected_merged_otu table. 

2) The "summarise 16 17 biom table" script was used to summarise the resultant biom table, once the 2018 samples had been removed 

3)The "compute Core Microbiome" code was used to compute the core microbiome of the relevant biom table. A 50% threshold was set

4)The resultant biom table was summarised using the "Summarise core microbiome table" script. The minimum sample count found from this script was used in the core diversity analysis

5) The "summarise taxa of core microbiome table" script was used to filter the core 50 biom table by L2 and L3 taxonomy levels

6) The "Core diversity analysis of core microbiome" script was used to conduct core diversity analysis on the core 50 microbiome table

7) statistical tests were carried out on both the L2 and L3 filtered core microbiome tables. The scripts for these can be found in the "stats folder"
