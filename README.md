XML-File-Error-Parsing
======================

Lex and Yacc Program to detect errors in an XML File

XML Parser for Syntax Checking


How to run
Step1: Copy all the test XML files in folder.

Step2: cd into that folder.

Step3: Compile the lex file
       flex lexfile.l
	
Step4: Compile the yacc file // not done .. we compile and run c++ file which detect error
       yacc -d yaccfile.y

Step5: g++ y.tab.c lex.yy.c -lfl

Step6 : ./a.out [filename.xml]
	eg : ./a.out input1.xml
	     ./a.out input2.xml
	     
Step7: The list of all errors which occured during parsing are displayed
	     


