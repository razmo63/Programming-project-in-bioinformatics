# Programming-project-in-bioinformatics
This is a pairwise alignment project that takes two DNA sequences as input (fasta or text files), as well as match, mismatch, and gap values provided by user, and outputs the alignment of the sequences as well as the score of best global alignment and identity score. Finally, visualize the alignment.

This program requires the following packages to run: re, numpy, matplotlib.pyplot, pandas, and IPython.display.

The two DNA sequence files provided are:
1.bronchitisvirus_strainD1466.fasta
2.bronchitisvirus_strainV1397.fasta

Also two short sequences which was used to evaluate the program are provided:
1. S1.txt
2. S2.txt

To run the program, user is to run five consecutive chunks of code. After the first chunk is run, in the second chunk, the user is asked to provide 5 inputs, the two fasta/text file names, followed by the numeric values for match, ,mismatch and gap when prompted by the program. Then, the rest of the code (chunks 3-5) is run to get the output.   