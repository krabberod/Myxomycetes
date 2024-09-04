# Primerdesign
- Challenge: To design primers specifically for myxomycetes, suitable for long-read (PacBio) sequencing. There are some primers published that cover the first part of 18S, but we lack a candidate in 28S. 

# Published primers

The list is from Schnittler et al. (2017), with som addition by me
  
### Forward 
| Primer        | Sequence 5' -> 3'         | Appr. bindingsite | Description | Taxonomic range                                                                                                       |
| ------------- | ------------------------- | ----------------- | ----------- | --------------------------------------------------------------------------------------------------------------------- |
| S1 (standard) | AACCTGGTTGATCTGCC         |                   |             | dark-spored, all genera except some Stemonitales, but amplifies as well some other protists (Fiore-Donno et al. 2008) |
| S3b           | TCTCTCTGAATCTGCCWAC       |                   |             | dark-spored, some bright-spored, specific for myxomycetes (Hoppe & Schnittler 2015)                                   |
| NUSSUF3       | CCTGCCAGAATCATATGCTGTCC   |                   |             | bright-spored myxomycetes (Feng & Schnittler 2015)                                                                    |
| NUSSUF20      | TGACAACCTGGTTGATCTGG      |                   |             | dark-spored myxomycetes (Feng et al. 2016)                                                                            |
| S1A           | CTGGTTGATCCTGCTAGAAG      |                   |             | bright-spored myxomycetes, especially Trichiales (Dagamac 2016)                                                       |
| SF2Dark       | GTTGATCCTGCCAGTAGTGT      |                   |             | dark-spored myxomycetes (Fiore-Donno et al. 2016)                                                                     |
| S2            | TGGTTGATCCTGCCAGTAGTGT    |                   |             | dark-spored myxomycetes (Fiore-Donno et al. 2008)                                                                     |
| SF12          | TCYTAAAGAYTAAGGGATGCATGYC |                   |             | Lycogala epidendrum and probably other bright-spored myxomycetes (Liu et al. 2014)                                    |
| PHYS-5        | GGAAGCAGAAGTCGTAACAAGG    |                   |             | (Martin et al 2003)                                                                                                   |
| PHYS-2        | CTGCGCTCTTCATCGAAGC       |                   |             | (Martin et al 2003)                                                                                                   |
| PHYS-3        | GCATCGATGAAGAACGCAG       |                   |             | (Martin et al 2003)                                                                                                   |
| PHYS-4        | TTCCTCCGCTGACTAATATGC     |                   |             | (Martin et al 2003)                                                                                                   |
### Reverse
These are not as interesting since they do not bind to the 28S gene. 

| Primer          | Sequence 5' -> 3'         | Appr. bindingsite | Description | Taxonomic range                                                                                                                                                            |
| --------------- | ------------------------- | ----------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| S19R (standard) | TGCTGGCACCAGACTTGT        |                   |             | dark-spored and some bright-spored genera, but covers in part the intron insertion site S516, which may give problems in genera with this intron (Fiore-Donno et al. 2008) |
| S30shortR       | CCCTTATCCTGTACCCGT        |                   |             | dark-spored, some bright-spored, rather specific for myxomycetes (unpubl.)                                                                                                 |
| NUSSUR4         | ACCAGACTTGTCCTCCAATTGTTAC |                   |             | bright-spored myxomycetes (Feng & Schnittler 2015)                                                                                                                         |
| SR4Bright       | TGCTGGCACCAGACTTGT        |                   |             | bright-spored myxomycetes (Fiore-Donno et al. 2012)                                                                                                                        |
| NUSSUR13        | ACCAGACTTGTCCTCTAATTGTTAC |                   |             | dark-spored myxomycetes (Feng et al. 2016)                                                                                                                                 |
| SRHem1          | GGGGTTTAAAGGTCCCC         |                   |             | bright-spored myxomycetes, especially Trichiales (Dagamac 2016)                                                                                                            |
| S31R            | ATCTCTCAGGCCACTCTCCAGG    |                   |             | dark-spored, specific for myxomycetes (unpubl.)                                                                                                                            |
| SU19R           | GACTTGTCCTCTAATTGTTACTCG  |                   |             | dark-spored myxomycetes (Fiore-Donno et al. 2012)                                                                                                                          |
| SR19Dark        | GTCCTCTAATTGTTACTCGAD     |                   |             | dark-spored myxomycetes (Fiore-Donno et al. 2016)                                                                                                                          |
| SP03r           | TCCTCTAATTGTTACTCGAG      |                   |             | dark-spored myxomycetes (Kamono et al. 2013)                                                                                                                               |

References
Schnittler, M., Shchepin, O. N., Dagamac, N. H. A., Dahl, M. B. & Novozhilov, Y. K. Barcoding myxomycetes with molecular markers: challenges and opportunities. Nova Hedwig. 104, 323–341 (2017).
Martín MP, Lado C, Johansen S. Primers are designed for amplification and direct sequencing of ITS region of rDNA from Myxomycetes. Mycologia. 2003 May-Jun;95(3):474-9. doi: 10.1080/15572536.2004.11833092. PMID: 21156636.

### Other primers
These are designed from the small portion of data we got from the first run of the PacBio sequencing.
| Primer    | Sequence 5' -> 3'    | Appr. bindingsite | Description                                                          | Taxonomic range |
| --------- | -------------------- | ----------------- | -------------------------------------------------------------------- | --------------- |
| LSU_Myx_1 | TCCTTGCTTACCAACRTGGC |                   | Designed on a short conserved region at the start of 28S (AKK, 2024) | unknown         |
| LSU_Myx_2 |                      |                   |                                                                      |                 |
