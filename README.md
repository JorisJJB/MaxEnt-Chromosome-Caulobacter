# MaxEnt-Chromosome-Caulobacter
Monte Carlo algorithm to derive a Maximum Entropy model of chromosome organization from Hi-C data.

For more information on this procedure, see 'Learning the distribution of single-cell chromosome
conformations in bacteria reveals emergent order across genomic scales', Messelink et al., 2021, Nature Communications.

Starting from all interaction energies equal to zero, the algorithm takes approximately two days to sufficiently converge when running on 36 cores of 2.3 GHz.

The 'configs_sample.txt' document contains a sample of 2000 chromosome configurations from the MaxEnt model for wild-type C. crescentus cells. 
Each configuration consists of 1620 monomers, with each 4th monomer representing the center of a genomic region. 
