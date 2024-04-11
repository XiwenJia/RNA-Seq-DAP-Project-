# RNA-Seq (DAP) Project

This is a RNA-Seq parsing toolkit for the NERPE-Seq method. It has the following functionalities:

1. Data preprocessing (quality score filter, R1 and R2 read check, and FASTQ trimming). 
2. Compute normalization factors for the control samples (AUCG and DUCG systems).
3. Grouping the products as complementary, mismatched, or unincorporated.
4. Compute and plot yield & fidelity.
5. Generate heatmaps for complementary products (position-dependent nucleobase and bridged dinucleotides distribution).
6. Generate heatmaps for mismatched template: product pairs.
7. Calculate probability of extension after a complementary/mismatched base pair, and stalling factor.
8. Predict the next nucleobase in the product sequence.  
