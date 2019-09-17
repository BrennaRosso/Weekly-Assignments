grep ">" WA1.fa | wc -l
This will count the number of sequences in the .fasta file by counting the number of ">" at the begining of the lines
cat WA1.fa | head -7 | tail -5
This pipe will produce the first seven sequences and the last five sequences and prints whats common to them both
sort WA1.fa | uniq 
This pipe will sort the given values and print only the unique ones
