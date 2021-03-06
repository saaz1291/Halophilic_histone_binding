# Periodicity_of_nucleosome_sequences_combined.Rmd

Evaluates the periodicity of nucleosome sequences. Location of these nucleosomes is taken from published data (Widom 2012 Nature, Maruyama 2013 EMBO, Ammar 2012 eLife) for yeast, Thermococcus kodakarensis, and Hfx volcanii nucleosomes respectively. All 3 were generated using MNase-Seq (sequences in the genome protected, preumably by nucleosomes, from digestion by micrococcal nuclease). Supplementary tables from these papers contained information regarding the centres of each nucleosome detected. The sequence around each nucleosome centre is taken and concatenated; the resultant sequence is checked for periodicity as described in the Periodicity_genomewide/README.md and Periodicity_genomewide/autoFT2_combined.Rmd files. Detailed information is commented throughout the codes.

Input dependencies: Supplementary tables from the 3 papers containing nucleosome centres, genome sequence for the 3 species downloaded from NCBI. R codes: convertseqtobinary_AATTTA2.R, convertnucleosomecentrestobinary.R, convertnucleosomecentrestobinary2.R, convertnucleosomecentrestobinary3.R.

Library dependencies: 
pracma_2.3.3 seqinr_4.2-8 readxl_1.3.1
