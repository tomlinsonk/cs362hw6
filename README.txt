Authors: Chae Kim and Kiran Tomlinson

To run the genome read simulator:
$ ./simulate.sh fasta_file coverage read_length error_rate

To run the assembler:
$ ./assemble.sh reads_file k [-d to write dot files]

To view the graphs using dot, after running assembler with -d:
$ ./dot.sh


Known bugs:
1. ./dot.sh assumes the existence of the .dot files generated by assemble.py