# OCAML-Interpreter
Interpreter developed in OCAML that allows for basic commands.

This OCAML interpreter is designed to take simple commands in order to create programs. This was originally an assignment for BU CAS CS320. You can see the documentation [here](https://github.com/kszhao552/OCAML-Interpreter/blob/master/doc/Interpreter.pdf).

When parsing out the commands given, the program will create a list of the commands, and then execute those commands. It puts results onto a stack, and can store variables in an environment. It will add the top value of the stack to an output if there has been a log command. If there is an error, it will throw it and terminate. More information can be found in the documentation.
