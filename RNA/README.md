This folder contains scripts referenced in my RNA-sequencing-related tutorials.

### star-summary.py

This script summarizes the final.out logs from all the samples in a STAR alignment workflow, and takes as a positional argument the directory in which those log files can be found. It outputs two different PNG files: the first shows the number of reads in each mapping category for each sample, while the second shows the different types of error rates for each sample.

### stringtie_expression_matrix.pl

This script summarizes Stringtie gene count information and normalizes them as TPM or FPKM values for tabular output. The original version of this script can be found at https://github.com/griffithlab/rnaseq_tutorial/blob/master/scripts/stringtie_expression_matrix.pl; I made a minor revision when the original stopped working on my system (maybe due to a Stringtie update) but the majority of the code is not mine.
