# GAPDH-Primer-Design
In-silico design and specificity analysis of GAPDH PCR primers using NCBI Primer-BLAST
Activity 1: Virtual Design and Specificity Testing of GAPDH PCR Primers

Objective-

The aim of this activity was to design specific PCR primers for the human GAPDH gene and evaluate their quality and specificity using NCBI Primer-BLAST.

Target Gene Information-

- Gene Name: GAPDH (Glyceraldehyde-3-Phosphate Dehydrogenase)
- Organism: Homo sapiens
- Gene ID: 2597
- mRNA Accession: NM_002046.7
- Chromosome: 12

Tools Used-

- NCBI Gene Database
- NCBI Nucleotide Database
- NCBI Primer-BLAST

Methodology-

1. The GAPDH mRNA sequence (NM_002046.7) was retrieved from the NCBI Nucleotide database.
2. The FASTA sequence was used as input in Primer-BLAST.
3. Primer design parameters were set as follows:
- Product size range: 70–200 bp
- Melting temperature (Tm): 57–63°C
- Primers spanning exon–exon junction to avoid genomic DNA amplification.
4. Primer specificity was checked against the human genome (Homo sapiens).
5. Primer quality was evaluated based on:
- Melting temperature (Tm)
- GC content
- Self-complementarity
- Product size

Selected Primer Pair (Primer Pair 1)
- Forward Primer (5' → 3') :
  TCGGAGTCAACGGATTTGGT

- Reverse Primer (5' → 3') :
  TTCCCGTTCTCAGCCTTGAC

| Parameter               | Forward Primer | Reverse Primer |
| ----------------------- | -------------- | -------------- |
| Length                  | 20 bp          | 20 bp          |
| Tm                      | 59.32 °C       | 59.97 °C       |
| GC Content              | 50%            | 55%            |
| Self-Complementarity    | 3.0            | 3.0            |
| 3′ Self-Complementarity | 1.0            | 1.0            |

Expected PCR Product Size: 181 bp

Specificity Analysis-
Primer-BLAST results showed that the selected primer pair successfully amplifies the GAPDH gene with high specificity. Although amplification was also observed in different transcript variants of GAPDH, no significant off-target amplification was detected elsewhere in the human genome.

Conclusion-

The designed primer pair demonstrates:
- Optimal Tm and GC content
- Low self-complementarity (minimal primer-dimer risk)
- Specific amplification of the human GAPDH gene

Therefore, this primer pair is suitable for PCR/qPCR applications.

Files Included-
- Primer-BLAST result screenshots
- Primer sequence and parameter details

Author:
Ayushi Sharma
B.Tech Biotechnology (2nd Semester)
