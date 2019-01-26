# CS4380-Assembler-VM-Multithreaded

An assembler which takes a .asm file and performs a two pass operation on it. The first pass loads a symbol table with all indentifiers in the assembly file. The second pass loads memory with all of the data members and the instructions in the file. 

The virtual machine then runs all of the instructions that were put into memory by the assembler. Supports multithreading with RUN, which starts a new thread, and LCK, ULCK, and mutex support. 
