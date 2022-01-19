# Scheme-Interpreter
This is the 4th project of UCB course 'CS61A: Structure and Interpretation of Computer Programs'

In this project, I implemented an interpreter for Scheme, a dialect of LISP, on the basis of Python3 languange.

The usage of this interpreter: open the folder in terminal, and input `python3 scheme.py`. If a prompt shows up, it means you have successfully awakened the console.

To stop using the console and go back to the terminal, press `Ctrl-D` to send EOF to the interpreter, or input `(exit)`

The coding framework was provided by UCB. I implemented several concrete functions of this interpreter,including:
- the parser, which takes in a list of tokens and converts it to a data-structure to be evaluated
- the mutual recursive logic of evaluating function and applying function, which is the core of evaluation
- user-define function and lambda function
- quotation
- managing the environment by defining the Frame class and making child frames
-  ...

