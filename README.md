# BIOC3301
This repository contains the scripts used in my BIOC3301 project


CORE ANALYSIS 
Core analysis was conducted for all three years and follows a basic pipeline that was replicated across years as outlined in the Bioc3301/Core Analysis folder

1) Due to high quality data in 2018, reads 1 and 2 were joined via the "Join paired ends" code (note that this was not done for 2016 or 2017)

2) The output of "Join paired ends" (seqprep_assembled.fastq.gz) was then inputted into the "Demultiplex" code which demultipexed the data based on Illumina barcodes and at a quality score of Q20. The demultiplex code also has a function to count the number of sequences produced from this process

3) The output output of "Demultiplex" was seqs.fna and a split_library_log.txt that contained a summary of the sequences obtained from samples 

4) Seqs.fna was inputted into the "Picking OTUs" script. This script uses the SILVA databse to assign OTUs

5) The output of the "Picking OTUs" script is a biom table. This biom table was summarised using the "Summarise Biom Table" script

6) The minimum number of sample counts (627) was passed as an argument in the "Core Diversity Analysis" script. 
