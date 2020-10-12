# Mini-C-Compiler
Mini C++ Compiler implemented in C language
This is a Mini Compiler built for the Language C++. The compiler has been built using the language C. The tools used for building this compiler were Lex and Yacc.  It is able to efficiently compile input C++  code, while catching any error that might be present in the source code. The various phases of the compiler that have been implemented are symbol table generation, creation of the abstract syntax tree, intermediate code generation, optimization of this intermediate code and finally the conversion of this code to assembly code.
<br>
The implemented mini- compiler handles the syntax and semantics of the C++ language’s grammar. This includes catching errors such as missing semicolons, using undeclared variables and mismatched parentheses or braces. The compiler identifies these syntax errors and generates meaningful errors, so that the problem can be easily fixed. The compiler also overlooks all forms of valid comments that may be present in the code. Invalid comments of the C++ language are identified as errors and returned accordingly.

The mini-compiler handles the following constructs:
if condition
for loop
while loop

Therefore, the compiler will be able to check for the semantics and proper use of the above constructs as they appear in the source code.

