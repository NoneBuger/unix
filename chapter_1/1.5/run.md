compile:  
	gcc -o std_io std_io.c -lapue
	gcc -o std_io_1 std_io_1.c -lapue

run:  
	1. ./std_io > outputfile , cp the stdin from keyboard to file <outputfile> , use ctrl + D stop the input
	2. ./std_io < inputfile > outputfile, cp the text from inputfile to outputfile
	3. ./std_io_1,  cp stdin to stdout
