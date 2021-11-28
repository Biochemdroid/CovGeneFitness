# SARS_CoV_2-Fitness

Uses the SpikeProSARS-CoV-2 by Fabrizio Pucci to determine the evolutionary fitness of different SARS-CoV-2 Variants. 
This code enables any SARS-CoV-2 nucleotide sequence to predict the inter-human transmissibility, infectivity based on the affinity of the spike protein with the ACE2 receptor, and viral evasion of the immune system. The reference COVID-19 sequence gets a fitness Θ = 1. The greater the Θ value the more infectious and transmittable the virus is predicted to be, along with a greater chance of escaping antibody neutralization. The results are not binding and are only predictions.

The SARS_CoV_2-Fitness suite allows a more rapid interface for truncating any genome to the spike protein region (+/- 100 flanking nucleotides), Aligning the sequence against a reference sequence, and then translating the aligned nucleotide sequence into an amino acid sequence. Moreover, it gives instructions for how to set up and run the SpikePro interface.

References: 
https://www.biorxiv.org/content/10.1101/2021.04.11.439322v1
https://github.com/3BioCompBio/SpikeProSARS-CoV-2
