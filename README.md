# mutcount

- Generate count tables for all screens included.
- Only exact matches of each mutant will be counted.
- This tool is specifically designed for data listed in the Nature Communications paper 'Phosphosite Scanning reveals a complex phosphorylation code underlying CDK-dependent activation of Hcm1'


## usage
`python mutcount.py <name.R1.fastq.gz> <name.R2.fastq.gz> <output_name> <FMT>`

## example
`python mutcount.py example.R1.fastq.gz example.R2.fastq.gz test WA`

## FMT (Library Format)
- AE: library containing all A and E substitutions at each phosphosite, in all possible combinations, in addition to the completely the wild type sequence
- WA: library containing the wild type sequence (W) or A substitutions at each phosphosite, in all possible combinations, in addition to the completely wild type sequence
- WE: library containing the wild type sequence (W) or E substitutions at each phosphosite, in all possible combinations, in addition to the completely wild type sequence

