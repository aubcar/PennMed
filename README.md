# PennMed - Bioinformatics Specialist 
Repository for proficiency exam

Part 1

PM_unique_AA.py

Execution
Input needs to be in an extended bed file [chr,start,stop,geneid] at minimum, more columns after gene id are fine
output is to standard out but can be piped to an output file


Useage 

python PM_unique_AA.py [input bed file]

Output

Output is per Gene ID in input bed and the unique Amino acid changes 

Part 2
Requires user to imput in the primers being searched and a DNA fasta file.
Outputs if primer 1/ primer 2 match in the sequence with up to 2 missmatches per primer.
Outputs the variant region between the two primers. 

Use case 
python match.py [primer 1]  [primer 2] [fasta]
