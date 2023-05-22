# C-compilor building from sratch
Skeleton: 
Given a source code the compiler will contain of three stages of processes:
1-	Lexical analysis  strings into internal token streams.
2-	Parsing  token streams into syntax tree.
3-	 Code  syntax tree into code for the target program(list of instructions) 
Skeleton (next” lexical” – program – instruction - entrance)
How computer works? 
Using virtual memory, we multiples the hard memory, program can use memory in 
1-	Text segment to store the instructions
2-	Data segment to store the initialized data
3-	Yeti segment to uninitialized data
4-	Stack segment to handle function calls
5-	Heap segment to allocate dynamically 
Registers:
1-	PC (program counter)
2-	SP (stack pointer) as we push new element SP decreases 
3-	BP (base pointer)  function calls.
4-	AC  accumulator register used to store the result of instruction.
Instruction Set: 
-	Arithmetic/logic instructions
-	Data transfer instructions
-	Interrupt instructions  branch and jump instructions 
MOV is one of the most fundamental instructions you'll met. Its job is to move data into registers or the memory, kind of like the assignment expression in C. There are two arguments in x86's MOV instruction: MOV destination, source(Intel style), source can be a number, a register or a memory address.

Function calling: 
Returning by convention to the Accumulator, Arguments as we work  
The difference between lexer and compiler?
Source code   (lexer)  token stream  (parser)  assembly
	Cause error generation we can use flex to generate lexers but here I worked from scratch. 
