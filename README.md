# West Nile Virus Lineage 1a — Nebraska Genomic Diversification (2012–2023)

Phylogenetic analysis of West Nile virus lineage 1a genetic diversity in Nebraska, using publicly available NCBI sequence data.

## 🌳 View the interactive tree
**[Click here to explore the phylogenetic tree](https://nextstrain.org/fetch/raw.githubusercontent.com/rishichundury/wnv-nebraska-lineage1a/main/auspice/wnv-nebraska.json)**

## What this is
267 WNV genome sequences collected in Nebraska between 2012 and 2023 were pulled from NCBI, aligned with MAFFT, and used to build a time-calibrated phylogenetic tree with IQ-TREE and Nextstrain's augur pipeline. The resulting tree was analyzed for amino acid mutations in the envelope (E) protein.

## Key finding
An E protein mutation (A19T) was found to have arisen independently on two separate, well-supported branches of the tree (bootstrap support 99–100), spanning samples from 2016–2023. A permutation test (n=10,000) showed this recurrence is highly unlikely to be due to chance (p < 0.001), suggesting possible recurrent positive selection at this site.

## Tools used
NCBI Entrez API, MAFFT, IQ-TREE2, Nextstrain augur/auspice, Python (Biopython, pandas)
