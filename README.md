# Mini-C++-Compiler
Mini C++ Compiler with if, if-else, while and for constructs

Implemented a mini C++ compiler with the for the major constructs like:
1) expressions and conditions
2) if clause
3) if-else clause
4) else-if clauses
5) for loops
6) while loops
This Mini-Compiler performs syntax analysis to verify if the sequence of tokens in the input forms a valid sentence based on the definition of the C++ grammar provided in the yacc file. It checks for the semantic validity of the given input. Appropriate rules are written to validate type checking, to ensure that all variables are declared before use and to catch any variable redeclarations. It also catches any bracket mismatch and correctly records the scope of each variable.

Design strategy and Implentation details involve:
1) SYMBOL TABLE CREATION
2) INTERMEDIATE CODE GENERATION
3) CODE OPTIMIZATION
4) ERROR HANDLING

Working Example:



