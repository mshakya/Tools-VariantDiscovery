# Tools-SNPs
A list of awesome tools and pipelines that calls variants from NGS data. I listed them into categories based on their original design or implementation (in published papers).

Human
-------------------------------------
* [freebayes](https://github.com/ekg/freebayes): Bayesian haplotype-based polymorphism discovery and genotyping.
* [LoFreq](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3526318/): LoFreq models sequencing run-specific error rates to accurately call variants occurring in <0.05% of a population.
* [VarScan 2](https://github.com/Jeltje/varscan2): Detects somatic mutations and copy number alterations (CNAs) from exome data.
* [GATK](https://software.broadinstitute.org/gatk/best-practices/)
* [DISCOVAR](https://software.broadinstitute.org/software/discovar/blog/): A new variant caller capable of assembling small genomes.
* [Platypus](https://github.com/andyrimmer/Platypus): Platypus is designed for efficient and accurate variant-detection.
* [SGA](https://github.com/jts/sga/blob/master/src/bin/sga-call-variants.pl)

Prokaryotes
-------------------------------------
* [VarCap](https://github.com/ma2o/VarCap): a workflow for the reliable prediction of different types of variants even at low frequencies
* [freebayes](https://github.com/ekg/freebayes): Bayesian haplotype-based polymorphism discovery and genotyping.
* [LoFreq](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3526318/): LoFreq models sequencing run-specific error rates to accurately call variants occurring in <0.05% of a population.
[VarScan 2](https://github.com/Jeltje/varscan2): Detects somatic mutations and copy number alterations (CNAs) from exome data.
* [breseq](https://github.com/barricklab/breseq): breseq finds mutations relative to a reference sequence in short-read DNA re-sequencing data for haploid microbial-sized genomes.
* [GATK](https://software.broadinstitute.org/gatk/best-practices/): use `HaplotypeCaller`, calls germline SNPs and indel.

Viruses (Eukaryotic)
-------------------------------------
* [LoFreq](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3526318/): LoFreq models sequencing run-specific error rates to accurately call variants occurring in <0.05% of a population.

Eukaryotes
-------------------------------------
* [Platypus](https://github.com/andyrimmer/Platypus): Platypus is designed for efficient and accurate variant-detection.

*Disclaimer*: Some of these tools might have already been used in categories where its not listed. It is likely not listed due to lack of updating this list or it did not show up in the first page of google result or was not exclusively mentioned in the abstract or readme files.