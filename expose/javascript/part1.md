# Part 1:

### Question 1
*values added: 20* is printed because since the third parameter of the call to the sumValues function is true, the first code block will execute. This means that the variable result is initially set to 0, then it is set to equal 10 + 10 which is 20, and then the console logs the print statement along with whatever result equals. 

### Question 2
*final result: 20* is printed since result is defined using 'var' which means result is not block-scoped and can be accessed outside of the if-statement on line 13.

### Question 3
*values added: 20* is printed because since the third parameter of the call to the sumValues function is true, the first code block will execute. This means that 'result' is initially set to 0, then it is set to 10 + 10 which is 20, and then the console logs the print statement along with whatever 'result' equals. 

### Question 4
Line 13 would return an error. This is because 'result' is declared in the if-block using 'let', this means that 'result' is only declared and defined in the if-block and cannot be accessed outside of it.

### Question 5
The code would return an error on line 9. This is because since the if-block executes (seeing that the call to the sumValues function has its third parameter set to true), 'const result' is used to set 'result' to equal 0, however, in the next line result is attempted to be reassigned to 'num1 + num2' which isn't possible since constants are an unchanging variable.  

### Question 6
Line 13 would return an error. This is because result is declared using 'const" which makes it block-scoped. Since result is defined in the if-statement, it will not be accessible outside of the if-block and on line 13.
