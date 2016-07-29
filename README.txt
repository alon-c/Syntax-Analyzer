---=== Syntax Analyzer ===---

- Description:
This is an an "Syntax Analyzer" in LL(1) method implemented in Java.

The program takes two arguments:
1. LL(1) table file (e.g. "Table1.ll1") the first line in the file shold contain the terminals sprated with commas started by the word "terminals=". the next lines are the non-terminals or commants. see Table1.ll1 file for example.
* commant is a line wich starts with "#".
2. text file: contains the code to analyze.

The program creates a .ptree file withe the matching parse tree. you can check the diagraph of the parse tree here http://www.webgraphviz.com/.

- "how to run?" / instructions:

a. open a new project and (use Eclipse IDE) import the files: 
 - ParserMain.java
 - LexicalAnalyzer.java
 - Token.java
- SyntaxAnalyzer.java
- Node.java

then copy your input files such as <file name>[.fileType] (e.g: Table1.ll1 and input1.txt) to the main project directory (e.g: C:\Users\<User name>\workspace\<project name>).

b. in Eclipse goto 'run' menu and choose 'run configurations...'.

c. in 'Main' tab browse for your project name, then choose the 'main class' which should be 'ParserMain'.

d. goto 'Arguments' tab and in the 'Program arguments:' feild type your LL1 table file and the file to test from, e.g: "table.ll1 file.txt".

e. choose 'apply' and then 'run'.

f. the output file should be in the project directory, by the name <text to analyze file name>.ptree.

Enjoy!