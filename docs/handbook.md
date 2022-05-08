# UwUlang handbook

### Processes
```
@PROCESS_NAME
	// process code
```
^=== definition of process  
`XwX PROCESS_NAME var` - runs process while variable isn't equal to 0  
**!!! Program runs `UWU` process when started**

### Integer operations
`0w0 var` ==> creates new/clears integer variable  
`+w+ var value` ==> adds constant integer value to integer variable  
`=w= var value` ==> sets integer variable to given constant integer value  
`*w* op1 op2 res` ==> sets result variable to sum of 2 operand variables  

### Buffer operations
`-w- buf` ==> creates new/clears buffer  
`>w> buf "text to be added"` ==> adds text fragment to buffer  
`VwV buf var` ==> sets integer variable to length of buffer  
`CwC buf index var` ==> sets variable into ASCII code of buffer symbol  
`QwQ buf var` ==> adds to buffer symbol from given in variable ASCII code  
`7w7 buf var` ==> adds to buffer string made from value in given variable  
`YwY buf var` ==> sets variable to number made from buffer symbols  
`TwT buf` ==> adds EOL symbol (`\n`) to buffer

### Input / output
`>w< buf index` ==> writes to terminal symbol from buffer    
`OwO buf` ==> writes to buffer symbols from user input  


### Dynamic memory operations

> Dynamic memory in UwUlang is Brainfuck-like infinite array of integers.  
Like in Brainfuck, operations with dynamic memory is made with help of pointer. At start of program, pointer position set to 0

`UwU move value` ==> moves pointer to right on given distance (can be <0)   

`UwU wwite var` ==> writes value from variable to memory cell  
`UwU wead var` ==> reads value from memory cell to variable  


