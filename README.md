# mutcount
- Generate count tables for all screens included.
- Only exact match of the designed mutations will be counted
- This tool is specifically designed for data listed in the nature communication paper 'Phosphosite Scanning reveals a complex phosphorylation code underlying CDK-dependent activation of Hcm1'

## usage
`python mutcount.py <name.R1.fastq.gz> <name.R2.fastq.gz> <output_name> <FMT>`

## example
`python mutcount.py example.R1.fastq.gz example.R2.fastq.gz test AE`

## FMT
- AE
- WA
- WE
