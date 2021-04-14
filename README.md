#This is a proposal for BIOL_7180 Scripting for Biologists

This project was formed by Yu Sun and Boyuan Wang.


Structural variations (SVs) contribute to the variability of our genome and are often associated with disease. 
In general, people used a program called "Breakdancer" that provides genome-wide detection of structural variants from next generation paired-end sequencing reads.
Specifically, breakdancer identifies five types of structural variants(SVs): insertions(INS), deletions(DEL), inversions(INV), inter- and intra-chromosomal translocations(ITX/CTX).
Here, we sift through the raw output for each chromosome to summarize the results by a Perl script.
The aim is calculate the characteristic value of the variant type detected in each chromosome.

The file of "file.list" is conduceted by command # ls > file.list, depends on all the test data files. And that file including the name list of test data, so that could 
easy generat the files needed to run the script.
Then, just run the command # perl code.pl file.list. That would be running fast and generated a output.txt, which includ the calculation results.
