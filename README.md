# Bioinformatics tools (Portfolio)

### Class Library

House all the classes called upon by the scripts.

### exonerate

Uses the command line exonerate tools to call exonerate from the command line with a protein sequence FASTA file query on a genomic sequence FASTA database

### create_blast_database

Uses the command line BLAST tools from NCBI to convert a genomic sequence FASTA file into a blast database.

### parallize_tblastn

Splits a FASTA file containing multiple protein sequences into multiple FASTA files containing n number of protein sequences. The multiple FASTA files are then used in parallize_tblastn as queries. 

### parallize_tblastn

A stand-alone script which uses pythons multiprocessing library to make TBLASTN calls from the command line, in parallel, between multiple protein sequence FASTA files and a genomic sequence FASTA database.




